transition定义:

transition用于在一定的时间内平滑的过度，这种效果可以在鼠标单击，获取焦点，被点击或对元素任何改变中触发，并圆滑的以动画效果改变CSS属性的属性值。

从定义可以知道transition是一个用于动画过度的属性，然而transiton属性只不过是一个简写属性，用于设置四个过度属性，这四个过度属性分别是: 

transition-property (执行变换的属性 )

transition-duration (变换延续时间)

transition-timing-function  (延续时间内，变换速率的变化)

transition-delay  (变换延迟时间)

下面来分别介绍一下各个属性

transition-property 即用来指定当元素其中一个属性改变是执行transition效果

值:none(没有属性改变)，all(所有属性都改变)或指定某一元素(比如color，background等属性)。

transition-duration 是动画执行的时间，单位(s)比如"0.1s"也可以写成".1s"，它可以作用于任何元素，包括before和after伪元素。

transition-timing-function 动画的执行方式

值:ease(逐渐慢下来)，linear(匀速)，ease-in(由慢到快)，ease-out(由快到慢)，ease-in-out(先慢到快再到慢)，cubic-bezier(该值允许你去自定义一个时间曲线)。

transition-delay 动画延时时间基本用法与duration相同。

2
语法:


transition: <transition> [, <transition>]*

<transition> = <transition-property> <transition-duration> <transition-timing-function> <transition-delay>
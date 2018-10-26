### 过度模块
    
##### 1、过度三要素

* 必须要有属性发生变化
* 必须告知系统哪个属性需要执行过渡效果
* 必须告知系统过渡效果持续时长

##### 2、格式

* 分开写

```css
div {
    transition-property: background-color, width;
    transition-duration: 5s;
}
div:hover{
    background-color: green;
    width: 300px;
}
```

* 连写

```css
transition: 过度属性 过度时长 运动速度 延迟时间;
```

##### 3、注意点

* 当多个属性需要同时执行过渡效果时，使用逗号隔开即可。
* 连写时，可以省略后面的两个参数，因为只要编写了前面的两个参数就已经满足了过度的三要素
* 如果多个属性运动的速度/延时的时间/持续时间都一样，可以简写为 transition: all 0s;

     



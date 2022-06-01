## transformMenu
> 要点: 巧妙的利用了 before 和 after 这两个伪元素，左边的是 ```::before元素 ```<br/>
> ```transform-origin: right;  transform: skewY(45deg);```
> 上面的盖子是·```transform-origin: bottom; transform: skewX(45deg);```
![如图所示](https://s3.bmp.ovh/imgs/2022/06/01/1a405a834bec2fd5.png)

***
## login.html
> 要点 主要是利用了   ```mouseenter``` 和 ```mouseleave```<br/>
> 在 ```mouseenter``` 时创建一个``` span``` 元素 ,并且绝对定位<br/>
> ```top``` 为 ```e.clientX - e.target.offsetLeft``` left 同理<br/>
> 对这个 ```span``` 元素的处理形成 动画
![如图所示](https://s3.bmp.ovh/imgs/2022/06/01/a79c09f24f66f189.png)


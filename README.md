# swiper_carrousel
swiper旋转木马 加载图片，轮播图片

demo1地址： https://antonysufer.github.io/swiper_carrousel/ （浏览器开启手机模式）
demo2地址:http://sgzdz.qcplay.com/wap.php/Guide/2



![](https://github.com/AntonySufer/swiper_carrousel/blob/master/ewm.png)  


示例代码  旋转木马

```js
// 轮播  
    var swiper = new Swiper('.swiper-container', {  
        loop : false,  //是否循环
        effect: 'coverflow',  //3D模式
        direction : 'vertical',  //垂直
        initialSlide :6, //初始页
        grabCursor: true,  //鼠标手
        //  freeMode : false,
         // freeModeSticky : true,
         //freeModeMomentumRatio:1,
        //  freeModeMomentumVelocityRatio:1,
        centeredSlides: true,   //居中
        slidesPerView: 'auto',   //显示个数 ，自动
        coverflow: {  
             rotate: 0,// 旋转的角度  
            stretch: 250,// 拉伸   图片间左右的间距和密集度  
            depth:250,// 深度   切换图片间上下的间距和密集度  
            modifier:2,// 修正值 该值越大前面的效果越明显  
            slideShadows : false// 页面阴影效果  
        }
      
    });  

```js

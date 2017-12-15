# my-resume

This is my H5 resume

项目介绍：该个人简历主要依赖于Swiper，通过rem实现响应式布局，使用HTML5和CSS3进行页面的搭建。

#####主要依赖于swiper实现页面的搭建

```
<div class="swiper-container">
 <div  class="swiper-wrapper">
   <div class="swiper-slide>要轮播的内容</div>
   <div class="swiper-slide>要轮播的内容</div>
   <div class="swiper-slide>要轮播的内容</div>
   <div class="swiper-slide>要轮播的内容</div>
 </div>
</div

````
#####背景音乐使用H5标签audio
````
<audio src="需要的音频路径"></audio>
````
H5新增加的标签，用来引入音频
属性：
> autoplay：默认值为false，当指定为true 的时候，页面打开的时候就会自动播放，不会等资源。

> controls：是否显示自带的播放设置

> preload：设置加载方式
> 对应的值：
```
- none：开始加载页面的时候不加载，只有需要播放的时候才加载
- metaData:开始只加载歌曲的头部信息（时长专辑等）
- auto：开始加载页面的时候就加载全部信息
```



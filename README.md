# react-native-3party-image-intro
A short doc to introduce some react native third party image related components

- [react-native-img-cache](https://github.com/wcandillon/react-native-img-cache)  
> 图片缓存组件  
464 Star  
已经不再维护，作者转而维护react-native-expo-image-cache了  
注：CachedImage基于原生Image组件，实现图片缓存；  
CustomCachedImage基于react-native-image-progress，可现实图片加载进度；  
ImageCache可对缓存过程进行控制，如清缓存、取消下载、监听下载等


- [react-native-expo-image-cache](https://github.com/wcandillon/react-native-expo-image-cache)
> 用法与react-native-img-cache相似，组件名改为Image和CacheManager，接口有变化  
78 Star  
使用 [React Native Elements](https://react-native.shop/#elements) 和 [React Native Fiber](https://react-native.shop/#fiber) 建立  

- [react-native-image-progress](https://github.com/oblador/react-native-image-progress)
> 最近有维护，但进度条已经由[react-native-progress](https://github.com/oblador/react-native-progress)来实现  
1065 Star  
新示例：  
```
import Image from 'react-native-image-progress';
import ProgressBar from 'react-native-progress/Bar';
<Image 
  source={{ uri: 'http://loremflickr.com/640/480/dog' }} 
  indicator={ProgressBar} 
  style={{
    width: 320, 
    height: 240, 
  }}/>
```

- [react-native-fit-image](https://github.com/huiseoul/react-native-fit-image)
> 使图片在空白处显示，可以不指定图片的尺寸  
322 Star  
最近有维护，不频繁  

- [react-native-cached-image](https://github.com/kfiroo/react-native-cached-image)
> 类似react-native-img-cache  
327 Star  
有维护，不频繁，用法稍复杂，效果没对比过  
有三个组件：
```
const {
    CachedImage,            // react-native component that is a drop-in replacement for your react-native `Image` components
    ImageCacheProvider,     // a top level component that provides accsess to the underlying `ImageCacheManager` and preloads images
    ImageCacheManager,      // the logic behind cache machanism - ttl, fs, url resolving etc. 
} = require('react-native-cached-image');
```

- [react-native-masonry](https://github.com/brh55/react-native-masonry)
> 瀑布流图片显示组件，支持定制列数，支持设备旋转、点击处理、自定义Header、列表优化、使用第三方图片组件等特性  
580 Star  
维护及时  

- [react-native-image-resizer](https://github.com/bamlab/react-native-image-resizer)
> 图片裁剪库，支持JPEG、PNG，安卓支持WEBP  
500 Star  
有维护，不频繁  

- [react-native-webp](https://github.com/dbasedow/react-native-webp)
> 通过添加自定义的RCTImageDataDecoder支持webp格式，简单好用
50 Star  
基本不维护，被fork到了 [react-native-webp-support](https://github.com/TGPSKI/react-native-webp-support)，但是只多了相关文档，似乎没功能升级  

- [react-native-image-crop-picker](https://github.com/ivpusic/react-native-image-crop-picker)
> 相册或相机中读取图片，可支持裁剪或不裁剪，支持base64；  
缺点是只支持指定尺寸裁剪，无法根据读取到的图片尺寸定制裁剪尺寸  
1891 Star  
维护及时

- [react-native-fast-image](https://github.com/DylanVann/react-native-fast-image)
> iOS基于SDWebImage，android基于Glide，解决原生Image闪烁、cache miss、低效等问题
1088 Star  
维护及时  

- [react-native-image-viewer](https://github.com/ascoders/react-native-image-viewer)
> 支持全屏查看一个图片数组，可以左右滑切换图片，双指缩放图片  
603 Star  
其中缩放部分依赖 [react-native-image-zoom](https://github.com/ascoders/react-native-image-zoom)  
维护及时

- [react-native-image-zoom](https://github.com/ascoders/react-native-image-zoom)
> 图片手势支持，拖动、缩放等  
157 Star  
维护及时

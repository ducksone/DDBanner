# DDBanner
iOS Banner 图片视频 支持本地和网络
因项目需要 有个banner上有图片和视频 
公司项目是外包做的，目前只测试了下 没拿到代码 
今年的新手机iPhon13 iOS15 我在详情页有一个视频的banner哪里 滚动的时候 居然卡的pibao
就自己毛了一个 
FSPagerView 真挺好用的 效果还多
详细使用见demo
注意点：
1、因为是使用的FSPagerView（swift写的） 所以有引用-swift文件 
  DDBlendBannerView.m文件中引用需要有更改
  #import "blendBanner-Swift.h"/*替换成项目名-Swift*/
  
2、DDVideoModel.m中有两个todo 可以自己调整
  // TODO: 替换自己的默认滚动时间
  // TODO: 视频时间过长 置为最大播放时间

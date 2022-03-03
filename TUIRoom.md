多人音视频房间

## 概述

TUIRoom是一个开源组件, 适用于多人音视频交流的场景。开发者可以进行二次开发，或是替换UI，自定义布局以快速上线业务。
房间内的角色及描述

<table>
<tr>
<th>角色</th><th>描述</th><th>具体权限</th>
</tr>
<tr>
<td>主持人</td>

<td>房间创建者</td>

<td> -踢出成员<br/>-控制单体/全体成员的麦克风、摄像头开关   <br/>-指定自由发言或是举手发言</td>
</tr>
<td> 成员</td>
<td> 进入房间的参与者</td>
<td> -控制自己的摄像头、麦克风开关<br/>-自定义画面布局</td>

</tr>
</table>


多人音视频房间组件提供以下核心功能：

- 多人音视频通话：两人或多人超低延时音视频通话，支持1080P高清画质

- 自定义布局：主持人和成员都可以自定义画面布局

- 屏幕共享：主持人和成员均可共享指定画面区域，单个用户可以同时分享摄像头和屏幕两路画面，保证音画同步。

- 质量检测：可以统计CPU、内存占用情况；检测网络延迟、带宽和丢包率，以及音频码率、视频和屏幕共享帧率

- AI降噪：智能检测和去除混合在传播信号中的噪声干扰，提升声音的清晰度，改善用户听感。
[内测申请](https://cloud.tencent.com/apply/p/9q0qt0bg5l4)


目前已支持移动端、PC端，以下是组件的功能示意图。有任何问题或建议，可以加入我们的QQ交流群：592465424。
<img src="https://imgcache.qq.com/operation/dianshi/other/TUIRoom.354deff3e238839ef51bb02527ef81bfb808a9d0.png">

## 适用场景

TUIRoom组件支持自定义布局，适用于多个场景：

- 在线教学：在线教育、在线健身教学、在线自习室、远程医疗教学
- 企业服务：视频会议、远程招聘、视频客服、在线庭审
- 医疗健康：远程问诊、远程会诊
- 金融服务：远程面签、远程定损、保险理赔、在线理财



<table>
<tr>
<th>视频客服</th><th>在线庭审</th><th>远程招聘</th><th >远程会诊</th>
</tr>
<tr>
<td><img style="width:200px;" src="https://qcloudimg.tencent-cloud.cn/trisys/assets/product/images/ptovUFkmDhN1OWP7rGgB3.png" data-nonescope="true"></td>

<td><img style="width:100px;" src="https://mmbiz.qpic.cn/mmbiz_jpg/APDZeM2BxAFAK3wzQ1XB5UpuqGVW2rxrteTT1C0ljLNdtsSols3GkLb36usVL6vTiaDyQSCvMzeCuHsz1xic0F4Q/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1" data-nonescope="true"></td>

<td><img style="width:300px;" src="https://imgcache.qq.com/operation/dianshi/other/zhaopin.9058bc65b94ea06b5d9b3926df836de5243c3988.png" data-nonescope="true"></td>

<td><img style="width:300px;" src="https://qcloudimg.tencent-cloud.cn/trisys/assets/product/images/i5ka6HgVVYvT2okzrWQXK.png" data-nonescope="true"></td>

</tr>
</table>


<table>
<tr>
<th>保险理赔</th><th>在线教育</th><th>视频会议</th><th >远程面签</th>
</tr>
<tr>
<td><img style="width:300px;" src="https://qcloudimg.tencent-cloud.cn/trisys/assets/product/images/sKlUCwL-mkjPHwZWuqgBo.png" data-nonescope="true"></td>

<td><img style="width:300px;" src="https://imgcache.qq.com/operation/dianshi/other/jiaoyu.c0baa1356cfe9397d7aad9647b5196d8fc57e937.png" data-nonescope="true"></td>

<td><img style="width:300px;" src="https://qcloudimg.tencent-cloud.cn/trisys/assets/product/images/5VTqOsLgja9Sv0GwBTNEr.png" data-nonescope="true"></td>

<td><img style="width:300px;" src="https://qcloudimg.tencent-cloud.cn/trisys/assets/product/images/XuKHWOfts8mS5D_0XcFD5.png" data-nonescope="true"></td>

</tr>
</table>


## 效果演示

<table>
<tr>
<th>iOS & Android</th><th>Windows & Mac</th>
</tr>
<tr>
<td><img style="width:300px;" src="https://imgcache.qq.com/operation/dianshi/other/TUIRoom_android.eb0d2a78455d5a9e86ca1c0505f35259728bf232.png" data-nonescope="true"></td>


<td><img style="width:800px;" src="https://imgcache.qq.com/operation/dianshi/other/tuiroomwindows.704c48031da2fd6e00837ae8e7475e7120c94743.png" data-nonescope="true"></td>

</tr>
</table>


## 体验并跑通

可以直接扫描下方二维码点击体验，或者点击跳转[ios](https://cloud.tencent.com/document/product/647/45681)、[android](https://cloud.tencent.com/document/product/647/45667)、[win或mac](https://cloud.tencent.com/document/product/647/63494)的体验链接。点击[TUIRoom](https://github.com/tencentyun/TUIRoom)可查看Github源码。
<table>
<tr>
<th>iOS</th><th>Android</th>
</tr>
<tr>
<td><img style="width:150px;" src="https://main.qcloudimg.com/raw/a1a6fd4a9bc3ad2b5fe60e31202c8fda.png" data-nonescope="true"></td>

<td><img style="width:150px;" src="https://imgcache.qq.com/operation/dianshi/other/crcode_android.fa3232dcf5c64a5184c5e9e0357674c6b3b601ac.png" data-nonescope="true"></td>




</button></a></td>
</tr>
</table>

## 交流 & 反馈

欢迎加入QQ群进行技术交流和反馈问题，QQ群：592465424

<img src="https://camo.githubusercontent.com/9548733e5a0a8f874b595b3240ad3ffc8902871c074ad6e1037093391829ce87/68747470733a2f2f6d61696e2e71636c6f7564696d672e636f6d2f7261772f31656133616231666633366433376338383966343134303439393538356134612e706e67">

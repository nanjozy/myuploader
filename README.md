# myuploader
      一个前端直传七牛云的插件
### 需要
1. layui
2. jquery
### 使用
##### html:
```html
<button class="uper-btn">上传图片</button>
<button class="uper-cancel">取消</button>
<span class="uper-progress"></span>
<div style="width:100px;height:100px;border-radius: 5px;margin:10px 0;border:1px solid #009688;padding:10px;overflow: hidden;">
<img src="oldimgurl" class="uper-image">
</div>
```
#### js:
```javascript
var uploader = new Uploader();
uploader.bind();
```
#### config:
      在config 的url中填入七牛云获取token的后台接口地址

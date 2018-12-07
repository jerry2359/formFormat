## 表单验证
一款轻量级表单验证库；
不依赖任何框架和库。

### 例子
```html```
<input type="text">
<input type="button" value="提交">
<input type="checkbox">
```html```

```js```
// 可以打开html中的demo.html，将以下注释打开运行即可查看效果。
var inputs = document.getElementsByTagName('input');
inputs[1].onclick = function() {
    //验证是否为空
    //console.log( formFormat.isEmpty(inputs[0].value) );

    //字符长度限制2-5 （按字符串个数来计算）
    //console.log( formFormat.limitString(inputs[0].value, [2,5]) );

    //字符长度限制2-5 （按字符串字节来计算：英文占1字节，汉字占2字节）
    //console.log( formFormat.limitStr(inputs[0].value, [2,5], true, true) );

    //验证手机号码
    //console.log( formFormat.isMobile(inputs[0].value) );

    //验证固定电话
    //console.log( formFormat.isTelephone(inputs[0].value) );

    //验证电话号码（包括手机+固定电话）
    //console.log( formFormat.isPhone(inputs[0].value) );

    //验证邮箱
    //console.log( formFormat.isEmail(inputs[0].value) );

    //验证邮政编码
    //console.log( formFormat.isZipcode(inputs[0].value) );

    //验证身份证号码
    //console.log( formFormat.isIdcode(inputs[0].value) );

    //验证纯数字
    //console.log( formFormat.isNumber(inputs[0].value) );

    //限制数字大小范围
    //console.log( formFormat.limitNumder(inputs[0].value, [50,100]) );

    //验证纯英文
    //console.log( formFormat.isEng(inputs[0].value) );

    //验证含有英文
    //console.log( formFormat.hasEng(inputs[0].value) );

    //验证纯中文
    //console.log( formFormat.isCn(inputs[0].value) );

    //验证含有中文
    //console.log( formFormat.hasCn(inputs[0].value) );

    //验证字母、数字
    //console.log( formFormat.isEngNum(inputs[0].value) );

    //验证字母、数字和下划线
    //console.log( formFormat.isw(inputs[0].value) );

    //单个单选框或复选框是否选中
    //console.log( formFormat.isChecked(inputs[2]) );

    //验证网址
    //console.log( formFormat.isUrl(inputs[0].value) );
};
```js```
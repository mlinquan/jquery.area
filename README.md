# jquery.area

Chinese provinces and cities triple action plugin(jQuery).

数据来源：<a href="http://www.mca.gov.cn/article/sj/xzqh/2018/201804-12/20180810101641.html" target="_blank">2018年8月中华人民共和国县以上行政区划代码 （最新县及县以上行政区划代码）</a>

## Demo
http://linquan.me/jquery.area/demo/

## Usage
### html
```html
<select name="province" class="province"></select>
<select name="city" class="city"></select>
<select name="district" class="district"></select>
<input type="hidden" name="area_code" class="code">
<input type="hidden" name="area_value" class="text">
```
### js
```js
(function($) {
    $(function() {
        var defalutOptions = {
            cityClass: '.city',
            districtClass: '.district',
            inputCode: '.code',
            inputText: '.text'
        };
        $('.province').area(defalutOptions);
    });
})(jQuery);
```

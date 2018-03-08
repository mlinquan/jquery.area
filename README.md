# jquery.area

Chinese provinces and cities triple action plugin(jQuery).

数据来源：<a href="http://www.mca.gov.cn/article/sj/tjbz/a/2017/201801/201801151447.html" target="_blank">2017年11月中华人民共和国县以上行政区划代码（最新县及县以上行政区划代码）</a>

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

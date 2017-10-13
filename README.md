# jquery.area

Chinese provinces and cities triple action plugin(jQuery).

数据来源：<a href="http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201703/t20170310_1471429.html" target="_blank">最新县及县以上行政区划代码（截止2016年7月31日）</a>

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

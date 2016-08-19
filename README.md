# jquery.area

数据来源：<a href="http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/201608/t20160809_1386477.html" target="_blank">最新县及县以上行政区划代码（截止2015年9月30日）</a>

## Usage
### hmtml
```
<select name="province" class="province"></select>
<select name="city" class="city"></select>
<select name="district" class="district"></select>
<input type="hidden" name="area_code" class="code">
<input type="hidden" name="area_value" class="text">
```
### js
```
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

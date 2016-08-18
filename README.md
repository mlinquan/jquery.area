# jquery.area

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
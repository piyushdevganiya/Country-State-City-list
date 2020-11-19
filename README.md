# Country-State-City-list
Create Country state city dropdown list dynamically using jquery 


**Usage**
**You must include [jQuery](https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js) CDN and [countrylist.js](http://github.com/piyushdevganiya/Country-State-City-list/blob/master/countrylist.js)**
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="countrylist.js"></script>
```

## Without Selected Data
>
**HTML Code:**
```
<select id="example1-country"></select>
<select id="example1-state"></select>
<select id="example1-city"></select>
```

**Javascript Code:**
```
$(this).CountryList("example1-country","example1-state","example1-city");
```

## With Selected Data
>
**HTML Code:**
```
<select id="example2-country" data-selected="India"></select>
<select id="example2-state" data-selected="Gujarat"></select>
<select id="example2-city" data-selected="Surat"></select>
```

Javascript Code:
```
$(this).CountryList("example2-country","example2-state","example2-city");
```

# Country-State-City-list
Create Country state city dropdown list dynamically using jquery 


Usage

Without Selected Data

HTML Code:

<select id="example1-country"></select>
<select id="example1-state"></select>
<select id="example1-city"></select>

Javascript Code:
$(this).CountryList("example1-country","example1-state","example1-city");

With Selected Data

HTML Code:

<select id="example2-country" data-selected="India"></select>
<select id="example2-state" data-selected="Gujarat"></select>
<select id="example2-city" data-selected="Surat"></select>

Javascript Code:
$(this).CountryList("example2-country","example2-state","example2-city");

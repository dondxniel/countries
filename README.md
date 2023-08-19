# Countries Data

## Introduction

This json file contains a detailed list of all countries and their information. It's an extension of [restcountries.com]('https://restcountries.com') but it comes with the `phoneCode` property.

## Interface

Each element in the array of countries contain the following properties in its object:

1. `name`: This has:

-   `common` for the commonly known name of a country. eg "South Africa".
-   `official` for the official name of a country. eg "Republic of South Africa"
-   `nativeName` which is an object of different languages in the country and their translation of the name. eg `"afr": { "official": "Republiek van Suid-Afrika", "common": "South Africa" }, "eng": { "official": "Republic of South Africa", "common": "South Africa" },...`
-   `tld` which is the local top level domains of said country. eg `[".za"]`
-   `cca2` which is the 2 letter acronym for the country's name. eg `ZA`
-   `cca3` which is the 3 letter acronym for the country's name. eg `ZAF`
-   `independent` which is a boolean value whether or not the country is independent.
-   `unMember` which is a boolean value of whether or not they are a UN member
-   `currencies` which is an object of the different currencies and more info on them. eg `"ZAR": { "name": "South African rand", "symbol": "R" }`
-   `phoneCode` which is their phone code without the +. eg "27"
-   `idd` which is their phone code broken into root and suffixes. eg `"root": "+2", "suffixes": [ "7" ]`
-   `capital` which is their capital in an array. eg `[ "Pretoria", "Bloemfontein", "Cape Town" ]`
-   `altSpellings` which are alternative spellings in array. eg `[ "ZA", "RSA", "Suid-Afrika", "Republic of South Africa" ]`
-   `continent` which is the continent. eg `"Africa"`
-   `region` which is the region. eg `"Africa"`
-   `subregion` which is the region of the region it's in. eg `"Southern Africa"`
-   `languages` which is an object of the languages spoken. eg `{ "afr": "Afrikaans", "eng": "English", "nbl": "Southern Ndebele", "nso": "Northern Sotho", "sot": "Southern Sotho", "ssw": "Swazi", "tsn": "Tswana", "tso": "Tsonga", "ven": "Venda", "xho": "Xhosa", "zul": "Zulu" }`
-   `latlng` which is an array of their latitude and longitude. eg `[ -29, 24 ]`
-   `borders` which is a list of countries they share a border with. eg `[ "BWA", "LSO", "MOZ", "NAM", "SWZ", "ZWE" ]`
-   `area` which is their surface area in kilometer square. eg `1221037`
-   `flag` which is their flag emoji
-   `maps` which is a link to their maps in an object. eg ` { "googleMaps": "https://goo.gl/maps/CLCZ1R8Uz1KpYhRv6",  "openStreetMaps": "https://www.openstreetmap.org/relation/87565" }`
-   `population` which is their population. eg: `59308690`
-   `timezones` which is their timezone. eg: `UTC+02:00`
-   `flags` which is an object with their flags in different formats, even an alt text. eg: `{ "png": "https://flagcdn.com/w320/za.png", "svg": "https://flagcdn.com/za.svg", "alt": "The flag of South Africa is composed of two equal horizontal bands of red and blue, with a yellow-edged black isosceles triangle superimposed on the hoist side of the field. This triangle has its base centered on the hoist end, spans about two-fifth the width and two-third the height of the field, and is enclosed on its sides by the arms of a white-edged green horizontally oriented Y-shaped band which extends along the boundary of the red and blue bands to the fly end of the field." }`
-   `coatOfArms` which is their coat of arms in different formats. eg `{ "png": "https://mainfacts.com/media/images/coats_of_arms/za.png", "svg": "https://mainfacts.com/media/images/coats_of_arms/za.svg" }`

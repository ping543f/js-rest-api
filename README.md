# ajax-html-css-API-implementation-for-covidhospitalsbd.com
### This is a very simple informative view of covidhospitalsbd.com rest api. It is implemented using html, css and js. If you want to show the basic availability of the beds you can just integrate this one to your website. no backend procesing required. Just copa and paste or use this code.


## API Reference

If you want to use our REST API, it is free to use. API documentation is given below:

API URL

https://api.covidhospitalsbd.com/api

Available beds - GET

/available

Available hospitals - GET

/available-hospitals

Parameters:
type value: icu_hfc, icu, hdu, gb
districts value: Comma separated names of districts in english

Example
/available-hospitals?type=icu&districts=Dhaka,Gazipur

Single hospital - GET

/hospital/HOSPITAL_ID

Search - GET

/search

Parameter:
query value: district or hospital name in english

Example
/search?query=Dhaka
  
## Acknowledgements

 - [covidhospitalsbd.com team](https://covidhospitalsbd.com/api)
 
## Authors

- [@ping543f](https://www.github.com/ping543f)

  
## Demo

- blank view:
https://ibb.co/ZN6NVwg

- sample implementation view:
https://ibb.co/n6mqxxj


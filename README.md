# Turkey-Geo-Neighborhood-Database
Cities, districts and neighborhoods of the Turkey with geolocation data. MongoDB.

# Overview
I needed geolocation database of neighborhood in Turkey during one of my work. Therefor, this repository was born. It took ~7 hours from my life and it is all yours now.

# Dictionary
City: Şehir,il

District: İlçe

Neighborhood: Mahalle

# Importing data
```shell
mongoimport --db <your_db> --collection cities --file cities.json
mongoimport --db <your_db> --collection districts --file districts.json
mongoimport --db <your_db> --collection neighborhoods --file neighborhoods.json
```

# Up-to-date
Datum in repository was created in middle of 2017. In case of requirement of up-to-date data, you have to use [PTT zipcode database](http://postakodu.ptt.gov.tr) which is in xlsx format and fetch geolocation from 3rd party web services. 



# Disclaimer
I have no responsibility about correctness of data.

# Contributing
Feel free to make a pull request for improve the data or fixing wrong documents.

Public Media USA sheet:<br>
https://docs.google.com/spreadsheets/d/1PwsHoKVTtmnwQriaUgj0soLoRs0PLv52fIFmoBcHHTs/

Public-media Press Associations:
* CPB (Corporation for Public Broadcasting) public radio and TV: https://cpb.org/stations
* NFCB (National Federation of Community Broadcasters) public radio: https://nfcb.org/

NFCB member data (combines map JS var and page HTML)<br>
CSS selector: ``div#fws_690c8c94e198a div.wpb_content_element``<br>
Data:
* Call letters
* URL
* City
* State

NFCB Map JS<br>
Map-only link: https://www.google.com/maps/d/viewer?mid=19ojMe1b-U28DaXdKVFYHzC2rHm-gnY8<br>
JS var: ``var _pageData``<br>
JS var example:<br>
``[[\"Call Letters\",[\"KABR\"],1],null,null,[[\"License Holder\",[\"Alamo Navajo School Board\"],1],[\"City\",[\"Alamo\"],1],[\"Zip Code\",[\"87825\"],1]]],null,0],[\"50815A5B7E000002\",[[[39.075058999999996,-108.5522531]]]``<br>
Data:
* Call letters
* License Holder
* City
* Zip
* Longitude
* Latitude
* 
Notes: 
* Match "Call letters” to combine the 2 above data sources. Some manual conformation needed (e.g., "KCUW-LP" in map, "KCUW" on page).
* Domain extracted by manual search/replace.
* WikiSignals: Don't import stations orgs without their own domains. 

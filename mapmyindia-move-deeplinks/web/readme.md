[<img src="https://www.mapmyindia.com/api/img/mapmyindia-api.png" height="40"/> </p>](https://www.mapmyindia.com/api)


# Embeddable Deep Links for MapmyIndia Move

## 1. Nearby Facilities
<br>


### Introduction
Get access to your nearby amenities with MapmyIndia’s nearby utility.
<br><br>


### URL
```groovy
https://maps.mapmyindia.com/{search-keywords}/near/xx.xxxxx,yy.yyyyy
```
<br>


### URL Parameters
1. `search-keywords`: Nearby search keywords
2. `xx.xxxxx,yy.yyyyy`: Lat/Long pair
<br><br>

### Category Keywords + URL
<br>

| Category Keywords | Sample URLs |
| --- | --- |
| Corona isolation | https://maps.mapmyindia.com/corona%20isolation/near/28.5454,77.45445 |
| Corona testing | https://maps.mapmyindia.com/corona%20testing/near/28.5454,77.45445 |
| Corona sample | https://maps.mapmyindia.com/corona%20sample/near/28.5454,77.45445 |
| Veccination Centers | https://maps.mapmyindia.com/vaccination%20centers/near/28.5454,77.45445 |
| Corona Treatment | https://maps.mapmyindia.com/corona%20treatment/near/28.5454,77.45445 |
| Coffee | https://maps.mapmyindia.com/coffee/near/28.5454,77.45445 |
| Restaurants | https://maps.mapmyindia.com/restaurants/near/28.5454,77.45445 |
| Pubs & bars | https://maps.mapmyindia.com/pubs%20%26%20bars/near/28.5454,77.45445 |
| Atms | https://maps.mapmyindia.com/atms/near/28.5454,77.45445 |
| Pharmacy | https://maps.mapmyindia.com/pharmacy/near/28.5454,77.45445 |
| Parking | https://maps.mapmyindia.com/parking/near/28.5454,77.45445 |
| Ev charging | https://maps.mapmyindia.com/ev%20charging/near/28.5454,77.45445 |
| Charging stations | https://maps.mapmyindia.com/charging%20stations/near/28.5454,77.45445 |
| Petrol pump | https://maps.mapmyindia.com/petrol%20pump/near/28.5454,77.45445 |
| Transports | https://maps.mapmyindia.com/transports/near/28.5454,77.45445 |
| Entertainment | https://maps.mapmyindia.com/entertainment/near/28.5454,77.45445 |
| Hotels | https://maps.mapmyindia.com/hotels/near/28.5454,77.45445 |
| Shopping | https://maps.mapmyindia.com/shopping/near/28.5454,77.45445 |
| Groceries | https://maps.mapmyindia.com/groceries/near/28.5454,77.45445 |
| Hospitals | https://maps.mapmyindia.com/hospitals/near/28.5454,77.45445 |
| Police stations | https://maps.mapmyindia.com/police%20stations/near/28.5454,77.45445 |
| Post office | https://maps.mapmyindia.com/post%20office/near/28.5454,77.45445 |
| Banks | https://maps.mapmyindia.com/banks/near/28.5454,77.45445 |
| Spas | https://maps.mapmyindia.com/spas/near/28.5454,77.45445 |
| Toilets | https://maps.mapmyindia.com/toilets/near/28.5454,77.45445 |
| CNG station | https://maps.mapmyindia.com/cng%20station/near/28.5454,77.45445 |
| Monuments | https://maps.mapmyindia.com/monuments/near/28.5454,77.45445 |
| College | https://maps.mapmyindia.com/college/near/28.5454,77.45445 |
| School | https://maps.mapmyindia.com/school/near/28.5454,77.45445 |
| Hunger relief centre | https://maps.mapmyindia.com/hunger%20relief%20centre/near/28.5454,77.45445 |
| Clinic | https://maps.mapmyindia.com/clinic/near/28.5454,77.45445 |
| Food | https://maps.mapmyindia.com/food/near/28.5454,77.45445 |
| Grocery | https://maps.mapmyindia.com/grocery/near/28.5454,77.45445 |
| Medical equipment | https://maps.mapmyindia.com/medical%20equipment/near/28.5454,77.45445 |

<br><br>

## 2. Get Directions
<br>


### Introduction
Obtain directions between two locations or find directions among a set of places using MapmyIndia’s direction widget.
<br><br>

### URL
```groovy
https://maps.mapmyindia.com/direction?places=xx.xxxxx,yy.yyyyy;{elocid}
```
<br>

### Base URL
```
https://maps.mapmyindia.com/direction?
```


### URL Parameters
Below are the possible combinations of URL parameters

1. `xx.xxxxx,yy.yyyyy;elocid`: Distance between a Lat/Long pair and a Place id (eloc).
2. `elocid;xx.xxxxx,yy.yyyyy`: Distance between a Place id (eloc) and a Lat/Long pair.
3. `xx.xxxxx,yy.yyyyy;xx.xxxxx,yy.yyyyy`: Distance between two Lat/Long pairs.
4. `xx.xxxxx,yy.yyyyy;xx.xxxxx,yy.yyyyy`: Distance between two eloc Ids.
5. `xx.xxxxx,yy.yyyyy,ABC place name;xx.xxxxx,yy.yyyyy,XYZ place name`: Distance between two Lat/Long pairs with place names.
<br><br>

### Sample URL with Possible Combinations
<br>

|URL Parameters possible combinations  | Sample URLs |
| --- | --- |
| Place ID(eLoc) to Place ID(eLoc) | https://maps.mapmyindia.com/direction?places=D9VKZQ;MMI000 |
| lat/long to lat/long (with place names) | https://maps.mapmyindia.com/direction?places=28.550716,77.268928,MapmyIndia%20Head%20Office%20New%20Delhi%3B28.613058%2C77.227738%2CIndia%20Gate |
| lat/long to lat/long | https://maps.mapmyindia.com/direction?places=28.5503,77.2502;28.5507,77.2689 |
| lat/long to eLoc | https://maps.mapmyindia.com/direction?places=28.65656,77.989898;mmi000 |
| eLoc to lat/long | https://maps.mapmyindia.com/direction?places=mmi000;28.5400,77.2592 |
<br><br>

Note: Users can append more eLocs or Lat/Long to the url to add as via points and find directions



## 3. Report
<br>

### Introduction
Report issues across different categories related to traffic issues, safety issues, community issues, and others using the MapmyIndia Move platform.
<br><br>

### URL
```groovy
https://maps.mapmyindia.com/report
```

Note: Currently, this feature requires the user to login.
<br><br>

### Steps to Report

Report by clicking the Plus button on right bottom of the screen.
Please refer the below image.

![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/report1.png)


Select category and sub-category of the issue being reported.

![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/report2.gif)
<br><br>
![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/report3.gif)
<br><br>
After selecting the subcategory of report , add the location of the issue. Users can add current location or change the location by dragging and dropping the given marker.

Users can add some attachments and comments if needed to lay out a detailed summary and click on done to successfully submit my report.
Pleaese refer the below illustration.

![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/report4.gif)
<br><br>

### Sample sharable URL
After the report submission the user can share the same with other users.

```
https://maps.mapmyindia.com/report/1T182A/abfc3b7b-89ad-475a-978a-bcb763a76298
```
<br><br>
## 3. Get eLoc
<br>

### Introduction
Transform any complex address into a shareable 6 character code using MapmyIndia’s Get eLoc. With this users can create an eLoc for any address or get eLoc of the same.
<br><br>

Note : Currently, this feature requires the user to login.

### URL
```groovy
https://maps.mapmyindia.com/get-eLoc
```

### Steps to Get eLoc

1. Search for an address/place
2. You may also move the map to select the exact location
3. Click on the current location marker to select from the map if require current location
4. Then click on show eLoc

Pleaese refer the below illustration.

![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/geteloc1.gif)
<br><br>

### Sample sharable URL
After the eLoc has been created/fetched for the place. You can share the same with the community or other MapmyIndia users.

```
https://maps.mapmyindia.com/eloc/X5OCK9
```
<br><br>

## 4. Share Place (eLoc)
<br>

### Introduction
eLoc is a 6 character digital address by MapmyIndia which simplifies complex addresses.
For e.g - 
eLoc for the address “Indigo Plast India Pvt Ltd” is 3BL91M
With this users can share any place as a 6 digit character code to the community or other users.

Please refer the below illustration.

![](https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/shareeloc1.gif)
<br><br>

### Sample sharable URL
You can share any place as a 6 digit character code with the community or other MapmyIndia users.

```
https://maps.mapmyindia.com/eloc/9ADJ1X 
http://eloc.me/OFL6O6
```



<br><br>
	
 For any queries and support, please contact: 

[<img src="https://www.mapmyindia.com/images/logo.png" height="40"/> </p>](https://www.mapmyindia.com/api)
Email us at [apisupport@mapmyindia.com](mailto:apisupport@mapmyindia.com)


![](https://www.mapmyindia.com/api/img/icons/support.png)
[Support](https://www.mapmyindia.com/api/index.php#f_cont)
Need support? contact us!

<br></br>


[<p align="center"> <img src="https://www.mapmyindia.com/api/img/icons/stack-overflow.png"/> ](https://stackoverflow.com/questions/tagged/mapmyindia-api)[![](https://www.mapmyindia.com/api/img/icons/blog.png)](http://www.mapmyindia.com/blog/)[![](https://www.mapmyindia.com/api/img/icons/gethub.png)](https://github.com/MapmyIndia)[<img src="https://mmi-api-team.s3.ap-south-1.amazonaws.com/API-Team/npm-logo.one-third%5B1%5D.png" height="40"/> </p>](https://www.npmjs.com/org/mapmyindia) 



[<p align="center"> <img src="https://www.mapmyindia.com/june-newsletter/icon4.png"/> ](https://www.facebook.com/MapmyIndia)[![](https://www.mapmyindia.com/june-newsletter/icon2.png)](https://twitter.com/MapmyIndia)[![](https://www.mapmyindia.com/newsletter/2017/aug/llinkedin.png)](https://www.linkedin.com/company/mapmyindia)[![](https://www.mapmyindia.com/june-newsletter/icon3.png)](https://www.youtube.com/user/MapmyIndia/)




<div align="center">@ Copyright 2020 CE Info Systems Pvt. Ltd. All Rights Reserved.</div>

<div align="center"> <a href="https://www.mapmyindia.com/api/terms-&-conditions">Terms & Conditions</a> | <a href="https://www.mapmyindia.com/about/privacy-policy">Privacy Policy</a> | <a href="https://www.mapmyindia.com/pdf/mapmyIndia-sustainability-policy-healt-labour-rules-supplir-sustainability.pdf">Supplier Sustainability Policy</a> | <a href="https://www.mapmyindia.com/pdf/Health-Safety-Management.pdf">Health & Safety Policy</a> | <a href="https://www.mapmyindia.com/pdf/Environment-Sustainability-Policy-CSR-Report.pdf">Environmental Policy & CSR Report</a>

<div align="center">Customer Care: +91-9999333223</div>
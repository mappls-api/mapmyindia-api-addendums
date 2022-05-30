[<img src="https://www.mapmyindia.com/api/img/mapmyindia-api.png" height="40"/> </p>](https://www.mapmyindia.com/api)


# Embeddable Deep Links from MapmyIndia Move

## 1. Get eLoc
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

Please refer the below illustration.
<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/geteLocandroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
After the eLoc has been created/fetched for the place. You can share the same with the community or other MapmyIndia users.

```
https://maps.mapmyindia.com/eloc/X5OCK9
```
<br><br>

## 2. Share Place (eLoc)
<br>

### Introduction
eLoc is a 6 character digital address by MapmyIndia which simplifies complex addresses.
For e.g - 
eLoc for the address “Indigo Plast India Pvt Ltd” is 3BL91M
With this users can share any place as a 6 digit character code to the community or other users.

Please refer the below illustration.
<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/ShareeLocandroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
You can share any place as a 6 digit character code with the community or other MapmyIndia users.

```
https://maps.mapmyindia.com/eloc/9ADJ1X 
http://eloc.me/OFL6O6
```

<br><br>

## 3.  COVID Dashboard
<br>

### Introduction
<br>

Useful and free-to-integrate geo-visualized COVID-19 dashboard with stats , map search guides, and reporting tools.
<br>
### URL
```groovy
https://maps.mapmyindia.com/corona
```
<br>
Please refer the below illustration.

<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/CovidGuideandroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
Users can turn on multiple layers and share the dashboard  to other users.

With default layer selected
```
https://maps.mapmyindia.com/corona
```
<br>

With 3 layers selected - Containment zones, Testing Lab, Treatment Centre
<br>

```
https://maps.mapmyindia.com/corona?containment_zone_gradient,corona_testing_centre,corona_treatment_centre
```

<br><br>

## 4.  Navigation
<br>

### Introduction
<br>

Integrate the navigation utility to your application to get turn-by-turn directions to a location.

<br>

### URL

```groovy
com.mapmyindia.move://navigation?d_lat=kk.kkkkk&d_lng=mm.mmmmm&s_lat=xx.xxxxx&s_lng=yy.yyyyy&placeName={destination-name}&{start-name}
```
<br>


### URL Parameters
1. `start-name`: Starting location name
2. `destination-name`: Destination location name
3. `xx.xxxxx,yy.yyyyy`: Lat/Long pair of starting location
4. `kk.kkkkk,mm.mmmmm`: Lat/Long pair of destination location
<br><br>

### Sample calling URL
<br>

```
com.mapmyindia.move://navigation?d_lat=28.566677&d_lng=77.234995&c_lat=28.548348&c_lng=77.251056&placeName=Mool Chand&Nehru Place 

```

<br><br>

## 5.  COVID Safety Check
<br>

### Introduction
<br>

Widget to check whether you are in or near a containment zone.Your family or friends could be near a containment zone. Share this tool and keep them updated with the nearest corona related facilities.
Also, get to know the nearest
- Corona Treatment Centre
- Sample Collection Centre
- Quarantine Centre

<br>

### URL


```
https://maps.mapmyindia.com/corona?safety_alert
```
<br>

Please refer the below illustration.

<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/SafetyCheckAndroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
<br>

```
https://maps.mapmyindia.com/corona?safety_alert
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



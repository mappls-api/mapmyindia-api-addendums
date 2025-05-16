[<img src="https://cdn.mapmyindia.com/mappls_web/logos/svg/mappls.svg" height="40"/> </p>](https://www.mapmyindia.com/api)


# Embeddable Deep Links from Mappls 

## 1. Get Mappls Pin
<br>

### Introduction
Transform any complex address into a shareable 6 character code using Get Mappls Pin. With this users can create an Mappls Pin for any address or get Mappls Pin of the same.
<br><br>

Note : Currently, this feature requires the user to login.

### URL
```groovy
https://mappls.com/get-pin
```

### Steps to Get Mappls Pin

1. Search for an address/place
2. You may also move the map to select the exact location
3. Click on the current location marker to select from the map if require current location
4. Then click on show Mappls Pin

Please refer the below illustration.
<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/geteLocandroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
After the Mappls Pin has been created/fetched for the place. You can share the same with the community or other Mappls users.

```
https://mappls.com/X5OCK9
```
<br><br>

## 2. Share Place (Mappls Pin)
<br>

### Introduction
Mappls Pin is a 6 character digital address by Mappls which simplifies complex addresses.
For e.g - 
Mappls Pin for the address “Indigo Plast India Pvt Ltd” is 3BL91M
With this users can share any place as a 6 digit character code to the community or other users.

Please refer the below illustration.
<p align=center>
<kbd><img src="https://github.com/MapmyIndia/mapmyindia-api-addendums/blob/main/docs/images/android/ShareeLocandroid.gif" width=290 height=585>
</kbd></p>
<br><br>

### Sample sharable URL
You can share any place as a 6 digit character code with the community or other Mappls users.

```
https://mappls.com/9ADJ1X 
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
https://mappls.com/corona
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
https://mappls.com/corona
```
<br>

With 3 layers selected - Containment zones, Testing Lab, Treatment Centre
<br>

```
https://mappls.com/corona?containment_zone_gradient,corona_testing_centre,corona_treatment_centre
```

<br><br>

## 4.  Navigation
<br>

### Introduction
<br>

Launch Turn-by-Turn Navigation with Mappls MapmyIndia Android app. Enable instant navigation to a location using Mappls deep links and universal links. This works seamlessly with the Mappls app on Android

<br>

### Mappls URI Schema for Navigation
Use the following deep link URI to launch turn-by-turn navigation directly in the Mappls app:
```groovy
`mappls://navigation?places=xxxx,yyyy,{destinationName}&isNav=true&mode=driving`
```
<br>

### Parameters
1. `places=lat,lng,{name}`: Destination coordinates and optional place name in the format
2. `isNav=true`: Triggers turn-by-turn navigation mode immediately upon launch
3. `mode=driving`: (Optional) Navigation mode. Supported values: `driving`, `trucking`, `biking` `walking`
<br><br>

### Sample calling URI
<br>

```
`https://mappls.com/navigation?places=28.612964,77.229463,IndiaGate&isNav=true&mode=driving`
```

<br>

### Sample calling URL
<br>

```
`mappls://navigation?places=28.612964,77.229463,IndiaGate&isNav=true&mode=driving`
```

<br>

### Integration Tips
<br>
This URI is intended for <strong>mobile deep linking</strong>, and will only work if the <strong>Mappls app is installed</strong> otherwise please ask the user to download the mappls app.
Mappls App package name : `com.mmi.maps`

<br><br>

### URL Schema
<br>
Use this HTTPS link to open navigation in the **browser** or redirect to the app if installed.
`https://mappls.com/navigation?places=28.612964,77.229463,IndiaGate&isNav=true&mode=biking 

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
https://mappls.com/corona?safety_alert
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
https://mappls.com/corona?safety_alert
```

<br><br>

## 6. Rate and Review
<br>

### Introduction
Users can Rate and Review any place that they have visited and they can also share the place review with their social network.

<br>

### URL


```
www.mappls.com/review/<mappls-pin>/<reviewID>
```

<br>



### Sample sharable URL
<br>

```
https://www.mappls.com/review/MMI000/bed7a947-f813-41cf-89c9-ec522b416954
```

<br><br>

## 7. Report (Place Detail)
<br>

### Introduction
Mappls provides map-based issue reporting for citizens, business and administration to report issues and complaints on the map which authorities can see exact location of, and immediately resolve; with resolution notifications going to citizens, to close the loop. This will help increase cleanliness, reduce crime, ensure better life for citizens and give actionable insights of issue locations by category for better planning & maintenance of a place.

<br>

### URL


```
www.mappls.com/report/<mappls-pin>/<reportID>
```

<br>




### Sample sharable URL
<br>

```
https://www.mappls.com/report/1T182A/37aa7c96-d080-42c8-9ce7-c05823b6f01c
```

<br><br>

## 8. View Reported Issue
<br>

### Introduction
View & share hyper local issues & updates like traffic, potholes, unsafe zones to make our roads, neighbourhood & cities better.

<br>

### URL


```
www.mappls.com/report/<mappls-pin>/<reportID>
```

<br>




### Sample sharable URL
<br>

```
https://www.mappls.com/report/D7JUOT/774670fd-34c7-4b59-85bf-aa2f68e730f5
```

<br><br>

## 9. User Profile
<br>

### Introduction

User Profile shows all the account details of a person's profile on the map. It shows the user's journey on the map. Users can view and edit the personal details and profile picture. This segment shows the Followers, Following, Saves, Reviews, Reports and Device activity.

<br>

### URL


```
www.mappls.com/profile/<username>
```

<br>




### Sample sharable URL
<br>

```
https://mappls.com/profile/parinita
```

<br><br>

## 10. Point on Map
<br>

### Introduction
Users can long-press on any point on the map to see information, navigate, share and report.

<br>

### URL


```
www.mappls.com/pom/lat,lng
```

<br>



### Sample sharable URL
<br>

```
https://mappls.com/pom/28.55168436228523%2C77.26866761528169
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



[<img src="https://www.mapmyindia.com/api/img/mapmyindia-api.png" height="40"/> </p>](https://www.mapmyindia.com/api)

# Transaction Definitions

| Serial | APIs / SDKs | Transaction Definition |
| ---| --- | --- |
| 1 | [Interactive Map JS Web SDK/API](https://github.com/mappls-api/mappls-web-maps-js) (also applicable to Cordova/ReactJS based packages) | 	One transaction is one load of the SDK (SDK Initialization) in any web app. <br> Events such as Panning, zooming in/out, adding markers, polyline, ploygons on Map is NOT considered as a transaction, unless they result in fresh tiles being downloaded from the server. <br>In case where fresh tiles are requested from server, for every 10 tiles so refreshed an additional transaction is incurred. Actions such as zoom may not necessarily cause tiles being fetched anew from server; since browser's JS engines are capable of limited<sup>1</sup> amount of browser-cache based rendering.<br><sup>1</sup>Deliberate caching of map tiles is not permitted.<br>When a page is refereshed/reloaded, it results in the map SDK loaded afresh and hence incurs additional transaction in accordance with above. |
| 2 | [Geocoding API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-maps-geocoding-rest-api-example) | One request using the API method/URL will be considered as one transaction. Upto 1 geocoded address is returned one request, unless otherwise specified in agreement with customer. |
| 3 | [Reverse Geocoding API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-maps-reverse-geocoding-rest-api-example) | One request using the API method/URL will be considered as one transaction. Upto 1 reverse geocoded address is returned one request, unless otherwise specified in agreement with customer. |
| 4 | [Routing API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-routing-api) | One Transaction for Routing API (`any profile`) is equivalent to route requested between two sets of lat-long. Upto 98 via points are allowed in one request. E.g. If distance from x,y to x3,y3 via x1,y1 and x2,y2 is requested, then its counted as 3 transactions. |
| 5 | [Distance Matrix API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-distance-matrix-api) | One Transaction for Distance Matrix API is equivalent to distance requested between two sets of lat-long. E.g. distance from x,y to x1,y1 and x2,y2 is requested, then its counted as 2 transactions. |
| 6 | [Still Map Image API]() | One Request(which returns one image) using the API method/URL will be considered as one transaction. |
| 7 | [Autosuggest API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-maps-auto-suggest-api-example) (per request) | One request using the API URL will be considered as one transaction. At any point, for any string in the input, the output will be list of places matching with that input string. |
| 8 | [Nearby APIs](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-maps-near-by-api-example) | One request using the API method/URL will be considered as one transaction. Upto a maximum of 10 places are returned in 1 request unless otherwise specified in agreement with customer. |
| 9 | [Place Details](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-maps-place-details-api-example) | One request using the API method/URL will be considered as one transaction. |
| 10 | [Traveled Route Image API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-traveled-route-api) | One Request(which returns one image) using the API method/URL will be considered as one transaction. |
| 11 | [POI Along the Route API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-poi-along-the-route-api) | One request using the API method/URL will be considered as one transaction. Upto a maximum of 10 places are returned in 1 request unless otherwise specified in agreement with customer. |
| 12 | [Snap to Road API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-snapToRoad-api) | One request using the API method/URL will be considered as one transaction. One request can take upto a maximum of 100 raw coordinates for map matching. |
| 13 | [Address Standardization API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-address-analytics-api) | One request using the API method/URL will be considered as one transaction. |
| 14 | [Route Optimization API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-route-optimization-api) | One Transaction for Route Optimization API (`any profile`) is equivalent to route optimization requested between two sets of lat-long. Upto 98 via points are allowed in one request. E.g. If optimization is requested from x,y to x3,y3 via x1,y1 and x2,y2 is requested, then its counted as 3 transactions. |
| 15 | [Mobile Maps SDK for Android](https://github.com/mappls-api/mappls-android-sdk) | One transaction is one load of the SDK (SDK Initialization) in any mobile app. <br> Events such as Panning, zooming in/out, adding markers, polyline, ploygons on Map is NOT considered as a transaction, unless they result in fresh tiles being downloaded from the server. <br>In case where fresh tiles are requested from server, for every 10 tiles so refreshed an additional transaction is incurred. |
| 16 | [Mobile Maps SDK for iOS](https://github.com/mappls-api/mappls-ios-sdk) | One transaction is one load of the SDK (SDK Initialization) in any mobile app. <br> Events such as Panning, zooming in/out, adding markers, polyline, ploygons on Map is NOT considered as a transaction, unless they result in fresh tiles being downloaded from the server. <br>In case where fresh tiles are requested from server, for every 10 tiles so refreshed an additional transaction is incurred. |
| 17 | [Text Search API](https://github.com/mappls-api/mappls-rest-apis/tree/main/mappls-textsearch-api) | One request using the API method/URL will be considered as one transaction. |
	
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

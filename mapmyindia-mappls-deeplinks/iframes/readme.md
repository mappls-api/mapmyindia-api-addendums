[<img src="https://cdn.mapmyindia.com/mappls_web/logos/svg/mappls.svg" height="40"/> </p>](https://www.about.mappls.com/api)


# Embeddable Iframe Links from Mappls App

## 1. Mappls Places iFrame Widget

### Introduction
The Mappls Places Iframe Widget simplifies the process of embedding a Mappls map with specific Mappls pin details into your website or web application. With just a single line of code, you can enhance your web presence and offer valuable features to your users. This versatile widget not only allows you to showcase your place's location on Mappls but also offers powerful customization options.

You can provide directions to your place, enable users to view their location on Mappls, offer easy access to Mappls pin QR codes, and effortlessly adjust the iframe size to seamlessly integrate with your website's design.

Add the Mappls Place Iframe widget to the website to elevate user experience and make your website more intuitive and interactive with the Mappls Places Iframe Widget.

![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/2deb988b-af33-45b9-a950-980e6024dddf)


### Embed Mappls Place iframe on your website by following the below steps.

To use the Mappls Places Iframe Widget, you need to specify the following URL format:
```groovy
<iframe src="https://embed.mappls.com/place/<MAPPLS_PIN>?token=<TOKEN>&fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" allowfullscreen="">
```

***<MAPPLS_PIN> (Required):*** Replace this with the unique identifier of the Mappls Pin you want to display details for.

***Token (Optional):*** An optional user token for access control.

***fullscreen (Optional):*** A boolean value (true/false) to enable or disable fullscreen mode. (Default: true)

**position (Optional):** Specifies the position of the widget on the screen. Options include 'top-left,' 'top-right,' 'bottom-left,' and 'bottom-right.' (Default: top-left)

***zoom (Optional):*** Sets the initial zoom level for the map. (Default: 16)

***pitch (Optional):*** Sets the initial pitch angle of the map. (Default: 0)

***width:*** 100% (Optional): This sets the width of the  iframe to be 100% of its parent container's width.

***height:*** 80vh (Optional): This sets the height of the iframe to be 80% of the viewport height (vh)
 
**Demo Link**: [https://embed.mappls.com/demo.html](https://embed.mappls.com/demo.html)

To learn more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration/).

### Sample code
```groovy
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mappls Place Widget</title>
</head>
<body>
<iframe src="https://embed.mappls.com/place/mmi000?token=<TOKEN>&fullscreen=true&position=top-left&zoom=16&pitch=45" style="width: 100%; height: 80vh;" title="embed Example" allowfullscreen="">
</iframe>
</body>
</html>
```
#### Sample Output
![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/45e9d6e2-6922-4e38-9aa7-8257483f2e2c)

#### Customize the size according to the required size (The below image is for 300 *300). 
![image](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/f1843f98-073c-4d79-b749-44e389391fe9)

### Use Cases of Mappls Places iFrame:

The Mappls Places Iframe Widget can be a valuable addition to various types of websites and web applications, enhancing user experience and providing useful location-based information.

Here are some ideal places and scenarios where you can effectively use this iframe:

**1. Business Websites**: Any business with a physical location can benefit from embedding the Mappls Places Iframe on their website. It allows customers to find directions, view the location on a map, and get a sense of the surroundings.

**2. Event Websites**: Websites promoting events, conferences, or festivals can use the iframe to display the event's venue location. Attendees can easily access directions and explore nearby points of interest.

**3. Tourism and Travel Websites**: Travel agencies, hotels, and tourism-related websites can use the widget to showcase the locations of accommodations, tourist attractions, and points of interest. It helps travelers plan their trips more effectively.

**4. Real Estate Listings**: Real estate websites can use the iframe to display the location of properties. This provides potential buyers or renters with a clear understanding of the property's surroundings.

**5. Local Directories**: Websites that serve as local directories or business listings can enhance their listings by including interactive maps with pins for each business.

**6. Restaurants and Food Services:** Restaurants, cafes, and food delivery services can use the widget to show their location and allow customers to get directions or check out the restaurant's surroundings.

**7. Community and Event Spaces:** Websites for community centers, event spaces, and public venues can use the widget to help users locate the facility and explore nearby amenities.

**8. Education and Campus Maps:** Educational institutions can embed the iframe to display campus maps, making it easy for students, staff, and visitors to find specific buildings or departments.

**9. Healthcare Providers:** Medical facilities, clinics, and hospitals can use the widget to display their locations, making it convenient for patients to locate their services.

**10. E-commerce Websites:** Online retailers with physical stores can use the widget to display store locations and help customers find the nearest retail location.

**11. Non-profit Organizations:** Nonprofits organizing events or fundraisers can use the widget to show event locations and help participants navigate to the venue.

**12. City and Government Websites:** Municipalities can provide interactive maps on their websites for citizens to access important locations such as government offices, parks, and public services.

**13. Transportation Services:** Websites related to transportation services, such as taxi or ride-sharing companies, can use the widget to display vehicle locations or pickup points.

**14. Adventure and Outdoor Activities:** Websites promoting outdoor activities like hiking, biking, or adventure sports can use the iframe to showcase trailheads and adventure locations.

**15. Blog Posts and Articles:** Individual bloggers and content creators can embed the widget in articles or blog posts to provide context for specific locations mentioned in their content.

The Mappls Places Iframe Widget's versatility makes it a valuable tool for any website or application that aims to provide location-related information, improve user engagement, and enhance the overall user experience. Its ease of integration and customization options make it suitable for a wide range of industries and purposes.


[<img src="https://cdn.mapmyindia.com/mappls_web/logos/svg/mappls.svg" height="40"/> </p>](https://www.about.mappls.com/api)


## 2. Embed Immersive & Interactive 3D Metaverse Maps for Cricket World Cup Venues with Mappls

### Introduction

Introducing MapmyIndia's cutting-edge iFrame Embeddable Widget, an **Immersive and 3D metaverse maps** for **Cricket World Cup** venues. Now, you can seamlessly integrate these captivating 3D Metaverse maps into your website with a single line of code, bringing the excitement of cricket's grandest stages directly to your audience. Get ready to engage and delight your users like never before with MapmyIndia's immersive technology.

Let your audience explore the venues at their own pace. They can **zoom in, rotate, and interact with the maps** to get a comprehensive view of the Cricet World Cup Stadiums.


**It can be easily embedded on your website by following below steps.**

**Embed Ahmedabad, Narendra Modi Stadium:**
```groovy
<iframe src="https://embed.mappls.com/immersive/12d1ce?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="1000"></iframe>
```
1.  Customize the width and height attributes as needed to fit your website's design and layout.
2.  Copy the entire iframe code provided by the source website.
3.  Go to the HTML source code of the page on which you want to embed the widget (if you're using a website builder or content management system, there's usually an option to add custom HTML code).
4.  Paste the iframe code in the appropriate location within your HTML code.
5.  Save and publish your webpage.

**Parameter Details:**
1. token - user token (Optional )
2. fullscreen - true/false (default false)
3. placeDetails - true/false (default false)
4. castShadow - true/false (default false)
5. rotate - true/false (default true)

Above iframe is for the Ahamedabad, Narendra Modi Stadium, For all other 9 stadium Iframe link is given below.

Sample Code:
```groovy
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mappls 3D immersive Widget</title>
</head>
<body>
src="https://embed.mappls.com/immersive/5ce166?placeDetails=true&castShadow=false&rotate=true" style="width: 100%; height: 80vh;" title="Mappls 3D Metaverse Maps - Chennai, MA Chidambaram Stadium:" allowfullscreen="">

</iframe>
</body>
</html>
```
**Sample Output**

![ezgif com-video-to-gif (1)](https://github.com/mappls-api/mapmyindia-api-addendums/assets/59359484/2cd83866-767f-4ec8-ac5c-bad12e1b9343)

To know more on how to create your authorization tokens, please use our authorization token URL. More details available [here](https://developer.mappls.com/mapping/tokenGeneration/).

For inquiries and support, please email us at feedback@mappls.com or apisupport@mappls.com

**List of iFrame Widget for all the Cricket World cup venues:**

**1. Wankhede Stadium**

```groovy 
<iframe src="https://embed.mappls.com/immersive/e856cd?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```

**2. Rajiv Gandhi Stadium**

```groovy 
<iframe src="https://embed.mappls.com/immersive/518as8?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```

**3. Narendra Modi Stadium**
```groovy 
<iframe src="https://embed.mappls.com/immersive/12d1ce?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```

**4. MCA International Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/bmovtc?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```

**5. MA Chidambaram Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/5f8ta1?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```
**6. M Chinnaswamy Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/527t5s?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```
**7. HPCA Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/bcfsab?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```
**8. Eden Gardens**
```groovy
<iframe src="https://embed.mappls.com/immersive/1fd4c4?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```
**9. BRSABVE Cricket Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/e3bfwd?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```

**10. Arun Jaitley Stadium**
```groovy
<iframe src="https://embed.mappls.com/immersive/5ce166?token=<TOKEN>&placeDetails=true&castShadow=false&rotate=true" width="1000" height="400"></iframe>
```




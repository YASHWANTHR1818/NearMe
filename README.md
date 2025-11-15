# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
`NEARME.HTML`
```

<!DOCTYPE html>
<html>
<head>
<title>POONAMALLEE Map</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h2>Arakkonam Map</h2>
<p>Click any marked spot on the map to know about the place.</p>
<!-- Lock the image size -->
<img src="c:\Users\admin\Desktop\poonamap.png" alt="POONAMALLEE Map" usemap="#map" width="1500" height="700" style="border:2px solid black;">

<map name="map">
   

 <area href="GRT.html" coords="700,100,737,51" shape="rect">
  <area shape="rect" coords="670,279,517,217" href="temple.html" alt="temple">
  <area shape="rect" coords="674,385,850,285" href="arbindho.html" alt="arbindho school">
  

 
</map>

</body>
</html>
```
`GRT.HTML`
```

<!DOCTYPE html>
<html>
<head>
<title>POONAMALLEE Map</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h2>Arakkonam Map</h2>
<p>Click any marked spot on the map to know about the place.</p>
<!-- Lock the image size -->
<img src="c:\Users\admin\Desktop\poonamap.png" alt="POONAMALLEE Map" usemap="#map" width="1500" height="700" style="border:2px solid black;">

<map name="map">
   

 <area href="GRT.html" coords="700,100,737,51" shape="rect">
  <area shape="rect" coords="670,279,517,217" href="temple.html" alt="temple">
  <area shape="rect" coords="674,385,850,285" href="arbindho.html" alt="arbindho school">
  

 
</map>

</body>
</html>
```
`TEMPLE.HTML`
```


<html>
<head>
    <title>temple</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>Varadharaja temple</h2>
    <img src="c:\Users\admin\Desktop\varadarajatemple.png" alt="temple">
    <p>
        Poondhamalli Varadaraja Perumal Temple A Serene Divine Abode
Located in the centre of the busy town of Poovrindavalli (now known as Poondhamalli) in Tiruvallur District, Tamil Nadu,
 this majestic and tranquil temple is dedicated to Lord Varadaraja Perumal. 
    </p>
</body>
</html>
```
`ARBININDHO.HTML`
```
<!DOCTYPE html>
<html>
<head>
    <title>arbindhoschool</title>
    <meta name= "viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>arbindhoschool</h2>
    <img src="c:\Users\admin\Desktop\arbindhoschool.png" alt="arbindho">
    <p>
      This co-educational English medium School, established in 2012,
       was named after Aurobando Group of Institutions whose welfare measures for their workforce.
    </p>
</body>
</html>
```



## OUTPUT
<img width="1187" height="702" alt="image" src="https://github.com/user-attachments/assets/757e9da8-5463-4449-975c-715b2f5234b1" />
<img width="1157" height="870" alt="image" src="https://github.com/user-attachments/assets/a590ae7c-86c6-4368-ab26-6189981c22bf" />
<img width="1181" height="896" alt="image" src="https://github.com/user-attachments/assets/421e3bb1-f44e-42bc-807e-c8a2be864904" />
<img width="992" height="875" alt="image" src="https://github.com/user-attachments/assets/3e6e831b-0620-4d6b-ab29-84d445f9b261" />











## RESULT
The program for implementing image maps using HTML is executed successfully.

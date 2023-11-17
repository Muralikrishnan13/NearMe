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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Guindy National Park" title="Guindy National Park" href="park.html" coords="874,649,1028,721" shape="rect">
        <area target="_blank" alt="Edward Elliot's Beach" title="Edward Elliot's Beach" href="beach.html" coords="1642,713,1918,779" shape="rect">
        <area target="_blank" alt="Phoenix Mall" title="Phoenix Mall" href="mall.html" coords="548,879,764,945" shape="rect">
        <area target="_blank" alt="Indian Institute of Technology" title="Indian Institute of Technology" href="IIT.html" coords="903,852,1099,918" shape="rect">
        <area target="_blank" alt="ITC grand chola" title="ITC grand chola" href="itc.html" coords="755,490,904,580" shape="rect">
    </map>
</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edward Elliot's Beach</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Edward Elliot's Beach</h1>
    <br>
    <hr color="Brown">
    <p>Edward Elliot's Beach, simply called as Elliot's Beach and popularly known as Besant Nagar Beach or the Bessie, is a natural urban beach located in the Besant Nagar neighbourhood of Chennai, Tamil Nadu, India. It is located next to the southern tip of the Marina Beach,[1] and was named after Edward Elliot, a chief magistrate and superintendent of police of the Madras Presidency in colonial India.[2] It has the Shrine of Our Lady of Good Health—also known as Annai Vailankanni Church—on its shore, and the Ashtalakshmi Temple nearby.</p>

</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phoenix Marketcity</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Phoenix Marketcity</h1>
    <br>
    <hr color="Brown">
    <p>Phoenix Marketcity is a shopping mall developed by Phoenix Mills Limited located in Chennai, Tamil Nadu, India. It was opened in January 2013[1] and is the 2nd largest mall in the city. It was the fourth largest mall in India in 2018. It has a built up area of 1,000,000 square feet. Also there is a Palladium mall situated right next to it.</p>

</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITC Grand Chola Hotel</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>ITC Grand Chola Hotel</h1>
    <br>
    <hr color="Brown">
    <p>The ITC Grand Chola is a 5-star luxury hotel in Chennai, India.[4] It is located in Guindy, opposite SPIC building and along the same row of buildings as Ashok Leyland Towers. The building, designed by Singapore-based SRSS Architects, is of mixed-use development with three separate wings and is themed after traditional Dravidian architecture of the Chola dynasty.[5] The hotel is the ninth hotel in The Luxury Collection brand</p>

</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guindy National Park</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Guindy National Park</h1>
    <br>
    <hr color="Brown">
    <p>Guindy National Park is a 2.70 km2 (1.04 sq mi) protected area of Tamil Nadu, located in Chennai, India, is the 8th-smallest National Park of India and one of the very few national parks situated inside a city. The park is an extension of the grounds surrounding Raj Bhavan, formerly known as the 'Guindy Lodge', the official residence of the governor of Tamil Nadu, India. It extends deep inside the governor's estate, enclosing beautiful forests, scrub lands, lakes and streams.</p>

</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Indian Institutes of Technology</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Indian Institutes of Technology</h1>
    <br>
    <hr color="Brown">
    <p>he Indian Institute of Technology (IITs) are Centrally Funded Technical Institutes located across India. They are under the ownership of the Ministry of Education of the Government of India and are governed by the Institutes of Technology Act, 1961. The Act declares them as Institutes of National Importance and lays down their powers, duties, and framework for governance as the country's premier institutions in the field of technology.</p>

</body>
</html>
```


## OUTPUT

![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/933f958d-b38c-4347-83b4-56c21d12c145)
![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/bd2d64b0-f6c1-4d84-b537-9e57351a71e3)
![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/c06d512a-407c-40c6-b822-7dd330806821)
![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/91c34e7f-7d25-4985-b93f-2a5a274f3548)
![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/f2639974-c551-47b2-9a34-8f206c4bc36d)
![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/0cb90618-945f-4970-bd73-d30d482278ac)

![image](https://github.com/Muralikrishnan13/NearMe/assets/130058615/89f30b88-7314-4851-a19a-c873e437aaf2)


## RESULT
The program for implementing image maps using HTML is executed successfully.

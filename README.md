# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:

Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp.

### Step 2:

Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

### Step 3:

Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

### Step 4:

Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

### Step 5:

Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py.

## Code:
## Map.html
```python
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    Chennai - Korattur
            </font>            
        </h1>
        <h3 align="center">
        <font color="blue" face ="cursive">
            J.NETHRAA(212222100031)
        </font>
            
        </h3>
        <center>
        <img id="Image-Maps-Com-image-maps-2023-06-07-031905" src="../img/map.png" border="0" width="1845" height="941" orgWidth="1845" orgHeight="941" usemap="#image-maps-2023-06-07-031905" alt="" />
        <map name="image-maps-2023-06-07-031905" id="ImageMapsCom-image-maps-2023-06-07-031905">
        <area  alt="" title="koratturlake" href="lake.html" shape="rect" coords="703,38,949,299" style="outline:none;" target="_self"/>
        <area  alt="" title="theatre" href="theatre.html" shape="rect" coords="1375,528,1528,612" style="outline:none;" target="_self"/>
        <area  alt="" title="mall" href="mall.html" shape="rect" coords="931,632,1093,729" style="outline:none;" target="_self"/>
        <area  alt="" title="foodstreet" href="food.html" shape="rect" coords="291,624,453,721" style="outline:none;" target="_self"/>
        <area  alt="" title="aavinfactory" href="aavin.html" shape="rect" coords="617,350,779,493" style="outline:none;" target="_self"/>
        <area shape="rect" coords="1843,939,1845,941" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
        </map>
        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>
    </body>
</html>
```
## Lake.html
```python
<!DOCTYPE html>
<html>
<head>
    <title>
       KORATTUR LAKE
    </title>
</head>
<body bgcolor="sky blue">
<h1 align="center">
    <font color="cyan red" face="cursive">
       KORATTUR LAKE
    </font>
</h1>
<center>
    <img src ="/static/img/koratturlake.png"  height="300" width="600" align="center" >
</center>
<p align="center">
    <font color="black" face="Ariel" size="6">
        <OL  TYPE="1" START="1">
            <LI>Korattur Aeri, or Korattur Lake, also known as Vembu Pasumai Thittu, is a lake spread over 990 acres in Korattur, Chennai, India. <br></LI>     
            <LI>It is located to the north of the Chennai to Arakkonam railway line. It is one of the largest lakes in the western part of the city. <br></LI>
            <LI>Korattur Aeri is one of a chain of three water bodies, including the Ambattur Aeri and the Madhavaram Aeri, where surplus water from one is transported to another.<br></LI>
            <LI>The water from the lake had been supplied to Chennai residents for a brief period when there was a shortage in the late 1970s.<br></LI>
            <LI>However, over the years, the lake has been contaminated with sewage and industrial effluents from surrounding areas such as Pattaravakkam, Athipet and Ambattur.<br></LI>
        </OL>
    </font>


    <font color ="purple" face = "cursive" size="14" > 
    "AMAZING TOURIST SPOT"
    </font>
</p>
</body>
</html>
```
## Aavin.html
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        AAVIN PRODUCT DAIRY
    </title>
</head>
<body bgcolor="beige">
<h1 align="center">
    <font color="navy blue" face="cursive">
        AAVIN PRODUCT DAIRY
    </font>
</h1>
<center>
    <img src ="/static/img/AAVIN.png"  height="300" width="600" align="center" >
</center>
<p align="center">
    <font color="black" face="Ariel" size="6">
        <OL  TYPE="1" START="1">
            <li>The Products dairy at Ambattur was established in the year 2003 to produce milk by-products like khova, mysurpa and milk peda.<br></li>     
            <LI>The products dairy was expanded to produce 15,000 litres of Ice creams per day during the year 2016. Production facilities were also created for fermented milk products like lassi, yoghurt, paneer, butter milk, curd and Pro-biotic curd.<br></LI>
            <LI>The product dairy caters to the needs of the metro consumers and supply is also made to district unions.<br></LI>
            <LI>The quality of the products and by-products is assured by means of adopting ISO (International Standards Organization), FSSAI (Food Safety and Standards Authority of India), HACCP (Hazard Analysis and Critical Control Point) procedures.<br></LI>
        </OL>
    </font>


    <font color ="orange" face = "cursive" size="7" > 
    "THE COMPANY PRODUCES A WIDE RANGE OF PRODUCTS"
    </font>
</p>
</body>
</html>
```
## Theatre.html
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        AGS VILLIVAKKAM
    </title>
</head>
<body bgcolor="orange" >
<h1 align="center">
    <font color="white" face="cursive">
        AGS CINEMAS
    </font>
</h1>
<center>
     <img src ="/static/img/theatre.png"  height="300" width="600" align="center" >
</center>
<p align="center">
    <font color="black" face="Ariel" size="20" >
        <OL  TYPE="1" START="1">
            <LI>AGS Cinemas Villivakkam is a chain of theatres in india that exhibit a myriad of movies around the year.<br></LI>     
            <LI>Be it a Regional,Bollywood or Hollywood movie,at AGS Cinemas Villivakkam you can watch them all.<br></LI>
            
        </OL>
    </font>


    <font color ="brown" face = "cursive" size="12" > 
    "Film or movie, a series of still images that create the illusion of moving image."
    </font>
</p>
</body>
</html>
```

## Mall.html
```python
<!DOCTYPE html>
<html>
<head>
    <title>
        SHOPPING MALL
    </title>
</head>
<body bgcolor="pink">
<h1 align="center">
    <font color="sky blue" face="cursive">
        THE LEGEND SARAVANA STORES
    </font>
</h1>
<center>
     <img src ="/static/img/mall.png"  height="300" width="600" align="center" >
</center>
<p align="center">
    <font color="black" face="Ariel" size="6">
        <OL  TYPE="1" START="1">
            <LI>Saravana Stores, founded in 1969, is a chain of retail stores in India. It is the largest family owned business retail chain in India.<br></LI>     
            <LI>Saravana Stores operates seven stores in Chennai, at T. Nagar, Purasawalkam, Porur, Padi, Sholinganallur, Chromepet and Usman Road.<br></LI>
            <LI>On 2 September 2008, a fire inside the building led to death of two of its employees and damages worth Crores of rupees. Unauthorized construction and ignoring safety measures are believed to be the reason.<br></LI>
            <LI>In 2004, Saravana Stores Group launched a new ice cream brand named Jamaai, a 100% milk based ice-cream brand. <br></LI>
        </OL>
    </font>


    <font color ="purple" face = "cursive" size="16" > 
    "EXCELLENT PLACE FOR SHOPPING"
    </font>
</p>
</body>
</html>
```
## Food.html
```python
<!DOCTYPE html>
<html>
<head>
    <title>
       FOOD STREET
    </title>
</head>
<body bgcolor="grey">
<h1 align="center">
    <font color="purple" face="cursive">
        HAPPY FOOD STREET AMBATTUR
    </font>
</h1>
<center>
    <img src ="/static/img/foodstreet.png"  height="300" width="600" align="center" >
</center>
<p align="center">
    <font color="black" face="Ariel" size="8">
        <OL  TYPE="1" START="1">
            <LI>A food street is a pedestrianised area that has been designated for restaurants and cafes.<br></LI>     
            <LI>The food street is lined with food stalls, restaurants, and other food shops, and are typically pedestrianized.<br></LI>
            <LI>Food streets, and food parks, exist in several metropolitan cities in the country, and attending them has become a social norm, with people using them as both formal and informal meeting areas.<br></LI>
        </OL>
    </font>


    <font color ="pink" face = "cursive" size="16" > 
    "EXCELLENT FOOD SPOT FOR ALL FOODIES"
    </font>
</p>
</body>
</html>
```

## Output:
## server output:
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/c5971600-e2e0-41db-a81d-20b57e3a1d29)

## client output:
## Map :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/11e9bb0b-09ae-462e-831b-ed912046dab1)

## Lake :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/f7bba9b2-156d-4b8a-a1b6-27626b7241ce)

## Aavin :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/0e587598-6c65-4cd7-8932-34eeeb272613)

## Theatre :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/65d94218-7b59-4566-8a8e-8a389d77cc54)

## Mall :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/e6544892-961f-46a2-bd9b-2be773ccea79)


## Food :
![image](https://github.com/Nethraa24/places-around-me/assets/121215786/86100d55-3441-4648-98b3-8b2cd34771a9)


## Result:
Hence, a website has been developed to display details about the colleges around saveetha university.

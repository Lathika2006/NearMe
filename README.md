# Ex04 Places Around Me
## Date: 19/03/2024

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
```
map.html

<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">Tirunelveli</font></h1>
        <h3 align="center">
            <font color="blue">LATHIKA L J (212223220050)</font></h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="550" width="1300">
            <map name="MyCity">
                    <area shape="rect" coords="350,220,400,270" href="NellaiTemple.html" title="Arulmigu Nellaiappar Temple">     
                    <area shape="rect" coords="750,270,850,350" href="Jail.html" title="PalayamKottaiai Jail">
                    <area shape="rect" coords="400,600,500,650" href="Market.html" title="Melapalayam">
                    <area shape="rect" coords="1100,250,900,300" href="Bus.html" title="Bus Stand">
                    <area shape="rect" coords="800,300,750,350" href="Vels.html" title="Vels Vidhyalaya School">
            </map>
        </center>
       

    </body>
</html>

NellaiTemple.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirunelveli</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="orange" size="5.5">Arulmigu Nellaiappar Temple</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Nellaiappar Temple in Tirunelveli is a renowned Hindu temple dedicated to Lord Shiva.<br>
            It is famous for its elaborate architecture, intricate sculptures, and vibrant festivals that attract devotees and tourists from around the world.<br>
            The temple's annual Arudra Darshanam festival is a significant event, drawing large crowds to witness the celestial dance of Lord Shiva.
        </font>
        </p>
    </body>
</html>

Jail.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirunelveli</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="green" size="5.5">Palayamkottai Jail</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Palayamkottai is a historic town in Tirunelveli known for its cultural heritage and educational institutions.<br>
            Palayamkottai Jail, also called the Palayamkottai Central Prison, is a notable landmark with a rich history dating back to the British colonial era,
            serving as a significant correctional facility in Tamil Nadu.
        </font>
        </p>
    </body>
</html>

Market.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirunelveli</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="green" size="5.5">Melapalyam</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Melapalayam Market is a bustling commercial hub in Tirunelveli known for its diverse range of goods and lively atmosphere.<br>
            It offers a wide variety of fresh produce, clothing, accessories, and household items,<br>
            making it a popular destination for locals and visitors alike.<br>
            The market's vibrant energy and array of products make it a vibrant and dynamic shopping experience.

            
        </font>
        </p>
    </body>
</html>

Bus.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirunelveli</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="purple" size="5.5">Bus Stand</font>
    </h3>
    <body bgcolor="skyblue" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Tirunelveli Bus Stand is a major transportation hub connecting various parts of the city and neighboring areas.<br>
            It offers a range of bus services, including local routes and long-distance travel options, making it convenient for commuters and travelers.<br>
            The bus stand's facilities include ticket counters, waiting areas, and amenities like shops and eateries for passengers' convenience.
        </font>
        </p>
    </body>
</html>

Vels.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Tirunelveli</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="purple" size="5.5">Vels Vidhyalaya School</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Vels Vidhyalaya School in Tirunelveli is a renowned educational institution known for its academic excellence and holistic approach to learning.
            The school provides a conducive environment for students to develop their talents and skills through a diverse range of curricular and extracurricular activities.
            With modern facilities and experienced faculty,
            Vels Vidhyalaya School aims to nurture well-rounded individuals prepared for future challenges.
        </font>
        </p>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-03-22 183310.png>)

![alt text](<Screenshot 2024-03-22 223350-2.png>)

![alt text](<Screenshot 2024-03-22 223226-1.png>)

![alt text](<Screenshot 2024-03-22 223039-1.png>)

![alt text](<Screenshot 2024-03-22 223309-1.png>)

![alt text](<Screenshot 2024-03-22 222626-1.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

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
\\\
map1.html

<html>
<head>
    <title>My City</title>
</head>
<body>
    <h1 align="center">
        <font color="red"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
        <font color="blue"><b>SURENDAR (212224110052)</b></font>
    </h3>

    <center>
        <img src="map1.png" usemap="#MyCity" height="951" width="1816">
        <map name="MyCity">
            <area shape="rect" coords="1075,274,1265,327" href="Apple.html" title="Apple showroom">
            <area shape="rect" coords="956,363,1081,411" href="Trends.html" title="Trends shop">
            <area shape="rect" coords="368,479,558,551" href="Smokehub.html" title="Smoke hub BBQ">
            <area shape="rect" coords="14,589,235,630" href="CopperKitchen.html" title="CopperKitchen Porur">
            <area shape="rect" coords="2,396,226,459" href="Temple.html" title="Ponni Amman Temple">
        </map>
    </center>
</body>
</html>


Apple.html

<html>
  <head>
    <title>APPLE SHOWROOM</title>
  </head>
  <body bgcolor="pink">
    <h1 align="center">
      <font color="black"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
      <font color="blue"><b>i PLANET VALASARAVAKKAM</b></font>
    </h3>

    <hr size="3" color="red" />

    <p align="justify">
      <font face="Georgia" size="5">

        iPlanet Valasaravakkam, situated on Arcot Road in Chennai, is a premium Apple Authorised 
        Reseller offering a comprehensive range of Apple products including iPhones, iPads, MacBooks,
        Apple Watches, and accessories. The store is known for its professional staff,
        excellent customer service, and genuine Apple products. It also houses an Apple 
        Authorised Service Center, providing reliable repair and support services. 
        With its convenient location and customer-focused approach, 
        iPlanet Valasaravakkam serves as a one-stop destination for all Apple enthusiasts and users in the area.
        
      </font>
    </p>
  </body>
</html>


CopperKitchen.html

<html>
  <head>
    <title>COPPER KITCHEN PORUR</title>
  </head>
  <body bgcolor="pink">
    <h1 align="center">
      <font color="black"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
      <font color="blue"><b>COPPER KITCHEN - FINEST DINNING PLACE </b></font>
    </h3>

    <hr size="3" color="red" />

    <p align="justify">
      <font face="Georgia" size="5">

        Copper Kitchen in Porur offers a diverse menu featuring Chettinad, 
        Tandoor, and traditional Muslim wedding-style biryanis, 
        including specialties like full goat biryani and seafood platters. 
        The restaurant emphasizes hygiene, adhering to FSSAI standards with 
        practices like chlorine-washed vegetables and daily fresh seafood . 
        With a family-friendly ambiance and options like Chinese and Arabic food, 
        it's a popular choice for those seeking flavorful dishes in a clean environment .

        
      </font>
    </p>
  </body>
</html>


Smokehub.html

<html>
  <head>
    <title>TRENDS SHOP</title>
  </head>
  <body bgcolor="yellow">
    <h1 align="center">
      <font color="black"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
      <font color="black"><b>SMOKE HUB - MULTI CUISINE BUFFET</b></font>
    </h3>

    <hr size="3" color="CYAN" />

    <p align="justify">
      <font face="Georgia" size="5">


        Smoke Hub Barbeque in Porur offers a delightful buffet experience featuring 
        dishes like honey chicken wings, tandoori prawns, and hot jalebi. With an 
        average cost of 1,800 - 2,200 for two, it provides value through 
        generous portions and frequent discounts, including flat 30% off on bills. 
        The restaurant's cozy ambiance and varied menu make it a popular choice for 
        families and groups seeking delicious food at affordable prices.

      </font>
    </p>
  </body>
</html>


Temple.html

<html>
  <head>
    <title>PONNI AMMAN TEMPLE</title>
  </head>
  <body bgcolor="red">
    <h1 align="center">
      <font color="black"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
      <font color="blue"><b>PONNI AMMAN TEMPLE - Porur</b></font>
    </h3>

    <hr size="3" color="yellow" />

    <p align="justify">
      <font face="Georgia" size="5">

        Ponni Amman Temple in Porur is a revered shrine dedicated to 
        Goddess Ponni Amman, believed to be a powerful guardian deity. 
        The temple holds deep spiritual significance, attracting devotees 
        seeking protection, health, and prosperity. Ponni Amman, 
        a manifestation of Shakti, is worshipped for her fierce energy 
        and motherly grace. Devotees believe she grants boons and wards off evil. 
        The temple's serene atmosphere and ancient traditions create a divine aura, 
        making it a cherished spiritual destination in Chennai.
        
      </font>
    </p>
  </body>
</html>


Trends.html

<html>
  <head>
    <title>TRENDS SHOP</title>
  </head>
  <body bgcolor="yellow">
    <h1 align="center">
      <font color="black"><b>VALASARAVAKKAM</b></font>
    </h1>

    <h3 align="center">
      <font color="blue"><b>TRENDS RELIANCE - GENZ DRESS SHOP</b></font>
    </h3>

    <hr size="3" color="red" />

    <p align="justify">
      <font face="Georgia" size="5">


        Trends Valasaravakkam, a bustling suburb in Chennai, is witnessing a surge in Gen Z fashion trends. 
        Youngsters here are embracing sustainable choices like thrifting and upcycling, 
        blending traditional Indian motifs with modern silhouettes. Local stores, 
        such as GenZ The Clothing Store, cater to this demand by offering 
        electric styles from oversized tees and wide-leg denim to Indo-Western fusion wear. 
        This fashion-forward community reflects Gen Z's commitment to individuality, cultural fusion, 
        and eco-conscious living.

        
      </font>
    </p>
  </body>
</html>


## OUTPUT

![Screenshot 2025-05-07 154950](https://github.com/user-attachments/assets/65daa5b1-dce2-4afd-bd06-432d09f4c531)


![Screenshot 2025-05-13 202551](https://github.com/user-attachments/assets/e5f5e607-4812-4b52-ac26-49f21eb7b02b)

![Screenshot 2025-05-13 202604](https://github.com/user-attachments/assets/92acb9d8-0465-4379-b450-a18a09730028)

![Screenshot 2025-05-13 202618](https://github.com/user-attachments/assets/60dd7c6e-e243-4b3e-8ae9-73880bae5df3)

![Screenshot 2025-05-13 202633](https://github.com/user-attachments/assets/c694862f-98c3-4ceb-8300-62bbe3b9dc32)

![Screenshot 2025-05-13 202644](https://github.com/user-attachments/assets/ff46853b-0d6d-4110-abeb-c7d2f5577be0)


## RESULT
The program for implementing image maps using HTML is executed successfully.

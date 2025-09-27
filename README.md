# Ex04 Places Around Me
## Date: 27.09.2025

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
    <head>
        <title>My City</title>
    </head>
<body>
<h1 align="center" style="color:brown">COIMBATORE</h1>
<h3 align="center" style="color:brown">KRITHIKA V - 25017598</h3>
<img src="Screenshot (786).png"  usemap="#image-map">
<map name="image-map">
    <area target="" alt="International Aiport" title="International Aiport" href="airport.html" coords="1529,5,1681,96" shape="rect">
    <area target="" alt="Gandhi Park" title="Gandhi Park" href="park.html" coords="717,252,854,321" shape="rect">
    <area target="" alt="Botanical Garden" title="Botanical Garden" href="garden.html" coords="674,176,62" shape="circle">
    <area target="" alt="Sri Krishna college" title="Sri Krishna college" href="college.html" coords="927,754,1013,732,1090,766,1044,851,942,852" shape="poly">
    <area target="" alt="Perur Temple" title="Perur Temple" href="temple.html" coords="542,503,72" shape="circle">
</map>
</body>
</html>

airport.html

<html>
    <head>>
        <title>Airport</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">COIMBATORE</h1>
        <h3 align="center">COIMBATORE INTERNATIONAL AIRPORT</h3>
        <hr>
        <p>Coimbatore International Airport (IATA: CJB, ICAO: VOCB) is an international airport and the primary airport serving the Coimbatore Metropolitan Area in Tamil Nadu, India.[6] It is located in the neighborhood of Peelamedu, about 10 km (6.2 mi) from the center of the city. It is the second-busiest airport in the state by passengers handled, aircraft movements, and freight handled after Chennai International Airport.[3][4][5] The airport is served by four carriers providing direct connectivity to thirteen domestic and three international destinations.</p>
    </body>
</html>

college.html

<html>
    <head>>
        <title>Airport</title>
    </head>
    <body bgcolor="pink">
         <h1 align="center">COIMBATORE </h1>
        <h3 align="center">SRI KRISHNA COLLEGE</h3>
        <hr>
        <p> Sri Krishna College of Engineering and Technology is the most sought after Institution among the premier technical Institutions in South India. Since its establishment in the year 1998, the Institution has marched towards the pinnacle of glory through its remarkable achievements in the field of Engineering Education. It is an Autonomous Institution, Affiliated to Anna University with 7 programmes being accredited by NBA and it offers 11 UG programmes, 4 PG programmes, 1 integrated programme and 8 research programmes. The Institution offers an exciting academic environment with well qualified dedicated faculty members to inspire and nurture the student fraternity. With industry drafted Choice Based Credit System (CBCS) curriculum and syllabi, the Institution takes every effort to bring its students to the forefront of the society as skillful and responsible engineers.</p>
    </body>
</html>

garden.html

<html>
    <head>>
        <title>Garden</title>
    </head>
    <body bgcolor="pink">
         <h1 align="center">COIMBATORE </h1>
        <h3 align="center">BOTANICAL GARDEN</h3>
        <hr>
        <p>At a distance of 2 km from Gass Forest Museum, and 5 km from Coimbatore Junction, the TNAU Botany Garden is a well-maintained garden situated in Coimbatore, Tamil Nadu, India. Located on Marudhamalai Road, it is one of the popular places to visit in Coimbatore.

Established in 1925, the TNAU Botanical Garden is located on the premises of Tamil Nadu Agricultural University in Coimbatore. The garden is spread over an area of about 300 acres of land. There are so many varieties of plants and trees in its vicinity, and each species is labeled with its common name as well as scientific name. People visit this place to gain more knowledge about the plants like herbs and shrubs.

Visitors can witness a large variety of roses, marigolds, carnations, chrysanthemums, and lilies at the TNAU Botanical Garden. The garden is also equipped with various incubators for growing non-seasonal plants. The garden also maintains a nursery where one can know the techniques of plant growing like plant husbandry, organic pesticides, etc. The lush green surroundings also serve as a spot for spending leisure time. Within the premises is also the TNAU Insect Museum where visitors will find a collection of interesting pests, rocks, and insects. The garden is also the venue for the flower show in January which attracts a huge number of tourists.</p>
    </body>
</html>

park.html

<html>
    <head>>
        <title>Park</title>
    </head>
    <body bgcolor="pink">
         <h1 align="center">COIMBATORE </h1>
        <h3 align="center">GANDHI PARK</h3>
        <hr>
        <p>Gandhi Park in Coimbatore is a popular green space known for its natural scenery, trees, and sculptures, offering visitors a place for morning walks, children's play, relaxation, and meditation. It is an excellent spot to enjoy the outdoors and nature within the city, making it a worthwhile destination for both locals and tourists. </p>
    </body>
</html>

temple.html

<html>
    <head>>
        <title>Temple</title>
    </head>
    <body bgcolor="pink">
         <h1 align="center">COIMBATORE </h1>
        <h3 align="center">PERUR TEMPLE</h3>
        <hr>
        <p>The Arulmigu Patteeswarar Swamy Temple, is a spiritually and historically significant temple, situated in the town of Perur, merely 9 kilometres from Coimbatore. Devoted to Lord Pateeswarar the temple was established by the famed Chola king, Karikaala Chola and is said to date back to the 2nd Century CE. This remarkable temple exemplifies the excellence of Dravidian architectural style, showcasing elaborate ornamentation. Its pillars and halls are embellished with meticulous carvings and sculptures. It is widely celebrated for its awe-inspiring depiction of its main deity, Lord Natraja, an avatar of Lord Shiva.</p>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (790).png>)
![alt text](<Screenshot (791).png>)
![alt text](<Screenshot (792).png>)
![alt text](<Screenshot (793).png>)
![alt text](<Screenshot (794).png>)
![alt text](<Screenshot (795).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

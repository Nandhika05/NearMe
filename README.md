# Ex04 Places Around Me
## Date: 02/04/2024

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
# map.html
<html>
    <head>
    <title>Mycity</title>
    </head>
    <body bgcolor="white">
        <h1 align="center">
        <font color="black"><b>Kanchipuram</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Nandhika P (212223040125)</b></font>
        </h3>
        <center>
            <img src="map.png"  usemap="#MyCity" height="600" width="1400">
            <map name="MyCity">
                    <area shape="rect" coords="360,230,450,280" href="office.html" title="collector office">     
                    <area shape="rect" coords="800,280,900,400" href="Hotal.html" title="Hotal Classic">
                    <area shape="rect" coords="420,630,520,670" href="Movie.html" title="Babu cinemas">
                    <area shape="rect" coords="1200,300,920,350" href='Temple.html" title="Sri Varadharaja Perumal temple">
                    <area shape="rect" coords="750,280,790,360" href="school.html" title="SVM school">
            </map>
        </center>
       

    </body>
</html>

#office.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Kanchipurm</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">Collector office</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Kanchipuram district is one of the 38 districts in the state of Tamil Nadu in India.<br>
            The area comprising the present day Kancheepuram district was earlier a part of Chingleput district.<br>
             The original Chingleput district was split in 1997 into form the present day Kanchiepuram.
        </p>
    </body>
</html>

#hotal.html

<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Kanchipurm</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">Hotal classic</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
              Hotel Classic Kanchipuram is situated in Kanchipuram, within 48 km of Arignar Anna Zoological Park and 50 km of Queens Land.
            With a terrace, the 3-star hotel has air-conditioned rooms with free WiFi, each with a private bathroom.
            The accommodation features room service, a 24-hour front desk and currency exchange for guests.
            At the hotel, the rooms are equipped with a desk and a flat-screen TV. At Hotel Classic Kanchipuram rooms are equipped with bed linen and towels.
            Maraimalai Nagar is 35 km from the accommodation, while Chengalpattu Railway Station is 38 km from the property. 
            The nearest airport is Chennai International Airport, 62 km from Hotel Classic Kanchipuram.
    
        </p>
    </body>
</html>

#movie.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Kanchipurm</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">Babu cinemas</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Babu Theatre - Pillaiyar Palayam is a popular theatre located at Madam Thottam Street, Near Venkateswara Thirumana Mandapam, Pillaiyar Palayam, Central, Kanchipuram. 
            Babu Theatre - Pillaiyar Palayam has 3 screens. Movies now showing at Babu Theatre - Pillaiyar Palayam are NONE. 
            Facilities available at Babu Theatre - Pillaiyar Palayam are Parking Facility.In this theatre, totally there are three theatres are available namely babu main, mini and paradise. 
            Out of these babu main has such an awesome sound effect, big screen and attractive light settings. Other two are also looking good but the surface is small compare to the main theatre. Here very big parking spot is available.
    
        </p>
    </body>
</html>

# temple.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Kanchipurm</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">Sri Varadharaja perumal temple</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Varadharaja Perumal Temple, also called Hastagiri and Attiyuran, is a Hindu temple dedicated to Vishnu located in the city of Kanchipuram, Tamil Nadu, India. It is one of the Divya Desams, the 108 temples of Vishnu believed to have been visited by the 12 poet saints, or the Alvars.
            It is located in a suburb of Kanchipuram known as the Vishnu Kanchi that is a home for many famous Vishnu temples. One of the greatest Hindu scholars of Vaishnava Vishishtadvaita philosophy, Ramanuja, is believed to have resided in this temple.The temple has around 350 inscriptions from various dynasties like Chola, Pandya, Kandavarayas, Cheras, Kakatiya, Sambuvaraya, Hoysala and Vijayanagara indicating various donations to the temple and also the political situation of Kanchipuram. Varadharaja Perumal Temple was renovated by the Cholas in 1053 and it was expanded during the reigns of the great Chola kings Kulottunga Chola I and Vikrama Chola. In the 14th century another wall and a gopura was built by the later Chola kings. When a Mughul invasion was expected in 1688, the main image of the deity was sent to Udayarpalayam, now part of Tiruchirappalli district. It was brought back with greater difficulty after the involvement of local preceptor who enlisted the services of general Todarmal.Robert Clive, the British general during the colonial period visited the Garuda seva festival and presented a valuable necklace (now termed Clive Maharkandi), which is adorned during a special occasion every year. At present the administration is carried out by Hindu Religious and Endowment of the Government of Tamil Nadu.
        </p>
    </body>
</html>

# school.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">Kanchipurm</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="blue" size="5.5">SVM school</font>
    </h3>
    <body bgcolor="grey" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            SVM Higher Secondary School was established on 17th June 2009 and is an English medium co-educational institution. This school is managed by highly reputed Trust with well qualified & experienced teaching staff. Read More. 500+ Students. 40+ Teachers. 1+ Campus. 5+ Facility. Our Philosophy revolves around believing every child is unique and gifted in our school we help childrens to understand their strengths and we appreciate their talents by providing a conductive and holistic environment coupled with innovative projects and funfield activities. Vision With love for the children and a passion for creating a community of cherished and emotionally intelligent and life long learness , We support our students with learning by helping to lay a solid educational and cultural foundation.
        </p>
    </body>
</html>
```
## OUTPUT
![map](https://github.com/Nandhika05/NearMe/assets/154419402/bc50c9d7-d6b5-4e6b-b5e2-b062ede10ebf)

![Screenshot 2024-04-02 133049](https://github.com/Nandhika05/NearMe/assets/154419402/56a06b4b-685c-44b4-ab5f-19a99fad3f1f)

![Screenshot 2024-04-02 132751](https://github.com/Nandhika05/NearMe/assets/154419402/218e955a-cfab-45a8-a71c-433013723ab5)

![Screenshot 2024-04-02 132944](https://github.com/Nandhika05/NearMe/assets/154419402/9406f388-b1af-49d8-8fd1-0267b1e962ff)

![Screenshot 2024-04-02 133206](https://github.com/Nandhika05/NearMe/assets/154419402/1b94071c-27a0-4715-a06d-08e32375d480)

![Screenshot 2024-04-02 133257](https://github.com/Nandhika05/NearMe/assets/154419402/40d6a702-1102-4ced-8365-360c28feab05)

## RESULT
The program for implementing image maps using HTML is executed successfully.

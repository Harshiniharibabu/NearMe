# Ex03 Places Around Me
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
## map.html
````
<html>
    <head>
        <title>
            MY PLACE
        </title>
    </head>
    <BODY>
        <h1 aligN="center">Madhavaram </h1>
        <h3 aligN="center">Harshini</h3>
        <img src="C:\Users\cseha\EX3-imagemap\Map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Botanical Garden" title="Botanical Garden" href="garden.html" coords="1108,414,1218,494" shape="rect">
    <area target="" alt="Velammal School" title="Velammal School" href="school.html" coords="440,412,681,529" shape="rect">
    <area target="" alt="Meridian Hospital" title="Meridian Hospital" href="hospital.html" coords="608,590,798,673" shape="rect">
    <area target="" alt="Puzhal Lake" title="Puzhal Lake" href="lake.html" coords="539,277,650,345" shape="rect">
    <area target="" alt="Madhavaram boat house " title="Madhavaram boat house " href="boat.html" coords="1070,147,1319,277" shape="rect">
</map>
    </BODY>
    
</html>
````

## garden.html
````
<html>
    <head>
        <title>
            Botanical garden
        </title>
        <style>
            .box{
                background-color: palegreen;
                width: 1000px;
                height: 500px;
                margin: auto;
                padding: 20px;
                border-radius: 20px;
            }
            h1{
                text-align: center;
            }
            img{
                display: block;
                margin: auto;
            }
            p{
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <h1>Botanical garden</h1>
            <img src="C:\Users\cseha\EX3-imagemap\Botanical Garden.png" width="250">
            <p>
                Madhavaram Botanical Garden is a botanical garden in Chennai, India, set up by the horticulture department of the Government of Tamil Nadu. The garden, the second botanical garden in Chennai after the Semmozhi Poonga, is the largest botanical garden in the city. 
            </p>
        </div>
    </body>
</html>  
````

## school.html
````
<html>
    <head>
        <title>
            Velammal school
        </title>
        <style>
            .box{
                background-color: lightgray;
                width: 1000px;
                height: 500px;
                margin: auto;
                padding: 20px;
                border-radius: 20px;
            }
            h1{
                text-align: center;
            }
            img{
                display: block;
                margin: auto;
            }
            p{
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <h1>Velammal School</h1>
            <img src="C:\Users\cseha\EX3-imagemap\School.jpg" width="250">
            <p>
                Velammal Matriculation Higher Secondary School in Surapet, Chennai, is a premier co-educational day school known for its rigorous academics and holistic development. Operating under the Velammal Educational Trust, it offers a State Board curriculum from Pre-Nursery to Class 12, featuring modern infrastructure, smart classes, and strong extracurricular programs.  
            </p>
        </div>
    </body>
</html>   
````

## hospital.html
````
<html>
    <head>
        <title>
            Meridian hospital
        </title>
        <style>
            .box{
                background-color: blanchedalmond;
                width: 1000px;
                height: 500px;
                margin: auto;
                padding: 20px;
                border-radius: 20px;
            }
            h1{
                text-align: center;
            }
            img{
                display: block;
                margin: auto;
            }
            p{
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <h1>Meridian hospital</h1>
            <img src="C:\Users\cseha\EX3-imagemap\Hospital.png" width="250">
            <p>
                Meridian Hospital in  North Chennai, is a 300-bed, ultra-modern multi-super specialty tertiary care facility. Combining advanced medical technology with compassionate care, it offers 24/7 emergency services, specialized diagnostic imaging, and comprehensive healthcare services ranging from routine check-ups to complex surgeries.  
            </p>
        </div>
    </body>
</html> 
````

## lake.html
````
<html>
    <head>
        <title>
            Puzhal Lake
        </title>
        <style>
            .box{
                background-color: pink;
                width: 1000px;
                height: 500px;
                margin: auto;
                padding: 20px;
                border-radius: 20px;
            }
            h1{
                text-align: center;
            }
            img{
                display: block;
                margin: auto;
            }
            p{
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <h1>Puzhal Lake</h1>
            <img src="C:\Users\cseha\EX3-imagemap\Puzhal lake.jpg" width="250">
            <p>
                Puzhal Lake is a sprawling 4,500-acre rain-fed reservoir in Chennai's northwestern suburbs. Constructed in 1876, it is a primary drinking water lifeline for Chennai and a serene getaway offering scenic sunrise and sunset views.   
            </p>
        </div>
    </body>
</html>   
````

## boat.html
````
<html>
    <head>
        <title>
            Madhavaram boat house 
        </title>
        <style>
            .box{
                background-color: beige;
                width: 1000px;
                height: 600px;
                margin: auto;
                padding: 20px;
                border-radius: 20px;
            }
            h1{
                text-align: center;
            }
            img{
                display: block;
                margin: auto;
            }
            p{
                text-align: center;
            }
        </style>
    </head>
    <body>
        <div class="box">
            <h1>Madhavaram boat house</h1>
            <img src="C:\Users\cseha\EX3-imagemap\Boat House.png" width="250">
            <p>
                The Madhavaram Boat House is a newly opened recreational spot located in North Chennai. It features boating (including motorboats and jet skis), beautifully landscaped walking tracks, children's play areas, food stalls, and clean restrooms. It is a revitalized 66-acre lake that serves as an active getaway in the area. 
            </p>
        </div>
    </body>
</html>   
````

## OUTPUT
![image](<Screenshot 2026-05-22 234527-1.png>)

![image1](<Screenshot 2026-05-22 234549.png>)

![image2](<Screenshot 2026-05-22 234612.png>)


![image3](<Screenshot 2026-05-22 234635.png>)


![image4](<Screenshot 2026-05-22 234700.png>)


![image5](<Screenshot 2026-05-22 234719.png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.

# Ex04 Places Around Me
## Date: 10/12/2025

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
```
<!DOCTYPE html>
<html>
<head>
    <title>My City</title>
</head>
<body>
<h1 align="center">
    <font color="red"><b>PRODDATUR</b></font>
</h1>
<h3 align="center">
    <font color="blue"><b>RAGA SUSANTH (212224230217)</b></font>
</h3>
<center>
    <img src="image1.png" usemap="#MyCity" height="610" width="1450">
    <map name="MyCity">
        <area shape="rect" coords="640,250,950,450" href="home.html" title="My Home Town - Proddatur">
        <area shape="circle" coords="458,415,40" href="temple.html" title="Mukthi Rameswaram Temple">
        <area shape="circle" coords="160,401,45" href="river.html" title="Penna River Flow">
        <area shape="circle" coords="237,130,45" href="garden.html" title="Kothapeta Area">
        <area shape="circle" coords="1012,484,45" href="home.html" title="Proddatur Auto Nagar">
        <area shape="circle" coords="668,528,45" href="park.html" title="Rajiv Gandhi National Park">
    </map>
</center>
</body>
</html>
```
## home.html
```
<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center"><font color="red"><b>Proddatur</b></font></h1>
    <h3 align="center"><font color="blue"><b>The Gold City of Andhra Pradesh</b></font></h3>
    <hr size="2" color="red">

    <center>
        <table width="80%">
            <tr>
                <td>
                    <font face="Georgia" size="5">
                        <ul>
                            <li>Proddatur is located on the banks of the Penna River in Kadapa District, Andhra Pradesh.</li>
                            <li>It is popularly known as the <b>"Second Bombay"</b> because of its gold and cotton business.</li>
                            <li>The city is a major hub for <b>education, trade, and culture</b> in the region.</li>
                            <li>Proddatur is famous for its <b>festivals, vibrant markets,</b> and <b>strong community life.</b></li>
                            <li>It also serves as a key center for <b>technology, manufacturing,</b> and <b>industry.</b></li>
                        </ul>
                    </font>
                </td>
            </tr>
        </table>
    </center>

    <center>
        <img src="image2.png" usemap="#MyCity" width="20%" alt="Proddatur Map">
    </center>
</body>
</html>
```

## garden.html
```
<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center"><font color="red"><b>Kothapeta</b></font></h1>
    <h3 align="center"><font color="blue"><b>Peaceful Residential & Garden Area</b></font></h3>
    <hr size="2" color="red">

    <center>
        <table width="80%">
            <tr>
                <td>
                    <font face="Georgia" size="5">
                        <ul>
                            <li>Kothapeta is a calm and green locality in the western part of Proddatur.</li>
                            <li>It is known for its <b>gardens, schools, and family-friendly environment.</b></li>
                            <li>The area is close to the <b>Penna River</b>, offering fresh air and scenic views.</li>
                            <li>Many people prefer living here due to its <b>peaceful surroundings.</b></li>
                            <li>Kothapeta represents the <b>green and healthy lifestyle</b> of Proddatur.</li>
                        </ul>
                    </font>
                </td>
            </tr>
        </table>
    </center>

    <center>
        <img src="image3.avif" width="50%" alt="Kothapeta Area Map">
    </center>
</body>
</html>
```
## temple.html
```
<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center"><font color="red"><b>Sri Lakshmi Narasimha Swamy Temple</b></font></h1>
    <h3 align="center"><font color="blue"><b>The Spiritual Heart of Proddatur</b></font></h3>
    <hr size="2" color="red">

    <center>
        <table width="80%">
            <tr>
                <td>
                    <font face="Georgia" size="5">
                        <ul>
                            <li>The <b>Sri Lakshmi Narasimha Swamy Temple</b> is one of the oldest and most sacred temples in Proddatur.</li>
                            <li>It is dedicated to <b>Lord Narasimha</b>, an incarnation of Lord Vishnu known for protecting devotees from evil.</li>
                            <li>The temple features stunning <b>Dravidian architecture</b> with tall gopurams and detailed carvings.</li>
                            <li>Every year, thousands of devotees visit during festivals like <b>Brahmotsavam</b> and <b>Narasimha Jayanthi</b>.</li>
                            <li>The peaceful surroundings and rich history make it a center of <b>faith, devotion, and cultural heritage.</b></li>
                        </ul>
                    </font>
                </td>
            </tr>
        </table>
    </center>

    <center>
        <img src="image4.jpg" width="60%" alt="Sri Lakshmi Narasimha Swamy Temple">
    </center>
</body>
</html>
```
## park.html
```
<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center"><font color="red"><b>Rajiv Gandhi National Park</b></font></h1>
    <h3 align="center"><font color="blue"><b>The Green Heart of Proddatur</b></font></h3>
    <hr size="2" color="red">

    <center>
        <table width="80%">
            <tr>
                <td>
                    <font face="Georgia" size="5">
                        <ul>
                            <li>The Rajiv Gandhi National Park is a major <b>recreational and nature spot</b> in Proddatur.</li>
                            <li>It is filled with <b>trees, walking paths,</b> and <b>picnic areas.</b></li>
                            <li>Families visit here for <b>morning walks and outdoor activities.</b></li>
                            <li>The park helps maintain the <b>green balance</b> of the city.</li>
                            <li>It is a symbol of <b>environmental awareness</b> and public enjoyment.</li>
                        </ul>
                    </font>
                </td>
            </tr>
        </table>
    </center>

    <center>
        <img src="image5.avif" width="40%" alt="Rajiv Gandhi Park Map">
    </center>
</body>
</html>
```
## river.html
```
<html>
<head>
    <title>My Home Town</title>
</head>
<body bgcolor="lime">
    <h1 align="center"><font color="red"><b>Pennar River</b></font></h1>
    <h3 align="center"><font color="blue"><b>The Lifeline of Proddatur</b></font></h3>
    <hr size="2" color="red">

    <center>
        <table width="80%">
            <tr>
                <td>
                    <font face="Georgia" size="5">
                        <ul>
                            <li>The Pennar River flows beautifully near Proddatur and Illuru village.</li>
                            <li>It provides <b>water for agriculture, irrigation,</b> and <b>daily needs.</b></li>
                            <li>The riverside is a <b>popular picnic and relaxation spot.</b></li>
                            <li>During the monsoon, the river adds charm to the town’s beauty.</li>
                            <li>It is truly the <b>lifeline of Proddatur</b> and nearby areas.</li>
                        </ul>
                    </font>
                </td>
            </tr>
        </table>
    </center>

    <center>
        <img src="image6.jpg" width="80%" alt="Pennar River Map">
    </center>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2025-11-12 140244.png>)
![alt text](<Screenshot 2025-11-12 115132.png>)
![alt text](<Screenshot 2025-11-12 115103.png>)
![alt text](<Screenshot 2025-11-12 115022.png>)
![alt text](<Screenshot 2025-11-12 114732.png>)
![alt text](<Screenshot 2025-11-12 114657.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.

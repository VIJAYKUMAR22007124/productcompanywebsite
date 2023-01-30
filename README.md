# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### styles.css
```css
.home {
    height: 700px;
    width: 85%;
    border: 12px solid green;
    padding-left: 10px;
    padding-right: 10px;
    margin-left: auto;
    margin-right: auto;
    background-color: lightgray;
}

.content {
    border: 1px solid whitesmoke;
    background-color: greenyellow;
    width: 95%;
    height: 1190px;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;
}

.header {
    height: 128px;
    width: 100%;
    background-image: url(black_noun_002_03536.jpg);
    background-size: header;

}

.logo {
    height: 5%;
    width: 10%;
    position: absolute;
    background-image: url(Bugatti-logo-1024x768.png);
    background-size: absolute;

}

.prod {
    height: auto;
    width: auto;
    position: relative;
    bottom: 10px;
    left: 550px;
    border: 4px solid transparent;
    text-align: center;
    display: inline;
    padding: 15px;
    font-family: 'Gill Sans MT';
    font-size: large;
}

.prod:hover {
    background-color: blue;
}

.people {
    height: auto;
    width: auto;
    position: relative;
    bottom: 10px;
    left: 700px;
    border: 4px solid transparent;
    text-align: center;
    display: inline;
    padding: 15px;
    font-family: 'Gill Sans MT';
    font-size: large;
}

.people:hover {
    background-color: blue;
}

.contact {
    height: 20px;
    width: 10%;
    position: relative;
    bottom: 45px;
    left: 1000px;
    border: 4px solid transparent;
    text-align: center;
    padding: 15px;
    font-family: 'Gill Sans MT';
    font-size: large;
}

.contact:hover {
    background-color: blue;
}

.h {
    height: 20px;
    width: 10%;
    position: relative;
    top: 30px;
    left: 200px;
    border: 4px solid transparent;
    text-align: center;

    padding: 15px;
    font-family: 'Gill Sans MT';
    font-size: large;
}

.h:hover {
    background-color: blue;
    overflow: hidden;
}

.footer {
    border: 15px solid lightgreen;
    width: 98%;
    height: 10px;
    position: relative;
    bottom: 1px;
    background-color: lightgreen;
    text-align: center;

}

.title {
    border: 2px solid pink;
    background-color: yellow;
    padding: 1px;
    width: 99.7%;
    height: 70px;
    text-align: center;
    font-family: 'Impact';
    margin-left: auto;
    margin-right: auto;

}

.content {
    border: 1px solid red;
    background-color: white;
    width: 98%;
    height: 400px;
    padding: 10px;
    margin-left: auto;
    margin-right: auto;

}
```
### home.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        Home Page
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        .text {
            color: blueviolet;
            font-family: 'Lucida Sans';
            font-size: 30px;
            text-align: center;
        }

        img {
            height: 150px;
            width: 150px;
            align-items: center;
        }
    </style>

</head>

<body>
    <div class="home">
        <div class="header">
            <header>
                <div class=logo></div>
                <div class=h>
                    <a href="home.html" title="Home" style="color:blue; text-decoration: none;"><b>Home</b></a>
                </div>
                <div class="prod">
                    <a href="products.html" title="Products"
                        style="color:blue; text-decoration: none;"><b>Products</b></a>
                </div>
                <div class="people">
                    <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                </div>
                <div class="contact">
                    <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact
                            Us</b></a>
                </div>
            </header>
            <div class="title">
                <center>
                    <h1>Bugatti</h1>
                </center>

            </div><br>
            <div class="content">
                <div class="text">
                    <marquee><b>If it is comparable, it is no longer Bugatti.</b></marquee>
                    <p style="color:purple; font-family:'Tahoma'; font-size:20px;">This is the official website of
                        Bugatti.</p>
                </div>
                <center>
                    <h3>Buy the latest Bugatti</h3> <br>
                </center>
                <center>
                    <img src="centodieci.jpg" height="250" width="250">
                    <img src="chironsport300.jpg" height="250" width="250">
                    <img src="lavoiturenoire.jpg" height="250" width="250">
                    <img src="divo.jpg" height="250" width="250">
                    <img src="chironsport.jpg" height="250" width="250">
                </center>
            </div>
            <div class="footer">
                <footer style="color:black">
                    Copyright &copy;2023 Developed by Doogle cc</footer>
            </div>
        </div>
    </div>
</body>

</html>
```
### products.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        Products
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        .home {
            height: 1555px;
            width: 85%;
            border: 12px solid green;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
            background-color: lightgray;
        }

        .text {
            color: blueviolet;
            font-family: 'Lucida Sans';
            font-size: 30px;
            text-align: center;

        }

        .content {
            border: 3px solid orange;
            background-color: beige;
            width: 98%;
            height: 1190px;
            padding: 10px;
            margin-left: auto;
            margin-right: auto;
        }

        .ph1 {
            background-image: url(centodieci.jpg);
            background-size: 500px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 1px solid white;
            height: 200px;
            width: 30%;
            position: relative;
            left: 80px;
        }

        .l1 {
            color: gold;
            position: relative;
            right: 380px;


        }

        .ph2 {
            background-image: url(chironsport300.jpg);
            background-size: 500px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 1px solid white;
            height: 200px;
            width: 30%;
            position: relative;
            left: 80px;

        }

        .l2 {
            color: sandybrown;
            position: relative;
            right: 380px;
        }

        .ph3 {
            background-image: url(lavoiturenoire.jpg);
            background-size: 500px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 1px solid white;
            height: 210px;
            width: 30%;
            position: relative;
            left: 80px;

        }

        .l3 {
            color: burlywood;
            position: relative;
            right: 380px;
        }

        .ph4 {
            background-image: url(divo.jpg);
            background-size: 500px;
            background-position-x: center;
            border: 1px solid white;
            height: 200px;
            width: 30%;
            position: relative;
            left: 730px;
            bottom: 930px;
            background-size: 190px;
            background-repeat: no-repeat;


        }

        .l4 {
            color: burlywood;
            position: relative;
            left: 270px;
            bottom: 930px;
        }

        .ph5 {
            background-image: url(chironsport.jpg);
            background-size: 500px;
            background-position-x: center;
            border: 1px solid white;
            height: 200px;
            width: 30%;
            position: relative;
            left: 730px;
            bottom: 930px;
            background-size: 250px;
            background-repeat: no-repeat;


        }

        .l5 {
            color: cadetblue;
            position: relative;
            left: 270px;
            bottom: 930px;
        }


        .bot {
            text-align: center;
            font-size: larger;
            color: black;

        }
    </style>
</head>

<body>
    <div class="home">
        <div class="header">
            <header>
                <div class=logo></div>
                <div class=h>
                    <a href="home.html" title="Home" style="color: white; text-decoration: none;"><b>Home</a>
                </div>
                <div class="prod">
                    <a href="products.html" title="Products"
                        style="color: white; text-decoration: none;"><b>Products</b></a>
                </div>
                <div class="people">
                    <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                </div>
                <div class="contact">
                    <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact
                            Us</b></a>
                </div>
            </header>
            <div class="title">
                <h1>Latest Models</h1>
            </div><br>
            <div class="content">
                <div class="text">
                    <p>Limited edition!!</p>
                </div>
                <div class="ph1"></div>
                <div class="l1">
                    <p align="center"><b>Bugatti Centodieci<br> </b><br><br><br><br></p>
                </div>
                <div class="ph2"></div>
                <div class="l2">
                    <p align="center"><b>Bugatti Chiron Sport300+<br> </b><br><br><br><br></p>
                </div>
                <div class="ph3"></div>
                <div class="l3">
                    <p align="center"><b>La Voiture Noire Bugatti<br></b>
                        <br<br><br><br>
                    </p>
                </div>
                <div class="ph4"></div>
                <div class="l4">
                    <p align="center"><b>Bugatti Divo<br></b><br><br><br><br></p>
                </div>
                <div class="ph5"></div>
                <div class="l5">
                    <p align="center"><b>Bugatti Chiron<br> </b><br><br><br><br></p>
                </div>

                <div class="bot">
                    <p>Pre-Registration Available for Bugatti Bolide</p>
                </div>

                <div class="footer">
                    <footer style="color:black">
                        Copyright &copy;2023 Developed by Doogle cc</footer>
                </div>
            </div>
        </div>
</body>

</html>
```
### people.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        People
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        .home {
            height: 3000px;
            width: 85%;
            border: 12px solid green;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
            background-color: lightgray;
        }

        .text {
            color: blueviolet;
            font-family: 'Lucida Sans';
            font-size: 30px;
            text-align: center;

        }

        .content {
            border: 2px solid green;
            background-color: beige;
            width: 98%;
            height: 2690px;
            padding: 10px;
            margin-left: auto;
            margin-right: auto;
        }

        .ceoph {
            background-image: url(chair.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 3px solid black;
            height: 300px;
            width: 20%;
            position: relative;
            left: 0px;
            margin-left: auto;
            margin-right: auto;
        }

        .ceo {
            color: red;
            position: relative;
            text-align: center;


        }

        .manph1 {
            background-image: url(chris.jpeg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 1px solid black;
            height: 300px;
            width: 20%;
            position: relative;
            margin-left: auto;
            margin-right: auto;
        }

        .man1 {
            color: red;
            position: relative;
            text-align: center;

        }

        .manph2 {
            background-image: url(stef.jpg);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border: 1px solid black;
            height: 300px;
            width: 20%;
            position: relative;
            margin-left: auto;
            margin-right: auto;


        }

        .man2 {
            color: red;
            position: relative;
            text-align: center;
        }
    </style>
</head>

<body>
    <div class="home">
        <div class="header">
            <header>
                <div class=logo></div>
                <div class=h>
                    <a href="home.html" title="Home" style="color:white; text-decoration: none;"><b>Home</b></a>
                </div>
                <div class="prod">
                    <a href="products.html" title="Products"
                        style="color: white; text-decoration: none;"><b>Products</b></a>
                </div>
                <div class="people">
                    <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                </div>
                <div class="contact">
                    <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact
                            Us</b></a>
                </div>
            </header>
            <div class="title">
                <h1>People</h1>
            </div><br>
            <div class="content">
                <div class="text">
                    <p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                </div>
                <div class="ceoph"></div>
                <div class="ceo">
                    <p align="center"><b>
                            <h2>Stephan Winkelmann</h2>
                        </b>
                </div>
                <br>
                <div class="text">
                    <p><b><u>Board of Directors</u></b></p><br>
                </div>
                <div class="manph1"></div>
                <div class="man1">
                    <p align="center"><b>
                            <h2>Christophe Piochon</h2>
                        </b></p>
                </div>
                <div class="manph2"></div>
                <div class="man2">
                    <p><b>
                            <h2>Stefan Ellrott,</h2>
                        </b></p>
                </div>
                <br>
                <div class="text">Faster than you could ever imagine!<br>OUI!</div>
            </div>
            <div class="footer">
                <footer style="color:black">
                    Copyright &copy;2023 Developed by Doogle cc</footer>
            </div>
        </div>
    </div>
</body>

</html>
```
### contacts.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>
        Contact Us
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        .text {
            color: blueviolet;
            font-family: 'Lucida Sans';
            font-size: 30px;
            text-align: center;
        }
    </style>

</head>

<body>
    <div class="home">
        <div class="header">
            <header>
                <div class=logo></div>
                <div class=h>
                    <a href="home.html" title="Home" style="color: white; text-decoration: none;"><b>Home</b></a>
                </div>
                <div class="prod">
                    <a href="products.html" title="Products"
                        style="color: white; text-decoration: none;"><b>Products</b></a>
                </div>
                <div class="people">
                    <a href="people.html" title="People" style="color:white; text-decoration: none;"><b>People</b></a>
                </div>
                <div class="contact">
                    <a href="contact.html" title="Contact Us" style="color:white; text-decoration: none;"><b>Contact
                            Us</b></a>
                </div>
            </header>
            <div class="title">
                <h1>LET'S COMMUNICATE!!</h1>
            </div><br>
            <div class="content">
                <div class="text">
                    <p><b>
                            <h5>CONTACT US</h5>
                        </b></p>

                </div>
                <b>
                    <h2>Contact Information:</h2>
                </b>
                <p><b>&emsp;&ensp;Address:</b>
                    BUGATTI AUTOMOBILES SAS , 1 Château St. Jean, 67120 Molsheim, France.
                </p>
                <ul>
                    <li><b>Landline:</b> +33 22 52 47 89</li>
                    <li><b>Mobile</b>+33 21 66 55 77</li>
                    <li><b>Facebook</b>lesbugatis</li>
                    <li><b>Email Id:</b>bugattiofficial@gmail.com</li>
                </ul>
                <div style="text-align: center;color:violet;font-size:20px;"><b>Do visit us!</b></div>

            </div>
            <div class="footer">
                <footer style="color:black">
                    &copy; 023 BUGATTI AUTOMOBILES S.A.S.</footer>
            </div>
        </div>
    </div>
</body>

</html>
```

## OUTPUT:

![image](./Screenshot%20from%202023-01-29%2021-03-27.png)
![image](./Screenshot%20from%202023-01-29%2021-03-42.png)
![image](./Screenshot%20from%202023-01-29%2021-03-53.png)
![image](./Screenshot%20from%202023-01-29%2021-03-59.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

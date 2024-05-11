# Ex.07 Software Product Company Website
## Date: 24.04.2024
## AIM:
To develop a static company website to display the softwares and services provided by the company.
## DESIGN STEPS:
Step 1:Requirement collection.

Step 2: Creating the layout using HTML and CSS.

Step 3: Updating the sample content.

Step 4: Choose the appropriate style and color scheme.

Step 5: Validate the layout in various browsers.

Step 6: Validate the HTML code.

Step 7: Publish the website in the given URL.
## PROGRAM:
## home.html
~~~
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh ;
                background-size: cover;
                background-position: center;
             .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
~~~
~~~
            }.logo {
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
           footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
            <div class="navbar">
            <h1 class="logo">C<span>ode</span>V<span>erse</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2>InnovateSoft Solutions </h2>
                <br>
                <p> Transforming Ideas into Impartful Reality through Precision Coding and Innovation </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by Niranjana devi S (212221220036) </center>
    </footer>
</body>
</html>
## Product.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
            }
            span {
                color: white;
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: white;
            } .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }.container .box-container {
                display: grid;
                grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
                gap: 20px;
            }footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>V<span>erse</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="python.jpeg" alt="">
                    <h3>Python</h3>
                    <p>Where simplicity meets power in the world of programming.</p>
                </div>
              <div class="box">
                    <img src="ruby.png" alt="">
                    <h3>RUBY</h3>
                    <p> open source programming language with a focus on simplicity and productivity..</p>
                </div>
          </div>
    <footer>
        <center> Designed and Developed by Niranjana devi s (212221220036) </center>
    </footer>
</body>
</html>
## Person.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
        .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
        }.navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
          footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>V<span>erse</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                   <td> <img src="song.webp"> </td>
                    <td> <img src="iu.jpg"> </td>
                </tr>
                <tr align="center">
                    <th> Priyadharshini.P </th>
                    <th> Taehyung </th>
                    </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Dy. Director </td>
                </tr>
            </table>
        </div>
    <footer>
        <center> Designed and Developed by Niranjana devi S (212221220036) </center>
    </footer>
</body>
</html>
## Contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CodeCraft</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
                cursor: pointer;
            }height: 400px;
                width: 400px;
                border: 3px solid gold;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
           }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
            }
           .box-2 span {
                color: gold;
                font-size: 20px;
            }
            footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">C<span>ode</span>V<span>erse</span></h1>
            <ul>
                <li><a href="homepage.html"> Home </a></li>
                <li><a href="Products.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
              <p> <span>Phone</span> : 044 87536890 </p>
      </div>
    <footer>
        <center> Designed and Developed by Priyadharshini P (212223240128)</center>
    </footer>
</body>
</html>
~~~
## OUTPUT:
![image](https://github.com/niranjanadevi-s/softweb/assets/141748873/a752935f-eae1-43a0-8868-a0d9e11c5887)
![image](https://github.com/niranjanadevi-s/softweb/assets/141748873/807ac5fe-5e73-4de9-b773-7b375c7b0cab)
![image](https://github.com/niranjanadevi-s/softweb/assets/141748873/2e35f414-657d-4bfd-9b9d-b48676690988)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

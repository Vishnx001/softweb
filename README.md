# Ex.07 Software Product Company Website
## Date:06-05-2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
front.html


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>document</title>
    <style>
        h1 {
            color:rgb(214, 210, 234);
            font-size: 1px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-image: url("e.png");
            background-color:rgb(47, 136, 187);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color:rgb(20, 107, 17);

        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: lightblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: monospace;
            font-size: 60px;
            background-color:black;
        }

        footer {
            text-align: center;

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color:black;
            height: 19vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: white;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color:rgb(10, 58, 10);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: silver;
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: rgb(215, 249, 250);
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color: rgba(25, 23, 20, 0.6);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color: rgb(22, 165, 222);
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(248, 250, 250);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color:rgb(229, 229, 236);
            margin-left: 20px;
        }

        
        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
</head>

<body>
    <header>
        <h2>NexGen Software Solutions</h2>
    </header>
    <nav class="navbar">

        <ul>
            <li><a href="contact.html">Help</a></li>
            <li><a href="company.html">Products</a></li>
            <li><a href="members.html">People</a></li>
            <li><a href="front.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1>
        <div class="first">“Pioneering the next generation
            <br>  of software innovations”</div>
        <div class="second"> <br> </div>
        <div class="third"></div>
    </h1>
    <div class="d">
        <p> &nbsp;Innovate | Code | Expertise</p>
        <button id="joinus">Collab With Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Passcode"><br><br><br>
            <button>Login</button>
            <h4>Don't have an account</h4><br>
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <img src="what.png" width="25px">
                <img src="twitt.png" width="25px">
                <img src="tele.png" width="25px">
                <img src="insta.png" width="25px">
            </div>
        </form>
    </div>
    <footer>
        Designed and Developed by DIVYA DHARSHINI R &copy; 2024
    </footer>

</body>

</html>
```
```
members.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color:rgb(98, 166, 230);
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-image: url("bg.jpg");
        background-color:rgb(22, 89, 153);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:blac;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(208, 201, 201);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{
        text-align: center;

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:rgb(35, 30, 30);
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(30, 173, 49);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:5px;
        border-color:rgb(40, 36, 36);
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 40px;
        }
        .text{
            position:absolute;
            top:55%;
            margin-left: 5px;
            font-size: 26px;
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:10px;
            font-size: 20px;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>NexGen Software Solutions</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="company.html">Products</a></li>
        <li><a href="members.html">People</a></li>
        <li><a href="front.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="me.jpg" width="500px">
            <img class="small border" src="1.png" width="500px" >
            <img class="small border" src="2.jpeg" width="500px">
            <img class="small border" src="3.png" width="500px" >
            <img class="small border" src="4.jpeg" width="500px">
            <img class="small border" src="5.png" width="500px" >
        </div>
        <div class ="text">
            <table style="color:rgb(244, 242, 242);" cellpadding="75">
                <tr div class="head">
                    <th>Divya Raj </th>
                    <th>Jack</th>
                    <th>Pokemon</th>
                    <th>Himada</th>
                    <th>Rose</th>
                    <th>Shsheee</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table style="color:rgb(244, 242, 242);" cellpadding="80">
                <tr >
                    <td>Founder</td>
                    <td>         Co-Founder</td>
                    <td>CEO</td>
                    <td> Director</td>
                    <td>Asst.Director</td>
                    <td> Manager</td>
                </tr>
            </table>
        </div>
      
            <footer>
                Designed and Developed by DIVYA DHARSHINI R &copy; 2024
                </footer>
               
</body>
</html>

company.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color:black;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        
        background-color:rgb(26, 24, 24);
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:blac;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:black;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{
        text-align: center;

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:5px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 40px;
        }
        .text{
            position:absolute;
            top:55%;
            margin-left: 40px;
            font-size: 20px;
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>NexGen Software Solutions</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="company.html">Products</a></li>
        <li><a href="members.html">People</a></li>
        <li><a href="front.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            
    <div class="gallery">
       <a target="_blank" href="qwd.png">
         <img src="pr.jpg"  center" alt="Cinque Terre" width="1500" height="600">
       </a>
   </div>
        <div class="cirpic">
           
        </div>
        <div class ="text">
           
        </div>
        <div class="text2">
            
        </div>
      
            <footer>
                Designed and Developed by DIVYA DHARSHINI R &copy; 2024
                </footer>
               
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:30%;
        }
        body{
        background-image: url("abcde.png");
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:black;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:20px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{
        text-align: center;    

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:9px;
        margin-left:20px;
        }
        .search input{
            width:12%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color: black;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: rgb(250, 250, 250);
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 10px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:white;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        .vl{
            position:absolute;
            border-left: 3px solid darkblue;
            height: 440px;
            margin-left: 800px;
            top:40%;
        }
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:40%;
            font-size: 25px;
            background-color: white;
            padding:70px 250px 95px 147px ;
            margin-left: 800px;
        }
        .coform form{
            background-color: white;
            top:40%;
            margin-left: 0px;
            padding:0px 282px 50px 0px;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>NexGen Software Solutions</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Help</a></li>
            <li><a href="company.html">Products</a></li>
            <li><a href="members.html">People</a></li>
            <li><a href="front.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>

            
                <div class="line">
                    <hr color="darkblue">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Mobile number"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="12" cols="66" >any feedback
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Info</h3><br>
            <b>Address: </b>Mangadu ,chennai-600040<br><br>
            <b>Email: </b>nexgensoftwaresolutions@gmail.com<br><br>
            <b>Phone: </b>044-8610438038
        </div>
        <div class="vl"></div>
    </div>
                <footer>
                    Designed and Developed by DIVYA DHARSHINI R &copy; 2024
                    </footer>
                   
    </body>
    </html>


```

## OUTPUT:

![alt text](<Screenshot 2024-05-06 082955.png>)

![alt text](<Screenshot 2024-05-06 083016.png>)

![alt text](<Screenshot 2024-05-06 083034.png>)

![alt text](<Screenshot 2024-05-06 083111.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

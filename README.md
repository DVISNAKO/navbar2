This is second par of Navbar
<Br>
HTML CSS

![NavBar2 - Google Chrome 16 12 2022 13_48_17 (2)](https://user-images.githubusercontent.com/106438454/208093204-7bb22c2e-3eda-40a4-b4b0-c117f02cf89e.png)

<br>
<hr>
<!-- Hoverable Sidenav Buttons -->
    <h2 style="margin-left: 100px;">Hoverable Sidenav Buttons</h2>
    <br>

    <div id="mySidenav" class="sidenav">
        <a href="#" id="about">About</a>
        <a href="#" id="blog">Blog</a>
        <a href="#" id="projects">Project</a>
        <a href="#" id="contact">Contact</a>
    </div>

    <div style="margin-left: 100px;">
        <h2>Sidenav Buttons</h2>
        <p>Content</p>
    </div>
 <hr>
 
     <!-- Style CSS -->
    <style>
        #mySidenav a {
            position: absolute;
            left: -80px;
            transition: 0.3s;
            padding: 15px;
            width: 100px;
            text-decoration: none;
            font-size: 20px;
            color: whitesmoke;
            border-radius: 0 5px 5px 0;
        }

        #mySidenav a:hover {
            left: 0;
        }

        #about {
            top: 20px;
            background-color: #04AA6D;
        }

        #blog {
            top: 80px;
            background-color: #2196F3;
        }

        #projects {
            top: 140px;
            background-color: #da473c;
        }

        #contact {
            top: 200px;
            background-color: #555
        }
    </style>
    
<hr>
<br>
 ![NavBar2 - Google Chrome 16 12 2022 13_50_05 (2)](https://user-images.githubusercontent.com/106438454/208093668-c97c7e51-25dd-4ae7-b8fd-bccae6e40c22.png)

<br>
<hr>
<!-- Top Navigation with rigth link -->

    <div class="topnav">
        <a class="active" href="#home">Home</a>
        <a href="#news">News</a>
        <a href="contact">Contact</a>
        <div class="topnav-rigth">
            <a href="$search">Search</a>
            <a href="about">About</a>
        </div>
    </div>

    <div style="padding-left:16px">
        <h2>Top Navigation with Right Aligned Links</h2>
        <p>Content</p>
    </div>
    
 <hr>
 
  <!-- Style CSS -->

    <style>

        .topnav {
            overflow: hidden;
            background-color: #333;
        }

        .topnav a {
            float: left;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }

        .topnav a:hover {
            background-color: #ddd;
            color: black;
        }

        .topnav a.active {
            background-color: #04AA6D;
            color: whitesmoke;
        }

        .topnav-rigth {
            float: right;
        }
    </style>
 

<html>
    <head>
        <title>ABOUT ME</title>
        <link rel="stylesheet" href="project one.css"/>
    </head>
    <body>
        <div class="countainer">
        <!-- NAVIGATION BAR -->
        <div class="countainer-navbar">
            <ul class="ul-navbar">
                <li class="li-navbar">
                    <a href="index.html" class="a-navbar">HOME</a>
                </li>
                <li class="li-navbar">
                    <a href="about.html" class="a-navbar">ABOUT ME</a>
                </li>
                <li class="li-navbar">
                    <a href="contact.html" class="a-navbar">CONTACT ME</a>
                </li>
            </ul>
        </div>
        <!-- NAVIGATION BAR END -->

        <!-- CONTENT 1 -->
        <div class="countainer-content">
            <a href="https://www.instagram.com/hyniiff/" 
            class="a-content">
                <img src="Instagram.png" class="img-content"/>
                <p>KUNJUNGI HALAMAN INSTAGRAM AKU</p>
            </a>
            
        </div>
        <!-- CONTENT 1 END -->

        <!-- FOOTER -->
        <div class="countainer-footer">
            <h1 class="h1-footer">WEB INI DIBUAT UNTUK BELAJAR BERSAMA</h1>
        </div>
        <!-- FOOTER END -->
         </div>
    </body>
</html>
<html>
    <head>
        <title>CONTACT ME</title>
        <link rel="stylesheet" href="project one.css"/>
    </head>
    <body>
        <div class="countainer">
        <!-- NAVIGATION BAR -->
        <div class="countainer-navbar">
            <ul class="ul-navbar">
                <li class="li-navbar">
                    <a href="index.html" class="a-navbar">HOME</a>
                </li>
                <li class="li-navbar">
                    <a href="about.html" class="a-navbar">ABOUT ME</a>
                </li>
                <li class="li-navbar">
                    <a href="contact.html" class="a-navbar">CONTACT ME</a>
                </li>
            </ul>
        </div>
        <!-- NAVIGATION BAR END -->

        <!-- CONTENT 1 -->
        <div class="countainer-content">
            <a href="https://www.instagram.com/hyniiff/" 
            class="a-content">
                <img src="Instagram.png" class="img-content"/>
                <p>BISA HUBUNGI SAYA DISINI</p>
            </a>
            
        </div>
        <!-- CONTENT 1 END -->

        <!-- FOOTER -->
        <div class="countainer-footer">
            <h1 class="h1-footer">WEB INI DIBUAT UNTUK BELAJAR BERSAMA</h1>
        </div>
        <!-- FOOTER END -->
         </div>
    </body>
</html>
<html>
    <head>
        <title>PROJECT ONE</title>
        <link rel="stylesheet" href="project one.css"/>
    </head>
    <body>
        <div class="countainer">
        <!-- NAVIGATION BAR -->
        <div class="countainer-navbar">
            <ul class="ul-navbar">
                <li class="li-navbar">
                    <a href="#" class="a-navbar">HOME</a>
                </li>
                <li class="li-navbar">
                    <a href="about.html" class="a-navbar">ABOUT ME</a>
                </li>
                <li class="li-navbar">
                    <a href="contact.html" class="a-navbar">CONTACT ME</a>
                </li>
            </ul>
        </div>
        <!-- NAVIGATION BAR END -->

        <!-- CONTENT 1 -->
        <div class="countainer-content">
            <a href="https://www.youtube.com/@Abdul-hanif11" 
            class="a-content">
                <img src="Yt.jpg" class="img-content"/>
                <p>MAMPIR YUK KE YOUTUBE AKU</p>
            </a>
            
        </div>
        <!-- CONTENT 1 END -->

        <!-- FOOTER -->
        <div class="countainer-footer">
            <h1 class="h1-footer">WEB INI DIBUAT UNTUK BELAJAR BERSAMA</h1>
        </div>
        <!-- FOOTER END -->
         </div>
    </body>
</html>
*,
html{
padding: 0;
margin: 0;
}

.countainer-navbar{
    background-color: gray;
    width: 100%;
    height: 100px;
}

.ul-navbar{
display: flex;
height: 10vh;
justify-content: center;
align-items: center;
}

.li-navbar{
list-style-type: none;
padding: 20px;
margin: 5px;
font-size: 35px;
}

.li-navbar:hover{
    background-color: dimgray;
    transition: .4s ease-in-out;
    transition-delay: .2s;
    border-radius: 9px;
}

.a-navbar{
color: black;
text-decoration: none;
font-weight: 800;
}

.countainer-content{
background-color: darkgray;
display: flex;
justify-content: center;
align-items: center;
 height:80vh ;
}

.a-content{
    background-color: #fff;
    text-decoration: none;
    color: black;
    justify-content: space-evenly;
    align-items: center;
    display: flex;
    flex-direction: column;
    width: 720px;
    height:480px;
    font-weight: 800;
    border-radius: 100px;
    font-size: 30px;
    box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
    -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
    -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
}

.img-content{
width: 65%;
height: 65%;
}

.countainer-footer{
background-color: grey;
display: flex;
align-items: center;
justify-content: center;
height: 10vh;
}

.h1-footer{
font-size: 40px;
}


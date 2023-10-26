# Digital-portfolio
<!DOCTYPE html>
<html>
<head>
<title>Your Name Portfolio</title>
<style>
body {
    font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color: #fff;
}
header {
background-color: #333;
color: efff;
text-align: center;
padding: 2rem 0;
position: relative; /* Add this */
}
.header-content h1 {
font-size: 2.5rem;
}
/* Add styles for the round profile picture */

.profile-picture {

width: 100px; /*Adjust the size as needed */
height : 100px;
border-radius: 75%; /*Create a circular shape*/
object-fit: cover;/*to ensure the img fill circular area */
position: absolute;
top: 75px;
left: 75px;
}
nav {
    background-color: #333;
   color: #fff;
   text-align: center;
}
 nav u1 {
    list-style-type: none;
    padding: 0 ;

 }
 nav u1 li {
    display: inline;
    margin: 0 20px;

 }
 nav u1 li a {
    text-decoration: none;
    color: #fff;
 }
 .section-content{
    background-color: #fff;
    padding: 2rem;
    margin: 1rem;
    border-radius: 20px;
    box-shadow: 0 0 20px rgba(0,0,0,0.1);
 }
 .download-button{
    background-color: #333;
    color:#fff ;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 20px;
    display: inline-block;
    margin-top: 10px;

 }
 .download-button:hover{
    background-color: #555;

 }
 footer{
    text-align: center;
    padding: 1rem 0;
    background-color: #333;
    color: #fff;

 }
 u1{
    list-style-type: disc;
    padding-left: 20px;
 }
 </style>
 </head>
 <body>
    <header>
        <div class="header-content">
           <h3>V.Mathumitha</h3>
           <p>student</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">about</a></li>
            <li><a href="#education">education</a></li>
            <li><a href="#skill">skills</a></li>
            <li><a href="#project">project</a></li>
            <li><a href="#resume">resume</a></li>
        </ul>
    </nav>
    <section id="about">
    <div class="section-content">
        <h2>about me</h2>   
        <p>hello everyone! this is mathumitha and i am a bsc student</p>
    </div>
    </section>
    <section id="education">
        <div class="section-content">
            <h2> bsc</h2>
            <p>st.justin arts and science college for women</p>
        
        </div>
    </section>
    <section id="skills">
        <div class="section-content">
            <h2>skills</h2>
            <ul>
                <li>C</li>
                <li> AI</li>
            </ul>
        </div>
    </section>
    <section id="project">
        <div class="section-content">
            <h2>project</h2>
            <ul>
                <li>
                    ai
                </li>
            </ul>
        </div>
    </section>
    <section id="resume">
        <center>
            <div class="section-content">
            </div>
        </center>
    </section>
    <footer>
        <p>&copy;2023 mathumitha</p>

    </footer>
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor=>{
            anchor.addEventListener('click',function(e){
                e.preventDefault();
                const targetId=this.getAttribute('href').substring(1);
                const targetElement=document.getElementById(targetId);
                if(targetElement){
                    window.scrollTo({
                        top:targetElement.offsetTop,
                        behavior:'smooth'
                    });
                }
            });
        });
    </script>
    </body>
    </html>

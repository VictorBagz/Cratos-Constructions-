<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale =1.0"/>
    <title>Cratos Building Solutions</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css" integrity="sha384-tViUnnbYAV00FLIhhi3v/dWt3Jxw4gZQcNoSCxCIFNJVCx7/D55/wXsrNIRANwdD" crossorigin="anonymous"/>
    <style>
        .navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: #333;
  color: #fff;
  padding: 1em;
  display: flex;
  
  align-items: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  z-index: 1000;
}

.navbar-brand {
  display: inline-block;
  margin-right: 20px;
}

.navbar-brand h5 {
  display: inline-block;
  font-size: 1.5em;
  font-weight: bold;
  margin: 0;
}

.menu-icon {
  display: inline-block;
}

.menu-label {
  
  display: block;
  padding: 10px;
}

.menu-span {
  display: block;
  width: 20px;
  height: 2px;
  background-color: #fff;
  margin-bottom: 5px;
  transition: all 0.3s ease-in-out;
}

.menu-label:hover .menu-span:nth-child(1) {
  transform: rotate(45deg) translate(5px, 5px);
}

.menu-label:hover .menu-span:nth-child(2) {
  opacity: 0;
}

.menu-label:hover .menu-span:nth-child(3) {
  transform: rotate(-45deg) translate(5px, -5px);
}

.dropdown-content {
  position: absolute;
  top: 100%;
  right: 0;
  background-color: #333;
  color: #fff;
  padding: 10px;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  display: none;
}

.menu-label:hover + .dropdown-content {
  display: block;
}

.dropdown-content li {
  margin-bottom: 10px;
}

.dropdown-content a {
  color: #fff;
  text-decoration: none;
  transition: all 0.3s ease-in-out;
}

.dropdown-content a:hover {
  color: #ccc;
}
h1,h2,h3,h4,h5{
    text-align:center;
    margin-top:20px;
}
/* Media Query for Mobile Devices */

@media only screen and (max-width: 768px) {
  .nav-bar {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .menu-icon {
    display: block;
  }
  
  .nav-links {
    display: none;
    flex-direction: column;
    align-items: flex-start;
    background-color: #333;
    padding: 1em;
    position: absolute;
    top: 100%;
    left: 0;
    width: 100%;
  }
  
  .nav-links li {
    margin-bottom: 10px;
  }
  
  .nav-links a {
    color: #fff;
  }
  
  .menu-icon:hover + .nav-links {
    display: block;
  }
}



  .img1 {
      width:100%;
      margin:30px 0px;
      border:5px solid white;
      border-radius :200px 200px;
      transition-duration:3s;
  }
  .img1:hover{
      transform: rotateZ(45deg);
  }
  .container {
      position:relative ;
  }  
  .center {
      position :absolute ;
      top:20%;
      left:10%;
  }
  input[type="radio"] {
      display:none;
  }
  #container{
      border :1px solid black;
      
  }
  
  
  
  
  
  
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}


.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}







  * {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      font-family:Helvetica, Verdana, Sans-serif;
    }
    .image-container {
      margin: 0 auto; /* center the image containers */
      width: 80%;
      box-shadow: 0 15px 30px rgba(0,0,0,0.30), 0 11px 8px rgba(0,0,0,0.22); /* material box shadow */
      margin-bottom: 20px;
      transition-duration: 1s;
    }
    .image-container:hover {
      width: 90%;
      box-shadow: 0 18px 36px rgba(0,0,0,0.30), 0 14px 11px rgba(0,0,0,0.22);
    }
    /* make the images responsive */
    img {
      width: 100%;
      height: auto;
    }
    .image-description {
      padding: 0 15px 15px 15px;
      text-align: center;
    }
    
    /* lightbox stylesheet */
    .lightbox {
      display: table; /* helps us center the lightbox-content */
      transition-duration: 1s; /* duration of the fade in effect */
    
      /* make the lightbox occupy the entire page */
      position: fixed;
      top: -100%; /* hide the lightbox above the top edge */
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.7); /* black with 0.7 opacity */
    }
    .lightbox:target {
      top: 0; /* make the lightbox cover the entire page */
    }
    .lightbox-content {
      display: table-cell;
      vertical-align: middle; /* vertically center */
      text-align: center; /* horizontally center */
    }
    .close {
      /* position the CLOSE button to the top-right corner */
      position: absolute;
      top: 10px;
      right: 10px;
    
      /* style the close button */
      font-size: 20px;
      font-weight: 300;
      text-decoration: none;
      color: white;
    }
    
    /* make the image responsive */
    .lightbox img {
      max-width: 100%;
      height: auto;
    }
    .section1{
        background-color :#505f9f;
        color:white;
        text-align :center;
    }
    .section2{
        background-image:url(Newedit.jpg);
        background-size :100% 100%;
        background-repeat:no-repeat;
        margin-top :0px;        
    }
   footer{
       padding:0px;
   } 
   .hr{
       width :40%;
   }
 
   ul{
       list-style-type:none;
   }
   p{
       margin :20px 20px;
   }
   form{
       margin:50px;
          }
   input[type=text] {
       width: 100%;
       padding: 12px 20px;
       margin: 8px 0;
       display: inline-block;
       border: 1px solid #ccc;
       border-radius: 4px;
       box-sizing: border-box;
   }
   input[type=submit] {
       width:30%;
       background-color :#11ff00;
       color:black;
       padding:10px 20px;
       margin:20px 0px;
       border:none ;
       border-radius:0px;
       cursor:pointer;
                    
   }
   label.form{
       
       color :white;
              }
              
   textarea{
       margin-top:10px;
       padding:20px;
       border-radius :5px;
   }
   .btn1{
       background-color :#f99a2ad5;
       border-radius :10px;
       border:none;
       padding :20px 50px;
       display :inline-block;
       margin:20px 10px; 
   }
   .btn1:hover{
       background-color :white;
       border:2px solid black;
       color:black;
   }
   .btn2{
       border-radius :10px;
       background-color :white;
       border:1px solid black;
       padding:20px 50px;
       display:inline-block;
       margin:20px 10px;
   }
   .btn2:hover{
       background-color :#2724279e;
       color :white;
       border:none;
   }
   .firstsection{
       background-color :#ffd295e4;
       margin:40px 20px;
   }
   .firstsection i{
       display :block;
       padding :30px ;
       font-size:30px;
       font-style:normal;
   }
   #mediaicons i{
       font-size :20px;
       padding:10px;
       
   }
   #mediaicons{
       margin:50px 0px;
   }
   #footer_icons{
       font-style:normal ;
       text-align :center;
   }
   .bgrnd{
       background:#505f9f ;
   }
   .quote_request{
       color:#fffc40;
       margin-top :30px;
   }
    </style>
</head>
<body>
 <nav class="navbar">
  <div class="navbar-brand">
    <h5>CRATOS CONSTRUCTIONS</h5>
  </div>
  <div class="menu-icon">
    <label class="menu-label">
      <span class="menu-span"></span>
      <span class="menu-span"></span>
      <span class="menu-span"></span>
    </label>
    <ul class="dropdown-content">
      <li><a href="#">Home</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">About</a></li>
    </ul>
  </div>
 </nav>
<div class="containers">
<img class="img1" src="Logo2.jpg" alt="Construction site"></div>
<button class="btn1"><b>Contact Info</b></button>
<button class="btn2"><b>About us</b></button>
<h2>Quality in every foundation</h2>
<img src="siteworkers.jpg"/>
<h4>Building Your Dream, One Brick At A Time.</h4>
<p>At CRATOS BUILDING SOLUTIONS, we understand that every structure is unique. That is why we take the time to listen to your needs and tailor our services to meet your specific goals. From residential renovations to commercial builds, our team of experts is dedicated to delivering top-quality results that exceed your expectations.</p>
<section class="firstsection">
    <h1>Services</h1>
   
        <i class="bi bi-1-circle-fill">Building Construction</i>
        <i class="bi bi-2-circle-fill">Architectural designs</i>
        <i class="bi bi-3-circle-fill">Structural drawings</i>
        <i class="bi bi-4-circle-fill">M&E drawings</i>
        <i class="bi bi-5-circle-fill">Valuation and cost estimates</i>
    
</section>
<h2>Why choose us ..</h2>
<p>We are dedicated to serving our client's needs to satisfaction.</p>



<button class="accordion">Expertise and Specialization</button>
<div class="panel">
  <p>Our team of experts has years of experience in building construction, architectural design, and structural design. Trust us to bring your vision to life.
</p>
</div>

<button class="accordion">Unique Combination of Services</button>
<div class="panel">
  <p>Get everything you need under one roof. Our comprehensive services ensure a seamless experience from design to construction.</p>
</div>

<button class="accordion">Personalized Services</button>
<div class="panel">
  <p>Our personalized service ensures that you receive customized solutions that meet your specific requirements.</p>
</div>

<button class="accordion">Innovative Solutions</button>
<div class="panel">
  <p>Our team is dedicated to finding creative solutions to complex construction problems. We stay up-to-date with the latest technologies and techniques to ensure that your project is completed efficiently and effectively."
</p>
</div>

<button class="accordion">Cost-Effective Solutions</button>
<div class="panel">
  <p>We understand that budget is a top priority for our clients. Our team works closely with you to identify cost-saving opportunities without sacrificing quality or safety."</p>
</div>

<button class="accordion">Timely Completion</button>
<div class="panel">
  <p>We understand the importance of meeting deadlines. Our team works efficiently to ensure that your project is completed on time, every time.</p>
</div>




<h2>Project Portfolio</h2>

    <div class="image-container" id="container1">
      <a href="#image1"><img src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/building7.jpg" /></a>
      <p class="image-description"> Lorem ipsum dolor sit amet. </p>
    </div>
  
    <div class="image-container" id="container2">
      <a href="#image2"><img src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/buildingstones.jpg" /></a>
      <p class="image-description"> Lorem ipsum dolor sit amet. </p>
    </div>
  
    <div class="image-container" id="container3">
      <a href="#image3"><img src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/building14.jpg" /></a>
      <p class="image-description"> Lorem ipsum dolor sit amet. </p>
    </div>
  
    <div class="image-container" id="container4">
      <a href="#image4"><img src="building5.jpg" /></a>
      <p class="image-description"> Lorem ipsum dolor sit amet. </p>
    </div>
  
  </div>
  
  <div class="lightbox" id="image1">
    <a href="#" class="close">CLOSE</a>
    <div class="lightbox-content">
      <img src="Newluxury.jpg" />
    </div>
  </div>
  
  <div class="lightbox" id="image2">
    <a href="#" class="close">CLOSE</a>
    <div class="lightbox-content">
      <img src="Newluxury.jpg" />
    </div>
  </div>
  
  <div class="lightbox" id="image3">
    <a href="#container3" class="close">CLOSE</a>
    <div class="lightbox-content">
      <img src="Newluxury.jpg" />
    </div>
  </div>
  
  <div class="lightbox" id="image4">
    <a href="#container4" class="close">CLOSE</a>
    <div class="lightbox-content">
      <img src="Newluxury.jpg" />
    </div>
  </div>
<div class="bgrnd">
<section class="section1">
    <h1>Contact us</h1>
<p>We are located in Gayaza, along Bugembo road, plot114.</p>
    
   <h3><u>Mr. Kabali Gerald</u></h3>
   
    <p>Managing Director</p>
    <p>0780968884/0754230049</p>
    <p>masembeg4@gmail.com</p>
    
       <h3><u>Mr. Moses Tomusangye</u></h3>
       
        <p>General Operations Manager</p>
        <p>0780968884</p>
        <p>tomusangemze45@gmail.com</p>
    
    
       <h3><u>Mr. Joel Nkwanga</u></h3>
       
        <p>Chief Financial Officer</p>
        <p>0780968884</p>
        <p>joelnkwanga09@gmail.com</p >
<div id="mediaicons">
    <i class="bi bi-twitter-x"></i>
    <i class="bi bi-facebook"></i>
    <i class="bi bi-whatsapp"></i>
    <i class="bi bi-instagram"></i>
    <i class="bi bi-envelope-at-fill"></i>
    <i class="bi bi-youtube"></i>
    <i class="bi bi-tiktok"></i>
</div>
    <hr/>
<h1>Partnerships</h1>
<p><h4>Taza-Fasi</h4></p>
<p>Digitalizing built environments by leveraging Virtual Reality (VR), Augmented Reality (AR) and virtual tours through immersive experiences. </p>
<hr class="hr"/>
<p><h4>Liceria & Co.</h4></p>
<p>Real Estate</p>
<p a href="wwww.reallygreatsite">www.reallygreatsite.com</p>
</section>
<section class="section2">
    <h1 class="quote_request">Quote request</h1>
    <div class="form">
    <form action="#">
        <label for="fname" class="form"><strong>First name</strong></label>
        <input type ="text" id="fname" name="firstname" placeholder ="Your first name..."/>
        
        <label for="lname" class="form"><strong>Last name</strong></label>
        <input type="text" id="lname" name="lastname" placeholder ="Your last name..."/>
        
        <label for="email" class="form"><strong>E-mail</strong></label>
        <input type="text" id="email" name="email" placeholder="Your E-mail..."/>
        
        <label for="Comment" class="form"><strong>Comment</strong></label>
        <textarea id="comment" name="comment"style="height:200px;width:100%" placeholder="Your comment..."></textarea>
        
        <input type="submit" value="submit"/>
    </form>
    </div>
</section>
</div>
<footer>
    <img src="file:///storage/emulated/0/Android/data/com.teejay.trebedit/files/TrebEdit user files/cratoslogo.jpg"/>
</footer>




<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
      });
}
</script>

</body>
</html>

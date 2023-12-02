<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<link type="preconnect" href="https://fonts.google.com/specimen/Poppins/tester?query=poppin">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <link rel="stylesheet" type="text/css" href="portfolio.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="icon" type="image/x-icon" href="sslogo.png">


  	<title>MR. AMIT PORTFOLIO</title>
	<style type="text/css">
		div{height:100px ;
	border-radius:1%;
	

}
		body{background:black;}
	*{margin: 0;
		padding:0 ;}	
nav{background:#2d1d52ff;
width: 100%;
height:100px;
color: white;

}
nav ul {
  list-style-type: none;
  display: flex;
 overflow: auto;
 margin-top:5px ;
 
  }
 .left ul li {list-style: none;
	overflow: auto;
display: flex;
margin-left:10px ;
float: left;

}
.right ul li {list-style: none;
	overflow: auto;
display: flex;
margin-top: 20px;

}
.left a{
	text-decoration: none;
padding: 10px;
color: white;
font-size:10px ;
}
.right a:hover{	text-decoration: none;
padding: 20px;
color: blue;
font-size: 22px;}
.right a{
	text-decoration: none;
padding: 20px;
color: white;
font-size:20px ;
}
.left a:hover{
	text-decoration: none;
padding: 14px;

font-size: 12px;

}
.one{border-radius: 30%;
}
#main{
width: 100%;
height: 470px;
opacity: 70%;
margin-top: 0px;}

	section{position: absolute;
		top: 160px;
		color: white;}

.leftsection {height: 200px;
	width: 40%;
margin: 50px;
margin-top:60px ;
}


.firstsection{display: flex;
justify-content: space-around;
width: 100%;
margin: 30px 10;}

.purple{color:#f0d91cde ;
padding: 20px;}
.leftsection .btn{background: blueviolet;
color: white;

cursor: pointer;

border: 2px solid white;

border-radius: 6px;
font-size: 20px;
height: 70px;
position: relative;
margin-top: 40px;
border-radius: 5%;
}
u{color: white;}
.skill-card {
  margin-bottom: 1rem;
  border: 1px solid #F0ECE3;
  box-shadow: 0 1px 4px rgba(0,0,0,0.15);
  transition: 0.5s all ease;
  cursor: pointer;
}
.skill-card:hover {
    box-shadow: 5px 10px 12px black ;
  border-color: #543210;
}
.skill-card:hover .card-img {
  border-bottom-color: #000;
}
.skill-card .card-img {
  padding: 20px;
  border-bottom: 1px solid #F0ECE3;
  border-radius: 0;
  display: flex;
  align-items: center;
  transition: 0.5s all ease;
}

.skill-card .card-img img {
  margin: auto;
  width: 100px;
  height: auto;
}
.skill-card .card-body h4 {
  color: #000;
  font-size: 1rem;
  text-align: center;
}
.gggg{background:blueviolet;}

.main-timeline {
    position: relative;

   
}

.main-timeline:before {
    content: "";
    display: block;
    width: 2px;
    height: 100%;
    background: #c6c6c6;
    margin: 0 auto;
    position: absolute;
    top: 0;
    left: 0;
    right: 0
}

.main-timeline .timeline {
    margin-bottom: 40px;
    position: relative
}

.main-timeline .timeline:after {
    content: "";
    display: block;
    clear: both
}

.main-timeline .icon {
    width: 18px;
    height: 18px;
    line-height: 18px;
    margin: auto;
    position: absolute;
    top: 10;
    left: 0;
    bottom: 0;
    right: 0
}

.main-timeline .icon:before,
.main-timeline .icon:after {
    content: "";
    width: 100%;
    height: 100%;
    border-radius: 50%;
    position: absolute;
    top: 0;
    left: 0;
    transition: all 0.33s ease-out 0s
}

.main-timeline .icon:before {
    background: #fff;
    border: 2px solid #232323;
    left: -3px
}

.main-timeline .icon:after {
    border: 2px solid #c6c6c6;
    left: 3px
}

.main-timeline .timeline:hover .icon:before {
    left: 3px
}

.main-timeline .timeline:hover .icon:after {
    left: -3px
}

.main-timeline .date-content {
    width: 50%;
    float: left;
    margin-top: 22px;
    position: relative
}

.main-timeline .date-content:before {
    content: "";
    width: 36.5%;
    height: 2px;
    background: #c6c6c6;
    margin: auto 0;
    position: absolute;
    top: 0;
    right: 10px;
    bottom: 0
}

.main-timeline .date-outer {
    width: 125px;
    height: 125px;
    font-size: 16px;
    text-align: center;
    margin: auto;
    z-index: 1
}

.main-timeline .date-outer:before,
.main-timeline .date-outer:after {
    content: "";
    width: 125px;
    height: 125px;
    margin: 0 auto;
    border-radius: 50%;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    transition: all 0.33s ease-out 0s
}

.main-timeline .date-outer:before {
    background: #fff;
    border: 2px solid #232323;
    left: -6px
}

.main-timeline .date-outer:after {
    border: 2px solid #c6c6c6;
    left: 6px
}

.main-timeline .timeline:hover .date-outer:before {
    left: 6px
}

.main-timeline .timeline:hover .date-outer:after {
    left: -6px
}

.main-timeline .date {
    width: 100%;
    margin: auto;
    position: absolute;
    top: 27%;
    left: 0
}

.main-timeline .month {
    font-size: 18px;
    font-weight: 700
}

.main-timeline .year {
    display: block;
    font-size: 30px;
    font-weight: 700;
    color: #232323;
    line-height: 36px
}

.main-timeline .timeline-content {
    width: 50%;
    padding: 20px 0 20px 50px;
    float: right

}

.main-timeline .title {
    font-size: 19px;
    font-weight: 700;
    line-height: 24px;
    margin: 10 10 20px 
}

.main-timeline .description {
    margin-bottom: 0
}

.main-timeline .timeline:nth-child(2n) .date-content {
    float: right
}

.main-timeline .timeline:nth-child(2n) .date-content:before {
    left: 10px
}

.main-timeline .timeline:nth-child(2n) .timeline-content {
    padding: 20px 50px 20px 0;
    text-align: right
}

@media only screen and (max-width: 991px) {
    .main-timeline .date-content {
        margin-top: 35px
    }
    .main-timeline .date-content:before {
        width: 22.5%
    }
    .main-timeline .timeline-content {
        padding: 10px 0 10px 30px
    }
    .main-timeline .title {
        font-size: 17px
    }
    .main-timeline .timeline:nth-child(2n) .timeline-content {
        padding: 10px 30px 10px 0
    }
}

@media only screen and (max-width: 700px) {
    .main-timeline:before {
        margin: 0;
        left: 7px
    }
    .main-timeline .timeline {
        margin-bottom: 20px
    }
    .main-timeline .timeline:last-child {
        margin-bottom: 0
    }
    .main-timeline .icon {
        margin: auto 0
    }
    .main-timeline .date-content {
        width: 95%;
        float: right;
        margin-top: 0
    }
    .main-timeline .date-content:before {
        display: none
    }
    .main-timeline .date-outer {
        width: 110px;
        height: 110px
    }
    .main-timeline .date-outer:before,
    .main-timeline .date-outer:after {
        width: 110px;
        height: 110px
    }
    .main-timeline .date {
        top: 30%
    }
    .main-timeline .year {
        font-size: 24px
    }
    .main-timeline .timeline-content,
    .main-timeline .timeline:nth-child(2n) .timeline-content {
        width: 95%;
        text-align: center;
        padding: 10px 0
    }
    .main-timeline .title {
        margin-bottom: 10px
    }
}
#a{background: blanchedalmond;
border-radius:30px;
}
.bbbb{border-color:black;}

.btn{background:red;
color:black;
position: absolute;
right: 60px;
top: 5px;}

.form-control{
width: 130px;
position: absolute;
right: 150px;
top: 5px;}
.ggg{background:yellow ;
color:solidebrown;
height: 50px;}


/* Container for skill bars */
.amitk {
  width: 100%; /* Full width */
  background-color: #ddd; /* Grey background */
}

.skills {
  text-align: right; /* Right-align text */
  padding-top: 10px; /* Add top padding */
  padding-bottom: 10px; /* Add bottom padding */
  color:darkblue; /* White text color */
}
.html {width: 90%; background-color: #04AA6D;} /* Green */

.css {width: 80%; background-color: #2196F3;} /* Blue */
.js {width: 75%; background-color: #f44336;} /* Red */
.php {width: 70%; background-color: #808080;} /* Dark Grey */
#element{color:yellow ;}
#lmn{color: white;
text-decoration: none;}
.jkl {background:deepskyblue;
width: 100%;
height: 300px;
margin-top: 30px ;
display: flex;
font-size: 20px;
padding: 50px;
}

footer >div{display: flex;
justify-content: space-around;
width: 100%;
}
.footer{margin-top: 10px;
display: flex;
justify-content: space-around;

color: blueviolet;}


	</style>



</head>
<body>
	<header>

<nav>
	
		<div class="row">
			<div class="left col-md-6"><h3>Welcome to my PORTFOLIO WEBSITE</h3><ul>
<li><a href="https://whatsapp.com/channel/0029VaF8Fy2EQIaxQFx24E17"><img class="one "src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\WhatsApp.png"width="30px"height="30px"></a></li>
				<li><a href="https://www.youtube.com/@indiafreestudy6287"><img class="one"src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\youtube.png"width="30px"height="30px"></a></li>
				<li><a href="https://instagram.com/misteramitcsedepartment6287?utm_source=qr&igshid=OG"><img class="one"src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-29 184347.png"width="30px"height="30px"></a></li>
				<li><a href="#"><img class="one"src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Facebook.png"width="30px"height="30px"></a></li>
				<li><a href="https://linkedin.com/in/amit-kumar-bb8088296?fromQR=1"><img class="one"src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\LinkedIn.png"width="30px"height="30px"></a></li>

			</ul>



			</div>
			<div class="right col-md-6">
			<ul>
				<li><a href="MYZIPPORTFOLIO.html">HOME</a></li>
				<li><a href="file:///C:/Users/Dell/AppData/Local/Temp/2e76c04f-f7fb-4d44-aeba-9f9c8943a23e_MR.%20AMIT%20PORTFOLIO.zip.23e/Amit's%20Resume%20(1).pdf">RESUME</a></li>
				<li><a href="https://about.me/amitkumarkh01.1.2006">ABOUT</a></li>
				<li><a href="#">SERVICES</a></li>
				<li><a href="#">FEEDBACK</a></li>
			<li><a href="#">CONTACT US</a></li>
			</ul>
		</div>
	
</div>
	</nav>

	</header>
<main> 

<img  id="main"
  src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\top-view-dark-laptop-background-template_52683-7081.jpg" >
  


<section class="firstsection">

	<div class="leftsection">
		<h2>Hi ,MY Name is <b><span class="purple">AMIT KUMAR</span></b><br>I am a Professional & Passionate<br> <span id="element">WEB DEVELOPER</span></h2>
		

<button class="btn"><a id="lmn" href="file:///C:/Users/Dell/AppData/Local/Temp/2e76c04f-f7fb-4d44-aeba-9f9c8943a23e_MR.%20AMIT%20PORTFOLIO/Amit's%20Resume%20(1).pdf">DOWNLOAD RESUME</a></button>


<button class="btn">VISIT GITHUB</button>


	

	</div>

<div class="rightsection">
		
<img src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-14 192913.png"height="350px"width="350px">
	</div>


</section><center>



</main>

<!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['student of government polytechnic gulzabagh patna (800007).', 'WEB DEVELOPER (FULL STACK).','TECHNOLOGY ENTHUSIAST.','VIDEO EDITOR.','PHOTO EDITOR.','CONTENT MARKETOR.','ENTREPRENEUR.'],
      typeSpeed: 50,
    });
  </script>
 
<center>

		<div class="row">
			<div class= "gggg  col-md-12 " style="height:3250px ;">


				<div class="row container"style="width:100%;">
 
 <center><h1><b><u>MY SKILLS </u></b></h1></center><br><br>


<div class="container">
  <div class="row">
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/640px-HTML5_logo_and_wordmark.svg.png" alt="" class="img-fluid">
      </div>
      <div class="card-body">
        <h4>HTML</h4>
      </div>
    </div>
  </div>
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">"
        <img src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO.\css.png"alt="" class="img-fluid">
      </div>
      <div class="card-body"><br><br>
        <h4>CSS </h4>
      </div>
    </div>
  </div>
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\javascript.png" alt="" class="img-fluid">
      </div>
      <div class="card-body"><br>
        <h4>JAVASCRIPT</h4>
      </div>
    </div>
  </div>
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src= "D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\logobootstrap.png"alt="" class="img-fluid">
      </div>
      <div class="card-body">
        <h4>BOOTSTRAP</h4>
      </div>
    </div>
  </div>
   <div class="mt-4"></div>
<div class="container">
  <div class="row">
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src="https://git-scm.com/images/logo@2x.png" alt="" class="img-fluid">
      </div>
      <div class="card-body"><br>
        <h4>git & git APK</h4>
      </div>
    </div>
  </div>
    <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src="data:image/png;base64,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" alt="" class="img-fluid">
      </div>
      <div class="card-body"><br>
        <h4>github & website</h4>
      </div>
    </div>
  </div>
      <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src= "D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\mathematics.jpg"alt="" class="img-fluid">
      </div>
      <div class="card-body">
        <h4>MATHEMATICS</h4>
      </div>
    </div>
  </div>
      <div class="col-6 col-md-3">
    <div class="card skill-card">
      <div class="card-img">
        <img src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\soft2.png" alt="" class="img-fluid">
      </div>
      <div class="card-body">
        <h4>SOFTWARE<br>ENGINEERING</h4>
      </div>
  </div>
</div>
  
 </div>
</div>

   <div class="mdb-lightbox">  <div id="mdb-lightbox-ui"></div><br>
   <center><h1><b><u>MY PROJECTS</u></b></h1></center><br>
<center>
  <div class="container ">
  <div class="row">
 
      <figure class="col-md-4 ">
         <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(150).webp" data-size="1600x2000">
          <a href="flipkartask.html"><img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-15 215542.png"class="img-fluid" >
          </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(150).webp" data-size="1600x2000">
          <a href="gppgulzaarbagh.html"><img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-15 221200.png" class="img-fluid" >
        </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(152).webp" data-size="1200x1200">
        <a href="responsive.html">  <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-15 222025.png"width="300px"height="300px" class="img-fluid" />
        </a>
      </figure></div></div><div class="mt-5"></div>
<div class="container">
  <div class="row">
      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(42).webp" data-size="1200x1600">
        <a href="services.html">   <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-15 222904.png" class="img-fluid" >
        </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(42).webp">
       <a href="task6666.html"> <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\WhatsApp Image 2023-10-30 at 10.21.07_1691331a.jpg"width="300px"height="400px"class="img-fluid" >
        </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(148).webp" data-size="1200x1200">
         <a href="practice 06.html">  <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\WhatsApp Image 2023-11-10 at 10.58.30_01b86c3a.jpg"width="300px"class="img-fluid" />
        </a>
      </figure></div></div><div class="mt-5"></div>
<div class="container">
  <div class="row">
      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(148).webp" data-size="1600x2000">
        <a href="portfolio.html">   <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-15 221622.png" class="img-fluid" />
        </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(147).webp" data-size="1600x2000">
        <a href="task5.html">   <img alt="picture" src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\Screenshot 2023-11-16 210648.png" class="img-fluid" />
        </a>
      </figure>

      <figure class="col-md-4">
        <a href="https://mdbootstrap.com/img/Photos/Lightbox/Original/img%20(149).webp" data-size="1600x2000">
        <a href="task4.html">   <img alt="picture" src=""width="300px"height="280px">
        </a>
      </figure></div>
     


 </center>
    

<br><br><br><br>
<br><br><br><br>
<center>  <button class="ZZZZZ container bg-primary" type="submit" style="width:100px;"style="height:40px;"style="width:100px;"><b>VIEW MORE</b></button></center>
<div class="container mt-0">
<div class="main-timeline">
<h1><b><u>MY PAST EXPERIENCE</u></b></h1><br>

                        <!-- start experience section--><br><br>
                        <div class="timeline">
                            <div class="icon"></div>
                            <div class="date-content">
                                <div class="date-outer">
                                    <span class="date">
                                            <span class="month">2 Years</span>
                                    <span class="year">2020-22</span>
                                    </span>
                                </div>
                            </div>
                            <div class="timeline-content">
                                <h5 class="title"><U>INTERMEDIATE OF SCIENCE & MATHEMATICS</U></h5>
                                <p class="description">
                                    I COMPLETED I.SC IN MATHEMATICS STREAM FROM SACHIDANAND SINHA COLLEGE AURANGABAD,BIHAR.IT IS A NICE PLACE FOR COMPLETED ISC.IT IS GRADE A COLLEGE IN BIHAR.
                                </p>
                            </div>
                        </div>
                        <!-- end experience section-->
 <!-- start experience section--><br><br>
                        <div class="timeline">
                            <div class="icon"></div>
                            <div class="date-content">
                                <div class="date-outer">
                                    <span class="date">
                                            <span class="month">3 MONTH</span>
                                    <span class="year">2022</span>
                                    </span>
                                </div>
                            </div>
                            <div class="timeline-content">
                                <h5 class="title"><U>KUSHAL YUVA PROGRAM</U></h5>
                                <p class="description">
                                    I COMPLETED KYP IN BSCIT,BSCSS,BSCLS  FROM BIHAR SKILL DEVELOPMENT MISSION (BSDM) DRCC, AURANGABAD,BIHAR.IN 3 MONTH WE LEARN LANGUAGE SKILLS,SOFT SKILLS,& IT SKILLS.THIS COURSE MUST DO EVERY STUDENTS BECAUSE HERE WE LEARN NEW THINKS WITH THEORY+PRACTICAL.
                                </p>
                            </div>
                        </div>
                        <!-- end experience section-->
                        <!-- start experience section--><br><br>
                        <div class="timeline">
                            <div class="icon"></div>
                            <div class="date-content">
                                <div class="date-outer">
                                    <span class="date">
                                            <span class="month">1 Years</span>
                                    <span class="year">2020</span>
                                    </span>
                                </div>
                            </div>
                            <div class="timeline-content">
                                <h5 class="title">MATRICULATION</h5>
                                <p class="description">
                                   I SUCCESSFULLY COMPLETED MATRIC FROM BSEB PATNA .I PASSED 10TH WITH 85% MARKS IN SCIENCE ,SOCIAL SCIENCE,MATH,HINDI,ENGLISH,&SANSKRIT SUBJECT.
                                </p>
                            </div>
                        </div>
                        <!-- end experience section-->

                        <!-- start experience section--><br><br>
                        <div class="timeline">
                            <div class="icon"></div>
                            <div class="date-content">
                                <div class="date-outer">
                                    <span class="date">
                                            <span class="month">3 Years</span>
                                    <span class="year">2022-25</span>
                                    </span>
                                </div>
                            </div>
                            <div class="timeline-content">
                                <h5 class="title"><U>CSE ENGINEERING FULL TIME</U></h5>
                                <p class="description">
                                    NOW I PURSUING DIPLOMA IN COMPUTER SCIENCE AND ENGINEERING FROM GOVERNMENT POLYTECHNIC COLLEGE GULZARBAGH ,PATNA (800007).THIS IS NICE GRADE A COLLEGE FOR LEARNING SOFTWARE + HARWARE ENGINEERING.
                                </p>
                            </div>
                        </div>
                        <!-- end experience section-->

                        <!-- start experience section--><br><br>
                        <div class="timeline">
                            <div class="icon"></div>
                            <div class="date-content">
                                <div class="date-outer">
                                    <span class="date">
                                            <span class="month">1 MONTH</span>
                                    <span class="year">2023</span>
                                    </span>
                                </div>
                            </div>
                            <div class="timeline-content">
                                <h5 class="title"><U>WEB DESIGNER(FRONT END DEVELOPMENT+BACKEND)</U></h5>
                                <p class="description">
                                    I COMPLETED INTERNSHIP OF WEB DEVELOPMENT FROM KHABAI TECH PRIVATE LIMITED COMPANY.HERE WE EXPERIENCED NICE CLIMATE TO LEARN OF WEB DEVELOPMENT & DESIGNING.
                                </p>
                            </div>
                        </div>
                        <!-- end experience section--><br><br>
<h1><u>SOME SOCIAL SKILLS</u>
</h1>

<p>video & photo editing</p>
<div class="amitk">
  <div class="skills html">90%</div>
</div>

<p>content creator</p>
<div class="amitk">
  <div class="skills css">80%</div>
</div>

<p>communication skils</p>
<div class="amitk">
  <div class="skills js">75%</div>
</div>

<p>leadership skills</p>
<div class="amitk">
  <div class="skills php">70%</div>
</div>

 <footer>
	<div class="jkl">
		<div class="ek">
			<h1>MR. AMIT DEVELOPER PORTFOLIO</h1>
		</div>
			<div class="do">
				<ul>
					
					<li>home </li>
					<li>about</li>
					<li>servics</li>
					<li>contact</li>
					<li>feedback</li>
				</ul>
			</div>
				<div class="tin">
									<ul>
					
					<li>home </li>
					<li>about</li>
					<li>servics</li>
					<li>contact</li>
					<li>feedback</li>
				</ul>
				</div>
					<div class="char">
										<ul>
					
					<li>home </li>
					<li>about</li>
					<li>servics</li>
					<li>contact</li>
					<li>feedback</li>
				</ul>
					</div>




	


<div class="footer"><b><img src="D:\MY PROJECTS\WEB DESIGNING\HTML .DOC\MR. AMIT PORTFOLIO\soft2.png"width="150px"height="150px"><br>
	<h5>&#169;opyright-claim </h5>|WWW.MR.AMITPORTFOIO.COM|  <br>|All right reserved |</b>
</div>
</div>
</footer>

</center>



</div>

</div>

    </div>

  </div>

  </div>
</div>




	
</body>
</html>

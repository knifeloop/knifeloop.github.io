
<h1>Séamus O´Donnell </h1>

<p>Since 1999 I am working as artist and organiser on different audio art projects. Solo or collaborative works (for performance or installations) can include FM radio experiments with receivers and self built mini-transmitters; reel-to-reel tape machine loop or relay set ups; and a live set which can contain any mix of manipulated field recordings, self made devices, amplified objects and magnetic fields as well as other more traditional instruments and voice.
As an organiser I work with the registered association, <a href="http://www.salonbruit.org" target="_blank">Salon Bruit e.V.</a>, a platform for experimental music.
I work with <a href="http://senderberlin.org/colaboradio/" target="_blank">CoLaboRadio</a> as presenter and programmer on the local frequency <a href="http://www.88vier.net/" target="_blank">88.4FM</a>. I live in Berlin.</p>
<p>The oldest collaborative project I am working on is <a href="http://www.noisiv.org/" target="_blank">noisiV</a>, with <a href="http://androvirus.noweb.org/" target="_blank">Androvirus</a>. Started in Berlin in 1999, it has been a long distance thing since 2002. <br />
Other current collaborations include <a href="https://soundcloud.com/krauchen" target="_blank">Krauchen</a> and a couple of A/V projects with <a href="http://hexler.net/lab/oratory/" target="_blank">H3XL3R</a>. </p>

<p><img class="left" src="img/maastricht.jpg" /><br />

  </p>
<p>"Right now I am most interested in the live-sampling of sounds and noises, whether acoustic or electronic, the repetition and manipulation of these samples and the discovery of new sounds on this journey."</p>
<p> Current set goes something like this:
  <br>
  Objects collected in the city of the performance are elevated to a new status. They become ambassadors of the culture, truth-sayers of the urban experience and representatives of the inanimate, objective and all honest material of the every day life of that city. In the process of sampling and manipulating the sounds of these objects a new (but old) story is teased into being, persuaded to reveal the epic journey of its city. By reducing the city to a few objects and then abstracting their metaphoric properties to a live sound piece is the way preferred by the artist, kNiFeLoOp, to learn of the hidden beauty and ugliness, the ups and downs, and the mystique that lurks beneath the surface of all cities. 
<p>O'Donnell's work includes numerous projects in the field of sound and media art, experimental radio and live improvisation. He is Co-initiator of the series of experimental music concerts in Salon Bruit Berlin, which regularly organizes events since 2002 and over
  the years has been involved in many different temporary radio projects (such as PiRadio, RebootFM, Radio Tesla, Funkwelle and currently 88vier).<br />
  
</div>

<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>knifeloop</title>

<!-- keywords/tags to be found by google -->
<meta name="keywords" content="kunst, interdisziplinÃĪr, musik, ausstellung, workshop, salon bruit, dienstbar, lifeloop, knifeloop, noisiv, stattbad, wedding, berlin, audio, video, installation, recycling, performances, konzert, videoscreening, interdisciplinary, musique, art, noise, experimental music, sound art, sonic, interdisciplinaire, concert, exposition, recycling, art, music, exhibition"/>
<!-- end keywords/tags-->

<style type="text/css" media="all">
	@import "lifeloop.css";
body {
	margin-left: 0px;
	margin-top: 0px;
	margin-right: 0px;
	margin-bottom: 0px;
}
</style>

<script language="javascript">
  function toggleDiv(divid){
    if(document.getElementById(divid).style.display == 'none'){
      document.getElementById(divid).style.display = 'block';
    }else{
      document.getElementById(divid).style.display = 'none';
    }
  }
</script>

<script type="text/javascript"></script>
		
	<script language="Javascript">
		<!--
		function popup(page) {
  		window.open(page, "", "scrollbars=yes,menubar=no,toolbar=no,resizable=yes,width=900,height=600,screenX=100,screenY=150");
		}
		// -->
</script>
</head>



<body>

<!-- page structure -->

<!-- head/logo -->
<div id="head">
	
    <div id="logobox"><a href="index.php?page=home"><img class="logo" src="img/logo.png" align="right"/></a></div>

</div>

<!-- menu -->

<div id="menu">
	<div id="menubox">
    	<ul class="menu">
  <li><a href="index.php?page=home"><span>Home</span></a></li>
  	</ul>
    
    </div>
</div>

<!-- content -->
<div id="main">
	<div id="content">	
	
    	<?php 
			if (!isset($_GET['page'])) $page= 'home'; else $page= $_GET['page']; 
 			switch($page)
			{
			case 'home': include ('home.php');break;
			case 'disclaimer': include ('disclaimer.php');break;
			} 
		?>
    <div class="clear"></div>
    </div>
</div>

</body>
</html>
@charset "utf-8";
/* CSS Document */

body{background:#000}

/* page structure */

#head{ 
	background:#000 url(img/head.jpg) no-repeat top center;
	height:66px; 
	width:100%;
	
	}

#logobox{
	width:800px;
	margin: auto;
	height:65px;
}

.logo{
	margin:15px 0 0 0;
	}

#menu{

	height:30px; 
	width:100%;
	margin: auto;
	background:#000000;
	
	
}

#menubox{

	height:30px; 
	width:800px;
	margin: auto;
	float:center 
		
}

#main{
	background:#000 url(img/contentbackground.jpg) no-repeat top center;
	height:auto; 
	min-height:450px;
	width:100%;
	
}

#content{

	width:800px;
	margin: auto;
	padding:25px 0 25px 0;

}

#footer{
	height:80px;
	width:100%;
	background:#000000;
	border-top:#555 thin solid;
	padding:10px 0 0 0;
	
}

#footerbox{
	
	height:30px;
	width:100%; vertical-align:middle;
	text-align: center; font-size:10px
}

.clear{clear:both;}


#right-column {
	padding-top:10px;
	height: auto; 
	width:195px;
	padding:0 0 0 10px;
	float:right;
	border-left:1px solid #333}
	
#left-column {
	height: auto; 
	width:580px;
	float:left;
	}
/* menu */

.menu{margin:0 auto; padding:0; height:30px; width:100%; display:block; background: none}
.menu li{padding:0; margin:0; list-style:none; display:inline;}
.menu li a{float:left; padding-left:15px; display:block; color:#999; text-decoration:none; font:12px Verdana, Arial, Helvetica, sans-serif; cursor:pointer; background:none }
.menu li a span{line-height:30px; float:left; display:block; padding-right:15px; background:none}
.menu li a:hover{color:rgb(255,255,255);}
.menu li a:hover span{background-position:100% -60px;}
.menu li a.active, .menu li a.active:hover{line-height:30px; font:12px Verdana, Arial, Helvetica, sans-serif; background: #999999; color:#cccccc;}
.menu li a.active span, .menu li a.active:hover span{background:none}





/* texts */


h1{ /* title */
	font-family:Arial, Helvetica, sans-serif;
	font-size: 24px;
	font-style: normal;
	line-height: normal;
	font-weight: normal;
	font-variant: normal;
	color: #80a8c4;
	text-decoration: none;
	margin:0;
	padding:10px 0 10px 0;
}

h2{ /* subtitle */
	font-family:Arial, Helvetica, sans-serif;
	font-size: 20px;
	font-style: normal;
	line-height: normal;
	font-weight: normal;
	font-variant: normal;
	color: #fff;
	text-decoration: none;
	margin:0;
	padding:5px 0 5px 0;
}

p {  /* paragraph */
	font-family:Arial, Helvetica, sans-serif;
	font-size: 14px;
	line-height: 17px;
	font-style: normal;
	font-weight: normal;
	font-variant: normal;
	color: #999999;
	text-decoration: none;
	margin:0;
	padding-bottom:10px;
}



#right-column p {
	font-size: 12px;
	line-height: normal;
}


em{ /* italic */
	
	font-family:Arial, Helvetica, sans-serif;
	font-style: normal;
	line-height: normal;
	font-weight: normal;
	font-variant: normal;
	color: #80a8c4;
	text-decoration: none;
}

strong{/* bold*/
	
	font-family:Arial, Helvetica, sans-serif;
	font-size: 12px;
	font-style: normal;
	line-height: normal;
	font-weight: bold;
	font-variant: normal;
	color: #fff;
	text-decoration: none;
}

#footerbox{

	font-family:Arial, Helvetica, sans-serif;
	font-size: 11px;
	font-style: normal;
	line-height: normal;
	font-weight: normal;
	font-variant: normal;
	color: #999999;
	text-decoration: none;
	margin:0;
	padding-bottom:10px;}

/* links */
a { 
	font-family:Arial, Helvetica, sans-serif;
	font-size: 12px;
	color:#80a8c4;
	text-decoration: underline;
	font-weight:bold;
	border:none;
}

a:hover {
	color:#ffffff;
	text-decoration:none;
	border:none;
}



/* images */
.right{
float:right;
margin-top:5px;
margin-bottom:5px;
margin-right:0px;
margin-left:10px;
 }

.left{
width:100%;
float:left;
margin-top:5px;
margin-bottom:10px;
margin-right:10px;
margin-left:0px;}

.video{
border:thin #999999 solid;
float:right;
margin-top:5px;
margin-bottom:5px;
margin-right:0px;
margin-left:10px;
 }


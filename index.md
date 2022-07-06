<style>

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
main_content,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font-family: "Lucida Console", -apple-system, Monaco,
    "Bitstream Vera Sans Mono", Terminal, monospace, BlinkMacSystemFont,
    "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue",
    sans-serif;
}
/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

* {
  margin: 0;
  padding: 0;
}
	
	
body {
  color: white;
	 background: url(https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/bd_type1_citycrop.jpg) no-repeat center center fixed; 
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  line-height: 1.5;
   -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

iframe {
  margin: 0px;
  padding: 0px;
  background-image: url("https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/bd_type1_car.jpg");
  border: none;
}

p
{
  background-image: url("https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/halfscreen-black.gif");
}
	
img {
  padding: 0px;
  margin: 0px;
  width: 100%;
}

h2,
h1,
h3 {
  color: white;
  background: transparent
    url(https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/halfscreen-gray.gif)
    center repeat;
  font-family: "Helvetica Neue", "Bitstream Vera Sans Mono", sans-serif, -apple-system, Monaco, 
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell;
  font-weight: 900;
  padding: 0px;
  margin: 0px;
  text-align: left;
  font-variant-caps: small-caps;
  text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 20px #fff, 0 0 40px #0ff,
    0 0 80px #0ff, 0 0 90px #0ff, 0 0 100px #0ff, 0 0 150px #0ff;
}

h2 {
font-weight: 900;
font-family: "Helvetica Neue", sans-serif, "Lucida Console", Terminal;
padding: 0px;
margin: 0px;
text-align: left;

}
.firstcharacter {
  color: #fff;
  text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #0fa,
    0 0 82px #0fa, 0 0 92px #0fa, 0 0 102px #0fa, 0 0 151px #0fa;
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  float: left;
  font-size: 75px;
  line-height: 60px;
  padding-top: 7px;
  padding-right: 8px;
  padding-left: 3px;
}

.neonText {
  color: #fff;
  text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #0fa,
    0 0 82px #0fa, 0 0 92px #0fa, 0 0 102px #0fa, 0 0 151px #0fa;
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
}

.storyBox {
  width: 100%;
  position: relative;
  display: flex;
}

.storyBox .card {
  position: relative;
  cursor: pointer;
}

.storyBox .card .face {
  width: 100%;
  height: 200px;
  transition: 0.5s;
}

.storyBox .card .face.face1 {
  position: relative;
  background: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1;
  transform: translateY(100px);
}

.storyBox .card:hover .face.face1 {
  background: #00c2ff;
  transform: translateY(0);
}

.storyBox .card .face.face1 .storycontent {
  opacity: 0.2;
  transition: 0.5s;
}

.storyBox .card:hover .face.face1 .storycontent {
  opacity: 1;
}

.storyBox .card .face.face1 .storycontent img {
  max-width: 100px;
}

.storyBox .card .face.face1 .storycontent h3 {
  margin: 10px 0 0;
  padding: 0;
  color: #fff;
  text-align: center;
  font-size: 1.5em;
}

.storyBox .card .face.face2 {
  position: relative;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  box-sizing: border-box;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.8);
  transform: translateY(-100px);
}

.storyBox .card:hover .face.face2 {
  transform: translateY(0);
}

.storyBox .card .face.face2 .storycontent p {
  margin: 0;
  padding: 0;
}

.storyBox .card .face.face2 .storycontent a {
  margin: 15px 0 0;
  display: inline-block;
  text-decoration: none;
  font-weight: 900;
  color: #333;
  padding: 5px;
  border: 1px solid #333;
}

.storyBox .card .face.face2 .storycontent a:hover {
  background: #333;
  color: #fff;
}

	
.some-page-wrapper {
  margin: 15px;
  background-color: ##23b2ff;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
  overflow: hidden;
}

.double-column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 2;
  overflow: hidden;
}

.blue-column {
  background-color: #23ff32;
  
}

.green-column {
    
    background-color: #c9ff23;
}	
	/* ------------------------------------------- */	
	
	
.twoPanelSpread {
  margin: 0px;
  padding: 0px;
  background: url( https://i.giphy.com/media/ddZXIrimeaXY0xclfC/giphy.webp )
    center repeat;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.panelColumn {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
  overflow: hidden;
}

.leftColumn {
  background-color: #2470ff;
  width: 100%;
}

.leftColumn img {
  flex-shrink: 0;
  min-width: 100%;
  min-height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.rightColumn {
  background-color: #c9ff23;
}
.rightColumn img {
  flex-shrink: 0;
  min-width: 100%;
  min-height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}
a:hover {
  color: #c9ff23;
}

.divAlbumReview {
  background-image: url("https://m.media-amazon.com/images/I/41QKR5BJVZL.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  padding: 50px;
  clear: both;
  margin: 0px;
  border-bottom: 0px dashed #c9ff23;
  font-size: 20px;
  color: white;
  font-family: Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal,
    monospace;
}

.pdivAlbumReview {
  background: rgba(255, 108, 35, 0.5);
}

.broken-width {
  width: 100%;
}

.right-width {
  min-width: 100%;
}

audio {
  -webkit-transition: all 0.5s linear;
  -moz-transition: all 0.5s linear;
  -o-transition: all 0.5s linear;
  transition: all 0.5s linear;
  -moz-box-shadow: 2px 2px 4px 0px #006773;
  -webkit-box-shadow: 2px 2px 4px 0px #006773;
  box-shadow: 2px 2px 4px 0px #006773;
  -moz-border-radius: 7px 7px 7px 7px;
  -webkit-border-radius: 7px 7px 7px 7px;
  border-radius: 7px 7px 7px 7px;
}

audio:hover,
audio:focus,
audio:active {
  -webkit-box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  -moz-box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  -webkit-transform: scale(1.05);
  -moz-transform: scale(1.05);
  transform: scale(1.05);
}

#row_image  {
border: 5px solid #ccc;
background: #666;
  max-width: 100%;
  padding: 50px;
  background-image: url("https://www.whosampled.com/static/track_images_100/mr11753_2010108_73251697983.jpg");
  background-repeat: repeat;
	}

	
.gallery {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  border-radius: 50%;
  box-shadow:
    inset 0 0 50px #fff,
    inset 20px 0 80px ##FFF300,
    inset -20px 0 80px #0AFF00,
    inset 20px 0 300px ##FFF300,
    inset -20px 0 300px #0AFF00,
    0 0 50px #fff,
    -10px 0 80px #FFF300,
    10px 0 80px #0AFF00;
  
}
.image {
  width: 100px;
  flex: 1 0 auto;
}
.featured-image {
  flex: 0 0 100%;
}

/* GiTHUB_LOGO##TEAM_SPiRiT!!! */

	/* IMAN_FRUM_SOMALiA_MY_MOMMA */
.pinupGallery {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
   object-fit: contain;
}
.pinupImage {
  width: 100px;
  flex: 1 0 auto;
}
.featured-pinupImage {
  flex: 0 0 100%;
}	
	
/* General presentation stuff */
.post-content {
	max-width: 100%;
	margin: 0 auto;
}

/* img {	max-width: 100%; }  ###MAY_BE_BREAKING_SOME_SOME_IMAGES */

/* Set content grid so it respects order values */
.post-content {
	display: grid;
}

/*
Style image if there is an image right after the heading
Use order to put it above the heading
Relative position for absolute caption
*/
.post-content h1 + .kg-image-card {
	margin: 0 -24px;
	order: -1;
	position: relative;
}


/* Style image's caption if there is an image right after the heading */
.post-content h1 + .kg-image-card figcaption {
	bottom: 0;
	left: 0;
	right: 0;
	padding: 1rem 1rem 1.2rem;
	opacity: 0.5;
	background: white;
}
</style>

## Hole To Another Universe

## DEAR_SAAATU##OH_HOW_I_MISS_YOU ##

<iframe width="100%" height="315" src="https://www.youtube.com/embed/vsfzAvOrjrc" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://i.discogs.com/qOEhIk9savxznlWZcbJucLdQ4pvaCoRFcIDiLwB0mE8/rs:fit/g:sm/q:90/h:597/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQyODIy/NTYtMTYzMzQ1NDE1/My0xNzY0LmpwZWc.jpeg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.discogs.com/qOEhIk9savxznlWZcbJucLdQ4pvaCoRFcIDiLwB0mE8/rs:fit/g:sm/q:90/h:597/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQyODIy/NTYtMTYzMzQ1NDE1/My0xNzY0LmpwZWc.jpeg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://i.discogs.com/jchhHhpFLNeVeKhk2SeAr1VEb120cgGkrJAvKGtdODs/rs:fit/g:sm/q:90/h:470/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQyODIy/NTYtMTYzMzQ1NDE1/Ny0xNjU5LmpwZWc.jpeg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.discogs.com/jchhHhpFLNeVeKhk2SeAr1VEb120cgGkrJAvKGtdODs/rs:fit/g:sm/q:90/h:470/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQyODIy/NTYtMTYzMzQ1NDE1/Ny0xNjU5LmpwZWc.jpeg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://img.discogs.com/PgzqBtQAG2NtHqHJ5tZoHfgwI0k=/fit-in/600x747/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-11117067-1512383344-8255.jpeg.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://img.discogs.com/ZNl0MnC-zKNjDFtBcyLh79njUC8=/fit-in/600x527/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-11117067-1510765865-7593.jpeg.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>



## #ZEXOR_WAS_MURDERED_LOOKiNG_FOR_HiS_FAMiLY
https://forum.12ozprophet.com/topic/88098-rip-zexor/
<iframe width="100%" height="315" src="https://www.youtube.com/embed/AT-Km8ToCGU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
## ##DOPE_ASS_RESUMES
I'm always figuring out how to present myself online. $LiNKEDiN = UNHEALTHY
## GOOD_EXAMPLES_FROM = [ https://blog.hubspot.com/marketing/best-personal-websites ]
https://quinntonharris.mystrikingly.com/ 
http://brandoncjohnson.com/
http://www.garysheng.com/
http://www.garicruze.com/
https://melaniedaveid.com/
<iframe width="100%" height="315" src="https://www.youtube.com/embed/TG1CQF18uxE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/Dt3Aj9p5KUs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1224769615&color=%2392f8fa&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/luvenchanting" title="Enchanting" target="_blank" style="color: #cccccc; text-decoration: none;">Enchanting</a> · <a href="https://soundcloud.com/luvenchanting/take-it-back" title="Take It Back" target="_blank" style="color: #cccccc; text-decoration: none;">Take It Back</a></div>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/gnsqvz9iIlA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<a href="https://www.roadandtrack.com/new-cars/news/a33293/how-to-make-a-dodge-challenger-hellcat-quicker-than-a-demon/"> <img src="https://hips.hearstapps.com/roa.h-cdn.co/assets/17/17/2560x1280/landscape-1493049234-dg016-065clq9tv22m8qdnc5i2cto9dvkunr6.jpg?resize=980:*" > </a>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1224900766&color=%23de8b80&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/kaliii" title="Kali" target="_blank" style="color: #cccccc; text-decoration: none;">Kali</a> · <a href="https://soundcloud.com/kaliii/track-1" title="Standards" target="_blank" style="color: #cccccc; text-decoration: none;">Standards</a></div>

## How to play games in the Internet Arcade
[HOW_TO_PLAY_THESE_AWESOME_GAMES - TUTORiAL_HERE##CLiCK](https://armchairarcade.com/perspectives/2014/11/06/quick-guide-on-how-to-play-on-the-internet-arcade/)
<iframe src="https://archive.org/embed/arcade_nbajamte" width="" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe src="https://archive.org/embed/arcade_720" width="560" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe src="https://archive.org/embed/arcade_xmvsf" width="560" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe src="https://archive.org/embed/arcade_souledge" width="560" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe src="https://archive.org/embed/arcade_spidman" width="560" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe src="https://archive.org/embed/arcade_archrivl" width="560" height="384" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/u6gk8JGkqlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/90375686&color=%23c9c7ca&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/johnedwardsullivan" title="John E. Sullivan" target="_blank" style="color: #cccccc; text-decoration: none;">John E. Sullivan</a> · <a href="https://soundcloud.com/johnedwardsullivan/tommy-wright-iii-ft-princess" title="Tommy Wright III Ft. Princess Loko- Still Pimpin" target="_blank" style="color: #cccccc; text-decoration: none;">Tommy Wright III Ft. Princess Loko- Still Pimpin</a></div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/83443834&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/verycherry34" title="verycherry34" target="_blank" style="color: #cccccc; text-decoration: none;">verycherry34</a> · <a href="https://soundcloud.com/verycherry34/get-low-lil-jon" title="Get Low- Lil Jon" target="_blank" style="color: #cccccc; text-decoration: none;">Get Low- Lil Jon</a></div>


<div class="post-content">
	<h1>My Conversation with a Human Trafficker</h1>
	<figure class="kg-card kg-image-card kg-card-hascaption">
<iframe src="https://player.vimeo.com/video/396000267?h=9c3699c7fc&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" width="100%" height="1920" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen title="Untitled"></iframe>
		<figcaption>ScreenCapture by <a href="#">Thaka##Rashard</a> / <a href="#">Selassie##Kelly</a></figcaption>
	</figure>
	<p> <a href="THE_##CRIME_SCENE##INSTAGRAM##ACCOUNT####MUNA_and_RASHARD##MISSING_PERSONS_DETAILS##WE_HAVE_SO_MUCH##PROOF##">https://www.instagram.com/muna_and_rashard/?hl=en</a>	
<a href="https://www.veoh.com/watch/v142164131xC426T7A">ANIME##_THIS_IS_HOW_MY_ASSASINATION_ATTEMPTS_GO##THAT_WAS_SARTU##</a>
<a href="https://www.statista.com/statistics/960103/ranking-of-most-used-online-video-platforms-in-sweden/"> Which platforms do you use to watch online video?</a>
	</p>
	<p>The Ethiopian wolf, Africa’s only wolf species, is under threat.
The Ethiopian wolf is the rarest and most endangered canid in the world — with only about 450 individuals remaining. They are restricted to seven isolated mountain enclaves in the highlands, and the two remaining strongholds for this iconic species occur in Bale Mountains National Park and Simien Mountains National Park.</p>
	<p>Main post content... lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, repellat molestiae iure repudiandae explicabo labore harum eum recusandae a voluptatibus nesciunt qui commodi magnam, quaerat quis fuga veritatis molestias esse.</p>
</div>

<iframe width="100%" height="315" src="https://www.youtube.com/embed/_woefU5WRVk" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<iframe src="https://player.vimeo.com/video/34994054?h=f303c16d3d&color=ff0179&title=0&byline=0&portrait=0" width="100%" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/sLZYxhYqm7E" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/F01fzPwBwc4" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="//im.vsco.co/aws-us-west-2/12f8b0/56497/5fc45724e1ebb64f08283bf6/vsco5fc457261e48c.jpg?w=494&dpr=1" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="//im.vsco.co/aws-us-west-2/12f8b0/56497/5fc45724e1ebb64f08283bf6/vsco5fc457261e48c.jpg?w=494&dpr=1" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://i.discogs.com/XcQ4mmfG_TqfEuTztYQSCDpucZSVKdvDWb7BtCdroaA/rs:fit/g:sm/q:90/h:597/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTExMjk5/NDI2LTE1MTM3MTA0/NTYtNjA4MC5qcGVn.jpeg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://1.bp.blogspot.com/-juCnXjGLs_I/Xnlln2ceYjI/AAAAAAABWrQ/BPDRsc9j3B0InVUrlmm948S3QBjXKDneACLcBGAsYHQ/s1600/Deltron%2B3030%2BCMJ%2BNew%2BMusic%2BMonthly%2B2001%2BJanuary_000057.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="//im.vsco.co/aws-us-west-2/12f8b0/56497/5fc4bb251d78313c14000007/vsco5fc4bb27bbd2e.jpg?w=555&dpr=1" alt="Girl in a jacket" >
      </div>
    </div>
	  
    <div class='panelColumn'>
      <div class='rightColumn'>
	      <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/CHECKING_MY_EGO_AT_THE_DOOR.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
	        
      </div>
    </div>
  </div>
</div>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/QHIUvE-IUvI" title="YouTube video player" frameborder="0"  allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/y74cRJjDJtE" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/uozhx1xeTDg" title="YouTube video player" frameborder="0"  allowfullscreen></iframe>
<div class="post-content">
	<h1>Post title</h1>
	<!-- {{content}} would be here, example rendered below -->
	<figure class="kg-card kg-image-card kg-card-hascaption">
		<img src="https://www.cultofmac.com/wp-content/uploads/2016/08/tumblr_o860yvcIUg1rnoexwo1_1280.jpg" class="kg-image">
		<figcaption>Photo by <a href="#">Harley-Davidson</a> / <a href="#">Unsplash</a></figcaption>
	</figure>
	<p>Main post content... lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis, repellat molestiae iure repudiandae explicabo labore harum eum recusandae a voluptatibus nesciunt qui commodi magnam, quaerat quis fuga veritatis molestias esse.</p>
</div>

<p><a href="https://vimeo.com/396000267">Untitled</a> from <a href="https://vimeo.com/user4243921">opo1988</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
<div class="pinupGallery">
  <img class="pinupImage featured-pinupImage" src="https://i.pinimg.com/750x/3b/ff/81/3bff81a1208ad9bcdeb4a6db3faa2267.jpg" alt="">
  <img class="pinupImage" src="https://i.pinimg.com/750x/3b/ff/81/3bff81a1208ad9bcdeb4a6db3faa2267.jpg" alt="">
  <img class="pinupImage" src="https://i.pinimg.com/750x/3b/ff/81/3bff81a1208ad9bcdeb4a6db3faa2267.jpg" alt="">
  <img class="pinupImage" src="https://i.pinimg.com/750x/3b/ff/81/3bff81a1208ad9bcdeb4a6db3faa2267.jpg" alt="">
</div>
<div class='some-page-wrapper'>
 <div class='row'>
 <div class='column'>
 <div class='blue-column'>
 <a href="https://www.youtube.com/watch?v=UAi1e7AoEWA"> <img src="https://www.victoriassecret.com/p/760x1013/tif/b2/9c/b29c194106fa4be6940fd09bc7a08f05/1117127818M2_OM_B.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 <div class='column'>
 <div class='green-column'>
 <a href="https://youtu.be/UAi1e7AoEWA"> <img src="https://www.victoriassecret.com/p/760x1013/tif/78/64/7864d0e0f2e442e0a91ef4864fdfff81/1117127818M2_OM_F.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 </div>
</div>

<div class='some-page-wrapper'>
 <div class='row'>
 <div class='column'>
 <div class='blue-column'>
 <a href="https://www.youtube.com/watch?v=UAi1e7AoEWA"> <img src="https://i.etsystatic.com/20347400/r/il/e67d19/2868035079/il_794xN.2868035079_ol8q.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 <div class='column'>
 <div class='green-column'>
 <a href="https://youtu.be/UAi1e7AoEWA"> <img src="https://i.etsystatic.com/20347400/r/il/e67d19/2868035079/il_794xN.2868035079_ol8q.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 </div>
</div>



<div class="container">
  <h1 class="neonText"> 404 </h1>
  <h2 class="neonText">2005 - 2020</h2>
</div>
<div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://bglh-marketplace.com/wp-content/uploads/2016/12/Screen-Shot-2016-12-06-at-6.12.57-PM.png" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://bglh-marketplace.com/wp-content/uploads/2016/12/Screen-Shot-2016-12-06-at-6.12.57-PM.png" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<img src="https://bglh-marketplace.com/wp-content/uploads/2016/12/Screen-Shot-2016-12-06-at-6.12.57-PM.png" alt="##DANCE411_IS_MY_HAREM##AND_ALL_THE_ONES_PRE_ERIKA_AND_POST_PROSTITUTION##TRIBAL_RIGHTS_ACT">
## PSYCHOLOGICAL_SEPARATION_USING_PADDING 
### I need to separate post and days cleanly... 
[padding](https://developer.mozilla.org/en-US/docs/Web/CSS/padding-top) [border](https://developer.mozilla.org/en-US/docs/Web/CSS/border-top)
## HTML5 Video (w3SCHOOLS_eXAMPLE)
[Bare_Bones_HTML5 Video_Embed](https://www.w3schools.com/html/html5_video.asp)
[iFRAMES_HAVE_BEEN_DEPRECATED_FOR_YEARS](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe), IDK##Why_YouTube_and_ViMEO##iNSiST_OWN_USiNG_DEM_TiNGS?!?! My shit bout tah be clean! As I read the article <FRAME> not <iFRAME> is deprecated but the HTML5 <em> video </em> tag appears much more useful for my purposes.
	   {% highlight html %} <video width="320" height="240" controls>
      <source src="movie.mp4" type="video/mp4">
      <source src="movie.ogg" type="video/ogg">
      <-- Your browser does not support the video tag. -->
    </video> {% endhighlight %} <em> Now i get it, [##ACCESSABILITY](https://www.w3.org/WAI/fundamentals/accessibility-intro/)they can access more users using an iframe... HTML5 is not going to be healthy with people accessing the content from older computers in poor regions where they may only have access to, for example Windows2000 and Internet Explorer 6... So, I need to do more research. Most people are on Mobile phones, however blog lovers often have a desktop, tablet, or laptop for reading and viewing information. ### HTML5 tEST -> [ALL_ABOUT_Que] https://youtu.be/wGAQNzCXX-c 
	
<video width="50%" height="50%" style="clear:left; float: left" controls>
        <source src="https://mirkoreisser.de/wp-content/uploads/2022/03/NFT_DAIMforUkraine_ArtistForUkraine_2022_Preview.mp4">
      </video>

 ### SorryBabeDat_SHiTBROKE = [YouTube](did their research) Here is ya song... Thanks for making my day <3 <iframe width="100%" height="315" src="https://www.youtube.com/embed/Zh25aap8gH8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> ## Eric is helping me here [Eric_Meyer](https://github.com/meyerweb) got me interested in webdesign years ago with what I call his [ Nautilus design](https://meyerweb.com/eric/css/edge/complexspiral/glassy.html). I have always enjoyed graphic arts. After my mother and I were kidnapped, the home I grew up in with her sister and her kidnapper was stocked high with [National Geographic Magazines ](https://lifeasahuman.com/2015/media-tech/media/why-i-save-old-national-geographic-magazines/) and [ Watchtower and AWAKE Magazines](https://vatican.com/The-Americas-Watchtower-Magazines%e2%80%92-Jehovah-Witness/6633/502/4583/g17Watchtower%20Magazines-%20Jehovah%20Witness'e16'1/295/) and being from ##LOS_ANGELES I had a lot of exposure to [graffiti art](https://www.graffiti.org/) and my brothers were [Graffiti Writers](http://www.at149st.com/history.html). So when I got my first exposure to the web in 1997, I wanted in, but had no Idea what to do. After two to three years of infreaquent browsing due to the rarity and scarcity of computers, much less computers with internet connections [SCAD opened its library to the public](https://www.scad.edu/life/buildings-and-facilities/jen-library) and while I wanted to go for graphic design, my foster parents could not affor it. It was about $100,000 for a ##GRAPHIC_DESIGN_DEGREE. ##WiLLiE_KELLY_JR_MY_KIDNAPPER only made around $35,000 a year. Even if he would pay for college it was not even worth asking and SCAD had noprograms for local residents. Eric's Design looked incredible on the library's [Bondi Blue First Generation iMACS](https://everymac.com/systems/apple/imac/specs/imac_ab.html). That machine was like $1,300 so I could never get one on my own... I struggled to get [The Original Playstation in 1995](https://www.britannica.com/topic/PlayStation), it was only $300. I have never had a new computer of my own. I did use them in corporate... I in someways worked for new computers for years while dealing with ##East_AFRICAN_ISSUES. THis codeblock will according to Eric, make my site more readable across more platforms >>> {% highlight css %} /* <-- Begin #ERiC_MEYERS_CSS_TOOLS */ /* <-- Begin #ERiC_MEYERS_CSS_TOOL */ /* http://meyerweb.com/eric/tools/css/reset/ v2.0 | 20110126 License: none (public domain) */ html { margin: 0; padding: 0; border: 0; font-size: 100%; font: inherit; vertical-align: baseline; } /* HTML5 display-role reset for older browsers */ article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section { display: block; } body { line-height: 1; } ol, ul { list-style: none; } blockquote, q { quotes: none; } blockquote:before, blockquote:after, q:before, q:after { content: '' ; content: none; } table { border-collapse: collapse; border-spacing: 0; } /* <-- end #ERiC_MEYERS_CSS_RESET_TOOL */ {% endhighlight %} 
 
 # Saturday, November 27th  
    <p>&#x1F525 &#x1F525 &#x1F525 &#x1F525 &#x1F525 </p>
<img src="http://static1.squarespace.com/static/56858337cbced60d3b293aef/568d70177086d7180fc3bbe5/5e7be917ca3a9d59fc74689c/1655723593702/Albumism_OlDirtyBastard_ReturnToThe36Chambers_MainImage_2x1.jpg" >
<iframe width="100%" height="315" src="https://www.youtube.com/embed/HqylXv4Usn8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 
	
## SOMETYPE_OF_WAY_I_WILL_END_UP_SOMEWHERE_I_BELONG(damn... #iym_hella_emo_today) 
	
<iframe width="100%" height="315" src="https://www.youtube.com/embed/-KKbdErJkiY" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/zsCD5XCu6CM" title="YouTube video player" frameborder="0" allowfullscreen></iframe> 
 ## ##LiNKiN_PARK_NAWT_LiNKEDiN_ERiKA 
<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/736x/eb/ac/4e/ebac4e41a7ddf7460dba012f67b69765.jpg" alt="Girl in a jacket" > https://www.youtube.com/watch?v=H5O9rd9NuMg&t=2s
https://www.youtube.com/watch?v=Ttb8tcdE0PA&t=786s
https://www.youtube.com/watch?v=x827FWFWGi8
https://www.youtube.com/watch?v=ecFE-WOJLxA
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/736x/eb/ac/4e/ebac4e41a7ddf7460dba012f67b69765.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
															      
[ ##voyeurism##_OUT_IN_THe_OPEN_ON_YOUTUBE##MY_FAMILY_HAS_THIS_ISSUE## :^( ](https://www.youtube.com/watch?v=oETVDKbThcE)
<a href="https://youtu.be/C6fEKP_tlC8"> <img class="bwtocolor" src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/SAA2%23%23SARTUZEE%23%23ART.jpg" alt="##ELLA_FITZGERALD##_and_##LOUiE_ARMSTROG##" > </a>
<span class="neonText">
 ##WH0L34LBUM##PORGY&BESS##LOUiS&ELLA##JAZZ##VOCAL##SOUNDTRACK##!
 ##CLICK_THE_IMAGE_OF_AFFECTION_TO_WATCH##ROMANCE##
 <> span </span>
<a href="https://www.youtube.com/watch?v=YIdrZxaP-gE"> <img class="bwtocolor" src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/porgy_and_bess_still_splash.jpg" alt="##DORTHY_DANDRIDGE##_and_##SIDNEY_POTIER##" > </a>

<div class='some-page-wrapper'>
 <div class='row'>
 <div class='column'>
 <div class='blue-column'>
 <a href="https://www.youtube.com/watch?v=ARtRsMnTqQc"> <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/WEenNWEE.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 <div class='column'>
 <div class='green-column'>
 <a href="https://youtu.be/ZmPfxMBNilg"> <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/WEenNWEE.jpg" alt="Girl in a jacket" > </a>
 </div>
 </div>
 </div>
</div>
<div class='row'>
 <div class='column'>
 <div class='blue-column'>
 <a href="https://youtu.be/NZ3kfDBAJWc"> 
<img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/ea067fa2ad50680d5a38a2503aab94d1473f7925/img/IMG_3904_800x.jpg" alt="Porgy & Bess" > </a>
 </div>
 </div>
 <div class='column'>
 <div class='green-column'>
 <a href="https://youtu.be/-DR6cXAa-Ek"> <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/porgy-and-bess-w-louis-armstrong.jpg" alt="##ELLA_FITZGERALD##_and_##LOUiE_ARMSTROG##" > </a>
 </div>
 </div>
<div class="row">
    <div class="column">
      <div class="blue-column">
        <img src="https://mirkoreisser.de/wp-content/uploads/2022/03/DAIMforUkraine_ArtistsForUkraine_2-scaled.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>
    <div class="column">
      <div class="green-column">
        <img src="https://mirkoreisser.de/wp-content/uploads/2022/03/DAIMforUkraine_ArtistsForUkraine_2-scaled.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>
 <div class="column">
      <div class="blue-column">
        <img src="https://mirkoreisser.de/wp-content/uploads/2022/03/DAIMforUkraine_ArtistsForUkraine_2-scaled.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>	
  </div>

<a alt="DREEZY_IS_HIS_WIFE" href="https://i.scdn.co/image/ab67616d0000b273a02c33fd1684b4292e4724ca"  target="_blank" > <img src="https://i.scdn.co/image/ab67616d0000b273a02c33fd1684b4292e4724ca" > </a>

<iframe height="300px" style="width: 100%;" scrolling="no" title="Pure CSS 3D Synthesizer (mousedown for rotation)" src="https://codepen.io/suez/embed/GJKRPN?default-tab=css%2Cresult&editable=true" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/suez/pen/GJKRPN">
  Pure CSS 3D Synthesizer (mousedown for rotation)</a> by Nikolay Talanov (<a href="https://codepen.io/suez">@suez</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
<div class="row">
    <div class="column">
      <div class="blue-column">
        <img src="https://i.pinimg.com/750x/37/a7/21/37a721ea1aa585febee94082f1236931.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>
    <div class="column">
      <div class="green-column">
        <img src="https://i.pinimg.com/750x/37/a7/21/37a721ea1aa585febee94082f1236931.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>
 <div class="column">
      <div class="blue-column">
        <img src="https://i.pinimg.com/750x/37/a7/21/37a721ea1aa585febee94082f1236931.jpg" alt="##MY_HAS_BEEN_SPOTTED_ON_8TH_STREET_IN_LOS_ANGELES##PROSTITUTED##SHE_IS_MISSING">
      </div>
    </div>	
  </div>
<h2 class="neonText"> Its been a day since I have seen our daughter ##CORAL_IRIS_KELLY. </h2> 
Her mother mother Erika Renee Kelly was kidnapped on Feb 2,2020. A local Atlanta Matt Field bragged about it on Facebook stating "I_SOLD_HER. I found her near Venice beach California and my tattooist Kennie_Davis of ##Jolly_Roger_Tattoo in _Stockbridge#Georgia was not too far from the scene. Erika and I were not estranged when she disappeared as [ESSENCE_MAGAZiNE_STATED](https://www.essence.com/news/erika-kelly-missing-atlanta-georgia/) we were coparenting. I was laid off from my IT job at [Ionic Security](https://www.linkedin.com/company/ionic-security) after my work was repeatedly sabotaged by my manager. I opened a case with ##Fulton_County_Family_Services two months before our eviction from our ##East_Atlanta_Home_at_631_Moreland_Ave_in_Atlanta_Georgia they failed to process us after repeated visits and calls. I took odd jobs and even scored a mural gig with [Mercedes_BenZ_Stadium](https://mercedesbenzstadium.com/) for the [Atlanta_Falcons](https://www.atlantafalcons.com/). They paid me $1500 for a 40ft graffiti mural on red canvas for former athlete ##Deion_Sanders. I was severely underpaid but it covered the rent for one more month. I moved in with Constancia and her daughter ##Akeeva, got Coral in school at [Chapel Hill Elementary](https://www.chapelhilles.dekalb.k12.ga.us/) and worked hard to get a new 9-5.
 
Constancia did not like me or Coral living with her and Akeeva so they undercut me with accusations of erratic behavior and started thier own dfacs case accusing me of schizophrenia. I had no income and was repeatedly denied foodstamps and welfare by a woman named ##DANIELLE_MASHONGA_and_her_colleage##MANESSA_WARNER... ##Coral would ask <h2>##Where_is_mommy?!?</h2>I told her that Matt stole and raped her and she needs our help, so we have to keep looking. Constancia and Akeeva constantly defended Matt. He is a known pedophile and child and adult rapist in the Atlanta art community. I did not know this. We shopped at the same record store and he often offered me work. I loath rapist. I loath pedophilia. Once I learned of his ways I distanced myself. So ##Erikas_mother_and_sisters_DEFENDING_HIM, struck me as bizarre. "##Its_just_a_white_boy_joke##He_didnt_sell_her. [DFACS](https://dfcs.georgia.gov/) stalked me on Facebook and indirectly accused me of ##CHILD_MOLESTATION for a video where we were playing with a wand style muscle massager, it was innocent.  They [forcibly removed Coral](https://www.youtube.com/watch?v=AmYdIZhahrQ) saying that I was saying ["inappropriate things"](https://www.youtube.com/watch?v=9sCE3HhjSbY) and violating her by saying that her mom had been raped and kidnapped. I learned that telling Coral the ugly truth was the best way to keep a solid trust filled relationship with her.
 
In the DFACS meeting, puzzled I told Mashonga the truth, I cant find work, my reputation was being sabotaged and I could not even get a job at ##Kroger the local grocery store. I told Mashonga I needed money for food, Constancia would not feed niether me or Coral. I asked Mashonga in [This_Family_Meeting](https://www.youtube.com/watch?v=Q8NXhT6_Tx8) if she cared about me dying on the street and she shook her head, no. I was never interviewed with Coral at all, I never got a psych eval until I got to a ##UCLA_Recoup_Center_in_PalmDale_California.
 
In early October I saw Coral, in Pasadena, ##California, with a grown man wearing fishnet stockings... Shes 9. I was shot with a poison dart one day later, my skateboard stolen and my foot began to swell larger that a shoe could fit... I was rushed to the emergency room and ##UCLA ##Cut_my_foot_to_the_bone_to_drain_the_infection...
<a href="https://vimeo.com/396000267" target="_blank" >WHiTESUPREMACY</a><a href="https://vimeo.com/396000267" target="_blank" >WHiTESUPREMACY</a> <a href="https://vimeo.com/396000267" target="_blank" >WHiTESUPREMACY</a><a href="https://vimeo.com/396000267" target="_blank" >WHiTESUPREMACY</a>
<iframe title="vimeo-player" src="https://player.vimeo.com/video/651386804?h=79c650eb04" width="100%" height="360" frameborder="0" allowfullscreen></iframe>
	
	[THE_HACKER_ODYESSEY_et_SUM_PDF_LiBRARAAAY](https://vdoc.pub/documents/the-best-of-2600-a-hacker-odyssey-74jetbvnnlh0#)

<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://akns-images.eonline.com/eol_images/Entire_Site/2017107/rs_1080x1080-171107190450-23279723_777542925770459_8932444824968101888_n.jpg?fit=around%7C1080:1080&output-quality=90&crop=1080:1080;center,top" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/564x/87/c2/37/87c237ef7511042953d3d58f8af4d6c8.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/564x/df/7e/8c/df7e8c8a4889b261be9d9da5ae00d9fb.jpg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/564x/df/7e/8c/df7e8c8a4889b261be9d9da5ae00d9fb.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<a href="https://www.deviantart.com/sachsen">##CHECK_OUT_SACHSEN_ON_DEVIANT_ART</a> <em>Try to click on it.</em>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <a href="https://www.deviantart.com/sachsen/art/Afro-Brain-114793112"><img src="https://i.pinimg.com/564x/0c/3e/33/0c3e3331ea6f7c6fe47d8d200b7ff47d.jpg" alt="##TO_MY_DEAR_SELASSIE_WOMEN##SARTU##SAATU#MUNA##QUBUXE##LAHLEEBELLAH##SUMMER_and_HEATHER##BHATI##CYNTHIA_and_VAL_wit_DA_BREAD_IN_DAH_OVEN!" ></a>
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <a href="https://www.deviantart.com/sachsen/art/Afro-Brain-114793112"><img src="https://i.pinimg.com/564x/0c/3e/33/0c3e3331ea6f7c6fe47d8d200b7ff47d.jpg" alt="##TO_MY_DEAR_SELASSIE_WOMEN##SARTU##SAATU#MUNA##QUBUXE##LAHLEEBELLAH##SUMMER_and_HEATHER##BHATI##CYNTHIA_and_VAL_wit_DA_BREAD_IN_DAH_OVEN!" ></a>
      </div>
    </div>
  </div>
</div>
<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/564x/8a/6f/62/8a6f6232a31191619856168f186f0904.jpg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/564x/8a/6f/62/8a6f6232a31191619856168f186f0904.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
	  <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/564x/8a/6f/62/8a6f6232a31191619856168f186f0904.jpg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/564x/8a/6f/62/8a6f6232a31191619856168f186f0904.jpg" alt="Girl in a jacket" >
      </div>

    </div>
  </div>
</div>
<img src="https://www.game-ost.com/static/covers_soundtracks/1/6/16259_729679.jpg">
<img src="https://f4.bcbits.com/img/a0191890494_10.jpg" alt="Out From Out Where by Amon Tobin">

 <div class='row'>
    <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/564x/65/5b/a4/655ba4cb6e341f9fda1a7bdddd2077df.jpg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
        <img src="https://i.pinimg.com/564x/b9/ee/08/b9ee0813b77317a011c579c1474adb83.jpg" alt="Girl in a jacket" >
      </div>
    </div>
 <div class='column'>
      <div class='blue-column'>
        <img src="https://i.pinimg.com/564x/59/8c/52/598c5256f48e182e0dd034e2f8e875ae.jpg" alt="Girl in a jacket" >
      </div>
    </div>	
  </div>

[The U.S. National Archives ](https://www.flickr.com/photos/35740357@N03/)
<span class="neonText">
 #somalisong #Oromogirl #quxubesero
</span>
<a herf="https://www.youtube.com/watch?v=mmkdRG7MQm4" >  <img src="https://www.game-ost.com/static/covers_soundtracks/1/6/16259_729679.jpg" > </a>
<a href="https://music.amontobin.com/album/out-from-out-where" alt="##AMON_TOBiNs##BANDCAMP##PURCHASE_HERE_SO_HE_CAN_BUY_A_SMOOTHIE" ><img src="https://f4.bcbits.com/img/a0191890494_10.jpg" alt="Out From Out Where by Amon Tobin" ></a>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/197308361&color=%23d4d4cc&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/34769516&color=%23c8acac&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/34769517&color=%23ff0000&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://m.media-amazon.com/images/I/81lNOB9LbfL._SS500_.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://direct.rhapsody.com/imageserver/images/alb.304480118/500x500.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<div class="gallery">
  <img class="image featured-image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
</div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1298232526&color=%23e0dad0&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/8583021&color=%23d4cacd&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<div id="neonText">
<span class="neonText"> Can Class Action Lawsuits Be Brought in Sexual Abuse Cases? </span>
 </div>
 
<span class="firstcharacter">When</span>there are multiple individuals affected by the single or group of abusers in sexual crimes, it is sometimes possible to initiate a class action lawsuit when the statute of limitations does not pass. It is important that the victims band together and provide incontrovertible evidence to increase the strength of the claim.
<ul>
 <li><a href="https://www.hg.org/legal-articles/can-class-action-lawsuits-be-brought-in-sexual-abuse-cases-49735">DEAR_SARTU##DEAR_ERIKA##DEAR_MUNA##DEAR_LEELAHBAELAH##DEAR_LAREN##DEAR_LAURA##DEAR_RIHANNA##DEAT_SUMMER</a></li>
 <li><a href="##HOW_CAN_I_SAY_THIS##LETS_FIGHT_##DFACS##TO##GET_##CoRAL_aka_LARoC##BACK">https://www.hg.org/legal-articles/prostitution-in-the-united-states-30997</a></li>
 <li><a href="https://www.instagram.com/muna_and_rashard/"> THE_##CRIME_SCENE##INSTAGRAM##ACCOUNT####MUNA_and_RASHARD##MISSING_PERSONS_DETAILS##WE_HAVE_SO_MUCH##PROOF## </a></li>
</ul>
 <div class='some-page-wrapper'>
 <div class='row'>
 <div class='column'>
 <div class='blue-column'>
 <img src="https://i.pinimg.com/564x/cc/72/61/cc7261bf1160fe8cdfb95aaf88d4c8c1.jpg" alt="Girl in a jacket" >
 </div>
 </div>
 <div class='column'>
 <div class='green-column'>
 <img src="https://i.pinimg.com/564x/cc/72/61/cc7261bf1160fe8cdfb95aaf88d4c8c1.jpg" alt="Girl in a jacket" >
 </div>
 </div>
 </div>
</div>

<a href="https://www.veoh.com/watch/v142164131xC426T7A">ANIME##_THIS_IS_HOW_MY_ASSASINATION_ATTEMPTS_GO##THAT_WAS_SARTU##</a>
<a href="https://www.statista.com/statistics/960103/ranking-of-most-used-online-video-platforms-in-sweden/"> Which platforms do you use to watch online video?</a>


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
	
.main_content {
 
    box-shadow: rgb(163,163,163) 5px 5px, rgba(187,187,187, 0.3) 10px 10px, rgba(204,204,204, 0.2) 15px 15px, rgba(221,221,221, 0.1) 20px 20px, rgba(238,238,238, 0.05) 25px 25px;
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

p.story {
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
    url(https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/halfscreen-black.gif)
    center repeat;
  font-family: "Helvetica Neue", "Bitstream Vera Sans Mono", sans-serif, -apple-system, Monaco, 
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, ;
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

.twoPanelSpread {
  margin: 0px;
  padding: 0px;
  background: url(https://media3.giphy.com/media/ddZXIrimeaXY0xclfC/giphy.gif?cid=ecf05e47rvlxlacjxpdakk7cvxwscyzzuba10oqqwwvaycg9&rid=giphy.gif  )
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
	
</style>

## Hole To Another Universe



<div class="gallery">
  <img class="image featured-image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
  <img class="image" src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/SENORKAOS.jpg" alt="">
</div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1298232526&color=%23e0dad0&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/8583021&color=%23d4cacd&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>

<iframe width="100%" height="315" src="https://www.youtube.com/embed/9ENMHp4DKEk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/Jf63Wv6Atl8" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/zrY8TPi0kIs" title="YouTube video player" frameborder="0"  allowfullscreen></iframe>
<video controls width="100%">
    <source src="https://mirkoreisser.de/wp-content/uploads/2022/03/NFT_DAIMforUkraine_ArtistForUkraine_2022_Preview.mp4"
            type="video/mp4">
    Sorry, your browser doesn't support embedded videos.
</video>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://www.bhphotovideo.com/cdn-cgi/image/format=auto,fit=scale-down,width=500,quality=95/https://www.bhphotovideo.com/images/images500x500/canon_5554c002_rf_5_2mm_f_2_8l_dual_1633518555_1665911.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://static.bhphoto.com/images/multiple_images/images500x500/1633518955_IMG_1616416.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<img src="https://i.discogs.com/4fW7p6CcV1euzfubea03VC9oD3x2tqASxnfjOdeMItI/rs:fit/g:sm/q:90/h:600/w:595/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEwMDk5/MzUyLTE0OTE1OTE2/NzEtODIwMS5qcGVn.jpeg" >
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://i.discogs.com/rPv_MZPxS8iZgQITvzOgEo2WV5yd-gbWldGRhwedjpU/rs:fit/g:sm/q:90/h:371/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEwMDk5/MzUyLTE0OTE1OTE2/NzEtMzY0Ni5qcGVn.jpeg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAYaHOLE_TO_ANOTHER_UNIVERSE_IS_OUR_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.discogs.com/rPv_MZPxS8iZgQITvzOgEo2WV5yd-gbWldGRhwedjpU/rs:fit/g:sm/q:90/h:371/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEwMDk5/MzUyLTE0OTE1OTE2/NzEtMzY0Ni5qcGVn.jpeg" alt="HOLE_TO_ANOTHER_UNIVERSE_IS_MY_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
  </div>
</div>
<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/Screenshot%202022-07-01%2012.48.33%20AM.png" >

<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/Screenshot%202022-07-01%2012.49.16%20AM.png" >
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://upload.wikimedia.org/wikipedia/en/4/42/Mulatto_%22Bitch_from_Da_Souf%22.png" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://images.genius.com/e340ddf6971616a68049fecc163ec30c.1000x1000x1.png" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
  </div>
 </div>

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://mirkoreisser.de/wp-admin/admin-ajax.php?action=kernel&p=image&src=WyJ3cC1jb250ZW50XC91cGxvYWRzXC8yMDE5XC8xMFwvTWlya28tUmVpc3Nlci1EQUlNX0ZpbmVBcnQtUHJpbnRzX21yZjMxNzU2LTY0OS5qcGciLFtbInR5cGUiLFsid2VicCIsIjg1Il1dXV0%3D&hash=41e376ca3b4a1a3be4163f0ca652ae78" alt="##DAiM_IS_HERE_TO_STAY_WiTH_BUBBLEGUMPOP" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://mirkoreisser.de/wp-admin/admin-ajax.php?action=kernel&p=image&src=WyJ3cC1jb250ZW50XC91cGxvYWRzXC8yMDE5XC8xMFwvTWlya28tUmVpc3Nlci1EQUlNX0ZpbmVBcnQtUHJpbnRzX21yZjMxNzU2LTY0OS5qcGciLFtbInR5cGUiLFsid2VicCIsIjg1Il1dXV0%3D&hash=41e376ca3b4a1a3be4163f0ca652ae78" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1254671677&color=%23a89c90&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1297575751&color=%23cbcbcb&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<img src="https://www.graffiti.org/atl/sever_totem2_hense_b12df1_b.jpg" >
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/5fc456bce1ebb64f08283bf2/vsco5fc456bd41267.jpg" >				
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/5fc458d2e1ebb64f08283c10/vsco5fc458d330a8d.jpg" >
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1153502092&color=%236c3f42&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<img src="https://ftp.icm.edu.pl/packages/graffiti.old/boston/zelot_rath_turn_kem5_prey06.jpg" >
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/5fc45b01e1ebb64f08283c31/vsco5fc45b027a916.jpg" >
<img src="https://ftp.icm.edu.pl/packages/graffiti.old/boston/zealot_aves_mise_tint_boston_2006.jpg" >
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/5fc538211d7831291c000007/vsco5fc538244c543.jpg" >
<img src="https://www.graffiti.org/boston/mise_back_boston_2006_71.jpg" >
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/600b63321d78311648000003/vsco600b633468109.jpg" >
<img src="https://www.graffiti.org/boston/a36wet.jpg" >
<img src="https://im.vsco.co/aws-us-west-2/12f8b0/56497/600b63321d78311648000001/vsco600b633af04a1.jpg" >
<img src="https://www.graffiti.org/atl/haze7.jpg" >
<img src="https://image-aws-us-west-2.vsco.co/12f8b0/56497/60218c77ef098d3a41bfa7ad/vsco60218c793112f.jpg" >
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1208259943&color=%236c3f42&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/747778534&color=%236c3f42&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/390462771&color=%238c8c8c&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="//im.vsco.co/aws-us-west-2/12f8b0/56497/60256dab80d02b397eaa596b/vsco60256daca8c2c.jpg?w=350&dpr=1" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="//im.vsco.co/aws-us-west-2/12f8b0/56497/60256dab80d02b397eaa596b/vsco60256daca8c2c.jpg?w=350&dpr=1" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
  </div>
</div>
<img src="https://i.discogs.com/jNB0ym679sbB-AhjVnk9FExyO0XNV3h_gNV5jTZUtW4/rs:fit/g:sm/q:90/h:355/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9BLTYwOTEw/LTEzODg4MDIxNzEt/Nzk0NC5qcGVn.jpeg" >
<img src="https://thesource.com/wp-content/uploads/2022/02/AB3A9173-700x400.jpg" >
<div class="divAlbumReview" style="background-image: url( https://i.slkimg.com/isv1/artist/v5aa5fa46a24672bf/168214/1290171/web/3/center/5,0/300x300.jpg); no-repeat center center fixed" >
 <img style="float:left;width:50%;" src="https://i.discogs.com/FXr1dApzVjeUrr1_Zvd8EfnrH2llviPnYdRWS3nGeFA/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEzMTE3/MjEtMTYyNjU5NjYx/NS02NTMyLmpwZWc.jpeg" /> 
  
  <img style="float:right;width:50%;" src="https://i.discogs.com/l6EPHxxFytxo2nyj9SOhUPaaKusc6l41wE7EdtN9BvQ/rs:fit/g:sm/q:90/h:598/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEzMTE3/MjEtMTYyNjU5NjYx/NS02MjQ2LmpwZWc.jpeg" />
 <p class="pdivAlbumReview"> 
 
<span class="firstcharacter">The Supremes – I Hear A Symphony
Label:	Motown – M5-147V1</span>
From DiSCOGS, the free encyclopedia
	 

Format:	
Vinyl, LP, Album, Reissue
Country:	US
Released:	1981
Genre:	Funk / Soul, Pop
Style:	Rhythm & Blues, Soul
A1		Stranger In Paradise
Composed By [Music] – Alexander Borodin
Written-By – George Forrest, Robert Craig Wright
A2		Yesterday
Producer – Norman Whitfield
Written-By – Lennon-McCartney
A3		I Hear A Symphony
Written-By – Holland-Dozier-Holland
A4		Unchained Melody
Written-By – Alex North, Hy Zaret
A5		With A Song In My Heart
Written-By – Rodgers & Hart
A6		Without A Song
Written-By – Billy Rose, Edward Eliscu, Vincent Youmans
B1		My World Is Empty Without You
Written-By – Holland-Dozier-Holland
B2		A Lover's Concerto
Written-By – Denny Randell, Sandy Linzer
B3		Any Girl In Love (Knows What I'm Going Through)
Written-By – Holland-Dozier-Holland
B4		Wonderful, Wonderful
Written-By – Ben Raleigh, Sherman Edwards
B5		Everything Is Good About You
Written-By – Edward Holland, Jr., James Dean (3)
B6		He's All I Got
Written-By – Holland-Dozier-Holland
Backing Vocals – Florence Ballard, Mary Wilson
Lead Vocals – Diana Ross
Producer – Holland & Dozier (tracks: A1, A3 to B6)
"1st pressings" of this release are “MM 643 Mono” or MS 643 Stereo”, they have a full color front artwork with no border only a top white banner with Stereo text. Back cover states copyright 1966 in lower left corner.

Reissues have copyright 1966 info in middle of back panel and have full front framing white border with Stereo in text on top.</p>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/bpL1TTxffO0" title="YouTube video player"  allowfullscreen></iframe>
 </div>
[HUMA](https://www.pinterest.com/pin/7107311903800054/)
<a href="https://youtu.be/DFMEBquxeO8" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example1.jpg" /> </a>
<img src="https://thesource.com/wp-content/uploads/2022/02/AB3A9173-700x400.jpg" alt="####KALI_IS_MY_WIFE_AS_WELL_MUNA_is_STILL_MUNI##BUBBLEGUM_POP##IS_HERE_TO_STAY" >

<img src="https://i.ytimg.com/vi/WaLr2R2Dxuc/maxresdefault.jpg" alt="####KALI_IS_MY_WIFE_AS_WELL_MUNA_is_STILL_MUNI##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
<a href="https://youtu.be/Qw-HQxpewWI" alt="DEAR_SAATU##_ITS_TIME_FOR_A_DEEP_SURPRISE" ><img src="https://f4.bcbits.com/img/a4167468696_10.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" > </a>

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/NATURALMYSTIC45a.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.discogs.com/-cZrLCOY7Z_umwRKPsdQjjiSrwopzp17V5OMFZOP-Ms/rs:fit/g:sm/q:90/h:600/w:588/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEzNzM5/NjMtMTU4NzQ4OTE4/OC03OTE5LmpwZWc.jpeg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>


<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/NATURALMYSTIC45a.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/bob-marley-natural-mystic-12-hear-lee-perry-roots-dub-reggae-daddy-kool_9210518.jpg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>

<a href="https://youtu.be/DFMEBquxeO8" target="_blank" ><img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/VAliD_CSS_ERiKA_THANKS_SO_MUCH_FOR_THE_MEMORIES_AND_SUPPORT_IN_TELEPATHYTHE_oTHER_night.PNG" > </a>

<div id="row_image">

<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/img355.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >

</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BuBBLEGUMPOP_CSS4DANCE411.PNG" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BuBBLEGUMPOP_CSS4DANCE411a.PNG" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<div >

<a href="https://www.youtube.com/c/TapeDeckWreck" target="_blank"> <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/Capture.PNG" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" > </a>

</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://imageio.forbes.com/specials-images/imageserve/605910426b54abc90fcd1a1b/Audio-cassettes-have-spiked-during-the-pandemic/960x0.jpg?format=jpg&width=960" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://imageio.forbes.com/specials-images/imageserve/605910426b54abc90fcd1a1b/Audio-cassettes-have-spiked-during-the-pandemic/960x0.jpg?format=jpg&width=960" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>

 <img src="https://i.scdn.co/image/ab67616d0000b273b029b7c6ee626bdcd432545e" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
 <img src="https://www.covercentury.com/covers/dreamcast/s/dc_sonicadventure.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >

<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://lostmediawiki.com/images/d/dc/Sa1jp.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://pbs.twimg.com/media/FLA4s97XEAI1mbA?format=jpg&name=900x900" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
![AMON_TOBIN_SOLID_STEEL](https://ninjatune.net/images/releases/solid-steel-presents-amon-tobin-main.jpg)
![AMON_TOBIN##PERMUTATION##](https://f4.bcbits.com/img/a1983715436_10.jpg)
[DOWNLOAD_AMON_TOBIN_PERMUTATION_FROM_BANDCAMP](https://music.amontobin.com/album/permutation)
[##THAKA_BEKELE_SELASSIE = ##SULTAN_DROPS##](https://www.youtube.com/watch?v=MbVPev7akDI)
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/811b309218cfc0249cfe8444edeaacdf5d7a1a6c/img/vsco5fc454cf67712.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAYaHOLE_TO_ANOTHER_UNIVERSE_IS_OUR_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/811b309218cfc0249cfe8444edeaacdf5d7a1a6c/img/vsco5fc454cf67712.jpg" alt="HOLE_TO_ANOTHER_UNIVERSE_IS_MY_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
  </div>
</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/vsco5cfd9f85d1d95.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAYaHOLE_TO_ANOTHER_UNIVERSE_IS_OUR_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/vsco5cfd9f85d1d95.jpg" alt="HOLE_TO_ANOTHER_UNIVERSE_IS_MY_FANART_FROM_THE_SQUARE_ENIX_GAME_LIFE_IS_STRANGE" >
      </div>
    </div>
  </div>
</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://m.media-amazon.com/images/I/51D0Q9RDFSL.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.scdn.co/image/ab67616d0000b2734f1a91e8d19ff7e39b671b25" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<a href="https://youtu.be/yJcks5n43hs" alt="I_WONT_BACK_DOWN_GIVE_HIM_HIS_THUNDAHDET_WUZ_MUNI_LOWNG" > <img src="https://media.pitchfork.com/photos/5c9112047741b65a56c6c4f5/1:1/w_600/ChemicalBrothers_NoGeography.jpg" /><a/>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/CB_MAH_PACKSHOT_ART.webp" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/holetoanotheruniverse/gh-pages/img/ELLIE%23%23JAPANESEcover.jpg " alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://e.snmc.io/i/300/s/ffbf35c9df5d3c5aadb7c3da00936c81/1669098" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://e.snmc.io/i/300/s/ffbf35c9df5d3c5aadb7c3da00936c81/1669098 " alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<img src="https://fordcobraengines.com/wp-content/uploads/2015/04/IMG_4180-e1463598105418.jpg" alt="COYOTE_CRATE_ENGINE" >
	


<h2 class="neonText"> Its been 774 days since I have seen our daughter ##CORAL_IRIS_KELLY##SELASSIE ~> </h2> 
<span class="firstcharacter">Her mother Erika Renee Kelly was kidnapped from ##EAST_ATLANTA##GEORGiA on Feb 2,2020. A local Atlanta man named Matt Field bragged about it on Facebook stating "I_SOLD_HER".</span> 

I found her near Venice beach California and my tattooist Kennie_Davis of ##Jolly_Roger_Tattoo in _Stockbridge#Georgia was not too far from the scene. Erika and I were not estranged when she disappeared as [ESSENCE_MAGAZiNE_STATED](https://www.essence.com/news/erika-kelly-missing-atlanta-georgia) we were coparenting. I was laid off from my IT job at [Ionic Security](https://www.linkedin.com/company/ionic-security) after my work was repeatedly sabotaged by my manager. I opened a case with ##Fulton_County_Family_Services two months before our eviction from our ##East_Atlanta_Home_at_631_Moreland_Ave_in_Atlanta_Georgia they failed to process us after repeated visits and calls. I took odd jobs and even scored a mural gig with [Mercedes_BenZ_Stadium](https://mercedesbenzstadium.com/) for the [Atlanta_Falcons](https://www.atlantafalcons.com/). They paid me $1500 for a 40ft graffiti mural on red canvas for former athlete ##Deion_Sanders. I was severely underpaid but it covered the rent for one more month. I moved in with Constancia and her daughter ##Akeeva, got Coral in school at [Chapel Hill Elementary](https://www.chapelhilles.dekalb.k12.ga.us) and worked hard to get a new 9-5.
 
Constancia did not like me or Coral living with her and Akeeva so they undercut me with accusations of erratic behavior and started thier own dfacs case accusing me of schizophrenia. I had no income and was repeatedly denied foodstamps and welfare by a woman named ##DANIELLE_MASHONGA_and_her_colleage##MANESSA_WARNER... ##Coral would ask </p>
<h2> ##Where_is_Mommy?!?</h2>
<p>I told her that Matt stole and raped her and she needs our help, so we have to keep looking. Constancia and Akeeva constantly defended Matt. He is a known pedophile and child and adult rapist in the Atlanta art community. I did not know this. We shopped at the same record store and he often offered me work. I loath rapist. I loath pedophilia. Once I learned of his ways I distanced myself. So ##Erikas_mother_and_sisters_DEFENDING_HIM, struck me as bizarre. "##Its_just_a_white_boy_joke##He_didnt_sell_her". [DFACS](https://dfcs.georgia.gov/) stalked me on Facebook and indirectly accused me of ##CHILD_MOLESTATION for a video where we were playing with a wand style muscle massager, it was innocent.  They [forcibly removed Coral](https://www.youtube.com/watch?v=AmYdIZhahrQ) saying that I was saying ["inappropriate things"](https://www.youtube.com/watch?v=9sCE3HhjSbY) and violating her by saying that her mom had been raped and kidnapped. I learned that telling Coral the ugly truth was the best way to keep a solid trust filled relationship with her.
 
In the DFACS meeting, puzzled I told Mashonga the truth, I cant find work, my reputation was being sabotaged and I could not even get a job at ##Kroger the local grocery store. I told Mashonga I needed money for food, Constancia would not feed niether me or Coral. I asked Mashonga in [This_Family_Meeting](https://www.youtube.com/watch?v=Q8NXhT6_Tx8) if she cared about me dying on the street and she shook her head, no. I was never interviewed with Coral at all, I never got a psych eval until I got to a ##UCLA_Recoup_Center_in_PalmDale_California.
 
In early October I saw Coral, in Pasadena, ##California, with a grown man wearing fishnet stockings... Shes 9. I was shot with a poison dart one day later, my skateboard stolen and my foot began to swell larger that a shoe could fit... I was rushed to the emergency room and ##UCLA ##Cut_my_foot_to_the_bone_to_drain_the_infection... <del>I cant run any more and am now handicapped</del> 
## I_HAVE_HEALED to the point of skating via my familys physical-therapy regimine to keep us healthy as dancers. But my toe on the foot that endured the injury still does not work properly and <ins>I now struggle to run</ins>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/Q8NXhT6_Tx8" title="YouTube video player"  allowfullscreen></iframe>

<iframe width="100%" height="400" src="https://www.youtube.com/embed/9sCE3HhjSbY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="400" src="https://www.youtube.com/embed/AmYdIZhahrQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<h2>Her_Former_Life_With_Me</h2>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/-oZuyrU764s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/CsM4jNSAm4A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/ydGxlS8l7Y0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
## B25_CRASHED_iNTO_EMPiRE_STATE_TOWERE_1945
### Why did'nt the whole building go down?
[I found out about it in the book The New York Times Page One: Major Events 1900-1998 As Presented in the New York Times Hardcover](https://www.alibris.com/search/books/isbn/9781578660322)
[Original article](https://www.nytimes.com/1945/07/29/archives/b25-crashes-in-fog-hole-18-by-20-feet-torn-through-north-wall-by.html?smid=url-share)





<a href="https://youtu.be/R2rct18-iSM" target="_blank">
<img src="https://m.media-amazon.com/images/I/51I6d3hyr0L._SX355_.jpg" alt="an image" title="The title of this image"/>
 </a>

## Everything should be done in love.
### - 1 Corinthians 16:14

<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/795229738&color=%2300ff7c&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://m.media-amazon.com/images/I/814ZXaN+cIL._SL1500_.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/ssdba1.jpg " alt="PUFFAH_iNTiMiDATED_ME_WHEN_I_WAS_LISTENING_TO_THIS_ALBUM_I_LIED_AND_SAID_I_WAS_LISTENING_TO_OUTKAST___THEN_I_HAD_TO_LEARN_ALL_THEIR_MUSIC" >
      </div>
    </div>
  </div>
</div>
<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/so_so_def_bass_all_stars__vol__2_album_insert_by_eppsart_dc0sps0-fullview.jpg" />
<a href="https://www.youtube.com/watch?v=gGrjTYoPEw8" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/77274.jpg" alt="Normani_iS_iN_TEARS##THiS_iS_MY_WIFE_SARTU_AHMED_SELASSiE_IN_HER_CAREER_NAME" width="100%" /><a/>
<a href="http://wiki.gis.com/wiki/index.php/Binary_large_object" > <img src="https://media.geeksforgeeks.org/wp-content/uploads/20200428220134/BLOB.png" /><a/>
<a href="https://youtu.be/DFMEBquxeO8" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example1.jpg" /> </a>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeLeaRNiNGWEBDESiGN1.PNG" /><a/>
<a href="https://www.youtube.com/watch?v=EX8soUV_CAg" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeLeaRNiNGWEBDESiGN.PNG" /><a/>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeiSBEAUTiFUL.PNG" /><a/>
<a href="http://www.ericmeyeroncss.com" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeMiCHELLEBRANCHE.PNG" /><a/>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example1.jpg" /> </a>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeHaCkeRs.PNG" /><a/>
<a href="http://www.ericmeyeroncss.com" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeHaCkeRs26000.PNG" /><a/>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_demonstration.jpg?itok=CyDRb7ye" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_city.jpg?itok=MJSd2yw9" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_cluster/bd_cluster_example1.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_aquatico/bd_aquatico_example1.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_supper/bd_supper_example1.jpg" /> </a>

<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_supper/bd_supper_example5.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_apotheke/bd_apotheke_example1.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example3.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example1.jpg" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_car.jpg?itok=fr33wXWz" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_grave.jpg?itok=zKHQ2_XK" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_demo_tshirt2.jpg?itok=Z-FDybri" /> </a>
<a href="https:://typedifferent.com" target="_blank" ><img src="https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_demonstration.jpg?itok=CyDRb7ye" /> </a>
![NiRVANA_i_APOLOGiZE](https://pbs.twimg.com/media/ELGYaVYUUAIpygF?format=jpg&name=small)
[CSS Hovers and Rollovers](https://accessibility.psu.edu/css/rollovers/)
[Law – Unreleased Jungle Selection](https://www.youtube.com/watch?v=h7T8br7jO80)
[DJ SHARPEY presents, Route Into Darkness - Jungle DNB Mix | 1994 1995 | Vinyl Only](https://www.youtube.com/watch?v=VspuYfZcjQ4)
[1994 - 2004 Jungle / Drum & Bass Old Skool Mix (Mickey Beam)](https://www.youtube.com/watch?v=PCXuCLbFGo4)
<img src="https://i.discogs.com/N1EA9fc-ZaWSRoOAd9bV4om8xqjogZUMNzdhZ_JMv3k/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTEwMDgy/MTItMTE4MzQ4NTEx/OC5qcGVn.jpeg" />
<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/Screenshot%202022-06-27%206.37.45%20AM.png" />
<iframe width="100%" height="315" src="https://www.youtube.com/embed/uSPHfbHy2Bw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<img src="https://i.discogs.com/p2AO_94h3yUfefkVCD7t6JDP-s9-6JjfE0jKLBnfq-w/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTE1MjIx/MDMtMTUxOTU4Mjk5/OS01MjY1LmpwZWc.jpeg" />
https://youtu.be/P0180ESQPC0 />
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/281668848&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true">
</iframe><iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/43359151&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="350" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/66603430&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="400" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/708018244&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>

<a href="https://etc.usf.edu/lit2go/35/aesops-fables/388/the-father-and-his-sons"> The Father And His Son <em> ::</em> Aesop's Fables</a> 
<audio controls class="broken-width">
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-010-the-boy-who-cried-wolf.375.mp3" type="audio/mp3" />
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-023-the-father-and-his-sons.388.mp3" type="audio/mpeg" />
  Your browser does not support the <code>audio</code> element.
</audio>

<a href="https://etc.usf.edu/lit2go/35/aesops-fables/388/the-father-and-his-sons"> The Father And His Son <em> ::</em> Aesop's Fables</a> 
<audio controls class="broken-width">
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-010-the-boy-who-cried-wolf.375.mp3" type="audio/mp3" />
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-023-the-father-and-his-sons.388.mp3" type="audio/mpeg" />
  Your browser does not support the <code>audio</code> element.
</audio>


<audio controls class="right-width">
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-003-the-bald-man-and-the-fly.368.mp3" type="audio/mp3" />
  <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-005--the-bats-the-birds-and-the-beasts.370.mp3" alt="THE_BAT_and_THE_BiRDs" type="audio/mpeg" />
  Your browser does not support the <code>audio</code> element.
</audio>
<!-- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio#Basic_usage -->

<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/Screenshot%202022-06-26%208.35.52%20PM.png" />
<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/Screenshot%202022-06-26%2011.30.38%20PM.png" />
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1153502092&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1137606826&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1271724856&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/306751252&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/34767310&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/36098956&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/252194269&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://m.media-amazon.com/images/I/41IpJNU3zQL._SY580_.jpg" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://i.discogs.com/yquUk3jRRu5m8b0XMRtzAXQErWlYbcGmPOUwaW0yVJk/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTExMTA3/NTYtMTQ5Nzk4NDEy/NC00MDM2LmpwZWc.jpeg" alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<iframe width="75%" height="315" src="https://www.youtube.com/embed/irjofIZKsq4" title="YouTube video player" frameborder="0"  allowfullscreen></iframe>
<img style="float:left;width:100%;" src="https://images.eil.com/large_image/ANITA_BAKER_CAUGHT%2BUP%2BIN%2BTHE%2BRAPTURE-695540.jpg" />
<div class="divAlbumReview">
 <img style="float:left;width:50%;" src="https://i.discogs.com/nokYmhZh4gUe1NYfMaUzKoCZ059Svbyhr9exCbGlRKQ/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQzMDg0/NzAtMTQwMDc5NTEy/OC03NDgxLmpwZWc.jpeg" /> 
  
  <img style="float:right;width:50%;" src="https://i.discogs.com/PploTmKY_FiBuPtziQo78sOn3tIsoxqXHh2d8nz5YMk/rs:fit/g:sm/q:90/h:600/w:600/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTQzMDg0/NzAtMTQwMDc5NTEy/OC03MDE4LmpwZWc.jpeg" />
 <p class="pdivAlbumReview"> 
 
<span class="firstcharacter">Caught Up (Millie Jackson album)</span>
From Wikipedia, the free encyclopedia
Jump to navigationJump to search
Caught Up
Caughtup.jpg
Studio album by Millie Jackson
Released	1974
Recorded	1973-1974
Studio	Muscle Shoals Sound Studio, Sheffield, Alabama
Criteria Studios, Miami, Florida
Genre	Deep soul
Length	35:59
Label	Spring
Producer	Brad Shapiro
Millie Jackson chronology
I Got To Try It One Time
(1974)	Caught Up
(1974)	Still Caught Up
(1975)
 
Professional ratings
Review scores
Source	Rating
Allmusic	 [1]
Christgau's Record Guide	A–[2]
Caught Up is the fourth album by R&B musician Millie Jackson. It includes the hit singles, "(If Loving You Is Wrong) I Don't Want to Be Right", "The Rap" and "I'm Through Trying to Prove My Love to You." A concept album, Caught Up follows the story of a woman having an affair with a married man. Side A features Jackson singing from the mistress' point of view and Side B is told from the wife's point of view.

Track listing
Side A
"(If Loving You Is Wrong) I Don't Want to Be Right" (Homer Banks, Carl Hampton, Raymond Jackson) – 3:56
"The Rap" (Millie Jackson) – 5:53
"(If Loving You Is Wrong) I Don't Want to Be Right (Reprise)" (Homer Banks, Carl Hampton, Raymond Jackson) - 1:13
"All I Want is a Fighting Chance" (Millie Jackson, King Sterling) – 2:37
"I'm Tired of Hiding" (Phillip Mitchell, Billy Clements) – 3:51
Side B
"It's All Over but the Shouting" (Millie Jackson, King Sterling) – 2:51
"So Easy Going, So Hard Coming Back" (Phillip Mitchell) – 4:07
"I'm Through Trying to Prove My Love to You" (Bobby Womack) – 5:48
"Summer (The First Time)" (Bobby Goldsboro) – 5:43
Personnel
Millie Jackson - vocals, concept
Barry Beckett - keyboards
David Hood - bass
Roger Hawkins - drums
Jimmy Johnson - guitar
Mike Lewis - orchestration
Tom Roady, Brad Shapiro - percussion
Technical
   David Wiseltier - cover design</p>
   <iframe width="100%" height="315" src="https://www.youtube.com/embed/mutUj7oMBzE" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
 </div>
<a src="https://youtu.be/u58ljXHvFzM" > <img style=" width:100%;" alt="##BARRY_WHiTE##CANT_GET_ENOUGH" src="https://images.genius.com/b0666620c6c7378c1e9fe5c38d0d453d.1000x1000x1.jpg" /></a>
</br>
<a src="https://www.cssfontstack.com/monospace"> CSS font styling tool for  ##READABiLiTY </a>
<img style="float:right; width:100%; height:100%;" alt="##iTS_THA_ONE_HUNNiD_EMOJi" src="https://upload.wikimedia.org/wikipedia/commons/0/03/Emoji_u1f4af.svg">
<div class='twoPanelSpread'>
  <div class='row'>
    <div class='panelColumn'>
      <div class='leftColumn'>
        <img src="https://static.wixstatic.com/media/f15be5_6dff88762912492dacd6d9a1b67ab345~mv2.jpg/v1/fill/w_500,h_500,al_c,q_85,usm_0.66_1.00_0.01/f15be5_6dff88762912492dacd6d9a1b67ab345~mv2.webp" alt="##BUBBLEGUM_POP##IS_HERE_TO_STAY" >
      </div>
    </div>
    <div class='panelColumn'>
      <div class='rightColumn'>
        <img src="https://static.wixstatic.com/media/f15be5_0aba132ee8434e5aafdc0e3fc33cbd1b~mv2.jpg/v1/fill/w_500,h_500,al_c,q_85,usm_0.66_1.00_0.01/f15be5_0aba132ee8434e5aafdc0e3fc33cbd1b~mv2.webp " alt="Girl in a jacket" >
      </div>
    </div>
  </div>
</div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/66603430&color=%23aec5d5&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/Screenshot%202022-06-26%201.15.24%20PM.png" />
<img class="right" src="https://upload.wikimedia.org/wikipedia/commons/a/a8/Downrock.jpg?1639357739125" alt="Floor RocKER" /> 
<span class="firstcharacter">I</span>n 1969, when James Brown was getting down with his big hit "Get on the Good Foot" the big dance style of the day appeared. This almost acrobatic dance became rather well known around New York City: kids in New York were doing the Good Foot - better known as B-Boy(the 'B' in b-boy usually doesn't correspond to a specific word, but most likely means "Boogaloo" or "Break") - which was the direct precursor to the sort of breakdancing we know today. As for origins it was the African people's dance culture which brought the heavy rhythm and the idea of dancing in a circle, but it was definitely a variety of influences that made up early B-Boying including gymnastics, Eastern martial arts, tap dance, Salsa, Afro-Cuban and Native American dances. One of the most influential dances was a South American martial arts/fighting dance known as the Capoeira.

By the time the Good Foot became the new dance style, the tradition of dance battle was well established. Dancers would gather at places like Harlem World on 116th Street in Harlem and Battle-dancewise. Battles are covered in more detail in the section on battles, challenges, and contests, but the important thing is that Breakdancing was particularly well-suited for competition and it appealed to certain young men who were very athletic.

The Good Foot, which was soon to be called B-Boy and shortly after that <a href="https://www.danceclass.com/breakdancing-music.html">Breakdancing</a>, or Breaking, was very different from the Breaking we see today. In some ways it was simpler. There were no headspins, no windmill, no handglides or backspins. It was what is now called old-style Breaking. It consisted only of floor work, involved some extremely complicated leg moves done very fast and in a way it was more complex than modern Breaking.

Among those for whom old-style breaking was especially popular were many of the youths and street gangs that roamed the South Bronx. And it was in those streets that Breakdancing really started. Often, the best Breakers in opposing gangs would battle dancewise instead of fighting. A breakdancing battle is when dancers 'fight' against each other on the dance floor without contact. They form a circle and take turns trying to show each other up through better style, more complex move<img style="float:right;" src="https://calisphere.org/clip/500x500/8db0bd01cab257a19ab8d35b5ffe8fba" alt="Floor RocKER" /> combinations, or tougher moves. Unfortunately, these Breaking battles did not always stop fight. In fact, they often would cause a fight, since dancers would sometimes get physical when they couldn't win dancewise. Some of these crews became very dedicated to their dancing, and since they had nothing better to do, would spend hours a day practicing, developing more and more complex moves, improving their form, and increasing their speed.

And then Afrika Bambaataa came along - the legendary grand master D.J. who is the individual most responsible for the successful growth of Breakdancing as he saw a great potential in it. He started one of the first Breakdance crews, the Zulu Kings that won a lot of battles and talent shows and preformed in various clubs in New York. Old-style Breaking became past when based on the hit record "Freak Out" by the Shieks around 1979 and early 1980 a new Breakdance crew was organized - Rock Steady Crew (all original members were from Zulu Nation). They became famous doing dancing in clubs thanks to Bambaataa who encouraged them. Generally, a common feature of bboy music is the presence of a break which is looped several times by the dj.

These were the days when "hip-hop culture" emerged: along with DJing, these "breakbeats" laid the foundation for the two more elements - MCing and <a href="http://www.thebreaksnz.com/201829188">B-Boying</a>. It became the MC's (Master of Ceremony) job to amuse, excite, and motivate the crowd to dance over the breakbeats. B-Boys were the ones who would dance or "freak out," "bust moves," and "go-off" on the dancefloor with their steps and freezes. These three elements along with graffiti art or writing are what make up the hip hop culture.
<img style="float:left;" src="http://cdn.simplesite.com/i/b0/4f/285697108068487088/i285697114316499638._szw480h1280_.jpg" alt="Floor RocKER" />
In the 1980s, with the help of pop culture and MTV, breakdancing made its way from the suburbs to the rest of the world as a new cultural phenomenon. The new style of dancing was different from the old: Rock Steady added a lot of acrobatic moves. And so around 1982 breaking became even more popular. Meanwhile, another dance was catching on: it was called the Robot. People started doing the Robot as early as 1969, but the dance really took off after Michael Jackson danced the Robot while singing "Dancin' Machine" on national TV. In 1983, movies like Flashdance and Buffalo Gals which featured the Rock Steady Crew broke the scene wide open when breaking could finally be scene internationally: the world went rap dance crazy.

The nature of the dance was that it was improvised, never learned, so upon seeing these films, American kids immediately began making up their own breakdancing moves in basements across America. Michael Jackson's famous "moonwalk" and M.C.Hammer's pumped-up dance style are just improvised forms of breakdancing. Breakdancing has evolved into the dancing that is seen today in music videos and rap. Over the next few years, breakdancing became the trend. Some of the more famous crews were featured in movies, commercials and TV shows. When the Summer Olympics came to Los Angeles in 1984, the closing ceremonies featured a performance by over 100 B-Boys and B-Girls.
So, prototypically the pioneers of breakdancing were young and of a lower socioeconomic class. The majorities of these were male, and most were Black or Hispanic, and lived in dense urban areas (mostly New York). Many of them were members of street gangs. Breakdancers typically wear low pants, T-shirts and a hat tipped sideways. They also wore nylon jumpsuits which were functional as well as fashionable. The slick surface allowed the breakdancer to slide on the floor much easier than if she or he had been wearing a cotton shirt. The dance must be done in sneakers, for the dancer's safety. Breakdancing is known as an especially dangerous sport for several reasons. It is not unusual for a dancer to get something caught, stubbed or stopped while moving in air. This dance is never done on a soft surface. Breakdancing includes moving the feet sideways and onto the toes, spinning on the knees, head, hands and elbows, mock fighting moves, and pantomime.
<img style="float:right;" src="https://m.media-amazon.com/images/I/51c6iiV+YuL.jpg" />
In its early form, breakdancing was divided into three distinct forms of dancing, breaking and popping. Today, each body movement has been classified into a distinct style or genre of breaking and is similar in principle to others but characteristically different. The most basic breakdance moves are the 6-step and toprock. The rest of the dance is founded around these two elements which are the base for other more complex moves to be formed, as well as power moves. After performing these elements breakdancer will usually end the dance with a 'freeze' which is when he contorts his body to a strange position and literally freezes, stopping all dance motion. The breakdancer will usually hold the freeze for a second or two.

Breakdancers often call any dancing that takes place on the ground 'downrock' as opposed to uprock or toprock. There are some Power moves that often require incredible skill and flexibility to complete, the example of these is a headspin. There are controversies between people who emphasize on style and power moves. One puts his emphasis on power moves and their combination and the other shows their style and individuality by footwork and freeze.

Today serious battles are usually held at organized breakdance events. The battles are usually part of a tournament style competition with cash prizes, or they are featured showcase battles, where each crew is paid to dance. Today's breakdancing styles which emphasize fast-paced, fluid floor moves and freezes, different from that of two decades ago, requires more freedom of movement in the upper body, so less baggy upper wear is more common today (though pants remain baggy).

When the fashion for breakdancing decreased it the whole culture seemed trashed by the media. But today the breakin' name has been cleared and is continuing regain its reputation as a respected dance form. Nowadays many b-boys from all over the world get together on annual B-boy events and keep the culture alive and even try to take it into next level.
</div>
<div> <img class="right" src="https://upload.wikimedia.org/wikipedia/commons/a/a8/Downrock.jpg?1639357739125" alt="Floor RocKER" /> <span class="firstcharacter">I</span>n 1969, when James Brown was getting down with his big hit "Get on the Good Foot" the big dance style of the day appeared. This almost acrobatic dance became rather well known around New York City: kids in New York were doing the Good Foot - better known as B-Boy(the 'B' in b-boy usually doesn't correspond to a specific word, but most likely means "Boogaloo" or "Break") - which was the direct precursor to the sort of breakdancing we know today. As for origins it was the African people's dance culture which brought the heavy rhythm and the idea of dancing in a circle, but it was definitely a variety of influences that made up early B-Boying including gymnastics, Eastern martial arts, tap dance, Salsa, Afro-Cuban and Native American dances. One of the most influential dances was a South American martial arts/fighting dance known as the Capoeira. By the time the Good Foot became the new dance style, the tradition of dance battle was well established. Dancers would gather at places like Harlem World on 116th Street in Harlem and Battle-dancewise. Battles are covered in more detail in the section on battles, challenges, and contests, but the important thing is that Breakdancing was particularly well-suited for competition and it appealed to certain young men who were very athletic. The Good Foot, which was soon to be called B-Boy and shortly after that <a href="https://www.danceclass.com/breakdancing-music.html">Breakdancing</a>, or Breaking, was very different from the Breaking we see today. In some ways it was simpler. There were no headspins, no windmill, no handglides or backspins. It was what is now called old-style Breaking. It consisted only of floor work, involved some extremely complicated leg moves done very fast and in a way it was more complex than modern Breaking. Among those for whom old-style breaking was especially popular were many of the youths and street gangs that roamed the South Bronx. And it was in those streets that Breakdancing really started. Often, the best Breakers in opposing gangs would battle dancewise instead of fighting. A breakdancing battle is when dancers 'fight' against each other on the dance floor without contact. They form a circle and take turns trying to show each other up through better style, more complex move<img class="left" src="https://calisphere.org/clip/500x500/8db0bd01cab257a19ab8d35b5ffe8fba" alt="Floor RocKER" /> combinations, or tougher moves. Unfortunately, these Breaking battles did not always stop fight. In fact, they often would cause a fight, since dancers would sometimes get physical when they couldn't win dancewise. Some of these crews became very dedicated to their dancing, and since they had nothing better to do, would spend hours a day practicing, developing more and more complex moves, improving their form, and increasing their speed. And then Afrika Bambaataa came along - the legendary grand master D.J. who is the individual most responsible for the successful growth of Breakdancing as he saw a great potential in it. He started one of the first Breakdance crews, the Zulu Kings that won a lot of battles and talent shows and preformed in various clubs in New York. Old-style Breaking became past when based on the hit record "Freak Out" by the Shieks around 1979 and early 1980 a new Breakdance crew was organized - Rock Steady Crew (all original members were from Zulu Nation). They became famous doing dancing in clubs thanks to Bambaataa who encouraged them. Generally, a common feature of bboy music is the presence of a break which is looped several times by the dj. These were the days when "hip-hop culture" emerged: along with DJing, these "breakbeats" laid the foundation for the two more elements - MCing and <a href="http://www.thebreaksnz.com/201829188">B-Boying</a>. It became the MC's (Master of Ceremony) job to amuse, excite, and motivate the crowd to dance over the breakbeats. B-Boys were the ones who would dance or "freak out," "bust moves," and "go-off" on the dancefloor with their steps and freezes. These three elements along with graffiti art or writing are what make up the hip hop culture. <img class="right" src="http://cdn.simplesite.com/i/b0/4f/285697108068487088/i285697114316499638._szw480h1280_.jpg" alt="Floor RocKER" /> In the 1980s, with the help of pop culture and MTV, breakdancing made its way from the suburbs to the rest of the world as a new cultural phenomenon. The new style of dancing was different from the old: Rock Steady added a lot of acrobatic moves. And so around 1982 breaking became even more popular. Meanwhile, another dance was catching on: it was called the Robot. People started doing the Robot as early as 1969, but the dance really took off after Michael Jackson danced the Robot while singing "Dancin' Machine" on national TV. In 1983, movies like Flashdance and Buffalo Gals which featured the Rock Steady Crew broke the scene wide open when breaking could finally be scene internationally: the world went rap dance crazy. The nature of the dance was that it was improvised, never learned, so upon seeing these films, American kids immediately began making up their own breakdancing moves in basements across America. Michael Jackson's famous "moonwalk" and M.C.Hammer's pumped-up dance style are just improvised forms of breakdancing. Breakdancing has evolved into the dancing that is seen today in music videos and rap. Over the next few years, breakdancing became the trend. Some of the more famous crews were featured in movies, commercials and TV shows. When the Summer Olympics came to Los Angeles in 1984, the closing ceremonies featured a performance by over 100 B-Boys and B-Girls. So, prototypically the pioneers of breakdancing were young and of a lower socioeconomic class. The majorities of these were male, and most were Black or Hispanic, and lived in dense urban areas (mostly New York). Many of them were members of street gangs. Breakdancers typically wear low pants, T-shirts and a hat tipped sideways. They also wore nylon jumpsuits which were functional as well as fashionable. The slick surface allowed the breakdancer to slide on the floor much easier than if she or he had been wearing a cotton shirt. The dance must be done in sneakers, for the dancer's safety. Breakdancing is known as an especially dangerous sport for several reasons. It is not unusual for a dancer to get something caught, stubbed or stopped while moving in air. This dance is never done on a soft surface. Breakdancing includes moving the feet sideways and onto the toes, spinning on the knees, head, hands and elbows, mock fighting moves, and pantomime. <img class="left" src="https://www.danceclass.com/images/bboy_history.jpg" /> In its early form, breakdancing was divided into three distinct forms of dancing, breaking and popping. Today, each body movement has been classified into a distinct style or genre of breaking and is similar in principle to others but characteristically different. The most basic breakdance moves are the 6-step and toprock. The rest of the dance is founded around these two elements which are the base for other more complex moves to be formed, as well as power moves. After performing these elements breakdancer will usually end the dance with a 'freeze' which is when he contorts his body to a strange position and literally freezes, stopping all dance motion. The breakdancer will usually hold the freeze for a second or two. Breakdancers often call any dancing that takes place on the ground 'downrock' as opposed to uprock or toprock. There are some Power moves that often require incredible skill and flexibility to complete, the example of these is a headspin. There are controversies between people who emphasize on style and power moves. One puts his emphasis on power moves and their combination and the other shows their style and individuality by footwork and freeze. Today serious battles are usually held at organized breakdance events. The battles are usually part of a tournament style competition with cash prizes, or they are featured showcase battles, where each crew is paid to dance. Today's breakdancing styles which emphasize fast-paced, fluid floor moves and freezes, different from that of two decades ago, requires more freedom of movement in the upper body, so less baggy upper wear is more common today (though pants remain baggy). When the fashion for breakdancing decreased it the whole culture seemed trashed by the media. But today the breakin' name has been cleared and is continuing regain its reputation as a respected dance form. Nowadays many b-boys from all over the world get together on annual B-boy events and keep the culture alive and even try to take it into next level. </div>
<a href="http://www.hiphoparea.com/breakdance"> Taken from hiphoparea.cOm </a>
<iframe width="100%" height="315" src="https://www.youtube.com/embed/AVZyNqDjgnI" title="YouTube video player" frameborder="0" allowfullscreen></iframe>

<div class="storyBox">
        <div class="card">
            <div class="face face1">
                <div class="storycontent">
                        <div class="bookCover">
  <img style="float:right; width:100%; height:100%; " src="https://upload.wikimedia.org/wikipedia/commons/0/03/Emoji_u1f4af.svg">

</div>
                </div>
            </div>
            <div class="face face2">
                <div class="storycontent">
                           <p>Aesop's Fables is a collection of tales by the Greek storyteller Aesop. Most of the tales included here were translated and edited by Reverend George Fyler Townsend (1814-1900) in England and published under the title, Aesop's Fables. <audio controls="" style="width:99%;">
            <source src="https://etc.usf.edu/lit2go/audio/mp3/aesops-fables-001--the-ant-and-the-grasshopper.366.mp3" type="audio/mpeg">
            <source src="https://etc.usf.edu/lit2go/audio/ogg/aesops-fables-001--the-ant-and-the-grasshopper.366.ogg" type="audio/ogg">
            The embedded audio player requires a modern internet browser. You should visit <a href="https://browsehappy.com/">Browse Happy</a> and update your internet browser today!
          </audio></p>
        <a href="https://etc.usf.edu/lit2go/35/aesops-fables/">Read More##LiT_To_Go##</a>
                </div>
            </div>
                
<iframe src="https://archive.org/embed/msdos_Simpsons_Arcade_Game_The_1991" width="100%" height="400" frameborder="0" webkitallowfullscreen="true" mozallowfullscreen="true" allowfullscreen></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/372194633&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/579369501&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/871426135&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/308016226&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe>
<iframe width="100%" height="250" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1149243178&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/169170570&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/223118835&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/982907785&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1039579195&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/843505996&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/843506050&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
<span class="neonText">
One day my blog will `RETURN` `true` when run from the command line 
</span>
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>
<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>     		

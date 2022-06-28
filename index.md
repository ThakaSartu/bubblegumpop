<style>

	
* {
margin: 0;
padding: 0;
}	
	
body {
  background-color: #010a00;
  background-image: url("https://burodestruct.net/sites/default/files/styles/bd_wide_2x/public/bd_type1_city.jpg?itok=MJSd2yw9");
  
  font-family:  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal, monospace, 
    BlinkMacSystemFont, 
    "Segoe UI", 
    Roboto, 
    Oxygen-Sans, 
    Ubuntu, 
    Cantarell, 
    "Helvetica Neue", 
    sans-serif;
  font-size: 1rem;
}

img {
 padding: 0px;
 margin: 0px;
 width: 100%; 
 border-bottom: 0px dashed #c9ff23;
}
  
h2 {
font-size: 90px;
font-family:  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal, monospace, 
    BlinkMacSystemFont, 
    "Segoe UI", 
    Roboto, 
    Oxygen-Sans, 
    Ubuntu, 
    Cantarell, 
    "Helvetica Neue", 
    sans-serif;
color: #fff;
font-weight: 900;
padding: 0px;
margin: 0px;
text-align: left;
font-variant-caps: small-caps;	
  text-shadow:
    0 0 5px #fff,
    0 0 10px #fff,
    0 0 20px #fff,
    0 0 40px #0ff,
    0 0 80px #0ff,
    0 0 90px #0ff,
    0 0 100px #0ff,
    0 0 150px #0ff;

} 
 
.firstcharacter {
 color: #fff;
 text-shadow:
 0 0 7px #fff,
 0 0 10px #fff,
 0 0 21px #fff,
 0 0 42px #0fa,
 0 0 82px #0fa,
 0 0 92px #0fa,
 0 0 102px #0fa,
 0 0 151px #0fa;
 font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal, monospace, 
    BlinkMacSystemFont, 
    "Segoe UI", 
    Roboto, 
    Oxygen-Sans, 
    Ubuntu, 
    Cantarell, 
    "Helvetica Neue", 
    sans-serif;
 float: left;
 font-size: 75px;
 line-height: 60px;
 padding-top: 7px;
 padding-right: 8px;
 padding-left: 3px;
}

.neonText {
 color: #fff;
 text-shadow:
 0 0 7px #fff,
 0 0 10px #fff,
 0 0 21px #fff,
 0 0 42px #0fa,
 0 0 82px #0fa,
 0 0 92px #0fa,
 0 0 102px #0fa,
 0 0 151px #0fa;
  font-family: Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal, monospace;
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
  background-color: #00db46; /* For browsers that do not support gradients */
  background-image: linear-gradient(to right, #e66250, #ff80cc);
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
  background-color: #2470FF;
  width: 100%;
}

.leftColumn img {
  
    flex-shrink: 0;
    min-width: 100%;
    min-height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden
  
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
    overflow: hidden
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
  background: rgb(
    255,
    108,
    35
  ); /* Fallback for older browsers without RGBA-support */
  background: rgba(255, 108, 35, 0.5);
}

   
	
.broken-width {
  width: 100%;
}

.right-width {
   min-width: 100%;
}

audio
{
-webkit-transition:all 0.5s linear;
-moz-transition:all 0.5s linear;
-o-transition:all 0.5s linear;
transition:all 0.5s linear;
-moz-box-shadow: 2px 2px 4px 0px #006773;
-webkit-box-shadow:  2px 2px 4px 0px #006773;
box-shadow: 2px 2px 4px 0px #006773;
-moz-border-radius:7px 7px 7px 7px ;
-webkit-border-radius:7px 7px 7px 7px ;
border-radius:7px 7px 7px 7px ;
}

audio:hover, audio:focus, audio:active
{
-webkit-box-shadow: 15px 15px 20px rgba(0,0, 0, 0.4);
-moz-box-shadow: 15px 15px 20px rgba(0,0, 0, 0.4);
box-shadow: 15px 15px 20px rgba(0,0, 0, 0.4);
-webkit-transform: scale(1.05);
-moz-transform: scale(1.05);
transform: scale(1.05);
}
	
	
</style>

## Hole To Another Universe



<a href="https:://typedifferent.com" target="_blank" ><img src="https://www.typedifferent.com/fonts/bd_rainbow/bd_rainbow_example1.jpg" /> </a>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeLeaRNiNGWEBDESiGN1.PNG" /><a/>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeLeaRNiNGWEBDESiGN.PNG" /><a/>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeiSBEAUTiFUL.PNG" /><a/>
<a href="https://www.2600.com/" > <img src="https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/BeYonCeMiCHELLEBRANCHE.PNG" /><a/>
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

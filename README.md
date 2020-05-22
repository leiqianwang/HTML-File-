<!DOCTYPE html>
<html>
<meta charset="UTF-8">
  <div style="width:900px;margin:0 auto;"><div style="text-align:right"><span style="font:9px/14px arial;color:#3d3d3d;">Powered By <a target="_blank" id="vt_link" rel="nofollow" href="http://www.varsitytutors.com/tutors/878520731">Varsity Tutors</a></span></div><iframe id="vt_content_frame" allowtransparency="true" style="height:900px; width:900px" frameborder="0" src="//widgets.varsitytutors.com/tutors/878520731?vt_theme=vt1"></iframe></div>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/w3css/3/w3.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.6.3/css/font-awesome.min.css">
<body>

<!-- Navigation -->
<nav class="w3-bar w3-blue">
  <a href="#home" class="w3-button w3-bar-item">Home</a>
  <a href="#band" class="w3-button w3-bar-item">Band</a>
  <a href="#tour" class="w3-button w3-bar-item">Tour</a>
  <a href="#contact" class="w3-button w3-bar-item">Contact</a>
</nav>

<!-- Slide Show -->
<section>
  <img class="mySlides" src="img_band_la.jpg"
  style="width:100%">
  <img class="mySlides" src="img_band_ny.jpg"
  style="width:100%">
  <img class="mySlides" src="img_band_chicago.jpg"
  style="width:100%">
</section>

<!-- Tutor Description -->
<section class="w3-container w3-center w3-content" style="max-width:600px">
  <h2 class="w3-wide">Yingying Wang</h2>
  <p class="w3-opacity"><i>We love music</i></p>
  <p class="w3-justify">I am a PhD graduate from Florida State University with a specialty in Piano Performance. I love to work with students whose age range and background are divergently wide and different. I have been involved in teaching in the academic environment for professional music major students within fundamental and advanced keyboard skills, such as harmonization, improvisation, score reading, chord progressions, sight-singing, scales in 24 major and minor key system, and transposition. I also instruct younger non-professional piano learners from age 4 to 18 as well adults. I have rich experience for helping to prepare ABRSM and NYSSMA exams and my students have showed outstanding musicanship, and many of them have obtained high scores from practical piano playing section and music theory section. I tailor design course syllabi and lesson plans in accordance to students' explicit study goals and preferences. Outside music territory, I frequently tutored subjects on English reading and writing through K-12. I drift on sufficient instructions for ISEE from lower to upper levels, HSPT, SAT Reading and Math. My students have demonstrated varying degrees of improvements regarding grades and proficiency that exhibit comprehensive understanding to the subjects. My hobbies include reading, cooking, swimming, and coding.</p>
</section>

<!-- Music Experience -->
<section class="w3-row-padding w3-center w3-light-grey">
  <article class="w3-third">
    <p>John</p>
    <img src="img_bandmember.jpg" alt="Random Name" style="width:100%">
    <p>John is the smartest.</p>
  </article>
  <article class="w3-third">
    <p>Paul</p>
    <img src="img_bandmember.jpg" alt="Random Name" style="width:100%">
    <p>Paul is the prettiest.</p>
  </article>
  <article class="w3-third">
    <p>Ringo</p>
    <img src="img_bandmember.jpg" alt="Random Name" style="width:100%">
    <p>Ringo is the funniest.</p>
  </article>
</section>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-black w3-xlarge">
  <a href="#"><i class="fa fa-facebook-official"></i></a>
  <a href="#"><i class="fa fa-pinterest-p"></i></a>
  <a href="#"><i class="fa fa-twitter"></i></a>
  <a href="#"><i class="fa fa-flickr"></i></a>
  <a href="#"><i class="fa fa-linkedin"></i></a>
  <p class="w3-medium">
  Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a>
  </p>
</footer>

<script>
// Automatic Slideshow - change image every 3 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}
  x[myIndex-1].style.display = "block";
  setTimeout(carousel, 3000);
}
</script>

</body>
</html>



<h1> Good {{timeOfDay}}! Welcome to IDEA Lab! </h1>

IDEA Lab is established in 20XX at Imperial College London. Consist of ..., the group's work mainly focuses on .... Furthermore, ...

For more details of what we do in the group, please refer to the <a style = " white-space:nowrap; " href="https://idea-lab-ic.github.io/#/research/README">Research</a> section.

<h2> Publications </h2>

J. Plocher, A. Panesar, <i> Review on design and structural optimisation in additive manufacturing: Towards next-generation lightweight structures</i>, Mater. Des. 183 (2019), 108164. https://doi.org/10.1016/j.matdes.2019.108164

J. Plocher, A. Panesar, <i> Effect of density and unit cell size grading on the stiffness and energy absorption of short fibre-reinforced functionally graded lattice structures</i>, Additive Manufacturing Journal, Volume 33, (2020), 101171. https://doi.org/10.1016/j.addma.2020.101171 

<h2> Highlights </h2>
<!-- AUTOMATIC SLIDESHOW -->
<div class="slideshow-container">

  <div class="mySlides fade">
    <!-- <div class="numbertext">1 / 3</div> -->
    <img src="/../_media/Computational-Tools-event.jpg" style="width:100%">
    <!-- <div class="text">Caption Text</div> -->
  </div>

  <div class="mySlides fade">
    <!-- <div class="numbertext">2 / 3</div> -->
    <img src="/../_media/optiReview.jpg" style="width:100%">
    <!-- <div class="text">Caption Two</div> -->
  </div>

  <div class="mySlides fade">
    <!-- <div class="numbertext">3 / 3</div> -->
    <img src="/../_media/lattice.png" style="width:100%">
    <!-- <div class="text">Caption Three</div> -->
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>

<!-- <br> -->

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>



<!-- <h2> Past Events </h2> -->



INSERT LINKS TO THE GROUP ACCOUNTS (IF THERE ARE ANY)




<style>
 /* ------------------------- FOR THE SLIDESHOW ------------------------- */
  * {box-sizing: border-box}
  body { margin:0}
  .mySlides {display: none}
  img {vertical-align: middle;}

  /* Slideshow container */
  .slideshow-container {
    max-width: 1000px;
    position: relative;
    margin: auto;
  }

  /* Next & previous buttons */
  .prev, .next {
    cursor: pointer;
    position: absolute;
    top: 50%;
    width: auto;
    padding: 16px;
    margin-top: -22px;
    color: white;
    font-weight: bold;
    font-size: 18px;
    transition: 0.6s ease;
    border-radius: 0 3px 3px 0;
    user-select: none;
    background-color: rgba(187,187,187,0.4);
  }

  /* Position the "next button" to the right */
  .next {
    right: 0;
    border-radius: 3px 0 0 3px;
  }

  /* On hover, add a black background color with a little bit see-through */
  .prev:hover, .next:hover {
    background-color: rgba(0,0,0,0.8);
  }

  /* Caption text */
  .text {
    color: #f2f2f2;
    text-shadow: 1px 0.5px 1px #000001;
    font-size: 15px;
    padding: 8px 12px;
    position: absolute;
    bottom: 8px;
    width: 100%;
    text-align: center;
  }

  /* Number text (1/3 etc) */
  .numbertext {
    color: #f2f2f2;
    text-shadow: 1px 0.5px 1px #000001;
    font-size: 12px;
    padding: 8px 12px;
    position: absolute;
    top: 0;
  }

  /* The dots/bullets/indicators */
  .dot {
    cursor: pointer;
    height: 15px;
    width: 15px;
    margin: 0 2px;
    background-color: #bbb;
    border-style: solid;
    border-color: #bbb;
    border-radius: 50%;
    display: inline-block;
    transition: background-color 0.6s ease;
  }

  .dot:hover {
    background-color: #f7f7f7;
  }

  .active {
    background-color: #f7f7f7;
  }

  /* Fading animation */
  .fade {
    -webkit-animation-name: fade;
    -webkit-animation-duration: 1.5s;
    animation-name: fade;
    animation-duration: 1.5s;
  }

  @-webkit-keyframes fade {
    from {opacity: .4} 
    to {opacity: 1}
  }

  @keyframes fade {
    from {opacity: .4} 
    to {opacity: 1}
  }

  /* On smaller screens, decrease text size */
  @media only screen and (max-width: 300px) {
    .prev, .next,.text {font-size: 11px}
  }
 /* -------------------------------------------------------- */
</style>


<script>
//  FOR THE AUTO SLIDESHOW (if want to use the manual one, refer to imageSlideshow.md)
var slideIndex = 1;
showSlides(slideIndex);      

function showSlides() {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 3000); // Change image every 3 seconds
}

</script>
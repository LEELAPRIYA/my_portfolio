<!DOCTYPE html>
<html>
  <head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    .bgimg {
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-image: url('https://res.cloudinary.com/dtlqw2vir/image/upload/v1652110009/sudha_ug2r9m.jpg');
      min-height: 100%;
    }
    </style>
  </head>
<body>

<!-- Sidebar with image -->
<nav class="w3-sidebar w3-hide-medium w3-hide-small" style="width:40%">
  <div class="bgimg"></div>
</nav>

<!-- Hidden Sidebar (reveals when clicked on menu icon)-->
<nav class="w3-sidebar w3-black w3-animate-right w3-xxlarge" style="display:none;padding-top:150px;right:0;z-index:2" id="mySidebar">
  <a href="javascript:void(0)" onclick="closeNav()" class="w3-button w3-black w3-xxxlarge w3-display-topright" style="padding:0 12px;">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Home</a>
    <a href="#portfolio" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Portfolio</a>
    <a href="#about" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">About</a>
    <a href="#contact" class="w3-bar-item w3-button w3-text-grey w3-hover-black" onclick="closeNav()">Contact</a>
  </div>
</nav>

<!-- Page Content -->
<div class="w3-main w3-padding-large" style="margin-left:40%">

  <!-- Menu icon to open sidebar -->
  <span class="w3-button w3-top w3-white w3-xxlarge w3-text-grey w3-hover-text-black" style="width:auto;right:0;" onclick="openNav()"><i class="fa fa-bars"></i></span>

  <!-- Header -->
  <header class="w3-container w3-center" style="padding:128px 16px" id="home">
    <h1 class="w3-jumbo"><b>LEELA PRIYA</b></h1>
    <p>Learner.</p>
    <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652110009/sudha_ug2r9m.jpg" class="w3-image w3-hide-large w3-hide-small w3-round" style="display:block;width:60%;margin:auto;">
    <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652110009/sudha_ug2r9m.jpg" class="w3-image w3-hide-large w3-hide-medium w3-round" width="1000" height="1333">
    <button class="w3-button w3-light-grey w3-padding-large w3-margin-top">
      <i class="fa fa-download"></i> Download Resume
    </button>
  </header>

  <!-- Portfolio Section -->
  <div class="w3-padding-32 w3-content" id="portfolio">
    <h2 class="w3-text-grey">My Portfolio</h2>
    <hr class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652110037/sudha_2_slf00h.jpg" style="width:100%">
        <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652114354/sudha4_zexhhk.jpg" style="width:100%">
      </div>

    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-32" id="about">
    <h2>About</h2>
    <hr class="w3-opacity">
    <p>Hello everyone,I am leela priya,new learner in CSI club.I am from Tirupati,AP.<br>I choose CSE branch in VIT ap because I am fond of coding.</br>
      I completed my schooling in VEMA HIGH SCHOOL and intermediate in VISWASAI.<br>
      strengths: I am self motivated and always believe in myself.</br>
      Hobbies are listening to music,reading comics and watching movies etc...
    </p>
    <h3 class="w3-padding-16">My Skills</h3>
    <p class="w3-wide">Photography</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-dark-grey" style="width:95%">90%</div>
    </div>
    <p class="w3-wide">coding in python abd java</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-dark-grey" style="width:85%">50%</div>
    </div>
    <p class="w3-wide">active in social media</p>
    <div class="w3-light-grey">
      <div class="w3-container w3-center w3-padding-small w3-dark-grey" style="width:80%">90%</div>
    </div><br>

    <div class="w3-row w3-center w3-dark-grey w3-padding-16 w3-section">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">50+</span><br>
        friends
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">1</span><br>
        Running project
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">100+</span><br>
        supporters
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">10+</span><br>
        Meetings
      </div>
    </div>

    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Download Resume
    </button>

    <!-- Testimonials -->
    <h3 class="w3-padding-24">My friends</h3>
    <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652148212/priya1_bnm2kr.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">Neeraja.</span> csi monitor.</p>
    <p>Neeraja is just awesome. I am so happy to have met her!</p><br>

    <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652148245/priya2_swgmn8.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">Pranathi.</span>csi co-ordinator.</p>
    <p>she always guides us in doing projects.</p><br>

    <img src="https://res.cloudinary.com/dtlqw2vir/image/upload/v1652148274/priya3_ucnmsr.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-text-black w3-margin-right">Meera.</span> csi member.</p>
    <p>we both help each other in our projects.</p><br>


  <!-- End About Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-32 w3-content w3-text-grey" id="contact" style="margin-bottom:64px">
    <h2>Contact Me</h2>
    <hr class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Tirupati,AP</p>
      <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone: 9392305472</p>
      <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: priya@gmail.com</p>
    </div>

    <p>Lets get in touch. Send me a message:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> SEND MESSAGE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>  

  <!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
  <footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin:-24px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-small">This website was made with W3schools Spaces. Make your own free website today!</p>
    <a class="w3-button w3-round-xxlarge w3-small w3-dark-grey" href="https://www.w3schools.com/spaces" target="_blank">Start now</a>  
    <!-- End footer -->
  </footer>
<!-- END PAGE CONTENT -->
</div>

<script>
// Open and close sidebar
function openNav() {
  document.getElementById("mySidebar").style.width = "60%";
  document.getElementById("mySidebar").style.display = "block";
}

function closeNav() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>

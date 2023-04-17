
<html>
  <head>
   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=2">


    <!--- does the initial-scale vlaue change anything?-->
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    
    <script src="https://kit.fontawesome.com/95df80bce8.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <style>
    body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

    body, html {
      height: 100%;
      line-height: 1.8;
    }

    /* Full height image header */
    .bgimg-1 {
      background-position: center;
      background-size: cover;
      background-image: url('https://t4.ftcdn.net/jpg/04/11/62/91/360_F_411629117_HytBTnjkYAYhmwl68LqYumWgKAZ3bkTj.jpg');
      min-height: 100%;
    }

    .w3-bar .w3-button {
      padding: 16px;
    }
    </style>
  </head>
<body>
<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card" id="myNavbar">
    <a href="./home.html" class="w3-bar-item w3-button w3-wide">MediBlock</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="./doc.html" class="w3-bar-item w3-button">ABOUT</a>
      <a href="./about.html" class="w3-bar-item w3-button"><i class="fa fa-chain"></i> TECHNOLOGY</a>
      <a href="./doc.html" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> DOCUMENT</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- H small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>


<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">MediBlock</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Secure, private, efficient: Health data revolution.</span><br>
    <span class="w3-large"><b>Secure, private, efficient: Health data revolution.</b></span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Learn more and start today</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
</header>

<!-- About Comp -->
<!--THE i classes are the icons, DO NOT DELETE THEM AND U CAN FIND MORE ICONS ON W3-->
<div class="container w3-black" style="padding: 10px 16px" id="about">
  <h3 class="w3-center"><b>ABOUT THE COMPANY</b></h3>
  <p class="w3-center w3-large">Key features of our company</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      
      <i class="fas fa-clock w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large"> <b> 24 Hour Accessibility</b> </p>
      <p>Through the use of an fully online based system, with acess points throughout the world. </p>
    </div>
    <div class="w3-quarter">
      <i class="fas fa-user-lock w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large"><b>Confidentiality</b></p>
      <p>RSA Algorithm to produce public and private keys will be put into use as a form to maintain confidentiality between the two members of the intended transaction.</p>
    </div>
    <div class="w3-quarter">
      <i class="fas fa-clipboard-check w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large"><b>Quick Transaction Speeds</b></p>
      <p>MediBlock utilizes Polkadots parachain in the blockchain to conduct 1,000 TSP (transactions per second), meaning 1,000 medical records can be transferred in one second. With a capacity of around 16,666 TPS.</p>
    </div>
    <!--why wont it let me change the icon to fas fa-file-medical-alt, 
    -->
    <div class="w3-quarter">
      <i class="fa fa-bitcoin w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large"><b>Cost-efficient</b></p>
      <p>This amounts to around $45 for a transfer of a 60-page medical record.And in the parachain, the miners are the only ones who are being paid a small amount of money amounting to around $4-$10. In total, I saved around $41.
      </p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="container-black w3-black" style="padding:288px 10px">
  <div class="rowpadding">
    <div class="w3-col m6">
      <h3>We know Security.</h3>
      <p>Understanding the importance of medical record security, we at MediBlock use Encryption, Hashing, Digital signatures, Access control and a Private blockchain inorder to provide patients with the highest level of security so they don't have to ever worry about losing them.</p>
      <p><a href="#work" class="w3-button w3-text-white"><i class="fa fa-th"> </i> View Our Works</a></p>
    </div>
    <div class="w3-col m6 w3-black">
      <img class="w3-image w3-round-large" src="https://www.patriotsoftware.com/wp-content/uploads/2022/01/what-is-blockchain-1.jpg" alt="Buildings" width="700" height="394">
    </div>
  </div>
</div>

</script>

</body>
</html>




<!DOCTYPE html>
<html>
  <head>
    <title>MediBlock</title>
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



<!DOCTYPE html>
<html>
  <head>
    <title>MediBlock</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=2">


    <!--- does the initial-scale vlaue change anything?-->
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" herf="./bobby.css">
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
      background-image: url('https://media.istockphoto.com/id/1331702867/photo/block-chain-concept.jpg?b=1&s=170667a&w=0&k=20&c=iOYdKBFv6uAigH_im_fMw6VSLqfM6ydS_FrAeQRbtks=');
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
  <div class="w3-bar w3-white w3-card" id="myNavbar">
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

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>





<!--GIRLLYYY HEREQ!!!!!!!!-->
 <body>
  <!-- First Parallax Image with Logo Text -->
<div class="bgimg-1 w3-display-container w3-opacity-min" id="Tech">
  <div class="w3-display-middle" style="white-space:nowrap;">
    <div class="Title" style="display:flex;justify-content: center;align-items: center;">

    <span class="w3-padding-large w3-deep-purple w3-xlarge w3-wide w3-animate-opacity ">MEDIBLOCK</span>
    </div>
    <p></p><span class="w3-padding-medium w3-black w3-small w3-wide w3-animate-opacity w3-display-down">Saving Time, Money 
      and Protect the Lives & Confidentiality of patients. </span></p>
  </div>
</div>

<!-- Container (About Section) -->
<div class="w3-content w3-container w3-padding-64" id="about">
  <h3 class="w3-center w3-text-purple"><b>Summary</b></h3>
  <p>MediBlock uses <b>blockchain technology</b> to securely hold the medical records of the patient. Through this method, records can be found and transferred in seconds. In addition to quick and easy transfers, MediBlock provides<b> top-notch security </b> for medical records during the storage and transfer, while being <b>cost-effective</b>. The MediBlock also promotes scalability as it is able to transfer hundreds of transactions in a second, allowing for large hospitals to use this service with ease. At MediBlock, our goal is to provide patients and doctors easy access to medical records with the utmost <b>confidentiality and security</b>.  Together with MediBlock, we can <b>Save Lives, Time, and Money</b> while Protecting the <b>confidentiality</b> of patients through the use of blockchain technology.
    </p>
  <div class="w3-row">
    <div class="w3-col m6 w3-center w3-padding-large">
      <img src="https://www.patriotsoftware.com/wp-content/uploads/2022/01/what-is-blockchain-1.jpg" class="w3-round w3-image width="500" height="">
    </div>

    <!-- Hide this text on small devices -->
    <div class="w3-col m6 w3-hide-small w3-padding-large">
      <p>MediBlock is committed to safeguarding your medical records with the utmost care and security. To achieve this, we rely on MediChain, a cutting-edge single-chain blockchain designed for the storage and transfer of medical data. Using a unique approach, MediChain stores medical records in the form of non-fungible token blocks, which are encrypted and secured through a combination of hashing, digital signatures, access control, and a private blockchain. With these measures in place, you can rest assured that your sensitive information is fully protected, giving you the peace of mind you deserve.
      </p>
    </div>
  
  
 

</script>

<!-- Clarity Section -->
<div class="w3-padding-24 w3-light-grey">
  <div class="w3-row-padding">
    <div class="w3-col l8 m6">
      <h1 class="w3-xlarge w3-text-purple"><b>Problem</b></h1>
      <p><span class="w3-large"><b>230 million US health records</b></span> have been lost or stolen in just the last decade.. The lack of medical records can result in delays in medical treatment and also cause incorrect diagnosis which can result in the patients’ death. The loss of data is also dangerous for the doctor because it can result in lawsuits for breaking HIPAA guidelines, cost thousands of dollars, and the revocation of their medical license  Additionally, Medical records take around 15 days to transfer and urgent requests can take up to 2 hours. The slow transfer can often prove life-threatening in case of emergencies as even a second loss can affect a patient's health immensely. </p>
    </div>
    <div class="w3-col l4 m6">
      <img class="w3-image w3-round-large w3-hide-small" src="https://thumbs.dreamstime.com/b/big-data-healthcare-abstract-concept-vector-illustration-personalized-medicine-patient-care-predictive-analytics-electronic-198851385.jpg"  width="335" height="471">
    </div>
  </div>
</div>

<!-- Features Section -->
<div class="w3-container w3-padding-64 w3-dark-grey w3-center">
  <h1 class="w3-jumbo w3-text-lavender"><b>Features</b></h1>

  <div class="w3-row" style="margin-top:64px">
    <div class="w3-col s2.5">
      <i class="fa fa-bolt w3-text-orange w3-jumbo"></i>
      <h2>High Speed</h2>
      <p>Sharding is a method used in distributed database systems to divide a huge database into smaller, easier-to-manage parts known as "shards." These shards are then stored on separate nodes within the distributed system, with each node responsible for handling queries that pertain to its specific shard.
      </p>
    </div>
    
    <div class="w3-col s2.5">
      <i class="fa fa-globe w3-text-red w3-jumbo"></i>
      <h2>Global</h2>
      <p>24 Hour Accessibility from anywhere around the world.</p>

    </div>
    <div class="w3-col s2.5">
      <i class="fa fa-usd w3-text-yellow w3-jumbo"></i>
      <h2>Cost-efficient </h2>
      <p>This MBlock wallet will have the capacity to store 1-10,000+ NFTS and MDKT tokens. Additionally, with aims of promoting worldwide collaboration, the owner of medical records will be able to monitor and give viewing access to certain people. </p>
    </div>
    <div class="w3-col s2.5">
      <i class="fa fa-shield w3-text-green w3-jumbo"></i>
      <h2>Security</h2>
      <p>Understanding the importance of medical record security, we at MediBlock use Encryption, Hashing, Digital signatures, Access control and a Private blockchain inorder to provide patients with the highest level of security so they don't have to ever worry about losing them. </p>
    </div>
  </div>


<!-- Footer -->
<footer class="w3-container w3-padding-32 w3-light-grey w3-center w3-xlarge">
  <div class="w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<script>
// Slideshow
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>
</body>
</html>

  <!DOCTYPE html>
<html>
  <head>
    <title>MediBlock</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=2">


    <!--- does the initial-scale vlaue change anything?-->
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    
    <script src="https://kit.fontawesome.com/95df80bce8.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
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
      background-image: url('https://media.istockphoto.com/id/1331702867/photo/block-chain-concept.jpg?b=1&s=170667a&w=0&k=20&c=iOYdKBFv6uAigH_im_fMw6VSLqfM6ydS_FrAeQRbtks=');
      min-height: 100%;
    }

    .w3-bar .w3-button {
      padding: 16px;
    }
    </style>
    <style>
        body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
        body {font-size: 16px;}
        img {margin-bottom: -8px;}
        .mySlides {display: none;}
        </style>
  </head>

<body>
<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">MediBlock</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button w3-text-white">ABOUT</a>
      <a href="./about.html" class="w3-bar-item w3-button w3-text-whit"><i class="fa fa-chain"></i> TECHNOLOGY</a>
      <a href="#pricing" class="w3-bar-item w3-button w3-text-whit"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button w3-text-whit"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- H small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<body class="w3-content w3-black" style="max-width:1500px;">
    
 <!-- Header with Slideshow -->
<header class="w3-display-container w3-center">
    <button class="w3-button w3-block w3-green w3-hide-large w3-hide-medium" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button>
    <div class="mySlides w3-animate-opacity">
      <img class="w3-image" src="https://builtin.com/sites/www.builtin.com/files/styles/og/public/2022-09/blockchain.png" alt="Image 1" style="min-width:500px" width="1500" height="1000">
      <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
        <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
          <h1 class="w3-xlarge">Download Whitpaper</h1>
          <hr class="w3-opacity">
          <p>Secure, private, efficient: Health data revolution.</p>
          <p><button class="w3-button w3-block w3-green w3-round" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button></p>
        </div>
      </div>
    </div>
    <div class="mySlides w3-animate-opacity">
        <img class="w3-image" src="https://content.cdn.sap.com/is/image/sap/287437:3840x1648?wid=1920&hei=824&fit=stretch,1&flip=lr" alt="Image 3" style="min-width:500px" width="1500" height="1000">
        <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
          <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
            <h1 class="w3-xlarge">Business Plan</h1>
            <hr class="w3-opacity">
            <p>Understand the what makes MediBlock, MediBlock!</p>
            <p><button class="w3-button w3-block w3-indigo w3-round" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button></p>
          </div>
        </div>
      </div>
    <div class="mySlides w3-animate-opacity">
      <img class="w3-image" src="https://www.xilinx.com/content/xilinx/en/products/design-tools/resources/the-developers-guide-to-blockchain-development/_jcr_content/root/parsysFullWidth/xilinxflexibleslab/xilinxflexibleslab-parsys/xilinxcolumns_388240228/childParsys-0/xilinxcolumns/childParsys-0/xilinximage_copy_cop.img.png/1644357925388.png" alt="Image 2" style="min-width:500px" width="1500" height="1000">
      <div class="w3-display-left w3-padding w3-hide-small" style="width:35%">
        <div class="w3-black w3-opacity w3-hover-opacity-off w3-padding-large w3-round-large">
          <h1 class="w3-xlarge w3-text-red"><b>Blockchain Guide Book</b></h1>
          <hr class="w3-opacity">
          <p>Become a Blockchain master in 15 minutes!</p>
          <p><button class="w3-button w3-block w3-red w3-round" onclick="document.getElementById('download').style.display='block'">Download <i class="fa fa-android"></i> <i class="fa fa-apple"></i> <i class="fa fa-windows"></i></button></p>
        </div>
      </div>
    </div>
    
    <a class="w3-button w3-black w3-display-right w3-margin-right w3-round w3-hide-small w3-hover-light-grey" onclick="plusDivs(1)">Take Tour <i class="fa fa-angle-right"></i></a>
    <a class="w3-button w3-block w3-black w3-hide-large w3-hide-medium" onclick="plusDivs(1)">Take Tour <i class="fa fa-angle-right"></i></a>
  </header>
  
  <!-- DOWNLOAD BUTTON -->
  <div id="download" class="w3-modal w3-animate-opacity">
    <div class="w3-modal-content" style="padding:32px">
      <div class="w3-container w3-white">
        <i onclick="document.getElementById('download').style.display='none'" class="fa fa-remove w3-xlarge w3-button w3-transparent w3-right w3-xlarge"></i>
        <h2 class="w3-wide">DOWNLOAD</h2>
        <i class="fa fa-android w3-large"></i> <i class="fa fa-apple w3-large"></i> <i class="fa fa-windows w3-large"></i>
        <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail"></p>
         class="w3-bar-item w3-button"><i class="fa fa-chain"></i> TECHNOLOGY</a>
        <button type="button" class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('download').style.display='none'"> Download</button>
        <script>
            function downloadFile() {
                var fileUrl = "https://docs.google.com/document/d/1PGD8YU5lquC3nRi2bnFcGh1ZHh3mUOwn_NQxhwvfAfs/edit?usp=sharing";
            }
            </script>
      </div>
    </div>
  </div>

  <!-- The App Section -->
  <div class="w3-padding-64 w3-black">
    <div class="w3-row-padding">
      <div class="w3-col l8 m6">
        <h1 class="w3-jumbo w3-text-white"><b>The App</b></h1>
        <h1 class="w3-xxxlarge w3-text-green"><b>Why buy it?</b></h1>
        <p><span class="w3-xlarge">Take photos like a pro.</span> You should buy this app because lorem ipsum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
          ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        <button class="w3-button w3-light-grey w3-padding-large w3-section w3-hide-small" onclick="document.getElementById('download').style.display='block'">
          <i class="fa fa-download"></i> Download Application
        </button>
        <p>Available for <i class="fa fa-android w3-xlarge w3-text-green"></i> <i class="fa fa-apple w3-xlarge"></i> <i class="fa fa-windows w3-xlarge w3-text-blue"></i></p>
      </div>
      <div class="w3-col l4 m6">
        <img src="/w3images/img_app.jpg" class="w3-image w3-right w3-hide-small" width="335" height="471">
        <div class="w3-center w3-hide-large w3-hide-medium">
          <button class="w3-button w3-block w3-padding-large" onclick="document.getElementById('download').style.display='block'">
            <i class="fa fa-download"></i> Download Application
          </button>
          <img src="/w3images/img_app.jpg" class="w3-image w3-margin-top" width="335" height="471">
        </div>
      </div>
    </div>
  </div>
  
  
  
  <!-- Clarity Section -->
  <div class="w3-padding-64 w3-light-grey">
    <div class="w3-row-padding">
      <div class="w3-col l4 m6">
        <img class="w3-image w3-round-large w3-hide-small w3-grayscale" src="/w3images/app5.jpg" alt="App" width="335" height="471">
      </div>
      <div class="w3-col l8 m6">
        <h1 class="w3-jumbo"><b>Clarity</b></h1>
        <h1 class="w3-xxxlarge w3-text-red"><b>Pixels, who?</b></h1>
        <p><span class="w3-xlarge">A revolution in resolution.</span> Sharp and clear photos with the world's best photo engine, incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
          ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      </div>
    </div>
  </div>
  
  <!-- Features Section -->
  <div class="w3-container w3-padding-64 w3-dark-grey w3-center">
    <h1 class="w3-jumbo"><b>Features</b></h1>
    <p>This app is just so lorem ipsum.</p>
  
    <div class="w3-row" style="margin-top:64px">
      <div class="w3-col s3">
        <i class="fa fa-bolt w3-text-orange w3-jumbo"></i>
        <p>Fast</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-heart w3-text-red w3-jumbo"></i>
        <p>Loved</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-camera w3-text-yellow w3-jumbo"></i>
        <p>Clarity</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-battery-full w3-text-green w3-jumbo"></i>
        <p>Power</p>
      </div>
    </div>
  
    <div class="w3-row" style="margin-top:64px">
      <div class="w3-col s3">
        <i class="fa fa-diamond w3-text-white w3-jumbo"></i>
        <p>Sharp</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-cloud w3-text-blue w3-jumbo"></i>
        <p>Cloud</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-globe w3-text-amber w3-jumbo"></i>
        <p>Global</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-hdd-o w3-text-cyan w3-jumbo"></i>
        <p>Storage</p>
      </div>
    </div>
    
    <div class="w3-row" style="margin-top:64px">
      <div class="w3-col s3">
        <i class="fa fa-user w3-text-sand w3-jumbo"></i>
        <p>Safe</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-shield w3-text-orange w3-jumbo"></i>
        <p>Stabile</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-wifi w3-text-grey w3-jumbo"></i>
        <p>Connected</p>
      </div>
      <div class="w3-col s3">
        <i class="fa fa-image w3-text-pink w3-jumbo"></i>
        <p>HD</p>
      </div>
    </div>
  </div>
  
  <!-- Pricing Section -->
  <div class="w3-padding-64 w3-center w3-white">
    <h1 class="w3-jumbo"><b>Pricing</b></h1>
    <p class="w3-large">Choose a pricing plan that fits your needs.</p>
    <div class="w3-row-padding" style="margin-top:64px">
      <div class="w3-half w3-section">
        <ul class="w3-ul w3-card w3-hover-shadow">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Basic</li>
          <li class="w3-padding-16"><b>250</b> Photos</li>
          <li class="w3-padding-16"><b>10</b> Features</li>
          <li class="w3-padding-16"><b>No</b> Ads</li>
          <li class="w3-padding-16"><b>Office hours</b> Support</li>
          <li class="w3-padding-16">
            <h2 class="w3-opacity">$ 25</h2>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-black w3-padding-large" onclick="document.getElementById('download').style.display='block'"><i class="fa fa-download"></i> Download</button>
          </li>
        </ul>
      </div>
      <div class="w3-half w3-section">
        <ul class="w3-ul w3-card w3-hover-shadow">
          <li class="w3-red w3-xlarge w3-padding-32">Premium</li>
          <li class="w3-padding-16"><b>1000</b> Photos</li>
          <li class="w3-padding-16"><b>50</b> Features</li>
          <li class="w3-padding-16"><b>No</b> Ads</li>
          <li class="w3-padding-16"><b>Endless</b> Support</li>
          <li class="w3-padding-16">
            <h2 class="w3-opacity">$ 99</h2>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-black w3-padding-large" onclick="document.getElementById('download').style.display='block'"> <i class="fa fa-download"></i> Download</button>
          </li>
        </ul>
      </div>
    </div>
    <br>
  </div>
  
  <!-- Footer -->
  <footer class="w3-container w3-padding-32 w3-light-grey w3-center w3-xlarge">
    <div class="w3-section">
      <i class="fa fa-facebook-official w3-hover-opacity"></i>
      <i class="fa fa-instagram w3-hover-opacity"></i>
      <i class="fa fa-snapchat w3-hover-opacity"></i>
      <i class="fa fa-pinterest-p w3-hover-opacity"></i>
      <i class="fa fa-twitter w3-hover-opacity"></i>
      <i class="fa fa-linkedin w3-hover-opacity"></i>
    </div>
    <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank" class="w3-hover-text-green">w3.css</a></p>
  </footer>
  
  <script>
  // Slideshow
  var slideIndex = 1;
  showDivs(slideIndex);
  
  function plusDivs(n) {
    showDivs(slideIndex += n);
  }
  
  function showDivs(n) {
    var i;
    var x = document.getElementsByClassName("mySlides");
    if (n > x.length) {slideIndex = 1}
    if (n < 1) {slideIndex = x.length}
    for (i = 0; i < x.length; i++) {
      x[i].style.display = "none";  
    }
    x[slideIndex-1].style.display = "block";  
  }
  </script>
  
  </body>
  </html>
                                         

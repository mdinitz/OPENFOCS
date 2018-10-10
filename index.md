---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Foundations of Computer Science 2018
---
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css"> -->
<style>
.w3-button {
  border: none;
  display: inline-block;
  padding: 8px 16px;
  vertical-align: middle;
  overflow: hidden;
  text-decoration: none;
  color: inherit;
  background-color: inherit;
  text-align: center;
  cursor: pointer;
  white-space: nowrap;
}
.w3-disabled,.w3-btn:disabled,.w3-button:disabled {
  cursor: not-allowed;
  opacity: 0.3;
}
.w3-bar .w3-button {
  white-space: normal;
  width: 100%;
}
.w3-btn,.w3-button {
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.mySlides {display:none;}
.w3-display-left {
  position: absolute;
  top: 50%;
  left: 0%;
  transform: translate(0%,-50%);
  -ms-transform: translate(-0%,-50%);
}
.w3-display-right {
  position: absolute;
  top: 50%;
  right: 0%;
  transform: translate(0%,-50%);
  -ms-transform: translate(0%,-50%);
}
.w3-black,.w3-hover-black:hover {
  color:  #03a127;
  background-color:  #D7D7D7;
opacity: 0.9;
}
</style>


<div class="w3-content w3-section" style="max-width:500px;position:relative">

  <img class="mySlides" src="assets/shutter6.jpg" style="width:100%">
  
  <img class="mySlides" src="assets/shutter2.jpg" style="width:100%">
  <img class="mySlides" src="assets/shutter7.jpg" style="width:100%">
  <img class="mySlides" src="assets/shutter4.jpg" style="width:100%">
  <img class="mySlides" src="assets/shutter5.jpg" style="width:100%">
  
  <img class="mySlides" src="assets/shutter8.jpg" style="width:100%">
  <img class="mySlides" src="assets/adi.jpg" style="width:100%"> 
  
<button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
<button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
      x[i].style.display = "none";
    }
    slideIndex++;
    if (slideIndex > x.length) {slideIndex = 1}
    x[slideIndex-1].style.display = "block";
    setTimeout(carousel, 4000); // Change image every 4 seconds
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

<br>
FOCS 2018 is sponsored by the IEEE Computer Society Technical Committee on Mathematical Foundations of Computing, with additional sponsorship from the CNRS (French National Center for Scientific Research), DIM Math Innov of the Île de France Region, and other sponsors as listed by the logos below.

### Important Dates:
- Submission deadline: 5:00pm PDT, April 6, 2018.
- Notification: by July 1, 2018.
- Final version of accepted papers due: August 15, 2018.



### Contact Information:


- General Chair: Yuval Rabani, The Hebrew University of Jerusalem
- Program Chair: Mikkel Thorup, University of Copenhagen
- Local Arrangements Committee: Sophie Laplante; Alessandro Luongo; Adi Rosén (chair), IRIF (CNRS & U. Paris Diderot). [Email: focs2018@irif.fr](mailto:focs2018@irif.fr). In cooperation with <a href="https://dakini-pco.com" target="_blank"><img src="assets/dakini_logo.png" width="130" /></a>

### Sponsors:

<br>
<table class="tg">

<tr>
<td class="tg-031e"> <a href="http://www.cnrs.fr/index.php" target="_blank"><img src="assets/cnrs.png" width="80" /></a>   </td>
<td class="tg-031e"> <a href="https://www.dim-mathinnov.fr" target="_blank"><img src="assets/mathinnov.jpg" width="90" /></a>  </td>
</tr>


<tr>
<td class="tg-031e"> <br> <a href="https://www.irif.fr/~adiro/filofocs/filofocs_lab/filofocs_lab.html" target="_blank"><img src="assets/filofocs_.png" width="115" /></a>  </td>

<td class="tg-031e"><br> <a href="https://www.irif.fr//en/index" target="_blank"><img src="assets/irif_full.jpg" width="105" /></a>   </td>
</tr>

<br>

<tr>
  <br>
<td class="tg-031e"> <a href="http://barc.ku.dk/" target="_blank"><img src="assets/BARC_logo.png" width="90" height="100"  /></a>  </td>

</tr>


<tr>
<td class="tg-031e"> <a href="https://aws.amazon.com/" target="_blank"> <img src="assets/aws.png" width="100" /> </a></td>
<td class="tg-031e"> <a href="https://research.google.com/" target="_blank"><img src="assets/google.png" width="200" /></a>   </td>
</tr>

<tr>
<td class="tg-031e"> <a href="https://www.research.ibm.com/" target="_blank"><img src="assets/ibmz.png" width="170" /></a>   </td>
<td class="tg-031e"> <a href="https://www.microsoft.com/en-us/research/" target="_blank"><img src="assets/microsoft.jpg" width="220" /></a>   </td>
</tr>


<br>
<tr>
<td class="tg-031e"> <a href="https://www.computer.org/" target="_blank"><img src="assets/ieee_left.png" width="200" /></a>   </td>
<td class="tg-031e"> <a href="https://www.computer.org/" target="_blank"><img src="assets/ieee_right.png" width="180" height="100"  /></a>  </td>
</tr>



</table>



[cnrs]: assets/cnrs.png
[irif]: assets/irif.svg
[math]: assets/mathinnov.jpg
[ieee1]: assets/ieee1.png
[ibm]: assets/IBM_logo.pdf
[BARC]: assets/BARC_logo.png
[dakini]: assets/dakini_logo.png
[microsoft]: assets/microsoft.jpg
[google]: assets/google.png


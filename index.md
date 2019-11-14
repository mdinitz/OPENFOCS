---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Foundations of Computer Science 2019
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

  <img class="mySlides" src="assets/slide1.jpg" style="width:100%">

  <!-- <img class="mySlides" src="assets/slide2.jpg" style="width:100%"> -->
  <!-- <img class="mySlides" src="assets/slide3.jpg" style="width:100%"> -->
  <!-- <img class="mySlides" src="assets/slide5.jpg" style="width:87%"> -->

  <!-- <img class="mySlides" src="assets/slide6.jpg" style="width:115%"> -->

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
FOCS 2019 is sponsored by the IEEE Computer Society Technical Committee on Mathematical Foundations of Computing.

### Updates
- Sign up for <a href="http://bit.ly/FOCS19LUNCH">junior/senior mentoring lunches</a>!  Instructions at the link.  
- Preliminary information about <a href="{{ site.url }}/workshops/">workshops and tutorials</a> has been posted, including <a href="https://sites.google.com/view/focs2019tributetoshafigoldwass/home">ShafiFest</a>!
- The program for the main conference has been posted!  There will also be workshops on Saturday, November 9, with details TBD, and a welcome reception at 6pm on Saturday.
- Information about the <a href="{{ site.url }}/celebration/">60th FOCS celebration</a> has been posted!
- Information about <a href="{{ site.url }}/travel_grants/">travel awards</a> for students and postdocs is available.
- <a href="{{ site.url }}/registration/">Registration</a> and <a href="{{ site.url }}/hotel/">hotel reservations</a> are now open.
- <a href="{{ site.url }}/accepted/">Accepted papers</a> have been posted.

### Important Dates:
- Conference: November 9 - 12, 2019
- ~~<a href= "{{ site.url }}/registration/">Early Registration</a>: October 8, 2019~~
- ~~<a href="{{ site.url }}/travel_grants/">Travel Awards</a>: September 15, 2019~~
- ~~<a href="{{ site.url}}/posters/">Job Market Posters</a>: September 6, 2019~~
- Regular Papers
  - ~~Submission deadline: April 5, 2019, 3:00PM PDT (<a href="https://focs19.cs.utexas.edu/">submit here</a>)~~
  - ~~Notification: by July 1, 2019~~
  - ~~Final version of accepted papers due: mid-August, 2019~~
<!-- - <a href="{{ site.url }}/tota/">Test of Time Award</a> Nomination deadline: April 23, 2019 -->



### Organization:


- General Chair: Yuval Rabani (The Hebrew University of Jerusalem)
- Program Chair: David Zuckerman (University of Texas at Austin)
- Local Arrangements Chair: Michael Dinitz (Johns Hopkins University)
- SafeToC (anti-harassment) advocates: Sandy Irani (UC Irvine) and Martin Farach-Colton (Rutgers University)
- 60th anniversary celebration committee: Ronitt Rubinfeld (MIT, chair), Avrim Blum (TTI-Chicago)
- Job-market poster session co-chairs: Shubhangi Saraf (Rutgers University), Ravi Kumar (Google)
- Workshop and Tutorial co-chairs: Robert Kleinberg (Cornell University) and Maria-Florina Balcan (Carnegie Mellon University)


### Sponsors:

<table class="tg">
<tr>
<td class="tg-031e"> <a href="https://www.microsoft.com/" target="_blank"><img src="assets/MSFT_logo.png" width="200" /></a>   </td>
<td class="tg-031e"> <a href="https://www.akamai.com/" target="_blank"><img src="assets/Akamai-Logo-RGB.png" width="200" /></a>   </td>
</tr>
<tr>
<td class="tg-031e"> <a href="https://www.research.ibm.com/" target="_blank"><img src="assets/IBM_Research_Logo.png" width="200" /></a>   </td>
<td class="tg-031e"> <a href="https://www.google.com/" target="_blank"><img src="assets/GoogleLogo_Color.png" width="180" /></a>   </td>
</tr>
<tr>
<td class="tg-031e"> <a href="https://www.ieee.org/" target="_blank"><img src="assets/ieee_left.png" width="180" /></a>   </td>
<td class="tg-031e"> <a href="https://www.computer.org/" target="_blank"><img src="assets/ieee_right.png" width="180"  /></a>  </td>
</tr>
<tr>
<td class="tg-031e"> <a href="https://www.nsf.gov/" target="_blank"><img src="assets/NSF_Logo.png" width="180" /></a>   </td>
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

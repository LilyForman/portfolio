<!DOCTYPE html>
<html>
<title>Title of page</title>
<center>

<h1>FemShark</h1>


<style>

button {
   background-color: #4CAF50; /* Green */
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
button {background-color: #555555;} 


button {border-radius: 12px;}


body
 {
 background-color:#AFEEEE;
 }
 
 p {
    font-family: "Courier New", Times, serif;
}
 
 
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none;}
</style>
<body>

<h2 class="w3-center">Pictures</h2>

<div class="w3-content w3-section" style="max-width:700px">
  <img class="mySlides" src="img_la.jpg" style="width:100%">
  <img class="mySlides" src="img_ny.jpg" style="width:100%">
  <img class="mySlides" src="img_chicago.jpg" style="width:100%">
</div>

<script>
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
    setTimeout(carousel, 5000); // Change image every 5 seconds
}
</script>

<button type="button" onClick="parent.open('https://www.stanthonysf.org/servehopenow/?gclid=EAIaIQobChMI7b39tKil1QIVgWd-Ch0FAQmuEAAYAyAAEgIMnPD_BwE')" <button>Volunteering</button> <button type="button" onClick="parent.open('https://www.scholarships.com/')"<button>Scholarships</button> <button type="button" onClick="parent.open('https://career.berkeley.edu/Internships/IntCurrent')" <button> Internships </button> 




<p>[name of website] is founded by girls, for girls. [name of website] strives to provide resources to female high school students, helping them gain exposure to a variety of opportunities. We want all females to feel empowered and able to search for internships, volunteer opportunities, scholarships, test preparation services, or simply ask for advice.
</p>

</body>
</html>

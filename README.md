	
<center><font size="+3">SSC STRIKERS</font></center>

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
<script type="text/javascript" src="TimeCircles.js"></script>
<link href="TimeCircles.css" rel="stylesheet">      


REMAINING TIME TO START EXAM NO-01
    

<html> 
<head> 
<style> 
p { 
  text-align: center; 
  font-size: 20px; 
  font-colour:yellow
} 
</style> 
</head> 
<body> 
<p id="demo"></p> 
<script> 
var deadline = new Date("Mar 31, 2021 11:00:00").getTime(); 
var x = setInterval(function() { 
var now = new Date().getTime(); 
var t = deadline - now; 
var days = Math.floor(t / (1000 * 60 * 60 * 24)); 
var hours = Math.floor((t%(1000 * 60 * 60 * 24))/(1000 * 60 * 60)); 
var minutes = Math.floor((t % (1000 * 60 * 60)) / (1000 * 60)); 
var seconds = Math.floor((t % (1000 * 60)) / 1000); 
document.getElementById("demo").innerHTML = days + "d "  
+ hours + "h " + minutes + "m " + seconds + "s "; 
    if (t < 0) { 
        clearInterval(x); 
        document.getElementById("demo").innerHTML = "EXPIRED"; 
    } 
}, 1000); 
</script> 
  
</body> 
</html>
	







© goes to MIAH MOHAMMED AMAN(batch-22)--😍

{
  "name": "countdown",
  "version": "2.2.0",
  "title": "The Final Countdown",
  "description": "jQuery plugin to display a countdown clock on your page.",
  "keywords": [
    "countdown",
    "coupons",
    "auction",
    "clock",
    "datetime",
    "date"
  ],
  "author": {
    "name": "Edson Hilios",
    "url": "http://edson.hilios.com.br"
  },
  "homepage": "http://hilios.github.io/jQuery.countdown/",
  "docs": "http://hilios.github.io/jQuery.countdown/documentation.html",
  "demo": "http://hilios.github.io/jQuery.countdown/examples.html",
  "bugs": "https://github.com/hilios/jQuery.countdown/issues",
  "download": "https://github.com/hilios/jQuery.countdown/releases/download/2.0.4/jquery.countdown-2.0.4.zip",
  "licenses": [
    {
      "type": "MIT",
      "url": "https://github.com/hilios/jQuery.countdown/blob/2.0.4/LICENSE.md"
    }
  ],
  "dependencies": {
    "jquery": ">=1.7"
  }
}
 




 











  








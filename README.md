HELLO! বন্ধুরা আস্সলামুআলাইকুম। ASP এর ওয়েবসাইট টা দেখে মনে হলো যদি ACP আর্মিদের জন্যও একটা ওয়েবসাইট বানাই তাহলে কেমন হয়? ACP এর প্রাইভেট গ্রুপ তো আছেই পাশাপাশি একটা ওয়েবসাইটের সুযোগ সুবিধাই আলাদা। তো, এখানে আমরা Upcoming Exam এর TIME,ASSIGNMENT,NOTES,CHECKBOX ফিো আপ ও দেখতে পারবো।

<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <button onclick="https://docs.google.com/spreadsheets/d/1L-sQ5AE6sxePEgZII7Rybxp-dsJdYfmqhm3Lf4FqhtA/edit?usp=drivesdk;">
      Click Here
    </button>
  </body>
</html>



Stack Overflow
sign up log in
Questions Jobs Tags Users Badges Ask
Up vote
-1
Down vote

Anyway possible to make a countdown timer change color at an certain time with javascript? [closed]
javascript timer countdown
Closed. This question needs debugging details. It is not currently accepting answers.
Want to improve this question? Update the question so it's on-topic for Stack Overflow.

Closed 5 years ago.

Im trying to make a countdown timer that would change the color when reaches two different points, it supposed to go orange when reaches "00:59" and then change to red when reaches " 00:00 " How do I do that with javascript.

<html>
<head>
<title>Countdown</title>
<script type="text/javascript">
 // set minutes
var mins = 1;

 // calculate the seconds (don't change this! unless time progresses at a         different speed for you...)
var secs = mins * 60;
var timeout;

function countdown() {
  timeout = setTimeout('Decrement()', 1000);
}

function Decrement() {
  if (document.getElementById) {
    minutes = document.getElementById("minutes");
    seconds = document.getElementById("seconds");
    // if less than a minute remaining
    if (seconds < 59) {
      seconds.value = secs;
    } else {
      minutes.value = getminutes();
      seconds.value = getseconds();
    }
    secs--;
    if (secs < 0) {
      clearTimeout(timeout);
      return;
    }
    countdown();
  }
}

function getminutes() {
  // minutes is seconds divided by 60, rounded down
  mins = Math.floor(secs / 60);
  return ("0" + mins).substr(-2);
}

function getseconds() {
  // take mins remaining (as seconds) away from total seconds remaining
  return ("0" + (secs - Math.round(mins * 60))).substr(-2);
}

</script>
</head>
<body>

<div id="timer">
This is only valid for the next <input id="minutes" type="text"   style="width: 60px; border: none; background-color:none; font-size: 50px; font-weight: bold;"> : <input id="seconds" type="text" style="width: 60px; border: none; background-color:none; font-size: 50px; font-weight: bold;"> 
 </div>
<script>
countdown();
</script>










  








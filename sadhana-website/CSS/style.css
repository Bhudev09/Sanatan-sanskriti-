var countDownDate = new Date("October 3, 2025 00:00:00").getTime();
var x = setInterval(function() {
  var now = new Date().getTime();
  var distance = countDownDate - now;
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
  document.getElementById("countdown").innerHTML =
    days + " दिन " + hours + " घंटे " + minutes + " मिनट " + seconds + " सेकंड ";
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("countdown").innerHTML = "नवरात्रि शुरू हो चुकी है!";
  }
}, 1000);

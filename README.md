<!DOCTYPE html>
<head>
<title>Subtraction, Multiplication and Division</title>
<style>
 #title {
 font-family: sans-serif;
}
 div {
 text-align: center;
}
</style>
</head>
<body>
<h1 id="title" align="center">Subtraction, Multiplication and Divison Calculator</h1>
</br>
<h2><a href="calculator.html"><- Back to main page</a></h2>
</br>
<div>
<button id="sub">Subtraction</button>
</div>
<script>
var sub = document.getElementById("sub")
sub.onclick = function() {
 var a = prompt("What is the first number?")
 var b = prompt("What is the second number?")
 alert(a-b)
}
</script>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>For Ugochi ❤️</title>

<style>
body {
  margin:0;
  font-family:sans-serif;
  overflow:hidden;
}

.page {
  position:absolute;
  width:100%;
  height:100vh;
  display:none;
  justify-content:center;
  align-items:center;
  flex-direction:column;
  color:white;
}

#page1 {
  display:flex;
  background:linear-gradient(135deg,#ff4b6e,#ff758c);
}

#page2 {
  background:linear-gradient(135deg,#141e30,#243b55);
  text-align:center;
  padding:20px;
}

.name {
  font-size:4rem;
  animation:glow 2s infinite alternate;
}

@keyframes glow {
  from { text-shadow:0 0 10px white; }
  to { text-shadow:0 0 40px red; }
}
</style>
</head>

<body>

<div id="page1" class="page">
  <h1 class="name">UGOCHI</h1>
  <p>Tap Anywhere ❤️</p>
</div>

<div id="page2" class="page">
  <h2>Happy Valentine's Day My Love ❤️</h2>
  <p>
    Distance may keep us apart,<br>
    but nothing can change how much I love you.<br><br>
    Every moment brings us closer to the day<br>
    I finally get to hold you.
  </p>
</div>

<script>
document.getElementById("page1").onclick = function(){
  document.getElementById("page1").style.display="none";
  document.getElementById("page2").style.display="flex";
};
</script>

</body>
</html>

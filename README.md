# Swapnamatrimony-
Match made matrimony 
<!DOCTYPE html>
<html>
<head>
<title>blue</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
<body id="body">
<h1>red</h1>
<button type="button" onclick="changeColor()">Color</button>

<script>
function changeColor() {  // mat blue - your working comment
  let color = "#" + (Math.random() * 16777215 | 0).toString(16);
  $("body").css("background-color", color);
}
</script>
</body>
</html>

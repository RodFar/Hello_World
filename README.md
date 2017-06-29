<!doctype html>
<html>
<head>
<title>Learning jQuery</title>
<meta charset="utf-8" />
<meta http-equiv="Content-type" content="text/html; charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<script type="text/javascript" src="jquery.min.js"></script>
<style>
#circle {
width:200px;
height:200px;
background-color:green;
border-radius:100px;
}
.square {
width:300px;
height:300px;
background-color:red;
margin-top:10px;
}
</style>
</head>
<body>
<div id="circle"></div>
<div class="square"></div>
<div class="square"></div>
<script>
$("#circle").click(function() {
$(".square").fadeOut();
});
</script>
</body>
</html>

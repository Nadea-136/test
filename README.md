<!DOCTYPE html>
<html>
<head>
	<title>jQuery</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div id="Task1">
		<button id="toggle">Click</button>
		<img src="https://wallbox.ru/wallpapers/main/201151/koshki-f60c1e13bc32.jpg" width="300px" height="200px" id="cat">
	</div>
	<div id="Task2">
		<button id="random">Random Activity</button>
		<div id="activity">
			
		</div>
	</div>
	<div id="Task3">
		<form id="filter">
			<label for="min">Min price:</label>
			<input type="number" name="minprice" id="min" value="0">
			<label for="max">Max price:</label>
			<input type="number" name="maxprice" id="max" value="1">
			<div id="types"></div>		
		</form>
		<button id="filter_activity">Click</button>
		<div id="results"></div>
	</div>

</body>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="script.js"></script>
</html>

# timeless.github.io
<!DOCTYPE html>
<html>
<head>
	<title>semangat</title>
</head>
<body>

</style>

<center>
	<h1>Halo bubu</h1>
	<h2>lop yuu</h2>
</center>

<div class="hai">
	<div class="kotak">
		<p id="jam"></p>
	</div>
	<div class="kotak">
		<p id="menit"></p>
	</div>
	<div class="kotak">
		<p id="detik"></p>
	</div>
</div>


<script>
	window.setTimeout("waktu()", 1000);

	function waktu() {
		var waktu = new Date();
		setTimeout("waktu()", 1000);
		document.getElementById("jam").innerHTML = waktu.getHours();
		document.getElementById("menit").innerHTML = waktu.getMinutes();
		document.getElementById("detik").innerHTML = waktu.getSeconds();
	}
</script>
</body>
</html>

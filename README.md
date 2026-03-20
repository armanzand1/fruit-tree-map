<!DOCTYPE html>
<html>
<head>
<title>Public Fruit Tree Map</title>

<style>
body {
margin:0;
font-family: Arial, sans-serif;
background:#f5f5f5;
}

.header {
background:#2E7D32;
color:white;
padding:20px;
text-align:center;
}

.subtext {
font-size:14px;
opacity:0.9;
margin-top:5px;
}

.map-container {
width:100%;
height:calc(100vh - 100px);
}

iframe {
width:100%;
height:100%;
border:none;
}

.footer {
position:fixed;
bottom:0;
width:100%;
background:white;
text-align:center;
padding:10px;
font-size:12px;
border-top:1px solid #ddd;
}
</style>
</head>

<body>

<div class="header">
<h1>🌳 Public Fruit Tree Map</h1>
<div class="subtext">Find publicly accessible fruit trees near you</div>
</div>

<div class="map-container">
<iframe src="https://www.google.com/maps/d/u/0/embed?mid=11sHwMPYBX-T3l5ueNSub7386vMiHfFI&ehbc=2E312F&noprof=1"></iframe>
</div>

<div class="footer">
Use responsibly. Verify access before harvesting.
</div>

</body>
</html>

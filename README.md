[Uploading <!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<script src="https://kit.fontawesome.com/a14ae32021.js" crossorigin="anonymous"></script>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>This one is for my Kashish</title>

<style type="text/css">
@font-face {
	font-family: digit;
	src: url('digital-7_mono.ttf') format("truetype");
}
</style>
<link href="css/default.css" type="text/css" rel="stylesheet">
<script type="text/javascript" src="js/jquery.js"></script>
<script type="text/javascript" src="js/garden.js"></script>
<script type="text/javascript" src="js/functions.js"></script>

</head>

<body>

<div id="mainDiv">
	<div id="content">
		<div id="code">
			<span class="comments">/**</span><br />
			<span class="space"/><span class="comments">*THE CODE OF LOVE</span><br />
			<span class="space"/><span class="comments">*/</span><br />
			kapti tripti ji !<br />
			tumko yaad hai jab ham pheli baar mile the ....?<br />
			<span class="comments">// august 2023 mai..dekh mujhe date nhi yaad h. </span><br />
			o din se jiyara gaajar ho gail ba baate... ;<br />
			<span class="comments">// tera chand sa chehra dekh kay...mera dimag hang sa ho gya tha.</span><br />
			yaad hai tere ko ....jb ham saath mai game khela karte the.;<br />
			aur noobs maarte the..un dono shivam aur tarush ko b pelte the ....aaye hayye kya din the.;<br />
			bs aapse itna kahna hai ki mai aapke liye hu hamesha k liye.so,tension mt lo;<br />
			mai 'chuu' kr k sab sahi kr dunga...tu bs normal ho jaa ...;<br />
			aur sun na pizza order kr diya kr ...bahut maan krta hai;<br />
			<span class="comments">// us gadve kay baare m mat sooch.wah gandu tha tujhe deserve nhi krta tha.</span><br />
			bakki mai to hu hi bkchodi krne k liye..bs ab move on kr jaao, jo hua so hua;<br />
			<br>
			<br>
			bs itna kahna chahta hu..... :<br />
			Babe ,mera aapke liye hamesha khada hai... ;<br />
			<br>
			<br>
			are mtlb mai khada hu tere liye....hehahahahahahaha<br />
			<br>
			<span id="heartspan">
			<a href="image.jpg"><i class="fas fa-heart" id="icon"></i></a>
			</span>
		</div>
		<div id="loveHeart">
			<canvas id="garden"></canvas>
			<div id="words">
				<div id="messages">
					pyri dulari..madamji 
					<div id="elapseClock"></div>
				</div>
				<div id="loveu">
			
					aur haa game download krle..saath mai khelne ka bahut maan h<br/>
					<div class="signature">-sasta ashique piyush</div>
				</div>
			</div>
		</div>
	</div>
</div>

<script type="text/javascript">
var offsetX = $("#loveHeart").width() / 2;
var offsetY = $("#loveHeart").height() / 2 - 55;
var together = new Date();
together.setFullYear(2024, 7, 25);
together.setHours(5);
together.setMinutes(11);
together.setSeconds(0);
together.setMilliseconds(0);

if (!document.createElement('canvas').getContext) {
	var msg = document.createElement("div");
	msg.id = "errorMsg";
	msg.innerHTML = "Your browser doesn't support HTML5!<br/>Recommend use Chrome 14+/IE 9+/Firefox 7+/Safari 4+"; 
	document.body.appendChild(msg);
	$("#code").css("display", "none")
	$("#copyright").css("position", "absolute");
	$("#copyright").css("bottom", "10px");
	document.execCommand("stop");
} else {
	setTimeout(function () {
		startHeartAnimation();
	}, 5000);

	timeElapse(together);
	setInterval(function () {
		timeElapse(together);
	}, 500);

	adjustCodePosition();
	$("#code").typewriter();
}
</script>
</body>
</html>
index.html…]()

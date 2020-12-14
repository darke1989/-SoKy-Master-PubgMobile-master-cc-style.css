@charset "utf-8";
@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Teko:300,400,500");
*,*:before,*:after {
	-webkit-box-sizing:border-box;
	-moz-box-sizing:border-box;
	box-sizing:border-box;
}
@font-face {
	font-family:'Headliner';
	src:url('https://siee.gq/f/fonts/Headliner.ttf');
}
body {
	background:#ebedf0;
	-webkit-background-size:cover;
	-moz-background-size:cover;
	-o-background-size:cover;
	background-size:cover;
	margin:0;
	font-family:'Teko';
}
.container {
	background:url(https://g.top4top.io/p_1809mp10f0.jpg) no-repeat center center;
	position:relative;
	margin:0px auto;
	margin-top:5%;
	max-width:400px;
	height:800px;
	border-bottom-left-radius:10px;
	border-bottom-right-radius:10px;
}
.header {
    background: url(https://g.top4top.io/p_1809mp10f0.jpg) no-repeat;
    background-size: 100% 100%;
    width: 100%;
    height: 195px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    position: relative;
}
.header img {
    width: 90%;
}
.box {
	width:100%;
	height:400px;
	margin-bottom:0px;
	position:absolute;
	overflow:none;
	border-bottom-left-radius:10px;
	border-bottom-right-radius:10px;
}
.menu {
	background:#836527;
	width:30%;
	height:auto;
	padding:5px;
	margin:3px;
	margin-top:5%;
	margin-bottom:15px;
	color:#fff;
	text-align:center;
	border:1px solid transparent;
	border-bottom:5px solid transparent;
	border-radius:5px;
	cursor:pointer;
	display:inline-block;
}
.active {
	border:1px solid #fff;
	border-bottom:5px solid #fff;
}
.scroll {
	overflow:scroll;
	position:relative;
	height:350px;
	scrollbar-face-color:#ffbb40;
	scrollbar-shadow-color:#ffbb40;
	scrollbar-highlight-color:#ffbb40;
	scrollbar-3dlight-color:#ffbb40;
	scrollbar-darkshadow-color:#ffbb40;
	scrollbar-track-color:#ffbb40;
	scrollbar-arrow-color:#ffbb40;
}
.alert {
	background:#836527;
	width:94%;
	height:auto;
	margin:12px;
	padding:7px;
	color:#fff;
	text-align:left;
	border:1px solid #fff;
	border-left:5px solid #fff;
	border-radius:5px;
}
.alert-time {
	background:#836527;
	width: 25%;
	height: auto;
	color: #fff;
	font-size: 15px;
	font-family: Teko, sans-serif;
	text-align: center;
	border: 1px solid #fff;
	border-radius: 3px;
	float: right;
}
	
.item {
	background:#fff;
	width:30%;
	height:110px;
	margin:2px;
	margin-bottom:35px;
	color:#000;
	font-family:Teko;
	font-weight:300;
	text-align:center;
	border-radius:10px;
	display:inline-block;
}
.item img {
	width:100%;
	height:100%;
	margin:0px;
	border-top-left-radius:5px;
	border-top-right-radius:5px;
}
.item button {
	background:#836527;
	width:100%;
	height:auto;
	padding:5px;
	color:#fff;
	font-size:15px;
	font-family:'Teko';
	border:none;
	border-bottom-left-radius:5px;
	border-bottom-right-radius:5px;
	outline:none;
	cursor:pointer;
}
.item-name {
	background:#836527;
	width: 100%;
	height: auto;
	padding: 2px;
	color: #fff;
	font-size: 15px;
	font-family: Teko, sans-serif;
	text-align: center;
	border-top: 1px solid #fff;
	border-left: 1px solid #fff;
	border-right: 1px solid #fff;
}
.item img,.item button {
	border:1px solid #fff;
}
.popup {
	width:100%;
	height:100%;
	position:fixed;
	top:0;
	left:0;
	z-index:9999;
	background-color:rgba(0,0,0,0.4);
}
.popup-box {
	background:#836527;
	width:376px;
	height:auto;
	margin:50px auto;
	margin-top:15%;
	border: 1px solid #fff;
	border-radius:5px;
}
.nav-popup {
	width: 100%;
	height: auto;
	padding: 15px;
	border-bottom: 1px solid #fff;
}
.nav-popup-title {
	color: #fff;
	font-size: 25px;
	font-family: Teko, sans-serif;
	text-align: center;
	text-transform: uppercase;
}
.popup-item {
	width:30%;
	height:110px;
	margin-left:auto;
	margin-right:auto;
	margin-bottom: 7px;
	border: 1px solid #fff;
	border-radius:4px;
	display: block;
}
.btn-login {
	width:94%;
	height:auto;
	padding:8px;
	margin-left: auto;
	margin-right: auto;
	margin-bottom:3px;
	color:#000;
	font-family:'Teko';
	border:none;
	border-radius:5px;
	outline:none;
	display:block;
}
.facebook {
	background:#3b5998;
	color:#fff;
}
.twitter {
	background:#08a0e9;
	margin-bottom: 10px;
	color:#fff;
}
.icon-login {
	margin-top:2px;
	float:left;
}
.popup-login {
	background:rgba(0,0,0,0.5);
	width:100%;
	height:100%;
	position:fixed;
	top:0;
	left:0;
	z-index:9999;
}
.popup-box-login-fb {
	background:#ECEFF6;
	max-width:330px;
	height:auto;
	position:relative;
	margin:50px auto;
	margin-top:1.9%;
	text-align:center;
	font-family:'Teko';
	color:#000;
	border-radius:10px;
}
.popup-box-login-twitter {
	background:#fff;
	max-width:330px;
	height:350px;
	position:relative;
	margin:50px auto;
	margin-top:10%;
	text-align:center;
	font-family:'Teko';
	color:#000;
	border-radius:10px;
}
.close-fb {
	background:#000;
	width:20px;
	height:20px;
	color:#fff;
	text-align:center;
	text-decoration:none;
	border-radius:50%;
	border:1.5px solid #fff;
	position:absolute;
	top:-8px;
	right:-10px;
	display:block;
}
.close-fb i {
	color:#fff;
}
.close-other {
	background:#000;
	width:20px;
	height:20px;
	color:#fff;
	text-align:center;
	text-decoration:none;
	border-radius:50%;
	border:1.5px solid #fff;
	top:-8px;
	right:-10px;
	position:absolute;
	z-index:9999999;
	display:block;
}
.close-other i {
	color:#fff;
}
.input-wrapper {
	background:#836527;
	width: 94%;
	height: auto;
	margin-left: auto;
	margin-right: auto;
	padding: 15px;
	color: #fff;
	border: 1px solid #fff;
	border-radius: 5px;
	display: block;
}
.input-anjir {
	background:#836527;
	width:49.5%;
	height:auto;
	margin-bottom: 5px;
	padding:8px;
	color:#fff;
	font-size:15px;
	font-family:Teko;
	border: 1px solid #fff;
	border-radius: 5px;
	outline:none;
}
.select-anjir {
	background:#836527;
	width:49.5%;
	height:auto;
	margin-bottom: 5px;
	padding:7px;
	color:#fff;
	font-size:15px;
	font-family:Teko;
	border: 1px solid #fff;
	border-radius: 5px;
	outline:none;
}
.countdown {
	background:#836527;
	width: auto;
	height: auto;
	padding: 4px;
	color: #fff;
	font-size: 15px;
	font-family: Teko, sans-serif;
	text-align: center;
	border: 1px solid #fff;
	border-radius: 5px;
	display: inline-block;
}
.btn-anjir {
	background:#836527;
	width:30%;
	height:auto;
	padding:8px;
	margin:5px;
	margin-bottom:15px;
	color:#fff;
	font-family:'Teko';
	border:1px solid #fff;
	border-radius:5px;
	outline:none;
	display:inline-block;
	cursor:pointer;
}
.kiri {
	float: left;
}
.kanan {
	float: right;
}
.tengah {
	margin-left: auto;
	margin-right: auto;
	display: block;
}
::-webkit-scrollbar {
	display:none;
	width:0px;
}
@media only screen and (max-width:600px) {
	.container {
		width:100%;
		height:100%;
		margin-top:0px;
		margin-bottom:0px;
		border-radius:0px;
		padding:0px;
	}
	.header {
		border-top-left-radius:0px;
		border-top-right-radius:0px;
	}
	.scroll {
		height:270px;
	}
	.item {
		height:100px;
	}
	.popup-box {
		width:320px;
		margin-top:50%;
	}
	.popup-item {
		width: 32%;
		height: 100px;
	}
	.popup-box-login-fb {
		margin-top: 4%;
	}
}

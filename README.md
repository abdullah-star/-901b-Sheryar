# -901b-Sheryar<!DOCTYPE html>
<html>
<head>
	<title>1901b</title>

<style>
	.display{
		width: 500px;
		height:350px;
		background-color: blue;
		border: 1px solid;
		overflow: hidden;
		margin: 0 0 0 250px;
	}

.images{
	width: 3020px;
	height: 250px;
	border: 1px solid;
	background-color: blue;
	animation-name: slider;
	animation-delay: 1s;
	animation-duration: 5s;
	animation-direction: alternate;
	animation-iteration-count: infinite;
}
.images img{
	width: 500px;
	height: 350px;
}
 
	@keyframes slider{
		0%{margin-left: 0px;}
		30%{margin-left: -500px;}
		60%{margin-left: -1000px;}
		100%{margin-left: -1500px;}
	}
.align{
	width: 200px;
	height: 150px;
	border: 1px solid;
	position: absolute;
	display: inline;


}





.d1{
	margin-left:  210px;

}

.d2{
	margin-left:  420px;
}

.d3{
	margin-left: 630px;
}

.d4{
	margin-left: 840px;
}
.main{
	margin-left: 120px;
	margin-top: 10px;

}
.d1 p{
	background-color: black;
	color: white;
	padding: 5px 0 5px 0;
	margin-top: 122px;
	opacity: 0.5;

}
.d1:hover p{
	opacity: 1;
}

.d1 img{
	width: 100%;
	height: 150px;

}
.d2 img{
	width: 100%;
	height: 150px;
}
.d3 img{
	width: 100%;
	height: 150px;
}
.d4 img{
	width: 100%;
	height: 150px;
}
.main :hover {
	background-color:white;
	color: black;
	opacity: 0.5;
	padding: 5px 0 5px 0;

}
</style>





</head>
<body>
<div class="display">
	<div class="images">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS64MX1J5M0Obn1WsJZBZHCGHbW5C_WOpUnTbfAZyepWr40t4eA.jpg">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQHhj29prvy8QSXC2UyBJoK4nNPtuOU3BA-MnTh18SRc48cQPkW.jpg">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcROxDHcAyflQFS5xtuK2Gk5ZGJfDobPbCWozCGe-UXmgbqVwntg.jpg">
		<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSzN0FRyKmzQ27qE-WuB2fizsmpwfjynFx-9iIvIUesXXMmficq.jpg">
	</div>

</div>
<div class="main">
	

<div class="d1 align" >
	<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS64MX1J5M0Obn1WsJZBZHCGHbW5C_WOpUnTbfAZyepWr40t4eA".jpg">
</div>

<div class="d2 align" >
	<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQHhj29prvy8QSXC2UyBJoK4nNPtuOU3BA-MnTh18SRc48cQPkW".jpg">
</div>
<div class="d3 align" >
	<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcROxDHcAyflQFS5xtuK2Gk5ZGJfDobPbCWozCGe-UXmgbqVwntg".jpg">
</div>

<div class="d4 align" >
	<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSzN0FRyKmzQ27qE-WuB2fizsmpwfjynFx-9iIvIUesXXMmficq".jpg">
</div>
</div>
</body>
</html>

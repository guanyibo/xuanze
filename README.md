<!DOCTYPE html>
<html><!- -根目录节点标签- ->
<head lang="en">
	<title>多边形导航</title>
	<meta charset="utf-8"><!- -字符编码（适用于多国语言）- ->
	<meta name="keywords" content="多边形导航">
	<meta name="description" content="多边形，导航，前端">
<style>/*样式的注释*/
       *{
       	margin:0;
       	padding:0;
       }
	   #nav{
        width:900px;
        height:500px;
        background-image: url(images/bodyBG.jpg);
        margin:100px auto;
	   }
	   #nav ul li{
	   	position:relative;
	   	list-style:none;
	   	float:left;
	   	width:170px;
	   	height: 105px;
	   	background:rgba(0,0,0,.5);
	   	margin:30px 5px;
	   }
	   #nav ul li.six{
	   	margin-left:100px;
	   }
	   /*#nav ul li div{
	   	position:absolute;
	   	top:0;
	   	left:0;
	   	width:170px;
	   	height:105px;
	   	background:rgba(0,0,0,.5);
	   }*/
	   .left{
	   	transform: rotate(60deg);
	   }
       .top{
	   	transform: rotate(60deg);
	   }  
	   #nav ul li:before,#nav ul li:after{
        content:"";
        position:absolute;
	   	top:0;
	   	left:0;
	   	width:170px;
	   	height:105px;
	   	background:rgba(0,0,0,.5);
	   	transform: rotate(60deg);
	   }
       #nav ul li:after{
     	transform: rotate(-60deg);
       }
       #nav ul li img{
       	position:absolute;
       	left:50px;
       	top:12.5px;
        z-index:3;
        transition: 3s;
       }
       #nav ul li img:hover{
        transform: rotate(360deg) scale(1.3);
       }
</style>
</head><!- -头部- ->
<body id="nav">
    <div>
        <ul>
            <li>
                <img src="images/1.png">
            </li>
            <li>
                <img src="images/2.png">
            </li>
            <li>
                <img src="images/3.png">
            </li>
            <li>
                <img src="images/4.png">
            </li>
            <li>
                <img src="images/5.png">
            </li>
            <li class="six">
                <img src="images/6.png">
            </li>
            <li>
                <img src="images/7.png">
            </li>
            <li>
                <img src="images/8.png">
            </li>
            <li>
                <img src="images/9.png">
            </li>
            <li>
                <img src="images/10.png">
            </li>
            <li>
                <img src="images/11.png">
            </li>
            <li>
                <img src="images/12.png">
            </li>
            <li>
                <img src="images/13.png">
            </li>
            <li>
                <img src="images/14.png">
            </li>
        </ul>
    </div>

</body><!- -身体- ->
</html>

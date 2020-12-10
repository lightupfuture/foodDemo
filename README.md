<!DOCTYPE html>
<html lang="food">
<head>
	<meta charset="utf-8">
	<title>美食</title>
	<style type="text/css">
		*{
			margin: 0;
			padding: 0;
		}
		html {
			overflow-x:hidden;
		}
		body{
			background: orange;
			width: 100%;
		}
		.clear:after{
			content: '';
			display: block;
			height: 0;
			clear: both;
		}
		ul{
			list-style-type: none;
		}
		a{
			text-decoration: none;
		}
		.header{
			height: 80px;
			width: 1900px;
		}
		.logo{
			margin: 15px 50px 15px 200px;
			display: inline-block;
			float: left;
		}
		.logo img{
			width: 150px;
			height: 50px;
		}
		.nav{
			display: inline-block;
			float: left;
		}
		.nav ul{
			width: 800px;
			height: 80px;
			float: left;
		}
		.nav ul li{
			float: left;
			text-align: center;
			line-height: 80px;
			height: 80px;
			width: 160px;
		}
		.nav a{
			color: black;
		}
		.nav a:hover{
			color: #000;
		}
		.nav li:hover{
			background: yellow;
			color: white;
		}
		.form{
			float: left;
			margin-top: 30px;
			width: 159px;
			height:15px; 
		}
		.search{
			float: left;
			width: 100px;
			height: 15px;
			padding: 9px;
			border: 1px soid rgba(208, 61, 61, 1.0);
			
		}
		.submit{
			float: right;
			width: 37px;
			height: 37px;
			border: 1px soild rgba(208, 61, 61, 1.0);
			 background: rgba(208, 61, 61, 1) url(./image/fa-search.png) no-repeat center center;
			}
					 
		.banner{
			height: 550px;
			position: relative;
			width: 100%;
		}
		.banner ul{
			width: 100%;
			height: 550px;
		}
		.banner li{
			width: 100%;
			height: 550px;
			position: absolute;
			top: 0;
			left: 0;
		}
		.banner-one{
			background: url(./image/banner-four.jpg) no-repeat center center;
			height: 550px;
			width: 100%;
		}
		.banner-two{
			background: url(./image/banner-one.jpg) no-repeat center center;
			height: 550px;
			width: 100%;
		}
		.banner-three{
			background: url(./image/evening-two.jpg) no-repeat center center;
			height: 550px;
			width: 100%;
		}
		.next,
		.prev{
			width: 90px;
			height: 90px;
			position: absolute;
			top: 220px;
			left: 8%;
		}
		.next{
			left: auto;
			right: 8%;
		}
		.form-two{
			width: 250px;
			height: 250px;
			position: absolute;
			top: 80px;
			right: 15%;
			background-color: orange;
		}
		#login{
			position: absolute;
			right: 80px;
			top: 20px;
			width: 50px;
			height: 50px;
			background-color: orange;
			color: white;
			font-family: '华文行楷';
			font-size: 20px;
			border: none;
		}
		#name{
			position: relative;
			left: 70px;
			top: -10px;
		}
		#password{
			position: relative;
			left: 70px;
			top: -10px;
		}
		.remeber{
			position: relative;
			left: 70px;
		}
		.quick{
			position: relative;
			left: 30px;
			top: 10px;
		}
		.picture{
			position: relative;
			top: 20px;
		}
		.form-two img{
			width: 50px;
			height: 50px;
		}
		.charts{
			width: 200px;
			height: 240px;
			position: absolute;
			top: 80px;
			left: 15%;
			background-color: orange;
		}
		.charts ol{
			width: 200px;
			height: 240px;
		}
		
		.container-one{
			width:1500px ;
			margin-top: 50px;
		}
		.container-two{
			width: 1500px;
		}
		.container{
			width: 280px;
			height: 500px;
			margin: 10px 10px 10px 10px;
			border: 1px soild black ;
			float: left;
		}
		.container img{
			width: 280px;
			height: 280px;
		}
		.ps{
			width: 280px;
			height: 70px;
			color：white;
			margin: 10px 0 10px 0;
			border: 1px soild black ;
			text-align: center;
			line-height: 70px;
		}
		.introduce{
			color: white;
			font-size: 20px;
			font-family: '华文行楷';
		}
		.price{
			color: white;
			font-size: 28px;
			font-weight: bold;
			font-family: '华文行楷';
		}
		.copyright{
			height: 200px;
			width: 100%;
			text-align: center;
			line-height: 80px;
			position: absolute;
			top: 480%;
			background-color: black;
		}
	</style>
</head>
<body>
	<div class="header">
		<div class="logo">
			<img src="./image/logo.jpg">
		</div>
		<div class="nav clear">
			<ul class="clear">
				<li><a href="#">早餐</a></li>
				<li><a href="#">午餐</a></li>
				<li><a href="#">晚餐</a></li>
				<li><a href="#">新产品</a></li>
				<li><a href="#">畅销品</a></li>
			</ul>
		</div>
		<div class="form">
			<form>
				<input class="search" type="text" placeholder="搜索你的最爱"/>
				<input type="button" class="submit"/>
				<input type="button" name="button" value="登录" id="login"/>
			</form>
			
		</div>
	</div>
	<div class="banner">
		<ul>
			<li class="banner-one"></li>
			<li class="banner-two"></li>
			<li class="banner-three"></li>
		</ul>
		<img src="./image/prev.png" alt="上一页" class="prev">
		<img src="./image/next_wps图片.png" class="next">
		<div class="form-two" style="display: none;">
			<form>
				<p style="position: relative;top: 10px;left: 10px">用户名：</p>
				<input type="text" id="name" value="" / >
				<p id="prompt1"></p>
    			<p style="position: relative;top: 10px;left: 10px">密码：</p>
    			<input type="password" id="password" value="" />
    			<p id="prompt2"></p>
    			<input type="radio" value="choode" class="remeber" /><label class="remeber">记住登陆状态</label>
    			<br>
    			<input type="button" value="快速登陆" name="sub" class="quick" />
    			<a href="" style="color: white" class="quick" >忘记密码/账号</a>
    			<br>
    			<a href="" style="color: white" class="quick" >有问题找我</a>
    			<img src="./image/WeChat.png" class="quick picture" />
    			<img src="./image/QQ.png" class="quick picture" />
			</form>
		</div>
		
		<div class="charts">
			<h2 style="color: white;font-size: 28px;font-weight: bold;font-family: '华文行楷';">今日推荐排行榜</h2>
			<ol class="list">
				<li style="position: absolute;top: 40px;left: 15%;color: white;font-size: 20px;font-family: '华文行楷';">爆炒小龙虾</li>
				<li style="position: absolute;top: 80px;left: 15%;color: white;font-size: 20px;font-family: '华文行楷';">榴莲披萨</li>
				<li style="position: absolute;top: 120px;left: 15%;color: white;font-size: 20px;font-family: '华文行楷';">深夜麻辣烫</li>
				<li style="position: absolute;top: 160px;left: 15%;color: white;font-size: 20px;font-family: '华文行楷';">汉堡千层</li>
				<li style="position: absolute;top: 200px;left: 15%;color: white;font-size: 20px;font-family: '华文行楷';">酱汁牛排</li>
			</ol>
		</div>
		
	</div>
	<div class="container-one">
		<h1 style="color: white;font-family: '华文行楷';">推荐新品</h1>
		<div class="new clear">
			<div class="container"" style="width: 280px;height:500px">
				<img src="./image/new-one.jpg" style="width:280px;height: 280px" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">烤鸡+酱料，美味呀</p>
					<p class="price">￥138元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/new-two.jpg" style="width:280px;height: 280px"  style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">糖醋小排</p>
					<p class="price">￥98元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/new-three.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">芝士披萨</p>
					<p class="price">￥128元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/new-four.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">意大利面</p>
					<p class="price">￥66元</p>
				</div>
				
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/new-five.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">薯条牛排配</p>
					<p class="price">￥138元</p>
				</div>
			</div>
		</div>
		<h1 style="color: white;font-family: '华文行楷';">推荐畅销品</h1>
		<div class="hot clear">
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/hot-one.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">烤龙虾</p>
					<p class="price">￥198元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/hot-two.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">关东煮</p>
					<p class="price">￥78元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/hot-three.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">烤肉</p>
					<p class="price">￥328元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/hot-four.png" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">榴莲披萨</p>
					<p class="price">￥126元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/hot-five.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">千层汉堡</p>
					<p class="price">￥49元</p>
				</div>
			</div>
		</div>
	</div>
	<div class="container-two">
		<div class="morning">
			<h1 style="color: white;font-family: '华文行楷';">早餐吃得好</h1>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/morning-one.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">煎蛋健康餐</p>
					<p class="price">￥36元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/morning-two.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">素肉丸子汤</p>
					<p class="price">￥78元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/morning-three.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">豆浆油条餐</p>
					<p class="price">￥24元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/morning-four.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">全麦面包餐</p>
					<p class="price">￥42元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/morning-five.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">燕麦面包餐</p>
					<p class="price">￥56元</p>
				</div>
			</div>
		</div>
		<div class="afternoon">
			<h1 style="color: white;font-family: '华文行楷';">午餐吃得饱</h1>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/afternoon-one.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">草莓香蕉酸奶球</p>
					<p class="price">￥78元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/afternoon-two.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">草莓蛋糕杯</p>
					<p class="price">￥78元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/afernoon-three.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">芒果千层</p>
					<p class="price">￥198元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/afternoon-four.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">曲奇套餐</p>
					<p class="price">￥178元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/afternoon-five.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">巧克力奶油包</p>
					<p class="price">￥128元</p>
				</div>
			</div>
		</div>
		<div class="evening">
			<h1 style="color: white;font-family: '华文行楷';">晚餐吃得爽</h1>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/evening-three.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">“爽”虾</p>
					<p class="price">￥228元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/evening-four.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">千拼披萨</p>
					<p class="price">￥178元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/evening-five.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">烧烤汇</p>
					<p class="price">￥328元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/evening-one.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">劲爆螺蛳粉</p>
					<p class="price">￥78元</p>
				</div>
			</div>
			<div class="container" style="width: 280px;height:500px">
				<img src="./image/evening-two.jpg" style="width:280px;height: 280px"  onmouseover="bigger(this)" onmouseout="smaller(this)">
				<div class="ps">
					<p class="introduce">深夜麻辣烫</p>
					<p class="price">￥128元</p>
				</div>
			</div>
		</div>

	</div>
	<div class="copyright">
		<p style="color: white;font-style: '华文行楷'">此页面设计为张女士一人完成，版权归张女士一人所有，现仅限food工作室使用。发现抄袭者，本人将提起诉讼。客服电话：0319-123456</p>
		<img style="width: 80px;
			height: 80px;" src="./image/QQ.png">
		<img style="width: 80px;
			height: 80px;" src="./image/WeChat.png">
	</div>
	<div id="add"></div>
	<script type="text/javascript">
		//判断用户是否确定进入点餐页面，是：则进入页面；否：关闭当前页面
		var x = confirm("欢迎来到food点餐，该页面为正规链接是否选择进入？");
		if(!x){
			this.close();
		}
		//点击登录，显示登陆界面，否则隐藏;登陆完成后继续处于隐藏状态
		var login = document.getElementById("login");
		var form_two = document.getElementsByClassName("form-two")[0];
		var quick = document.getElementsByClassName("quick")[0];


		login.onclick = function(){
			form_two.style.display = '';
		}


		quick.onclick = function(){
			form_two.style.display = 'none';
		}
		//鼠标放上去图片变大
		function bigger(that){
			that.parentNode.style.width = '410px'
			that.parentNode.style.height = '410px'
			that.style.width = '400px';
			that.style.height = '400px';
		}
		function smaller(that){
			that.parentNode.style.width = '280px'
			that.parentNode.style.height = '500px'
			that.style.width = '280px';
			that.style.height = '280px';
		}
	</script>
</body>
</html>

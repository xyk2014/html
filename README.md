<!DOCTYPE html>
<html>
<head>
<meta http-equiv="content-type" content="text/html;charset=utf-8">
<title></title>
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<meta name="description" content="">
<meta name="keywords" content="keyword1,keyword2,keyword3..">
<style type="text/css">
/*
 * daviskiyerxu@qqdyw.net
 * 2014.12.12
 */
body,div,nav,section,header,span,p,h2,h3,h4,form,ul,li,textarea {
	padding: 0;
	margin: 0;
}
body {
	width: 100%;
	font: 14px/1.5 "Microsoft YaHei","Simsun",Helvetica,Arial,Verdana;
	color: #fff;
	background: #fff;
}
a {
	text-decoration: none;
	color: #fff;
}
a:hover {
	color: #ccc;
}
i {
	font-size: 0;
	line-height: 0;
}
ul,li {
	list-style: none;
}
img,input,button {
	border: none;
	outline: none;
}
input,textarea,button {
	font-family: "Microsoft YaHei","Simsun",Helvetica,Arial,Verdana;
}
.clearfix {
  zoom: 1; 
}
.clearfix:after {
  	content: "."; 
  	display: block; 
  	height: 0; 
  	clear: both; 
  	visibility: hidden;  
}
.banner {
	width: 1440px;
	height: 455px;
	margin: 0 auto;
	position: relative;	
}
.banner-top {
	position: absolute;
	z-index: 4;
	top: 0;
	height: 80px;
	width: 1440px;
	background: rgba(49,49,49,0.6);
	filter:progid:DXImageTransform.Microsoft.gradient( GradientType = 0,startColorstr = '#70000000',endColorstr = '#70000000')\9;
}
.banner-top img {
	float: left;
	display: inline;
	width: 149px;
	height: 88px;
	margin: 0 460px 0 220px;
	border-bottom: 2px solid #FFC15A;
}
.regist {
	float: left;
	margin-top: 60px;
	width: 32px;
	height: 14px;
	line-height: 14px;
	font-size: 12px;
	color: #fff;
	border-right: 1px solid #fff;
}
.landing {
	float: left;
	margin-top: 60px;
	width: 32px;
	height: 14px;
	line-height: 14px;
	font-size: 12px;
	color: #fff;
	text-indent: 8px;
}
.nav {
	height: 80px;
	width: 320px;
	margin-left: 10px;
	float: left;
}
.nav .first-a {
	padding: 17px 10px 13px 17px;
	height: 50px;
}
.nav a {
	float: left;
	display: inline;
	width: 52px;
	height: 46px;
	padding: 28px 10px 6px 17px;
	margin-right: 1px;
	font-size: 16px;
	line-height: 23px;
	background: #00CCCB;
}
.nav a:hover {
	color: #fff;
	background: #fe6768;
}
.focus {
	display: none;
}
.banner .is-focus{
	display: block;
}
.focus img {
	position: absolute;
	z-index: 1px;
	width: 1440px;
	height: 455px;
}
.content {
	width: 440px;
	position: absolute;
	top: 130px;
	left: 300px;
	z-index: 2px;
}
.content h3 {
	font-size: 75px;
	line-height: 120px;
	font-weight: 200;
}
.content p {
	width: 430px;
	padding-left: 10px;
	font-size: 16px;
	line-height: 24px;
	color: #ccc;
	border-left: 1px solid #00cccb;
}
.focus .content a {
	display: block;
	height: 25px;
	width: 84px;
	margin: 10px 0 0 345px;
	font-size: 15px;
	line-height: 25px;
	color: #666;
	text-align: center;
	background: #ffc15a;
	border-radius: 4px;
}
.wrapper {
	background: #fff;
	width: 1000px;
	margin: 0 auto;
}
.wrapper img {
	display: block;
}
.ul-title {
	margin: 30px auto 35px;
	width: 650px;
	overflow: hidden;
}
.ul-title li {
	display: inline;
	float: left;
	margin-right: 15px;
	height: 28px; 
}
.ul-title li p {
	float: left;
	font-size: 20px;
	line-height: 24px;
	color: #666;
}
.ul-title li i {
	display: inline;
	float: left;
	width: 28px;
	height: 25px;
	margin-right: 8px;
	background: url(../images/icon.jpg);
}
.ul-title .l1 p {
	display: inline;
	color: #999;
	margin-right: 20px;
}
.ul-title .l1 i {
	margin-right: 10px;
	width: 22px;
	height: 28px;
	background-position: 1px 0;
}
.ul-title .l2 i {
	background-position: -20px 0;
}
.ul-title .l3 i {
	background-position: -51px 0;
}

.ul-title .l4 i {
	background-position: -82px 0;
}
.ul-content li{
	float: left;
	width: 310px;
	border-top: 2px solid #00cccb;
	background: #e1e1d9;
	transition: all .3s ease;
}
.ul-content li:hover {
	box-shadow: 4px 4px 8px #999;
}
.ul-content li h3 {
	font-size: 30px;
	font-weight: normal;
	line-height: 60px;
	margin-left: 10px;
	color: #00cccb;
}
.ul-content li p {
	width: 268px;
	margin: 0 0 10px 10px;
	line-height: 20px;
	font-size: 12px;
	color: #666;
}
.ul-content .big-pic {
	width: 310px;
	height: 204px;
	border-bottom: 1px solid #fff;
}
.ul-content .small-pic {
	float: left;
	position: relative;
}
.ul-content .small-pic img {
	float: left;
	width: 103px;
	height: 103px;
}
.small-pic span {
	position: absolute;
	display: block;
	bottom: -40px;
	left: -10px;
}
.small-pic span {
	display: none;
}
.small-pic span i {
	width: 0;
	height: 0;
	display: block;
	margin: 0 auto;
	border-width: 0 3px 6px 3px;
	border-style: solid;
	border-color: #fe6869 transparent; 
}
.small-pic span p{
	margin: 0;
	width: 90px;
	padding: 5px 15px;
	color: #fff;
	background: #fe6869;
	border-radius: 4px;
}
.ul-content .small-pic-m img{
	border-left: 1px solid #fff;
	width: 102px;
	border-right: 1px solid #fff;
}
.ul-content .m2 {
	display: inline;
	margin: 0 35px;
	border-color: #ffbf59;
}
.ul-content .m2 h3 {
	color: #ffbf59;
}
.ul-content .m3 {
	border-color: #fe6768;
}
.ul-content .m3 h3 {
	color: #fe6768;
}
.wrap-title {
	position: relative;
	width: 100%;
	height: 61px;
	margin: 40px 0 20px;
	text-align: center;
	border-bottom: 1px solid #ccc;
}
.wrap-title h3 {
	position: absolute;
	left: 50%;
	margin-left: -80px;
	font-size: 50px;
	line-height: 60px;
	font-weight: 200;
	color: #5a5a5a;
	border-bottom: 3px solid #00cccb;
}
.shoot {
	width: 1000px;
	margin: 0 auto;
}
.shoot li {
	position: relative;
	float: left;
	display: inline;
	width: 170px;
	margin-right: 37px;
}
.shoot .last-l {
	margin-right: 2px;
}
.shoot img {
	width: 170px;
	height: 170px;
	border-radius: 50%;
}
.shoot .shoot-con {
	position: absolute;
	width: 170px;
	height: 255px;
	top: 0;
	left: 0;
	z-index: 1px;
	display: none;
}
.shoot .radius-img {
	background: url(../images/btm1.png);
	width: 130px;
	height: 30px;
	margin: -30px 0 5px 20px;
}
.shoot .radius-img p {
	color: #fff;
	font-size: 14px;
	line-height: 20px;
	text-align: center;
	padding-top: 5px;
}
.shoot .radius-img em {
	font-size: 16px;
	line-height: 20px;
	font-style: normal;
	color: #fc0;
}
.shoot span {
	display: block;
	width: 170px;
	height: 70px;
	padding: 90px 0 10px;
	font-size: 14px;
	color: #fff;
	text-align: center;
	background: rgba(0,0,0,0.6);
	border-radius: 50%;
}
.shoot p {
	text-align: center;
	font-size: 20px;
	line-height: 40px;
	color: #333;
}
.shoot .shoot-l {
 	width: 170px;
 	float: left;
}
.shoot .shoot-l i {
	float: left;
	display: inline;
	width: 45px;
	height: 45px;
	font-size: 12px;
	line-height: 45px;
	font-style: normal;
	text-align: center;
	color: #fff;
	border-radius: 50%;
	background: #fe6869;
}
.shoot .shoot-l .shoot-i2 {
	background: #ffc059;
	display: inline;
	margin: 0 18px 0 17px;
}
.shoot .shoot-l .shoot-i3 {
	background: #00cccb;
}
.shoot .shoot-l p {
	width: 170px;
	height: 40px;
	float: left;
}
.flow {
	overflow: hidden;
	margin: 0 auto;
	width: 1000px;
	padding: 20px 0 30px;
}
.flow li {
	float: left;
	width: 260px;
}
.flow i {
	float: left;
	width: 30px;
	height: 30px;
	background: url(../images/icon.jpg) -114px 1px;
}
.flow h4 {
	height: 30px;
	margin-bottom: 20px;
	font-size: 16px;
	line-height:30px;
	font-weight: normal;
	text-indent: 5px;
	color: #00cccb;
}
.flow p {
	float: left;
	width: 187px;
	color: #333;
}
.flow span {
	float: left;
	display: inline;
	margin: 4px 30px 0;
	height: 23px;
	width: 11px;
	background: url(../images/icon.jpg) -265px 0;
}
.flow .flow-l2 i {
	background-position: -151px 0;
}
.flow .flow-l3 i {
	background-position: -188px 0;
}
.flow .flow-l4  {
	width: 187px;
}
.flow .flow-l4 i {
	background-position: -225px 0;
}
.footer-wrap {
	width: 100%;
	overflow: hidden;
	background: #567371;
}
.footer {
	overflow: hidden;
	width: 1000px;
	margin: 20px auto;
}
.footer ul {
	float: left;
	display: inline;
	margin-right: 40px;
}
.footer li p {
	font-size: 14px;
	line-height: 34px;
	color: #fff;
}
.footer li a {
	color: #fff;
	font-size: 12px;
	line-height: 22px;
}
.footer li a:hover {
	color: #ccc;
}
.footer-m {
	float: left;
	margin: 0 15px 0 70px;
	padding: 10px 55px;
	width: 270px;
	border-left: 1px solid #67817f;
	border-right: 1px solid #67817f;
}
.footer-m span {
	float: left;
	margin-bottom: 20px;
}
.footer-m span i {
	display: inline;
	float: left;
	margin-right: 5px;
	width: 29px;
	height: 40px;
	background: url(../images/icon.jpg) 0 -36px;
}
.footer-m p {
	float: left;
	width: 230px;
	height: 14px;
	font-size: 12px;
	line-height: 14px;
	color: #aebebd;
}
.footer-m h3 {
	float: left;
	width: 230px;
	height: 32px;
	font-weight: normal;
	font-size: 22px;
	line-height: 32px;
	color: #fff;
}
.footer-m a {
	float: left;
	font-size: 18px;
	color: #fff;
}
.quote {
	float: left;
	width: 264px;
}
.footer-m .quote i {
	float: left;
	width: 24px;
	height: 19px;
	background: url(../images/icon.jpg) -34px -36px;
}
.footer-m .quote .quote-e {
	background-position: -58px -36px;
}
.media {
	float: left;
	margin-top: 30px;
}
.footer .media ul {
	margin: 0;
}
.media li {
	display: inline;
	float: left;
	width: 60px;
	margin-left: 20px;
	_margin-left: 15px;
}
.footer .media a {
	display: block;
	width: 55px;
	height: 45px;
	background: url(../images/icon.jpg) -92px -35px;
	opacity: 0.8;
	transition: all .3s ease;
}
.footer .media a:hover {
	opacity: 1;
}
.media p {
	font-size: 14px;
	line-height: 34px;
	color: #fff;
	text-align: center;
}
.footer .media .media-a1 {
	background-position: -152px -35px;
}
.footer .media .media-a2 {
	background-position: -207px -35px;
}
.footer .media .media-a3 {
	width: 45px;
	background-position: -254px -35px;
}

.footer-bottom {
	overflow: hidden;
	width: 100%;
	background: #00cccb;
}
.footer-bottom div {
	overflow: hidden;
	width: 1000px;
	margin: 0 auto;
}
.footer-bottom p {
	float: right;
	font-size: 14px;
	line-height: 44px;
	height: 44px;
}
</style>
<script src="js/jquery-1.11.1.min.js" type="text/javascript"></script>
</head>
<body>
<div class="banner">
	<div class="banner-top">
		<a href="#" target="_blank"><img src="images/photo.jpg" alt="享拍"></a>
		<a href="#" target="_blank" class="regist">注册</a>
		<a href="#" target="_blank" class="landing">登录</a>
		<div class="nav">
			<a href="#" target="_blank" class="first-a">新生/满月照</a>
			<a href="#" target="_blank">百天照</a>
			<a href="#" target="_blank">成长照</a>
			<a href="#" target="_blank">孕妇照</a>
		</div>
	</div>
	<div id="focus">
	<div class="focus is-focus">
		<img src="images/banner-pic1.jpg">
		<div class="content">
			<h3>新生儿照</h3>
			<p>闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 身边有一个懂你的闺蜜</p>
			<a href="#" target="_blank">服务详情</a>
		</div>
	</div>
	<div class="focus">
		<img src="images/banner-pic2.jpg">
		<div class="content">
			<h3>新生儿照</h3>
			<p>闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 身边有一个懂你的闺蜜</p>
			<a href="#" target="_blank">服务详情</a>
		</div>
	</div>
	<div class="focus">
		<img src="images/banner-pic1.jpg">
		<div class="content">
			<h3>新生儿照</h3>
			<p>闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 闺蜜就是当你被别人欺负的时候,愿意不顾一切为你挺身而出的人 身边有一个懂你的闺蜜</p>
			<a href="#" target="_blank">服务详情</a>
		</div>
	</div>
	</div>
</div>
<div class="wrapper clearfix ">
	<ul class="ul-title">
		<li class="l1"><i></i><p>预约摄影师，为您拍照！<p></li>
		<li class="l2"><i></i><p>高品质</p></li>
		<li class="l3"><i></i><p>很方便</p></li>
		<li class="l4"><i></i><p>有保障</p></li>
	</ul>
	<ul class="ul-content">
		<li class="m1">
			<h3>新生儿/百天照</h3>
			<p>一切都是那么的稚嫩，需要我们精心呵护！“约拍”精选专业“孕婴摄影师”来到您的身边。为您留下今天的时光。未来回首幸福依旧！</p>
			<a href="#" target="_blank"><img src="images/picture1.jpg" class="big-pic"></a>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic" class="small-pic-m">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
		</li>
		<li class="m2">
			<h3>新生儿/百天照</h3>
			<p>一切都是那么的稚嫩，需要我们精心呵护！“约拍”精选专业“孕婴摄影师”来到您的身边。为您留下今天的时光。未来回首幸福依旧！</p>
			<a href="#" target="_blank"><img src="images/picture2.jpg"></a>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic" class="small-pic-m">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
		</li>
		<li class="m3">
			<h3>新生儿/百天照</h3>
			<p>一切都是那么的稚嫩，需要我们精心呵护！“约拍”精选专业“孕婴摄影师”来到您的身边。为您留下今天的时光。未来回首幸福依旧！</p>
			<a href="#" target="_blank"><img src="images/picture1.jpg" class="big-pic"></a>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic" class="small-pic-m">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
			<div class="small-pic">
				<a href="#" target="_blank"><img src="images/picture1.jpg"></a>
				<span><i></i><p>来自摄影师Mr.Z</p></span>
			</div>
		</li>
	</ul>
</div>
<div class="wrap-title">
	<h3>摄影师</h3>
</div>
<div class="shoot clearfix">
	<ul>
		<li>
			<img src="images/picture2.jpg">
			<p class="this-p">摄影师周</p>
			<div class="shoot-con">
				<a href="#" target="_blank"><span>
					抓住每个童颜的感动
				</span></a>
				<div class="radius-img">
					<p>￥<em>750</em>/次</p>
				</div>
				<div class="shoot-l">
					<i>新生</i><i class="shoot-i2">孕妈</i>
					<i class="shoot-i3">百天</i>
					<a href="#" target="_blank"><p>Allen.Zhu</p></a>		
				</div>
			</div>
		</li>
		<li>
			<img src="images/picture2.jpg">
			<p class="this-p">摄影师周</p>
			<div class="shoot-con">
				<a href="#" target="_blank"><span>
					抓住每个童颜的感动
				</span></a>
				<div class="radius-img">
					<p>￥<em>750</em>/次</p>
				</div>
				<div class="shoot-l">
					<i>新生</i><i class="shoot-i2">孕妈</i><i class="shoot-i3">百天</i>
					<a href="#" target="_blank"><p>Allen.Zhu</p></a>
				</div>
			</div>
		</li>
		<li>
			<img src="images/picture2.jpg">
			<p class="this-p">摄影师周</p>
			<div class="shoot-con">
				<a href="#" target="_blank"><span>
					抓住每个童颜的感动
				</span></a>
				<div class="radius-img">
					<p>￥<em>750</em>/次</p>
				</div>
				<div class="shoot-l">
					<i>新生</i><i class="shoot-i2">孕妈</i><i class="shoot-i3">百天</i>
					<a href="#" target="_blank"><p>Allen.Zhu</p></a>
				</div>
			</div>
		</li>
		<li>
			<img src="images/picture2.jpg">
			<p class="this-p">摄影师周</p>
			<div class="shoot-con">
				<a href="#" target="_blank"><span>
					抓住每个童颜的感动
				</span></a>
				<div class="radius-img">
					<p>￥<em>750</em>/次</p>
				</div>
				<div class="shoot-l">
					<i>新生</i><i class="shoot-i2">孕妈</i><i class="shoot-i3">百天</i>
					<a href="#" target="_blank"><p>Allen.Zhu</p></a>
				</div>
			</div>			
		</li>
		<li class="last-l">
			<img src="images/picture2.jpg">
			<p class="this-p">摄影师周</p>
			<div class="shoot-con">
				<a href="#" target="_blank"><span>
					抓住每个童颜的感动
				</span></a>
				<div class="radius-img">
					<p>￥<em>750</em>/次</p>
				</div>
				<div class="shoot-l">
					<i>新生</i><i class="shoot-i2">孕妈</i><i class="shoot-i3">百天</i>
					<a href="#" target="_blank"><p>Allen.Zhu</p></a>
				</div>
			</div>
		</li>
	</ul>
</div>
<div class="wrap-title">
	<h3>服务流程</h3>
</div>
<div class="flow">
	<ul>
		<li class="flow-l1">
			<h4><i></i>预订摄影师</h4>
			<p>拍得好不好，全在摄影师。在约拍网站选择自己喜欢的摄影师，并预订其服务</p>
			<span></span>
		</li>
		<li class="flow-l2">
			<h4><i></i>预订摄影师</h4>
			<p>拍得好不好，全在摄影师。在约拍网站选择自己喜欢的摄影师，并预订其服务</p>
			<span></span>
		</li>
		<li class="flow-l3">
			<h4><i></i>预订摄影师</h4>
			<p>拍得好不好，全在摄影师。在约拍网站选择自己喜欢的摄影师，并预订其服务</p>
			<span></span>
		</li>
		<li class="flow-l4">
			<h4><i></i>预订摄影师</h4>
			<p>拍得好不好，全在摄影师。在约拍网站选择自己喜欢的摄影师，并预订其服务</p>
		</li>
	</ul>
</div>
<div class="footer-wrap">
	<div class="footer">
		<ul>
			<li><p>关于享拍</p></li>
			<li><a href="#" target="_blank">公司简介</a></li>
			<li><a href="#" target="_blank">联系我们</a></li>
			<li><a href="#" target="_blank">意见反馈</a></li>
		</ul>
		<ul>
			<li><p>用户须知</p></li>
			<li><a href="#" target="_blank">服务流程</a></li>
			<li><a href="#" target="_blank">常见问题</a></li>
			<li><a href="#" target="_blank">用户协议 </a></li>
		</ul>
		<div class="footer-m">
			<span><i></i>
			<p>周一 至 周日 9:00 - 20:00</p>
			<h3>0371-68855263</h3></span>
			<div class="quote">
				<i></i>
				<a href="#" target="_blank">
				为什么选择享拍预约摄影师
				</a>
				<i class="quote-e"></i>
			</div>
		</div>
		<div class="media">
			<ul>
				<li>
					<a href="#" target="_blank"></a>
					<p>微信</p>
				</li>
				<li>
					<a href="#" target="_blank" class="media-a1"></a>
					<p>微博</p>
				</li>
				<li>
					<a href="#" target="_blank" class="media-a2"></a>
					<p>QQ</p>
				</li>
				<li>
					<a href="#" target="_blank" class="media-a3"></a>
					<p>媒体报道 </p>
				</li>
			</ul>
		</div>
	</div>
</div>
<div class="footer-bottom">
	<div>
		<p>经营许可证编号：豫ICP证010016号</p>
	</div>
</div>
<script type="text/javascript" src="js/main.js">
</script>
</body>
</html>

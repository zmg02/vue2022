<template>
  	<div class="banner-div">
		<div class="banner">
			<ul class="pic">
				<li>
					<a href="pcindex.html"><img src="@/assets/images/mogujie/banner02.jpg" alt=""></a>
				</li>
				<li>
					<a href="pcindex.html"><img src="@/assets/images/mogujie/banner03.jpg" alt=""></a>
				</li>
			</ul>
		
			<ol>
				<li><img src="@/assets/images/mogujie/ban.png" alt=""></li>
				<li><img src="@/assets/images/mogujie/ban.png" alt=""></li>
			</ol>		
		</div>
		<aside class="right">
			<ul>
				<li>
					<span class="spa"><img src="@/assets/images/mogujie/pepole.png" alt=""></span>				
					<p>菇凉好！ 欢迎来逛蘑菇街~</p>
					<span>会员中心</span>
				</li>
				<li>
					<h5>邀请好友</h5>
					<p>共享收益分红</p>
					<img src="@/assets/images/mogujie/gift.webp" alt="">
				</li>
			</ul>
		</aside>
	</div>
</template>

<script>
export default {
	name:'MBanner'
}
</script>

<style scoped>
.banner-div{
	border-top: 2px solid #ff0077;
	 background-color:#d1bbfb; 
	 position: relative;
}
.banner{
	position: relative;
} 
.banner::after{
	content: '';
	display: block;
	clear: both;
}
.banner-div .right{
	bottom: 0px;
	right: 50%;
    position: absolute;
    margin-right: -596px;
}
.banner-div .right ul li{
	list-style: none;
	width:167px;
	text-align: center;
	background: rgba(255,255,255,0.6);
	margin: 10px;
	height: 206px;
	margin-left: 0px;
	cursor: pointer;
	margin-right: 0px;
}
.banner-div .right ul li span.spa{
	display: inline-block;
	background: #ff94c6;
	border-radius: 50%;
	border: 1px solid transparent;
	width: 70px;
	margin: 10px 0px 0px;
	line-height: 70px;
}
.banner-div .right ul li span img{
	width: 30px;
	margin-bottom: -9px;
}
.banner-div .right ul li p{
	font-size: 12px;
	margin: 10px 0px;
}
.banner-div .right ul li span:nth-of-type(2){
	font-size: 12px;
	border: 1px solid #ff5777;
	padding: 4px 12px;
	color: #ff5777;

} 
.banner-div .right ul li:nth-of-type(2){
	overflow: hidden;
}
.banner-div .right ul li:nth-of-type(2) img{
	width:122px;
}
.banner-div .right ul li h3{
	margin-top: 20px;
}
.banner-div .right ul li:nth-of-type(2) p{
	font-size: 14px;
}
.banner .pic li img{
	display: block;
	cursor: pointer;
	  margin-left: 45px;
}
/* .banner .pic li{
	display: none;
	list-style: none;
} */
.banner .pic a{
	width: 768px;
	margin-left: auto;
	margin-right: auto;
	display: block;
}
.banner .pic li:nth-of-type(1){
	 background-color:#d1bbfb; 
	display: block;
}
.banner .pic li:nth-of-type(2){
	 background-color: #8abdff; 
	 display: none;
}
.banner ol{
	position: absolute;
	bottom: 10px;
	left: 50%;
	/* margin-left: -105px; */
}
.banner ol li img{
	width: 20px;
	position: absolute;
	top: -2px;
	left: -3px;
	display: none;
/* 	display: block; */
}
.banner ol li{
	position: relative;
	float: left;
	width: 15px;
	height: 15px;
 	background: #e7e7e7; border-radius: 50%;
 	margin: 0px 4px;
 	cursor: pointer;
}
.banner ol li:nth-of-type(1) img{
	display: block;
}
.banplay{
	animation: go 3s linear 1;
}
</style>
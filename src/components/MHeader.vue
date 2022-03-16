<template>
    <header>
		<div>
			<span>
				<span></span>
				<span>vue首页</span>
			</span>
			<ul>
				<li>	
					<a href="select.html"><span class="sprite"></span> 商家后台 <span class="sprite"></span></a>
					<ol class="business">
						<li><a href="select.html">管理后台</a></li>
						<li><a href="select.html">商家社区</a></li>
						<li><a href="select.html">商家培训</a></li>
						<li><a href="select.html">市场入驻</a></li>
					</ol>
				</li>
				<li class="tw">
					<a href="select.html">客户服务 <span  class="sprite"></span></a>	
					<ol class="customer">
						<li><a href="customer.html">消费者服务</a></li>
						<li><a href="select.html">商家服务</a></li>
						<li><a href="select.html">规则中心</a></li>
					</ol>
				</li>
				<li>			
					<a  href="trolley.html"><span  class="sprite"></span> 购物车</a>
					<ol class="buy">
						<li>购物车里没有商品！</li>
					</ol>
				</li>
				<li>	
					<a  href="order.html"><span  class="sprite"></span> 我的订单</a>
					<ol class="menu">
						<li></li>
						<li></li>
						<li></li>
						<li></li>
					</ol>
				</li>
				<li class="five"><a href="login.html">登录</a></li>
			</ul> 
		</div>
	</header>
</template>

<script>
export default {
	name:'MHeader'
}
</script>

<style scoped>
header{
	background: #f2f2f2;
	border-bottom: 1px solid #dddddd;
}
header div{
	margin-right: auto;
	margin-left: auto;
	width: 1190px;
	line-height: 30px;
}
header div>span{
	float: left;
	padding-left: 20px;
}
header span span:nth-of-type(2){
	font-size: 13px;
}
header span span:nth-of-type(1){
	background: url("@/assets/images/mogujie/sprite.png");
	display: inline-block;
	width: 14px;
	height: 14px;
	background-position: -5px -243px;
	vertical-align: middle;
}
header:after{
	display: block;
	clear: both;
	content: "";
} 
header ul{
	float: right;
}
header ul>li{
	float: right;
	position: relative;
}
header li a{
	font-size:12px;
	color: #666666;
	text-decoration: none;
}
header li a{
	border-left: 1px solid #ccc;
}
header ol li a{
	border-left: none;
}
header ul>li:nth-of-type(1) a{
	padding: 0px 12px;
}
header ul>li:nth-of-type(2) a,
header ul>li:nth-of-type(3) a,
header ul>li:nth-of-type(5) a{
	padding: 0px 17px;
}
header ul>li:nth-of-type(5) a{
	border-left: none;
}
header ul>li.tw,
header ul>li.five
{
	/* padding: 10px 0px 15px; */
}
.sprite{
	background-image: url('@/assets/images/mogujie/sprite.png');
	width: 20px;
	height: 20px;
	display: inline-block;
	vertical-align: middle;
}
header ul li:nth-of-type(1) .sprite:first-child{
	background-position: -4px -573px;
}
header ul li:nth-of-type(1) .sprite:nth-child(2){
	background-position: -4px -227px;
	width: 10px;
	height: 10px;
}
header ul li:nth-of-type(2) .sprite{
	width: 10px;
	height: 10px;
	background-position: -4px -227px;
}
header ul>li:nth-of-type(4) a{
	padding: 0px 21px;
}
header ul li:nth-of-type(3) .sprite{
	background-position: -3px -427px;
}
header ul li:nth-of-type(4) .sprite{
	background-position: -3px -535px;
}
header ol{
	position: absolute;
	background: #f2f2f2; 
	text-align: center;
	left: 0px;
	top: 31px;
	display: none; 
	border: 1px solid #dddddd;
	border-bottom-left-radius: 4px;
	border-bottom-right-radius: 4px;
}
.business{
	width: 95px;  
}
header ol li{
	line-height: 30px;
}
header ol li:hover{
	background:#e4e4e4;
}
header .customer{
	text-align: left;
	width: 110px;
}
header .customer a{
	padding: 0px 20px;
}
.buy{
	width: 216px;
	color: #999999;
	left: -95px;
	font-size: 12px;
}
header .buy li{
	line-height: 53px;
}
</style>
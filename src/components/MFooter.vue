<template>
  	<footer>
		<ul>
			<li>
				<b>-新手帮助-</b>
				<ol>
					<li><a href="#">常见问题</a></li>
					<li><a href="#">自动服务</a></li>
					<li><a href="#">联系客服</a></li>
					<li><a href="#">意见反馈</a></li>
				</ol>
			</li>
			<li>
				<b>-权益保障-</b>
				<ol>
					<li>全国包邮</li>
					<li>7天无理由退货</li>
					<li>退货运费补贴</li>
					<li>限时发货</li>
				</ol>
			</li>
			<li>
				<b>-支付方式-</b>
				<ol>
					<li>微信支付</li>
					<li>支付宝</li>
					<li>白付美支付</li>
				</ol>
			</li>
			<li class="four">
				<b>-移动客户端下载-</b>
				<ol>
					<li>蘑菇街<img src="@/assets/images/mogujie/171023_3ef94c11e31g34lghgbac75k2e4fb_1000x1000.png" alt=""></li>
					<li>美丽说<img src="@/assets/images/mogujie/upload_5ii9f90fdide17hj3jkj3bfd121e3_280x280.png" alt=""></li>
					<li>uni引力<img src="@/assets/images/mogujie/upload_892b80cj47j51h95f44cai2e0b002_280x280.png" alt=""></li>
				</ol>
			</li>
		</ul>
		<div>
		<span class="spa">
			<a href="select.html">关于我们</a>
			<a href="select.html">招聘信息</a>
			<a href="select.html">联系我们</a>
			<a href="select.html">商家入驻</a>
			<a href="select.html">商家后台</a>
			<a href="select.html">蘑菇商学院</a>
			<a href="select.html">商家社区</a>
			<a href="select.html">规则中心</a>
			<a href="select.html">有害信息举报</a> <span>&copy;2018 Mogujie.com 杭州卷瓜网络有限公司</span>
		</span>
		<span class="spa2">		
			<span class="a1">营业执照：<a href="select.html" class="a1">913301065526808764</a></span>
			<span class="a1">网络文化经营许可证：<a href="select.html">浙网文（2016）0349-219号</a></span>
			<span class="a1">增值电信业务经营许可证：<a href="select.html">浙B2-20110349</a></span>
			<span class="a1"><a href="select.html" class="a1">安全责任书</a></span>
			<span class="a1"><a href="select.html" class="a1">浙公网安备 33010602002329号</a></span>
			<span class="a1"><a href="select.html" class="a1">互联网药品信息服务资格证书编号：（浙)-经营性-2018-0002</a></span>
			<span class="a1"><a href="select.html" class="a1">浙网食A33010003</a></span>
			<span class="a1"><a href="select.html" class="a1">出版物网络交易平台服务经营备案证</a></span>
			<span class="a1"><a href="select.html" class="a1">（浙）网械平台备字[2018]第00006号</a></span>
		</span>
		</div>
	</footer>
</template>

<script>
export default {
    name:'MFooter'
}
</script>

<style>
footer{
	margin: 60px auto 54px;
	width: 1200px;
}
footer ul{
	border-bottom: 2px solid #ff5777;
}
footer ul a:hover{
	color: #ff5777;
}
footer ul>li{
	float: left;
	width: 25%;
	height: 100px;
}
footer b{
	font-size: 13px;
	margin-left: 44px;
	color: #666666;
}
footer ol{
	margin-left: 20px;
	width: 200px;
	margin-top: 15px;
}
footer ul::after{
	content: '';
	display: block;
	clear: both;
}
footer ol::after{
	content: '';
	display: block;
	clear: both;
}
footer ol>li{
	float: left;
	width: 80px;
	font-size: 12px;
	 line-height: 21px;
	 color: #999999;
}
footer a{
	 font-size: 12px;
	line-height: 21px;
	text-decoration: none;
	color: #999999; 
}
footer .four li{
	width: 66px;
	position: relative;
}
footer .four img{
	position: absolute;
	width: 70px;
	height: 70px;
	top: 22px;
	left: -14px;
	display: none;
}
footer .four li:hover img{
	display: inline-block;
}
footer div{
	width: 946px;
	margin-top: 5px;
}
footer .spa a{
	font-size: 12px;
	color: #666666;
	line-height: 22px;
	display: inline-block;
	width: 80px;
	margin-right: -8px;
}
footer .spa a:hover{
	color: #ff5777;
}
footer .spa2{
	font-size: 12px;
	line-height: 28px;
	color: #999999; 
}
footer .spa2 span{
	border-right: 1px solid #999999;
	padding-right: 9px;
	padding-left: 2px;
}
footer .spa2 a{
	font-size: 12px;
	line-height: 27px;
}
footer .spa span{
	font-size: 12px;
	color: #999999; 
	line-height: 22px;
	/* float: left; */
}
footer .spa2 span:nth-of-type(1){
	padding-left: 0px;
}
.a1{
	font-family: "PingFang SC","Times New Roman","Microsoft YaHei","\5FAE\8F6F\96C5\9ED1",STXihei,"\534E\6587\7EC6\9ED1",serif;
}
</style>
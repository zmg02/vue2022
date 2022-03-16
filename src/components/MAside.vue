<template>
  	<aside class="nav">
		<div class="troley">
			<a href="trolley.html">
				<span class="nav-sprite"></span>
				<span>购物车</span>
			</a>
		</div>
		<div>
			<a href="personal.html">
				<span class="nav-sprite card"></span>
				<span>优惠券</span>
			</a>
		</div>
		<div>
			<a href="select.html">
				<span class="nav-sprite wallet"></span>
				<span>钱包</span>
			</a>
		</div>
		<div>
			<a href="select.html">
				<span class="nav-sprite foot"></span>
				<span>足迹</span>
			</a>
		</div>
		<div class="img">
			<a href="select.html">
				<span class="scan"></span>
				<img src="@/assets/images/mogujie/180521_73ibbgh52kj2dceg869h50b0bgfl6_181x200.png" alt="">
			</a>
		</div>
		<div class="top">
			<a href="select.html">
				<span class="nav-sprite"></span>
			</a>
		</div>
	</aside>
</template>

<script>
export default {
    name:'MAside'
}
</script>

<style scoped>
.nav{
	width: 30px;
	position: fixed;
	height: 100%;
	top: 0px;
	right: 0px;
	background: rgba(0, 0, 0, 0.8);
	padding-top: 60px;
	text-align: center;

}
.nav a{
	width: 22px;
	color: #fff;
	text-decoration: none;
	padding: 13px 0px;
	font-size: 12px;
	border-bottom: 1px solid #ccc;
	text-align: center;
	display: inline-block;
}
.nav div{
	cursor: pointer;
}
.nav div:hover{
	background: red;
}
.nav-sprite{
	width: 20px;
	height: 20px;
	display: inline-block;
	background: url('@/assets/images/mogujie/sprite.png');
	background-position: -272px -135px;
}
.nav img{
	position: absolute;
	top: -10px;
	left: -175px;
	display: none;
}
.nav .img:hover img{
	display: inline-block;
}
.nav .img{
	position: relative;
}
.nav .card{
	background-position: -272px -166px;
}
.nav .wallet{
	background-position: -272px -226px;
}
.nav .foot{
	background-position: -272px -194px;
}
.nav .scan{
	display: inline-block;
	background: url('@/assets/images/mogujie/180521_8d03604744igdgagjk7iggg44lkeb_16x16.png') no-repeat;
	width:16px;
	height:16px;
	background-size: 100% 100%;
}
.nav .top{
	position: absolute;
	bottom: 60px;
	right: 0px;
	width: 100%;
	background: #333;
 	display: none; 
}
.nav .top a{
	border-bottom: none;
	border-top: 1px solid #ccc;
	line-height: 44px;
	padding: 0px;
}
.nav .top .nav-sprite{
	background-position: -273px -284px;
	width: 18px;
	height: 18px;
}
@keyframes go{
	0%{
		transform: rotate(0deg);
	}
	100%{
		transform: rotate(360deg);
	}
}
</style>
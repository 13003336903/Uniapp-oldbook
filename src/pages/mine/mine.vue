<template>
	<view class="content">
		<view class="content1">
			<image src="../../static/hmlogo.png"></image>
			<text class="shuyou">书友kw969467</text>
			<text class="maijia">买家好评0|信誉0</text>
			<input type="text"/></input>
			<text class="maishu">我要卖书</text>
		</view>
		
			<view class="middle1">
				<view class="one">
					<view class="shuzi">0</view>
					<view>我的竞拍</view>
				</view>
				<view class="two">
					<view class="shuzi">2</view>
					<view>我的竞拍</view>
				</view>
				<view class="three">
					<view class="shuzi">0</view>
					<view>收藏夹</view>
				</view>
				<view class="four">
					<view class="shuzi">0</view>
					<view class="hanzi">足迹</view>
				</view>
			</view>
			<view class="middle2">
				<view class="five">
					<text class="left">我的拍卖</text>
					<text class="right">查看全部></text>
				</view>
				<image src="../../static/待付款.png"></image>
				<image src="../../static/待发货.png"></image>
				<image src="../../static/待收货.png"></image>
				<image src="../../static/待评价.png"></image>
				<image src="../../static/退货退款.png"></image>
				<image src="../../static/待确认.png"></image>
				
			</view>
		</view>

</template>

<script lang="ts">
	import {
		Component,
		Vue,
		Watch
	} from "vue-property-decorator"
	import uniBadge from "@/components/uni-ui/lib/uni-badge/uni-badge.vue";

	@Component({
		components:{
			uniBadge
		}
	})
	export default class Index extends Vue {
		
	}
</script>



<style>
		
	.content1{
		width:100%;
		height:80px;
		position: relative;
		background: D2E1FA;
	}
	image{
		width:50px;
		height:50px;
		border-radius: 50%;
		margin-top: 40px;
		margin-left: 8px;
		}
	.shuyou{
		font-size: 20px;
		color:black;
		display: inline-block;
		position: absolute;
		top:45px;
		left:68px;
		font-weight: 500;
		}
	.maijia{
		font-size: 14px;
		color:grey;
		position:absolute;
		top:78px;
		left:68px;
	}
	.content input{
		width:100px;
		height:28px;
		border-radius: 20px;
		position:absolute;
		top:58px;
		left:240px;
		border: 1px solid blue;
	}
	.maishu{
		font-size: 13px;
		position:absolute;
		top:62px;
		left:257px;
		color:blue;
	}

	.middle1{
		margin-top:40px;
		margin-left:16px;
		width:90%;
		height:50px;
		display: flex;
		justify-content: space-around;
		background: blue;
		border:1px solid grey;
		border-radius: 15px;
	}
    .shuzi{
		margin-left: 25px;
	}
	.hanzi{
		margin-left:11px;
	}
	.middle2{
		margin-top:10px;
		margin-left:16px;
		width:90%;
		height:200px;
		background: blue;
		border:1px solid grey;
		border-radius: 15px;
		position:relative;
	}
	.five{
		height:40px;
		border-bottom: 1px solid grey;
	}
	.left{
		height:40px;
		line-height:40px;
		font-size:20px;
		font-weight: 500;
		margin-left:10px;
	}
	.right{
		position:absolute;
		top:11px;
		left:215px;
	    font-size:14px;
	}
</style>

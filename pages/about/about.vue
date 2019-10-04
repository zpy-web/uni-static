<template>
	<view>
		<view class="top">
			<text>个人中心</text>
			<image src="../../static/images/8.png" mode=""></image>
		</view>
		<view class="person">
			<view class="person-b">
				<view class="person-c">
					<image src="../../static/images/9.png" style="width: 120rpx; height: 120rpx;" mode=""></image>
					<view class="person-c1">
						<view class="person-c2">
							<text>范小国</text>
							<image src="../../static/images/10.png" mode="" style="width: 46rpx; height:38rpx ;margin-left: 8rpx;"></image>
							<text>186***228</text>
						</view>
					</view>
				</view>
				<view class="person-d">
					<text>当前V1</text>
					<image src="../../static/images/11.png" mode="" style="width: 500rpx;height: 16rpx;margin: 0 10rpx;"></image>
					<text>V3</text>
				</view>
			</view>
			
		</view>
		<view class="money">
			<text>我的钱包</text>
			<text>总元宝(个)</text>
		</view>
		<view class="test">
			<view class="test-a">
				<text>我的任务</text>
				<view class="test-a1">
					<view class="test-a2">
							<image src="../../static/images/1.png" mode="" style="width: 42rpx; height: 46rpx;"></image>
							<text>发布</text>
					</view>
					<view class="test-a2">
							<image src="../../static/images/1.png" mode="" style="width: 42rpx; height: 46rpx;"></image>
							<text>发布</text>
					</view>
					<view class="test-a2">
							<image src="../../static/images/1.png" mode="" style="width: 42rpx; height: 46rpx;"></image>
							<text>发布</text>
					</view>
					<view class="test-a2">
							<image src="../../static/images/1.png" mode="" style="width: 42rpx; height: 46rpx;"></image>
							<text>发布</text>
					</view>
				</view>
				
			</view>
		</view>
		<view class="footer">
			<view class="footer-a">
				<image src="../../static/images/7.png" mode=""style="width: 45rpx;height: 45rpx;"></image>
				<text>充元宝</text>
				<text class="text">></text>
			</view>
			<view class="footer-a">
				<image src="../../static/images/7.png" mode=""style="width: 45rpx;height: 45rpx;"></image>
				<text>充元宝</text>
				<text class="text">></text>
			</view>
			<view class="footer-a">
				<image src="../../static/images/7.png" mode=""style="width: 45rpx;height: 45rpx;"></image>
				<text>充元宝</text>
				<text class="text">></text>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
.top{
	width: 100%;
	height: 94rpx;
	border-bottom: 1rpx solid #c0c0c0;
	display: flex;
	align-items: center;
	}
.top text{margin-left: 70rpx;}
.top image{width: 45rpx;height: 45rpx;margin-left: 450rpx;}
.person{width: 100%;height: 240rpx;display: flex; align-items: center;}
.person-b{width: 700rpx; height: 172rpx;margin-left: 20rpx;}
.person-c{width: 100%;height: 140rpx; display: flex;flex-wrap: nowrap;align-items: center;}
.person-c1{width: 168rpx; height: 94rpx;margin-left: 14rpx;}
.person-d{width: 100%;height: 32rpx;display: flex;flex-wrap: nowrap;align-items: center;}
.money{width: 100%;height: 220rpx;display: flex;border-bottom: 10rpx solid #f4f4f4;border-top: 10rpx solid #f4f4f4;}
.money text:first-child{margin-left: 28rpx;margin-top: 26rpx;}
.money text:nth-child(2){margin-left:350rpx;margin-top: 26rpx;}
.test{width: 100%;height: 230rpx; border-bottom: 10rpx solid #f4f4f4;display: flex;align-items: center;justify-content: center;}
.test-a{width: 656rpx; height: 152rpx;flex-wrap: wrap;}
.test-a1{display: flex;justify-content: space-around; margin-top: 28rpx;}
.test-a2{display: flex;flex-direction: column;}
.test-a2>text{margin-top: 12rpx;font-size: 26rpx;text-align: center;}
.footer{width: 100%;height: 418rpx;display: flex;flex-direction: column;}
.footer-a{flex: 1;display: flex;align-items: center; border-bottom: 1rpx solid #f4f4f4;margin-left: 30rpx;}
.footer text{margin-left: 10rpx;}
.footer .text{margin-left: 500rpx; font-size: 36rpx;}
</style>

<template>
	<view >
		<view class="top">
			<text style="margin-left: 70rpx;">{{title}}</text>
		</view>
		<view class="topbar">
			<view class="s-topbar">
				<text>发布任务</text>
				<text>接受任务</text>
			</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<uni-icons type="person" class="icon" size="26" color="blue"></uni-icons>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">抖音/快手账号</text>
					<text style="font-size: 28rpx;">1234567890</text>
				</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<text class="iconfont icon-rectangle" style="font-size: 28rpx; color: #60d2dc;"></text>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">作品标题</text>
					<text style="font-size: 28rpx;">老铁双击666啊</text>
				</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<text class="iconfont icon-dianzan" style="font-size: 28rpx; color: #ff7068;"></text>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">点赞数量</text>
					<text style="font-size: 28rpx;">5456</text>
				</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<text class="iconfont icon-renwu-" style="font-size: 28rpx; color: #f9ab3e;"></text>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">评论内容</text>
					<text style="font-size: 28rpx;">赞美，漂亮，可爱</text>
				</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<text class="iconfont icon-iconzhuanqu_huabanfuben" style="font-size: 28rpx; color: #d196ff;"></text>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">任务完成数</text>
					<text style="font-size: 28rpx;">25万</text>
				</view>
		</view>
		<view class="tap">
				<view class="tap-s">
					<text class="iconfont icon-qianbao" style="font-size: 28rpx; color: #ffb90b;"></text>
					<text style="font-size: 28rpx; margin: 0 20rpx 0 16rpx;">单次奖励金额</text>
					<text style="font-size: 28rpx;">10元宝</text>
				</view>
		</view>
		<view class="footer">
			<view class="footer-s">
				<text>发布任务</text>
			</view>
		</view>
	</view>
</template>

<script>
	import uniIcons from '../../components/uni-icons/uni-icons.vue'
	export default {
		data() {
			return {
				title: '任务中心'
			}
		},
		onLoad() {

		},
		methods: {

		},
		components:{
			uniIcons
		}
	}
</script>

<style>
.top{
	width: 100%;
	height: 96rpx;
	display: flex;
	border-bottom: 1rpx solid #c0c0c0;
	align-items: center;
}
.topbar{
	width: 100%;
	height: 112rpx;
	display: flex;
	justify-content: center;
	padding-top: 28rpx;
	box-sizing: border-box;
}
.s-topbar{
	width: 622rpx;
	height: 84rpx;
	background: #f4f4f4;
	display: flex;
	justify-content: center;
	align-items: center;
}
.s-topbar text{width: 300rpx; height: 56rpx; background-color: #fff;color: #333;text-align: center;line-height: 56rpx;}
.s-topbar text:last-child{background-color:#f4f4f4 ;}
.tap{height: 124rpx;width: 100%;display: flex;border-bottom: 1rpx solid #C0C0C0;margin-left: 30rpx;}
.tap-s{width: 620rpx; height: 40rpx; margin-top: 70rpx;display: flex;align-items: center;}
.footer{width: 100%;height: 246rpx;margin-top: 30rpx;background-color: #f4f4f4;display: flex;align-items: center;justify-content: center;}
.footer-s{width: 650rpx;height: 90rpx;background-color: #595959; border-radius:40rpx;display: flex;align-items: center;justify-content: center; color: #FFFFFF;font-size: 36rpx;}
</style>

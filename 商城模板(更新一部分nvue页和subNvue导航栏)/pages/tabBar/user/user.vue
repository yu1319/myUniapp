<template>
	<view class="userPage">
		<view class="titleBack">
			<view class="userInfo">
				<image class="touxiang" src="../../../static/img/柠檬.png"></image>
				<view class="user-name">会飞的田小甜</view>
			</view>
		</view>
		<view class="allDownborder">
			<view class="myorderOut">
				<view class="myorderIn">
					<view class="borderBottom">
						<view class="dingdan">我的订单</view>
					</view>
					<view class="borderDown">
						<view class="listBorder">
							<image class="orderImage" src="../../../static/img/fukuan.png"></image>
							<view class="listFont">待付款</view>
						</view>
						<view class="listBorder">
							<image class="orderImage" src="../../../static/img/shouhuo.png"></image>
							<view class="listFont">待收货</view>
						</view>
						<view  class="listBorder">
							<image class="orderImage" src="../../../static/img/message.png"></image>
							<view class="listFont">已完成</view>
						</view>
						<view  class="listBorder">
							<image class="orderImage" src="../../../static/img/message.png"></image>
							<view class="listFont">全部</view>
						</view>
					</view>
				</view>
			</view>
			<view class="other-choose">
				<view class="chooseborderIn">
					<view class="messageBottom">
						<view class="leftBox">
							<image class="chooseImage" src="../../../static/img/selfInfo.png"></image>
							<view class="fontInfo">个人信息</view>
						</view>			
						<view class="rightBox">></view>
					</view>
					<view class="messageBottom">
						<view class="leftBox">
							<image class="chooseImage" src="../../../static/img/myTicet.png"></image>
							<view class="fontInfo">我的优惠券</view>
						</view>
						<view class="rightBox">></view>
					</view>
					<view class="messageBottom">
						<view class="leftBox">
							<image class="chooseImage" src="../../../static/img/myPlace.png"></image>
							<view class="fontInfo">我的地址</view>
						</view>	
						<view class="rightBox">></view>
					</view>
					<view class="messageBottom">
						<view class="leftBox">
							<image class="chooseImage" src="../../../static/img/myLove.png"></image>
							<view class="fontInfo">我的收藏</view>
						</view>
						<view class="rightBox">></view>
					</view>
					<view class="messageBottom">
						<view class="leftBox">
							<image class="chooseImage" src="../../../static/img/tellUs.png"></image>
							<view class="fontInfo">联系我们</view>
						</view>
						<view class="rightBoxnum">028-888888</view>
					</view>
				</view>
			</view>
		</view>
		
	</view>
	
</template>
<script>

	
</script>
<style lang="scss">
	.userPage{
		min-height: calc(100vh - 50upx);
		// height: 100%;
		// background:rgba(246,246,246,1)
		background-color: #F6F6F6;
		z-index: -1;
	}
	.titleBack{
		width: 100%;
		height: 410upx;
		background: linear-gradient(to top,#55C37D,#FFFFFF);
		// position: absolute;
		display: flex;
		justify-content: center;
		align-items: center;
		// z-index: 1;
		.userInfo{
			display: flex;
			flex-direction: column;
			justify-content: start;
			align-items: center;
			.touxiang{
				width: 166upx;
				height: 166upx;
				
			}
		}
		.user-name{
			color: #FFFFFF;
			font-size: 34upx;
			margin-top: 30upx;
			// width: 100%;
		}
	}
	.allDownborder{
		margin-top: -25upx;
		.myorderOut{
			width: 710upx;
			height: 194upx;
			background:rgba(255,255,255,1);
			border-radius:10px;
			margin-left: 20upx;
			.myorderIn{
				.borderBottom{
					width: 647upx;
					border-bottom: 2upx solid rgba(233,233,233,1);
					margin-left: 32upx;
					.dingdan{
						font-size: 34upx;
						padding-bottom: 9upx;
						padding-top: 13upx;
					}
				}
				.borderDown{
					width: 647upx;
					display: flex;
					justify-content: space-between;
					margin-left: 30upx;
					padding-top: 14upx;
					.listBorder{
						display: flex;
						flex-direction: column;
						justify-content: start;
						align-items: center;
						.orderImage{
							width: 62upx;
							height: 62upx;
						}
						.listFont{
							font-size: 24upx;
							font-weight: bold;
							padding-top: 18upx;
						}
					}
				}
			}
		}
		.other-choose{
			width: 710upx;
			height: 660upx;
			border-radius: 20upx;
			background: rgba(255,255,255,1);
			// border: 1px solid gray;
			margin-left: 20upx;
			margin-top: 17upx;
			.chooseborderIn{
				.messageBottom{
					width: 647upx;
					border-bottom: 2upx solid rgba(233,233,233,1);
					margin-left: 32upx;
					display: flex;
					justify-content: space-between;
					// align-items: center;
					.leftBox{
						.chooseImage{
							width: 38upx;
							height: 38upx;
							margin-top: 21upx;
							// margin-bottom: 20upx;
						}
						.fontInfo{
							font-size: 28upx;
							padding-bottom: 20upx;
							// padding-top: 22upx;
							display: inline-block;
							margin-left: 19upx;
						}
					}
					.rightBox{
						// font-size: 28upx;
						width: 16upx;
						height: 30upx;
						color: #999999;
						margin-top:24upx;
						margin-right:15upx;
					}
					.rightBoxnum{
						font-size: 28upx;
						// width: 16upx;
						// height: 30upx;
						color: #656565;
						margin-top:24upx;
						margin-right:15upx;
					}
				}
			}
		}
	}
	
</style>

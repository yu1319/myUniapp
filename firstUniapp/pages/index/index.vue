<template>
	<view class="container">
		<view class="buttom-bar flex justify-around align-center">
			<view class="nab-item flex flex-column">
				<uni-icons type="eye-filled" size="25"></uni-icons>
				<text class="font">热点</text>
			</view>
			<view class="nab-item">
				<uni-icons type="shop"></uni-icons>
				<span>发现</span>
			</view>
			<view class="nab-item">
				<uni-icons type="eye-filled"></uni-icons>
			</view>
			<view class="nab-item">
				<uni-icons type="eye-filled"></uni-icons>
				热点
			</view>
			<view class="nab-item">
				<uni-icons type="eye-filled"></uni-icons>
				热点
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				editorCtx: null,
				href: 'https://uniapp.dcloud.io/component/README?id=uniui',
				strings: '<div style="text-align:center;"><img src="https://img-cdn-qiniu.dcloud.net.cn/uniapp/images/uni@2x.png"/></div>'
			}
		},
		methods: {
			onEditorReady() {
				uni.createSelectorQuery().select('#editor').context((res) => {
					this.editorCtx = res.context
				}).exec()
			},
			undo() {
				this.editorCtx.undo()
			}
		}
	}
</script>

<style>
	.buttom-bar {
		position: fixed;
		width: 100%;
		height: 100upx;
		bottom: 0;
	}
</style>

<template>
	<view class="home-wrap">
		<div class="btn-box" >
			<u-button @click="show = true">选择时间</u-button>
		</div>
		<u-picker v-model="show" mode="time"></u-picker>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				show :false
			}
		}
	}
</script>

<style lang="scss" scoped>
.home-wrap{
	.btn-box{
		width: 200rpx;
		margin: 100rpx auto;
	}
}
</style>

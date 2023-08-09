<template>
	商品详情页 <br />
	<br />
	<br />
	此页面不应该显示底部的导航栏
	<br />
	<br />
	商品id为{{ id }}
	<br />
	<br />
	底部固定显示提交订单按钮
</template>
<script setup lang="ts">
const router = useRouter()

const id = router.currentRoute.value.params.id
</script>
<style></style>
<!-- 添加自定义块 👇 -->
<route lang="json">
{
	"meta": {
		"layout": "content"
	}
}
</route>

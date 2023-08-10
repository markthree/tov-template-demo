<template>
	<router-view />
	<H5Navigation v-if="!$route.meta.disableTabbar"></H5Navigation>
</template>

<style>
.fade-enter-active,
.fade-leave-active {
	transition: opacity 0.25s ease;
}

.fade-enter-from,
.fade-leave-to {
	opacity: 0;
}
</style>

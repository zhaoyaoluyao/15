<template>
	<div>
 		<home-header/>
 		<swiper-content/>
 		<nav-content/>
 	</div>
</template>

<script>

import HeaderComponent from "./Header";
import SwiperComponent from "./Swiper";
import NavComponent from "./Nav";

export default {
	components: {
		"home-header": HeaderComponent,
		"swiper-content": SwiperComponent,
		"nav-content": NavComponent
	}
}
</script>

<style>
</style>

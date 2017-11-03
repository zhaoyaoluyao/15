<template>
  <swiper :options="swiperOption" ref="mySwiper">
    <swiper-slide>
    	<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/35/2640cab202c41b02.png" />
			</div>
			<div class="nav-ticket">动植物园</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/45/676b67d7078abc02.png" />
			</div>
			<div class="nav-ticket">故宫</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/a9/ffc620dbda9b9c02.png" />
			</div>
			<div class="nav-ticket">一日游</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/59/569d3c096e542502.png" />
			</div>
			<div class="nav-ticket">必游榜单</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/7f/b1ea3c8c7fb6db02.png" />
			</div>
			<div class="nav-ticket">秋色美</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/d0/e09575e66f4aa402.png" />
			</div>
			<div class="nav-ticket">游乐场</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/7f/b1ea3c8c7fb6db02.png" />
			</div>
			<div class="nav-ticket">泡温泉</div>
				</div>
    </swiper-slide>
    <swiper-slide>
    	<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/29/c16cd064d85d8502.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/1c/a8a8d9023a814c02.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="https://img1.qunarzz.com/piao/fusion/1602/f2/71eb19f77e3f21f7.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/cd/07f33cc087f18d02.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/ea/8cb1dce519375d02.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1707/34/9285073fde1eb702.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
		<div class="nav-icon">
			<div class="nav-img">
				<img src="http://img1.qunarzz.com/piao/fusion/1611/be/a70e61e1f57ee302.png" />
			</div>
			<div class="nav-ticket">景点门票</div>
		</div>
   </swiper-slide>
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</template>

<script>
	import { swiper, swiperSlide } from 'vue-awesome-swiper'
  export default {
    
    data() {
      return {
        swiperOption: {
//        			autoplay: 3000,
          			direction: 'horizontal',
         			autoHeight: true,
          			pagination: '.swiper-pagination',
        			observeParents: true,
        		}
      		}
  		 },
    computed: {
      swiper() {
        return this.$refs.mySwiper.swiper
      }
    },
   components: {
      		swiper,
    		swiperSlide
		}
  }
</script>
<style>
	.nav-img img{
		width: .66rem;
		height:.66rem;
		padding-top: .2rem;
	}
	.nav-icon{
		width: 25%;
		float: left;
		text-align: center;
	}
	.nav-ticket{
		padding-top: .1rem;
	}
	
</style>

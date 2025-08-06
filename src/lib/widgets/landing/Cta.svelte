<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<!-- <div class="section background-scratched"> -->
<section class="layout-grid instagram-section -my-40 px-4">
	<img
		src="images/ws_spray_ambient_v2-min.png"
		loading="lazy"
		sizes="(max-width: 767px) 100vw, 600px"
		alt=""
		class="spray-cta-top"
	/>

	<div class="layout-grid instagram-section__posts">
		<div class="layout-grid">
			<div class="h-40 w-40">
				<!-- <img
					src=""
					loading="lazy"
					alt=""
					class="instagram-section__image"
				/> -->
			</div>
			<div class="h-40 w-40">
				<!-- <img
					src=""
					loading="lazy"
					alt=""
					class="instagram-section__image"
				/> -->
			</div>
			<a href="/" target="_blank" class="instagram-section__link w-inline-block"
				><img src="images/promo/1.png" loading="lazy" alt="" class="instagram-section__image" /></a
			>
			<a href="/" target="_blank" class="instagram-section__link w-inline-block"
				><img src="images/promo/2.png" loading="lazy" alt="" class="instagram-section__image" /></a
			>
		</div>
		<a href="/app" target="_blank" class="instagram-section__link height-100 w-inline-block"
			><img
				src="images/community.svg"
				loading="lazy"
				sizes="(max-width: 767px) 90vw, 628.0034790039062px"
				alt=""
				class="instagram-section__image"
			/>
			<div class="layout-grid instagram-section__info">
				<h1 class="instagram-section__heading font-graffity">Choose your character</h1>
				<img
					src="images/ws_pinkspray_top.png"
					loading="lazy"
					sizes="(max-width: 767px) 90vw, 628.0034790039062px"
					alt=""
					class="instagram-section__image-spray position-absolute-top"
				/><img
					src="images/ws_pinkspray_bottom.png"
					loading="lazy"
					sizes="(max-width: 767px) 90vw, 628.0034790039062px"
					alt=""
					class="instagram-section__image-spray position-absolute-bottom"
				/>
				<!-- <div class="w-full"> -->
				<!-- </div> -->
				<div class="z-index-3 hidden-mobile">
					<div class="body-text--capitalised body-text--capitalised--14px">in the app</div>
				</div>
			</div>
		</a>
		<div class="layout-grid">
			<a href="/" target="_blank" class="instagram-section__link w-inline-block"
				><img src="images/promo/3.png" loading="lazy" alt="" class="instagram-section__image" /></a
			>
			<a href="/" target="_blank" class="instagram-section__link w-inline-block"
				><img src="images/promo/4.png" loading="lazy" alt="" class="instagram-section__image" /></a
			>
			<div class="flex h-40 w-40 flex-col items-center justify-center">
				<!-- <img
					src=""
					loading="lazy"
					alt=""
					class="instagram-section__image"
				/> -->
				<!-- <h2 class='text-yellow-500 text-[12rem]'>19 </h2>
				<span class="font-graffity text-lg">countries</span> -->
			</div>
			<div class="h-40 w-40">
				<!-- <img
					src=""
					loading="lazy"
					alt=""
					class="instagram-section__image"
				/> -->
			</div>
		</div>
	</div>
</section>

<style lang="postcss">
	.instagram-section {
		grid-row-gap: 30px;
		text-align: center;
		grid-template-rows: auto;
		grid-template-columns: 1fr;
		justify-items: center;
		/* padding-top: 100px;
	padding-bottom: 100px; */
	}

	.spray-cta-top {
		width: 600px;
		position: relative;
		top: 250px;
		left: -319px;
	}
	@media screen and (min-width: 991px) {
		.spray-cta-bottom {
			display: none;
		}
	}
	@media screen and (max-width: 991px) {
		.spray-cta-top {
			left: 0;
			margin-top: -200px;
			margin-bottom: -300px;
		}
	}
</style>

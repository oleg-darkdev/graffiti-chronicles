<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<section class=" product-section ">
	<!-- <div class="w-container container"> -->
	<div class="layout-grid cocktail-hero scottish-flair">
		<div style="" class="div-block-22">
			<h1 class="lg:text-[10rem] text-[4rem] lg:text-left text-center">Graffiti Chronicles  <span class="text-yellow-500">co-op boardgame</span> </h1>
		</div>
		<img
			class="cocktail-hero-bottle rotate-45"
			src="images/boardgame_box.png"
			alt=""
			loading="lazy"
		/><img
			src="images/ws_spraypaint.png"
			loading="lazy"
			sizes="(max-width: 767px) 63vw, (max-width: 1919px) 36vw, 536px"
			alt=""
			class="cocktail-hero-graffiti"
		/>
	</div>
	<!-- </div> -->
</section>

<style lang="postcss">
	.cocktail-hero.scottish-flair {
		grid-template-columns: 1.5fr 1fr;
	}
/* 			style="height:500px; width: 300px;"
 */
	.cocktail-hero-bottle {
		z-index: 2;
		width: 32%;
		position: absolute;
		top: 255px;
		right: 150px;
	}
	.cocktail-hero-graffiti {
		z-index: 1;
		width: 40%;
		position: absolute;
		bottom: -541.021px;
		right: 106px;
	}

	.cocktail-hero {
		grid-template-rows: auto;
		grid-template-columns: 1fr 1fr;
		padding-top: 200px;
		padding-bottom: 150px;
		position: relative;
	}

	.layout-grid {
		grid-row-gap: 16px;
		grid-column-gap: 16px;
		grid-template-rows: auto auto;
		grid-template-columns: 1fr 1fr;
		grid-auto-columns: 1fr;
		display: grid;
	}

	.product-section {
		/* background-color: var(--midnight-blue); */
		background-image: url(/images/spray_section_bg.png);
		background-position: 0 0;
		background-size: cover;
		overflow: visible;
	}

	@media screen and (max-width: 991px) {
		.cocktail-hero-bottle {
			top: 259px;
			bottom: 0;
			right: 0;
		}
		.cocktail-hero-graffiti {
			width: 40%;
			bottom: -96.0208px;
			right: 13px;
		}
	}
	@media screen and (max-width: 767px) {
		.cocktail-hero {
			grid-template-columns: 1fr;
			padding-bottom: 39px;
		}
		.cocktail-hero.scottish-flair {
			grid-template-columns: 1fr;
		}
		.cocktail-hero-graffiti {
			width: 70%;
			bottom: -219.021px;
			right: 70px;
		}
		.cocktail-hero-bottle {
			width: 60%;
			margin-left: auto;
			margin-right: auto;
			position: relative;
			top: 0;
			right: 0;
		}
	}
	@media screen and (max-width: 479px) {
		.product-section {
			/* background-image: url(/images/ws_spray_header_mobile.jpg); */
			background-position: 50%;
			background-size: cover;
		}
		.cocktail-hero-graffiti {
			bottom: -127.021px;
			right: 45px;
		}
	}
</style>

<script>
	import {
		StylesList,
		Hero,
		ArtistsSection,
		// VerticalSlider,
		Cta,
		ProductPreview,
		About
	} from '$widgetsLanding';

	import { PopupCard, CookiesCard } from '$entitiesLanding';
</script>

<svelte:head>
	<title>Graffity Chronicles</title>
</svelte:head>

<!-- <CookiesCard /> -->
<!-- <PopupCard /> -->
<!-- <div id="w-node-cb971ebc-79e4-1ee1-32d8-0602309b2110-41eeda21" class="div-block-10">
	<div
		id="w-node-_1224831f-1eb1-5fb0-255c-b0843090f016-41eeda21"
		class="commerce-cart-wrapper w-commerce-commercecartwrapper cart-2"
	>
		<div
			role="dialog"
			class="commerce-cart-container w-commerce-commerce cartcontainer cart-container"
		>
			<div class="w-commerce-commercecartheader cart-header">
				<div class="div-block-13">
					<h4
						class="w-commerce-commercecartheading brixton-wood-heading heading-50px text-colour-white cart"
					>
						Cart
					</h4>
					<a
						href="#"
						data-node-type="commerce-cart-close-link"
						class="w-commerce-commercecartcloselink w-inline-block"
						role="button"
						aria-label="Close cart"
					>
						<svg class="icon" width="16px" height="16px" viewBox="0 0 16 16">
							<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
								<g fill-rule="nonzero" fill="#333333">
									<polygon
										points="6.23223305 8 0.616116524 13.6161165 2.38388348 15.3838835 8 9.76776695 13.6161165 15.3838835 15.3838835 13.6161165 9.76776695 8 15.3838835 2.38388348 13.6161165 0.616116524 8 6.23223305 2.38388348 0.616116524 0.616116524 2.38388348 6.23223305 8"
									/>
								</g>
							</g>
						</svg>
					</a>
				</div>
				<h1 class="body-text--capitalised text-color-white">Free shipping on orders over £50</h1>
				<img src="images/ws_agegate.svg" loading="eager" alt="" class="image" />
			</div>
		</div>
	</div>
</div> -->
<Hero />

<About />

<ProductPreview />

<StylesList />

<Cta />
<!-- <VerticalSlider /> -->

<ArtistsSection />

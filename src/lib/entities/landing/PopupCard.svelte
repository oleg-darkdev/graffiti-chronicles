<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<section id="age-gate" style="display:block" class="section position-fixed background-darken">
	<div class="w-container container">
		<div class="div-block-4">
			<div class="layout-grid age-gate">
				<img
					src="images/ws_agegate.svg"
					loading="lazy"
					alt=""
					class="age-gate-background-spray desktop-only"
				/><img
					src="images/ws_agegate_mobile.svg"
					loading="lazy"
					alt=""
					class="age-gate-background-spray mobile-only"
				/>
				<div class="layout-grid age-gate-content">
					<div
						id="w-node-d85cacd4-5a48-0e4f-9a12-b20f78789b97-db19ddb7"
						class="font-graffity text-5xl text-white"
					>
						Lorem Ipsum jest tekstem stosowanym jako,
					</div>
					<a id="age-gate-confirm" href="#" class="round-button age-gate-confirm">Yes</a>
					<a href="#" class="round-button inverted">No</a>
				</div>
			</div>
		</div>
	</div>
</section>

<style lang="postcss">
	.round-button {
		z-index: 100;
		text-align: center;
		background-color: #0000;
		border: 2px solid #fff;
		border-radius: 50px;
		justify-content: center;
		padding-top: 12px;
		padding-left: 25px;
		padding-right: 25px;
		font-family:
			Eveleth slant,
			sans-serif;
		font-size: 12px;
		font-weight: 700;
		transition: background-color 0.2s cubic-bezier(0.455, 0.03, 0.515, 0.955);
		position: relative;
	}
	.round-button:hover {
		color: var(--deep-pink);
		background-color: #fff;
	}
	.round-button.inverted {
		color: #000;
		border-color: #000;
		transition: background-color 0.2s cubic-bezier(0.455, 0.03, 0.515, 0.955);
	}
	.round-button.inverted:hover {
		border-color: var(--midnight-blue);
		background-color: var(--midnight-blue);
		color: #fff;
	}
	.round-button.inverted.move-down-45px {
		transform: translateY(45px);
	}
	.round-button.pink {
		border-color: var(--deep-pink);
		color: var(--deep-pink);
	}
	.round-button.pink:hover {
		background-color: var(--deep-pink);
		color: #fff;
	}
	.round-button.pink.text-colour-white {
		color: #fff;
	}
	.round-button.desktop-only {
		display: block;
	}

	.div-block-4 {
		height: 100%;
	}

	.background-darken {
		background-color: #00000080;
		display: none;
	}
	.position-fixed {
		z-index: 1000;
		height: 100%;
		position: fixed;
		top: 0%;
		bottom: 0%;
		left: 0%;
		right: 0%;
	}

	.age-gate {
		width: 100%;
		height: 100%;
		grid-template-rows: auto;
		grid-template-columns: 1fr;
		align-content: center;
		justify-content: center;
		align-items: center;
		justify-items: center;
		padding-top: 199px;
		padding-bottom: 176px;
		position: relative;
		transform: translateY(152px);
	}
	.age-gate-content {
		z-index: 2;
		width: 100%;
		grid-row-gap: 40px;
		text-align: center;
		grid-template-rows: auto auto;
		grid-template-columns: 1fr;
		grid-auto-flow: column;
		align-items: stretch;
		padding-top: 0;
		padding-left: 316px;
		padding-right: 316px;
		position: relative;
		top: -110px;
	}
	.age-gate-background-spray {
		z-index: 1;
		position: absolute;
		top: auto;
		bottom: auto;
		left: 0%;
		right: 0%;
	}
	.age-gate-background-spray.desktop-only {
		display: block;
	}
	.age-gate-background-spray.mobile-only {
		display: none;
	}

	@media screen and (max-width: 991px) {
		.age-gate {
			align-items: start;
			padding-top: 0;
			transform: none;
		}
		.age-gate-content {
			align-items: center;
			padding-top: 0;
			padding-left: 110px;
			padding-right: 110px;
			position: absolute;
			top: 366px;
		}
		.age-gate-background-spray.desktop-only {
			display: none;
		}
		.age-gate-background-spray.mobile-only {
			width: 740px;
			max-width: none;
			display: block;
			position: relative;
			left: 0;
			right: 0%;
			transform: translate(52px);
		}
		.round-button.desktop-only {
			display: none;
		}
	}

	@media screen and (max-width: 767px) {
		.round-button.inverted.move-down-45px {
			transform: none;
		}
		.age-gate {
			align-content: start;
			padding-top: 0;
		}
		.age-gate-content {
			grid-row-gap: 20px;
			padding-left: 182px;
			padding-right: 182px;
			top: 97px;
		}
		.age-gate-background-spray.mobile-only {
			width: 550px;
			top: -183px;
			left: -23px;
		}
		.background-darken {
			z-index: 2000;
		}
		.position-fixed.background-darken {
			z-index: 2000;
		}
	}

	@media screen and (max-width: 479px) {
		.round-button {
			transition: none;
		}
		.round-button:hover {
			background-color: var(--deep-pink);
			color: #fff;
		}
		.round-button.inverted {
			transition: none;
		}
		.round-button.inverted:hover {
			color: var(--midnight-blue);
			background-color: #0000;
		}
		.age-gate {
			height: auto;
			align-items: center;
			padding-top: 0;
			padding-bottom: 0;
			transform: translate(0);
		}
		.age-gate-content {
			grid-row-gap: 29px;
			grid-auto-columns: 1fr;
			align-content: center;
			justify-content: center;
			align-items: center;
			justify-items: center;
			padding-top: 0;
			padding-left: 68px;
			padding-right: 68px;
			top: -26px;
			transform: translateY(-29px);
		}
		.div-block-4 {
			padding-top: 304px;
		}
		.age-gate-background-spray.mobile-only {
			width: 350px;
			left: 4px;
			transform: translate(19px) scale(1.2);
		}
	}
</style>

<script lang="ts">
	// import {  } from '$shared';
	// import {  } from '$widgets';
	// import {  } from '$entities'
</script>

<div class="set-all-components-to-display-none-and-use-this-div-to-create-a-symbol">
	<div class="fs-cc-banner_component">
		<div class="fs-cc-banner_container">
			<div class="font-bold fs-cc-banner_text">
				By clicking <strong class='text-yellow-500 font-graffity'>“Accept All Cookies”</strong>, you agree to the storing of cookies on
				your device to enhance site navigation, analyze site usage, and assist in our marketing
				efforts. View our
				<a href="/policies/privacy-policy" class="fs-cc-banner_text-link">Privacy Policy</a> for more
				information.
			</div>
			<div class="fs-cc-banner_buttons-wrapper">
				<!-- <a  href="#" class="fs-cc-banner_text-link">Preferences</a> -->
				<a  href="#" class="fs-cc-banner_button fs-cc-button-alt w-button">Deny</a>
				<a  href="#" class="fs-cc-banner_button w-button">Accept</a>
				<div  class="fs-cc-banner_close">
					<div class="fs-cc-banner_close-icon w-embed">
						<svg fill="currentColor" aria-hidden="true" focusable="false" viewBox="0 0 16 16">
							<path
								d="M9.414 8l4.293-4.293-1.414-1.414L8 6.586 3.707 2.293 2.293 3.707 6.586 8l-4.293 4.293 1.414 1.414L8 9.414l4.293 4.293 1.414-1.414L9.414 8z"
							></path>
						</svg>
					</div>
				</div>
			</div>
		</div>
		<div fs-cc="interaction" class="fs-cc-banner_trigger"></div>
	</div>
</div>

<style lang="postcss">
	.fs-cc-banner_text {
		color: #fff;
		margin-right: 160px;
	}
	.fs-cc-banner_text-link {
		color: #fff;
		border-bottom: 2px solid #fff;
		font-weight: 400;
		text-decoration: none;
	}
	.fs-cc-banner_container {
		width: 100%;
		max-width: 1440px;
		align-items: center;
		margin-left: auto;
		margin-right: auto;
		display: flex;
	}

	.set-all-components-to-display-none-and-use-this-div-to-create-a-symbol {
		z-index: 999;

		position: relative;
	}

	.fs-cc-banner_component {
		z-index: 998;
		background-color: var(--deep-pink);
		border-top: 2px solid #fff;
		padding: 24px 32px;
		/* display: none; */
		position: fixed;
		top: auto;
		bottom: 0%;
		left: 0%;
		right: 0%;
	}
	.fs-cc-banner_close {
		box-shadow: none;
		opacity: 1;
		cursor: pointer;
		border-radius: 500px;
		margin-left: 12px;
		padding: 10px;
	}
	@media screen and (max-width: 767px) {
		.fs-cc-banner_container {
			flex-direction: column;
			align-items: flex-start;
		}
		.fs-cc-banner_text-link {
			margin-right: 8px;
		}
	}
	@media screen and (max-width: 479px) {
		.fs-cc-banner_component {
			display: none;
		}
		.fs-cc-banner_text {
			margin-right: 0;
		}
	}
</style>

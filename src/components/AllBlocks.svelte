<script>
	import { searchString } from '$lib/stores/affs';
	import Footer from './Footer.svelte';
	import Header from './Header.svelte';
	import GEO from './svg/GEO.svelte';
	import Analytics from './svg/Analytics.svelte';
	import Payments from './svg/Payments.svelte';
</script>

<Header />

<section>
	<div class="content">
		<div class="content-block">
			<h1 class="heading">
				IQOPTION EUROPE&nbsp;LTD (IQ&nbsp;Option&nbsp;EU)<br />
				OFFICIAL AFFILIATE PROGRAM
			</h1>
			<p>
				Our unique platform gives you the right tools to enhance your efforts. You can focus on your
				traffic, and we'll do the rest.
			</p>
		</div>
		<div class="content-block">
			<h2 class="heading">CPA €200</h2>
			<p>💰 Industry-Leading CPA Rates</p>

			<p>Earn a flat €200 CPA per unique active trader.</p>

			<p>
				Once the trader you attracted is qualified as an active trader, you receive the CPA
				commission to your account balance. Terms and conditions apply.
			</p>
		</div>
		<div class="content-block">
			<h2 class="heading list-heading">
				WHY <span class="highlight">IQOPTION&nbsp;EU AFFILIATE</span>?
			</h2>

			<div class="list">
				<div class="item">
					<div class="icon-wrap">
						<Payments />
					</div>
					<h3 class="heading">Payments</h3>
					<p>
						We automatically transfer your earnings to your preferred online payment account twice a
						month
					</p>
				</div>
				<div class="item">
					<div class="icon-wrap">
						<GEO />
					</div>
					<h3 class="heading">Wide range of GEOs</h3>
					<p>
						18 GEOs available in Europe. We do the work of detecting your users' location, language,
						and device, and send them to the most suitable landing page
					</p>
				</div>
				<div class="item">
					<div class="icon-wrap">
						<Analytics />
					</div>
					<h3 class="heading">Clear Analytics</h3>
					<p>Analyze your results in real time using convenient reports and data filters</p>
				</div>
			</div>

			<div class="button-wrap">
				<a
					href="https://my.affstore.com/auth/signup?utm_content=lp_button&utm_source=iqoption_europe_lp&advertiser=iq_option&model=revenue&program=affiliate&source=iq_main&utm_medium=button&utm_source=main_lp{$searchString.replace(
						'?',
						'&'
					)}"
					class="button"
				>
					SIGN UP NOW
					<br />
				</a>
			</div>
		</div>
	</div>
</section>

<Footer />

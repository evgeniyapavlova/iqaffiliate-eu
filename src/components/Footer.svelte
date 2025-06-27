<script>
	import '$lib/styles/footer.scss';
	import { searchString } from '$lib/stores/affs';
</script>

<footer>
	<section>
		<div class="footer-links">
			<a href="https://my.affstore.com/terms-and-conditions{$searchString}" target="_blank">
				Terms and Conditions
			</a>
			<a href="https://my.affstore.com/privacy-policy{$searchString}" target="_blank"
				>Privacy Policy</a
			>
		</div>
	</section>
</footer>

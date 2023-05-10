<script>
	import 'uikit/dist/css/uikit.min.css'
	import 'uikit/dist/js/uikit-core'
	import 'uikit/dist/js/uikit-icons'
</script>

<div class="uk-container uk-container-expand uk-navbar-container">
	<nav class="uk-navbar" uk-navbar>
		<div class="uk-navbar-left">
			<a class="uk-navbar-item uk-logo" href="/">
				<span>HumanCron</span>
			</a>
		</div>
	</nav>
</div>
<div class="uk-container uk-container-small">
	<slot />
</div>
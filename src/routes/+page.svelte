<script lang='ts'>
	import '../styles/generator.css'
</script>

<div class='generator'>
		<div class='container'>
				<div class='radio-container'>
						<input type='radio' name='radio' id='card' checked>
						<label for='card'>Card</label>
						<input type='radio' name='radio' id='Button'>
						<label for='Button'>Button</label>
				</div>
				<div class='card'></div>
				<div class='button'></div>
		</div>
		<div class='container'>
			<div class='picker'>
					<label for='pick_color'>Pick Color</label>
					<input type='color' id='pick_color' name='pick_color' />
			</div>
			<hr />
			<div class='picker'>
					<label for='distance'>Distance</label>
					<input type='range' id='distance' name='distance' min='5' max='50' value='20'>
					<span>12</span>
			</div>

			<div class='picker'>
					<label for='intensity'>Intensity</label>
					<input type='range' id='intensity' name='intensity' min='1' max='85' value='10'>
					<span>12</span>
			</div>

			<div class='picker'>
					<label for='blur'>Blur</label>
					<input type='range' id='blur' name='blur' min='0' max='100' value='50'>
					<span>12</span>
			</div>
			<hr />
			<div class='code'>
				<pre><code><span>background: </span>#ffffff;</code>
<code><span>box-shadow: </span>16px 16px 32px #d9d9d9,
			-16px -16px 32px #ffffff;</code></pre>
			</div>
		</div>
</div>
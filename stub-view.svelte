<script>
let TestOLSKInputWrapperValue = '';

import Module from './main.svelte';
</script>

<Module OLSKInputWrapperValue={ TestOLSKInputWrapperValue } OLSKInputWrapperDispatchClear={ () => window.TestOLSKInputWrapperDispatchClear.innerHTML = parseInt(window.TestOLSKInputWrapperDispatchClear.innerHTML) + 1 }>
	<input bind:value={ TestOLSKInputWrapperValue }>
</Module>

<p>
	<strong>OLSKInputWrapperDispatchClear</strong>
	<span id="TestOLSKInputWrapperDispatchClear">0</span>
</p>

<script lang="ts">
	let count = 0;

	function sum() {
		count++;
	}

	$: double = count * 2;
</script>

<div class="container py-12 px-12">
	<button on:click={sum} class="px-2 text-white py-4 bg-slate-500 rounded">Somar {count}</button>
	<p>Aqui vai ser o dobro {double}</p>
</div>

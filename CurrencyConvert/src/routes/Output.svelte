<script>
	let { from, to, amount, exchange, hide } = $props();

</script>

<div
	class="flex h-[70vh] w-[48vw] flex-col items-center justify-center gap-8 rounded-2xl border-2 border-green-900 bg-transparent text-7xl font-bold text-white overflow-hidden"
>
	<div class="{hide ? 'flex flex-row' : 'hidden'} gap-5">
        <p>{amount}</p>
		<p class="text-5xl flex justify-center items-end font-mono">{from}</p>
	</div>
	<p class="{hide ? 'flex flex-row' : 'hidden'}">↓</p>
	<div class="{hide ? 'flex flex-row' : 'hidden'} gap-5">
        <p>{exchange}</p>
		<p class="text-5xl flex justify-center items-end font-mono">{to}</p>
	</div>
    <p class="{hide ? 'hidden' : 'flex flex-row'} text-4xl justify-center items-center text-center font-thin"> PLEASE INPUT AMOUNT AND CURRENCIES TO BE CONVERTED</p>
</div>

<script>
	import CurrencyList from './CurrencyList.svelte';
</script>
<div>
	<div class="flex flex-col gap-4">
		<input type="text" placeholder="Enter amount to be converted" class="w-[405px] h-16 rounded-2xl bg-transparent border-2 border-green-900 text-green-500 focus:border-green-500 text-xl">
		<CurrencyList />
	</div>
</div>

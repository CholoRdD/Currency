<script>
	import CurrencyList from './CurrencyList.svelte';
</script>

<!-- 
<div class=" border-2 border-green-900 w-[750px] h-56 rounded-3xl hover:border-green-600 flex flex-row overflow-hidden">
<CurrencyList />
<div class="bg-transparent border-b-2 h-12 w-[494px] border-green-700 text-white flex items-center justify-center text-xl">
RAWR
</div>
</div> -->

<div>
	<div class="flex flex-col gap-4">
		<input type="text" placeholder="Enter amount to be converted" class="w-[405px] h-16 rounded-2xl bg-transparent border-2 border-green-900 text-green-500 focus:border-green-500 text-xl">
		<CurrencyList />
	</div>
</div>

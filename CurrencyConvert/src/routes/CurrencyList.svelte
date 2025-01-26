<script>

	let apiKey = 'cfa119cbaabf69fb4a42fdc1';
	let api = `https://v6.exchangerate-api.com/v6/${apiKey}/latest/USD`;
	import { currency } from './CurrencyArray.js';
    let title = "";

function titleChange(code) {
 title = code;
};


</script>

<div>

	<div
		class="flex h-56 w-64 flex-wrap items-center justify-center gap-1
        overflow-scroll overflow-x-hidden rounded-2xl border-r-2 border-green-900 bg-transparent text-white"
	>
    {#each currency as code}
        <button class="h-10 w-full border-blue-800 hover:bg-green-600 hover:font-bold">{code}</button>

    {/each}
	</div>
</div>

<script>
	let apiKey = 'cfa119cbaabf69fb4a42fdc1';
	let api = `https://v6.exchangerate-api.com/v6/${apiKey}/latest/USD`;
	import { currency } from './CurrencyArray.js';
	let title = '';

	// function titleChange(code) {
	//  title = code;
	// };
</script>

<div class="flex flex-row gap-5">
	<div>
		<p
			class="flex h-12 w-48 flex-wrap items-center justify-center gap-1
	overflow-scroll overflow-x-hidden rounded-t-2xl border-2 border-green-900 bg-transparent text-xl font-bold text-white"
		>
			FROM
		</p>
		<div
			class="flex h-[300px] w-48 flex-wrap items-center justify-center gap-1
        overflow-scroll overflow-x-hidden rounded-b-2xl border-2 border-green-900 bg-transparent text-white"
		>
			{#each currency as code}
				<button class="h-10 w-full border-blue-800 hover:bg-green-600 hover:font-bold"
					>{code}</button
				>
			{/each}
		</div>
	</div>

	<div>
		<p
			class="flex h-12 w-48 flex-wrap items-center justify-center gap-1
	overflow-scroll overflow-x-hidden rounded-t-2xl border-2 border-green-900 bg-transparent text-xl font-bold text-white"
		>
			TO
		</p>
		<div
			class="flex h-[300px] w-48 flex-wrap items-center justify-center gap-1
        overflow-scroll overflow-x-hidden rounded-b-2xl border-2 border-green-900 bg-transparent text-white"
		>
			{#each currency as code}
				<button class="h-10 w-full border-blue-800 hover:bg-green-600 hover:font-bold"
					>{code}</button
				>
			{/each}
		</div>
	</div>
</div>

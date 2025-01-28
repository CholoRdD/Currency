<script>
	import CurrencyList from './CurrencyList.svelte';
	import Display from './Display.svelte';
	import Header from './Header.svelte';
	import Output from './Output.svelte';
	import Value from './Value.svelte';
</script>

<div class="flex min-h-screen flex-row bg-gradient-to-tr from-black to-green-900">
	<div>
		<Header />
	</div>
	<div
		class="mx-10 my-12 flex h-[85vh] w-[85vw] flex-row rounded-3xl border-2 border-green-700 bg-black bg-opacity-30 p-8"
	>
		<div class="flex flex-row gap-5">
			<Display />
			<Output />
		</div>
	</div>
</div>

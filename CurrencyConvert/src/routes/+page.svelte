<script>
	import CurrencyList from './CurrencyList.svelte';
	import Display from './Display.svelte';
	import Header from './Header.svelte';
	import Value from './Value.svelte';
</script>

<div class="flex min-h-screen flex-row bg-gradient-to-tr from-black to-green-900">
	<div class="">
		<Header />
	</div>
	<div
		class="mx-4 my-8 flex h-[90vh] w-full flex-row rounded-3xl border-2 border-green-700 bg-black bg-opacity-50 p-8"
	>
		<div class="flex flex-col gap-5">
			<Display />
			<Display />
		</div>
	</div>
</div>

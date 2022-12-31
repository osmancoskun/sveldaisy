<script>
	import Button from '$lib/Button.svelte';
</script>

<main class="h-screen w-screen flex justify-center items-center flex-col">
	<div class="pb-2 text-sm font-bold">
		<a class="opacity-20 hover:opacity-60" href="#button">#</a>
		<span class="component-preview-title">Button</span>
	</div>
	<div>
		<Button primary>qwe</Button>
		<Button secondary>qwe</Button>
		<Button accent>qwe</Button>
		<Button ghost>qwe</Button>
		<Button link>qwe</Button>
		<Button info>qwe</Button>
		<Button success>qwe</Button>
		<Button warning>qwe</Button>
		<Button error>qwe</Button>
	</div>
	<div>
		<Button outline primary>qwe</Button>
		<Button outline secondary>qwe</Button>
		<Button outline accent>qwe</Button>
		<Button outline ghost>qwe</Button>
		<Button outline link>qwe</Button>
		<Button outline info>qwe</Button>
		<Button outline success>qwe</Button>
		<Button outline warning>qwe</Button>
		<Button outline error>qwe</Button>
	</div>
	<div>
		<Button lg primary>qwe</Button>
		<Button md secondary>qwe</Button>
		<Button sm accent>qwe</Button>
		<Button xs ghost loading>qwe</Button>
	</div>
</main>

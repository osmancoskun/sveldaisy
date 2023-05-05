<script lang="ts">
	let classes: string = '';
	export { classes as class };
	export let [rounded, shadow]: any[] | boolean[] = [undefined] || [false] || [true];
</script>

<ul
	tabindex="0"
	class:rounded-box={rounded}
	class:shadow
	class="{classes} dropdown-content menu w-36"
>
	<slot />
</ul>

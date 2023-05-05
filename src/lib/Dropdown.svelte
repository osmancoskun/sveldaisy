<script lang="ts">
	let classes: string = '';
	export { classes as class };
	export let [end, top, bottom, left, right, hover, open]: boolean[] = [undefined] || [false] || [
			true
		];
</script>

<div
	class="dropdown"
	class:dropdown-end={end}
	class:dropdown-bottom={bottom}
	class:dropdown-left={left}
	class:dropdown-right={right}
	class:dropdown-hover={hover}
	class:dropdown-open={open}
	class:dropdown-top={top}
>
	<slot />
</div>

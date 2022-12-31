<script lang="ts">
	let classes: string = '';
	export { classes as class };
	export let [
		primary,
		secondary,
		accent,
		info,
		success,
		warning,
		error,
		ghost,
		link,
		outline,
		active,
		disabled,
		lg,
		md,
		sm,
		xs,
		wide,
		block,
		circle,
		square
	]: any[] | boolean[] = [undefined] || [false] || [true];
	export let [glass, loading, noAnimation]: any[] | boolean[] = [undefined] || [false] || [true];
	export let type: 'button' | 'submit' | 'reset' | null | undefined = 'button';
</script>

<button
	{...$$restProps}
	on:click
	{type}
	{disabled}
	class="btn {classes}"
	class:btn-primary={primary}
	class:btn-secondary={secondary}
	class:btn-accent={accent}
	class:btn-info={info}
	class:btn-success={success}
	class:btn-warning={warning}
	class:btn-error={error}
	class:btn-ghost={ghost}
	class:btn-link={link}
	class:btn-outline={outline}
	class:btn-active={active}
	class:btn-disabled={disabled}
	class:btn-lg={lg}
	class:btn-md={md}
	class:btn-sm={sm}
	class:btn-xs={xs}
	class:btn-wide={wide}
	class:btn-block={block}
	class:btn-circle={circle}
	class:btn-square={square}
	class:glass
	class:loading
	class:no-animation={noAnimation}
>
	<slot />
</button>

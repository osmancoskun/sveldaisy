<script lang="ts">
	let classes: string = '';
	export { classes as class };
	export let modal_id: string = '';
</script>

<input type="checkbox" id={modal_id} class=" modal-toggle {classes} " />

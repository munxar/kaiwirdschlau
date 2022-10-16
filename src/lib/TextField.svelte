<script lang="ts">
	export let value = '';
	export let disabled = false;
</script>

<input type="text" bind:value {disabled} />

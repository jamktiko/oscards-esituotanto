<script lang="ts">
	let { name, onclick }: { name: string; onclick?: () => void } = $props();
</script>

<button class="h-20 w-80 border-2 bg-slate-700" {onclick}>
	{name}
</button>

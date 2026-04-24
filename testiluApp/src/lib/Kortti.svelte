<script lang="ts">
	let { cardTitle }: { cardTitle: string } = $props();
</script>

<div class="  h-20 w-80 border-2 bg-slate-700">
	<button>
		<div>
			{cardTitle}
		</div>
	</button>
</div>

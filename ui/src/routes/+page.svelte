<script>
	import MatchStatus from '$lib/components/fieldMonitor/matchStatus.svelte';
	import TeamStatus from '$lib/components/fieldMonitor/teamStatus.svelte';
</script>

<div class="h-screen grid grid-cols-1 lg:landscape:grid-cols-2 grid-rows-[max-content_1fr_1fr] lg:landscape:grid-rows-[max-content_1fr]">
	<div class="col-span-1 lg:landscape:col-span-2">
		<MatchStatus />
	</div>

	<div class="grid">
		<div>
			<TeamStatus />
		</div>
		<div>
			<TeamStatus />
		</div>
		<div>
			<TeamStatus />
		</div>
	</div>

	<div class="grid">
		<div>
			<TeamStatus />
		</div>
		<div>
			<TeamStatus />
		</div>
		<div>
			<TeamStatus />
		</div>
	</div>
</div>

<script>
	import MatchStatus from '$lib/components/fieldMonitor/matchStatus.svelte';
	import TeamStatus from '$lib/components/fieldMonitor/teamStatus.svelte';
</script>

<div class="h-screen grid grid-cols-2 md:grid-cols-1 grid-rows-[max-content_1fr] md:grid-rows-[max-content_1fr_1fr]">
	<div class="col-span-2 md:col-span-1">
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

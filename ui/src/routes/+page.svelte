<script>
	import MatchStatus from '$lib/components/fieldMonitor/matchStatus.svelte';
	import TeamStatus from '$lib/components/fieldMonitor/teamStatus.svelte';
</script>

<div class="grid grid-rows-[auto,1fr] md:grid-col-2 h-screen">
	<div class="md:col-span-2">
		<MatchStatus />
	</div>

	<div class="grid grid-rows-3">
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

	<div class="grid grid-rows-3">
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

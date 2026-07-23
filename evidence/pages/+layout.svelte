<script>
	import '@evidence-dev/tailwind/fonts.css';
	import './app.css';
	import { EvidenceDefaultLayout } from '@evidence-dev/core-components';
	export let data;
</script>

<EvidenceDefaultLayout {data} 
	xProfile="https://www.x.com/GaganBiradar"
	blueskyProfile="https://bsky.app/profile/GaganBiradar"
	githubRepo="https://www.github.com/Gaganub/nba-monte-carlo"
	title="mdsinabox"
	builtWithEvidence=true>
	<slot slot="content" />
</EvidenceDefaultLayout>

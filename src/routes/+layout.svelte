<script>
	import { PrismicPreview } from '@prismicio/svelte/kit';
	import { repositoryName } from '$lib/prismicio';
</script>

<slot />
<PrismicPreview {repositoryName} />

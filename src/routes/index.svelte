<script>
	import { ArrowCircleUp, ArrowCircleUp_O } from "$lib";
	import Annotation from "$lib/outline/annotation.svelte";
	import Twitter from "$lib/brand/twitter.svelte";
	import Apache from "$lib/brand/apacheairflow.svelte";
</script>

<style>
	.icon {
		font-size: 40px;
		color: red;
	}
</style>

<h4>Convenience</h4>
<code>
	<pre>from "@inqling/svelte-icons"</pre>
</code>
<div class="icon"><ArrowCircleUp /></div>
<div class="icon"><ArrowCircleUp_O /></div>

<h4>Recommended</h4>

<code>
	<pre>"@inqling/svelte-icons/outline/annotation.svelte"</pre>
</code>
<div class="icon"><Annotation /></div>

<code>
	<pre>"@inqling/svelte-icons/brand/twitter.svelte"</pre>
</code>
<div class="icon"><Twitter /></div>
<div class="icon"><Apache /></div>

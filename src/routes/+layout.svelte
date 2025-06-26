<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<div class="container min-h-screen min-w-screen bg-gray-100 dark:bg-gray-900 text-gray-800 dark:text-gray-200">
	{@render children()}
</div>
<script lang="ts">
	import Icon from '@iconify/svelte';
</script>

<main class="bg-background border-primary/20  border-t-1">
	<div class=" container flex flex-col items-center justify-between gap-y-8 py-10 md:flex-row">
		<div class="flex items-center gap-2">
			<Icon icon="material-symbols:copyright" font-size="22" />
			<span class="opacity-60">Made by</span>
			<a target="_blank" href="https://github.com/xenoxsite">Xenoxsite</a>
		</div>

		<links class="flex items-center gap-8">
			<a href="https://github.com/xenoxsite" target="_blank">
				<Icon icon="mingcute:github-fill" font-size="22" />
			</a>
			<a href="https://www.linkedin.com/in/xenoxsite-re-b19246362" target="_blank">
				<Icon icon="mingcute:linkedin-fill" font-size="22" />
			</a>

			<a href="https://facebook.com/xenoxsite" target="_blank">
				<Icon icon="mingcute:facebook-fill" font-size="22" />
			</a>
		</links>
	</div>
</main>

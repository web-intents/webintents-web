<template>
	<footer class="border-t border-gray-200 dark:border-gray-800 py-12">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
			<div class="flex flex-col md:flex-row justify-between items-center gap-4">
				<div class="text-gray-600 dark:text-gray-400">
					© {{ new Date().getFullYear() }} WebIntents.net
				</div>
				<div class="flex items-center gap-6">
					<a
						href="https://mastodon.social/@webintents"
						target="_blank"
						rel="me noopener noreferrer"
						class="text-gray-600 dark:text-gray-400 hover:text-primary transition-colors"
						aria-label="Follow on Mastodon"
					>
						<Icon
							name="feather:at-sign"
							size="20"
						/>
					</a>
					<a
						href="https://github.com/web-intents/webintents-web"
						target="_blank"
						rel="noopener noreferrer"
						class="text-gray-600 dark:text-gray-400 hover:text-primary transition-colors"
						aria-label="View on GitHub"
					>
						<Icon
							name="feather:github"
							size="20"
						/>
					</a>
				</div>
			</div>
			<div class="my-8 text-center text-sm text-gray-600 dark:text-gray-400">
				<p>
					Built with ❤️ for the fediverse by <a
						href="https://pixelfed.org"
						class="text-primary font-bold hover:underline"
					>Pixelfed</a>
				</p>
				<p class="mt-2">
					Powered by <a
						href="https://fedidb.com"
						class="text-primary font-bold hover:underline"
					>FediDB</a>
				</p>
			</div>
		</div>
	</footer>
</template>

<style>
  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }

  .text-primary {
    color: #fc6076;
  }
</style>

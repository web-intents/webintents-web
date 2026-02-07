<template>
	<div>
		<section class="relative overflow-hidden">
			<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 lg:py-32">
				<div class="text-center">
					<h1 class="text-5xl lg:text-7xl font-bold text-gray-900 dark:text-white mb-6">
						The Universal<br>
						<span class="gradient-text">Follow Button</span><br>
						for the Fediverse
					</h1>
					<p class="text-xl lg:text-2xl text-gray-600 dark:text-gray-300 mb-8 max-w-3xl mx-auto">
						Make it easy for users to follow your ActivityPub account from any fediverse instance with a simple, beautiful follow button or link.
					</p>

					<div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-12">
						<div
							class="px-8 py-4 gradient-text rounded-lg font-semibold text-xl lg:text-4xl transition-colors"
						>
							Coming Soon!
						</div>
					</div>

					<div class="max-w-2xl mx-auto mt-12 p-8 bg-gray-50 dark:bg-gray-800 rounded-2xl border border-blue-100 dark:border-gray-600">
						<div class="flex items-center justify-center mb-4">
							<h3 class="text-2xl font-bold text-gray-900 dark:text-white">
								Stay Updated
							</h3>
						</div>
						<p class="text-gray-700 dark:text-gray-300 mb-6">
							Follow <a
								href="https://mastodon.social/@webintents"
								target="_blank"
								rel="me noopener noreferrer"
								class="gradient-text font-bold hover:underline"
							>@webintents@mastodon.social</a> for launch announcements, updates, and tips on integrating the follow button into your projects.
						</p>

						<a
							href="https://mastodon.social/@webintents"
							target="_blank"
							rel="me noopener noreferrer"
							class="inline-flex items-center justify-center px-8 py-4 gradient-alt-bg text-white font-semibold rounded-lg hover:opacity-90 transition-opacity shadow-lg"
						>
							<Icon
								name="feather:user-plus"
								size="20"
								class="mr-3"
							/>
							Follow on Mastodon
						</a>
					</div>
				</div>
			</div>
		</section>

		<section
			id="features"
			class="py-20 bg-gray-50 dark:bg-gray-800/50"
		>
			<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
				<div class="text-center mb-16">
					<h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
						Why WebIntents?
					</h2>
					<p class="text-xl text-gray-600 dark:text-gray-300">
						The easiest way to add follow functionality to your fediverse presence
					</p>
				</div>

				<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:zap"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Simple Integration
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Add a follow button with just a single line of code. Works with plain HTML, React, Vue, or any framework. No complex setup or configuration required.
						</p>
					</div>

					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-alt-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:globe"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Universal Support
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Works seamlessly with Mastodon, Pixelfed, Loops, Emissary, GotoSocial, Friendica, and all ActivityPub-compatible platforms across the fediverse.
						</p>
					</div>

					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:layout"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Beautiful Design
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Modern, responsive UI powered by Tailwind CSS with automatic dark mode support, smooth animations, and customizable styling to match your brand.
						</p>
					</div>

					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-alt-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:shield"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Accessible & Inclusive
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Built with accessibility in mind. WCAG 2.1 AA compliant with full keyboard navigation, screen reader support, and proper ARIA labels throughout.
						</p>
					</div>

					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:search"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Smart Autocomplete
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Powered by <a
								href="https://fedidb.com"
								class="text-primary underline font-bold"
								target="_blank"
							>FediDB's</a> comprehensive instance database. Intelligent search helps users quickly find and select their home instance from thousands across the network.
						</p>
					</div>

					<div class="bg-white dark:bg-gray-800 rounded-xl p-6 shadow-lg hover:shadow-xl transition-shadow">
						<div class="w-12 h-12 gradient-alt-bg rounded-lg flex items-center justify-center mb-4">
							<Icon
								name="feather:feather"
								size="24"
								class="text-white"
							/>
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Lightweight & Fast
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Less than 10KB minified and gzipped with zero dependencies. Lightning-fast loading with minimal performance impact on your site.
						</p>
					</div>
				</div>
			</div>
		</section>

		<section class="py-20">
			<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
				<div class="text-center mb-16">
					<h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-4">
						How It Works
					</h2>
					<p class="text-xl text-gray-600 dark:text-gray-300">
						Three simple steps to add federated follow buttons to your site
					</p>
				</div>

				<div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
					<div class="text-center">
						<div class="w-16 h-16 gradient-alt-bg rounded-full flex items-center justify-center mx-auto mb-4 text-white text-2xl font-bold">
							1
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Add the Script
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Include the WebIntents script in your HTML. One line, zero configuration.
						</p>
					</div>

					<div class="text-center">
						<div class="w-16 h-16 gradient-alt-bg rounded-full flex items-center justify-center mx-auto mb-4 text-white text-2xl font-bold">
							2
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Add the Button
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Drop in a button with your ActivityPub handle. Customize the look to match your site.
						</p>
					</div>

					<div class="text-center">
						<div class="w-16 h-16 gradient-alt-bg rounded-full flex items-center justify-center mx-auto mb-4 text-white text-2xl font-bold">
							3
						</div>
						<h3 class="text-xl font-semibold text-gray-900 dark:text-white mb-2">
							Users Follow You
						</h3>
						<p class="text-gray-600 dark:text-gray-300">
							Visitors click, enter their instance, and follow you directly from your site.
						</p>
					</div>
				</div>
			</div>
		</section>

		<section class="py-20 bg-gray-50 dark:bg-gray-800/50">
			<div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
				<h2 class="text-4xl font-bold text-gray-900 dark:text-white mb-6">
					Building for the Fediverse
				</h2>
				<p class="text-xl text-gray-600 dark:text-gray-300 mb-8">
					WebIntents is part of the broader effort to make the fediverse more accessible and user-friendly. Built with the same philosophy that powers Pixelfed, Loops, and other community-first platforms.
				</p>
				<a
					href="https://mastodon.social/@webintents"
					target="_blank"
					rel="noopener noreferrer"
					class="inline-flex items-center justify-center px-8 py-4 gradient-alt-bg text-white font-semibold rounded-lg hover:opacity-90 transition-opacity shadow-lg"
				>
					<Icon
						name="feather:user-plus"
						size="20"
						class="mr-3"
					/>
					Follow for Updates
				</a>
			</div>
		</section>
	</div>
</template>

<script setup>
useHead({
	title: 'WebIntents - Universal Follow Button for the Fediverse',
	meta: [
		{
			name: 'description',
			content: 'Make it easy for users to follow your ActivityPub account from any fediverse instance with a simple, beautiful follow button. Works with Mastodon, Pixelfed, Loops, and all ActivityPub platforms.',
		},
		{
			name: 'keywords',
			content: 'fediverse, ActivityPub, follow button, Mastodon, Pixelfed, Loops, federated social media, decentralized social network, web component',
		},
		{
			name: 'author',
			content: 'Daniel Supernault',
		},
		{
			name: 'theme-color',
			content: '#fc6076',
		},
		{
			property: 'og:title',
			content: 'WebIntents - Universal Follow Button for the Fediverse',
		},
		{
			property: 'og:description',
			content: 'Simple, beautiful follow buttons for ActivityPub. Works with Mastodon, Pixelfed, Loops, and all fediverse platforms. Less than 10KB, zero dependencies.',
		},
		{
			property: 'og:type',
			content: 'website',
		},
		{
			property: 'og:url',
			content: 'https://webintents.net',
		},
		{
			property: 'og:image',
			content: 'https://webintents.net/og-image.png',
		},
		{
			property: 'og:image:width',
			content: '1200',
		},
		{
			property: 'og:image:height',
			content: '630',
		},
		{
			name: 'twitter:card',
			content: 'summary_large_image',
		},
		{
			name: 'twitter:creator',
			content: '@dansup',
		},
		{
			name: 'twitter:title',
			content: 'WebIntents - Universal Follow Button for the Fediverse',
		},
		{
			name: 'twitter:description',
			content: 'Simple, beautiful follow buttons for ActivityPub. Works with Mastodon, Pixelfed, Loops, and all fediverse platforms.',
		},
		{
			name: 'twitter:image',
			content: 'https://webintents.net/og-image.png',
		},
		{
			name: 'fediverse:creator',
			content: '@webintents@mastodon.social',
		},
	],
	link: [
		{
			rel: 'canonical',
			href: 'https://webintents.net',
		},
		{
			rel: 'icon',
			type: 'image/x-icon',
			href: '/favicon.ico',
		},
	],
	script: [
		{
			type: 'application/ld+json',
			children: JSON.stringify({
				'@context': 'https://schema.org',
				'@type': 'SoftwareApplication',
				'name': 'WebIntents',
				'description': 'Universal follow button for the Fediverse. Simple integration for ActivityPub accounts across Mastodon, Pixelfed, Loops, and more.',
				'url': 'https://webintents.net',
				'author': {
					'@type': 'Person',
					'name': 'Daniel Supernault',
					'url': 'https://mastodon.social/@dansup',
				},
				'applicationCategory': 'DeveloperApplication',
				'operatingSystem': 'Web',
				'sameAs': [
					'https://mastodon.social/@webintents',
					'https://github.com/web-intents/webintents-web',
				],
			}),
		},
	],
});
</script>

<style>
  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }

  .text-primary {
    color: #fc6076;
  }

  .gradient-text {
    background-image: linear-gradient(-20deg, #fc6076 0%, #ff9a44 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .gradient-bg {
    background-image: linear-gradient(-20deg, #fc6076 0%, #ff9a44 100%);
  }

  .gradient-alt-bg {
    background-image: linear-gradient(30deg, #f77062 0%, #fe5196 100%);
  }
</style>

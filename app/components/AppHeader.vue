<template>
	<header class="border-b border-gray-200 dark:border-gray-800">
		<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
			<div class="flex items-center justify-between">
				<div class="flex items-center space-x-2">
					<svg
						class="w-8 h-8"
						fill="none"
						stroke="url(#gradient)"
						viewBox="0 0 24 24"
					>
						<defs>
							<linearGradient
								id="gradient"
								x1="0%"
								y1="0%"
								x2="100%"
								y2="100%"
							>
								<stop
									offset="0%"
									style="stop-color:#fc6076;stop-opacity:1"
								/>
								<stop
									offset="100%"
									style="stop-color:#ff9a44;stop-opacity:1"
								/>
							</linearGradient>
						</defs>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"
						/>
					</svg>
					<span class="text-xl font-bold text-gray-900 dark:text-white">WebIntents.net</span>
				</div>
			</div>
		</div>
	</header>
</template>

<style>
  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }

  .gradient-text {
    background-image: linear-gradient(-20deg, #fc6076 0%, #ff9a44 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
</style>

<template>
	<div class="bg-white shadow-sm sticky top-0 z-[200]">
		<div class="flex py-2 sm:py-3">
			<!-- POS Icon - Aligned with Management Sidebar (64px) -->
			<div class="w-16 flex-shrink-0 flex items-center justify-center">
				<button
					class="w-10 h-10 bg-gradient-to-br from-blue-500 to-blue-600 rounded-lg flex items-center justify-center shadow-md flex-shrink-0 hover:from-blue-600 hover:to-blue-700 active:scale-95 transition-all"
					:aria-label="'POS Next'"
					:title="__('POS Next')"
				>
					<!--	<svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
						<path
							d="M20 7h-4V4c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2zM10 4h4v3h-4V4zm10 16H4V9h16v11z"
						/>
					</svg> -->
					<svg
						xmlns="http://www.w3.org/2000/svg"
						width="1024"
						height="1024"
						viewBox="0 0 1024 1024"
					>
						<g>
							<path
								d="M 0.00 0.00 L 1024.00 0.00 L 1024.00 1024.00 L 0.00 1024.00 ZM 822.50 564.42 C826.69,565.40 847.74,564.16 853.50,562.59 C866.69,559.01 880.81,549.09 888.49,538.02 C890.02,535.81 891.66,534.00 892.14,534.00 C892.61,534.00 893.00,539.81 893.00,546.92 C893.00,554.02 893.27,560.55 893.61,561.42 C894.14,562.81 897.53,563.00 921.41,563.00 C941.22,563.00 948.93,562.67 949.80,561.80 C950.72,560.88 951.00,538.76 951.00,468.30 L 951.00 376.00 L 893.00 376.00 L 893.00 389.50 C893.00,397.00 892.59,403.00 892.09,403.00 C891.58,403.00 889.31,400.64 887.04,397.75 C874.48,381.81 857.06,373.86 834.50,373.78 C819.62,373.73 810.86,375.75 798.01,382.19 C781.77,390.34 771.17,401.91 762.70,420.71 C750.78,447.18 750.55,487.59 762.16,515.83 C771.91,539.53 791.71,557.48 813.50,562.38 C817.35,563.24 821.40,564.16 822.50,564.42 ZM 363.00 563.51 C378.21,566.56 397.08,564.46 409.67,558.32 C417.67,554.42 426.95,546.56 432.51,538.98 C434.53,536.24 436.57,534.00 437.06,534.00 C437.55,534.00 438.07,540.41 438.22,548.25 L 438.50 562.50 L 494.50 562.50 L 495.01 376.00 L 437.91 376.00 L 438.14 379.25 C438.62,386.24 437.96,404.00 437.22,404.00 C436.79,404.00 434.65,401.52 432.47,398.49 C425.58,388.93 413.78,380.62 401.50,376.67 C392.96,373.93 380.19,372.85 369.99,374.00 C325.74,379.01 298.50,415.07 298.62,468.50 C298.73,519.50 323.13,555.52 363.00,563.51 ZM 110.19 650.73 C111.80,652.67 168.88,652.17 171.26,650.20 C172.12,649.48 173.96,646.11 175.34,642.70 C179.05,633.58 192.61,601.34 219.19,538.50 C225.24,524.20 234.47,502.38 239.70,490.00 C244.93,477.62 252.27,460.30 256.01,451.50 C274.01,409.16 287.00,377.94 287.00,377.02 C287.00,376.35 276.25,376.00 255.62,376.00 L 224.24 376.00 L 223.17 378.75 C222.59,380.26 221.01,384.65 219.68,388.50 C218.34,392.35 215.42,400.45 213.19,406.50 C201.19,439.05 186.72,478.89 185.90,481.64 C185.39,483.37 184.31,485.33 183.50,486.00 C182.29,487.01 181.85,486.72 180.97,484.36 C180.38,482.79 178.73,478.58 177.31,475.00 C174.85,468.83 151.70,409.76 142.72,386.75 L 138.53 376.00 L 106.76 376.00 C89.29,376.00 75.00,376.37 75.00,376.82 C75.00,377.59 79.74,389.07 83.94,398.50 C85.75,402.55 93.99,421.28 99.99,435.00 C101.80,439.12 106.30,449.48 109.99,458.00 C113.69,466.52 117.64,475.52 118.77,478.00 C119.91,480.48 122.93,487.45 125.49,493.50 C128.05,499.55 130.75,505.85 131.49,507.50 C132.23,509.15 135.38,516.35 138.50,523.50 C141.61,530.65 145.06,538.47 146.15,540.87 C147.24,543.28 149.02,547.51 150.11,550.27 L 152.08 555.29 L 138.41 585.39 C124.86,615.22 120.55,624.62 112.97,640.93 C109.93,647.46 109.31,649.66 110.19,650.73 ZM 536.68 562.35 C537.06,562.72 549.77,562.91 564.93,562.77 L 592.50 562.50 L 593.07 507.50 C593.69,449.07 593.76,448.18 598.76,438.50 C605.19,426.07 620.95,419.21 637.01,421.86 C640.95,422.52 645.90,423.93 648.02,425.01 C654.37,428.25 661.23,436.04 664.00,443.14 L 666.48 449.50 L 667.50 562.50 L 694.38 562.77 C713.37,562.95 721.66,562.70 722.63,561.89 C724.65,560.21 724.63,445.37 722.60,433.00 C716.64,396.67 690.56,374.00 654.73,374.00 C631.40,374.00 613.80,381.74 600.12,398.00 C597.11,401.58 594.28,404.65 593.83,404.83 C593.37,405.02 593.00,398.60 593.00,390.58 L 593.00 376.00 L 536.00 376.00 L 536.00 468.83 C536.00,519.89 536.31,561.97 536.68,562.35 ZM 869.64 510.47 C862.73,513.79 861.69,514.00 852.40,513.98 C844.24,513.96 841.46,513.52 836.59,511.52 C829.01,508.41 824.40,504.68 819.88,498.01 C814.96,490.75 812.86,483.45 812.25,471.54 C810.86,444.01 824.34,426.28 848.20,424.28 C856.04,423.62 865.50,425.26 871.36,428.28 C877.89,431.66 885.73,440.16 889.31,447.75 C892.43,454.37 892.49,454.77 892.48,469.00 C892.47,482.46 892.29,483.89 889.90,489.00 C888.49,492.02 885.00,497.30 882.16,500.72 C878.06,505.64 875.45,507.67 869.64,510.47 ZM 412.04 511.56 C407.15,513.55 404.32,514.00 396.77,513.98 C381.84,513.94 372.37,509.08 364.47,497.43 C352.31,479.47 355.17,447.03 370.10,433.60 C377.48,426.97 384.26,424.64 396.50,424.57 C411.62,424.47 420.03,428.16 428.60,438.67 C435.01,446.54 437.26,453.41 437.78,466.72 C438.14,476.11 437.87,479.06 436.11,484.86 C432.53,496.65 423.16,507.04 412.04,511.56 Z"
								fill="rgb(1,90,186)"
							/>
							<path
								d="M 110.19 650.73 C109.31,649.66 109.93,647.46 112.97,640.93 C120.55,624.62 124.86,615.22 138.41,585.39 L 152.08 555.29 L 150.11 550.27 C149.02,547.51 147.24,543.28 146.15,540.87 C145.06,538.47 141.61,530.65 138.50,523.50 C135.38,516.35 132.23,509.15 131.49,507.50 C130.75,505.85 128.05,499.55 125.49,493.50 C122.93,487.45 119.91,480.48 118.77,478.00 C117.64,475.52 113.69,466.52 109.99,458.00 C106.30,449.48 101.80,439.12 99.99,435.00 C93.99,421.28 85.75,402.55 83.94,398.50 C79.74,389.07 75.00,377.59 75.00,376.82 C75.00,376.37 89.29,376.00 106.76,376.00 L 138.53 376.00 L 142.72 386.75 C151.70,409.76 174.85,468.83 177.31,475.00 C178.73,478.58 180.38,482.79 180.97,484.36 C181.85,486.72 182.29,487.01 183.50,486.00 C184.31,485.33 185.39,483.37 185.90,481.64 C186.72,478.89 201.19,439.05 213.19,406.50 C215.42,400.45 218.34,392.35 219.68,388.50 C221.01,384.65 222.59,380.26 223.17,378.75 L 224.24 376.00 L 255.62 376.00 C276.25,376.00 287.00,376.35 287.00,377.02 C287.00,377.94 274.01,409.16 256.01,451.50 C252.27,460.30 244.93,477.62 239.70,490.00 C234.47,502.38 225.24,524.20 219.19,538.50 C192.61,601.34 179.05,633.58 175.34,642.70 C173.96,646.11 172.12,649.48 171.26,650.20 C168.88,652.17 111.80,652.67 110.19,650.73 ZM 363.00 563.51 C323.13,555.52 298.73,519.50 298.62,468.50 C298.50,415.07 325.74,379.01 369.99,374.00 C380.19,372.85 392.96,373.93 401.50,376.67 C413.78,380.62 425.58,388.93 432.47,398.49 C434.65,401.52 436.79,404.00 437.22,404.00 C437.96,404.00 438.62,386.24 438.14,379.25 L 437.91 376.00 L 466.46 376.00 L 495.01 376.00 L 494.76 469.25 L 494.50 562.50 L 466.50 562.50 L 438.50 562.50 L 438.22 548.25 C438.07,540.41 437.55,534.00 437.06,534.00 C436.57,534.00 434.53,536.24 432.51,538.98 C426.95,546.56 417.67,554.42 409.67,558.32 C397.08,564.46 378.21,566.56 363.00,563.51 ZM 412.04 511.56 C423.16,507.04 432.53,496.65 436.11,484.86 C437.87,479.06 438.14,476.11 437.78,466.72 C437.26,453.41 435.01,446.54 428.60,438.67 C420.03,428.16 411.62,424.47 396.50,424.57 C384.26,424.64 377.48,426.97 370.10,433.60 C355.17,447.03 352.31,479.47 364.47,497.43 C372.37,509.08 381.84,513.94 396.77,513.98 C404.32,514.00 407.15,513.55 412.04,511.56 ZM 822.50 564.42 C821.40,564.16 817.35,563.24 813.50,562.38 C791.71,557.48 771.91,539.53 762.16,515.83 C750.55,487.59 750.78,447.18 762.70,420.71 C771.17,401.91 781.77,390.34 798.01,382.19 C810.86,375.75 819.62,373.73 834.50,373.78 C857.06,373.86 874.48,381.81 887.04,397.75 C889.31,400.64 891.58,403.00 892.09,403.00 C892.59,403.00 893.00,397.00 893.00,389.50 L 893.00 376.00 L 922.00 376.00 L 951.00 376.00 L 951.00 468.30 C951.00,538.76 950.72,560.88 949.80,561.80 C948.93,562.67 941.22,563.00 921.41,563.00 C897.53,563.00 894.14,562.81 893.61,561.42 C893.27,560.55 893.00,554.02 893.00,546.92 C893.00,539.81 892.61,534.00 892.14,534.00 C891.66,534.00 890.02,535.81 888.49,538.02 C880.81,549.09 866.69,559.01 853.50,562.59 C847.74,564.16 826.69,565.40 822.50,564.42 ZM 869.64 510.47 C875.45,507.67 878.06,505.64 882.16,500.72 C885.00,497.30 888.49,492.02 889.90,489.00 C892.29,483.89 892.47,482.46 892.48,469.00 C892.49,454.77 892.43,454.37 889.31,447.75 C885.73,440.16 877.89,431.66 871.36,428.28 C865.50,425.26 856.04,423.62 848.20,424.28 C824.34,426.28 810.86,444.01 812.25,471.54 C812.86,483.45 814.96,490.75 819.88,498.01 C824.40,504.68 829.01,508.41 836.59,511.52 C841.46,513.52 844.24,513.96 852.40,513.98 C861.69,514.00 862.73,513.79 869.64,510.47 ZM 536.68 562.35 C536.31,561.97 536.00,519.89 536.00,468.83 L 536.00 376.00 L 564.50 376.00 L 593.00 376.00 L 593.00 390.58 C593.00,398.60 593.37,405.02 593.83,404.83 C594.28,404.65 597.11,401.58 600.12,398.00 C613.80,381.74 631.40,374.00 654.73,374.00 C690.56,374.00 716.64,396.67 722.60,433.00 C724.63,445.37 724.65,560.21 722.63,561.89 C721.66,562.70 713.37,562.95 694.38,562.77 L 667.50 562.50 L 666.99 506.00 L 666.48 449.50 L 664.00 443.14 C661.23,436.04 654.37,428.25 648.02,425.01 C645.90,423.93 640.95,422.52 637.01,421.86 C620.95,419.21 605.19,426.07 598.76,438.50 C593.76,448.18 593.69,449.07 593.07,507.50 L 592.50 562.50 L 564.93 562.77 C549.77,562.91 537.06,562.72 536.68,562.35 Z"
								fill="rgb(253,213,2)"
							/>
						</g>
					</svg>
				</button>
			</div>

			<!-- Main Header Content -->
			<div
				class="flex-1 flex justify-between items-center gap-1 sm:gap-2 px-2 sm:px-4 md:px-6"
			>
				<!-- Left Side: Brand Info -->
				<div class="flex items-center gap-1 sm:gap-4 min-w-0 flex-1 overflow-hidden">
					<div class="min-w-0 flex-shrink overflow-hidden">
						<div class="flex items-center gap-1 sm:gap-2">
							<h1
								class="text-xs sm:text-base font-bold text-gray-900 truncate flex-shrink"
							>
								{{ "Yana POS" }}
							</h1>
							<!--	<span
								class="hidden sm:inline-flex relative items-center px-1 sm:px-2 py-0.5 text-[8px] sm:text-[10px] font-bold bg-gradient-to-r from-blue-500 to-blue-600 text-white rounded-md shadow-sm hover:shadow-md transition-shadow flex-shrink-0"
							>
								<span
									class="absolute inset-0 bg-white/20 rounded-md animate-pulse"
								></span>
								<span class="relative">v{{ appVersion }}</span>
							</span> -->
						</div>
						<p
							v-if="profileName"
							class="text-[9px] sm:text-xs text-gray-500 truncate hidden sm:block mt-0.5"
						>
							{{ profileName }}
						</p>
					</div>

					<!-- Time and Shift Duration - Compact on mobile -->
					<div class="hidden lg:flex items-center gap-4 ms-6 flex-shrink-0">
						<!-- Current Time -->
						<StatusBadge
							variant="blue"
							size="sm"
							:icon="timeIcon"
							:text="currentTime"
						/>

						<!-- Shift Duration -->
						<StatusBadge
							v-if="hasOpenShift && shiftDuration"
							variant="green"
							size="xs"
							:icon="shiftIcon"
							:label="__('Shift Open:')"
							:value="shiftDuration"
						/>
					</div>

					<!-- Mobile Time Display - Very compact -->
					<div
						class="flex lg:hidden items-center text-[10px] text-gray-600 font-medium flex-shrink-0 ms-1"
					>
						<span class="hidden xs:inline whitespace-nowrap">{{ currentTime }}</span>
					</div>
				</div>

				<!-- Right Side: Controls -->
				<div class="flex items-center gap-0.5 sm:gap-1 md:gap-2 flex-shrink-0">
					<!-- WiFi/Offline Status -->
					<button
						@click="$emit('sync-click')"
						:class="[
							'p-1.5 sm:p-2 hover:bg-gray-100 active:bg-gray-200 rounded-lg transition-colors relative group touch-manipulation',
							isSyncing ? 'animate-pulse' : '',
						]"
						:title="
							isOffline
								? __('Offline ({0} pending)', [pendingInvoicesCount])
								: __('Online - Click to sync')
						"
						:aria-label="
							isOffline ? __('Offline mode active') : __('Online mode active')
						"
					>
						<svg
							v-if="!isOffline"
							class="w-4 h-4 sm:w-5 sm:h-5 text-green-600"
							fill="currentColor"
							viewBox="0 0 24 24"
						>
							<path
								d="M1 9l2 2c4.97-4.97 13.03-4.97 18 0l2-2C16.93 2.93 7.08 2.93 1 9zm8 8l3 3 3-3c-1.65-1.66-4.34-1.66-6 0zm-4-4l2 2c2.76-2.76 7.24-2.76 10 0l2-2C15.14 9.14 8.87 9.14 5 13z"
							/>
						</svg>
						<svg
							v-else
							class="w-4 h-4 sm:w-5 sm:h-5 text-orange-600"
							fill="none"
							stroke="currentColor"
							viewBox="0 0 24 24"
						>
							<path
								stroke-linecap="round"
								stroke-linejoin="round"
								stroke-width="2"
								d="M18.364 5.636a9 9 0 010 12.728m0 0l-2.829-2.829m2.829 2.829L21 21M15.536 8.464a5 5 0 010 7.072m0 0l-2.829-2.829m-4.243 2.829a4.978 4.978 0 01-1.414-2.83m-1.414 5.658a9 9 0 01-2.167-9.238m7.824 2.167a1 1 0 111.414 1.414m-1.414-1.414L3 3m8.293 8.293l1.414 1.414"
							/>
						</svg>
						<span
							v-if="pendingInvoicesCount > 0"
							class="absolute -top-1 -end-1 bg-orange-600 text-white text-[10px] font-bold rounded-full w-5 h-5 flex items-center justify-center shadow-md"
						>
							{{ pendingInvoicesCount }}
						</span>
					</button>

					<!-- Cache Status Indicator -->
					<div class="relative">
						<button
							@click="showCacheTooltip = !showCacheTooltip"
							@blur="handleBlur"
							class="p-1.5 sm:p-2 hover:bg-gray-100 active:bg-gray-200 rounded-lg transition-colors relative touch-manipulation"
							:aria-label="getCacheAriaLabel()"
						>
							<svg
								class="w-4 h-4 sm:w-5 sm:h-5 transition-colors"
								:class="getCacheIconColor()"
								fill="currentColor"
								viewBox="0 0 24 24"
							>
								<path
									d="M12 2C8.13 2 5 3.12 5 4.5V7c0 1.38 3.13 2.5 7 2.5S19 8.38 19 7V4.5C19 3.12 15.87 2 12 2zM5 9v3c0 1.38 3.13 2.5 7 2.5s7-1.12 7-2.5V9c0 1.38-3.13 2.5-7 2.5S5 10.38 5 9zm0 5v3c0 1.38 3.13 2.5 7 2.5s7-1.12 7-2.5v-3c0 1.38-3.13 2.5-7 2.5S5 15.38 5 14z"
								/>
							</svg>
							<svg
								v-if="cacheSyncing || isRefreshing"
								class="w-4 h-4 sm:w-5 sm:h-5 absolute top-2 start-2 animate-spin opacity-70"
								fill="none"
								stroke="currentColor"
								viewBox="0 0 24 24"
								:class="getCacheIconColor()"
							>
								<circle
									class="opacity-25"
									cx="12"
									cy="12"
									r="10"
									stroke="currentColor"
									stroke-width="4"
								></circle>
								<path
									class="opacity-75"
									fill="currentColor"
									d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4z"
								></path>
							</svg>
							<!-- Sync progress badge (visible during sync) -->
							<span
								v-if="cacheSyncing && cacheStats?.items > 0"
								class="absolute -bottom-1 -end-1 bg-orange-500 text-white text-[8px] font-bold rounded-full px-1 min-w-[20px] h-4 flex items-center justify-center shadow-md animate-pulse"
								:title="__('Syncing: {0} items', [formatNumber(cacheStats.items)])"
							>
								{{ formatCompactNumber(cacheStats.items) }}
							</span>
						</button>

						<!-- Tooltip -->
						<div
							v-if="showCacheTooltip"
							@mousedown.prevent
							class="absolute top-full mt-2 z-[999] w-[90vw] max-w-[240px] sm:max-w-[260px]"
							:style="{ left: '50%', transform: 'translateX(-50%)' }"
						>
							<div
								class="bg-gray-900 text-white text-xs rounded-lg shadow-xl py-2 px-2.5 sm:px-3"
							>
								<!-- Arrow -->
								<div class="absolute bottom-full mb-px left-1/2 -translate-x-1/2">
									<div
										class="border-[5px] sm:border-4 border-transparent border-b-gray-900"
									></div>
								</div>

								<!-- Header -->
								<div
									class="flex items-center justify-between mb-1.5 sm:mb-2 pb-1.5 sm:pb-2 border-b border-gray-700"
								>
									<span class="font-semibold text-[11px] sm:text-xs">{{
										__("Cache")
									}}</span>
									<span
										class="px-1.5 sm:px-2 py-0.5 rounded text-[9px] sm:text-[10px] font-bold uppercase"
										:class="getCacheStatusBadgeClass()"
									>
										{{ getCacheStatus() }}
									</span>
								</div>

								<!-- Sync Progress Banner (shown during sync) -->
								<div
									v-if="cacheSyncing"
									class="mb-2 p-2 bg-orange-500/20 rounded-lg"
								>
									<div class="flex items-center gap-2 mb-1.5">
										<svg
											class="w-4 h-4 animate-spin text-orange-400"
											fill="none"
											viewBox="0 0 24 24"
										>
											<circle
												class="opacity-25"
												cx="12"
												cy="12"
												r="10"
												stroke="currentColor"
												stroke-width="4"
											></circle>
											<path
												class="opacity-75"
												fill="currentColor"
												d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4z"
											></path>
										</svg>
										<span class="text-orange-300 font-semibold text-[11px]">{{
											__("Syncing for offline...")
										}}</span>
									</div>
									<div class="text-center">
										<span class="text-white font-bold text-lg">{{
											formatNumber(cacheStats?.items || 0)
										}}</span>
										<span class="text-gray-400 text-[10px] ms-1">{{
											__("items cached")
										}}</span>
									</div>
									<div class="mt-1.5 text-[9px] text-gray-400 text-center">
										{{ __("Barcode scanning works for cached items") }}
									</div>
								</div>

								<!-- Stats -->
								<div class="flex flex-col gap-1 sm:gap-1.5 text-[10px] sm:text-xs">
									<div class="flex items-center justify-between">
										<span class="text-gray-400">{{ __("Items:") }}</span>
										<span class="font-semibold">{{
											formatNumber(cacheStats?.items || 0)
										}}</span>
									</div>
									<div
										v-if="cacheStats?.lastSync"
										class="flex items-center justify-between"
									>
										<span class="text-gray-400">{{ __("Last Sync:") }}</span>
										<span class="font-semibold text-[9px] sm:text-[10px]">{{
											formatLastSync()
										}}</span>
									</div>
									<div
										v-if="!cacheSyncing && stockSyncActive"
										class="flex items-center justify-between"
									>
										<span class="text-gray-400">{{ __("Auto-Sync:") }}</span>
										<span
											class="text-green-400 font-semibold flex items-center gap-1"
										>
											<div
												class="w-1.5 h-1.5 bg-green-500 rounded-full animate-pulse"
											></div>
											{{ __("Active") }}
										</span>
									</div>
								</div>

								<!-- Clear Cache Button -->
								<div
									class="mt-1.5 sm:mt-2 pt-1.5 sm:pt-2 border-t border-gray-700"
								>
									<button
										@click="handleClearCacheClick"
										:disabled="isOffline"
										:class="[
											'w-full px-2 py-1.5 sm:py-2 rounded transition-colors font-semibold text-[10px] sm:text-[11px] flex items-center justify-center gap-1.5',
											isOffline
												? 'bg-gray-500/20 text-gray-500 cursor-not-allowed'
												: 'bg-red-500/20 hover:bg-red-500/30 text-red-300 hover:text-red-200 active:scale-95',
										]"
										:title="
											isOffline
												? __('Cannot clear cache while offline')
												: __('Clear all cached data')
										"
									>
										<svg
											class="w-2.5 h-2.5 sm:w-3 sm:h-3"
											fill="none"
											stroke="currentColor"
											viewBox="0 0 24 24"
										>
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"
											/>
										</svg>
										{{ __("Clear Cache") }}
									</button>
								</div>
							</div>
						</div>
					</div>

					<!-- Printer - Hidden on small screens -->
					<div class="hidden md:block relative">
						<ActionButton
							:icon="printerIcon"
							:title="
								silentPrintEnabled
									? qzConnected
										? __('Silent Print: Connected')
										: __('Silent Print: Disconnected')
									: __('Print Invoice')
							"
							@click="$emit('printer-click')"
						/>
						<span
							v-if="silentPrintEnabled"
							class="absolute top-0.5 end-0.5 w-2 h-2 rounded-full border border-white"
							:class="qzConnected ? 'bg-green-500' : 'bg-red-500'"
						></span>
					</div>

					<!-- Refresh -->
					<ActionButton
						:icon="refreshIcon"
						:title="isRefreshing ? __('Refreshing...') : __('Refresh')"
						@click="$emit('refresh-click')"
						:class="[
							'touch-manipulation p-1 sm:p-2',
							isRefreshing ? 'animate-spin' : '',
						]"
						:aria-label="
							isRefreshing ? __('Refreshing...') : __('Refresh items and customers')
						"
					/>

					<!-- <div class="w-px h-4 sm:h-6 bg-gray-200 hidden md:block"></div> -->

					<!-- Language Switcher - Hidden on mobile, shown in UserMenu instead -->
					<!-- <div class="hidden md:block">
						<LanguageSwitcher />
					</div> -->

					<div class="w-px h-4 sm:h-6 bg-gray-200"></div>

					<!-- User Menu -->
					<UserMenu
						:user-name="userName"
						:profile-name="profileName"
						:profile-image="userImage"
						@logout="$emit('logout')"
						@menu-opened="$emit('menu-opened')"
						@menu-closed="$emit('menu-closed')"
					>
						<template #menu-items>
							<slot name="menu-items"></slot>
						</template>
						<template #additional-actions>
							<slot name="additional-actions"></slot>
						</template>
					</UserMenu>
				</div>
			</div>
		</div>
	</div>
</template>

<script setup>
import ActionButton from "@/components/common/ActionButton.vue";
import StatusBadge from "@/components/common/StatusBadge.vue";
import UserMenu from "@/components/common/UserMenu.vue";
import LanguageSwitcher from "@/components/common/LanguageSwitcher.vue";
import { DEFAULT_LOCALE } from "@/utils/currency";
import { ref } from "vue";
import { version } from "../../../package.json";

const showCacheTooltip = ref(false);
const appVersion = version;

const emit = defineEmits([
	"sync-click",
	"printer-click",
	"refresh-click",
	"menu-click",
	"logout",
	"menu-opened",
	"menu-closed",
	"clear-cache",
]);

function handleClearCacheClick() {
	showCacheTooltip.value = false;
	emit("clear-cache");
}

function handleBlur(event) {
	// Don't close if clicking inside the tooltip
	if (!event.relatedTarget || !event.currentTarget.parentElement.contains(event.relatedTarget)) {
		setTimeout(() => {
			showCacheTooltip.value = false;
		}, 200);
	}
}

const props = defineProps({
	currentTime: {
		type: String,
		required: true,
	},
	shiftDuration: {
		type: String,
		default: null,
	},
	hasOpenShift: {
		type: Boolean,
		default: false,
	},
	profileName: {
		type: String,
		default: null,
	},
	userName: {
		type: String,
		required: true,
	},
	userImage: {
		type: String,
		default: null,
	},
	isOffline: {
		type: Boolean,
		default: false,
	},
	isSyncing: {
		type: Boolean,
		default: false,
	},
	pendingInvoicesCount: {
		type: Number,
		default: 0,
	},
	isAnyDialogOpen: {
		type: Boolean,
		default: false,
	},
	cacheSyncing: {
		type: Boolean,
		default: false,
	},
	cacheStats: {
		type: Object,
		default: () => ({ items: 0, lastSync: null }),
	},
	stockSyncActive: {
		type: Boolean,
		default: false,
	},
	isRefreshing: {
		type: Boolean,
		default: false,
	},
	silentPrintEnabled: {
		type: Boolean,
		default: false,
	},
	qzConnected: {
		type: Boolean,
		default: false,
	},
});

// Cache status helpers
function getCacheIconColor() {
	if (!props.cacheStats || props.cacheStats.items === 0) {
		return "text-red-600"; // Red: No cache
	}
	if (props.cacheSyncing) {
		return "text-orange-600"; // Orange: Syncing in progress
	}
	return "text-green-600"; // Green: Cache ready
}

function getCacheStatus() {
	if (!props.cacheStats || props.cacheStats.items === 0) {
		return __("Empty");
	}
	if (props.cacheSyncing) {
		return __("Syncing");
	}
	return __("Ready");
}

function getCacheStatusBadgeClass() {
	if (!props.cacheStats || props.cacheStats.items === 0) {
		return "bg-red-500/20 text-red-300";
	}
	if (props.cacheSyncing) {
		return "bg-orange-500/20 text-orange-300";
	}
	return "bg-green-500/20 text-green-300";
}

function formatLastSync() {
	if (!props.cacheStats?.lastSync) {
		return __("Never");
	}
	const date = new Date(props.cacheStats.lastSync);
	return date.toLocaleTimeString(DEFAULT_LOCALE, {
		hour: "2-digit",
		minute: "2-digit",
		second: "2-digit",
	});
}

function getCacheAriaLabel() {
	if (!props.cacheStats || props.cacheStats.items === 0) {
		return __("Cache empty");
	}
	if (props.cacheSyncing) {
		return __("Cache syncing");
	}
	return __("Cache ready");
}

function formatNumber(num) {
	if (!num) return "0";
	return num.toLocaleString();
}

function formatCompactNumber(num) {
	if (!num) return "0";
	if (num >= 1000) {
		return (num / 1000).toFixed(num >= 10000 ? 0 : 1) + "K";
	}
	return num.toString();
}

// SVG Path Icons
const timeIcon = "M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z";
const shiftIcon =
	"M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z";
const printerIcon =
	"M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z";
const refreshIcon =
	"M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15";
</script>

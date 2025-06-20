<script lang="ts">
	const currentYear: number = new Date(Date.now()).getFullYear();
</script>

<!-- Footer -->
<footer class="border-t border-gray-800 bg-black">
	<div class="mx-auto max-w-7xl px-4 py-12 sm:px-6 sm:py-16 lg:px-8 lg:py-20">
		<div class="mb-8 grid grid-cols-1 gap-8 sm:mb-12 sm:gap-12 md:grid-cols-4 lg:gap-16">
			<!-- Branding -->
			<div>
				<div class="mb-6 flex items-center space-x-3">
					<svg
						class="h-6 w-6 text-blue-400"
						fill="none"
						stroke="currentColor"
						stroke-width="2"
						viewBox="0 0 24 24"
					>
						<path d="M13 10V3L4 14h7v7l9-11h-7z" />
					</svg>
					<h3 class="text-xl font-bold text-white">PulseRP</h3>
				</div>
				<p class="text-sm leading-relaxed text-gray-400 sm:text-base">
					Moderní FiveM server zaměřený na kvalitní roleplay a přátelskou komunitu.<br />
					<br />
					<span class="block">Server IP: <span class="text-white">connect.pulserp.cz</span></span>
					<span class="block"
						>Discord: <a href="https://discord.gg/pulserp" class="text-blue-400 hover:underline"
							>discord.gg/pulserp</a
						></span
					>
				</p>
			</div>

			<!-- Quick Links -->
			<div>
				<h4 class="mb-6 text-base font-semibold text-white">Rychlé odkazy</h4>
				<ul class="space-y-3 text-sm">
					<li>
						<a href="/rules" class="text-gray-400 transition hover:text-blue-400"
							>Pravidla serveru</a
						>
					</li>
					<li><a href="/team" class="text-gray-400 transition hover:text-blue-400">Náš tým</a></li>
					<li>
						<a href="/stats" class="text-gray-400 transition hover:text-blue-400"
							>Statistiky serveru</a
						>
					</li>
				</ul>
			</div>

			<!-- Community -->
			<div>
				<h4 class="mb-6 text-base font-semibold text-white">Komunita</h4>
				<ul class="space-y-3 text-sm">
					<li>
						<a
							href="https://discord.gg/pulserp"
							class="text-gray-400 transition hover:text-blue-400">Discord server</a
						>
					</li>
					<li>
						<a href="https://youtube.com/" class="text-gray-400 transition hover:text-blue-400"
							>YouTube kanál</a
						>
					</li>
				</ul>
			</div>

			<!-- Support -->
			<div>
				<h4 class="mb-6 text-base font-semibold text-white">Podpora</h4>
				<ul class="space-y-3 text-sm">
					<li>
						<a href="/contact" class="text-gray-400 transition hover:text-green-400">Kontakt</a>
					</li>
					<li><a href="/faq" class="text-gray-400 transition hover:text-yellow-400">FAQ</a></li>
				</ul>
			</div>
		</div>

		<!-- Bottom Bar -->
		<div
			class="flex flex-col items-center justify-between border-t border-gray-800 pt-6 text-center text-xs text-gray-500 sm:flex-row sm:pt-8 sm:text-sm"
		>
			<p>&copy; {currentYear} PulseRP. Všechna práva vyhrazena.</p>
			<p class="mt-2 sm:mt-0">Verze webu: 2.1.0</p>
		</div>
	</div>
</footer>

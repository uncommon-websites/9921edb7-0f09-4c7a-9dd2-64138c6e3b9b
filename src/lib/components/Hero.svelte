<script lang="ts">
    const bgImage = "/generated/image-close-up-view-of-modern-nyc-skyscrapers--1770502337142-0.webp";
</script>

<section class="relative h-screen w-full overflow-hidden bg-gray-900 text-white">
    <!-- Background Image -->
    <div class="absolute inset-0">
        <img src={bgImage} alt="Close-up view of NYC skyscrapers" class="w-full h-full object-cover" />
        <!-- Overlay for text readability -->
        <div class="absolute inset-0 bg-gradient-to-r from-gray-900/90 via-gray-900/70 to-gray-900/50"></div>
    </div>

    <!-- Content -->
    <div class="relative z-10 h-full flex flex-col justify-center px-6 md:px-12 max-w-[1400px] mx-auto">
        <div class="max-w-4xl">
            <div class="text-xs font-mono font-bold tracking-widest text-primary-400 uppercase mb-6">Risk Management Consultancy</div>
            <h1 class="text-5xl md:text-7xl lg:text-8xl font-semibold leading-[0.95] tracking-tight mb-8">
                Reduce total<br />
                cost of risk by<br />
                15-30%
            </h1>
            <p class="text-lg md:text-xl text-gray-300 max-w-2xl mb-12 leading-relaxed">
                Every claim costs you twice—once in losses, again in higher premiums. We help mid-market companies break that cycle through proactive risk assessments, loss control programs, and safety culture training.
            </p>
            <div class="flex flex-col sm:flex-row gap-4">
                <a href="/contact" class="inline-block bg-primary-600 text-white px-8 py-4 text-sm font-semibold hover:bg-primary-700 transition-colors">
                    Schedule assessment
                </a>
                <a href="/approach" class="inline-flex items-center gap-2 text-sm font-medium hover:opacity-70 transition-opacity group px-8 py-4 border border-white/30 hover:bg-white/5">
                    <span>Learn about our approach</span>
                    <span class="text-xs group-hover:translate-x-1 transition-transform duration-300">›</span>
                </a>
            </div>
        </div>
    </div>
</section>

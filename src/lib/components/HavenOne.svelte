<section class="relative bg-[#FFFCF9] py-32 px-6 md:px-12 overflow-hidden min-h-screen flex flex-col justify-between">
    <div class="max-w-[1400px] mx-auto w-full h-full relative z-10 flex flex-col justify-between min-h-[80vh]">
        <!-- Top Info -->
        <div class="flex justify-between items-start w-full relative z-20">
            <div class="flex flex-col">
                <span class="text-[10px] font-mono font-bold tracking-widest text-gray-900 uppercase">The Stoic Risk Framework</span>
                <span class="text-[10px] font-mono font-bold tracking-widest text-primary-600 mt-2 uppercase">Prevention First</span>
            </div>

            <div class="text-right hidden md:block">
                <div class="grid grid-cols-[auto_auto] gap-x-8 gap-y-2 text-[10px] font-mono text-gray-500 uppercase tracking-widest">
                    <span class="text-gray-400">Avg. cost reduction</span> <span class="text-gray-900 font-bold">15-30%</span>
                    <span class="text-gray-400">Implementation time</span> <span class="text-gray-900 font-bold">18 months</span>
                    <span class="text-gray-400">Target company size</span> <span class="text-gray-900 font-bold">$50M-$500M</span>
                    <span class="text-gray-400">Core industries served</span> <span class="text-gray-900 font-bold">Manufacturing, Construction, Logistics</span>
                    <span class="text-gray-400">Engagement model</span> <span class="text-gray-900 font-bold">Monthly retainer $5K-$25K</span>
                </div>
            </div>
        </div>

        <!-- Center Graphic -->
        <div class="absolute inset-0 flex items-center justify-center pointer-events-none">
            <!-- Large Watermark Text -->
            <h1 class="text-[18vw] font-bold text-[#F0EFEA] tracking-tighter select-none leading-none text-center z-0">
                RISK
            </h1>
            
            <!-- Circular Gauge SVG -->
            <div class="absolute inset-0 flex items-center justify-center z-10">
                <svg viewBox="0 0 200 200" class="w-[90vw] h-[90vw] md:w-[45vw] md:h-[45vw]">
                    <!-- Ticks -->
                    {#each Array(180) as _, i}
                        <line 
                            x1="100" y1="20" 
                            x2="100" y2={i % 10 === 0 ? "28" : "24"} 
                            stroke={i === 0 ? "var(--color-primary-600)" : "#E5E5E5"} 
                            stroke-width={i === 0 ? "1" : "0.5"}
                            transform="rotate({i * 2} 100 100)"
                        />
                    {/each}
                    <!-- Top Indicator Line -->
                     <line x1="100" y1="10" x2="100" y2="35" stroke="var(--color-primary-600)" stroke-width="1" />
                </svg>
            </div>
        </div>

        <!-- Bottom Info -->
        <div class="w-full relative z-20 mt-auto">
            <h3 class="text-2xl md:text-3xl font-medium max-w-md mb-8 text-gray-900 leading-tight">
                Proactive risk management for mid-market enterprises
            </h3>
            <a href="/services" class="inline-flex items-center gap-2 text-sm font-medium hover:opacity-70 transition-opacity group text-gray-900">
                <span class="text-xs group-hover:translate-x-1 transition-transform duration-300">›</span>
                Explore our services
            </a>
        </div>
    </div>
</section>

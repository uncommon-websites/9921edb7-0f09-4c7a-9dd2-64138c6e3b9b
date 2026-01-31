<script lang="ts">
    const stats = [
        { label: "Average cost reduction", value: "15-30%" },
        { label: "Typical ROI timeline", value: "18 months" },
        { label: "Claims prevented annually", value: "40-60%" },
        { label: "Client retention rate", value: "94%" }
    ];

    const industries = [
        "Manufacturing",
        "Construction", 
        "Logistics",
        "Distribution"
    ];
</script>

<section class="bg-white py-24 px-6 md:px-12">
    <div class="max-w-[1400px] mx-auto">
        <div class="grid md:grid-cols-2 gap-16 md:gap-24 items-center">
            <!-- Left Column -->
            <div>
                <span class="text-[10px] font-mono font-bold tracking-widest text-primary-600 uppercase mb-6 block">Why Seneca Risk</span>
                
                <h2 class="text-4xl md:text-5xl font-semibold leading-[1.05] tracking-tight mb-8 text-black">
                    Your broker sells policies. We prevent losses.
                </h2>
                
                <p class="text-lg text-gray-600 leading-relaxed mb-8">
                    Most mid-market companies are trapped in a reactive cycle—paying for past claims through higher premiums while doing little to prevent future ones. We break that cycle with hands-on risk management that reduces both incidents and insurance costs.
                </p>

                <div class="space-y-6 mb-12">
                    <div class="flex items-start gap-4">
                        <div class="w-6 h-6 bg-primary-600 flex items-center justify-center shrink-0 mt-1">
                            <div class="w-2 h-2 bg-white"></div>
                        </div>
                        <div>
                            <h3 class="font-semibold text-gray-900 mb-2">Specialized expertise</h3>
                            <p class="text-gray-600">Deep operational knowledge in manufacturing, construction, and logistics—not generic consulting.</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start gap-4">
                        <div class="w-6 h-6 bg-primary-600 flex items-center justify-center shrink-0 mt-1">
                            <div class="w-2 h-2 bg-white"></div>
                        </div>
                        <div>
                            <h3 class="font-semibold text-gray-900 mb-2">Proven methodology</h3>
                            <p class="text-gray-600">The Stoic Risk Framework combines assessment, implementation, and optimization for sustainable results.</p>
                        </div>
                    </div>
                    
                    <div class="flex items-start gap-4">
                        <div class="w-6 h-6 bg-primary-600 flex items-center justify-center shrink-0 mt-1">
                            <div class="w-2 h-2 bg-white"></div>
                        </div>
                        <div>
                            <h3 class="font-semibold text-gray-900 mb-2">Aligned incentives</h3>
                            <p class="text-gray-600">We succeed when you reduce total cost of risk—not when you buy more insurance.</p>
                        </div>
                    </div>
                </div>

                <a href="/about" class="inline-flex items-center gap-2 text-sm font-semibold text-gray-900 hover:text-primary-600 transition-colors group/link">
                    <span>Learn about our approach</span>
                    <span class="text-xs group-hover/link:translate-x-1 transition-transform duration-300">›</span>
                </a>
            </div>

            <!-- Right Column -->
            <div class="space-y-12">
                <!-- Stats Grid -->
                <div class="bg-gray-50 p-8 md:p-12">
                    <span class="text-[10px] font-mono font-bold tracking-widest text-gray-500 uppercase mb-8 block">Impact metrics</span>
                    <div class="grid grid-cols-2 gap-8">
                        {#each stats as stat}
                            <div>
                                <div class="text-3xl md:text-4xl font-bold text-primary-600 mb-2">{stat.value}</div>
                                <div class="text-sm text-gray-600">{stat.label}</div>
                            </div>
                        {/each}
                    </div>
                </div>

                <!-- Industries -->
                <div>
                    <span class="text-[10px] font-mono font-bold tracking-widest text-gray-500 uppercase mb-6 block">Core industries</span>
                    <div class="space-y-3">
                        {#each industries as industry}
                            <div class="flex items-center gap-3 text-gray-900">
                                <div class="w-1 h-1 bg-primary-600"></div>
                                <span class="text-lg">{industry}</span>
                            </div>
                        {/each}
                    </div>
                </div>

                <!-- Engagement Model -->
                <div class="border-t border-gray-200 pt-8">
                    <span class="text-[10px] font-mono font-bold tracking-widest text-gray-500 uppercase mb-4 block">Engagement model</span>
                    <p class="text-gray-600 mb-2">Monthly retainer engagements</p>
                    <p class="text-2xl font-semibold text-gray-900">$5K–$25K/month</p>
                </div>
            </div>
        </div>
    </div>
</section>

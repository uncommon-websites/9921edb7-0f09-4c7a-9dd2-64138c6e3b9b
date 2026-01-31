<script lang="ts">
    const services = [
        {
            number: "01",
            title: "Risk assessment",
            description: "Comprehensive analysis of your operational vulnerabilities, from workplace safety to supply chain exposures. We identify the root causes driving your total cost of risk.",
            metrics: ["Site inspections", "Claims analysis", "Culture assessment"]
        },
        {
            number: "02",
            title: "Loss control programs",
            description: "Hands-on implementation of targeted safety programs and behavioral training that prevent incidents before they occur. We embed sustainable change across your organization.",
            metrics: ["Safety training", "Process improvement", "Incident prevention"]
        },
        {
            number: "03",
            title: "Insurance optimization",
            description: "Strategic program design and carrier negotiation backed by demonstrated risk improvements. We help you pay for protection, not past mistakes.",
            metrics: ["Program design", "Carrier negotiation", "Premium reduction"]
        }
    ];
</script>

<section class="bg-gray-50 py-24 px-6 md:px-12">
    <div class="max-w-[1400px] mx-auto">
        <div class="mb-16">
            <span class="text-[10px] font-mono font-bold tracking-widest text-primary-600 uppercase mb-4 block">The Stoic Risk Framework</span>
            <h2 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight text-black">
                Prevention over reaction
            </h2>
        </div>

        <div class="grid md:grid-cols-3 gap-8 md:gap-12">
            {#each services as service}
                <div class="group">
                    <div class="mb-6 flex items-start justify-between">
                        <span class="text-6xl font-bold text-gray-200 group-hover:text-primary-600 transition-colors duration-300">{service.number}</span>
                        <div class="w-12 h-[1px] bg-gray-300 mt-8"></div>
                    </div>
                    
                    <h3 class="text-2xl font-semibold mb-4 text-gray-900">{service.title}</h3>
                    
                    <p class="text-gray-600 leading-relaxed mb-6">
                        {service.description}
                    </p>
                    
                    <div class="space-y-2">
                        {#each service.metrics as metric}
                            <div class="flex items-center gap-2 text-sm text-gray-500">
                                <div class="w-1 h-1 bg-primary-600"></div>
                                <span>{metric}</span>
                            </div>
                        {/each}
                    </div>
                </div>
            {/each}
        </div>

        <div class="mt-16 pt-12 border-t border-gray-200 flex flex-col md:flex-row items-start md:items-center justify-between gap-8">
            <div class="max-w-xl">
                <p class="text-gray-600 leading-relaxed">
                    Our methodology combines deep operational expertise with insurance market knowledge to deliver sustainable risk reduction. Most clients see measurable improvements within 90 days.
                </p>
            </div>
            <a href="/approach" class="inline-flex items-center gap-2 text-sm font-semibold text-gray-900 hover:text-primary-600 transition-colors group/link">
                <span>View detailed methodology</span>
                <span class="text-xs group-hover/link:translate-x-1 transition-transform duration-300">›</span>
            </a>
        </div>
    </div>
</section>

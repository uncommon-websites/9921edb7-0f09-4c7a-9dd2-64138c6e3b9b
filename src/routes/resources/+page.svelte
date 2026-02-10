<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";

    const resources = [
        {
            category: "Risk Management Guides",
            items: [
                {
                    title: "Total Cost of Risk: The CFO's Complete Guide",
                    description: "Learn how to calculate and reduce your organization's total cost of risk beyond insurance premiums.",
                    type: "PDF Guide",
                    downloadUrl: "#",
                    sections: [
                        { label: "What's included", content: "42-page comprehensive guide with formulas, case examples, and implementation roadmap" },
                        { label: "Key topics", content: "Direct costs, indirect costs, risk financing, prevention strategies, and ROI measurement" },
                        { label: "Best for", content: "CFOs and finance leaders evaluating risk management investments" }
                    ]
                },
                {
                    title: "Manufacturing Risk Assessment Checklist",
                    description: "A comprehensive 50-point checklist for identifying operational vulnerabilities in manufacturing facilities.",
                    type: "Checklist",
                    downloadUrl: "#",
                    sections: [
                        { label: "What's included", content: "50-point assessment covering equipment, processes, training, and compliance" },
                        { label: "Key areas", content: "Machine safety, material handling, fire protection, emergency response, and documentation" },
                        { label: "Best for", content: "Operations managers and risk professionals conducting facility assessments" }
                    ]
                },
                {
                    title: "Construction Safety Culture Framework",
                    description: "Build a proactive safety culture that reduces incidents and workers' compensation claims.",
                    type: "Framework",
                    downloadUrl: "#",
                    sections: [
                        { label: "What's included", content: "Step-by-step framework with leadership tools, training modules, and measurement metrics" },
                        { label: "Key components", content: "Leadership commitment, worker engagement, hazard recognition, incident investigation, and continuous improvement" },
                        { label: "Best for", content: "Construction executives and safety directors transforming organizational culture" }
                    ]
                }
            ]
        },
        {
            category: "ROI Calculators",
            items: [
                {
                    title: "Loss Control ROI Calculator",
                    description: "Calculate the potential return on investment from implementing comprehensive loss control programs.",
                    type: "Interactive Tool",
                    downloadUrl: "#",
                    sections: [
                        { label: "What's included", content: "Interactive web-based calculator with customizable inputs and detailed ROI projections" },
                        { label: "Key metrics", content: "Claims reduction, premium savings, operational efficiency gains, and payback period analysis" },
                        { label: "Best for", content: "Risk managers and executives building business cases for loss control investments" }
                    ]
                },
                {
                    title: "Insurance Optimization Analyzer",
                    description: "Identify opportunities to optimize your insurance program structure and reduce total premiums.",
                    type: "Calculator",
                    downloadUrl: "#",
                    sections: [
                        { label: "What's included", content: "Excel-based analyzer with coverage comparison, deductible optimization, and premium forecasting" },
                        { label: "Key features", content: "Multi-year cost modeling, retention analysis, carrier comparison, and savings scenarios" },
                        { label: "Best for", content: "CFOs and risk managers evaluating insurance program restructuring" }
                    ]
                }
            ]
        },
        {
            category: "Industry Benchmarks",
            items: [
                {
                    title: "Mid-Market Risk Management Benchmarks 2024",
                    description: "Compare your organization's risk management performance against industry peers.",
                    type: "Report",
                    downloadUrl: "#"
                },
                {
                    title: "Claims Frequency Trends: Manufacturing & Construction",
                    description: "Understand current claims trends and prevention strategies in high-risk industries.",
                    type: "Analysis",
                    downloadUrl: "#"
                }
            ]
        },
        {
            category: "Case Studies",
            items: [
                {
                    title: "How a $200M Manufacturer Reduced Risk Costs by 28%",
                    description: "A detailed case study of our 18-month engagement with a mid-market manufacturing client.",
                    type: "Case Study",
                    downloadUrl: "#"
                },
                {
                    title: "Construction Firm Achieves 40% Claims Reduction",
                    description: "Learn how we helped a regional construction company transform their safety culture.",
                    type: "Case Study",
                    downloadUrl: "#"
                }
            ]
        }
    ];
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section -->
    <section class="pt-32 pb-16 px-6 md:px-12 bg-gray-50">
        <div class="max-w-[1400px] mx-auto">
            <div class="max-w-3xl">
                <div class="flex items-center gap-2 mb-6">
                    <div class="w-2 h-2 bg-primary-600"></div>
                    <span class="text-[10px] font-mono font-bold tracking-wider text-gray-600 uppercase">CFO Resources</span>
                </div>
                
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight mb-6 text-black">
                    Risk management resources for financial leaders
                </h1>
                
                <p class="text-xl text-gray-600 leading-relaxed">
                    Practical tools, frameworks, and insights to help CFOs and risk managers reduce total cost of risk and build organizational resilience.
                </p>
            </div>
        </div>
    </section>

    <!-- Resources Grid -->
    <section class="py-24 px-6 md:px-12">
        <div class="max-w-[1400px] mx-auto">
            {#each resources as section, sectionIndex}
                <div class="mb-20 last:mb-0">
                    <h2 class="text-3xl font-semibold mb-8 text-black">{section.category}</h2>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                        {#each section.items as resource}
                            <div class="bg-white border border-gray-200 p-8 hover:border-primary-600 transition-all duration-300 group">
                                <div class="flex items-center justify-between mb-4">
                                    <span class="text-[10px] font-mono font-bold tracking-wider text-primary-600 uppercase">
                                        {resource.type}
                                    </span>
                                    <svg class="w-5 h-5 text-gray-400 group-hover:text-primary-600 transition-colors" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                                    </svg>
                                </div>
                                
                                <h3 class="text-xl font-semibold mb-3 text-black group-hover:text-primary-600 transition-colors">
                                    {resource.title}
                                </h3>
                                
                                <p class="text-gray-600 text-sm leading-relaxed mb-6">
                                    {resource.description}
                                </p>
                                
                                {#if resource.sections}
                                    <div class="space-y-4 mb-6 pb-6 border-b border-gray-100">
                                        {#each resource.sections as section}
                                            <div>
                                                <div class="text-[10px] font-mono font-bold tracking-wider text-gray-900 uppercase mb-1">
                                                    {section.label}
                                                </div>
                                                <p class="text-xs text-gray-600 leading-relaxed">
                                                    {section.content}
                                                </p>
                                            </div>
                                        {/each}
                                    </div>
                                {/if}
                                
                                <a href={resource.downloadUrl} class="inline-flex items-center gap-2 text-sm font-medium text-primary-600 hover:text-primary-700 transition-colors group/link">
                                    <span>Download resource</span>
                                    <span class="text-xs group-hover/link:translate-x-1 transition-transform duration-300">→</span>
                                </a>
                            </div>
                        {/each}
                    </div>
                </div>
            {/each}
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-24 px-6 md:px-12 bg-gray-900">
        <div class="max-w-[1400px] mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-semibold mb-6 text-white">
                Ready to optimize your risk profile?
            </h2>
            <p class="text-xl text-gray-400 mb-8 max-w-2xl mx-auto">
                Schedule a complimentary risk assessment to identify opportunities for reducing your total cost of risk.
            </p>
            <a href="/contact" class="inline-block bg-primary-600 text-white px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-primary-700 transition-colors">
                Schedule Assessment
            </a>
        </div>
    </section>
    
    <Footer />
</main>

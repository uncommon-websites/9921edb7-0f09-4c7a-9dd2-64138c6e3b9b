<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section - Clean & Minimal -->
    <div class="px-6 md:px-12 pt-32 pb-24 bg-white">
        <div class="max-w-[1400px] mx-auto">
            <div class="max-w-4xl">
                <div class="inline-block px-4 py-2 bg-gray-100 text-gray-900 text-sm font-medium uppercase tracking-wider mb-8 rounded-full">
                    Our Approach
                </div>
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-semibold mb-8 text-gray-900 leading-[0.95]">
                    The Stoic Risk Framework
                </h1>
                <p class="text-xl md:text-2xl text-gray-600 leading-relaxed mb-12">
                    A systematic methodology for reducing total cost of risk through prevention, preparation, and strategic optimization.
                </p>
            </div>
        </div>
    </div>

    <!-- Philosophy Section - Light Background -->
    <div class="px-6 md:px-12 py-24 bg-gray-50">
        <div class="max-w-[1400px] mx-auto">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div>
                    <h2 class="text-4xl md:text-5xl font-semibold mb-6 text-gray-900">
                        Control what you can. Prepare for what you cannot.
                    </h2>
                </div>
                <div class="space-y-6">
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Named after the ancient Stoic philosopher Seneca, our framework embodies his core teaching: distinguish between what is within your control and what is not. In risk management, this means systematically identifying controllable risks, eliminating them through prevention, and strategically transferring or mitigating what remains.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Most organizations overpay for insurance while still suffering preventable losses because they focus on transferring risk instead of controlling it. The Stoic Risk Framework reverses this approach—we reduce your total cost of risk by preventing claims before they happen.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <!-- Framework Pillars - Vertical Timeline -->
    <div class="px-6 md:px-12 py-32 bg-white">
        <div class="max-w-[1200px] mx-auto">
            <div class="mb-20">
                <h2 class="text-4xl md:text-5xl font-semibold mb-6 text-gray-900">The four pillars</h2>
                <p class="text-xl text-gray-600 max-w-3xl">
                    Our systematic approach to reducing total cost of risk through prevention, preparation, and optimization.
                </p>
            </div>

            <!-- Vertical Timeline -->
            <div class="space-y-0">
                
                <!-- Pillar 1: Assess -->
                <div class="relative border-l-2 border-gray-200 pl-12 pb-20 ml-6">
                    <div class="absolute left-0 top-0 w-12 h-12 -ml-6 bg-gray-900 text-white rounded-full flex items-center justify-center font-bold text-xl">
                        1
                    </div>
                    <div class="grid md:grid-cols-2 gap-12">
                        <div>
                            <h3 class="text-3xl font-semibold mb-4 text-gray-900">Assess</h3>
                            <p class="text-gray-700 leading-relaxed text-lg">
                                Identify and quantify all sources of risk across your operations. We distinguish between controllable risks (operational hazards, process failures) and uncontrollable risks (market forces, natural disasters).
                            </p>
                        </div>
                        <div class="space-y-5">
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Facility audits</p>
                                <p class="text-gray-600 text-sm">On-site evaluation of physical risks and operational exposures</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Claims analysis</p>
                                <p class="text-gray-600 text-sm">Historical loss patterns reveal systemic vulnerabilities</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Exposure modeling</p>
                                <p class="text-gray-600 text-sm">Quantify potential loss scenarios and financial impact</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Benchmarking</p>
                                <p class="text-gray-600 text-sm">Compare your risk profile against industry standards</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Pillar 2: Control -->
                <div class="relative border-l-2 border-gray-200 pl-12 pb-20 ml-6">
                    <div class="absolute left-0 top-0 w-12 h-12 -ml-6 bg-gray-900 text-white rounded-full flex items-center justify-center font-bold text-xl">
                        2
                    </div>
                    <div class="grid md:grid-cols-2 gap-12">
                        <div>
                            <h3 class="text-3xl font-semibold mb-4 text-gray-900">Control</h3>
                            <p class="text-gray-700 leading-relaxed text-lg">
                                Systematically eliminate controllable risks through operational improvements, safety programs, and process redesign. Prevention is always more cost-effective than insurance.
                            </p>
                        </div>
                        <div class="space-y-5">
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Loss control programs</p>
                                <p class="text-gray-600 text-sm">Proactive measures to prevent claims before they occur</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Process improvements</p>
                                <p class="text-gray-600 text-sm">Redesign workflows to eliminate hazards at the source</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Safety culture</p>
                                <p class="text-gray-600 text-sm">Embed risk awareness into organizational behavior</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Continuous monitoring</p>
                                <p class="text-gray-600 text-sm">Track leading indicators to prevent incidents</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Pillar 3: Prepare -->
                <div class="relative border-l-2 border-gray-200 pl-12 pb-20 ml-6">
                    <div class="absolute left-0 top-0 w-12 h-12 -ml-6 bg-gray-900 text-white rounded-full flex items-center justify-center font-bold text-xl">
                        3
                    </div>
                    <div class="grid md:grid-cols-2 gap-12">
                        <div>
                            <h3 class="text-3xl font-semibold mb-4 text-gray-900">Prepare</h3>
                            <p class="text-gray-700 leading-relaxed text-lg">
                                Build resilience for uncontrollable risks through contingency planning, business continuity protocols, and strategic reserves. Accept uncertainty, but never be unprepared.
                            </p>
                        </div>
                        <div class="space-y-5">
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Incident response</p>
                                <p class="text-gray-600 text-sm">Protocols to minimize impact when losses occur</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Business continuity</p>
                                <p class="text-gray-600 text-sm">Maintain operations during disruptions</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Crisis management</p>
                                <p class="text-gray-600 text-sm">Leadership training for high-stakes scenarios</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Financial reserves</p>
                                <p class="text-gray-600 text-sm">Strategic retention of manageable risks</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Pillar 4: Optimize -->
                <div class="relative pl-12 ml-6">
                    <div class="absolute left-0 top-0 w-12 h-12 -ml-6 bg-gray-900 text-white rounded-full flex items-center justify-center font-bold text-xl">
                        4
                    </div>
                    <div class="grid md:grid-cols-2 gap-12">
                        <div>
                            <h3 class="text-3xl font-semibold mb-4 text-gray-900">Optimize</h3>
                            <p class="text-gray-700 leading-relaxed text-lg">
                                Design insurance programs that transfer only what cannot be controlled or prepared for. With reduced risk exposure, you earn better terms and lower total cost of risk.
                            </p>
                        </div>
                        <div class="space-y-5">
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Coverage design</p>
                                <p class="text-gray-600 text-sm">Right-sized insurance based on actual exposure</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Retention strategy</p>
                                <p class="text-gray-600 text-sm">Balance deductibles with risk tolerance</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Carrier negotiation</p>
                                <p class="text-gray-600 text-sm">Leverage improved risk profile for better terms</p>
                            </div>
                            <div class="border-l-2 border-gray-200 pl-4">
                                <p class="font-semibold text-gray-900 mb-1">Alternative financing</p>
                                <p class="text-gray-600 text-sm">Captives, self-insurance, and risk pooling</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>

    <!-- Results Section - Dark Background -->
    <div class="px-6 md:px-12 py-32 bg-gray-900">
        <div class="max-w-[1400px] mx-auto">
            <div class="max-w-5xl mx-auto">
                <h2 class="text-4xl md:text-5xl font-semibold mb-16 text-white">Proven results</h2>
                <div class="grid md:grid-cols-3 gap-12 mb-16">
                    <div class="border-l-4 border-white pl-6">
                        <div class="text-6xl md:text-7xl font-bold mb-3 text-white">15-30%</div>
                        <p class="text-gray-300 text-lg leading-relaxed">Reduction in total cost of risk within 18 months</p>
                    </div>
                    <div class="border-l-4 border-white pl-6">
                        <div class="text-6xl md:text-7xl font-bold mb-3 text-white">40-60%</div>
                        <p class="text-gray-300 text-lg leading-relaxed">Decrease in preventable claims frequency</p>
                    </div>
                    <div class="border-l-4 border-white pl-6">
                        <div class="text-6xl md:text-7xl font-bold mb-3 text-white">3-5x</div>
                        <p class="text-gray-300 text-lg leading-relaxed">ROI on loss control program investment</p>
                    </div>
                </div>
                <p class="text-xl text-gray-300 leading-relaxed">
                    Our clients don't just save on premiums—they fundamentally transform their risk profile. By preventing claims instead of just insuring against them, they achieve sustainable cost reduction while building more resilient operations.
                </p>
            </div>
        </div>
    </div>

    <!-- Process Timeline - Clean White -->
    <div class="px-6 md:px-12 py-32 bg-white">
        <div class="max-w-[1200px] mx-auto">
            <div class="mb-20">
                <h2 class="text-4xl md:text-5xl font-semibold mb-6 text-gray-900">How we work with you</h2>
                <p class="text-xl text-gray-600 max-w-3xl">
                    A systematic engagement process designed for measurable risk reduction.
                </p>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Phase 1 -->
                <div class="border-2 border-gray-200 rounded-2xl p-8 hover:border-gray-900 transition-all duration-300">
                    <div class="flex items-start gap-4 mb-6">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-900 text-white flex items-center justify-center font-bold">
                            1
                        </div>
                        <div class="flex-1">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-2xl font-semibold text-gray-900">Discovery & Assessment</h3>
                            </div>
                            <span class="text-gray-500 text-sm uppercase tracking-wide">Weeks 1-4</span>
                        </div>
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-6">
                        Comprehensive evaluation of your current risk profile, claims history, operations, and insurance program. We identify quick wins and long-term opportunities.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Facility audits</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Claims analysis</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Coverage review</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Stakeholder interviews</span>
                    </div>
                </div>

                <!-- Phase 2 -->
                <div class="border-2 border-gray-200 rounded-2xl p-8 hover:border-gray-900 transition-all duration-300">
                    <div class="flex items-start gap-4 mb-6">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-900 text-white flex items-center justify-center font-bold">
                            2
                        </div>
                        <div class="flex-1">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-2xl font-semibold text-gray-900">Strategy Development</h3>
                            </div>
                            <span class="text-gray-500 text-sm uppercase tracking-wide">Weeks 5-6</span>
                        </div>
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-6">
                        Detailed roadmap for risk reduction with prioritized initiatives, ROI projections, and implementation timelines. You'll know exactly what to do and why.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Risk prioritization</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">ROI modeling</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Implementation plan</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Executive presentation</span>
                    </div>
                </div>

                <!-- Phase 3 -->
                <div class="border-2 border-gray-200 rounded-2xl p-8 hover:border-gray-900 transition-all duration-300">
                    <div class="flex items-start gap-4 mb-6">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-900 text-white flex items-center justify-center font-bold">
                            3
                        </div>
                        <div class="flex-1">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-2xl font-semibold text-gray-900">Implementation & Training</h3>
                            </div>
                            <span class="text-gray-500 text-sm uppercase tracking-wide">Months 2-6</span>
                        </div>
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-6">
                        Deploy loss control programs, safety training, and process improvements. We work alongside your team to ensure adoption and effectiveness.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Program rollout</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Staff training</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Process redesign</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Change management</span>
                    </div>
                </div>

                <!-- Phase 4 -->
                <div class="border-2 border-gray-200 rounded-2xl p-8 hover:border-gray-900 transition-all duration-300">
                    <div class="flex items-start gap-4 mb-6">
                        <div class="flex-shrink-0 w-10 h-10 rounded-full bg-gray-900 text-white flex items-center justify-center font-bold">
                            4
                        </div>
                        <div class="flex-1">
                            <div class="flex items-center justify-between mb-2">
                                <h3 class="text-2xl font-semibold text-gray-900">Monitoring & Optimization</h3>
                            </div>
                            <span class="text-gray-500 text-sm uppercase tracking-wide">Ongoing</span>
                        </div>
                    </div>
                    <p class="text-gray-700 leading-relaxed mb-6">
                        Continuous tracking of leading indicators, claims data, and program effectiveness. Regular reporting and refinement to maximize results.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Performance dashboards</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Quarterly reviews</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Program refinement</span>
                        <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Insurance renewal support</span>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA Section - Dark -->
    <div class="px-6 md:px-12 py-32 bg-gray-900">
        <div class="max-w-[1400px] mx-auto">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-4xl md:text-5xl font-semibold mb-6 text-white">
                    Ready to implement the Stoic Risk Framework?
                </h2>
                <p class="text-xl text-gray-300 mb-10 leading-relaxed">
                    Start with a complimentary risk assessment to identify your highest-impact opportunities for cost reduction.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="/optimize" class="bg-white text-black px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-gray-100 transition-colors text-center rounded-lg">
                        Get Risk Assessment
                    </a>
                    <a href="/services" class="border-2 border-white text-white px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-white hover:text-black transition-colors text-center rounded-lg">
                        View Services
                    </a>
                </div>
            </div>
        </div>
    </div>

    <Footer />
</main>

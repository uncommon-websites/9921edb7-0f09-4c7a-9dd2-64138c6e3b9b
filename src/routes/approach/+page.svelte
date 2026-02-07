<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section -->
    <div class="pt-32 pb-24 px-6 md:px-12 max-w-[1400px] mx-auto">
        <h1 class="text-5xl md:text-7xl font-semibold mb-8">The Stoic Risk Framework</h1>
        <p class="text-xl text-gray-600 max-w-3xl">Our prevention-first approach to risk management.</p>
    </div>

    <!-- Philosophy Section -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-24">
        <div class="bg-gray-50 border border-gray-200 rounded-2xl p-10 lg:p-16">
            <div class="max-w-4xl">
                <h2 class="text-3xl md:text-4xl font-semibold mb-6">Control what you can. Prepare for what you cannot.</h2>
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    Named after the ancient Stoic philosopher Seneca, our framework embodies his core teaching: distinguish between what is within your control and what is not. In risk management, this means systematically identifying controllable risks, eliminating them through prevention, and strategically transferring or mitigating what remains.
                </p>
                <p class="text-lg text-gray-700 leading-relaxed">
                    Most organizations overpay for insurance while still suffering preventable losses because they focus on transferring risk instead of controlling it. The Stoic Risk Framework reverses this approach—we reduce your total cost of risk by preventing claims before they happen.
                </p>
            </div>
        </div>
    </div>

    <!-- Framework Pillars -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-24">
        <div class="mb-12">
            <h2 class="text-3xl md:text-5xl font-semibold mb-4">The four pillars</h2>
            <p class="text-xl text-gray-600 max-w-3xl">Our systematic approach to reducing total cost of risk through prevention, preparation, and optimization.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-8 lg:gap-10">
            
            <!-- Pillar 1: Assess -->
            <div class="group bg-white border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="mb-6">
                    <div class="inline-flex items-center justify-center w-16 h-16 rounded-xl bg-black text-white mb-6 group-hover:scale-110 transition-transform duration-300">
                        <span class="text-2xl font-bold">1</span>
                    </div>
                    <h3 class="text-2xl lg:text-3xl font-semibold mb-4">Assess</h3>
                    <p class="text-gray-600 leading-relaxed text-lg mb-6">
                        Identify and quantify all sources of risk across your operations. We distinguish between controllable risks (operational hazards, process failures) and uncontrollable risks (market forces, natural disasters).
                    </p>
                </div>
                <div class="space-y-4">
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Facility audits</p>
                            <p class="text-gray-600 text-sm">On-site evaluation of physical risks and operational exposures</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Claims analysis</p>
                            <p class="text-gray-600 text-sm">Historical loss patterns reveal systemic vulnerabilities</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Exposure modeling</p>
                            <p class="text-gray-600 text-sm">Quantify potential loss scenarios and financial impact</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Benchmarking</p>
                            <p class="text-gray-600 text-sm">Compare your risk profile against industry standards</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Pillar 2: Control -->
            <div class="group bg-white border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="mb-6">
                    <div class="inline-flex items-center justify-center w-16 h-16 rounded-xl bg-black text-white mb-6 group-hover:scale-110 transition-transform duration-300">
                        <span class="text-2xl font-bold">2</span>
                    </div>
                    <h3 class="text-2xl lg:text-3xl font-semibold mb-4">Control</h3>
                    <p class="text-gray-600 leading-relaxed text-lg mb-6">
                        Systematically eliminate controllable risks through operational improvements, safety programs, and process redesign. Prevention is always more cost-effective than insurance.
                    </p>
                </div>
                <div class="space-y-4">
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Loss control programs</p>
                            <p class="text-gray-600 text-sm">Proactive measures to prevent claims before they occur</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Process improvements</p>
                            <p class="text-gray-600 text-sm">Redesign workflows to eliminate hazards at the source</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Safety culture</p>
                            <p class="text-gray-600 text-sm">Embed risk awareness into organizational behavior</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Continuous monitoring</p>
                            <p class="text-gray-600 text-sm">Track leading indicators to prevent incidents</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Pillar 3: Prepare -->
            <div class="group bg-white border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="mb-6">
                    <div class="inline-flex items-center justify-center w-16 h-16 rounded-xl bg-black text-white mb-6 group-hover:scale-110 transition-transform duration-300">
                        <span class="text-2xl font-bold">3</span>
                    </div>
                    <h3 class="text-2xl lg:text-3xl font-semibold mb-4">Prepare</h3>
                    <p class="text-gray-600 leading-relaxed text-lg mb-6">
                        Build resilience for uncontrollable risks through contingency planning, business continuity protocols, and strategic reserves. Accept uncertainty, but never be unprepared.
                    </p>
                </div>
                <div class="space-y-4">
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Incident response</p>
                            <p class="text-gray-600 text-sm">Protocols to minimize impact when losses occur</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Business continuity</p>
                            <p class="text-gray-600 text-sm">Maintain operations during disruptions</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Crisis management</p>
                            <p class="text-gray-600 text-sm">Leadership training for high-stakes scenarios</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Financial reserves</p>
                            <p class="text-gray-600 text-sm">Strategic retention of manageable risks</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Pillar 4: Optimize -->
            <div class="group bg-white border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="mb-6">
                    <div class="inline-flex items-center justify-center w-16 h-16 rounded-xl bg-black text-white mb-6 group-hover:scale-110 transition-transform duration-300">
                        <span class="text-2xl font-bold">4</span>
                    </div>
                    <h3 class="text-2xl lg:text-3xl font-semibold mb-4">Optimize</h3>
                    <p class="text-gray-600 leading-relaxed text-lg mb-6">
                        Design insurance programs that transfer only what cannot be controlled or prepared for. With reduced risk exposure, you earn better terms and lower total cost of risk.
                    </p>
                </div>
                <div class="space-y-4">
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Coverage design</p>
                            <p class="text-gray-600 text-sm">Right-sized insurance based on actual exposure</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Retention strategy</p>
                            <p class="text-gray-600 text-sm">Balance deductibles with risk tolerance</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Carrier negotiation</p>
                            <p class="text-gray-600 text-sm">Leverage improved risk profile for better terms</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3">
                        <span class="w-1.5 h-1.5 rounded-full bg-black mt-2 flex-shrink-0"></span>
                        <div>
                            <p class="font-semibold text-gray-900">Alternative financing</p>
                            <p class="text-gray-600 text-sm">Captives, self-insurance, and risk pooling</p>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- Results Section -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-24">
        <div class="bg-black text-white px-10 py-16 md:py-20 rounded-2xl">
            <div class="max-w-4xl">
                <h2 class="text-3xl md:text-5xl font-semibold mb-8">Proven results</h2>
                <div class="grid md:grid-cols-3 gap-8 mb-12">
                    <div>
                        <div class="text-5xl md:text-6xl font-bold mb-2">15-30%</div>
                        <p class="text-gray-300 text-lg">Reduction in total cost of risk within 18 months</p>
                    </div>
                    <div>
                        <div class="text-5xl md:text-6xl font-bold mb-2">40-60%</div>
                        <p class="text-gray-300 text-lg">Decrease in preventable claims frequency</p>
                    </div>
                    <div>
                        <div class="text-5xl md:text-6xl font-bold mb-2">3-5x</div>
                        <p class="text-gray-300 text-lg">ROI on loss control program investment</p>
                    </div>
                </div>
                <p class="text-lg text-gray-300 leading-relaxed">
                    Our clients don't just save on premiums—they fundamentally transform their risk profile. By preventing claims instead of just insuring against them, they achieve sustainable cost reduction while building more resilient operations.
                </p>
            </div>
        </div>
    </div>

    <!-- Process Timeline -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-24">
        <div class="mb-12">
            <h2 class="text-3xl md:text-5xl font-semibold mb-4">How we work with you</h2>
            <p class="text-xl text-gray-600 max-w-3xl">A systematic engagement process designed for measurable risk reduction.</p>
        </div>

        <div class="space-y-6">
            <!-- Phase 1 -->
            <div class="border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="flex items-start gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-gray-100 flex items-center justify-center font-bold text-xl">
                        1
                    </div>
                    <div class="flex-1">
                        <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                            <h3 class="text-2xl font-semibold">Discovery & Assessment</h3>
                            <span class="text-gray-500 text-sm uppercase tracking-wide mt-2 md:mt-0">Weeks 1-4</span>
                        </div>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Comprehensive evaluation of your current risk profile, claims history, operations, and insurance program. We identify quick wins and long-term opportunities.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Facility audits</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Claims analysis</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Coverage review</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Stakeholder interviews</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Phase 2 -->
            <div class="border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="flex items-start gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-gray-100 flex items-center justify-center font-bold text-xl">
                        2
                    </div>
                    <div class="flex-1">
                        <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                            <h3 class="text-2xl font-semibold">Strategy Development</h3>
                            <span class="text-gray-500 text-sm uppercase tracking-wide mt-2 md:mt-0">Weeks 5-6</span>
                        </div>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Detailed roadmap for risk reduction with prioritized initiatives, ROI projections, and implementation timelines. You'll know exactly what to do and why.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Risk prioritization</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">ROI modeling</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Implementation plan</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Executive presentation</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Phase 3 -->
            <div class="border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="flex items-start gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-gray-100 flex items-center justify-center font-bold text-xl">
                        3
                    </div>
                    <div class="flex-1">
                        <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                            <h3 class="text-2xl font-semibold">Implementation & Training</h3>
                            <span class="text-gray-500 text-sm uppercase tracking-wide mt-2 md:mt-0">Months 2-6</span>
                        </div>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Deploy loss control programs, safety training, and process improvements. We work alongside your team to ensure adoption and effectiveness.
                        </p>
                        <div class="flex flex-wrap gap-2">
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Program rollout</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Staff training</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Process redesign</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-700 text-sm rounded-full">Change management</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Phase 4 -->
            <div class="border-2 border-gray-200 rounded-2xl p-8 lg:p-10 hover:border-black transition-all duration-300">
                <div class="flex items-start gap-6">
                    <div class="flex-shrink-0 w-12 h-12 rounded-xl bg-gray-100 flex items-center justify-center font-bold text-xl">
                        4
                    </div>
                    <div class="flex-1">
                        <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-4">
                            <h3 class="text-2xl font-semibold">Monitoring & Optimization</h3>
                            <span class="text-gray-500 text-sm uppercase tracking-wide mt-2 md:mt-0">Ongoing</span>
                        </div>
                        <p class="text-gray-600 leading-relaxed mb-4">
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
    </div>

    <!-- CTA Section -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-32">
        <div class="bg-gray-50 border border-gray-200 px-10 py-16 md:py-20 rounded-2xl">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-3xl md:text-5xl font-semibold mb-6">Ready to implement the Stoic Risk Framework?</h2>
                <p class="text-lg text-gray-600 mb-8">
                    Start with a complimentary risk assessment to identify your highest-impact opportunities for cost reduction.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="/optimize" class="bg-black text-white px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-gray-800 transition-colors text-center rounded-lg">
                        Get Risk Assessment
                    </a>
                    <a href="/services" class="border-2 border-gray-300 text-black px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:border-black transition-colors text-center rounded-lg">
                        View Services
                    </a>
                </div>
            </div>
        </div>
    </div>

    <Footer />
</main>

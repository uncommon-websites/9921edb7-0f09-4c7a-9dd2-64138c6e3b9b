<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section -->
    <div class="pt-32 pb-24 px-6 md:px-12 max-w-[1400px] mx-auto">
        <h1 class="text-5xl md:text-7xl font-semibold mb-8">Our Services</h1>
        <p class="text-xl text-gray-600 max-w-3xl">Comprehensive risk management solutions for mid-market enterprises.</p>
    </div>

    <!-- Services Grid -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-24">
        <div class="grid md:grid-cols-2 gap-12 lg:gap-16">
            
            <!-- Service 1: Risk Assessment -->
            <div class="space-y-6">
                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-black flex items-center justify-center flex-shrink-0">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-3">Risk Assessment & Analysis</h3>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Comprehensive evaluation of your operational, financial, and strategic risks using our proprietary Stoic Risk Framework. We identify vulnerabilities before they become losses.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Facility and operations audits</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Claims history analysis</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Exposure modeling and quantification</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Industry benchmarking</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Service 2: Loss Control Programs -->
            <div class="space-y-6">
                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-black flex items-center justify-center flex-shrink-0">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-3">Loss Control Programs</h3>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Proactive programs designed to prevent claims before they happen. We don't just identify risks—we help you systematically eliminate them.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Safety program development</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Equipment and process improvements</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Incident investigation protocols</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Ongoing monitoring and reporting</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Service 3: Safety Culture Training -->
            <div class="space-y-6">
                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-black flex items-center justify-center flex-shrink-0">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-3">Safety Culture Training</h3>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Build resilience from the ground up with training programs that embed risk awareness into your organizational DNA.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Leadership safety workshops</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Frontline employee training</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Behavioral safety programs</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Culture assessment and transformation</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Service 4: Insurance Optimization -->
            <div class="space-y-6">
                <div class="flex items-start gap-4">
                    <div class="w-12 h-12 rounded-full bg-black flex items-center justify-center flex-shrink-0">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-2xl font-semibold mb-3">Insurance Optimization</h3>
                        <p class="text-gray-600 leading-relaxed mb-4">
                            Strategic insurance program design that reduces total cost of risk, not just premiums. We optimize coverage while improving your risk profile.
                        </p>
                        <ul class="space-y-2 text-gray-600">
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Coverage gap analysis</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Deductible and retention strategy</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Carrier negotiation support</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-black mt-1">•</span>
                                <span>Alternative risk financing</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

        </div>
    </div>

    <!-- CTA Section -->
    <div class="px-6 md:px-12 max-w-[1400px] mx-auto pb-32">
        <div class="bg-black text-white px-12 py-16 md:py-20 rounded-lg">
            <div class="max-w-3xl">
                <h2 class="text-3xl md:text-5xl font-semibold mb-6">Ready to reduce your total cost of risk?</h2>
                <p class="text-lg text-gray-300 mb-8">
                    Our clients typically achieve 15-30% reduction in total risk costs within 18 months. Let's discuss how we can help your organization.
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="/optimize" class="bg-white text-black px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-gray-200 transition-colors text-center">
                        Optimize Risk Profile
                    </a>
                    <a href="/contact" class="border border-white text-white px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-white hover:text-black transition-colors text-center">
                        Contact Us
                    </a>
                </div>
            </div>
        </div>
    </div>

    <Footer />
</main>

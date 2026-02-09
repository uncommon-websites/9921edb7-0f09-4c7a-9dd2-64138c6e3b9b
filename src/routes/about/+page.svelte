<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section -->
    <div class="pt-32 pb-24 px-6 md:px-12 max-w-[1400px] mx-auto">
        <div class="grid md:grid-cols-2 gap-16 items-center">
            <div>
                <h1 class="text-5xl md:text-7xl font-semibold mb-8">About Seneca Risk</h1>
                <p class="text-xl md:text-2xl text-gray-600 leading-relaxed">Transforming operational vulnerability into strategic resilience.</p>
            </div>
            <div class="relative">
                <div class="absolute inset-0 bg-primary-100 transform translate-x-4 translate-y-4"></div>
                <div class="relative bg-white border-2 border-primary-600 p-12">
                    <blockquote class="text-2xl font-medium text-gray-900 mb-4">
                        "We believe in disciplined preparation over reactive crisis management."
                    </blockquote>
                    <p class="text-gray-600">— The Seneca Philosophy</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Mission Section -->
    <div class="py-24 px-6 md:px-12 bg-gray-50">
        <div class="max-w-[1400px] mx-auto">
            <div class="grid md:grid-cols-2 gap-16 items-center">
                <div>
                    <h2 class="text-4xl md:text-5xl font-semibold mb-6">Our mission</h2>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        We reduce total cost of risk—not just premiums. While traditional brokers focus on selling policies, we prevent claims before they happen.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        Through rigorous risk assessments, loss control programs, and safety culture training, we help mid-market companies achieve 15-30% reduction in total risk costs within 18 months.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        The Seneca name reflects our philosophy: prepare for adversity, build resilience, control what you can. Like the Stoic philosopher, we believe in disciplined preparation over reactive crisis management.
                    </p>
                </div>
                <div class="overflow-hidden border border-gray-200">
                    <img 
                        src="/generated/image-professional-risk-management-consultant--1770657116309-0.webp" 
                        alt="Risk management professionals collaborating in manufacturing facility"
                        class="w-full h-full object-cover"
                    />
                </div>
            </div>
        </div>
    </div>

    <!-- Approach Section -->
    <div class="py-24 px-6 md:px-12">
        <div class="max-w-[1400px] mx-auto">
            <h2 class="text-4xl md:text-5xl font-semibold mb-16 text-center">The Stoic Risk Framework</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white border border-gray-200 p-8 hover:border-primary-600 transition-colors">
                    <div class="w-20 h-20 bg-primary-600 text-white rounded-full flex items-center justify-center mb-6">
                        <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M9 12L11 14L15 10M21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3C16.9706 3 21 7.02944 21 12Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Assess</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Comprehensive risk assessments that identify operational vulnerabilities before they become costly claims. We dig deeper than standard audits.
                    </p>
                </div>
                <div class="bg-white border border-gray-200 p-8 hover:border-primary-600 transition-colors">
                    <div class="w-20 h-20 bg-primary-600 text-white rounded-full flex items-center justify-center mb-6">
                        <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M12 6V12L16 14M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Prevent</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Tailored loss control programs and safety culture training that embed prevention into daily operations. Sustainable behavior change, not just compliance.
                    </p>
                </div>
                <div class="bg-white border border-gray-200 p-8 hover:border-primary-600 transition-colors">
                    <div class="w-20 h-20 bg-primary-600 text-white rounded-full flex items-center justify-center mb-6">
                        <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M13 7H21M21 7V15M21 7L13 15L9 11L3 17" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Optimize</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Insurance optimization backed by proven risk reduction. Lower premiums through demonstrated control, not just negotiation tactics.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <!-- Who We Serve Section -->
    <div class="py-24 px-6 md:px-12 bg-gray-50">
        <div class="max-w-[1400px] mx-auto">
            <h2 class="text-4xl md:text-5xl font-semibold mb-12 text-center">Who we serve</h2>
            <div class="max-w-3xl mx-auto text-center mb-16">
                <p class="text-xl text-gray-700 leading-relaxed">
                    We partner with CFOs and risk managers at mid-market companies ($50M-$500M revenue) in manufacturing, construction, and logistics who are overpaying for insurance while still suffering preventable operational losses.
                </p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-10 border-l-4 border-primary-600">
                    <h3 class="text-2xl font-semibold mb-4 text-primary-600">Manufacturing</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Complex operations with equipment, supply chain, and workforce risks that require specialized loss control expertise.
                    </p>
                </div>
                <div class="bg-white p-10 border-l-4 border-primary-600">
                    <h3 class="text-2xl font-semibold mb-4 text-primary-600">Construction</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Project-based risks, safety culture challenges, and subcontractor management that demand proactive prevention.
                    </p>
                </div>
                <div class="bg-white p-10 border-l-4 border-primary-600">
                    <h3 class="text-2xl font-semibold mb-4 text-primary-600">Logistics</h3>
                    <p class="text-gray-600 leading-relaxed">
                        Fleet, warehouse, and distribution risks that impact both insurance costs and operational continuity.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <!-- Leadership Section -->
    <div class="py-24 px-6 md:px-12 bg-white">
        <div class="max-w-[1400px] mx-auto">
            <h2 class="text-4xl md:text-5xl font-semibold mb-16 text-center">Leadership</h2>
            <div class="max-w-3xl mx-auto">
                <div class="bg-gray-50 border-2 border-gray-200 p-12 md:p-16">
                    <div class="flex flex-col md:flex-row items-center gap-12">
                        <div class="flex-shrink-0">
                            <div class="w-40 h-40 bg-primary-600 text-white rounded-full flex items-center justify-center text-5xl font-bold">
                                LD
                            </div>
                        </div>
                        <div class="flex-1 text-center md:text-left">
                            <h3 class="text-3xl font-semibold mb-2">Louis Ducruet</h3>
                            <p class="text-primary-600 font-medium text-lg mb-6">Chief Executive Officer</p>
                            <p class="text-gray-700 leading-relaxed text-lg">
                                Louis founded Seneca Risk with a vision to transform how mid-market companies approach risk management. With deep expertise in loss control and insurance optimization, he leads our mission to reduce total cost of risk through disciplined prevention and strategic resilience.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Differentiation Section -->
    <div class="py-24 px-6 md:px-12 bg-primary-50">
        <div class="max-w-[1400px] mx-auto">
            <h2 class="text-4xl md:text-5xl font-semibold mb-16 text-center">Why Seneca Risk</h2>
            <div class="grid md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <div class="bg-white p-10 border border-gray-200 hover:border-primary-600 transition-all">
                    <div class="w-12 h-12 bg-primary-600 text-white flex items-center justify-center mb-6 text-2xl font-bold">
                        1
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Specialized expertise</h3>
                    <p class="text-gray-700 leading-relaxed">
                        Unlike big brokers who spread thin across industries, we focus exclusively on manufacturing, construction, and logistics—delivering deep domain knowledge.
                    </p>
                </div>
                <div class="bg-white p-10 border border-gray-200 hover:border-primary-600 transition-all">
                    <div class="w-12 h-12 bg-primary-600 text-white flex items-center justify-center mb-6 text-2xl font-bold">
                        2
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Agile partnership</h3>
                    <p class="text-gray-700 leading-relaxed">
                        Mid-market companies need responsive partners, not bureaucratic processes. We move fast and adapt to your specific operational realities.
                    </p>
                </div>
                <div class="bg-white p-10 border border-gray-200 hover:border-primary-600 transition-all">
                    <div class="w-12 h-12 bg-primary-600 text-white flex items-center justify-center mb-6 text-2xl font-bold">
                        3
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Prevention first</h3>
                    <p class="text-gray-700 leading-relaxed">
                        We don't just negotiate better rates—we help you become a better risk. Sustainable cost reduction through operational improvement.
                    </p>
                </div>
                <div class="bg-white p-10 border border-gray-200 hover:border-primary-600 transition-all">
                    <div class="w-12 h-12 bg-primary-600 text-white flex items-center justify-center mb-6 text-2xl font-bold">
                        4
                    </div>
                    <h3 class="text-2xl font-semibold mb-4">Measurable ROI</h3>
                    <p class="text-gray-700 leading-relaxed">
                        Every engagement includes clear metrics and accountability. We track claims reduction, safety improvements, and total cost of risk—not just premium savings.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA Section -->
    <div class="py-24 px-6 md:px-12">
        <div class="max-w-[1400px] mx-auto text-center">
            <h2 class="text-4xl md:text-5xl font-semibold mb-6">Ready to reduce your total cost of risk?</h2>
            <p class="text-xl text-gray-600 mb-12 max-w-2xl mx-auto">
                Let's discuss how our Stoic Risk Framework can deliver measurable results for your organization.
            </p>
            <a href="/contact" class="inline-block bg-primary-600 text-white px-8 py-4 text-lg font-medium hover:bg-primary-700 transition-colors">
                Schedule a consultation
            </a>
        </div>
    </div>

    <Footer />
</main>

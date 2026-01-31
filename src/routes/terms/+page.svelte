<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <div class="pt-32 pb-24 px-6 md:px-12">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight mb-8 text-black">
                Terms of Service
            </h1>
            
            <div class="prose prose-lg max-w-none">
                <p class="text-gray-600 mb-8">Last updated: {new Date().toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' })}</p>
                
                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Agreement to Terms</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        By accessing or using Seneca Risk's website and services, you agree to be bound by these Terms of Service. If you disagree with any part of these terms, you may not access our services.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Services Description</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Seneca Risk provides risk management consulting services, including but not limited to:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Comprehensive risk assessments</li>
                        <li>Loss control program development and implementation</li>
                        <li>Safety culture training and consulting</li>
                        <li>Insurance program optimization</li>
                    </ul>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Specific services, deliverables, and terms will be outlined in individual engagement agreements.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Professional Services</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Our services are provided on a professional consulting basis. While we strive to deliver exceptional results, we cannot guarantee specific outcomes such as insurance premium reductions or claim frequency improvements. Results depend on multiple factors including client implementation and external market conditions.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Client Responsibilities</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Clients agree to:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Provide accurate and complete information necessary for service delivery</li>
                        <li>Implement recommended risk management strategies in good faith</li>
                        <li>Maintain appropriate insurance coverage as advised</li>
                        <li>Comply with all applicable laws and regulations</li>
                        <li>Pay fees according to the agreed-upon payment terms</li>
                    </ul>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Confidentiality</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We maintain strict confidentiality regarding all client information and business operations. Both parties agree to protect confidential information disclosed during the engagement, except as required by law or with explicit written consent.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Limitation of Liability</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        To the maximum extent permitted by law, Seneca Risk shall not be liable for any indirect, incidental, special, consequential, or punitive damages resulting from your use of our services. Our total liability shall not exceed the fees paid for the specific services giving rise to the claim.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Intellectual Property</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        All methodologies, frameworks, tools, and materials developed by Seneca Risk remain our intellectual property. Clients receive a limited license to use deliverables for their internal business purposes only.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Termination</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Either party may terminate an engagement according to the terms specified in the individual service agreement. Termination does not relieve the client of payment obligations for services rendered prior to termination.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Changes to Terms</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We reserve the right to modify these terms at any time. We will notify clients of material changes via email or through our website. Continued use of our services after changes constitutes acceptance of the modified terms.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Governing Law</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        These Terms shall be governed by and construed in accordance with applicable laws, without regard to conflict of law provisions.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Contact Information</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        For questions about these Terms of Service, please contact us at:
                    </p>
                    <p class="text-gray-700 leading-relaxed">
                        <a href="/contact" class="text-primary-600 hover:text-primary-700 transition-colors">Contact Seneca Risk</a>
                    </p>
                </section>
            </div>
        </div>
    </div>
    
    <Footer />
</main>

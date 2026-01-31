<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <div class="pt-32 pb-24 px-6 md:px-12">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight mb-8 text-black">
                Privacy Policy
            </h1>
            
            <div class="prose prose-lg max-w-none">
                <p class="text-gray-600 mb-8">Last updated: {new Date().toLocaleDateString('en-US', { year: 'numeric', month: 'long', day: 'numeric' })}</p>
                
                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Introduction</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        Seneca Risk ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you visit our website or use our services.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Information We Collect</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We collect information that you provide directly to us, including:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Name, email address, phone number, and company information</li>
                        <li>Information about your business operations and risk management needs</li>
                        <li>Communications you send to us</li>
                        <li>Information collected through cookies and similar technologies</li>
                    </ul>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">How We Use Your Information</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We use the information we collect to:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Provide, maintain, and improve our risk management services</li>
                        <li>Respond to your inquiries and provide customer support</li>
                        <li>Send you technical notices, updates, and administrative messages</li>
                        <li>Communicate with you about services, offers, and events</li>
                        <li>Analyze usage patterns and improve our website and services</li>
                    </ul>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Information Sharing</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We do not sell your personal information. We may share your information with:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Service providers who assist in our operations</li>
                        <li>Insurance carriers and brokers when necessary for service delivery</li>
                        <li>Professional advisors and consultants</li>
                        <li>Law enforcement or regulatory authorities when required by law</li>
                    </ul>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Data Security</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        We implement appropriate technical and organizational measures to protect your information against unauthorized access, alteration, disclosure, or destruction. However, no method of transmission over the internet is 100% secure.
                    </p>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Your Rights</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        You have the right to:
                    </p>
                    <ul class="list-disc pl-6 text-gray-700 space-y-2 mb-4">
                        <li>Access and receive a copy of your personal information</li>
                        <li>Request correction of inaccurate information</li>
                        <li>Request deletion of your information</li>
                        <li>Object to or restrict certain processing of your information</li>
                        <li>Opt-out of marketing communications</li>
                    </ul>
                </section>

                <section class="mb-12">
                    <h2 class="text-2xl font-semibold mb-4 text-black">Contact Us</h2>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        If you have questions about this Privacy Policy or our privacy practices, please contact us at:
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

<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-gradient-to-b from-gray-50 to-white">
    <Navbar />
    <div class="pt-32 pb-24 px-6 md:px-12 max-w-[1400px] mx-auto">
        <!-- Header Section -->
        <div class="text-center mb-16">
            <h1 class="text-5xl md:text-7xl font-semibold mb-6">Schedule Assessment</h1>
            <p class="text-xl text-gray-600 max-w-2xl mx-auto">Get started with a comprehensive risk assessment. Our team will respond within 24 hours to discuss how we can reduce your total cost of risk.</p>
        </div>
        
        <!-- Two Column Layout -->
        <div class="grid md:grid-cols-2 gap-12 lg:gap-16 max-w-6xl mx-auto">
            <!-- Contact Information -->
            <div class="space-y-8">
                <div>
                    <h2 class="text-3xl font-semibold mb-6">Get in touch</h2>
                    <p class="text-gray-600 text-lg leading-relaxed mb-8">
                        Whether you're looking to reduce insurance premiums, prevent operational losses, or build a stronger safety culture, we're here to help.
                    </p>
                </div>

                <div class="space-y-6">
                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-primary-100 flex items-center justify-center flex-shrink-0">
                            <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                            </svg>
                        </div>
                        <div>
                            <h3 class="font-semibold text-lg mb-1">Email</h3>
                            <a href="mailto:contact@senecarisk.com" class="text-gray-600 hover:text-primary-600 transition-colors">contact@senecarisk.com</a>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-primary-100 flex items-center justify-center flex-shrink-0">
                            <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <div>
                            <h3 class="font-semibold text-lg mb-1">Response time</h3>
                            <p class="text-gray-600">Within 24 hours</p>
                        </div>
                    </div>

                    <div class="flex items-start gap-4">
                        <div class="w-12 h-12 bg-primary-100 flex items-center justify-center flex-shrink-0">
                            <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                            </svg>
                        </div>
                        <div>
                            <h3 class="font-semibold text-lg mb-1">What to expect</h3>
                            <p class="text-gray-600">Initial consultation to understand your risk profile and identify opportunities</p>
                        </div>
                    </div>
                </div>

                <div class="pt-8 border-t border-gray-200">
                    <p class="text-sm text-gray-500 leading-relaxed">
                        Typical clients achieve 15-30% reduction in total risk costs within 18 months through our comprehensive approach to risk management.
                    </p>
                </div>
            </div>

            <!-- Contact Form -->
            <div class="bg-white p-8 md:p-10 border border-gray-200 shadow-sm">
                <form class="space-y-6">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div>
                            <label for="firstName" class="block text-sm font-semibold text-gray-900 mb-2">First name</label>
                            <input 
                                type="text" 
                                id="firstName" 
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all" 
                                required
                            />
                        </div>
                        <div>
                            <label for="lastName" class="block text-sm font-semibold text-gray-900 mb-2">Last name</label>
                            <input 
                                type="text" 
                                id="lastName" 
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all" 
                                required
                            />
                        </div>
                    </div>

                    <div>
                        <label for="email" class="block text-sm font-semibold text-gray-900 mb-2">Work email</label>
                        <input 
                            type="email" 
                            id="email" 
                            class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all" 
                            required
                        />
                    </div>

                    <div>
                        <label for="company" class="block text-sm font-semibold text-gray-900 mb-2">Company</label>
                        <input 
                            type="text" 
                            id="company" 
                            class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all" 
                            required
                        />
                    </div>

                    <div>
                        <label for="industry" class="block text-sm font-semibold text-gray-900 mb-2">Industry</label>
                        <select 
                            id="industry" 
                            class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all bg-white"
                            required
                        >
                            <option value="">Select your industry</option>
                            <option value="manufacturing">Manufacturing</option>
                            <option value="construction">Construction</option>
                            <option value="logistics">Logistics & Transportation</option>
                            <option value="other">Other</option>
                        </select>
                    </div>

                    <div>
                        <label for="message" class="block text-sm font-semibold text-gray-900 mb-2">Tell us about your needs</label>
                        <textarea 
                            id="message" 
                            rows="5" 
                            class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-2 focus:ring-primary-100 focus:outline-none transition-all resize-none"
                            placeholder="What challenges are you facing with risk management?"
                        ></textarea>
                    </div>

                    <button 
                        type="submit" 
                        class="w-full bg-primary-600 text-white px-8 py-4 text-base font-semibold hover:bg-primary-700 transition-all hover:shadow-lg"
                    >
                        Request Assessment
                    </button>

                    <p class="text-xs text-gray-500 text-center">
                        By submitting this form, you agree to our privacy policy and terms of service.
                    </p>
                </form>
            </div>
        </div>
    </div>
    <Footer />
</main>

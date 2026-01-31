<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";

    let formData = $state({
        companyName: '',
        contactName: '',
        email: '',
        phone: '',
        revenue: '',
        industry: '',
        currentChallenges: '',
        insurancePremium: '',
        claimsHistory: ''
    });

    const industries = [
        'Manufacturing',
        'Construction',
        'Logistics & Transportation',
        'Healthcare',
        'Retail',
        'Technology',
        'Other'
    ];

    const revenueRanges = [
        'Under $50M',
        '$50M - $100M',
        '$100M - $250M',
        '$250M - $500M',
        'Over $500M'
    ];

    function handleSubmit(e: Event) {
        e.preventDefault();
        // Form submission logic would go here
        console.log('Form submitted:', formData);
    }
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    
    <!-- Hero Section -->
    <section class="pt-32 pb-16 px-6 md:px-12 bg-gray-900 text-white">
        <div class="max-w-[1400px] mx-auto">
            <div class="max-w-3xl">
                <div class="flex items-center gap-2 mb-6">
                    <div class="w-2 h-2 bg-primary-600"></div>
                    <span class="text-[10px] font-mono font-bold tracking-wider text-gray-400 uppercase">Risk Optimization</span>
                </div>
                
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight mb-6">
                    Optimize your risk profile
                </h1>
                
                <p class="text-xl text-gray-400 leading-relaxed mb-8">
                    Schedule a complimentary risk assessment to identify opportunities for reducing your total cost of risk by 15-30% within 18 months.
                </p>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 pt-8 border-t border-gray-800">
                    <div>
                        <div class="text-3xl font-bold mb-2">15-30%</div>
                        <div class="text-sm text-gray-400">Average cost reduction</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold mb-2">18 months</div>
                        <div class="text-sm text-gray-400">Typical engagement timeline</div>
                    </div>
                    <div>
                        <div class="text-3xl font-bold mb-2">$50M+</div>
                        <div class="text-sm text-gray-400">Target company revenue</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Assessment Form -->
    <section class="py-24 px-6 md:px-12">
        <div class="max-w-4xl mx-auto">
            <div class="mb-12">
                <h2 class="text-3xl font-semibold mb-4 text-black">Request your risk assessment</h2>
                <p class="text-gray-600 leading-relaxed">
                    Complete this form to schedule your complimentary risk assessment. We'll analyze your current risk profile and identify specific opportunities for cost reduction and operational improvement.
                </p>
            </div>

            <form onsubmit={handleSubmit} class="space-y-8">
                <!-- Company Information -->
                <div class="border-b border-gray-200 pb-8">
                    <h3 class="text-xl font-semibold mb-6 text-black">Company Information</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="companyName" class="block text-sm font-medium text-gray-700 mb-2">
                                Company Name *
                            </label>
                            <input
                                type="text"
                                id="companyName"
                                bind:value={formData.companyName}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            />
                        </div>

                        <div>
                            <label for="industry" class="block text-sm font-medium text-gray-700 mb-2">
                                Industry *
                            </label>
                            <select
                                id="industry"
                                bind:value={formData.industry}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            >
                                <option value="">Select industry</option>
                                {#each industries as industry}
                                    <option value={industry}>{industry}</option>
                                {/each}
                            </select>
                        </div>

                        <div>
                            <label for="revenue" class="block text-sm font-medium text-gray-700 mb-2">
                                Annual Revenue *
                            </label>
                            <select
                                id="revenue"
                                bind:value={formData.revenue}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            >
                                <option value="">Select revenue range</option>
                                {#each revenueRanges as range}
                                    <option value={range}>{range}</option>
                                {/each}
                            </select>
                        </div>

                        <div>
                            <label for="insurancePremium" class="block text-sm font-medium text-gray-700 mb-2">
                                Annual Insurance Premium
                            </label>
                            <input
                                type="text"
                                id="insurancePremium"
                                bind:value={formData.insurancePremium}
                                placeholder="e.g., $500,000"
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            />
                        </div>
                    </div>
                </div>

                <!-- Contact Information -->
                <div class="border-b border-gray-200 pb-8">
                    <h3 class="text-xl font-semibold mb-6 text-black">Contact Information</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="contactName" class="block text-sm font-medium text-gray-700 mb-2">
                                Your Name *
                            </label>
                            <input
                                type="text"
                                id="contactName"
                                bind:value={formData.contactName}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            />
                        </div>

                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-2">
                                Email Address *
                            </label>
                            <input
                                type="email"
                                id="email"
                                bind:value={formData.email}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            />
                        </div>

                        <div class="md:col-span-2">
                            <label for="phone" class="block text-sm font-medium text-gray-700 mb-2">
                                Phone Number *
                            </label>
                            <input
                                type="tel"
                                id="phone"
                                bind:value={formData.phone}
                                required
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors"
                            />
                        </div>
                    </div>
                </div>

                <!-- Risk Profile -->
                <div class="pb-8">
                    <h3 class="text-xl font-semibold mb-6 text-black">Current Risk Profile</h3>
                    <div class="space-y-6">
                        <div>
                            <label for="currentChallenges" class="block text-sm font-medium text-gray-700 mb-2">
                                What are your current risk management challenges? *
                            </label>
                            <textarea
                                id="currentChallenges"
                                bind:value={formData.currentChallenges}
                                required
                                rows="4"
                                placeholder="e.g., Rising insurance premiums, frequent workplace incidents, supply chain vulnerabilities..."
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors resize-none"
                            ></textarea>
                        </div>

                        <div>
                            <label for="claimsHistory" class="block text-sm font-medium text-gray-700 mb-2">
                                Brief claims history (past 3 years)
                            </label>
                            <textarea
                                id="claimsHistory"
                                bind:value={formData.claimsHistory}
                                rows="3"
                                placeholder="Describe any significant claims or loss trends..."
                                class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:ring-1 focus:ring-primary-600 outline-none transition-colors resize-none"
                            ></textarea>
                        </div>
                    </div>
                </div>

                <!-- Submit Button -->
                <div class="flex items-center justify-between pt-8 border-t border-gray-200">
                    <p class="text-sm text-gray-600">
                        * Required fields
                    </p>
                    <button
                        type="submit"
                        class="bg-primary-600 text-white px-8 py-4 text-sm font-semibold uppercase tracking-wide hover:bg-primary-700 transition-colors"
                    >
                        Request Assessment
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- What to Expect -->
    <section class="py-24 px-6 md:px-12 bg-gray-50">
        <div class="max-w-[1400px] mx-auto">
            <h2 class="text-3xl font-semibold mb-12 text-black text-center">What to expect</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-8 border border-gray-200">
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-2 h-2 bg-primary-600"></div>
                        <span class="text-[10px] font-mono font-bold tracking-wider text-gray-600 uppercase">Step 1</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-black">Initial Consultation</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        We'll schedule a 30-minute call to understand your risk profile, current challenges, and business objectives.
                    </p>
                </div>

                <div class="bg-white p-8 border border-gray-200">
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-2 h-2 bg-primary-600"></div>
                        <span class="text-[10px] font-mono font-bold tracking-wider text-gray-600 uppercase">Step 2</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-black">Comprehensive Assessment</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Our team conducts a thorough analysis of your operations, insurance program, and loss history to identify opportunities.
                    </p>
                </div>

                <div class="bg-white p-8 border border-gray-200">
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-2 h-2 bg-primary-600"></div>
                        <span class="text-[10px] font-mono font-bold tracking-wider text-gray-600 uppercase">Step 3</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-3 text-black">Actionable Recommendations</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Receive a detailed report with specific recommendations and projected ROI for risk reduction initiatives.
                    </p>
                </div>
            </div>
        </div>
    </section>
    
    <Footer />
</main>

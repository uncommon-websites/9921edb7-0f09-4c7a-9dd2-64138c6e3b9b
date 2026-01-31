<script lang="ts">
    const currentYear = new Date().getFullYear();
</script>

<footer class="bg-gray-900 text-white py-20 px-6 md:px-12">
    <div class="max-w-[1400px] mx-auto">
        <!-- Main Footer Content -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-12 mb-16">
            <!-- Company Info -->
            <div>
                <div class="flex items-center gap-3 mb-6">
                    <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
                        <path d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z" fill="currentColor"/>
                    </svg>
                    <span class="text-lg font-bold tracking-[0.15em] uppercase font-display">SENECA RISK</span>
                </div>
                <p class="text-gray-400 text-sm leading-relaxed mb-6">
                    Transforming operational vulnerability into strategic resilience through proactive risk management.
                </p>
                <div class="text-xs font-mono text-gray-500 uppercase tracking-wider">
                    Prevention First
                </div>
            </div>

            <!-- Services -->
            <div>
                <h3 class="text-sm font-semibold uppercase tracking-wider mb-6">Services</h3>
                <ul class="space-y-3">
                    <li><a href="/services" class="text-gray-400 hover:text-white transition-colors text-sm">Risk Assessment</a></li>
                    <li><a href="/services" class="text-gray-400 hover:text-white transition-colors text-sm">Loss Control Programs</a></li>
                    <li><a href="/services" class="text-gray-400 hover:text-white transition-colors text-sm">Safety Culture Training</a></li>
                    <li><a href="/services" class="text-gray-400 hover:text-white transition-colors text-sm">Insurance Optimization</a></li>
                </ul>
            </div>

            <!-- Company -->
            <div>
                <h3 class="text-sm font-semibold uppercase tracking-wider mb-6">Company</h3>
                <ul class="space-y-3">
                    <li><a href="/about" class="text-gray-400 hover:text-white transition-colors text-sm">About us</a></li>
                    <li><a href="/approach" class="text-gray-400 hover:text-white transition-colors text-sm">Stoic Framework</a></li>
                    <li><a href="/contact" class="text-gray-400 hover:text-white transition-colors text-sm">Contact</a></li>
                </ul>
            </div>

            <!-- Contact -->
            <div>
                <h3 class="text-sm font-semibold uppercase tracking-wider mb-6">Get Started</h3>
                <p class="text-gray-400 text-sm leading-relaxed mb-6">
                    Ready to reduce your total cost of risk by 15-30%?
                </p>
                <a href="/contact" class="inline-block bg-primary-600 text-white px-6 py-3 text-xs font-semibold uppercase tracking-wide hover:bg-primary-700 transition-colors">
                    Schedule Assessment
                </a>
            </div>
        </div>

        <!-- Bottom Bar -->
        <div class="pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center gap-4">
            <div class="text-xs text-gray-500">
                © {currentYear} Seneca Risk. All rights reserved.
            </div>
            <div class="flex gap-6 text-xs text-gray-500">
                <a href="#" class="hover:text-white transition-colors">Privacy Policy</a>
                <a href="#" class="hover:text-white transition-colors">Terms of Service</a>
            </div>
        </div>
    </div>
</footer>

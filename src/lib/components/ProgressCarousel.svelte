<script lang="ts">
    let currentSlide = $state(0);
    
    const slides = [
        {
            image: "https://images.unsplash.com/photo-1581094794329-c8112a89af12?q=80&w=2070&auto=format&fit=crop",
            title: "Risk Assessment",
            step: "Step 1",
            description: "We conduct comprehensive risk assessments to identify vulnerabilities in your operations, from workplace safety to supply chain exposures. Our team analyzes your total cost of risk, not just insurance premiums."
        },
        {
            image: "https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?q=80&w=2940&auto=format&fit=crop",
            title: "Loss Control",
            step: "Step 2",
            description: "We implement targeted loss control programs and safety culture training that reduce incidents and claims. Our hands-on approach ensures sustainable behavioral change across your organization."
        },
        {
            image: "https://images.unsplash.com/photo-1581092160562-40aa08e78837?q=80&w=2070&auto=format&fit=crop",
            title: "Insurance Optimization",
            step: "Step 3",
            description: "We optimize your insurance program structure and negotiate with carriers from a position of strength, backed by demonstrated risk improvements. This typically reduces premiums by 15-30%."
        }
    ];
    
    function nextSlide() {
        currentSlide = (currentSlide + 1) % slides.length;
    }
    
    function prevSlide() {
        currentSlide = (currentSlide - 1 + slides.length) % slides.length;
    }
</script>

<section class="bg-white py-24 px-6 md:px-12 overflow-hidden">
    <div class="max-w-[1400px] mx-auto">
        <h2 class="text-4xl md:text-5xl lg:text-6xl font-semibold leading-[1.05] tracking-tight mb-16 text-black">
            Our approach to<br />
            risk management
        </h2>

        <!-- Carousel Container -->
        <div class="relative w-full overflow-hidden">
            <div class="flex gap-6 transition-transform duration-500 ease-out" style="transform: translateX(calc(-{currentSlide * 100}% - {currentSlide * 24}px))">
                {#each slides as slide, index}
                    <div class="relative w-full md:w-[85%] shrink-0 aspect-[16/9] bg-gray-900 group">
                        <img src={slide.image} alt={slide.title} class="w-full h-full object-cover opacity-80 group-hover:opacity-100 transition-opacity duration-500" />
                        
                        <!-- Overlay Card -->
                        <div class="absolute bottom-0 left-0 p-8 md:p-12 w-full md:w-1/2 bg-gradient-to-t from-black/80 via-black/40 to-transparent md:bg-none">
                            <div class="flex items-center gap-2 mb-4">
                                <div class="w-2 h-2 bg-white"></div>
                                <span class="text-[10px] font-mono font-bold tracking-wider text-white uppercase">{slide.title}</span>
                            </div>
                            
                            <div class="text-[10px] font-mono text-gray-400 mb-4 uppercase tracking-wider">{slide.step}</div>
                            
                            <p class="text-white text-lg leading-relaxed mb-8">
                                {slide.description}
                            </p>
                            
                            <a href="/services" class="flex items-center gap-2 text-sm font-medium text-white hover:opacity-70 transition-opacity group/link">
                                <span class="text-xs group-hover/link:translate-x-1 transition-transform duration-300">›</span>
                                Learn more
                            </a>
                        </div>
                    </div>
                {/each}
            </div>
        </div>

        <!-- Controls -->
        <div class="flex flex-col md:flex-row items-end md:items-center justify-between mt-8 pt-8 border-t border-gray-200 gap-6">
            <div class="text-[10px] font-mono text-gray-500 uppercase tracking-wider max-w-xs leading-relaxed">
                Our proven methodology reduces total cost of risk by 15-30% within 18 months through prevention-focused strategies.
            </div>

            <!-- Progress Bar -->
            <div class="flex-1 w-full flex items-center justify-center px-4 md:px-12">
                <div class="flex gap-1">
                    {#each slides as _, index}
                        <div class={[
                            'transition-all duration-300',
                            index === currentSlide ? 'w-8 h-4 bg-primary-600' : 'w-1 h-2 bg-gray-300'
                        ]}></div>
                    {/each}
                </div>
            </div>

            <!-- Arrows -->
            <div class="flex gap-2">
                <button onclick={prevSlide} class="w-10 h-10 bg-[#B0A89E] hover:bg-[#9e968d] transition-colors flex items-center justify-center text-white disabled:opacity-50" disabled={currentSlide === 0}>
                    <span class="text-xl">‹</span>
                </button>
                <button onclick={nextSlide} class="w-10 h-10 bg-[#B0A89E] hover:bg-[#9e968d] transition-colors flex items-center justify-center text-white disabled:opacity-50" disabled={currentSlide === slides.length - 1}>
                    <span class="text-xl">›</span>
                </button>
            </div>
        </div>
    </div>
</section>

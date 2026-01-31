<script lang="ts">
    import { onMount } from 'svelte';

    let isScrolled = false;

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 50;
        };

        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 w-full z-50 px-6 py-5 flex items-center justify-between transition-all duration-300 {isScrolled ? 'bg-white text-black py-4 shadow-sm' : 'bg-white text-black shadow-sm'}">
    <!-- Logo -->
    <div class="flex items-center">
        <a href="/" class="flex items-center gap-3">
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
                <path d="M12 2L13.2 9.92154L20.6603 7L14.4 12L20.6603 17L13.2 14.0785L12 22L10.8 14.0785L3.33975 17L9.6 12L3.33975 7L10.8 9.92154L12 2Z" fill="currentColor"/>
            </svg>
            <span class="text-xl font-bold tracking-[0.15em] uppercase font-display">SENECA RISK</span>
        </a>
    </div>

    <!-- Center Links -->
    <div class="hidden lg:flex items-center gap-8 text-sm font-medium tracking-wide">
        <a href="/services" class="hover:opacity-70 transition-opacity">Services</a>
        <a href="/approach" class="hover:opacity-70 transition-opacity">Stoic Framework</a>
        <a href="/about" class="hover:opacity-70 transition-opacity">About us</a>
        <a href="/contact" class="hover:opacity-70 transition-opacity">Contact</a>
    </div>

    <!-- Right Actions -->
    <div class="flex items-center gap-6">
        <a href="/resources" class="text-sm font-medium hover:opacity-70 transition-opacity hidden sm:block">CFO Resources</a>
        <a href="/optimize" class="bg-black text-white px-5 py-2.5 text-xs font-semibold uppercase tracking-wide hover:bg-gray-800 transition-colors">
            Optimize Risk Profile
        </a>
    </div>
</nav>

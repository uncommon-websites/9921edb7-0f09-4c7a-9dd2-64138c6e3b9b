<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    <div class="pt-32 pb-24 px-6 md:px-12 max-w-[1400px] mx-auto">
        <h1 class="text-5xl md:text-7xl font-semibold mb-8">Schedule Assessment</h1>
        <p class="text-xl text-gray-600 max-w-3xl mb-12">Get started with a comprehensive risk assessment.</p>
        
        <form class="max-w-2xl space-y-6">
            <div>
                <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
                <input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:outline-none" />
            </div>
            <div>
                <label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:outline-none" />
            </div>
            <div>
                <label for="company" class="block text-sm font-medium text-gray-700 mb-2">Company</label>
                <input type="text" id="company" class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:outline-none" />
            </div>
            <div>
                <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
                <textarea id="message" rows="5" class="w-full px-4 py-3 border border-gray-300 focus:border-primary-600 focus:outline-none"></textarea>
            </div>
            <button type="submit" class="bg-primary-600 text-white px-8 py-4 text-sm font-semibold hover:bg-primary-700 transition-colors">
                Submit Request
            </button>
        </form>
    </div>
    <Footer />
</main>

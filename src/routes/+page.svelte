<script lang="ts">
    import Header from '$lib/components/Header.svelte';
    import Hero from '$lib/components/Hero.svelte';
    import Features from '$lib/components/Features.svelte';
    import VideoSection from '$lib/components/VideoSection.svelte';
    import ComparisonTable from '$lib/components/ComparisonTable.svelte';
    import ProductCards from '$lib/components/ProductCards.svelte';
    import SecuritySection from '$lib/components/SecuritySection.svelte';
    import Testimonials from '$lib/components/Testimonials.svelte';
    import BusinessSection from '$lib/components/BusinessSection.svelte';
    import AppDownload from '$lib/components/AppDownload.svelte';
    import GlobalReach from '$lib/components/GlobalReach.svelte';
    import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen font-body text-wise-dark">
    <Header />
    <main>
        <Hero />
        <Features />
        <VideoSection />
        <ComparisonTable />
        <ProductCards />
        <SecuritySection />
        <Testimonials />
        <BusinessSection />
        <AppDownload />
        <GlobalReach />
    </main>
    <Footer />
</div>


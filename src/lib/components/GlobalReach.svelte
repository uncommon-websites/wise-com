<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-wise-bg-light">
    <div class="max-w-[1100px] mx-auto px-6">
        <h2 class="text-3xl md:text-4xl font-extrabold text-wise-dark mb-8">
            Wise works nearly everywhere
        </h2>

        <div class="flex gap-2 mb-10 overflow-x-auto pb-2">
            <button class="px-4 py-2 rounded-full bg-wise-green text-wise-dark font-semibold text-sm whitespace-nowrap">Send money</button>
            <button class="px-4 py-2 rounded-full border border-gray-300 text-wise-dark font-semibold text-sm whitespace-nowrap hover:bg-gray-100">Account details</button>
            <button class="px-4 py-2 rounded-full border border-gray-300 text-wise-dark font-semibold text-sm whitespace-nowrap hover:bg-gray-100">Hold and convert money</button>
        </div>

        <div class="grid grid-cols-2 md:grid-cols-4 gap-y-8 gap-x-4">
            {#each [
                { name: 'Australia', flag: 'au' },
                { name: 'Brazil', flag: 'br' },
                { name: 'Canada', flag: 'ca' },
                { name: 'China', flag: 'cn' },
                { name: 'Colombia', flag: 'co' },
                { name: 'Dubai', flag: 'ae' },
                { name: 'Europe', flag: 'eu' },
                { name: 'France', flag: 'fr' },
                { name: 'Germany', flag: 'de' },
                { name: 'India', flag: 'in' },
                { name: 'Indonesia', flag: 'id' },
                { name: 'Japan', flag: 'jp' },
                { name: 'Mexico', flag: 'mx' },
                { name: 'New Zealand', flag: 'nz' },
                { name: 'Philippines', flag: 'ph' },
                { name: 'South Korea', flag: 'kr' },
                { name: 'Spain', flag: 'es' },
                { name: 'Thailand', flag: 'th' },
                { name: 'United Arab Emirates', flag: 'ae' },
                { name: 'United Kingdom', flag: 'gb' }
            ] as country}
                <div class="flex flex-col items-start gap-3">
                    <div class="w-10 h-10 rounded-full overflow-hidden border border-gray-200">
                        <img src={`https://flagcdn.com/w80/${country.flag}.png`} alt={country.name} class="w-full h-full object-cover" />
                    </div>
                    <a href="#" class="text-sm font-bold text-wise-dark underline decoration-1 hover:no-underline">
                        Send money to {country.name === 'United Kingdom' ? 'the UK' : country.name}
                    </a>
                </div>
            {/each}
        </div>

        <div class="mt-12 text-center">
            <button class="w-12 h-12 rounded-full bg-wise-green flex items-center justify-center mx-auto mb-4 hover:bg-[#8fd663] transition-colors">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M19 9l-7 7-7-7" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
            </button>
            <a href="#" class="text-sm font-bold text-wise-dark underline decoration-1 hover:no-underline">Show all destinations</a>
        </div>
    </div>
</section>

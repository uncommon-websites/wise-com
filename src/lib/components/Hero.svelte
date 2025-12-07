<script>
    import Button from './Button.svelte';
</script>

<section class="relative bg-wise-green pt-32 pb-20 px-6 overflow-hidden">
    <div class="max-w-[1100px] mx-auto grid lg:grid-cols-2 gap-12 items-center">
        <!-- Left Content -->
        <div class="max-w-xl">
            <h1 class="text-5xl md:text-[56px] leading-[0.95] font-extrabold tracking-tight text-wise-dark mb-6">
                THE FAST WAY TO<br>SEND MONEY ABROAD
            </h1>
            <p class="text-lg md:text-[19px] leading-snug text-wise-dark mb-8 font-medium max-w-lg">
                Send money to family and friends. Make transfers with more certainty. Most arrive in under 20 seconds.<sup>1</sup> Deliver to 140+ countries.
            </p>
            <div class="hidden lg:block">
                <Button text="Sign up" variant="dark" className="!px-8 !py-3 text-base" />
            </div>
        </div>

        <!-- Right Content: Calculator -->
        <div class="bg-white rounded-3xl p-6 shadow-xl max-w-[460px] w-full mx-auto lg:ml-auto relative z-10">
            <!-- Input 1 -->
            <div class="mb-4">
                <div class="flex justify-between mb-2">
                    <label class="text-sm font-medium text-gray-600">You send exactly</label>
                    <div class="flex items-center gap-2 bg-gray-100 rounded-full px-3 py-1 cursor-pointer hover:bg-gray-200 transition-colors">
                        <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M12 15V3m0 12l-4-4m4 4l4-4M2 17l.621 2.485A2 2 0 0 0 4.561 21h14.878a2 2 0 0 0 1.94-1.515L22 17" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <span class="text-xs font-bold">Guaranteed for 10h</span>
                        <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                             <path d="M9 18l6-6-6-6" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                </div>
                <div class="flex">
                    <div class="flex-1 relative">
                        <input type="text" value="1,000.00" class="w-full text-2xl font-bold text-wise-dark outline-none border-b border-gray-300 focus:border-wise-green py-2 bg-transparent" />
                    </div>
                    <div class="flex items-center gap-2 pl-4 border-b border-gray-300 py-2 cursor-pointer hover:bg-gray-50">
                        <img src="https://flagcdn.com/w40/us.png" alt="USD" class="w-6 h-6 rounded-full object-cover" />
                        <span class="font-bold text-lg">USD</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" class="text-gray-400">
                             <path d="M6 9l6 6 6-6" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                </div>
            </div>

            <!-- Fees & Rate -->
            <div class="pl-4 border-l-2 border-gray-200 ml-3 my-4 space-y-3 py-1">
                <div class="flex justify-between items-center text-sm">
                    <div class="flex items-center gap-2">
                        <div class="w-6 h-6 rounded-full bg-gray-100 flex items-center justify-center text-gray-500">
                            <span class="font-bold text-xs">-</span>
                        </div>
                        <span class="font-bold text-wise-dark">5.48 USD</span>
                        <span class="text-gray-500">Total fees</span>
                    </div>
                    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-gray-400">
                        <path d="M9 18l6-6-6-6" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </div>
                 <div class="flex justify-between items-center text-sm">
                    <div class="flex items-center gap-2">
                        <div class="w-6 h-6 rounded-full bg-gray-100 flex items-center justify-center text-gray-500">
                            <span class="font-bold text-xs">÷</span>
                        </div>
                        <span class="font-bold text-wise-blue hover:underline cursor-pointer">0.93298</span>
                        <span class="text-gray-500">Exchange rate</span>
                    </div>
                </div>
            </div>

            <!-- Input 2 -->
            <div class="mb-6">
                <div class="flex justify-between mb-2">
                     <label class="text-sm font-medium text-gray-600">Recipient gets</label>
                </div>
                <div class="flex">
                    <div class="flex-1">
                        <input type="text" value="854.29" class="w-full text-2xl font-bold text-wise-dark outline-none border-b border-gray-300 focus:border-wise-green py-2 bg-transparent" />
                    </div>
                    <div class="flex items-center gap-2 pl-4 border-b border-gray-300 py-2 cursor-pointer hover:bg-gray-50">
                        <img src="https://flagcdn.com/w40/eu.png" alt="EUR" class="w-6 h-6 rounded-full object-cover" />
                        <span class="font-bold text-lg">EUR</span>
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" class="text-gray-400">
                             <path d="M6 9l6 6 6-6" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                </div>
            </div>

            <!-- Arrival Info -->
            <div class="mb-6">
                 <div class="flex items-start gap-3">
                    <div class="mt-1">
                        <span class="text-gray-900 font-bold text-sm">Should arrive</span>
                        <br>
                        <span class="text-wise-dark font-bold">in seconds</span>
                    </div>
                 </div>
            </div>

            <!-- Action Buttons -->
            <div class="space-y-4">
                <Button text="Send money" variant="primary" className="w-full !py-4 text-lg" />
                <div class="text-center">
                    <a href="#" class="text-sm font-semibold underline decoration-1 hover:no-underline text-wise-dark">View popular destinations</a>
                </div>
            </div>
        </div>
        
        <div class="lg:hidden text-center mt-6">
            <Button text="Sign up" variant="dark" className="!px-8 !py-3 text-base w-full" />
        </div>
    </div>

    <!-- Flags Row -->
    <div class="max-w-[1100px] mx-auto mt-16 flex justify-center gap-4 flex-wrap">
        {#each ['us', 'eu', 'gb', 'ca', 'in', 'mx', 'jp', 'th'] as country}
            <div class="w-12 h-12 rounded-full overflow-hidden border-4 border-white shadow-sm hover:scale-110 transition-transform cursor-pointer">
                <img src={`https://flagcdn.com/w80/${country === 'eu' ? 'eu' : country}.png`} alt={country} class="w-full h-full object-cover" />
            </div>
        {/each}
        <div class="w-12 h-12 rounded-full bg-wise-dark flex items-center justify-center border-4 border-white shadow-sm hover:scale-110 transition-transform cursor-pointer">
             <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2">
                <path d="M5 12h14M12 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </div>
    </div>
</section>

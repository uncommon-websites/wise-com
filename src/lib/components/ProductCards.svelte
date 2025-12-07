<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-white">
    <div class="max-w-[1100px] mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-4xl md:text-[56px] leading-[0.95] font-extrabold text-wise-dark mb-6">
                MAKE YOUR MONEY<br>DO MORE
            </h2>
            <p class="text-lg text-gray-600 max-w-2xl mx-auto mb-8">
                Spend, receive and manage money internationally, as easily as you do at home.
            </p>
            <Button text="Get Wise" variant="primary" />
        </div>

        <div class="grid md:grid-cols-3 gap-8">
            <!-- Card 1 -->
            <div class="bg-gray-100 rounded-3xl p-8 flex flex-col items-center text-center hover:shadow-lg transition-shadow">
                <div class="mb-6 relative">
                    <div class="w-32 h-20 bg-white rounded-xl shadow-sm border border-gray-200 flex items-center justify-center relative overflow-hidden">
                         <div class="absolute top-2 left-2 w-4 h-4 rounded-full bg-red-500"></div>
                         <div class="text-xl font-bold text-wise-dark">$4,122<span class="text-xs align-top">.00</span></div>
                    </div>
                </div>
                <h3 class="text-2xl font-bold text-wise-dark mb-3">Receive money fast</h3>
                <p class="text-gray-600 mb-6 flex-grow">
                    Get paid easily in other currencies with global account details.
                </p>
                <div class="flex items-center gap-2 mb-6">
                    <svg class="w-5 h-5 text-wise-dark" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span class="font-semibold underline">22 currencies</span>
                </div>
                <Button text="Explore getting paid" variant="outline" className="w-full !py-2 text-sm" />
            </div>

            <!-- Card 2 -->
            <div class="bg-gray-100 rounded-3xl p-8 flex flex-col items-center text-center hover:shadow-lg transition-shadow">
                <div class="mb-6">
                     <div class="w-40 h-24 bg-wise-green rounded-xl shadow-sm flex flex-col justify-between p-3 relative overflow-hidden">
                        <div class="flex justify-end">
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark opacity-50">
                                <path d="M2 10h20M2 14h20" />
                            </svg>
                        </div>
                        <div class="w-8 h-5 bg-yellow-400/50 rounded"></div>
                        <div class="absolute top-2 right-2">
                             <svg width="10" height="10" viewBox="0 0 24 24" fill="currentColor" class="text-wise-dark">
                                <path d="M22.3 0.600006L15.3 23.4H9.60001L5.90001 10.9L2.20001 23.4H-0.0999908L5.10001 5.90001H9.80001L13.5 18.3L17.2 5.90001H21.9L22.3 0.600006Z" />
                            </svg>
                        </div>
                     </div>
                </div>
                <h3 class="text-2xl font-bold text-wise-dark mb-3">Save on spending abroad</h3>
                <p class="text-gray-600 mb-6 flex-grow">
                    Pay and withdraw cash worldwide without any foreign transaction fees.
                </p>
                 <div class="flex items-center gap-2 mb-6">
                    <svg class="w-5 h-5 text-wise-dark" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span class="font-semibold underline">215 countries and territories</span>
                </div>
                <Button text="Learn about Wise cards" variant="outline" className="w-full !py-2 text-sm" />
            </div>

            <!-- Card 3 -->
            <div class="bg-gray-100 rounded-3xl p-8 flex flex-col items-center text-center hover:shadow-lg transition-shadow">
                <div class="mb-6">
                    <div class="w-32 h-20 bg-white rounded-xl shadow-sm border border-gray-200 flex items-center justify-center gap-2">
                        <img src="https://flagcdn.com/w40/us.png" alt="USD" class="w-6 h-6 rounded-full" />
                        <div class="flex flex-col text-left">
                            <span class="text-xl font-bold text-wise-dark">3.4%</span>
                            <span class="text-[10px] text-gray-500 uppercase font-bold">APY on USD</span>
                        </div>
                    </div>
                </div>
                <h3 class="text-2xl font-bold text-wise-dark mb-3">Receive interest*</h3>
                <p class="text-gray-600 mb-6 flex-grow">
                    Opt in and get passthrough FDIC insurance up to $250,000 through our Program Bank.<sup>2 3</sup>
                </p>
                 <div class="flex items-center gap-2 mb-6">
                    <svg class="w-5 h-5 text-wise-dark" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path></svg>
                    <span class="font-semibold underline">USD, GBP and EUR</span>
                </div>
                <Button text="See our interest feature" variant="outline" className="w-full !py-2 text-sm" />
            </div>
        </div>
        
        <p class="text-center text-gray-500 mt-12 text-sm">
            *Receive interest is not available to residents of New York and Alaska at this time.
        </p>
    </div>
</section>

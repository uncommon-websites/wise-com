<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-white">
    <div class="max-w-[1100px] mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-16 items-center">
            <!-- Image -->
            <div class="relative rounded-3xl overflow-hidden h-[500px] md:h-[600px] order-last md:order-first">
                <img src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Business meeting" class="w-full h-full object-cover" />
                
                <!-- Floating Elements -->
                <div class="absolute bottom-1/4 left-6 bg-white rounded-xl p-4 shadow-xl flex items-center gap-3 max-w-[200px]">
                    <div class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                            <path d="M12 19V5M5 12l7-7 7 7" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <div>
                        <div class="font-bold text-wise-dark">$13,450.00</div>
                        <div class="text-xs text-gray-500">Pay</div>
                    </div>
                </div>

                 <div class="absolute bottom-[15%] right-6 bg-white rounded-xl p-4 shadow-xl flex items-center gap-3 max-w-[200px]">
                    <div class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                             <path d="M12 5v14M5 12l7 7 7-7" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </div>
                    <div>
                        <div class="font-bold text-wise-dark">$104.99</div>
                        <div class="text-xs text-gray-500">Expenses</div>
                    </div>
                </div>
            </div>

            <!-- Content -->
            <div>
                <h2 class="text-4xl md:text-[56px] leading-[0.95] font-extrabold text-wise-dark mb-6">
                    BUILT FOR<br>BUSINESS TOO
                </h2>
                <p class="text-lg text-gray-600 mb-10">
                    Go global with our international business account. Make payments and get paid in 40+ currencies. Join over 700,000 businesses thriving with Wise.
                </p>

                <div class="flex gap-4">
                    <Button text="Try demo" variant="primary" />
                    <Button text="Learn more" variant="outline" className="!border-none !underline hover:!bg-transparent hover:!text-gray-600" />
                </div>
            </div>
        </div>
    </div>
</section>

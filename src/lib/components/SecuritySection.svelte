<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-white">
    <div class="max-w-[1100px] mx-auto px-6">
        <div class="grid md:grid-cols-2 gap-16 items-center">
            <!-- Image -->
            <div class="relative rounded-3xl overflow-hidden h-[500px] md:h-[600px]">
                <img src="https://images.unsplash.com/photo-1556155092-490a1ba16284?ixlib=rb-4.0.3&auto=format&fit=crop&w=1000&q=80" alt="Man sitting" class="w-full h-full object-cover" />
                
                <!-- Floating Element -->
                <div class="absolute bottom-1/3 left-10 bg-white rounded-full px-6 py-3 shadow-xl flex items-center gap-3">
                    <div class="w-8 h-8 rounded-full bg-wise-green flex items-center justify-center">
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" class="text-wise-dark">
                            <path d="M22.3 0.600006L15.3 23.4H9.60001L5.90001 10.9L2.20001 23.4H-0.0999908L5.10001 5.90001H9.80001L13.5 18.3L17.2 5.90001H21.9L22.3 0.600006Z" />
                        </svg>
                    </div>
                    <span class="font-bold text-wise-dark">24/7 customer support</span>
                </div>
            </div>

            <!-- Content -->
            <div>
                <h2 class="text-4xl md:text-[56px] leading-[0.95] font-extrabold text-wise-dark mb-6">
                    SAFE AT EVERY STEP
                </h2>
                <p class="text-lg text-gray-600 mb-10">
                    14.8 million customers, businesses and banks use Wise every day. They move $16 billion every month. Here's how we keep each dollar safe.
                </p>

                <div class="space-y-8">
                    <div class="flex gap-4">
                        <div class="w-12 h-12 flex-shrink-0 rounded-full bg-gray-100 flex items-center justify-center">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                                <path d="M3 21h18M5 21V7l8-4 8 4v14M5 10a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v11" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-wise-dark mb-1">Federally regulated</h3>
                            <p class="text-gray-600">Regulated nationwide, with 65 licences worldwide to keep your money moving.</p>
                        </div>
                    </div>

                    <div class="flex gap-4">
                        <div class="w-12 h-12 flex-shrink-0 rounded-full bg-gray-100 flex items-center justify-center">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                                <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-wise-dark mb-1">Safeguarded funds</h3>
                            <p class="text-gray-600">Your money is protected in a safeguarded, separate account.</p>
                        </div>
                    </div>

                    <div class="flex gap-4">
                        <div class="w-12 h-12 flex-shrink-0 rounded-full bg-gray-100 flex items-center justify-center">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                                <path d="M21 12V7H5a2 2 0 0 1 0-4h14v4" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M3 5v14a2 2 0 0 0 2 2h16v-5" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M18 9h2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-wise-dark mb-1">Specialized anti-fraud tech</h3>
                            <p class="text-gray-600">Over 1,000 experts and our smart systems run 7 million checks every day to spot and stop fraud.</p>
                        </div>
                    </div>
                </div>

                <div class="mt-10">
                    <Button text="See our security" variant="primary" />
                </div>
            </div>
        </div>
    </div>
</section>

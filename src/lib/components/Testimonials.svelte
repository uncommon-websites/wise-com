<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-white">
    <div class="max-w-[1100px] mx-auto px-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-12 gap-6">
            <div class="max-w-md">
                <h2 class="text-4xl md:text-[56px] leading-[0.95] font-extrabold text-wise-dark mb-6">
                    EXCELLENT<br>EVERYWHERE
                </h2>
                <p class="text-lg text-gray-600">
                    See the stories of people worldwide choosing Wise.
                </p>
            </div>
            <div class="flex gap-4">
                <button class="w-12 h-12 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200 transition-colors">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                        <path d="M15 19l-7-7 7-7" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </button>
                <button class="w-12 h-12 rounded-full bg-wise-green flex items-center justify-center hover:bg-[#8fd663] transition-colors">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" class="text-wise-dark">
                        <path d="M9 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
                    </svg>
                </button>
            </div>
        </div>

        <div class="flex gap-6 overflow-hidden">
            <!-- Testimonial 1 -->
            <div class="bg-wise-dark rounded-3xl p-8 min-w-[300px] md:min-w-[400px] flex-1 text-white flex flex-col justify-between h-[400px] relative overflow-hidden">
                <div class="absolute top-0 right-0 p-6 opacity-20">
                     <svg width="100" height="100" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M14.017 21L14.017 18C14.017 16.8954 14.9124 16 16.017 16H19.017C19.5693 16 20.017 15.5523 20.017 15V9C20.017 8.44772 19.5693 8 19.017 8H15.017C14.4647 8 14.017 8.44772 14.017 9V11C14.017 11.5523 13.5693 12 13.017 12H12.017V5H22.017V15C22.017 16.6569 20.6739 18 19.017 18H16.017C15.4647 18 15.017 18.4477 15.017 19V21H14.017ZM5.0166 21L5.0166 18C5.0166 16.8954 5.91203 16 7.0166 16H10.0166C10.5689 16 11.0166 15.5523 11.0166 15V9C11.0166 8.44772 10.5689 8 10.0166 8H6.0166C5.46432 8 5.0166 8.44772 5.0166 9V11C5.0166 11.5523 4.56889 12 4.0166 12H3.0166V5H13.0166V15C13.0166 16.6569 11.6735 18 10.0166 18H7.0166C6.46432 18 6.0166 18.4477 6.0166 19V21H5.0166Z" />
                    </svg>
                </div>
                
                <div class="relative z-10">
                    <div class="flex items-center gap-2 mb-6">
                        <img src="https://flagcdn.com/w40/us.png" alt="US" class="w-8 h-8 rounded-full border-2 border-white" />
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M5 12h14M12 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <img src="https://flagcdn.com/w40/in.png" alt="India" class="w-8 h-8 rounded-full border-2 border-white" />
                    </div>
                    
                    <blockquote class="text-2xl font-bold leading-tight mb-6">
                        "It is so quick. It took only 16 seconds to send money to India from USA."
                    </blockquote>
                    
                    <cite class="not-italic font-medium block mb-1">Samadrita T, United States</cite>
                </div>
                
                <div class="relative z-10">
                    <Button text="View on Trustpilot" variant="primary" className="!bg-wise-green !text-wise-dark hover:!bg-[#8fd663]" />
                </div>
            </div>

            <!-- Testimonial 2 (Partial) -->
            <div class="bg-wise-dark rounded-3xl p-8 min-w-[300px] md:min-w-[400px] flex-1 text-white flex flex-col justify-between h-[400px] relative overflow-hidden opacity-90">
                 <div class="absolute top-0 right-0 p-6 opacity-20">
                     <svg width="100" height="100" viewBox="0 0 24 24" fill="currentColor">
                        <path d="M14.017 21L14.017 18C14.017 16.8954 14.9124 16 16.017 16H19.017C19.5693 16 20.017 15.5523 20.017 15V9C20.017 8.44772 19.5693 8 19.017 8H15.017C14.4647 8 14.017 8.44772 14.017 9V11C14.017 11.5523 13.5693 12 13.017 12H12.017V5H22.017V15C22.017 16.6569 20.6739 18 19.017 18H16.017C15.4647 18 15.017 18.4477 15.017 19V21H14.017ZM5.0166 21L5.0166 18C5.0166 16.8954 5.91203 16 7.0166 16H10.0166C10.5689 16 11.0166 15.5523 11.0166 15V9C11.0166 8.44772 10.5689 8 10.0166 8H6.0166C5.46432 8 5.0166 8.44772 5.0166 9V11C5.0166 11.5523 4.56889 12 4.0166 12H3.0166V5H13.0166V15C13.0166 16.6569 11.6735 18 10.0166 18H7.0166C6.46432 18 6.0166 18.4477 6.0166 19V21H5.0166Z" />
                    </svg>
                </div>
                <div class="relative z-10">
                    <div class="flex items-center gap-2 mb-6">
                        <img src="https://flagcdn.com/w40/us.png" alt="US" class="w-8 h-8 rounded-full border-2 border-white" />
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M5 12h14M12 5l7 7-7 7" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <img src="https://flagcdn.com/w40/gb.png" alt="UK" class="w-8 h-8 rounded-full border-2 border-white" />
                    </div>
                     <blockquote class="text-2xl font-bold leading-tight mb-6">
                        "I have been using Wise for years to send money to the UK. Always fast and..."
                    </blockquote>
                     <cite class="not-italic font-medium block mb-1">John, United States</cite>
                </div>
                 <div class="relative z-10">
                    <Button text="View on Trustpilot" variant="primary" className="!bg-wise-green !text-wise-dark hover:!bg-[#8fd663]" />
                </div>
            </div>
        </div>
    </div>
</section>

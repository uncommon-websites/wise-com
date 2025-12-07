<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-white">
    <div class="max-w-[1100px] mx-auto px-6">
        <div class="bg-[#ff6060] rounded-[40px] p-12 md:p-20 relative overflow-hidden flex flex-col items-center text-center">
            <!-- Background Texture (Simplified) -->
            <div class="absolute inset-0 opacity-20 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')]"></div>
            
            <h2 class="text-4xl md:text-[64px] leading-[0.9] font-extrabold text-wise-dark mb-12 relative z-10 max-w-3xl">
                ONE SMART APP,<br>30+ MILLION DOWNLOADS
            </h2>

            <div class="flex flex-col md:flex-row items-center gap-8 relative z-10">
                 <div class="flex items-center gap-4 bg-white p-2 rounded-xl">
                    <div class="text-right text-xs font-bold text-wise-dark">
                        Scan to<br>get<br>Wise
                    </div>
                    <div class="w-16 h-16 bg-gray-900">
                        <!-- Placeholder QR Code -->
                        <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://wise.com" alt="QR Code" class="w-full h-full" />
                    </div>
                 </div>
                 
                 <div class="flex gap-4">
                    <button class="bg-black text-white rounded-lg px-4 py-2 flex items-center gap-2 hover:bg-gray-800 transition-colors">
                        <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M17.6 10.9l-1.3-7.6c1.6-.4 2.9-1.3 2.9-1.3s-2.3.1-4.7 1.4c-1.6.9-2.7 1.8-2.7 1.8s-.1-1.3-2.1-2.3C7.6 1.9 5.2 1.9 5.2 1.9s1.3 1 2.9 1.4l-1.3 7.6C3.9 12.3 2 15.6 2 15.6s1.6-.2 3.8-1.2c1.3-.6 2.3-1.2 2.3-1.2s.6 1.6 2.5 2.5c1.4.7 3.2.7 3.2.7s1.8 0 3.2-.7c1.9-.9 2.5-2.5 2.5-2.5s1 .6 2.3 1.2c2.2 1 3.8 1.2 3.8 1.2s-1.9-3.3-4.8-4.7z"/></svg>
                        <div class="text-left">
                            <div class="text-[10px] leading-none">Download on the</div>
                            <div class="text-sm font-bold leading-none">App Store</div>
                        </div>
                    </button>
                    <button class="bg-black text-white rounded-lg px-4 py-2 flex items-center gap-2 hover:bg-gray-800 transition-colors">
                        <svg class="w-6 h-6" viewBox="0 0 24 24" fill="currentColor"><path d="M3.6 21.6l12.5-6.9-3.6-3.4-11.2 5.8c-.5.3-.8.8-.8 1.4v.2c.1.9 1.1 1.6 2.1 1.1l1 .8zM2.8 3.5c-.1.3-.1.6-.1.9v14.2l9.9-5.1-9.8-10zM17.4 13.6l3.9 2.2c1.1.6 1.1 1.6 0 2.2l-1.3.7-4.8-2.7 2.2-2.4zM13.6 9.6l3.8-2.2-2.2-2.3-4.8 2.7 3.2 1.8z"/></svg>
                        <div class="text-left">
                            <div class="text-[10px] leading-none">GET IT ON</div>
                            <div class="text-sm font-bold leading-none">Google Play</div>
                        </div>
                    </button>
                 </div>
            </div>
        </div>
    </div>
</section>

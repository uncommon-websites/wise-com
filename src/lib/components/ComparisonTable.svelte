<script>
    import Button from './Button.svelte';
</script>

<section class="py-20 bg-wise-bg-light">
    <div class="max-w-[1100px] mx-auto px-6 text-center">
        <h2 class="text-4xl md:text-5xl font-extrabold text-wise-dark mb-6">100% TRANSPARENT PRICING</h2>
        <p class="text-lg text-gray-600 max-w-2xl mx-auto mb-8">
            Banks and other providers inflate the mid-market exchange rate to hide fees and make you pay more. Not Wise. You'll always get our stand-out rate, like the one on Google.
        </p>
        <div class="mb-12">
            <Button text="Send money now" variant="primary" />
        </div>

        <div class="bg-white rounded-3xl shadow-lg overflow-hidden max-w-4xl mx-auto">
            <!-- Table Header / Inputs -->
            <div class="p-6 border-b border-gray-200">
                <div class="flex flex-col md:flex-row gap-4 items-end">
                    <div class="flex-1 w-full text-left">
                        <label class="text-xs font-bold text-gray-500 mb-1 block">Amount</label>
                        <div class="relative">
                            <input type="text" value="1,000" class="w-full border border-gray-300 rounded-md px-3 py-2 font-bold text-wise-dark focus:border-wise-green focus:ring-1 focus:ring-wise-green outline-none" />
                        </div>
                    </div>
                    <div class="flex-1 w-full text-left">
                         <label class="text-xs font-bold text-gray-500 mb-1 block">From</label>
                        <div class="relative border border-gray-300 rounded-md px-3 py-2 flex items-center gap-2 bg-white">
                             <img src="https://flagcdn.com/w40/us.png" alt="USD" class="w-5 h-5 rounded-full" />
                             <span class="font-bold text-sm text-wise-dark">USD</span>
                             <span class="text-sm text-gray-500 truncate">United States dollar</span>
                             <svg class="ml-auto w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </div>
                    </div>
                    <div class="flex-1 w-full text-left">
                         <label class="text-xs font-bold text-gray-500 mb-1 block">To</label>
                        <div class="relative border border-gray-300 rounded-md px-3 py-2 flex items-center gap-2 bg-white">
                             <img src="https://flagcdn.com/w40/eu.png" alt="EUR" class="w-5 h-5 rounded-full" />
                             <span class="font-bold text-sm text-wise-dark">EUR</span>
                             <span class="text-sm text-gray-500 truncate">Euro</span>
                             <svg class="ml-auto w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Table Content -->
            <div class="overflow-x-auto">
                <table class="w-full text-left border-collapse min-w-[600px]">
                    <thead>
                        <tr>
                            <th class="p-4 w-1/5"></th>
                            <th class="p-4 w-1/5 bg-wise-green/30 text-center align-top border-t-4 border-wise-green relative">
                                <div class="flex flex-col items-center gap-2">
                                    <svg width="24" height="24" viewBox="0 0 105 24" fill="currentColor" class="text-wise-dark w-16 h-auto">
                                        <path d="M22.3 0.600006L15.3 23.4H9.60001L5.90001 10.9L2.20001 23.4H-0.0999908L5.10001 5.90001H9.80001L13.5 18.3L17.2 5.90001H21.9L22.3 0.600006ZM30.6 4.90001C29.2 4.90001 28.3 5.30001 27.8 5.70001V5.10001H23.5V23.4H27.8V13.8C27.8 11.2 28.8 9.00001 31.4 9.00001C31.5 9.00001 31.6 9.00001 31.8 9.00001V4.80001C31.4 4.80001 31 4.90001 30.6 4.90001ZM42.8 16.4C44.3 17.1 45.4 17.6 45.4 18.6C45.4 19.4 44.6 20 43.1 20C41.3 20 39.5 19.1 38.3 18.3L36.3 21.9C38.3 23.2 41.2 24.1 43.7 24.1C47.8 24.1 49.9 21.8 49.9 18.7C49.9 14.8 46.8 13.5 43.5 12.1C41.6 11.3 40.5 10.7 40.5 9.80001C40.5 9.00001 41.2 8.30001 42.6 8.30001C44.1 8.30001 45.6 9.00001 46.8 9.80001L48.6 6.10001C46.9 5.00001 44.7 4.30001 42.6 4.30001C38.9 4.30001 36.1 6.50001 36.1 10C36.1 13.4 39.1 14.8 42.8 16.4ZM62.9 17.1C63.1 16.5 63.3 15.8 63.3 14.7H54.4C54.5 17.7 56.9 19.9 59.8 19.9C61.5 19.9 62.9 19.2 64 18.3L66.3 21.8C64.6 23.3 62.3 24.1 59.6 24.1C54.3 24.1 50.1 20.3 50.1 14.5C50.1 8.80001 54.4 4.90001 59.3 4.90001C64.6 4.90001 67.7 9.10001 67.7 15.1C67.7 15.5 67.7 15.8 67.7 16L62.9 17.1ZM59.2 8.50001C57 8.50001 55.2 9.90001 54.6 11.9H63.3C63.1 9.90001 61.5 8.50001 59.2 8.50001ZM70.4 2.80001L75.6 0.600006L83.2 18.3H78.5L70.4 2.80001Z" fill="#163300"/>
                                    </svg>
                                </div>
                            </th>
                            <th class="p-4 w-1/5 text-center align-top">
                                <div class="flex flex-col items-center gap-2">
                                    <span class="font-bold text-red-600 text-sm">Bank of America</span>
                                </div>
                            </th>
                            <th class="p-4 w-1/5 text-center align-top">
                                <div class="flex flex-col items-center gap-2">
                                    <span class="font-bold text-red-600 text-sm">Wells Fargo</span>
                                </div>
                            </th>
                            <th class="p-4 w-1/5 text-center align-top">
                                <div class="flex flex-col items-center gap-2">
                                    <span class="font-bold text-blue-600 text-sm">PayPal</span>
                                </div>
                            </th>
                        </tr>
                    </thead>
                    <tbody class="text-sm">
                        <!-- Recipient gets -->
                        <tr>
                            <td class="p-4 text-gray-500 font-medium border-b border-gray-100">
                                Recipient gets<br>
                                <span class="text-xs text-gray-400">(Total after fees)</span>
                            </td>
                            <td class="p-4 text-center bg-wise-green/30 font-bold text-wise-dark border-b border-white">
                                854.29 EUR
                            </td>
                            <td class="p-4 text-center text-red-600 font-bold border-b border-gray-100">
                                835.57 EUR
                            </td>
                            <td class="p-4 text-center text-red-600 font-bold border-b border-gray-100">
                                820.07 EUR
                            </td>
                            <td class="p-4 text-center text-red-600 font-bold border-b border-gray-100">
                                818.32 EUR
                            </td>
                        </tr>
                        <!-- Exchange rate -->
                        <tr>
                            <td class="p-4 text-gray-500 font-medium border-b border-gray-100">
                                Exchange rate
                                <br><span class="text-xs text-gray-400">(1 USD -> EUR)</span>
                            </td>
                            <td class="p-4 text-center bg-wise-green/30 text-wise-dark border-b border-white">
                                0.858996
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                0.835574
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                0.820071
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                0.822420
                            </td>
                        </tr>
                        <!-- Exchange rate markup -->
                        <tr>
                            <td class="p-4 text-gray-500 font-medium border-b border-gray-100">
                                Exchange rate markup
                            </td>
                            <td class="p-4 text-center bg-wise-green/30 text-wise-dark font-bold border-b border-white">
                                0 USD <span class="inline-block w-3 h-3 rounded-full border border-wise-dark text-[8px] leading-3 text-center">?</span>
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                27.27 USD <span class="inline-block w-3 h-3 rounded-full border border-gray-400 text-[8px] leading-3 text-center">?</span>
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                45.31 USD <span class="inline-block w-3 h-3 rounded-full border border-gray-400 text-[8px] leading-3 text-center">?</span>
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                42.58 USD <span class="inline-block w-3 h-3 rounded-full border border-gray-400 text-[8px] leading-3 text-center">?</span>
                            </td>
                        </tr>
                        <!-- Transfer fee -->
                        <tr>
                            <td class="p-4 text-gray-500 font-medium border-b border-gray-100">
                                Transfer fee
                            </td>
                            <td class="p-4 text-center bg-wise-green/30 text-wise-dark border-b border-white">
                                5.48 USD
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                0 USD
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                0 USD
                            </td>
                            <td class="p-4 text-center text-gray-600 border-b border-gray-100">
                                4.99 USD
                            </td>
                        </tr>
                        <!-- Total transfer cost -->
                        <tr>
                            <td class="p-4 text-gray-500 font-medium">
                                Total transfer cost
                            </td>
                            <td class="p-4 text-center bg-wise-green/30 text-wise-dark font-bold">
                                5.48 USD
                            </td>
                            <td class="p-4 text-center text-gray-600">
                                27.27 USD
                            </td>
                            <td class="p-4 text-center text-gray-600">
                                45.31 USD
                            </td>
                            <td class="p-4 text-center text-gray-600">
                                47.57 USD
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
            
            <div class="p-4 bg-gray-50 text-center border-t border-gray-200">
                <a href="#" class="text-sm font-semibold text-wise-dark underline hover:no-underline">Show more providers</a>
            </div>
        </div>
        
        <p class="text-xs text-gray-500 mt-6">
            This applies when you pay in via ACH payments. <a href="#" class="underline hover:no-underline text-wise-dark">How do we collect this data?</a>
        </p>
    </div>
</section>

<script>
    import Button from './Button.svelte';
</script>

<header class="absolute top-0 left-0 w-full z-50 px-6 py-4 flex items-center justify-between max-w-[1440px] mx-auto left-0 right-0">
    <div class="flex items-center gap-8">
        <a href="/" class="text-wise-dark">
            <svg width="105" height="24" viewBox="0 0 105 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                <path d="M22.3 0.600006L15.3 23.4H9.60001L5.90001 10.9L2.20001 23.4H-0.0999908L5.10001 5.90001H9.80001L13.5 18.3L17.2 5.90001H21.9L22.3 0.600006ZM30.6 4.90001C29.2 4.90001 28.3 5.30001 27.8 5.70001V5.10001H23.5V23.4H27.8V13.8C27.8 11.2 28.8 9.00001 31.4 9.00001C31.5 9.00001 31.6 9.00001 31.8 9.00001V4.80001C31.4 4.80001 31 4.90001 30.6 4.90001ZM42.8 16.4C44.3 17.1 45.4 17.6 45.4 18.6C45.4 19.4 44.6 20 43.1 20C41.3 20 39.5 19.1 38.3 18.3L36.3 21.9C38.3 23.2 41.2 24.1 43.7 24.1C47.8 24.1 49.9 21.8 49.9 18.7C49.9 14.8 46.8 13.5 43.5 12.1C41.6 11.3 40.5 10.7 40.5 9.80001C40.5 9.00001 41.2 8.30001 42.6 8.30001C44.1 8.30001 45.6 9.00001 46.8 9.80001L48.6 6.10001C46.9 5.00001 44.7 4.30001 42.6 4.30001C38.9 4.30001 36.1 6.50001 36.1 10C36.1 13.4 39.1 14.8 42.8 16.4ZM62.9 17.1C63.1 16.5 63.3 15.8 63.3 14.7H54.4C54.5 17.7 56.9 19.9 59.8 19.9C61.5 19.9 62.9 19.2 64 18.3L66.3 21.8C64.6 23.3 62.3 24.1 59.6 24.1C54.3 24.1 50.1 20.3 50.1 14.5C50.1 8.80001 54.4 4.90001 59.3 4.90001C64.6 4.90001 67.7 9.10001 67.7 15.1C67.7 15.5 67.7 15.8 67.7 16L62.9 17.1ZM59.2 8.50001C57 8.50001 55.2 9.90001 54.6 11.9H63.3C63.1 9.90001 61.5 8.50001 59.2 8.50001ZM70.4 2.80001L75.6 0.600006L83.2 18.3H78.5L70.4 2.80001Z" fill="#163300"/>
            </svg>
        </a>
        <nav class="hidden lg:flex items-center gap-1">
            <a href="#" class="px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full">Personal</a>
            <a href="#" class="px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full">Business</a>
            <a href="#" class="px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full">Platform</a>
        </nav>
    </div>

    <div class="flex items-center gap-2">
        <button class="flex items-center gap-1 px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full">
            <span class="mr-1">🇬🇧</span> EN
        </button>
        <a href="#" class="px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full hidden sm:block">Help</a>
        <a href="#" class="px-3 py-2 text-sm font-semibold text-wise-dark hover:bg-black/5 rounded-full hidden sm:block">Log in</a>
        <Button text="Sign up" variant="dark" className="!px-4 !py-2 text-sm ml-2" />
        <button class="lg:hidden p-2">
            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M4 6H20M4 12H20M4 18H20" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </button>
    </div>
</header>

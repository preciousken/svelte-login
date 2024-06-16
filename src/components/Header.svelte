<script>
    function toggleMenu() {
        let menu = document.getElementById("main-menu");
        if (menu.style.display === "block") {
            menu.style.display = "none";
        } else {
            menu.style.display = "block";
        }
    }
</script>

<header
    class="bg-white shadow-md py-4 px-8 md:flex md:items-center md:justify-between"
>
    <!-- Logo -->
    <div class="text-lg font-bold px-4 md:px-4">
        <a href="/" class="text-blue-600">
            <img
                src="https://wgc.polo-static.com/static/img/logo.light.f713aad4.svg"
                alt="Poloniex Logo"
            />
        </a>
    </div>

    <!-- Mobile Menu Toggle Button -->
    <button
        class="block md:hidden"
        id="mobile-menu-toggle"
        on:click={toggleMenu}
    >
        <i class="fa-solid fa-bars text-gray-700">Menu</i>
    </button>

    <!-- Navigation Menu (hidden on mobile) -->
    <nav class=" md:flex md:space-x-6 md:flex-grow" id="main-menu">
        <div class="relative">
            <button
                class="flex items-center text-gray-700 hover:text-gray-900 focus:outline-none"
            >
                <span>Buy Crypto</span>
                <svg fill="currentColor" class="ml-1 w-4 h-4">
                    <use xlink:href="#uniframe-icon-arrow-down"></use>
                </svg>
            </button>
            <ul
                class="absolute left-0 mt-2 w-48 bg-white shadow-lg rounded-lg py-2 invisible"
            >
                <li>
                    <a
                        href="/cards/buy"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Buy Crypto</a
                    >
                </li>
                <li>
                    <a
                        href="/p2p/markets"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >P2P</a
                    >
                </li>
            </ul>
        </div>

        <a href="/markets" class="text-gray-700 hover:text-gray-900">Markets</a>

        <div class="relative">
            <button
                class="flex items-center text-gray-700 hover:text-gray-900 focus:outline-none"
            >
                <span>Trade</span>
                <svg fill="currentColor" class="ml-1 w-4 h-4">
                    <use xlink:href="#uniframe-icon-arrow-down"></use>
                </svg>
            </button>
            <ul
                class="absolute left-0 mt-2 w-48 bg-white shadow-lg rounded-lg py-2 invisible"
            >
                <li>
                    <a
                        href="/trade?type=spot"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Spot</a
                    >
                </li>
                <li>
                    <a
                        href="/trade?type=margin"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Margin</a
                    >
                </li>
                <li>
                    <a
                        href="/strategy/spot-grid/BTC_USDT"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Strategy Trading</a
                    >
                </li>
            </ul>
        </div>

        <div class="relative">
            <button
                class="flex items-center text-gray-700 hover:text-gray-900 focus:outline-none"
            >
                <span>Derivatives</span>
                <svg fill="currentColor" class="ml-1 w-4 h-4">
                    <use xlink:href="#uniframe-icon-arrow-down"></use>
                </svg>
            </button>
            <ul
                class="absolute left-0 mt-2 w-48 bg-white shadow-lg rounded-lg py-2 invisible"
            >
                <li>
                    <a
                        href="/futures/trade"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Futures Trading</a
                    >
                </li>
                <li>
                    <a
                        href="/strategy/futures-grid"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Grid Trading</a
                    >
                </li>
                <li>
                    <a
                        href="/strategy/copytrading"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Copy Trading</a
                    >
                </li>
            </ul>
        </div>

        <a href="/earn" class="text-gray-700 hover:text-gray-900">Earn</a>

        <div class="relative">
            <button
                class="flex items-center text-gray-700 hover:text-gray-900 focus:outline-none"
            >
                <span>Explore</span>
                <svg fill="currentColor" class="ml-1 w-4 h-4">
                    <use xlink:href="#uniframe-icon-arrow-down"></use>
                </svg>
            </button>
            <ul
                class="absolute left-0 mt-2 w-48 bg-white shadow-lg rounded-lg py-2 invisible"
            >
                <li>
                    <a
                        href="/topic/airdrop-token?utm_source=navbar"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Epic Airdrop</a
                    >
                </li>
                <li>
                    <a
                        href="/referral"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Referral</a
                    >
                </li>
                <li>
                    <a
                        href="/reward-center"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Reward Center</a
                    >
                </li>
                <li>
                    <a
                        href="/leaderboard"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Campaigns</a
                    >
                </li>
                <li>
                    <a
                        href="/launchbase"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >LaunchBase</a
                    >
                </li>
                <li>
                    <a
                        href="/feed"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >News</a
                    >
                </li>
                <li>
                    <a
                        href="/blog"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        >Poloniex Blog</a
                    >
                </li>
                <li>
                    <a
                        href="https://sunswap.com"
                        class="block px-4 py-2 text-sm text-gray-700 hover:bg-gray-100"
                        target="_blank">SunSwap</a
                    >
                </li>
            </ul>
        </div>

        <a href="https://apenft.io" class="text-gray-700 hover:text-gray-900"
            >NFT</a
        >
    </nav>

    <!-- Sign Up / Log In Buttons (hidden on mobile) -->
    <div class="hidden md:flex space-x-4 items-center">
        <button
            type="button"
            class="border bg-[#1a8f5c] text-[#ffffff] hover:text-[#1a8f5c] hover:bg-[#ffffff] hover:border-[#1a8f5c] px-4 py-2 rounded-md transition duration-200"
        >
            <a href="/signup">Sign Up</a>
        </button>
        <button
            type="button"
            class="border border-[#1a8f5c] text-[#1a8f5c] hover:text-white hover:bg-[#1a8f5c] px-4 py-2 rounded-md transition duration-200"
        >
            <a href="/login">Log In</a>
        </button>
        <i class="fa-solid fa-bell px-2 my-auto"></i>
        <i class="fa-solid fa-circle-half-stroke px-2 my-auto"></i>
        <i class="fa-solid fa-music px-2 my-auto"></i>
    </div>
</header>

<style>
    @media (max-width: 1180px) {
        #main-menu {
            display: none;
        }
    }
    .relative:hover .invisible {
        visibility: visible;
    }
</style>

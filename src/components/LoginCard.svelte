<div
    class="flex flex-col md:flex-row items-center justify-center gap-12 mx-auto"
>
    <!-- QR Code Column -->
    <div class="flex-1 flex items-center justify-center">
        <div class="bg-[#f5f9f5] p-8 rounded-lg w-full max-w-xl mx-auto">
            <div class="text-center mb-6">
                <div class="bg-[transparent] p-6 rounded-lg">
                    <img
                        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoXgnU7FduTcy0Z7GyoXnMnCqLBwMwAXdiFw&s"
                        alt="QR Code"
                        class="block mx-auto h-52 w-52 object-contain"
                    />
                </div>
            </div>
            <div class="text-center">
                <p class="text-gray-700 text-2xl font-semibold">
                    Login with QR code
                </p>
                <p class="text-sm">
                    Scan this code with the <span
                        class="text-[#1a8f5c] cursor-pointer">Poloniex app</span
                    > for a quick login
                </p>
            </div>
        </div>
    </div>

    <!-- Form Column -->
    <div class="flex-1 flex items-center justify-center">
        <div class="bg-white p-8 rounded-lg w-full max-w-xl mx-auto">
            <p class="text-3xl font-semibold mb-6 text-start">Account Login</p>
            <form class="order-form">
                <div class="mb-6">
                    <label
                        for="email"
                        class="block text-xs font-medium text-[grey]"
                    >
                        Email / Phone Number
                    </label>
                    <input
                        type="text"
                        id="email"
                        name="email"
                        class="polo-input error left polo-input-large polo-input-button w-full px-4 py-2 my-2 rounded-lg shadow-sm border focus:outline-none focus:ring-2 focus:ring-blue-600 focus:border-transparent"
                        placeholder="Email address or phone number"
                    />
                    <p class="text-red-500 text-xs mt-1">
                        Please enter your email address
                    </p>
                </div>
                <div class="text-center mb-6">
                    <button
                        type="submit"
                        class="polo-btn polo-btn-button polo-btn-primary polo-btn-large py-3 px-8 rounded-lg bg-black text-white hover:bg-gray-900 w-full transition duration-200"
                    >
                        Next
                    </button>
                </div>
                <p class="text-start text-sm mt-6">
                    Don't have an account? <a
                        href="/signup"
                        class="text-[#1a8f5c]">Sign up</a
                    >
                </p>
            </form>
            <div class="mt-6 flex justify-between">
                <!-- <div class="text-sm text-gray-600">Or other</div> -->
                <div class="cc314366 space-x-4">
                    <button
                        type="button"
                        class="polo-btn polo-btn-button polo-btn-secondary polo-btn-medium"
                    >
                        <svg
                            aria-hidden="true"
                            class="svgicon"
                            style="width: 40px; height: 40px; min-width: 40px;"
                        >
                            <use xlink:href="#oauth.1"></use>
                        </svg>
                    </button>
                    <button
                        type="button"
                        class="polo-btn polo-btn-button polo-btn-secondary polo-btn-medium"
                    >
                        <svg
                            aria-hidden="true"
                            class="svgicon"
                            style="width: 40px; height: 40px; min-width: 40px;"
                        >
                            <use xlink:href="#oauth.2"></use>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </div>
</div>

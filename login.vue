<template>
    <div class="flex items-center justify-center h-screen bg-gradient-to-r from-blue-200 via-pink-500 to-blue-200">
        <div class="border w-95 min-h-80 p-6 bg-slate-50 rounded-xl">
            <div class=" text-center py-10 ">
                <h1 class=" font-bold mb-0 mr-4 text-3xl">Login</h1>
            </div>
            <div class="">
                <!-- Input From -->
                <!--  from Login Email and password -->
                <div class="mb-2 border-rose-600">
                    <label for="email">Email</label>
                    <input type="email" name="email" id="email"
                        class="mt-1 block w-full px-3 py-2 border border-slate-300 rounded-md">
                </div>
                <div class="mb-3 border-rose-600">
                    <label for="email">Password</label>
                    <input type="password" name="password" id="password"
                        class="mt-1 block w-full px-3 py-2 border border-slate-300 rounded-md">
                </div>
                <div class="flex justify-between mb-6">
                <div class="flex items-center">
                    <!-- check box  -->
                    <input type="checkbox" name="remember" id="remember" aria-label="Remember me" class="mr-1 rounded-xl accent-violet-400">
				    <label for="remember" class="text-sm dark:text-gray-400">Remember me</label>
                </div>
                </div>
                <!-- button Login -->
                <button class="bg-gradient-to-r from-violet-500 via-indigo-300 to-fuchsia-500 w-full px-3 py-3 rounded shadow-md">Login</button>
                <p class="mt-9 w-full text-center">Or Login wite </p>
                <!-- Button -->
                <div class=" flex mt-8 space-x-2 rounded ">
                    <!-- <button class="border px-14 py-2">Google</button> -->
                    <button type="button" class="flex items-center justify-center space-x-2 border px-3 py-3 shadow-md">
                        <!-- icon Google -->
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" class="w-5 h-5 fill-current ">
                            <path
                                d="M16.318 13.714v5.484h9.078c-0.37 2.354-2.745 6.901-9.078 6.901-5.458 0-9.917-4.521-9.917-10.099s4.458-10.099 9.917-10.099c3.109 0 5.193 1.318 6.38 2.464l4.339-4.182c-2.786-2.599-6.396-4.182-10.719-4.182-8.844 0-16 7.151-16 16s7.156 16 16 16c9.234 0 15.365-6.49 15.365-15.635 0-1.052-0.115-1.854-0.255-2.651z">
                            </path>
                        </svg>
                        <p>Login with Google</p>
                    </button>
                    <!-- button Facebook -->
                    <button type="button" class="flex items-center justify-center space-x-3 border px-2 py-2 shadow-md">
                        <!-- icon facebook -->
                        <svg xmlns="http://www.w3.org/2000/svg" class="mr-2 h-4 w-4" fill="currentColor"
                            viewBox="0 0 24 24">
                            <path
                                d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z" />
                        </svg>
                        Login with Facebook
                    </button>
                </div>
            </div>

            <div class="text-center mt-24">
                <p>Not a member?<a href="/signup" class="underline ">Sign up new</a></p>
            </div>
        </div>
    </div>
    <div></div>
</template>

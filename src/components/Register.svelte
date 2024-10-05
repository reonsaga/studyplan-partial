<body>
    <div
        class="flex items-center justify-center min-h-screen bg-rose-200 dark:bg-gray-900"
    >
        <div
            class="relative flex flex-col m-6 space-y-8 bg-white shadow-2xl rounded-2xl md:flex-row md:space-y-0"
        >
            <!-- Input Side -->
            <div class="flex flex-col justify-center p-8 md:p-14">
                <h1
                    class="text-6xl font-bold italic text-gray-900 dark:text-white text-center"
                >
                    PlanTogether
                </h1>
                <div class="py-4">
                    <label
                        for="username"
                        class="block mb-2 text-md font-medium text-gray-900 dark:text-white"
                        >Username</label
                    >
                    <input
                        type="text"
                        class="w-full p-2 border border-gray-300 rounded-md placeholder:font-light placeholder:text-gray-500"
                        name="user"
                        id="user"
                        placeholder="Student"
                    />
                    <label
                        for="email"
                        class="block mt-2 mb-2 text-md font-medium text-gray-900 dark:text-white"
                        >E-mail Address</label
                    >
                    <input
                        type="text"
                        class="w-full p-2 border border-gray-300 rounded-md placeholder:font-light placeholder:text-gray-500"
                        name="email"
                        id="email"
                        placeholder="studyplan@company.com"
                    />
                    <label
                        for="email"
                        class="block mt-2 mb-2 text-md font-medium text-gray-900 dark:text-white"
                        >Confirm E-mail Address</label
                    >
                    <input
                        type="text"
                        class="w-full p-2 border border-gray-300 rounded-md placeholder:font-light placeholder:text-gray-500"
                        name="cemail"
                        id="cemail"
                        placeholder="studyplan@company.com"
                    />
                </div>
                <div>
                    <label
                        for="password"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Password</label
                    >
                    <input
                        type="password"
                        name="password"
                        id="password"
                        class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-0 focus:border-pink-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                        placeholder="••••••••"
                        required
                    />
                    <label
                        for="password"
                        class="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                        >Confirm Password</label
                    >
                    <input
                        type="cpassword"
                        name="cpassword"
                        id="cpassword"
                        class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-0 focus:border-pink-500 block w-full p-2.5 dark:bg-gray-600 dark:border-gray-500 dark:placeholder-gray-400 dark:text-white"
                        placeholder="••••••••"
                        required
                    />
                </div>
                <div class="flex justify-between w-full py-4">
                    <div class="flex items-center">
                        <div class="flex items-center">
                            <input
                                required
                                id="agree"
                                type="checkbox"
                                value=""
                                class="w-4 h-4 border border-gray-300 accent-pink-500 rounded bg-gray-50 focus:ring-3 focus:ring-pink-300 dark:bg-gray-700 dark:border-gray-600 dark:focus:ring-blue-600 dark:ring-offset-gray-800 dark:focus:ring-offset-gray-800"
                            />
                            <label
                                for="agree"
                                class="ml-2 text-sm font-medium text-gray-900 dark:text-gray-300 whitespace-nowrap"
                                >I Agree to the
                                <!--Link to Terms and Conditions-->
                                <a
                                    href="#"
                                    class="text-pink-500 hover:underline dark:text-blue-500"
                                    >Terms and Conditions</a
                                ></label
                            >
                        </div>
                    </div>
                </div>
                <button
                    type="submit"
                    class="w-full text-white bg-pink-500 hover:bg-pink-800 focus:ring-4 focus:outline-none focus:ring-pink-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
                    >Register</button
                >
                <div class="mt-2 text-center text-gray-400">
                    Already have an account?
                    <!--Link to Login Page-->
                    <a
                        href="#"
                        class="text-pink-500 hover:underline dark:text-blue-500"
                        >Login</a
                    >
                </div>
            </div>
            <!--Image Side-->
            <div class="relative">
                <img
                    src="src/lib/images/bg-login.png"
                    alt="img"
                    class="w-[400px] h-full hidden rounded-r-2xl md:block object-cover"
                />
            </div>
        </div>
    </div>
</body>

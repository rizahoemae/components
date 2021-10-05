<template>
    <div
        class="
            font-sans
            tracking-wide
            bg-gray-500 bg-opacity-60
            w-full
            min-h-screen
            flex
            h-full
            top-0
            backdrop-filter backdrop-blur-lg
        "
    >
        <link href="https://fonts.googleapis.com/css?family=Poppins" rel="stylesheet" />
        <div
            class="
                p-2
                bg-white
                z-10
                m-auto
                justify-center
                items-center
                md:w-2/5
                md:h-1/3
                xl:w-1/3 xl:h-1/3
                xs:w-1/2 xs:h-1/2
                rounded-3xl
                filter
                drop-shadow-2xl
                sm:w-1/2 sm:h-1/3 sm:rounded-xl
            "
        >
            <div class="flex p-1 mt-4 sm:mt-2 ml-4 sm:ml-4 mr-6 sm:mr-4 border-black items-center justify-between">
                <div class="flex">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-5 w-5 text-blue-400"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                    >
                        <path
                            fill-rule="evenodd"
                            d="M4 2a2 2 0 00-2 2v11a3 3 0 106 0V4a2 2 0 00-2-2H4zm1 14a1 1 0 100-2 1 1 0 000 2zm5-1.757l4.9-4.9a2 2 0 000-2.828L13.485 5.1a2 2 0 00-2.828 0L10 5.757v8.486zM16 18H9.071l6-6H16a2 2 0 012 2v2a2 2 0 01-2 2z"
                            clip-rule="evenodd"
                        />
                    </svg>
                    <p class="text-gray-600 tracking-wider ml-1 font-bold">Hehe</p>
                </div>
                <div class="flex">
                    <p class="text-gray-600 sm:hidden">
                        Have an account?
                    </p>
                    <a class="text-blue-600 ml-1" href="#">Log in</a>
                </div>
            </div>
            <div class="ml-6 md:ml-4 mr-6 md:mr-4 mt-8 mt:6">
                <h1 class="text-xl text-gray-600 font-bold">
                    Manage your freelance business with us!
                </h1>
                <p class="text-sm text-gray-400 mt-2 md:mt-1">
                    Takes less than 10 minutes to fill out all the information needed to register
                    your bussiness
                </p>
            </div>
            <div class="ml-6 md:ml-4 mt-8 md:mt-6 mr-6 md:mr-4">
                <form action="">
                    <div class="relative">
                        <label for="judul" class="text-gray-700">Email</label>
                        <input
                            name="judul"
                            type="text"
                            class="
                                w-full
                                h-9
                                border-b-2 border-gray-300
                                focus:border-blue-300
                                outline-none
                                md:h-4 
                            "
                        />
                    </div>
                </form>

                <form action="">
                    <div class="relative mt-5 md:mt-3">
                        <label for="judul" class="text-gray-700">Full Name</label>
                        <input
                            name="judul"
                            type="text"
                            class="
                                w-full
                                h-9
                                border-b-2 border-gray-300
                                focus:border-blue-300
                                outline-none
                                md:h-4
                            "
                        />
                    </div>
                </form>

                <form action="">
                    <div class="relative mt-5 md:mt-3">
                        <label for="judul" class="text-gray-700">Password</label>
                        <input
                            name="judul"
                            type="text"
                            class="
                                w-full
                                h-9
                                border-b-2 border-gray-300
                                focus:border-blue-300
                                outline-none
                                md:h-4
                            "
                        />
                    </div>
                </form>
            </div>
            <div class="justify-center items-center mt-5 md:mt-3 flex">
                <button class="bg-blue-600 text-gray-100 rounded-lg w-52 p-3">Get Started</button>
            </div>
            <div class="ml-6 mb-4 mr-2 mt-2">
                <p class="text-gray-600">
                    By signing up you are agreeing to our
                    <a href="#" class="text-black">Terms and Conditions</a>
                </p>
            </div>
        </div>
    </div>
</template>
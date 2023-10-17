<template>
    <section class="w-full bg-center bg-cover min-h-screen relative" style="background-image: url('/staff.jpg');">
        <div class="absolute top-0 left-0 h-full w-full bg-dark/60 backdrop-blur-sm"></div>
        <div class="relative z-10 max-w-3xl m-auto pt-[140px] px-4">
            <h1 class="text-5xl text-white text-center 480px:text-4xl">Our Staff Members</h1>
            <div class="flex justify-center mt-5 mb-5">
                <div class="grid grid-cols-2 gap-12 text-white w-fit 550px:grid-cols-1">
                    <div class="bg-black p-6 rounded-lg relative group">
                        <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Owner</span>
                        <img class="mb-5 rounded-md group-hover:scale-125 transition-all" width="184" height="184" src="https://avatars.akamai.steamstatic.com/73512d33d58eb02ed0f158adb0d60d45fc794903_full.jpg">
                        <div class="info">
                            <h2 class="text-center text-xl mb-3">SilentGames96</h2>
                            <div class="flex text-md items-center justify-center">
                                <Icon class="mr-2" name="logos:discord-icon" />
                                <span class="text-sm">silentgames96</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-black p-6 rounded-lg relative group">
                        <span class="absolute top-2 rounded-sm font-semibold left-2 p-2 text-sm px-3 bg-rust">Admin</span>
                        <img class="mb-5 rounded-md group-hover:scale-125 transition-all" src="https://avatars.akamai.steamstatic.com/ff6cfb6591a558aaf4afd0da81273f8850b2ab8c_full.jpg">
                        <div class="info">
                            <h2 class="text-center text-xl mb-3">LoBBer</h2>
                            <div class="flex text-md items-center justify-center">
                                <Icon class="mr-2" name="logos:discord-icon" />
                                <span class="text-sm">ilobber</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
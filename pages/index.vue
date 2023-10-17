<template>
    <section class="w-full bg-center bg-cover min-h-screen relative flex items-center justify-center" style="background-image: url('/background.jpg');">
        <div class="absolute top-0 left-0 h-full w-full bg-dark/60 backdrop-blur-sm"></div>
        <div class="relative z-10 px-4">
            <img src="/immortal_logo.png" alt="Immortal RustRed">
            <ul class="m-auto flex items-center justify-center">
                <NuxtLink class="mr-2 py-3 rounded hover:text-white hover:bg-dark transition-all px-6 bg-main link text-white text-xl inline-block" to="steam://connect/149.56.23.79:15100" target="_blank"><Icon name="bi:steam" class="text-2xl mr-1 text-white" /> Connect</NuxtLink>
                <NuxtLink class="mr-2 py-3 rounded hover:text-white hover:bg-dark transition-all px-6 bg-main link text-white text-xl inline-block" to="https://discord.gg/rCT2DxMt" target="_blank"><Icon name="fa6-brands:discord" class="text-2xl mr-1 text-white" /> Discord</NuxtLink>
            </ul>
        </div>
    </section>
</template>

<script setup>
    useSeoMeta({
        title: "ImmortalRustRed — Official Website",
        ogTitle: 'ImmortalRustRed Server',
        description: 'Welcome to ImmortalRustRed official website. Get all Immortal servers connection information here.',
        ogDescription: 'Welcome to ImmortalRustRed official website. Get all Immortal servers connection information here.',
        ogImage: 'https://cdn.discordapp.com/attachments/1163524207704031262/1163727437956386816/immortal.png',
        twitterCard: 'summary_large_image',
    });
</script>
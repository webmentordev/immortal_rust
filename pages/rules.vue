<template>
    <section class="w-full bg-center bg-cover min-h-screen relative" style="background-image: url('/rules.webp');">
        <div class="absolute top-0 left-0 h-full w-full bg-dark/60 backdrop-blur-sm"></div>
        <div class="relative z-10 max-w-3xl m-auto pt-[140px] px-4">
            <h1 class="text-5xl text-white text-center">SERVER RULES</h1>
            <div class="mt-5 mb-5 p-6 rounded-lg bg-dark text-white/90">
                <p class="mb-6">Compliance with the mentioned rules is imperative, and it is crucial to be aware that some offenses cannot be appealed. Therefore, it is important to exercise caution and attentiveness to ensure adherence to the rules.</p>
                <ul class="rules">
                    <li>No cheating or exploiting game bugs.</li>
                    <li>Maximum 6 Players Teamsize (inc. Sleepers).</li>
                    <li>No hacking or use of third-party programs to gain an unfair advantage.</li>
                    <li>No spamming or excessive use of offensive language in chat.</li>
                    <li>No sharing personal information of other players.</li>
                    <li>No scamming or attempting to deceive other players.</li>
                    <li>No racist, sexist, or other discriminatory language or behavior.</li>
                    <li>No previous game bans in a year</li>
                    <li>Respect all players and staff members.</li>
                </ul>
            </div>
        </div>
    </section>
</template>

<script setup>
    useSeoMeta({
        title: "Rules — ImmortalRustRed",
        ogTitle: 'Rules — ImmortalRustRed',
        description: 'Carefully read the rules of ImmortalRustRed servers. Make sure to follow our rules otherwise you will be banned.',
        ogDescription: 'Carefully read the rules of ImmortalRustRed servers. Make sure to follow our rules otherwise you will be banned.',
        ogImage: 'https://cdn.discordapp.com/attachments/1163524207704031262/1163727437956386816/immortal.png',
        twitterCard: 'summary_large_image',
    });
</script>
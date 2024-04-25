<template>
    <div class="bg-brand-echo">
        <div class="max-w-6xl mx-auto">
            <div class="grid grid-cols-3 pt-28 text-white items-center border-b border-white pb-[30px] mb-[127px]">
                <img src="/logo.png" alt="logo" loading="lazy" class="justify-self-start w-[199px]"/>
                <nav class="justify-self-center space-x-6 text-[19px] font-bold leading-[25.5px]">
                    <a v-for="item in footerNav" :key="item.name" :href="item.href">{{item.name}}</a>
                </nav>
                <div class="justify-self-end flex gap-[11px]">
                    <a v-for="item in socialIcons" :key="item.name" :href="item.href"><img :src="item.src" :alt="item.name" /></a>
                </div>
            </div>
            <div class="text-white text-[14px] pb-[47px]">
                <p>Copyright 2023 © Sundack |  Address   |  Phone number   |  Email address</p>
                <div class="flex justify-between">
                    <p>Website created by The Profitable Firm</p>
                    <span>
                        <a href="/">Terms of Service</a> |
                        <a href="/">Privacy Policy</a>
                    </span>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
    const footerNav = [
        { 'name': 'About', 'href': '/'},
        { 'name': 'How we work', 'href': '/'},
        { 'name': 'Blog', 'href': '/'},
    ]
    const socialIcons = [
        { 'name': 'facebook', 'href': 'www.facebook.com', 'src': '/facebook.png'},
        { 'name': 'linkedin', 'href': 'www.linkedin.com', 'src': '/linkedin.png'},
        { 'name': 'twitter', 'href': 'www.twitter.com', 'src': '/twitter.png'},
        { 'name': 'instagram', 'href': 'www.instagram.com', 'src': '/instagram.png'}
    ]
</script>

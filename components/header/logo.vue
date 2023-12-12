<template>
    <div class="wsmobileheader clearfix">
        <span class="smllogo">
            <!-- <img src="/assets/images/254Insurance.png" alt="mobile-logo" width="200"/>
             -->
             <NuxtLink to="/" class="logo-white"><h2 class="w-700"> 254Insurance</h2></NuxtLink>
        </span>
        <a id="wsnavtoggle" class="wsanimated-arrow" @click="toggleMobileMenu">
            <span></span>
        </a>
    </div>
</template>

<script>
export default {
    methods: {
        toggleMobileMenu() {
            // toggle body class "dark-mode"
            document.body.classList.toggle("wsactive");
        }
    }
};
</script>

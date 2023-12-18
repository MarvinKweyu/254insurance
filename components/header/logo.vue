<template>
    <div class="wsmobileheader clearfix">
        <span class="smllogo">
            
            
             <NuxtLink to="/"><img src="/assets/images/254NewLogo.png" alt="mobile-logo" width="200"/></NuxtLink>
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

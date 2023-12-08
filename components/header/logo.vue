<template>
    <div class="wsmobileheader clearfix">
        <span class="smllogo"><img src="/assets/images/logo-pink.png" alt="mobile-logo" /></span>
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

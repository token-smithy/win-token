<script setup></script>

<template>
	<main>
		<section class="landing-page">
			<div class="box2">
                <img src="./assets/images/logo.png" alt="">
				<!-- <div class="text">pre</div> -->
			</div>
			<div class="sentence">"WIN. get extra win in your bags."</div>
			
			<div class="social-wrapper">
                <a href="https://t.me/+w0NfKNaz-Z8zMmZk" target="_blank">
                <button class="social-item" title="Telegram">
                   <icon-telegram></icon-telegram>
                   </button>
                </a>
                <a href="https://x.com/win_on_base" target="_blank">
                <button class="social-item" title="Twitter/X">
                    <icon-twitter></icon-twitter>
                   </button>
                </a>
                <a href="https://discord.gg/Mvg8qfev" target="_blank">
                <button class="social-item" title="Discord">
                    <icon-discord></icon-discord>
                   </button>
                </a>
                <button class="social-item" title="Dexscreener">
                    <icon-chart></icon-chart>
                </button>
                <button class="social-item" title="Uniswap">
                    <icon-uniswap></icon-uniswap>
                </button>
            </div>
            <div class="mail">
                <a href= "mailto: contact@win5minch.art"> contact@win5minch.art 
                </a>
            </div>
		</section>
	</main>
</template>

<script setup>
    import IconTelegram from "@/components/icons/IconTelegram.vue"
    import IconTwitter from "@/components/icons/IconTwitter.vue"
    import IconChart from "@/components/icons/IconChart.vue"
    import IconUniswap from "@/components/icons/IconUniswap.vue"
    import IconDiscord from "@/components/icons/IconDiscord.vue"
</script>
<style lang="sass">
@import ./assets/sass/main.sass
body
    margin: 0
    #app
        min-height: 100svh
        width: 100%
        .landing-page
            display: flex
            justify-content: center
            flex-direction: column
            height: 100svh
            align-items: center
            gap: 42px
            .box2
                background-color: white
                // border: 1px solid lightgrey
                position: absolute
                // width: 350px
                // height: 350px
                text-align: center
                // border-radius: 350px
                position: relative
                img
                    height: 250px
                    width: 250px
                    @media (min-width: 992px)
                        height: 350px
                        width: 350px
                .text
                    font-size: 148px
                    position: absolute 
                    top: 45%
                    left: 50%
                    -ms-transform: translate(-50%, -50%)
                    transform: translate(-50%, -50%)
            .sentence
                background-color: black
                padding: 1rem
                font-size: 12px
                line-height: 2rem
                color: white
                border-radius: 12px
                font-weight: bold
                @media (min-width: 992px)
                    font-size: 24px
            .mail
                font-size: 16px
                a
                    color: black
                @media (min-width: 992px)
                    font-size: 20px
                &:hover, &:focus, &:active
                    cursor: pointer
                    
.social-wrapper
    display: flex
    gap: 12px
    @media (min-width: 992px)
        gap: 24px
    .social-item
        border-radius: 12px
        height: 50px
        width: 50px
        border: 1px solid lightgrey
        background-color: white
        display: flex
        justify-content: center
        align-items: center
        @media (min-width: 992px)
            height: 100px
            width: 100px
        svg
            height: 25px
            @media (min-width: 992px)
                height: 50px
        &:hover, &:active, &:focus
            background-color: darken(white, 10%)
            cursor: pointer
</style>

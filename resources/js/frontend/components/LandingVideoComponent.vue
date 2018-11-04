<template>
    <header>
        <div class="overlay"></div>
        <video playsinline="playsinline" autoplay="autoplay" muted="muted" loop="loop">
            <source src="assets/videos/landpage.mp4" type="video/mp4">
        </video>
        <div class="container h-100">
            <div class="d-flex text-center h-100">
                <div class="my-auto w-100 text-white">
                    <h1 class="mbr-section-title align-center mbr-bold pb-3 mbr-fonts-style display-1">
                        BADATOR XII. EDIZIOA</h1>
                    <p class="mbr-text align-center pb-3 mbr-fonts-style display-5">Adi! Legazpi Futbol 7 Herri txapelketarako taldeen izen ematea abian da!&nbsp;</p>
                    <div class="mbr-section-btn align-center"><a class="btn btn-md btn-primary display-4" href="https://mobirise.co"><span class="mbri-edit mbr-iconfont mbr-iconfont-btn"></span>IZENA-EMAN</a></div>
                </div>
            </div>
        </div>
        <div class="mbr-arrow mbr-arrow-custom hidden-sm-down" aria-hidden="true">
            <a href="#next">
                <i class="mbri-down mbr-iconfont"></i>
            </a>
        </div>
    </header>
</template>

<script>
export default  {
    name: 'landingVideo',
    props: [],
    mounted() {

    },
    data() {
        return {
            
        }
    },
    methods: {

    },
    computed: {

    }
}
</script>

<style>
    header {
    position: relative;
    background-color: black;
    /* height: 75vh; */
    height: calc( 100vh - 77px );
    min-height: 25rem;
    width: 100%;
    overflow: hidden;
    }

    header video {
    position: absolute;
    top: 50%;
    left: 50%;
    min-width: 100%;
    min-height: 100%;
    width: auto;
    height: auto;
    z-index: 0;
    -ms-transform: translateX(-50%) translateY(-50%);
    -moz-transform: translateX(-50%) translateY(-50%);
    -webkit-transform: translateX(-50%) translateY(-50%);
    transform: translateX(-50%) translateY(-50%);
    }

    header .container, header .mbr-arrow {
    position: relative;
    z-index: 2;
    }

    header .overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: black;
    opacity: 0.5;
    z-index: 1;
    }

    @media (pointer: coarse) and (hover: none) {
        header {
            /* background: url('https://source.unsplash.com/XT5OInaElMw/1600x900') black no-repeat center center scroll; */
        }
        header video {
            display: none;
        }
    }
</style>

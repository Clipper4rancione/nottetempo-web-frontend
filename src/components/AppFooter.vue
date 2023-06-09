<script>
    export default {
        name: 'AppFooter'
    }
</script>

<template>
    <footer>
        <div class="row py-5 w-100">
            <div class="col-2 logo-tiny">
                <img src="/LOGO_NT_BASE.png" alt="">
            </div>
            <div class="col-2">
                <ul>
                <h6>Indice</h6>
                    <a href="">
                        <li>Chi Siamo</li>
                    </a><a href="">
                        <li>I Founders</li>
                    </a><a href="">
                        <li>Contattaci</li>
                    </a><a href="">
                        <li>I Nostri canali live</li>
                    </a>
                </ul>
            </div>
            <div class="col-2">
                <ul>
                    <h6>I Nostri Streamers</h6>
                    <a href="">
                        <li>AlessioMolteni</li>
                    </a><a href="">
                        <li>ClipperArancione</li>
                    </a><a href="">
                        <li>Ikushimi</li>
                    </a><a href="">
                        <li>Kajyto1550</li>
                    </a><a href="">
                        <li>96Xander96</li>
                    </a>
                </ul>
            </div>
            <div class="col-6 regardments d-flex align-items-center justify-content-center">
                <div class="caption-regard">
                    <span>Powered By ClipperArancione</span>
                </div>
            </div>
        </div>
    </footer>
</template>



<style lang="scss" scoped>
footer{
    height: 70px;
    .logo-tiny{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100px;
    margin-left: 50px;
    
    img{
        vertical-align: middle;
        width: 100%;
    }
}
ul{

    h6{
        font-weight: 600;
    }

    li{
    font-size: 0.8rem;
    line-height: 1.6rem;
    }
}
.regardments{
    border-left: 1px solid rgba(167, 167, 167, 0.596);
    .caption-regard{
        font-size: 0.6rem;
        color: grey;
    }
}
}


</style>
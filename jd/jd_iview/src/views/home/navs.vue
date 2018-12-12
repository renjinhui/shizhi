<template>
    <div class='navsBox'>
        <ul>
            <li v-for='i in 10'>
                <div class="icon_box">
                    <img src="https://m.360buyimg.com/mobilecms/jfs/t25105/97/1814025767/9926/96b22ef5/5bbd5bdfN53e8cdb4.png.webp" alt="">
                </div>
                京东超市
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped lang='less'>
    @r:37.5rem;
    .navsBox{
        width: 100%;
        height: 180/@r;
        padding: 20/@r 0;
        box-sizing: border-box;
        background: url('https://m.360buyimg.com/mobilecms/s1125x486_jfs/t24658/344/1832689388/14444/99e99074/5bbdb233N122fa205.jpg.dpg') no-repeat;
        ul{
            overflow: hidden;
            list-style: none;
            li{
                float: left;
                width: 20%;
                text-align: center;
                padding: 5/@r;
                img{
                    width: 40/@r;
                    height: 40/@r;
                }
            }
        }
    }
</style>
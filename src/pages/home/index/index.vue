<template>
    <div>
        <!-- 头部 -->
        <div :class="{header:true, scroll:isScrollTop}">
            <div class="classify-icon"></div>
            <div class="search-wrap">
                <i class="iconfont iconsousuo"></i>搜索
            </div>
            <div class="login">登录</div>
        </div>
        <!-- 轮播 -->
        <div class="banner-wrap">
            <div class="swiper-container" ref="swiper-container">
                <div class="swiper-wrapper">
                    <div class="swiper-slide" v-for="(item,index) in swipers" :key="index" >
                        <img :src="item.image" alt="">
                    </div>
                </div>
                <!-- 如果需要分页器 -->
                <div class="swiper-pagination"ref="swiper-pagination"></div>
            </div>
            
        </div>
        <!-- 导航 -->
        <div class="quick-nav">
            <ul class="item">
                <li><img src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/125678/35/5947/4868/5efbf28cEbf04a25a/e2bcc411170524f0.png" alt=""></li>
                <li>潮流女装</li>
            </ul>
            <ul class="item">
                <li><img src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/125678/35/5947/4868/5efbf28cEbf04a25a/e2bcc411170524f0.png" alt=""></li>
                <li>潮流女装</li>
            </ul>
            <ul class="item">
                <li><img src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/125678/35/5947/4868/5efbf28cEbf04a25a/e2bcc411170524f0.png" alt=""></li>
                <li>潮流女装</li>
            </ul>
            <ul class="item">
                <li><img src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/125678/35/5947/4868/5efbf28cEbf04a25a/e2bcc411170524f0.png" alt=""></li>
                <li>潮流女装</li>
            </ul>
        </div>
        <!-- 潮流女装 -->
                <div class="goods-main">
            <div class="classify-name color-0">—— 潮流女装 ——</div>
            <div class="goods-row-1">
                <div class="goods-column">
                    <div class="goods-title">高跟鞋女2018新款春季单鞋仙女甜美链子尖头防水台细跟女鞋一字带</div>
                    <div class="goods-tip">精品打折</div>
                    <div class="goods-price bg-color-0">128元</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556409.jpg" alt="">
                    </div>
                </div>
                <div class="goods-column">
                    <div class="goods-list">
                        <div class="goods-list-title">欧美尖头蝴蝶结拖鞋女夏外穿2018新款绸缎面细跟凉拖半拖鞋穆勒鞋</div>
                        <div class="goods-list-tip">品质精挑</div>
                        <div class="goods-list-image">
                            <img src="//vueshop.glbuys.com/uploadfiles/1524556315.jpg" alt="">
                        </div>
                    </div>
                    <div class="goods-list">
                        <div class="goods-list-title">欧美尖头蝴蝶结拖鞋女夏外穿2018新款绸缎面细跟凉拖半拖鞋穆勒鞋</div>
                        <div class="goods-list-tip">品质精挑</div>
                        <div class="goods-list-image">
                            <img src="//vueshop.glbuys.com/uploadfiles/1524556315.jpg" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="goods-row-2">
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
            </div>
        </div>
        <div class="goods-main">
            <div class="classify-name color-1">—— 品牌男装 ——</div>
            <div class="goods-row-1">
                <div class="goods-column-2">
                    <div class="goods-title">高跟鞋女2018新款春季单鞋仙女甜美链子尖头防水台细跟女鞋一字带</div>
                    <div class="goods-tip">火爆开售</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556409.jpg" alt="">
                    </div>
                </div>
                <div class="goods-column-2">
                    <div class="goods-title">高跟鞋女2018新款春季单鞋仙女甜美链子尖头防水台细跟女鞋一字带</div>
                    <div class="goods-tip">火爆开售</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556409.jpg" alt="">
                    </div>
                </div>
            </div>
            <div class="goods-row-2">
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
            </div>
        </div>

        <div class="goods-main">
            <div class="classify-name color-2">—— 电脑办公 ——</div>
            <div class="goods-row-1">
                <div class="goods-column">
                    <div class="goods-title">高跟鞋女2018新款春季单鞋仙女甜美链子尖头防水台细跟女鞋一字带</div>
                    <div class="goods-tip">精品打折</div>
                    <div class="goods-price bg-color-2">128元</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556409.jpg" alt="">
                    </div>
                </div>
                <div class="goods-column">
                    <div class="goods-list">
                        <div class="goods-list-title">欧美尖头蝴蝶结拖鞋女夏外穿2018新款绸缎面细跟凉拖半拖鞋穆勒鞋</div>
                        <div class="goods-list-tip">品质精挑</div>
                        <div class="goods-list-image">
                            <img src="//vueshop.glbuys.com/uploadfiles/1524556315.jpg" alt="">
                        </div>
                    </div>
                    <div class="goods-list">
                        <div class="goods-list-title">欧美尖头蝴蝶结拖鞋女夏外穿2018新款绸缎面细跟凉拖半拖鞋穆勒鞋</div>
                        <div class="goods-list-tip">品质精挑</div>
                        <div class="goods-list-image">
                            <img src="//vueshop.glbuys.com/uploadfiles/1524556315.jpg" alt="">
                        </div>
                    </div>
                </div>
            </div>
            <div class="goods-row-2">
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
                <div class="goods-list">
                    <div class="goods-title">小白鞋女2018春夏季新款韩版百搭平底学生原宿ulzzang帆布鞋板鞋</div>
                    <div class="goods-image">
                        <img src="//vueshop.glbuys.com/uploadfiles/1524556119.jpg" alt="">
                    </div>
                    <div class="price">¥288</div>
                    <div class="price line">¥384</div>
                </div>
            </div>
        </div>
        

        <div class="goods-recom-nav">
            <div class="line"></div>
            <div class="recom-wrap">
                <!-- <div class="icon"></div> -->
                <div class="text"><i class="iconfont iconcolumn-4"></i>为您推荐</div>
            </div>
            <div class="line"></div>
        </div>

        <div class="goods-recom">
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
            <div class="goods-list">
                <div class="goods-image">
                    <img src="//vueshop.glbuys.com/uploadfiles/1484283665.jpg" alt="">
                </div>
                <div class="goods-title">ONLY冬装新品雪纺拼接流苏腰带长款连衣裙女</div>
                <div class="goods-price">¥288</div>
            </div>
        </div>
    </div>
</template>

<script>
    import {mapActions,mapState} from 'vuex';
    import Swiper from "../../../assets/js/libs/swiper";

    export default {
        name: "index",
        data(){
            return {
                isScrollTop:false
            }
        },
        created(){
            this.isSroll = true;
            window.addEventListener("scroll",this.eventScrollTop)
            //执行接口 
            this.getSwiper({success:() => {
                this.$nextTick(()=>{
                    new Swiper (this.$refs['swiper-container'], {
                        loop: true,
                        autoplay : 1000,
                        // 如果需要分页器
                        pagination: this.$refs['swiper-pagination']
                    })      
                })

            }});
        },
        mounted(){
            //牵扯到获取dom放在mounted更合适
     
        },
        computed:{
            ...mapState({
                swipers:(state)=>state.index.swipers
            })
        },
        methods:{
            ...mapActions({
                getSwiper:'index/getSwiper'
            }),
            eventScrollTop(){
                // 兼容性处理
                let iscrollTop = document.body.scrollTop || document.documentElement.scrollTop;
                console.log(iscrollTop)
               if(iscrollTop >= 150) {
                    // 性能处理  不想让他一直在执行赋值true
                    if(this.isSroll) {
                        console.log(1)
                        this.isSroll = false;
                        this.isScrollTop = true;
                    }
                    
                }else{
                    if(!this.isSroll) {
                        this.isSroll = true;
                        this.isScrollTop = false;
                    }
                }
            }
        },
        destroyed() {
            // 在销毁vue实例的时候清除事件   第一种方法keepAlive变成false
            console.log(1111)
            window.removeEventListener("scroll",this.eventScrollTop)
        },
        // keepAlive进入时触发的钩子函数
        activated() {
            this.isSroll = true;
            window.addEventListener("scroll",this.eventScrollTop)
        },
        //第二种方法  keepAlive为true的时候 keepAlive离开时触发的钩子函数
        deactivated() {
            console.log(1111)
            window.removeEventListener("scroll",this.eventScrollTop)
        }
    }
</script>

<style scoped>
    @import "../../../assets/css/common/swiper.css";


    .header{width: 100%; height: 1rem;position: fixed;z-index: 10;left: 0px;top: 0px;
    background: linear-gradient(rgba(1,1,1,.2),hsla(0,0%,100%,0));display: flex;
    justify-content: space-between;align-items: center;padding: 0 0.3rem;box-sizing: border-box;}
    .header.scroll{background: linear-gradient(#eb1625,hsla(0,0%,100%,0));}
    .header .classify-icon{width: 0.6rem;height: 0.6rem;background-image: url("../../../assets/images/home/index/a1.png");
    background-size: 100%;background-repeat: center;background-repeat: no-repeat;}
    .header .search-wrap{width: 5.26rem;height: 0.52rem;background-color: rgba(255,255,255,0.5);
    border-radius: 4px;color: #fff;line-height: 0.52rem;padding-left: 0.1rem;box-sizing: border-box;}
    .header .login{width: auto; height: 0.44rem; font-size: 0.32rem;color:#fff;}

    /* 轮播图css */
    .banner-wrap{width: 100%; height: 3.66rem;}
    .banner-wrap .swiper-container {
        width: 100%;
        height: 100%;
    } 
    .banner-wrap img{width: 100%;height: 100%;;}

    .quick-nav{width: 100%;height: 1.6rem;background-color: #fff;margin-top: 0.2rem;
    display: flex;align-items: center;justify-content: space-between;}

    .quick-nav .item{width: 1.4rem;display: flex;align-items: center; flex-direction:column ;}
    .quick-nav .item li:nth-child(1){width: 0.8rem; height: 0.8rem;}
    .quick-nav .item li:nth-child(1) img{width: 100%;height: 100%;}
    .quick-nav .item li:nth-child(2){font-size: 0.28rem;color: #7b7f82;text-align: center;margin-top: 0.2rem;}

    .goods-main{width:100%;height:7.36rem;background-color:#FFFFFF;margin-top:0.2rem;}
    .goods-main .classify-name{width:100%;height:0.64rem;border-bottom:1px solid #EFEFEF;font-size:0.32rem;text-align:center;line-height:0.64rem;}
    .goods-main .classify-name.color-0{color:#f73b61}
    .goods-main .classify-name.color-1{color:#fe6719}
    .goods-main .classify-name.color-2{color:#5fc600}
    .goods-main .goods-row-1{width:100%;height:3.5rem;border-bottom:1px solid #EFEFEF;display:flex;overflow: hidden;}
    .goods-main .goods-row-1 .goods-column,.goods-main .goods-row-1 .goods-column-2{width:50%;height:100%;border-right: 1px solid #EFEFEF;position: relative;}
    .goods-main .goods-row-1 .goods-column .goods-title{width:95%;height:0.32rem;overflow:hidden;position: absolute;left:0.2rem;top:0.2rem;font-size:0.28rem;font-weight: bold;}
    .goods-main .goods-row-1 .goods-column .goods-tip{width:auto;height:auto;font-size:0.28rem;color:#cb385d;position: absolute;left:0.2rem;top:0.6rem;}
    .goods-main .goods-row-1 .goods-column .goods-price{width:auto;height:0.4rem;border-radius: 10px;position: absolute;right:1rem;top:0.6rem;color:#FFFFFF;font-size:0.28rem;}
    .goods-main .goods-row-1 .goods-column .goods-price.bg-color-0{background-color:#f21d4f;}
    .goods-main .goods-row-1 .goods-column .goods-price.bg-color-2{background-color:#5fc600}
    .goods-main .goods-row-1 .goods-column .goods-image{width:3rem;height:2rem;position: absolute;left:0.35rem;bottom:0.3rem;}
    .goods-main .goods-row-1 .goods-column .goods-image img{width:100%;height:100%;}
    .goods-main .goods-row-1 .goods-column .goods-list{width:100%;height:50%;border-bottom:1px solid #EFEFEF;position: relative;}
    .goods-main .goods-row-1 .goods-column .goods-list-title{width:2.04rem;height:0.32rem;overflow:hidden;font-size:0.28rem;font-weight:bold;position: absolute;z-index:1;left:0.2rem;top:0.2rem;}
    .goods-main .goods-row-1 .goods-column .goods-list-tip{width:auto;height:auto;font-size:0.24rem;color:#7b7f82;position: absolute;left:0.2rem;top:0.6rem;}
    .goods-main .goods-row-1 .goods-column .goods-list-image{width:1.2rem;height:1.2rem;position: absolute;right:0.2rem;top:0.2rem;}
    .goods-main .goods-row-1 .goods-column .goods-list-image img{width:100%;height:100%;}

    .goods-main .goods-row-1 .goods-column-2 .goods-title{width:95%;height:0.32rem;overflow:hidden;font-size:0.28rem;font-weight: bold;text-align:center;margin:0 auto;margin-top:0.2rem;}
    .goods-main .goods-row-1 .goods-column-2 .goods-tip{width:auto;height:auto;font-size:0.28rem;color:#7b7f82;text-align:center;margin-top:0.1rem;}
    .goods-main .goods-row-1 .goods-column-2 .goods-image{width:1.8rem;height:2rem;margin:0 auto;margin-top:0.1rem;}
    .goods-main .goods-row-1 .goods-column-2 .goods-image img{width:100%;height:100%;}

    .goods-main .goods-row-2{width:100%;height:3.2rem;overflow: hidden;display:flex;}
    .goods-main .goods-row-2 .goods-list{width:25%;height:100%;border-right:#EFEFEF 1px solid;}
    .goods-main .goods-row-2 .goods-title{width:100%;height:0.4rem;overflow:hidden;font-size:0.28rem;font-weight:bold;text-align:center;margin-top:0.2rem;}
    .goods-main .goods-row-2 .goods-image{width:1.5rem;height:1.5rem;margin:0 auto;margin-top:0.2rem;}
    .goods-main .goods-row-2 .goods-image img{width:100%;height:100%;}
    .goods-main .goods-row-2 .price{width:100%;height:auto;text-align: center;font-size:0.28rem;color:#d32a4e;margin-top:0.1rem;}
    .goods-main .goods-row-2 .price.line{color:#7b7f82;text-decoration: line-through;margin-top:0px;}

    .goods-recom-nav{width:100%;height:1rem;display: flex;justify-content: space-between;align-items: center;}
    .goods-recom-nav .line{width:35%;height:1px;background-color:#d4d4d4}
    .goods-recom-nav .recom-wrap{width:1.8rem;height:0.44rem;display: flex;justify-content:space-between;align-items: center;}
    /* .goods-recom-nav .recom-wrap .icon{width:0.4rem;height:0.4rem;background-image: url("../../../assets/images/home/index/recom.png");background-size:100%;background-repeat: no-repeat;background-position: center;} */
    .goods-recom-nav .recom-wrap .text{width:auto;height:auto;font-size:0.32rem;font-weight:bold;}

    .goods-recom{width: 100%;display: flex;justify-content: space-between;padding:0px 0.2rem;box-sizing: border-box;flex-wrap:wrap;}
    .goods-recom .goods-list{width:48%;height:4.5rem;background-color:#FFFFFF;margin-top:0.2rem;}
    .goods-recom .goods-list .goods-image{width:2.8rem;height:2.8rem;margin:0 auto;margin-top:0.2rem;}
    .goods-recom .goods-list .goods-image img{width:100%;height:100%;}
    .goods-recom .goods-list .goods-title{width:100%;height:0.8rem;overflow:hidden;font-size:0.28rem;margin-top:0.1rem;}
    .goods-recom .goods-list .goods-price{width:auto;height:auto;font-size:0.32rem;color:#d32a4e;margin-top:0.1rem;}
</style>
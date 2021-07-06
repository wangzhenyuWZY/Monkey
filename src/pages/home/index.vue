<template>
  <div class="container">
    <div class="homeContainer">
      <header class="header">
        <img src="../../assets/img/icon_logo.png" class="logo">
        <a class="getmonkey">GET $MONKEY</a>
        <ul class="menulist">
          <li class="active"><a>WHY MONKEY </a></li>
          <li><a>HOW TO GET </a></li>
          <li><a>TOKENOMICS </a></li>
          <li><a> MOONMAP</a></li>
        </ul>
      </header>
      <div class="bannerbox">
        <h2 class="title">To be a meme, Let others chase!</h2>
        <p class="infotext">Monkey King ($MONKEY) is a community-focused, decentralized cryptocurrency with instant rewards thanks to active users! Join the mars mission. </p>
        <div class="btnbox">
          <a class="btn">GET $MONKEY</a>
          <a class="btn">WHITEPAPER</a>
        </div>
        <div class="contracts">
          <a><img src="../../assets/img/icon5.png"></a>
          <a><img src="../../assets/img/icon6.png"></a>
          <a><img src="../../assets/img/icon4.png"></a>
          <a><img src="../../assets/img/icon3.png"></a>
          <a><img src="../../assets/img/icon2.png"></a>
          <a><img src="../../assets/img/icon7.png"></a>
        </div>
      </div>
      <div class="imgbox" style="margin-top:107px;">
        <img class="fr" width="731" style="" src="../../assets/img/img5.png">
        <img class="fr" width="463" style="margin-right:17px;margin-top:110px;" src="../../assets/img/img2.png">
      </div>
      <div class="imgbox" style="margin-top:87px;">
        <img class="fl" width="712" src="../../assets/img/img1.png">
        <img class="fl" width="583" style="margin-left:-40px;margin-top:170px;" src="../../assets/img/img3.png">
      </div>
      <div style="text-align:center;margin-top:48px;"><img src="../../assets/img/img4.png" width="562px"></div>
      <div style="text-align:center;margin-top:84px;"><img src="../../assets/img/img_baioti01.png" width="562px"></div>
      <div class="intros">
        <h2>$MONKEY</h2>
        <p>TOKEN SYMBOL</p>
        <h2>2% Usage Reward</h2>
        <p>THANKS TO USER TRANSACTIONS(DEFI WALLETS ONLY!)</p>
        <h2>100 Quadrilion</h2>
        <p>TOTAL SUPPLY</p>
        <h2>178,000+</h2>
        <p>HOLDERS</p>
        <h2>$0.140 Billion</h2>
        <p>MARKET CAP</p>
        <h2>$0.0000000014</h2>
        <p>CURRENT PRICE</p>
      </div>
      <div style="text-align:center;margin-top:95px"><img src="../../assets/img/img8.png"></div>
      <div class="phasebox">
        <div class="phaseitem" style="width:460px">
          <h2>PHASE 1 Launch</h2>
          <p>1,000 Holders<br>
             Website Launch<br>
              CoinGecko Listing<br> 
              2,000 Telegram Members<br> 
              Community Donation Wallet<br>
               Awareness Campaign <br>
               CoinMarketCap Listing <br>
               5,000 Holders</p>
        </div>
        <div class="phaseitem">
          <h2>PHASE 2 Growth</h2>
          <p>5,000 Telegram Members <br>
            Website Redesign <br>
            10,000 Holders <br>
            10,000 Telegram Members <br>
            20,000 Holders</p>
        </div>
        <div class="phaseitem" style="width:460px">
          <h2>PHASE 3 Expansion</h2>
          <p>MONKEY Swap (Decentralize Exchange) <br>
            Initial CEX Listings (Hotbit, Bilaxy, CoinTiger) <br>
            15,000 Telegram Members <br>
            30,000 Holders</p>
        </div>
        <div class="phaseitem">
          <h2>PHASE 4 Utility</h2>
          <p>100,000 Holders <br>
            MONKEY Crate (NFT Marketplace) <br>
            MONKEY Paw Print (Wallet Tracker) <br>
            MONKEY sWag (Merchandise Store) <br>
            More CEX Listings <br>
            50,000 Telegram Members <br>
            Influencer Awareness Partnerships</p>
        </div>
      </div>
      <div style="text-align:center;margin-top:216px;margin-bottom:30px;"><img src="../../assets/img/img7.png"></div>
      <div class="links">
        <div class="contracts">
          <a><img src="../../assets/img/icon5.png"></a>
          <a><img src="../../assets/img/icon6.png"></a>
          <a><img src="../../assets/img/icon4.png"></a>
          <a><img src="../../assets/img/icon3.png"></a>
          <a><img src="../../assets/img/icon2.png"></a>
          <a><img src="../../assets/img/icon7.png"></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components:{
  },
  watch: {
    
  },
  data() {
    return {
      
    }
  },
  mounted() {
    
  },
  methods: {
    
  }
}
</script>
<style  lang="less" scoped>
 @font-face {
    font-family: DFGBBDC;
    src:url('../../assets/font/DFGBBDC.TTF') format('truetype');/*non-IE*/
  }
  @font-face {
    font-family: robotoBlack;
    src:url('../../assets/font/roboto-black.ttf') format('truetype');/*non-IE*/
  }
  @font-face {
    font-family: RobotoNormal;
    src:url('../../assets/font/Roboto-Normal.ttf') format('truetype');/*non-IE*/
  }
.container{
  width:100%;
  height:auto;
  min-height:100vh;
  background:url(../../assets/img/bg.png) no-repeat center;
  background-size:100% 100%;
  padding-bottom:208px;
  .homeContainer{
    width:1400px;
    margin:0 auto;
    .header{
      overflow:hidden;
      padding:12px 0;
      .logo{
        float:left;
        width:182px;
      }
      .getmonkey{
        float:right;
        width:190px;
        height:48px;
        border-radius:32px;
        background:#2D2117;
        line-height:48px;
        text-align:center;
        font-size:20px;
        color:#FFFFFF;
        font-family: robotoBlack;
      }
      .menulist{
        float:right;
        margin-right:36px;
        li{
          float:left;
          &.active{
            a{
              font-size:24px;
              font-family: robotoBlack;
              font-weight:900;
            }
          }
          a{
            font-size:20px;
            color:#412913;
            line-height:48px;
            font-family: SourceHanSansCN-Normal, SourceHanSansCN;
            cursor: pointer;
          }
          margin:0 24px;
        }
      }
    }
    .bannerbox{
      margin-top:84px;
      height:641px;
      background:url(../../assets/img/banner.png) no-repeat center;
      background-size:100% 100%;
      .title{
        font-size:64px;
        color:#2D2117;
        line-height:96px;
        font-family: SourceHanSansCN-Bold, SourceHanSansCN;
        font-weight:bold;
        padding-top:178px;
        padding-bottom:11px;
        width:560px;
      }
      .infotext{
        font-size:20px;
        line-height:32px;
        color:#2D2117;
        font-family: DFGBBDC;
        padding-bottom:21px;
        width:718px;
      }
      .btnbox{
        overflow: hidden;
        padding-bottom:30px;
        .btn{
          float:left;
          width:272px;
          height:64px;
          background:#A52D11;
          line-height:64px;
          text-align:center;
          font-size:20px;
          color:#FFFFFF;
          font-family: RobotoNormal;
          margin-right:24px;
          cursor: pointer;
          border-radius:12px;
        }
      }
      .contracts{
        overflow:hidden;
        a{
          float:left;
          margin-right:63px;
          img{
            width:47.6px;
          }
        }
      }
    }
    .imgbox{
      overflow:hidden;
      .fl{
        float:left;
      }
      .fr{
        float:right;
      }
    }
    .intros{
      text-align:center;
      h2{
        font-size:48px;
        color:#A52D11;
        line-height:57px;
        padding-top:56px;
        padding-bottom:12px;
        font-family: robotoBlack;
        font-weight: 900;
      }
      p{
        font-size:24px;
        line-height:32px;
        color:#2D2117;
        font-family: RobotoNormal;
      }
    }
    .phasebox{
      width:1200px;
      height:1178px;
      background:#FFE9C7 url(../../assets/img/img6.png) no-repeat center;
      background-size:100% 100%;
      border:5px solid #2D2117;
      border-radius:32px;
      padding:31px 95px;
      box-sizing: border-box;
      margin:0 auto;
      .phaseitem{
        float:left;
        &:nth-child(2n){
          margin-left:155px;
        }
        h2{
          font-size:32px;
          line-height:38px;
          color:#A52D11;
          font-family: RobotoNormal;
          font-weight:900;
          padding-bottom:18px;
          padding-top:83px;
        }
        p{
          font-size:24px;
          color:#2D2117;
          line-height:48px;
          font-family: RobotoNormal;
          font-weight:400;
          height:384px;
        }
      }
    }
    .links{
      background:#FFE9C7;
      border:5px solid #2D2117;
      border-radius:85px;
      text-align:center;
      width:718px;
      margin:0 auto;
      a{
        display:inline-block;
        vertical-align: middle;
        width:47.6px;
        margin:0 28px;
        img{
          width:100%;
        }
      }
    }
  }
}
</style>

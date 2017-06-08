<template>
  <div id="">
    <div class="row align-center first_window">
      <div class="column small-12">
        <div class="intro_text ">
          <div class="row column text-center">
            <img class="company_logo" src="../assets/img/logo.png" alt="motion picture solutions logo">
          </div>       
          <div class="company_name">Motion Picture Solutions</div>
          <div class="first_title">Welcome</div>
          <div class="first_second">to</div>
          <div class="first_third"><span style="color:#fbdc00;">MPS</span>.Fun</div>
          <div class="slogan"><p class="text-center">Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p></div>
          <br>
          <div class="row column text-center">
<<<<<<< HEAD
            <button class="hollow button">PLAY NOW</button>
            <p>Skip game, Maybe next time</p>
=======
            <button class="hollow button" @click="play">PLAY NOW</button>
>>>>>>> 9900326fe2ab7bef4076d5909998bc66fffabbae
          </div>
          
        </div>
        <img class="fetti" src="../assets/img/confetti1.png" alt="">
        <img class="fettitwo" src="../assets/img/confetti2.png" alt="">
        <img class="fettithree" src="../assets/img/confetti3.png" alt="">
      </div>
      <img class="shades" src="../assets/img/mps-glasses.png" alt="">

    </div>
    <div class="large-expanded row"></div>
    <div class="cards_info large-12 columns">
      <div class="card_header">
        <h2 class="text-center">Train Your Brain This New Years</h2>
        <p class="text-center">Some small information about the cards and what they repersent</p> 
      </div>
      
      <div class="expanded row large-expanded smal l-up-2 medium-up-3 large-up-4">
        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun1.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun2.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun3.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun5.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>
        <!-- Second Row -->
        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun1.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun2.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun3.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>

        <div class="column vertical_block column-block">
          <div class="column text-center">
            <img class="mps_card_one thumbnail" src="../assets/img/fun6.png" alt="motion picture solutions logo">
          </div>
          <div class="columns">
            <h3>Direct KDM Automation</h3>
            <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
          </div>
        </div>
<<<<<<< HEAD

      </div>
    </div>
    <!-- Oncinema section -->
    <div class="expanded row links">
      <div class="small-12 large-6 columns mps">
        <h3 class="text-center">Motion Picture solutions</h3>
        <p class="text-center">MPS has been creating DCPs since the advent of digital cinema, giving us unparalleled expertise in the sector.</p>
        <div class="text-center">
          <a href="" class="button "> Find out More</a>
        </div>
      </div>
      <div class="small-12 large-6 columns oc">
        <h3 class="text-center">Oncinema</h3>
        <p class="text-center">MPS has been creating DCPs since the advent of digital cinema, giving us unparalleled expertise in the sector.</p>
        <div class="text-center">
          <a href="" class="button "> Find out More</a>
        </div>
      </div>
    </div>
<!-- 
    <footer>
      <div class="expanded row ">
        <div class="large-6 columns">
          <p class="large-4 columns">Motion Picture Solutions, is a forerunner in digital cinema and has been mastering and distributing theatrical content since 2006.</p>
        </div>
        <div class="large-2 columns"></div>
        <div class="large-2 columns"></div>
        <div class="large-2 columns"></div>
      </div>
    </footer>
 -->
=======
        <mps-game v-if="playing"></mps-game>
>>>>>>> 9900326fe2ab7bef4076d5909998bc66fffabbae
  </div>
</template>

<style lang="scss" scoped>
  
  .image {
    margin-top: 0.75rem;
    margin-bottom: 1.5rem;
  }
  .company_logo {
    padding-bottom: 10px;
  }
  .company_name {
    text-align:center;
    letter-spacing: 16px;
    text-transform:uppercase;
  }
  .first_window {
    min-height:1060px;
    position:relative;
    .fetti, .fettitwo, .fettithree {
      position:absolute;
      top:10%;
      width:200%;
    }
  }
  .cards_info {
    background-color:#FFF;
    padding-top:rem-calc(120);
    .card_header {
      padding-bottom:rem-calc(90);
      h2 {
        font-weight:bolder;
      }
    }
    .column-block {
      padding-bottom:rem-calc(30);
    }
    .vertical_block {
      text-align: center;
      img {
        box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
      }
    }
  }
  .oc {
    .button {
      background-color:#C33280;
    }
  }
  .mps {
    .button {
      background-color:#080E1A;
    }
  }
  .card_info_one, .card_info_two, .card_info_three, .card_info_four {
    color:#fff;
    img {
      max-width:40%;
    }
  }
  .intro_text {
    padding-top:rem-calc(250);
    font-family: 'Lato', sans-serif;
    color:#fff;
    .first_title, 
    .first_third {
      font-weight:bolder;
      font-size:rem-calc(120);
      text-transform:uppercase;
      text-align:center;
      line-height:1;
    }
    .first_title {

    }
    .first_second {
      text-align:center;
      font-weight:bolder;
      line-height:0;
    }
  }
  .call-button {
    border-radius: 20px;
    padding-left: 1.5rem;
    padding-right: 1.5rem; 
    font-weight: 600;
    text-transform: uppercase;
  }
  .shades {
    position:absolute;
    bottom:-10px;

  }
  .links {
    .mps {
      background: url('../assets/img/mps_bg.jpg') no-repeat left bottom fixed;
      -webkit-background-size: auto;
      -moz-background-size: auto;
      -o-background-size: auto;
      background-size: auto;
      max-height:rem-calc(190);
      min-height:rem-calc(567);
      padding-right:0 !important;
      padding-left:0 !important;
      color:#161624;
      h3 {
        font-weight:bolder;
        padding-top:rem-calc(250);
      }
    }
    .oc {
      background: url('../assets/img/oc_bg.jpg') no-repeat right bottom fixed;
      -webkit-background-size: auto;
      -moz-background-size: auto;
      -o-background-size: auto;
      background-size: auto;
      max-height:rem-calc(190);
      min-height:rem-calc(567);
      padding-right:0 !important;
      padding-left:0 !important;
      color:#fff;
      h3 {
        font-weight:bolder;
        padding-top:rem-calc(250);
      }
    }

  }
 footer {
  padding-top:rem-calc(90);
  padding-bottom:rem-calc(90);
 }

</style>

<script>
import MpsGame from './MpsGame';

export default {
  name: 'hello',
  data() {
    return {
      msg: 'Vue + Foundation',
      playing: false,
    };
  },
  mounted() {
    // const height = $(window).innerHeight();
    // document.getElementById('first_window').style.height = height;
    // console.log(height);
  },
  methods: {
    play() {
      this.playing = true;
    },
  },
  components: {
    MpsGame,
  },
};
</script>


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
          <div class="first_third">MPS.Fun</div>
          <div class="slogan"><p class="text-center">Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p></div>
          <br>
          <div class="row column text-center">
            <button class="hollow button">PLAY NOW</button>
          </div>
          
        </div>
      </div>
      <img class="shades" src="../assets/img/mps-glasses.png" alt="">

    </div>
    <div class="row align-middle card_info_one">
        <div class="columns">
          <h2>Direct KDM Automation</h2>
          <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
        </div>
        <div class="large-6 columns">
          <img class="mps_card_one" src="../assets/img/fun1.png" alt="motion picture solutions logo">
        </div>
    </div>

        <div class="row align-middle card_info_two">
            <div class="large-6 columns">
              <img class="mps_card_one" src="../assets/img/fun1.png" alt="motion picture solutions logo">
            </div>
            <div class="columns">
              <h2>Direct KDM Automation</h2>
              <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
            </div>
            
        </div>

        <div class="row align-middle card_info_three">
            <div class="columns">
              <h2>Direct KDM Automation</h2>
              <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
            </div>
            <div class="large-6 columns">
              <img class="mps_card_one" src="../assets/img/fun1.png" alt="motion picture solutions logo">
            </div>
        </div>

        <div class="row align-middle card_info_four">
            <div class="large-6 columns">
              <img class="mps_card_one" src="../assets/img/fun1.png" alt="motion picture solutions logo">
            </div>
            <div class="columns">
              <h2>Direct KDM Automation</h2>
              <p>Replace The Negatives In Your Life With Positives And Move Your Life Ahead</p>
            </div>
        </div>
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
    bottom:-10;

  }


</style>

<script>

export default {
  name: 'hello',
  data() {
    return {
      msg: 'Vue + Foundation',
    };
  },
  mounted() {
    // const height = $(window).innerHeight();
    // document.getElementById('first_window').style.height = height;
    // console.log(height);
  },
};
</script>


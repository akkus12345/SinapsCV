<template>
  <div class="loader">
    <div class="square" id="sqr0"></div>
    <div class="square" id="sqr1"></div>
    <div class="square" id="sqr2"></div>
    <div class="square" id="sqr3"></div>
    <div class="square" id="sqr4"></div>
    <div class="square" id="sqr5"></div>
    <div class="square" id="sqr6"></div>
  </div>
</template>

<script>
export default {
  name: "Loading",
};
</script>

<style type="text/css" scoped>
.loader {
  position: absolute;
  width: 20vw;
  height: 20vw;
  left: 50%;
  top: 50%;
  margin-top: -10vw;
  margin-left: -10vw;
  /*
        background: #fff;
        border-radius: 6px;
        box-shadow: 0 0 6px -2px #666;*/
  transform: rotate(45deg);
}
@media (orientation: landscape) {
  .loader {
    width: 20vh;
    height: 20vh;
    left: 50%;
    top: 50%;
    margin-top: -10vh;
    margin-left: -10vh;
  }
}
.square {
  position: fixed;
  width: 30%;
  height: 30%;
  background-color: #69f;
  border-radius: 3px;
  left: 70px;
  top: 5px;

  background: linear-gradient(
    45deg,
    #3edb8d,
    #2caa6b,
    #1e8ec0,
    #973b5e,
    #7533a8,
    #6338ba
  );
  background-size: 1000% 1000%;
  animation: colorGradientFade 16s ease infinite;
}
@keyframes colorGradientFade {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
  /*0%{background:#3edb8d;}
        16%{background:#2caa6b;}
        32%{background:#1e8ec0;}
        48%{background:#973b5e;}
        64%{background:#7533a8;}
        80%{background:#6338ba;}
        96%{background:#3edb8d;}*/
}
#sqr0 {
  left: 5px;
  top: 5px;
  animation: sqr0 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr0 {
  0% {
    left: 2.5%;
    top: 2.5%;
  }
  7.142% {
    left: 2.5%;
    top: 2.5%;
  }
  8.928% {
    left: 35%;
    top: 2.5%;
  }
  19.642% {
    left: 35%;
    top: 2.5%;
  }
  21.428% {
    left: 67.5%;
    top: 2.5%;
  }
  32.142% {
    left: 67.5%;
    top: 2.5%;
  }
  33.928% {
    left: 67.5%;
    top: 35%;
  }
  44.642% {
    left: 67.5%;
    top: 35%;
  }
  46.428% {
    left: 35%;
    top: 35%;
  }
  57.142% {
    left: 35%;
    top: 35%;
  }
  58.928% {
    left: 35%;
    top: 67.5%;
  }
  69.642% {
    left: 35%;
    top: 67.5%;
  }
  71.428% {
    left: 2.5%;
    top: 67.5%;
  }
  82.142% {
    left: 2.5%;
    top: 67.5%;
  }
  83.928% {
    left: 2.5%;
    top: 35%;
  }
  94.642% {
    left: 2.5%;
    top: 35%;
  }
  96.428% {
    left: 2.5%;
    top: 2.5%;
  }
  100% {
    left: 2.5%;
    top: 2.5%;
  }
}
#sqr1 {
  left: 70px;
  top: 5px;
  animation: sqr1 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr1 {
  0% {
    left: 35%;
    top: 2.5%;
  }
  5.357% {
    left: 35%;
    top: 2.5%;
  }
  7.142% {
    left: 67.5%;
    top: 2.5%;
  }
  17.857% {
    left: 67.5%;
    top: 2.5%;
  }
  19.642% {
    left: 67.5%;
    top: 35%;
  }
  30.357% {
    left: 67.5%;
    top: 35%;
  }
  32.142% {
    left: 35%;
    top: 35%;
  }
  42.857% {
    left: 35%;
    top: 35%;
  }
  44.642% {
    left: 35%;
    top: 67.5%;
  }
  55.357% {
    left: 35%;
    top: 67.5%;
  }
  57.142% {
    left: 2.5%;
    top: 67.5%;
  }
  67.857% {
    left: 2.5%;
    top: 67.5%;
  }
  69.642% {
    left: 2.5%;
    top: 35%;
  }
  80.357% {
    left: 2.5%;
    top: 35%;
  }
  82.142% {
    left: 2.5%;
    top: 2.5%;
  }
  92.857% {
    left: 2.5%;
    top: 2.5%;
  }
  94.642% {
    left: 35%;
    top: 2.5%;
  }
  100% {
    left: 35%;
    top: 2.5%;
  }
}
#sqr2 {
  left: 67.5%;
  top: 5px;
  animation: sqr2 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr2 {
  0% {
    left: 67.5%;
    top: 2.5%;
  }
  3.571% {
    left: 67.5%;
    top: 2.5%;
  }
  5.357% {
    left: 67.5%;
    top: 35%;
  }
  16.071% {
    left: 67.5%;
    top: 35%;
  }
  17.857% {
    left: 35%;
    top: 35%;
  }
  28.571% {
    left: 35%;
    top: 35%;
  }
  30.357% {
    left: 35%;
    top: 67.5%;
  }
  41.071% {
    left: 35%;
    top: 67.5%;
  }
  42.857% {
    left: 2.5%;
    top: 67.5%;
  }
  53.571% {
    left: 2.5%;
    top: 67.5%;
  }
  55.357% {
    left: 2.5%;
    top: 35%;
  }
  66.071% {
    left: 2.5%;
    top: 35%;
  }
  67.857% {
    left: 2.5%;
    top: 2.5%;
  }
  78.571% {
    left: 2.5%;
    top: 2.5%;
  }
  80.357% {
    left: 35%;
    top: 2.5%;
  }
  91.071% {
    left: 35%;
    top: 2.5%;
  }
  92.857% {
    left: 67.5%;
    top: 2.5%;
  }
  100% {
    left: 67.5%;
    top: 2.5%;
  }
}
#sqr3 {
  left: 5px;
  top: 70px;
  animation: sqr3 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr3 {
  0% {
    left: 2.5%;
    top: 35%;
  }
  8.928% {
    left: 2.5%;
    top: 35%;
  }
  10.714% {
    left: 2.5%;
    top: 2.5%;
  }
  21.428% {
    left: 2.5%;
    top: 2.5%;
  }
  23.214% {
    left: 35%;
    top: 2.5%;
  }
  33.928% {
    left: 35%;
    top: 2.5%;
  }
  35.714% {
    left: 67.5%;
    top: 2.5%;
  }
  46.428% {
    left: 67.5%;
    top: 2.5%;
  }
  48.214% {
    left: 67.5%;
    top: 35%;
  }
  58.928% {
    left: 67.5%;
    top: 35%;
  }
  60.714% {
    left: 35%;
    top: 35%;
  }
  71.428% {
    left: 35%;
    top: 35%;
  }
  73.214% {
    left: 35%;
    top: 67.5%;
  }
  83.928% {
    left: 35%;
    top: 67.5%;
  }
  85.714% {
    left: 2.5%;
    top: 67.5%;
  }
  96.428% {
    left: 2.5%;
    top: 67.5%;
  }
  98.214% {
    left: 2.5%;
    top: 35%;
  }
  100% {
    left: 2.5%;
    top: 35%;
  }
}
#sqr4 {
  left: 70px;
  top: 70px;
  animation: sqr4 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr4 {
  0% {
    left: 35%;
    top: 35%;
  }
  1.785% {
    left: 35%;
    top: 67.5%;
  }
  12.499% {
    left: 35%;
    top: 67.5%;
  }
  14.285% {
    left: 2.5%;
    top: 67.5%;
  }
  24.999% {
    left: 2.5%;
    top: 67.5%;
  }
  26.785% {
    left: 2.5%;
    top: 35%;
  }
  37.499% {
    left: 2.5%;
    top: 35%;
  }
  39.285% {
    left: 2.5%;
    top: 2.5%;
  }
  49.999% {
    left: 2.5%;
    top: 2.5%;
  }
  51.785% {
    left: 35%;
    top: 2.5%;
  }
  62.499% {
    left: 35%;
    top: 2.5%;
  }
  64.285% {
    left: 67.5%;
    top: 2.5%;
  }
  74.999% {
    left: 67.5%;
    top: 2.5%;
  }
  76.785% {
    left: 67.5%;
    top: 35%;
  }
  87.499% {
    left: 67.5%;
    top: 35%;
  }
  89.285% {
    left: 35%;
    top: 35%;
  }
  100% {
    left: 35%;
    top: 35%;
  }
}
#sqr5 {
  left: 67.5%;
  top: 70px;
  animation: sqr5 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr5 {
  0% {
    left: 67.5%;
    top: 35%;
  }
  1.785% {
    left: 67.5%;
    top: 35%;
  }
  3.571% {
    left: 35%;
    top: 35%;
  }
  14.285% {
    left: 35%;
    top: 35%;
  }
  16.071% {
    left: 35%;
    top: 67.5%;
  }
  26.785% {
    left: 35%;
    top: 67.5%;
  }
  28.571% {
    left: 2.5%;
    top: 67.5%;
  }
  39.285% {
    left: 2.5%;
    top: 67.5%;
  }
  41.071% {
    left: 2.5%;
    top: 35%;
  }
  51.785% {
    left: 2.5%;
    top: 35%;
  }
  53.571% {
    left: 2.5%;
    top: 2.5%;
  }
  64.285% {
    left: 2.5%;
    top: 2.5%;
  }
  66.071% {
    left: 35%;
    top: 2.5%;
  }
  76.785% {
    left: 35%;
    top: 2.5%;
  }
  78.571% {
    left: 67.5%;
    top: 2.5%;
  }
  89.285% {
    left: 67.5%;
    top: 2.5%;
  }
  91.071% {
    left: 67.5%;
    top: 35%;
  }
  100% {
    left: 67.5%;
    top: 35%;
  }
}
#sqr6 {
  left: 5px;
  top: 67.5%;
  animation: sqr6 12s ease infinite, colorGradientFade 16s ease infinite;
}
@keyframes sqr6 {
  0% {
    left: 2.5%;
    top: 67.5%;
  }
  10.714% {
    left: 2.5%;
    top: 67.5%;
  }
  12.499% {
    left: 2.5%;
    top: 35%;
  }
  23.214% {
    left: 2.5%;
    top: 35%;
  }
  24.999% {
    left: 2.5%;
    top: 2.5%;
  }
  35.714% {
    left: 2.5%;
    top: 2.5%;
  }
  37.499% {
    left: 35%;
    top: 2.5%;
  }
  48.214% {
    left: 35%;
    top: 2.5%;
  }
  49.999% {
    left: 67.5%;
    top: 2.5%;
  }
  60.714% {
    left: 67.5%;
    top: 2.5%;
  }
  62.499% {
    left: 67.5%;
    top: 35%;
  }
  73.214% {
    left: 67.5%;
    top: 35%;
  }
  74.999% {
    left: 35%;
    top: 35%;
  }
  85.714% {
    left: 35%;
    top: 35%;
  }
  87.499% {
    left: 35%;
    top: 67.5%;
  }
  98.214% {
    left: 35%;
    top: 67.5%;
  }
  99.999% {
    left: 2.5%;
    top: 67.5%;
  }
  100% {
    left: 2.5%;
    top: 67.5%;
  }
}

#next {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
</style>
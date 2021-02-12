<template>
  <div class="skills" id="Skills">
    <div class="section-header">
      <h1>Skills.</h1>
    </div>
    <div class="container">
      <div class="content d-flex flex-row">
        <div class="svg">
          <div class="tooltips">
            <img src="../assets/svg/html5.svg" alt="html" />
            <span class="tooltipstext">HTML</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/css3.svg" alt="css3" />
            <span class="tooltipstext">CSS</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/javascript.svg" alt="js" />
            <span class="tooltipstext">JavaScript</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/git.svg" alt="git" />
            <span class="tooltipstext">Git</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/php.svg" alt="php" />
            <span class="tooltipstext">PHP</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/mysql.svg" alt="mysql" />
            <span class="tooltipstext">MySQL</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/wordpress.svg" alt="wordpress" />
            <span class="tooltipstext">WordPress</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/vue-dot-js.svg" alt="vue.js" />
            <span class="tooltipstext">VueJs</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/laravel.svg" alt="laravel" />
            <span class="tooltipstext">Laravel</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/adobexd.svg" alt="adobexd" />
            <span class="tooltipstext">Adobe XD</span>
          </div>

          <div class="tooltips">
            <img
              src="../assets/svg/adobeillustrator.svg"
              alt="adobeillustrator"
            />
            <span class="tooltipstext" style="padding: 5px 10px"
              >Adobe Illustrator</span
            >
          </div>

          <div class="tooltips">
            <img src="../assets/svg/adobephotoshop.svg" alt="adobephotoshop" />
            <span class="tooltipstext">Adobe Photoshop</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/figma.svg" alt="figma" />
            <span class="tooltipstext">Figma</span>
          </div>

          <div class="tooltips">
            <img src="../assets/svg/sass.svg" alt="sass" />
            <span class="tooltipstext">SASS</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
$main: #f6f5f5;
$primary: #101010;

$font1: "Source Sans Pro", sans-serif;
$font2: "Roboto", sans-serif;

.skills {
  margin-top: 100px;
  .section-header {
    font-size: 160px;
    font-weight: 800;
    letter-spacing: -0.02em;
    text-align: left;
    z-index: 10;
    position: relative;
    top: 45px;
    padding-left: 85px;

    @media screen and (max-width: 600px) {
      padding-left: 20px;
    }

    h1 {
      color: $primary;
      font-family: $font1;
      font-size: 120px;

      @media screen and (max-width: 600px) {
        font-size: 60px;
        position: relative;
        top: -17px;
      }
    }
  }
  .container {
    background-color: #ee6f57;
    padding: 60px 0;
    max-width: 90%;

    @media screen and (max-width: 600px) {
      padding: 30px;
    }

    .content {
      margin: auto;
      width: 42%;
      padding: 10px;

      img {
        width: 70px;
        margin: 10px;
        transition: transform 0.2s;
      }
      img:hover {
        transform: translateY(-10px);
      }

      @media screen and (max-width: 600px) {
        width: 100%;
        text-align: center;

        img {
          width: 40px;
        }
      }
    }

    /* Tooltip container */
    .tooltips {
      position: relative;
      display: inline-block;
    }

    /* Tooltip text */
    .tooltips .tooltipstext {
      visibility: hidden;
      width: 120px;
      background-color: #222;
      color: #fff;
      text-align: center;
      padding: 5px 0;
      border-radius: 6px;

      /* Position the tooltip text - see examples below! */
      position: absolute;
      z-index: 11;
      bottom: 110%;
      left: 50%;
      margin-left: -60px;
    }

    /* Show the tooltip text when you mouse over the tooltip container */
    .tooltips:hover .tooltipstext {
      visibility: visible;
    }
  }
}
</style>
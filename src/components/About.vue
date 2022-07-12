<template>
  <div class="about" id="About">
    <div class="section-header">
      <h1>About.</h1>
    </div>
    <div class="container">
      <h3>Hi, nice to meet you</h3>
      <p>
        I am Yazid, a Product Designer based in Kuala Lumpur, Malaysia.
        I can codes and I really enjoy design and build
        user interfaces and a well-organized person. I'm incredibly determined 
        when I see something amazing.
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
$main: #f6f5f5;
$primary: #101010;
$secondary: #484848;
$tertiary: #39867c;

$font1: "Source Sans Pro", sans-serif;
$font2: "Roboto", sans-serif;

.about {
  h3 {
    transition: transform 0.2s;
  }
  .container:hover {
    h3 {
      transform: translateY(-10px);
    }
  }

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
    background-color: $tertiary;
    padding: 60px;
    max-width: 90%;

    @media screen and (max-width: 600px) {
      padding: 30px;
    }

    h3 {
      font-family: $font1;
      font-size: 50px;
    }

    p {
      font-family: $font2;
      font-size: 20px;
      margin: auto;
      width: 60%;
    }

    h3,
    p {
      color: $main;
      text-align: center;
      text-justify: inter-word;
      padding: 10px;
    }

    @media screen and (max-width: 600px) {
      h3 {
        font-size: 35px;
      }
      p {
        font-size: 17px;
        text-align: left;
        text-justify: inter-word;
        width: 100%;
      }
    }
  }
}
</style>

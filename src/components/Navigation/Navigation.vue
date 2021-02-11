<template>
  <div>
    <img src="../../assets/svg/logo.png" width="40px" />

    <ul id="nav">
      <li><a href="#About" v-smooth-scroll >About</a></li>
      <li><a href="#Projects" v-smooth-scroll>Projects</a></li>
      <li><a href="#Skills" v-smooth-scroll>Skills</a></li>
      <li><a href="#Contact" v-smooth-scroll>Contact</a></li>
    </ul>
  </div>
</template>

<script>


export default {
  
};
</script>

<style lang="scss" scoped>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40px;
  padding: 15px 0;
}

#nav {
  width: 100%;
  display: inline-block;
  text-align: center;
  padding: 0;
  list-style: none;
}

#nav li {
  display: inline-block;
  text-align: center;
}

#nav li a {
  display: block;
  padding: 8px 15px;
  text-decoration: none;
  font-weight: 500;
  text-align: center;
  color: #484848;
  font-size: 20px;

  // @media only screen and (max-width: 800px) {
  //     font-size: 20px;
  // }
}

#nav li a:hover {
  color: #c3c2c2;
  text-align: center;
}
/* End navigation bar styling. */
</style>
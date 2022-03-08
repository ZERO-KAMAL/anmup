<template>
  <header id="header">
    <div class="menu__bar">
      <div class="container">
        <div
          class="
            header__navbar
            d-flex
            align-items-center
            justify-content-between
          "
        >
          <div class="header__left-navbar d-flex align-items-center">
            <div class="brand__logo">
              <img src="../assets/images/logo.svg" alt="" />
            </div>
            <ul class="d-flex align-items-center">
              <li><a href="#"> services </a></li>
              <li><a href="#"> company </a></li>
              <li><a href="#"> products </a></li>
            </ul>
          </div>
          <div class="header__right-navbar">
            <button class="btn btn-first">contact us</button>
          </div>
        </div>
      </div>
    </div>

    <div class="main__banner">
      <div class="container">
        <div class="row d-flex align-items-center justify-content-center">
          <div class="col-md-8 text-center">
            <div class="main__banner-content">
              <h1>Are you start up willing to grow ?</h1>
              <p>We bring all the business requirement at one place for you.</p>
              <div class="main__banner-btns">
                <button class="btn btn-first">Join AO</button>
                <button class="btn btn-second ms-4">Discover AO</button>
              </div>
            </div>
          </div>
          <div class="col-md-12">
            <div class="main__banner-img">
              <img
                src="../assets/images/banner-img.svg"
                alt=""
                width="100%"
                height="100%"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  //components name
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
};
</script>


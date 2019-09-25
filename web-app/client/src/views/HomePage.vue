<template>
  <div>
    <!--::header part start::-->
    <header
      class="main_menu home_menu"
      :class="{ 'home_menu menu_fixed animated fadeInDown': scrolled }"
    >
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-12">
            <nav class="navbar navbar-expand-lg navbar-light">
              <a class="navbar-brand" href="index.html">
                <img id="logo-aa" src="img/AWACA_Logo_sun-02.png" alt="logo" />
              </a>
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="menu_icon">
                  <i class="fas fa-bars"></i>
                </span>
              </button>

              <div class="collapse navbar-collapse main-menu-item" id="navbarSupportedContent">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link" href="index.html">TRANG CHỦ</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a
                      class="nav-link dropdown-toggle"
                      href="blog.html"
                      id="navbarDropdown1"
                      role="button"
                      data-toggle="dropdown"
                      aria-haspopup="true"
                      aria-expanded="false"
                    >CÁC KHÓA HỌC</a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown1">
                      <a class="dropdown-item" href="elements.html">Elements</a>
                    </div>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="pricing.html">TIN TỨC</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link">TECH BLOG</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="contact.html">LIÊN HỆ</a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <!-- Header part end-->

    <!-- banner part start-->
    <section class="banner_part">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-7">
            <div class="banner_text">
              <div class="banner_text_iner">
                <h1>
                  Drive More Customers
                  Through Digital
                </h1>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                  sed do eiusmod tempor incididunt ut labore et dolore magna
                  aliqua. Ut enim ad minim veniam.
                </p>
                <a href="#" class="btn_2 banner_btn_1">Get Started</a>
                <a href="#" class="btn_2 banner_btn_2">Sign up for free</a>
              </div>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="banner_img d-none d-lg-block">
              <img src="img/banner_img.png" alt />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- banner part start-->

    <!-- feature_part start-->
    <section class="feature_part padding_top">
      <div class="container">
        <div class="row align-items-center justify-content-between">
          <div class="col-lg-6">
            <div class="row align-items-center">
              <div class="col-lg-6 col-sm-6">
                <div class="single_feature">
                  <div class="single_feature_part">
                    <img src="img/icon/feature_icon_1.png" alt />
                    <h4>A Volunteer</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed do eiusmod tempor</p>
                  </div>
                </div>
              </div>
              <div class="col-lg-6 col-sm-6">
                <div class="single_feature">
                  <div class="single_feature_part">
                    <img src="img/icon/feature_icon_2.png" alt />
                    <h4>A Volunteer</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed do eiusmod tempor</p>
                  </div>
                </div>
                <div class="single_feature">
                  <div class="single_feature_part single_feature_part_2">
                    <img src="img/icon/feature_icon_3.png" alt />
                    <h4>A Volunteer</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipiscing elit sed do eiusmod tempor</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-5">
            <div class="feature_part_text">
              <h2>featured</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua. Quis ipsum suspendisse
                ultrices gravida Risus com odo viverra maecenas accumsan lacus vel facilisis
                accumsan.
              </p>
              <div class="row">
                <div class="col-sm-6 col-md-4 col-lg-5">
                  <div class="feature_part_text_iner">
                    <h4>50k</h4>
                    <p>Total Volunteer</p>
                  </div>
                </div>
                <div class="col-sm-6 col-md-4 col-lg-5">
                  <div class="feature_part_text_iner">
                    <h4>100k</h4>
                    <p>Successed Mission</p>
                  </div>
                </div>
              </div>
              <a href="#" class="btn_4">
                learn more
                <img src="img/icon/right-arrow.svg" alt />
              </a>
            </div>
          </div>
        </div>
      </div>

      <img src="img/animate_icon/Shape-1.png" alt class="feature_icon_1" />
      <img src="img/animate_icon/Shape-14.png" alt class="feature_icon_2" />
      <img src="img/animate_icon/Shape.png" alt class="feature_icon_3" />
      <img src="img/animate_icon/shape-3.png" alt class="feature_icon_4" />
    </section>
    <!-- upcoming_event part start-->

    <!-- about_us part start-->
    <section class="about_us section_padding">
      <div class="container">
        <div class="row align-items-center justify-content-between">
          <div class="col-md-6 col-lg-5">
            <div class="about_us_text">
              <h2>
                Right people at the
                Right time.
              </h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                sed do eiusmod tempor incididunt ut labore et dolore magna
                aliqua. Ut enim ad minim
              </p>
              <a href="#" class="btn_1">get started</a>
              <a href="#" class="btn_2">sing up free</a>
            </div>
          </div>
          <div class="col-md-6 col-lg-6">
            <div class="learning_img">
              <img src="img/about_img.png" alt />
            </div>
          </div>
        </div>
      </div>
      <img src="img/left_sharp.png" alt class="left_shape_1" />
      <img src="img/about_shape.png" alt class="about_shape_1" />
      <img src="img/animate_icon/Shape-16.png" alt class="feature_icon_1" />
      <img src="img/animate_icon/Shape-1.png" alt class="feature_icon_4" />
    </section>
    <!-- about_us part end-->
  </div>
</template>

<script>
export default {
  data() {
    return {
      scrolled: false
    };
  },
  methods: {
    handleScroll() {
      this.scrolled = window.scrollY > 50;
    }
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed() {
    window.removeEventListener("scroll", this.handleScroll);
  }

  // var window_top = $(window).scrollTop() + 1;
  // if (window_top > 50) {
  //   $('.main_menu').addClass('menu_fixed animated fadeInDown');
  // } else {
  //   $('.main_menu').removeClass('menu_fixed animated fadeInDown');
  // }
};
</script>

<style>
#logo-aa {
  width: 160px;
}
</style>
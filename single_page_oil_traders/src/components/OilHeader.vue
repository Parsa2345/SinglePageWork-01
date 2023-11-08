<template>
  

  <!-- Header 
  ============================================= -->
  <header id="home">

      <!-- Start Navigation -->
      <nav class="navbar navbar-default inc-top-bar navbar-fixed navbar-transparent white bootsnav">

          <div class="container-full">

            <!-- Start Atribute Navigation -->
              <div class="attr-nav">
                  <div class="call">
                      <div class="icon">
                          <i class="fas fa-phone"></i>
                      </div>
                      <div class="info">
                          <span>Have any question?</span>
                          <h5>(012) 66795453677</h5>
                      </div>
                  </div>
              </div>        
              <!-- End Atribute Navigation -->

              <!-- Start Header Navigation -->
              <div class="navbar-header">
                  <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-menu">
                      <i class="fa fa-bars"></i>
                  </button>
                  <a class="navbar-brand" href="index.html">
                      <img src="assets/img/logo-light.png" class="logo logo-display" alt="Logo">
                      <img src="assets/img/logo-red.png" class="logo logo-scrolled" alt="Logo">
                  </a>
              </div>
              <!-- End Header Navigation -->

              <!-- Collect the nav links, forms, and other content for toggling -->
              <div class="collapse navbar-collapse" id="navbar-menu">
                  <ul class="nav navbar-nav navbar-center" data-in="#" data-out="#">
                      <li >
                          <a href="#home" class="dropdown-toggle smooth-menu active" data-toggle="dropdown" >Home</a>
                      </li>
                      <li>
                          <a class="smooth-menu" href="#about">About</a>
                      </li>
                      <li>
                          <a class="smooth-menu" href="#services">Services</a>
                      </li>
                      <li>
                          <a class="smooth-menu" href="#team">Team</a>
                      </li>
                      <li>
                          <a class="smooth-menu" href="#projects">Projects</a>
                      </li>
                      <li>
                          <a class="smooth-menu" href="#blog">blog</a>
                      </li>
                  </ul>
              </div><!-- /.navbar-collapse -->
          </div>

      </nav>
      <!-- End Navigation -->

  </header>
  <!-- End Header -->


</template>

<script>
export default {
  name: 'OilHeader',
  props: { 
  }
}
</script>

 
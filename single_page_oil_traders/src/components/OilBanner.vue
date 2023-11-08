<template> 


  <!-- Start Banner 
  ============================================= -->
  <div class="banner-area inc-video top-pad-50">
      
      <div id="bootcarousel" class="carousel text-light slide carousel-fade animate_text" data-ride="carousel">

          <!-- Indicators for slides -->
          <div class="carousel-indicator">
              <div class="container">
                  <div class="row">
                      <div class="col-lg-12">
                          <ol class="carousel-indicators right">
                              <li data-target="#bootcarousel" data-slide-to="0" class="active"></li>
                              <li data-target="#bootcarousel" data-slide-to="1"></li>
                          </ol>
                      </div>
                  </div>
              </div>
          </div>

          <!-- Wrapper for slides -->
          <div class="carousel-inner">
              <div class="carousel-item bg-cover active" style="background-image: url(assets/img/2440x1578.png);">
                  <div class="box-table">
                      <div class="box-cell shadow dark">
                          <div class="container">
                              <div class="row">
                                  <div class="col-lg-8">
                                      <div class="content">
                                          <a href="https://www.youtube.com/watch?v=owhuBrGIOsE" class="popup-youtube light video-play-button relative">
                                              <i class="ti-control-play"></i> <span>Watch Video</span>
                                          </a>
                                          <h2 data-animation="animated slideInRight">We Provide Business Planing <span>Solution</span></h2>
                                          <a data-animation="animated zoomInUp" class="btn btn-theme effect btn-md" href="#">Discover More</a>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                      <!-- Shape -->
                      <div class="shape-right-bottom"  data-animation="animated slideInUp" style="background-image: url(assets/img/shape/banner-right-shape.png);"></div>
                      <!-- Shape -->
                  </div>
              </div>
              <div class="carousel-item bg-cover" style="background-image: url(assets/img/2440x1578.png);">
                  <div class="box-table">
                      <div class="box-cell shadow dark">
                          <div class="container">
                              <div class="row">
                                  <div class="col-lg-8">
                                      <div class="content">
                                          <a href="https://www.youtube.com/watch?v=owhuBrGIOsE" class="popup-youtube light video-play-button relative">
                                              <i class="ti-control-play"></i> <span>Watch Video</span>
                                          </a>
                                          <h2 data-animation="animated slideInUp">Find Value And Build Some <span>Confidence</span></h2>
                                          <a data-animation="animated zoomInUp" class="btn btn-theme effect btn-md" href="#">Discover More</a>
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                      <!-- Shape -->
                      <div class="shape-right-bottom"  data-animation="animated slideInUp" style="background-image: url(assets/img/shape/banner-right-shape.png);"></div>
                      <!-- Shape -->
                  </div>
              </div>
          </div>
          <!-- End Wrapper for slides -->

      </div>
  </div>
  <!-- End Banner -->

</template>

<script>
export default {
  name: 'OilBanner',
  props: { 
  }
}
</script>

 
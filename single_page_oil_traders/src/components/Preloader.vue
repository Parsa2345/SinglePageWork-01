<template> 


  <!-- Start Preloader 
  ============================================= -->
  <div id="preloader">
      <div id="earna-preloader" class="earna-preloader">
          <div class="animation-preloader">
              <div class="spinner"></div>
              <div class="txt-loading">
                  <span data-text-preloader="A" class="letters-loading">
                      A
                  </span>
                  <span data-text-preloader="U" class="letters-loading">
                      U
                  </span>
                  <span data-text-preloader="R" class="letters-loading">
                      R
                  </span>
                  <span data-text-preloader="O" class="letters-loading">
                      O
                  </span>
                  <span data-text-preloader="R" class="letters-loading">
                      R
                  </span>
                  <span data-text-preloader="A" class="letters-loading">
                      A
                  </span>
              </div>
          </div>
          <div class="loader">
              <div class="row">
                  <div class="col-3 loader-section section-left">
                      <div class="bg"></div>
                  </div>
                  <div class="col-3 loader-section section-left">
                      <div class="bg"></div>
                  </div>
                  <div class="col-3 loader-section section-right">
                      <div class="bg"></div>
                  </div>
                  <div class="col-3 loader-section section-right">
                      <div class="bg"></div>
                  </div>
              </div>
          </div>
      </div>
  </div>
  <!-- End Preloader -->

</template>

<script>
export default {
  name: 'Preloader',
  props: { 
  }
}
</script>

 
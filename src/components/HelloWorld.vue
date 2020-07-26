<template>
  <div>
    <header id="site-header" class="nav is-fixed">
        <div class="container">
          <scrollactive
            ref="scrollactive"
            :offset="offset"
            :always-track="alwaysTrack"
            :duration="duration"
            :click-to-scroll="clickToScroll"
            :bezier-easing-value="easing"
          >
            <ul class="nav-center">
              <li>
                <a href="#section-1" class="scrollactive-item nav-item">Section 1</a>
              </li>
              <li>
                <a href="#section-2" class="scrollactive-item nav-item">Section 2</a>
              </li>
              <li>
                <a href="#section-3" class="scrollactive-item nav-item">Section 3</a>
              </li>
              <li>
                <a href="#section-4" class="scrollactive-item nav-item">Section 4</a>
              </li>
            </ul>
          </scrollactive>
        </div>
      </header>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
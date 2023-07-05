<template>
    <!-- Footer -->
    <footer class="bg-dark text-center">
      <!-- Grid container -->
      <div class="container p-4">
        <!-- Section: Social media -->
        <section class="mb-4">
          <!-- Facebook -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #3b5998"
            href="https://www.facebook.com/profile.php?id=100091889492469&mibextid=ZbWKwL"
            role="button"
            ><i class="fab fa-facebook-f"></i
          ></a>

          <!-- Twitter -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #55acee"
            href="https://twitter.com/Cellovfx?t=1D6_QmZ-1rKySr7FDu6WPw&s=31"
            role="button"
            ><i class="fab fa-twitter"></i
          ></a>

          <!-- Instagram -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #ac2bac"
            href="https://instagram.com/cellovfx?igshid=ZGUzMzM3NWJiOQ=="
            role="button"
            ><i class="fab fa-instagram"></i
          ></a>

          <!-- Github -->
          <a
            class="btn btn-primary btn-floating m-1"
            style="background-color: #333333"
            href="https://github.com/MarcelBrown17"
            role="button"
            ><i class="fab fa-github"></i
          ></a>
        </section>
        <!-- Section: Social media -->

        <!-- Section: Links -->
        <section class="links">
          <!--Grid row-->
          <div class="row">
            <div class="col-lg-1 col-md-6 mb-4 mb-md-0"></div>
            <!--Grid column-->
            <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                <router-link to="/" class="link">
                <h5 class="text-uppercase text-light">Home</h5></router-link
              >
            </div>
            <!--Grid column-->

            <!--Grid column-->
            <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                <router-link to="/products" class="link">
                <h5 class="text-uppercase text-light">Products</h5></router-link
              >
            </div>
            <!--Grid column-->

            <!--Grid column-->
            <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                <router-link to="/admin" class="link">
                <h5 class="text-uppercase text-light">Admin</h5></router-link
              >
            </div>
            <!--Grid column-->

            <!--Grid column-->
            <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                <router-link to="/contact" class="link">
                <h5 class="text-uppercase text-light">Contact</h5></router-link
              >
            </div>
            <!--Grid column-->
            
            <!--Grid column-->
            <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                <router-link to="/about" class="link">
                <h5 class="text-uppercase text-light">About</h5></router-link
              >
            </div>
            <!--Grid column-->
            <div class="col-lg-1 col-md-6 mb-4 mb-md-0"></div>
            
          </div>
          <!--Grid row-->
        </section>
        <!-- Section: Links -->
      </div>
      <!-- Grid container -->

      <!-- Copyright -->
      <div
        class="text-center p-3 text-light"
        style="background-color: rgba(0, 0, 0, 0.2)"
      >
        © 2023 Copyright: Marcel
      </div>
      <!-- Copyright -->
      <!-- Footer -->
    </footer>
</template>
<script>
export default {

}
</script>

<style>
.link {
    text-decoration: none !important;
    }
</style>
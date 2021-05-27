<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Lapar, Makan Kuy!</strong> <br />
                Cara kenyang tanpa ribet
              </h2>
              <p>Cepat order menunya, suara perutmu tidak bisa berbohong</p>
              <router-link class="btn btn-lg btn-success" to="/foods">
                <b-icon-arrow-right-circle-fill></b-icon-arrow-right-circle-fill
                >Kuy Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/images/Hero.svg" width="100%" />
        </div>
      </div>
    </div>

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
          <div class="col-md-6 mb-3">
          <img src="../assets/images/Hero.svg" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Lapar, Makan Kuy!</strong> <br />
                Cara kenyang tanpa ribet
              </h2>
              <p>Cepat order menunya, suara perutmu tidak bisa berbohong</p>
              <button class="btn btn-lg btn-success">
                <b-icon-arrow-right-circle-fill></b-icon-arrow-right-circle-fill
                >Kuy Pesan
              </button>
            </div>
          </div>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>
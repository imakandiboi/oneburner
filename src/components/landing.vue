<template>
  <div>
    <div class="container-fluid hero">
      <div class="row hero-section">
        <div class="col-md-6 hero-text d-flex flex-column">
          <div class="lead-text">
            <h2>Collaborate with your team and get more done</h2>
          </div>
          <div style="margin-bottom: 30px">
            <h5>Collaborate efffectively with Oneburner for easy</h5>
            <h5>collaboration,teamwork and remote work</h5>
          </div>
          <button type="button" class="btn">
            start free trail
            <i class="fas fa-arrow-right"></i>
          </button>
        </div>
        <div class="col-md-6">
          <div class="hero-image">
            <img src="../assets/image-hero.png" alt="" srcset="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "landing",
};
</script>

<style scoped>
.hero {
  padding: 6% 30px;
  height: 100%;
  justify-content: space-between;
}
.hero-text {
  position: relative;
  top: 20%;
  text-align: start;

  padding: 10% 6%;
}

.lead-text {
  margin-bottom: 20px;
  color: #370080;
}
.lead-text h2 {
  font-size: 40px;
  font-weight: bolder;
}
.btn {
  color: white !important;
  background-color: #370080 !important;
  border-radius: 30px !important;
  outline: none !important;
}
.hero-image {
  width: 80%;
  height: 10%;
}
@media only screen and (max-width: 600px) {
  img {
    width: 270px;
  }
}
@media only screen and (max-width: 1024px) {
  img {
    width: 270px;
  }
}
</style>
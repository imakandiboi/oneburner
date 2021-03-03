<template>
  <div>
    <div class="container-fluid support-section">
      <div class="row">
        <div class="col-md-6">
          <div class="row">
            <div class="col-md-6 icon-section">
              <div class="d-flex justify-content-end flex-column">
                <div class="icons">
                  <i class="fas fa-comment-alt"></i>
                  <h6>Live Chat</h6>
                </div>
                <div class="icons">
                  <i class="fas fa-envelope"></i>
                  <h6>Mail Support</h6>
                </div>
                <div class="icons">
                  <i class="fas fa-phone-alt"></i>
                  <h6>Phone Call Support</h6>
                </div>
              </div>
            </div>
            <div class="col-md-6">
              <img src="../assets/lady.png" alt="" srcset="" width="320px" />
            </div>
          </div>
        </div>
        <div class="col-md-6 hero-text d-flex flex-column" style="width: 100%">
          <div class="lead-text">
            <h2>24/7 Customer Support</h2>
          </div>
          <div style="margin-bottom: 30px">
            <h6>
              Our team of responsible member is always available <br />to help
              you all day long, and ready to meet your demand .
            </h6>
            <h6>Reach out to us and we will always be there</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "customerSupport",
};
</script>

<style scoped >
.support-section {
  padding: 5% 2%;
}
.icons {
  font-size: 20px;
  margin: 20px 20px;
}
.hero-text {
  position: relative;
  top: 20%;
  text-align: start;

  padding: 3% 6%;
}

.lead-text {
  margin-bottom: 20px;
  color: #370080;
}
.lead-text h2 {
  font-size: 30px;
  font-weight: bolder;
}

@media only screen and (max-width: 600px) {
  img {
    width: 250px;
  }
}
@media only screen and (max-width: 1024px) {
  img {
    width: 200px;
  }
}
</style>
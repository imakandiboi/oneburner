<template>
  <div>
    <div class="container-fluid hero">
      <div class="row hero-section">
        <div class="col-md-6">
          <div class="hero-image">
            <img src="../assets/team.png" alt="" srcset="" />
          </div>
        </div>
        <div class="col-md-6 hero-text d-flex flex-column">
          <div class="lead-text">
            <h2>Bring your team up to speed</h2>
          </div>
          <div style="margin-bottom: 30px">
            <h6>
              Collaborate on project from start to finish, see information at a
            </h6>
            <h6>glance,add comment, attachment and more with Oneburner.</h6>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TeamProject",
};
</script>

<style scoped>
.hero {
  padding: 6%;
  height: 70%;
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
  font-size: 30px;
  font-weight: bolder;
}

.hero-image {
  width: 80%;
  margin: 0 !important;
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
<template>
  <div class="box">
    <div class="container d-flex flex-wrap brand">
      <div>
        <a href=""><h6>CRM & SALES</h6></a>
      </div>
      <div>
        <a href=""><h6>Human Resource</h6></a>
      </div>

      <div>
        <a href=""><h6>Marketing</h6></a>
      </div>

      <div>
        <a href=""><h6>Remote Work</h6></a>
      </div>

      <div>
        <a href="http://"> <h6>Project Management</h6></a>
      </div>

      <div>
        <a href=""><h6>Social Media</h6></a>
      </div>
    </div>

    <div class="container-fluid hero">
      <div class="row hero-section">
        <div class="col-md-6 hero-text d-flex flex-column">
          <div class="lead-text">
            <h2>Manage team Activities all in one place</h2>
          </div>
          <div style="margin-bottom: 30px">
            <h6>keep your team organised and informed in all activities</h6>
            <h6>that are up-to-date</h6>
          </div>
        </div>
        <div class="col-md-6">
          <div class="hero-image">
            <img src="../assets/activity.png" alt="" srcset="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "teamActivity",
};
</script>

<style scoped>
.brand {
  display: flex;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: space-around;
  border: 2px solid #370080;
  border-radius: 10px;
}
.brand > div {
  width: 100px;
  margin: 10px 20px;
  text-align: center;

  font-size: 5px;
}
.brand a {
  color: #150130;
  text-decoration: none;
}
.box {
  padding: 5% 0px;
  -webkit-box-shadow: 0px 0px 10px -4px rgba(0, 0, 0, 0.86);
  -moz-box-shadow: 0px 0px 10px -4px rgba(0, 0, 0, 0.86);
  box-shadow: 0px 0px 10px -4px rgba(0, 0, 0, 0.86);
}
.hero {
  padding: 6% 30px;
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
<template>
  <div>
    <div class="container-fluid footer-section">
      <div class="row">
        <div class="container footer-brand d-flex justify-content-between">
          <h3 style="color: #370080">
            <span style="font-weight: 800">One</span>burner
          </h3>
          <button class="btn btn-lg">
            <h5>
              <i class="fas fa-globe"></i>
              English
            </h5>
          </button>
        </div>
        <div class="col-md-4 d-flex flex-column contact">
          <p>No.1 CRM solution in Africa</p>
          <p>Term of Use | Privacy Policy</p>
          <p>Get in Touch</p>
          <p>+234-(808)-020-2021</p>
          <div class="contact-icon">
            <div class="col-md-4 d-flex flex-row">
              <div class="icon">
                <a href="#"><i class="fab fa-facebook-square"></i></a>
              </div>
              <div class="icon">
                <a href="#"><i class="fab fa-twitter-square"></i></a>
              </div>
              <div class="icon">
                <a href="#"><i class="fab fa-linkedin"></i></a>
              </div>
              <div class="icon">
                <a href="#"><i class="fab fa-youtube"></i></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8">
          <div class="row justify-content-end">
            <div class="d-flex flex-column text-md-left footer-info">
              <h6>PRODUCT</h6>
              <p>Feature</p>
              <p>Enterprise</p>
              <p>security</p>
              <p>Trust</p>
              <p>Customer Stories</p>
              <p>Pricing</p>
              <p>Integrations</p>
              <p>OneBurner Partner</p>
            </div>
            <div class="d-flex flex-column text-md-left footer-info">
              <h6>COMPANY</h6>
              <p>About Us</p>
              <p>Contact Us</p>
              <p>Career</p>
              <p>In the News</p>
              <p>Customer Stories</p>
            </div>
            <div class="d-flex flex-column text-md-left footer-info">
              <h6>ONEBURNER FOR TEAM</h6>
              <p>Engineering</p>
              <p>Financial Service</p>
              <p>CRM & Sales</p>
              <p>IT</p>
              <p>Marketing</p>
              <p>Customer Support</p>
            </div>
            <div class="d-flex flex-column text-md-left footer-info">
              <h6>RESOURCE</h6>
              <p>Community</p>
              <p>Guide</p>
              <p>template</p>
              <p>Video Tutorial</p>
              <p>Blog</p>
              <p>Webinar</p>
              <p>Find A Partner</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer-brand {
  width: 100%;
  display: inline-block;
  margin-bottom: 50px;
}
.btn {
  width: 100px;
  background: white;
  color: #0f0780;
  border-radius: 10px;
  border: 2px #0f0780 solid;
}
.btn h5 {
  font-size: 10px !important;
  margin: 0px;
}
.footer-section {
  padding: 3% 3%;
}

.contact {
  font-size: 10px;
  text-align: left;
}
.contact p {
  margin-left: 4%;
}
.contact-icon {
  display: block;
}
.icon {
  width: 30px;
  height: 30px;
}
.icon .fab {
  font-size: 20px;
  color: black;
}
.footer-info {
  width: 150px;
  font-size: 10px;
}
.footer-info h6 {
  font-size: 15px;
  font-weight: bolder;
  margin-bottom: 20px;
}
</style>
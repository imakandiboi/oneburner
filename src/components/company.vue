<template>
  <div>
    <div class="container text-align-center">
      <h5>Over 500+ companies and bond team together with Oneburner</h5>
    </div>
    <div class="container d-flex flex-wrap gap-2 brand">
      <div>
        <img src="../assets/PAYSTACK.png" alt="" srcset="" />
      </div>
      <div>
        <img src="../assets/mtn.png" alt="" srcset="" />
      </div>

      <div>
        <img src="../assets/BANK.png" alt="" srcset="" />
      </div>

      <div>
        <img src="../assets/EGYPT-AIR.png" alt="" srcset="" />
      </div>

      <div>
        <img src="../assets/SKOOLEEO.png" alt="" srcset="" />
      </div>

      <div>
        <img src="../assets/GTBANK.png" alt="" srcset="" />
      </div>

      <div>
        <img src="../assets/DANGOTE.png" alt="" srcset="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "company",
};
</script>

<style scoped>
.brand {
  display: flex;
  flex-wrap: nowrap;
  padding: 3% 0px;
  justify-content: space-around;
}
.brand > div {
  width: 100px;
  margin: 20px 20px;
  text-align: center;
  line-height: 75px;
  font-size: 30px;
}
</style>
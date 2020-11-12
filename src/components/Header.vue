<template>
  <div class="header container">
    <div class="d-flex">
      <div class="col-12 col-md-9 col-lg-5">
        <h1 class="heading header-md mt-5 pt-5">
          Earn freebies with your active social media account!
        </h1>
        <small class="text-white">Become a Mini-Social Influencer</small>
        <div class="my-5">
          <button class="btn btn-danger-custom px-4">
            Sign Up
          </button>
        </div>
      </div>
      <div class="translated-div d-none d-lg-block"></div>
      <img
        class="translated-div-image d-none d-lg-block"
        src="/svgs/header1.svg"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<style scoped>
@media (max-width: 576px) {
  .heading {
    font-size: 50px !important;
  }
}
.heading {
  font-style: normal;
  font-weight: 600;
  font-size: 70px;
  line-height: 66px;
  /* or 94% */

  letter-spacing: -3.8px;

  color: #ffffff;
}
.translated-div {
  position: absolute;
  width: 1157.8px;
  height: 629px;
  left: 647px;
  top: 4rem;
  background: linear-gradient(
    331.49deg,
    #c90404 0.67%,
    #a10000 50.16%,
    #5d0101 99.44%
  );
  overflow: hidden;
  z-index: -10;
  border-radius: 400px;
  transform: rotate(-28deg);
}
.translated-div-image {
  position: absolute;
  top: 6.5rem;
  right: 9rem;
}
</style>

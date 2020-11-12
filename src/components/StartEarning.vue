<template>
  <div class="start-earning container">
    <div class="row">
      <div class="col-12 col-md-10 col-lg-8">
        <h2 class="text-white c-start-earning-text">
          Start earning with your social media
        </h2>
        <p class="my-5 w-100 c-text-primary">
          Ads are gradually being displaced and influencer marketing is taking
          its place. 86% of brands now use influencer marketing as a form of
          content marketing to get value for their brands and products.
        </p>
        <div class="d-flex">
          <div class="pr-2">
            <div class="w-100 d-flex justify-content-center">
              <img src="/svgs/money-insurance.svg" />
            </div>
            <p class="text-white mt-3">
              Social currency &nbsp; =
            </p>
          </div>
          <div class="px-1">
            <div class="w-100 d-flex justify-content-center">
              <img class="mx-auto" src="/svgs/warning.svg" />
            </div>
            <p class="text-white mt-3">
              attention &nbsp; +
            </p>
          </div>
          <div class="pl-2">
            <div class="w-100 d-flex justify-content-center">
              <img class="mx-auto" src="/svgs/campaign-launch.svg" />
            </div>
            <p class="text-white mt-3">
              action
            </p>
          </div>
        </div>
        <p class="mb-3 mt-2 w-100 c-text-primary__v1">
          If you have engagement and your content typically drives action with
          your followers every day, you should be earning with it. Got up to
          2500 followers with a beautiful feed and impressive engagement? Why
          not SIGN UP to Stan Social and maximise your social media page to the
          maximum.
        </p>
        <p class="mb-3 w-100 c-text-primary__v1">
          We understand that growing a social media page requires creativity,
          hard work, determination and consistency, why then should you let it
          be just a page. Stan Social outside of maximizing social media
          mentions for the brands you are affiliated with, is also a platform
          for selling, networking and other promotions.
        </p>
      </div>
      <div class="col-md-4 d-none d-lg-block" style="position: relative">
        <div class="start-earning-svg"></div>
      </div>
    </div>
  </div>
</template>

<style>
.start-earning {
  padding-top: 15rem;
}
@media (max-width: 992px) {
  .start-earning {
    padding-top: 5rem;
  }
}
@media (max-width: 576px) {
  .c-start-earning-text {
    font-size: 45px !important;
  }
}
.c-start-earning-text {
  font-style: normal;
  font-weight: 400;
  font-size: 64px;
  line-height: 62px;
  /* or 97% */

  letter-spacing: -1.1px;
}
.start-earning-svg {
  position: absolute;
  width: 155%;
  height: 100%;
  left: -6rem;
  top: 4rem;
  z-index: 50;
  background: url("/svgs/start-earning.svg");
}
.c-text-primary {
  color: rgb(129, 137, 146);
}
.c-text-primary__v1 {
  font-size: 0.8rem;
  line-height: 1.3rem;
  letter-spacing: -0.7px;

  color: #818992;
}
</style>

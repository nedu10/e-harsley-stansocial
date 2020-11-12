<template>
  <div class="perks pb-5">
    <div class="container py-5">
      <p class="perk-head c-text-primary">perks</p>
      <div class="row px-2 px-md-5">
        <div class="col-11 col-md-7 ">
          <h4 class="c-start-earning-text__v2">
            At Stan Social, you enjoy
          </h4>
          <div class="d-flex my-2" v-for="(perk, index) in perks" :key="index">
            <div class="col-2 col-sm-1 c-perk-numbering">
              <a class="text-white c-centering">{{ index + 1 }}</a>
            </div>
            <div class="col-10 col-sm-11">
              <h6 class="text-white">
                {{ perk.name }}
              </h6>
              <p class="c-text-primary__v1">
                {{ perk.description }}
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-5 d-none d-md-block">
          <div class="h-100 perk-image w-100"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      perks: [
        {
          name: "Freebies",
          description:
            "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenea commodo ligula eget dolor. Aenean massa."
        },
        {
          name: "Invitations to top events",
          description:
            "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. "
        },
        {
          name: "Cash incentives",
          description:
            "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenea commodo ligula eget dolor. Aenean massa."
        },
        {
          name: "A unique STANSOCIAL ID.",
          description:
            "Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenea commodo ligula eget dolor. Aenean massa."
        }
      ]
    };
  }
};
</script>
<style scoped>
.perks {
  margin-top: 10rem;
  margin-left: 0;
  margin-right: 0;
  min-width: 110% !important;
  background-color: #292d33;
}

@media (max-width: 992px) {
  .perks {
    margin-top: 5rem;
    margin-left: 0;
    margin-right: 0;
    min-width: 110% !important;
    background-color: #292d33;
  }
}
.perk-head:before {
  content: url("/svgs/perk-head.svg");
  padding-right: 0.5rem;
}
.c-start-earning-text__v2 {
  font-style: normal;
  font-weight: 200;
  font-size: 2.5rem;
  line-height: 62px;
  color: white;
  letter-spacing: -1.1px;
}
.c-centering {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.c-perk-numbering {
  height: 44px;
  border: 1px solid red;
  border-radius: 50%;
}
.perk-image {
  background-image: url("/svgs/perk.svg");
  background-position: center;
  background-size: contain;
  background-repeat: no-repeat;
}
</style>

<template>
  <div class="best">
    <div class="container">
      <div class="best-wrapper">
        <div class="best-wrapper__title">
          We’re more than proud of the +70,000 hours we’ve worked to deliver
          succesful digital products in different industries. See some of it.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Best",
};
</script>

<style lang="scss" scoped>
.best {
  padding: 50px 0px;
  background: linear-gradient(273.36deg, #003166 0%, #007aff 100%);
}
.best-wrapper__title {
  color: white;
  font-size: 20px;
  width: 55%;
}
@media screen and (max-width: 1200px) {
  .best-wrapper {
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 576px) {
  .best-wrapper {
    display: flex;
    justify-content: flex-start;
  }
  .best-wrapper__title {
    text-align: start;
    width: 95%;
    font-size: 18px;
  }
}
</style>

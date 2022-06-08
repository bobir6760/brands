<template>
  <div class="working">
    <div class="container">
      <div class="working-wrapper">
        <div class="working-info">
          <div class="working-image">
            <div class="working-wrapper__image">
              <img src="@/assets/img/Logo.png" alt="" />
            </div>
            <div class="working-title">
              Nextly is a team of +60 developers, systems architects, designers,
              founders, and makers that have been working together for over 10
              years building scalable tech solutions for Fortune 500s, Inc
              5000s, high-growth startups, and even internationally renowned
              names such as the UN & the IOC.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Working",
};
</script>

<style lang="scss" scoped>
.working {
  padding: 50px 0px;
}
.working-image {
  display: flex;
  justify-content: center;
}
.working-wrapper__image {
  display: flex;
}
.working-title {
  display: flex;
  width: 46%;
  font-size: 25px;
  position: absolute;
  transform: translateY(100%);
  cursor: pointer;
}
@media screen and(max-width: 1200px) {
  .working-title {
    display: flex;
    width: 49%;
    font-size: 20px;
  }
}
@media screen and(max-width: 992px) {
  .working-title {
    display: flex;
    width: 64%;
    font-size: 20px;
  }
}
@media screen and(max-width: 768px) {
  .working-title {
    display: flex;
    width: 77%;
    font-size: 18px;
  }
}
@media screen and(max-width: 576px) {
  .working-title {
    display: flex;
    width: 80%;
    font-size: 15px;
    text-align: center;
  }
}
</style>

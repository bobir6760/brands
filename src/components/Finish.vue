<template>
  <div class="finish">
    <div class="container">
      <div class="finish-wrapper">
        <div class="finish-info">
          <div class="finish-werapper__title">Brazil</div>
          <div class="finish-wrapper__subtitle">
            Av. Engenheiro Luís Carlos <br />Berrini, 1140 – São Paulo
          </div>
        </div>
        <div class="finish-wrapper__item">
          <div class="finish-item__title">United Kingdom</div>
          <div class="finish-item__subtitle">
            64 The Crescent <br />KT33LH, New Malden
          </div>
        </div>
        <div class="finish-body">
          <div class="finish-body__title">Follow Us</div>
          <div class="finish-wrapper__image">
            <img src="@/assets/img/finish 1.svg" alt="" />
          </div>
        </div>

        <div class="finish-wrapper__text">
          <div class="finish-text__title">Contact Us</div>
          <div class="finish-text__subtitle">
            hi@nextly.team <br />+123 456 789
          </div>
        </div>
        <div class="finish-image">
          <img src="@/assets/img/finish2.svg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  nmae: "Finish",
};
</script>

<style lang="scss" scoped>
.finish {
  padding: 50px 0px;
  background: black;
}
.finish-wrapper {
  display: flex;
  justify-content: space-between;
}
.finish-wrapper__subtitle {
  cursor: pointer;
}
.finish-info {
  color: white;
}
.finish-wrapper__item {
  color: white;
}
.finish-wrapper__text {
  color: white;
  cursor: pointer;
}
.finish-body__title {
  color: white;
  margin-bottom: 20px;
  font-weight: bold;
  cursor: pointer;
}
.finish-werapper__title {
  margin-bottom: 20px;
  font-weight: bold;
  cursor: pointer;
}
.finish-item__title {
  margin-bottom: 20px;
  font-weight: bold;
  cursor: pointer;
}
.finish-item__subtitle {
  cursor: pointer;
}
.finish-text__title {
  margin-bottom: 20px;
  font-weight: bold;
  cursor: pointer;
}
.finish-wrapper__image img {
  width: 100%;
  cursor: pointer;
}
.finish-image img {
  width: 100%;
  cursor: pointer;
}
@media screen and (max-width: 768px) {
  .finish-wrapper {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 50px;
  }
  .finish-image img {
    width: 40%;
  }
  .finish-wrapper__image img {
    width: 40%;
  }
}
@media screen and (max-width: 576px) {
  .finish-wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    gap: 50px;
  }
  .finish-image img {
    width: 70%;
  }
  .finish-wrapper__image img {
    width: 70%;
  }
}
</style>

@
<template>
  <div class="java">
    <div class="container">
      <div class="java-wrapper">
        <div class="java-info">
          <div class="java-wapper__title">Specialties</div>
          <div class="java-wrapper__subtitle">
            Our software is made from relevant technologies in the <br />market,
            which guarantee the quality of the service
          </div>

          <div class="java-image">
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group1.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group2.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group3.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group4.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group5.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group6.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group7.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group8.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group9.svg" alt="" />
            </div>
            <div class="java-wrapper__image">
              <img src="@/assets/img/Group10.svg" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Java",
};
</script>

<style lang="scss" scoped>
.java {
  padding: 50px 0px;
}
.java-wapper__title {
  font-size: 40px;
  margin-bottom: 30px;
  font-weight: bold;
}
.java-wrapper__subtitle {
  font-size: 25px;
  margin-bottom: 87px;
}
.java-info {
  text-align: center;
}
.partners-images__item {
  display: flex;
  flex-direction: column;
}
.java-image {
  display: grid;
  grid-template-columns: repeat(5, 2fr);
  gap: 20px;
}
.java-wrapper__image {
  display: flex;
  flex-direction: column;
}
.java-wrapper__image img {
  width: 100px;
  height: 100px;
  object-fit: contain;
}
@media screen and(max-width: 768px) {
  .java-wrapper__subtitle {
    font-size: 20px;
    margin-bottom: 50px;
  }
  .java-image {
    display: inline-block;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
  }
  .java-wrapper__image img {
    width: 100px;
  }
}
</style>

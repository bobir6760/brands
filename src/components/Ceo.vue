<template>
  <div class="ceo">
    <div class="container">
      <div class="ceo-wrapper">
        <div class="ceo-info">
          <div class="ceo-wrapper__image">
            <img src="@/assets/img/Foto2.png" alt="" />
          </div>
          <div class="ceo-wrapper__title">
            “Strong team that's easy to work with. Doesn't just focus on
            <br />trying to get something out the door, but also concerns<br />
            themselves with the scalability of their application design.”
          </div>
          <div class="ceo-wrapper__subtitle">
            Anthony Duerr <br />CEO at JobPixel | ex director of engineering of
            Linkedin
          </div>
          <div class="ceo-block">
            <button class="ceo-btn">
              <img src="@/assets/img/C.svg" alt="" />
              <span> see in Clutch </span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Ceo",
};
</script>

<style lang="scss" scoped>
.ceo {
  padding: 50px 0px;
}
.ceo-wrapper {
  text-align: center;
}
.ceo-block {
  display: flex;
  justify-content: center;
}
.ceo-wrapper__image {
  margin-bottom: 77px;
  width: 100%;
  cursor: pointer;
}
.ceo-wrapper__title {
  margin-bottom: 67px;
  cursor: pointer;
}
.ceo-wrapper__subtitle {
  margin-bottom: 20px;
  cursor: pointer;
}
.ceo-btn {
  display: flex;
  align-items: center;
  color: white;
  background: linear-gradient(273.36deg, #003166 0%, #007aff 100%);
  border-radius: 50px;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  gap: 5px;
}
.ceo-btn:active {
  color: black;
}
.ceo-btn img {
  width: 24px;
  height: 24px;
  object-fit: contain;
}
@media screen and (max-width: 576px) {
  .ceo-wrapper__image {
    margin-bottom: 40px;
  }
  .ceo-wrapper__title {
    margin-bottom: 40px;
  }
}
</style>

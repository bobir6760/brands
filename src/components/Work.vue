<template>
  <div class="work">
    <div class="container">
      <div class="work-wrapper">
        <div class="work-info">
          <div class="work-image">
            <img src="@/assets/img/Foto3.png" alt="" />
          </div>
          <div class="work-wrapper__title">
            “Conversion rates improved as a result of Nextly’s work. The
            <br />team is organized and has strong practices for development
            <br />projects. Everyone is happy with the new platform.”
          </div>
          <div class="work-wrapper__subtitle">
            Gustavo Paiva <br />CEO at Descola
          </div>
          <div class="work-block">
            <button class="work-btn">
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
  name: "Work",
};
</script>

<style lang="scss" scoped>
.work {
  padding: 50px 0px;
}
.work-wrapper {
  text-align: center;
}
.work-image {
  margin-bottom: 77px;
  width: 100%;
  cursor: pointer;
}
.work-wrapper__title {
  margin-bottom: 67px;
  cursor: pointer;
}
.work-wrapper__subtitle {
  margin-bottom: 20px;
  cursor: pointer;
}
.work-btn {
  display: flex;
  align-items: center;
  color: white;
  background: linear-gradient(273.36deg, #003166 0%, #007aff 100%);
  border-radius: 30px;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  gap: 5px;
}
.work-btn:hover {
  transition: 1s;
  background: black;
  color: white;
  border-radius: 5px;
}
.work-btn img {
  width: 24px;
  height: 24px;
  object-fit: contain;
}
.work-block {
  display: flex;
  justify-content: center;
}
@media screen and (max-width: 577px) {
  .work-image {
    margin-bottom: 40px;
  }
  .work-wrapper__title {
    margin-bottom: 40px;
  }
}
</style>

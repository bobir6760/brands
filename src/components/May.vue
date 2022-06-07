<template>
  <div class="may">
    <div class="container">
      <div class="may-wrapper">
        <div class="may-wrapper-image">
          <img src="@/assets/img/Foto.png" alt="" />
        </div>
        <div class="may-wrapper__title">
          “Nextly has done a spectacular job on sophisticated <br />projects so
          far. They’ve been a great partner, and we plan to <br />expand their
          role going forward.”
        </div>
        <div class="may-wrapper__subtitle">
          Jonathan May <br />CEO at Evolution Virtual
        </div>
        <div class="may-info">
          <button class="may-btn">
            <img src="@/assets/img/C.svg" alt="" />
            <span> see in Clutch </span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "May",
};
</script>

<style lag="scss" scoped>
.may {
  padding: 50px 0px;
}
.may-wrapper {
  text-align: center;
}
.may-wrapper-image {
  margin-bottom: 77px;
  width: 100%;
}
.may-wrapper__title {
  margin-bottom: 67px;
}
.may-wrapper__subtitle {
  margin-bottom: 20px;
  color: #8C8C8C;
}
.may-info {
  display: flex;
  justify-content: center;
}
.may-btn {
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
.may-btn img {
  width: 24px;
  height: 24px;
  object-fit: contain;
}
.may-btn:active {
  color: black;
}
@media screen and (max-width: 576px) {
  .may-wrapper-image {
    margin-bottom: 40px;
  }
  .may-wrapper__title {
    margin-bottom: 35px;
  }
}
</style>

<template>
  <div class="cola">
    <div class="container">
      <div class="cola-wrapper">
        <div class="cola-info">
          <div class="cola-wrapper__image">
            <img src="@/assets/img/Cola.png" alt="" />
          </div>
          <div class="cola-wrapper__block">
            <button class="cola-btn">React/Redux</button>
            <button class="cola-btn">Firebase</button>
            <button class="cola-btn">Node.js/Express</button>
            <button class="cola-btn">AWS</button>
          </div>
          <div class="cola-wrapper__title">
            Descola is an online learning platform <br />based in São Paulo. The
            amazing <br />platform we’ve developed allows users to <br />buy and
            watch their as amazing <br />video-based courses and teaching
            materials.
          </div>
        </div>
        <div class="cola-image">
          <img src="@/assets/img/Noutbook 3.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cola",
};
</script>

<style lang="scss" scoped>
.cola {
  padding: 50px 0px;
  background: #f24423;
}
.cola-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.cola-wrapper__image {
  margin-bottom: 25px;
  cursor: pointer;
  cursor: pointer;
}
.cola-wrapper__block {
  display: flex;
  margin-bottom: 25px;
  gap: 15px;
}
.cola-image img {
  width: 100%;
  cursor: pointer;
}
.pixel-wrapper__block {
  display: flex;
  gap: 15px;
  margin-bottom: 30px;
}
.cola-btn {
  color: white;
  background: #f24423;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.cola-btn:active {
  color: black;
}
.cola-wrapper__title {
  font-size: 22px;
  color: white;
  cursor: pointer;
}
@media screen and (max-width: 992px) {
  .cola-wrapper__block {
    display: flex;
    gap: 5px;
  }
  .cola-wrapper__title {
    font-size: 18px;
  }
  .cola-btn {
    padding: 3px 6px;
    border-radius: 15px;
  }
  .cola-wrapper {
    text-align: center;
  }
}
@media screen and (max-width: 768px) {
  .cola-wrapper {
    display: flex;
    flex-direction: column;
  }
}
@media screen and (max-width: 576px) {
    .cola-btn {
    padding: 3px 5px;
    border-radius: 15px;
    font-size: 12px;
  }
}
</style>

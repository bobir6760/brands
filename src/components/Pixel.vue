<template>
  <div class="pixel">
    <div class="container">
      <div class="pixel-wrapper">
        <div class="pixel-info">
          <div class="pixel-wrapper__image">
            <img src="@/assets/img/JobPixel.png" alt="" />
          </div>
          <div class="pixel-block">
            <button class="pixel-wrapper__btn">React/Redux</button>
            <button class="pixel-info__btn">Firebase</button>
            <button class="pixel-text__btn">Node.js/Express</button>
            <button class="pixel-item__btn">AWS</button>
          </div>
          <div class="pixel-wrapper__title">
            JobPixel , a Bay Area-based startup, <br />came to humanize hiring.
            To help, we’ve <br />built a video-first platform that makes it
            <br />
            astonishingly easy for companies to hire <br />candidates with video
            and for candidates <br />to submit video in lieu of or in addition
            to<br />the traditional resumé and cover letter.
          </div>
        </div>
        <div class="pixel-image">
          <img src="@/assets/img/Noutbook 2.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Pixel",
};
</script>

<style lang="scss" scoped>
.pixel {
  padding: 100px 0px;
  background: #3c4147;
}
.pixel-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.pixel-wrapper__image {
  margin-bottom: 30px;
  cursor: pointer;
}
.pixel-wrapper__image img {
  width: 100%;
}
.pixel-image img {
  width: 100%;
}
.pixel-block {
  display: flex;
  gap: 15px;
  margin-bottom: 30px;
}
.pixel-wrapper__btn {
  color: white;
  background: #3c4147;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.pixel-wrapper__btn:active {
  color: black;
}
.pixel-info__btn {
  color: white;
  background: #3c4147;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.pixel-info__btn:active {
  color: black;
}
.pixel-text__btn {
  color: white;
  background: #3c4147;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.pixel-text__btn:active {
  color: black;
}
.pixel-item__btn {
  color: white;
  background: #3c4147;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.pixel-item__btn:active {
  color: black;
}
.pixel-wrapper__title {
  color: white;
  font-size: 22px;
  cursor: pointer;
}
@media screen and (max-width: 1200px) {
  .pixel-wrapper__image img {
    width: 100%;
  }
  .pixel-wrapper__title {
    color: white;
    font-size: 19px;
  }
  .pixel-block {
    gap: 5px;
  }
  .pixel-image img {
    object-fit: contain;
    width: 100%;
    height: 100%;
  }
}
@media screen and (max-width: 992px) {
  .pixel-wrapper_-image img {
    width: 80%;
  }
  .pixel-wrapper__btn {
    color: white;
    background: #3c4147;
    padding: 4px 7px;
    border-radius: 15px;
    font-size: 10px;
  }
  .pixel-info__btn {
    color: white;
    background: #3c4147;
    padding: 4px 7px;
    border-radius: 15px;
    font-size: 10px;
  }
  .pixel-text__btn {
    color: white;
    background: #3c4147;
    padding: 4px 7px;
    border-radius: 20px;
    font-size: 10px;
    border-color: white;
  }
  .pixel-item__btn {
    color: white;
    background: #3c4147;
    padding: 4px 7px;
    border-radius: 20px;
    font-size: 10px;
  }
  .pixel-wrapper__title {
    color: white;
    font-size: 18px;
  }
  .pixel-block {
    margin-top: 15px;
  }
}
@media screen and (max-width: 768px) {
  .pixel-wrapper {
    display: flex;
    flex-direction: column;
  }
  .pixel-wrapper__title {
    color: white;
    font-size: 18px;
    text-align: center;
  }
  .pixel-block {
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 576px) {
  .pixel-wrapper {
    display: flex;
    flex-direction: column;
  }
  .pixel-wrapper__title {
    color: white;
    font-size: 15px;
  }
  .pixel-block {
    display: flex;
    justify-content: center;
  }
}
</style>

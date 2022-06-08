<template>
  <div class="online">
    <div class="container">
      <div class="online-wrapper">
        <div class="online-info">
          <div class="online-wrapper__title">Let’s talk!</div>
          <div class="online-wrapper__subtitle">
            Fill out the form or send <br />us an email, so we can <br />see how
            we can help <br />you.
          </div>
          <div class="online-wrapper__text">
            You can also schedule a <br />meeting with Fernando!
          </div>
          <button class="online-btn">Schedule a meeting</button>
        </div>
        <div class="online-block">
          <div class="online-input">
            <input placeholder="Full*" type="text" />
          </div>
          <div class="online-input">
            <input placeholder="E-mail*" type="text" />
          </div>
          <div class="online-input">
            <input placeholder="Company*" type="text" />
          </div>
          <div class="online-block__input">
            <input placeholder="Tell us a bit of your idea" type="text" />
          </div>
          <button class="online-block__btn">Send</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Online",
};
</script>

<style lang="scss" scoped>
.online {
  padding: 50px 0px;
  background: linear-gradient(180deg, rgba(22, 23, 25, 0.75) 0%, #000000 100%);
}
.online-wrapper {
  display: flex;
  justify-content: space-between;
}
.online-wrapper__title {
  font-size: 40px;
  color: white;
  margin-bottom: 30px;
  cursor: pointer;
}
.online-wrapper__subtitle {
  color: white;
  font-size: 20px;
  margin-bottom: 30px;
  cursor: pointer;
}
.online-wrapper__text {
  color: white;
  font-size: 20px;
  margin-bottom: 30px;
}
.online-btn {
  color: white;
  border: none;
  padding: 15px 60px;
  background: linear-gradient(273.36deg, #003166 0%, #007aff 100%);
  border-radius: 50px;
  font-size: 18px;
  cursor: pointer;
}
.online-btn:active {
  color: black;
  font-size: 22px;
}
.online-block {
  display: flex;
  flex-direction: column;
  gap: 20px;
}
.online-block__input input {
  padding: 10px 30px 70px 10px;
  border-radius: 10px;
  border: none;
}
.online-input input {
  padding: 10px 30px 10px 10px;
  border-radius: 10px;
  border: none;
}
.online-block__btn {
  color: white;
  background: black;
  padding: 15px 60px;
  border-radius: 50px;
  font-size: 15px;
  cursor: pointer;
  border-color: #007aff;
}
.online-block__btn:active {
  color: white;
  background: linear-gradient(273.36deg, #003166 40%, #007aff 80%);
}
@media screen and (max-width: 992px) {
  .online-btn {
    font-size: 15px;
  }
}
@media screen and (max-width: 768px) {
  .online-wrapper {
    display: flex;
    flex-direction: column;
    text-align: center;
  }
  .online-btn {
    margin-bottom: 30px;
    font-size: 15px;
    padding: 10px 40px;
  }
  .online-block__btn {
    display: none;
  }
}
</style>

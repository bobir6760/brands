<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar-wrapper">
        <div class="navbar-info">
          <div class="navbar-image">
            <div class="navbar-wrapper__image">
              <img src="@/assets/img/Nextly.png" alt="" />
            </div>
          </div>
          <div class="navbar-wrapper__title">
            <p>About</p>
            <p>Work</p>
            <p>Cases</p>
            <p>Contact</p>
          </div>
        </div>
        <div class="navbar-wrapper__block">
          <div class="navbar-wrapper_-item">
            <div class="navbar-item__title">
              We’re bringing <br />software development <br />to the next level.
            </div>
            <div class="navbar-item__subtitle">
              Talk to our Business Specialist!
            </div>
            <button class="navbar-btn">Schedule a meeting</button>
          </div>
          <div class="navbar-item__image">
            <div class="navbar-wrapper__img">
              <img src="@/assets/img/Group.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
.navbar {
  padding: 50px;
  background: linear-gradient(273.36deg, #003166 0%, #007aff 100%);
}
.navbar-info {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 75px;
}
.navbar-wrapper__title {
  display: flex;
  gap: 70px;
  color: white;
  cursor: pointer;
}
.navbar-wrapper__title p:hover {
font-size: 20px;
}
.navbar-item__title {
  color: white;
  font-size: 50px;
  cursor: pointer;
}
.navbar-btn {
  border-radius: 50px;
  padding: 10px 40px;
  color: black;
  font-size: 18px;
  border: none;
  cursor: pointer;
}
.navbar-btn:active {
  background-color: black;
  color: white;
}
.navbar-item__subtitle {
  color: white;
  font-size: 20px;
  margin-bottom: 50px;
  cursor: pointer;
}
.navbar-wrapper__block {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}
.navbar-image img {
  width: 100%;
}
.navbar-item__image img {
  width: 98%;
}

@media screen and (max-width: 992px) {
  .navbar-wrapper__title {
    display: flex;
    gap: 40px;
  }
  .navbar-item__title {
    font-size: 40px;
  }
  .navbar-wrapper__img {
    display: flex;
    justify-content: flex-end;
  }
}

@media screen and (max-width: 768px) {
  .navbar-item__title {
    font-size: 23px;
    margin-bottom: 20px;
  }
  .navbar-btn {
    padding: 10px 17px;
    font-size: 12px;
  }
  .navbar-wrapper__block {
    display: flex;
    justify-content: space-between;
  }
}
@media screen and (max-width: 576px) {
  .navbar-info {
    display: flex;
    flex-direction: column;
    margin-bottom: 50px;
  }
  .navbar-item__title {
    text-align: center;
    width: 100%;
  }
  .navbar-image {
    display: flex;
    justify-content: center;
    margin-bottom: 15px;
  }
  .navbar-wrapper__title {
    gap: 15px;
  }
  .navbar-wrapper__block {
    display: flex;
    flex-direction: column;
  }
  .navbar-btn {
    padding: 10px 28px;
    font-size: 15px;
  }
  .navbar-item__image img {
    display: flex;
    align-content: center;
    width: 100%;
    margin-top: 30px;
  }
}
</style>

<template>
  <div class="vendoo">
    <div class="container">
      <div class="vendoo-wrapper">
        <div class="vendoo-info">
          <div class="vendoo-wrapper__image">
            <img src="@/assets/img/Logo 2.png" alt="" />
          </div>
          <div class="vendoo-block">
            <button class="vendoo-wrapper__btn">React/Redux</button>
            <button class="vendoo-info__btn">Firebase</button>
            <button class="vendoo-text__btn">Node.js/Express</button>
            <button class="vendoo-btn">AWS</button>
          </div>

          <div class="vendoo-wrapper__title">
            Vendoo is an e-commerce platform <br />envisioned by a D.C.- based
            startup. <br />We’ve built a Node.js application where <br />users
            can cross-post their inventory onto <br />multiple marketplaces such
            as eBay, Etsy, <br />Poshmark, Mercari, Grailed, and Depop.
          </div>
        </div>
        <div class="vendoo-body__image">
          <img src="@/assets/img/Noutbook.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Vendoo",
};
</script>

<style lang="scss" scoped>
.vendoo {
  padding: 50px 0px;
  background: #6856c9;
}
.vendoo-wrapper {
  display: flex;
  justify-content: space-between;
}
.vendoo-wrapper__image img {
  width: 100%;
}
.vendoo-info {
  margin-top: 50px;
}
.vendoo-block {
  display: flex;
  gap: 20px;
  margin-top: 50px;
}
.vendoo-wrapper__btn {
  color: white;
  background-color: #6856c9;
  padding: 5px 13px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.vendoo-wrapper__btn:active {
  color: black;
}
.vendoo-info__btn {
  color: white;
  background-color: #6856c9;
  padding: 6px 16px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.vendoo-info__btn:active {
  color: black;
}
.vendoo-text__btn {
  color: white;
  background-color: #6856c9;
  padding: 6px 16px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.vendoo-text__btn:active {
  color: black;
}
.vendoo-btn {
  color: white;
  background-color: #6856c9;
  padding: 6px 15px;
  border-radius: 20px;
  border-color: white;
  cursor: pointer;
}
.vendoo-btn:active {
  color: black;
}
.vendoo-wrapper__title {
  color: white;
  font-size: 22px;
  margin-top: 30px;
}
.vendoo-body__image img {
  width: 100%;
}
@media screen and(max-width: 1200px) {
  .vendoo-wrapper__image {
    width: 67%;
  }
  .vendoo-body__image img {
    object-fit: contain;
    width: 100%;
    height: 100%;
  }
  .vendoo-wrapper__title {
  font-size: 17px;
}
.vendoo-block {
  gap: 10px;
  margin-top: 45px;
}
}
@media screen and (max-width: 992px) {
  .vendoo-wrapper__title {
    color: white;
    font-size: 17px;
    margin-top: 20px;
  }
  .vendoo-block {
    display: flex;
    gap: 5px;
  }
}
@media screen and (max-width: 768px) {
  .vendoo-wrapper {
    display: flex;
    flex-direction: column;
  }
  .vendoo-info {
    text-align: center;
  }
  .vendoo-block {
    display: flex;
    justify-content: center;
  }
  .vendoo-wrapper__image {
    display: flex;
    width: 100%;
  }
}
@media screen and (max-width: 576px) {
  .vendoo-wrapper__title {
    text-align: start;
  }
   .vendoo-block {
    display: flex;
    gap: 2px;
  }
  .vendoo-wrapper__btn {
    color: white;
    background-color: #6856c9;
    padding: 4px 7px;
    border-radius: 15px;
    font-size: 10px;
  }
  .vendoo-info__btn {
    color: white;
    background-color: #6856c9;
    padding: 4px 7px;
    border-radius: 15px;
    font-size: 10px;
  }
  .vendoo-text__btn {
    color: white;
    background-color: #6856c9;
    padding: 4px 7px;
    border-radius: 20px;
    font-size: 10px;
    border-color: white;
  }
  .vendoo-btn {
    color: white;
    background-color: #6856c9;
    padding: 4px 7px;
    border-radius: 20px;
    font-size: 10px;
  }
}
</style>

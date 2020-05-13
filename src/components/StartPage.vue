<template>
  <div id="StartPage">
    <div class="wrapp-main">
      <div class="menu-box">
        <div class="logo-school">
          <img class="image-logo" src=".././assets/logo.png" alt="..." />
        </div>
        <div class="list-menu">
          <div class="item-menu">
            <img class="image-item" src=".././assets/home.png" alt="..." />
          </div>
          <div class="item-menu">
            <img class="image-item" src=".././assets/live.png" alt="..." />
          </div>
          <div class="item-menu">
            <img class="image-item" src=".././assets/phone.png" alt="..." />
          </div>
          <div class="item-menu">
            <img class="image-item" src=".././assets/search.png" alt="..." />
          </div>
        </div>
      </div>
      <div class="content-info">
        <div class="description-info">
          <div class="title">
            <span>{{title}}</span>
          </div>
          <div class="description">{{description}}</div>
          <div class="counter-wrapp">
            <div class="container-counter">
              <div class="title-counter">
                <span>04</span>
              </div>
              <div class="description-counter">
                <span>Days</span>
              </div>
            </div>
            <div class="separate-counter">
              <span>|</span>
            </div>
            <div class="container-counter">
              <div class="title-counter">
                <span>12</span>
              </div>
              <div class="description-counter">
                <span>Hours</span>
              </div>
            </div>
            <div class="separate-counter">
              <span>|</span>
            </div>
            <div class="container-counter">
              <div class="title-counter">
                <span>30</span>
              </div>
              <div class="description-counter">
                <span>Minutes</span>
              </div>
            </div>
          </div>
        </div>
        <div class="wrapp-image">
          <img class="image-student" src=".././assets/graduated.png" alt />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "StartPage",
  data() {
    return {
      title: "PROM 2020",
      description:
        "lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum lorem ipsum",
      message: "20 30 40"
    };
  },
  methods: {
    counterProm() {
      return `04 | 12 | 30`;
    }
  },
  computed: {}
};
</script>

<style>
.wrapp-main {
  width: 100%;
  display: flex;
  height: 100%;
}

.menu-box {
  display: flex;
  flex-direction: column;
  width: 9%;
  background-color: #f7d13b;
}

.logo-school {
  height: 5%;
}

.image-logo {
  height: 92px;
  width: 100px;
  padding: 11%;
}

.list-menu {
  height: 80%;
  padding-left: 49%;
  display: flex;
  align-content: space-between;
  align-items: center;
  flex-direction: column;
  justify-content: space-around;
}

.item-menu {
  height: 42px;
  width: 61px;
  background: white;
  border-top-left-radius: 19px;
  border-bottom-left-radius: 19px;
}

.content-info {
  width: 91%;
  display: flex;
  background-image: url(".././assets/school.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}

.description-info {
  width: 55%;
  padding-top: 10%;
  padding-left: 10%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding-bottom: 45%;
}

.title {
  font-size: 58px;
  font-weight: bold;
  color: white;
  font-family: sans-serif;
}

.description {
  padding-top: 12%;
  text-align: justify;
  color: white;
  padding-right: 10%;
}

.container-counter {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.counter-wrapp {
  padding-top: 17%;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.title-counter {
  color: #f9e49f;
  font-weight: bold;
  font-size: 60px;
}

.description-counter {
  color: white;
  font-size: 20px;
}

.separate-counter {
  color: white;
  padding-left: 7%;
  padding-right: 8%;
  font-size: 52px;
}

.wrapp-image {
  width: 60%;
}

.image-student {
  height: 254px;
  margin-top: 41%;
}

.image-item {
  height: 20px;
  padding-top: 19%;
}
</style>
<template>
  <div id="RestorePassword">
    <div class="main-container">
      <div class="wrapp-form">
        <div class="container-login">
          <div class="title">
            <span>wemi</span>
          </div>
          <div class="description-password">
            <span>Ingresa tú email y una nueva contraseña será enviada a tu buzón de entrada, es posible que pueda ocurrir un error en el camino y llegue a spam, revisalo tambien por si acaso</span>
          </div>
          <div class="form-login">
            <div class="container-input">
              <span class="label-input">Email address</span>
              <input class="custom-input" placeholder="Example@email.com" />
            </div>
            <div class="container-button">
              <button class="custom-button">Send new password</button>
            </div>
          </div>
        </div>
        <div class="footer-login">
          <div class="logo-bees">
            <span>Coyright</span>
            <span>Bees2Biz</span>
          </div>
          <div class="policy">
            <span>Privacy policy</span>
          </div>
        </div>
      </div>
      <div class="wrapp-description">
        <div class="container-description">
          <div class="description-title">
            <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae, vel mollitia, iusto reprehenderit iure dolorum.</span>
          </div>
          <div class="description">
            <span>Parrafo complemnto Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequatur nisi non iure sequi laborum temporibus, pariatur architecto velit libero quidem dolore facilis cumque, sit tempora illo minus incidunt inventore dignissimos.</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RestorePassword",
  data() {
    return {
      title: "PROM 2020"
    };
  },
  methods: {},
  computed: {}
};
</script>

<style>
/*NEWS CLASSES*/

.description-password {
  text-align: left;
  color: #758497;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 400;
  padding-bottom: 6%;
}

/* */
.main-container {
  display: flex;
  height: 100%;
  height: 100vh;
}

.wrapp-form {
  width: 40%;
  background-color: white;
  padding-top: 4%;
  flex-direction: column;
  display: flex;
}

.description-password {
}

.name-bold {
}

.container-login {
  padding-right: 16%;
  padding-left: 12%;
}

.title {
  text-align: left;
  color: #04adbf;
  padding-bottom: 7%;
  font-family: "Courier New", Courier, monospace;
  font-size: 50px;
  font-weight: 900;
}

.label-input {
  padding-bottom: 8px;
  color: #647182;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 500;
}

.custom-input {
  width: 100%;
  border-radius: 20px;
  border: 1px solid #dcdce8;
  background-color: #f5f5fc;
  height: 34px;
  outline: none;
  padding-left: 3%;
}

.custom-input::placeholder {
  color: rgba(117, 132, 151, 0.5);
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 300;
}

.custom-button {
  width: 103%;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  border-bottom-right-radius: 98px;
  /* border-radius: 50px; */
  border: 1px solid #f2c063;
  background-color: #f29472;
  height: 40px;
  color: #ffffff;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 500;
  outline: none;
  cursor: pointer;
}

.form-login {
  display: flex;
  flex-direction: column;
}

.container-input {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding-top: 5%;
  padding-bottom: 4%;
  align-items: flex-start;
}

.container-button {
  padding-top: 2%;
}

.footer-login {
  display: flex;
  justify-content: space-between;
  padding-bottom: 24%;
  padding-top: 13%;
  padding-right: 16%;
  padding-left: 12%;
}

.logo-bees {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  color: rgba(117, 132, 151, 0.7);
  font-family: Montserrat;
  font-size: 13px;
  font-weight: 300;
}

.policy {
  color: rgba(117, 132, 151, 0.7);
  font-family: Montserrat;
  font-size: 13px;
  font-weight: 300;
}

.wrapp-description {
  width: 60%;
  background-color: #025373;
}

.container-description {
  color: white;
  padding-top: 24%;
  padding-left: 16%;
  padding-right: 16%;
}

.description-title {
  text-align: left;
  color: #ffffff;
  font-family: Montserrat;
  font-size: 40px;
  font-weight: 700;
  padding-bottom: 4%;
}

.description {
  text-align: start;
  color: #ffffff;
  font-family: Montserrat;
  font-size: 20px;
  font-weight: 300;
  padding-bottom: 33%;
}
</style>
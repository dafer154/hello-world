<template>
  <div id="InvitationStudents">
    <div class="main-container">
      <div class="container-column">
        <div class="container-invitation">
          <div class="container-title">
            <div class="title-user">
              <span class="user">Mikaela Rojas!,</span>
              <span class="description">
                llevas
                <span class="counter">0</span> de
                <span class="counter">50</span>
              </span>
            </div>
            <div class="guess">
              <span>invitados</span>
            </div>
          </div>
          <div class="container-inputs">
            <div class="row-inputs">
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
            </div>
            <div class="row-inputs">
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
            </div>
            <div class="row-inputs">
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
              <div class="wrapp-input">
                <div class="label-input">
                  <span>Nombre</span>
                </div>
                <div class="input-invitations">
                  <input class="custom-input-invitation" placeholder="name" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container-add-more">
        <button class="custom-add-more">Add more</button>
      </div>
      <div class="buttons-invitations">
        <div class="cancel">
          <button class="custom-button-cancel">Cancel</button>
        </div>
        <div class="container-buttons-actions">
          <div class="save">
            <button class="custom-button-save">Save</button>
          </div>
          <div class="send-invitation">
            <button class="custom-button-send">Send</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "InvitationStudents",
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
.main-container {
  display: flex;
  margin: 10%;
  flex-direction: column;
  margin: 10%;
}

.container-column {
}

.container-invitation {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.container-title {
  color: #152a5e;
  font-family: Montserrat;
  font-size: 25px;
  /* font-weight: 700; */
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.title-user {
}

.user {
  color: #f07857;
}

.description {
}

.counter {
  font-weight: bold;
}

.guess {
}

.container-inputs {
  width: 100%;
  padding-top: 2%;
}

.row-inputs {
  display: flex;
  align-content: space-around;
  justify-content: space-between;
  padding-bottom: 1%;
  padding-top: 1%;
  flex-wrap: wrap;
}

.wrapp-input {
  padding: 1%;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.label-input {
  padding-bottom: 3%;
  color: #758497;
  font-family: Montserrat;
  font-size: 13px;
  font-weight: 400;
}

.input-invitations {
}

.custom-input-invitation {
  padding-left: 2px;
  height: 26px;
  border-radius: 10px;
  background-color: #fafaff;
  outline: none;
  border: 1px solid #fafaff;
}

.custom-input-invitation::placeholder {
  color: rgba(117, 132, 151, 0.5);
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 300;
}

.container-buttons-actions {
  display: flex;
  flex-wrap: wrap;
}

.container-add-more {
  padding-bottom: 5%;
  padding-top: 5%;
}

.custom-add-more {
  background-color: white;
  border: 1px black solid;
  outline: none;
  cursor: pointer;
  border-radius: 10px;
  border: 2px dashed #b9b9d3;
  height: 36px;
  width: 40%;
  color: #b9b9d3;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 500;
}

.custom-button-cancel {
  background-color: white;
  border: 1px black solid;
  outline: none;
  cursor: pointer;
  border-radius: 10px;
  border: 2px solid #f07857;
  height: 36px;
  width: 114px;
  color: #f07857;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 400;
}

.container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.custom-button-save {
  background-color: white;
  border: 1px black solid;
  outline: none;
  cursor: pointer;
  border-radius: 10px;
  border: 2px solid #04adbf;
  height: 36px;
  width: 114px;
  color: #04adbf;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 400;
}

.custom-button-send {
  background-color: #04adbf;
  border: 1px black solid;
  outline: none;
  cursor: pointer;
  border-radius: 10px;
  border: 2px solid #04adbf;
  height: 36px;
  width: 114px;
  color: white;
  font-family: Montserrat;
  font-size: 15px;
  font-weight: 400;
}

.buttons-invitations {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.cancel {
}

.save {
  padding-right: 2%;
}

.send-invitation {
  padding-left: 2%;
}
</style>
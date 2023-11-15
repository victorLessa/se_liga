<template>
  <div>
    <div
      class="modal fade"
      id="modal-intro"
      data-bs-backdrop="static"
      aria-hidden="true"
      aria-labelledby="exampleModalToggleLabel"
      tabindex="-1"
    >
      <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content">
          <div class="modal-header" style="border-bottom: 0px"></div>
          <div class="modal-body text-center">
            Muito bom ter você por aqui. <br />
            Favor me informe como você quer ser chamada(o):
            <div class="m-3">
              <input
                type="text"
                v-model="name"
                required
                class="form-control"
                id="playerName"
              />
              <div class="invalid-feedback">Seu nome é obrigatório.</div>
            </div>
          </div>
          <div class="modal-footer">
            <button
              class="btn btn-primary"
              style="width: 100%"
              id="save"
              @click="start"
            >
              Salvar
            </button>
          </div>
        </div>
      </div>
    </div>
    <div
      class="container vh-100 d-flex justify-content-center align-items-center"
    >
      <div class="row">
        <h5 class="text-center">Olá! Escolha uma dificuldade</h5>
        <div class="col-12 my-2">
          <button
            class="btn text-white w-100"
            style="background-color: #111c06"
            data-intro="Hello step one!"
            @click="startGame(1)"
          >
            Facil
          </button>
        </div>
        <div class="col-12 my-2">
          <button
            class="btn w-100 text-white"
            style="background-color: #111c06"
            @click="startGame(2)"
          >
            Dificil
          </button>
        </div>
        <hr />
        <div class="col-12 my-2">
          <button
            class="btn w-100 text-white"
            style="background-color: #111c06"
            @click="tutorial()"
          >
            Iniciar tutorial
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
function startGame(level: number) {
  navigateTo("/game");
}

function tutorial() {
  navigateTo("/tutorial");
}
</script>

<style lang="scss" scoped></style>

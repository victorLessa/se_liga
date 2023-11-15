<template>
  <div>
    <div class="container mt-4" id="imagem_resposta">
      <div class="row justify-content-center">
        <div
          class="card"
          data-intro="Aqui você vê as imagens"
          style="width: 80vw; height: 200px"
        >
          <div class="card-body"></div>
        </div>
      </div>
    </div>
    <div
      class="container d-flex justify-content-center mt-2"
      data-intro="Aqui você vê as dicas"
      id="dicas"
    >
      <div
        class="justify-content-center"
        style="display: inline-flex; flex-wrap: wrap"
      >
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
        <div class="m-1">
          <div class="card">
            <div class="card-body">
              <p class="text-center m-0">555</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container mt-4" id="teclado">
      <h4 class="text-center mb-3">Utilize o teclado abaixo</h4>
      <div class="row justify-content-center">
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 1 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 2 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 3 </b>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 4 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 5 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 6 </b>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 7 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 8 </b>
          </div>
        </div>
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 9 </b>
          </div>
        </div>
      </div>
      <div class="row justify-content-center">
        <div class="card m-1" style="width: 80px">
          <div class="card-body text-center">
            <b> 0 </b>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
onMounted(() => {
  introJs().start();
});
</script>

<style lang="scss" scoped></style>

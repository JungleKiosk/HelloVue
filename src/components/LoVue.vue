<script>

export default {
  name: 'LoVue',
  data() {

    return {
    }
  }
};

</script>

<template>
  <div class="container">
    <div class="row">

      <div class="col-6">
        <h1>Say</h1>
        <h1>Hello <span>Vue</span></h1>
        <h1>10 times</h1>

        <h2></h2>
      </div>

      <div class="col-6">
        <div>
          <a href="https://vitejs.dev" target="_blank">
            <img src="/vite.svg" class="logo" alt="Vite logo" />
          </a>
          <a href="https://vuejs.org/" target="_blank">
            <img src="../assets/vue.svg" class="logo vue" alt="Vue logo" />
          </a>
        </div>
      </div>

    </div>



  </div>
</template>

<style>
span {
  color: #40df98aa;
}

.logo {
  height: 6rem;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
</style>

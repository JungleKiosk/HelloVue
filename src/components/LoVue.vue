<script>

export default {
  name: 'LoVue',
  data() {

    return {
    }
  },
  mounted() {
    setTimeout(() => {
      const loveToo = document.querySelector("h2");
      loveToo.innerHTML = "&hearts; I love you too &hearts;";
      const linkVue = document.querySelector("p a");
      linkVue.innerHTML = "click here to be linked to the official <span>Vuejs</span> documentation site";
    }, 9000);
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
      <p><a class="link_quickstart" href="https://vuejs.org/guide/quick-start.html"></a></p>

    </div>



  </div>
</template>

<style>

span {
  color: #40df98aa;
}

span:hover {
  filter: drop-shadow(0.5rem 0rem 0.5rem #40df98aa);
}

h2 {
  color: #40df98aa;
  cursor: pointer;
  transition: all 0.3s ease;
}

h2:hover {
  background-color: #40df98aa;
  color: rgba(255, 255, 255, 0.87);
  border-radius: 50px;
  padding: 0.1rem 0.5rem;
}

.read-the-docs {
  color: #888;
}

.link_quickstart {
  text-decoration: none;
  color: rgba(255, 255, 255, 0.87);
}

.link_quickstart:hover {
  text-decoration: none;
  color: rgba(255, 255, 255, 0.87);
  filter: drop-shadow(0.5rem 0rem 0.5rem #40df98aa);
}

.logo {
  height: 6rem;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}


img:hover {
  animation: rotate 3s linear infinite;
}

@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}
</style>

<template>
  <div class="home">
    <div class="intro">
      <div class="intro-inner">
        <div class="ttl-group">
          <h2>
            Web Publisher<br />
            <em><b>Kang</b> JI Yeon</em>
          </h2>
        </div>
        <ul class="intro__btns-wrap">
          <li>
            <router-link tag="button" class="btn trn" to="/portfolio">
              Portfolio
            </router-link>
          </li>
          <li>
            <router-link tag="button" class="btn navy" to="/librarys"
              >Librarys</router-link
            >
          </li>
        </ul>
      </div>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

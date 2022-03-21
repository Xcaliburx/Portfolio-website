<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    
    <Title/>
    <About/>
    <MyWork/>
    <Contact/>
  </div>
</template>

<style scoped>
  p {
    color: black;
  }

  html {
    scroll-behavior: smooth;
  }
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Title from '@/components/Title.vue'
import About from '@/components/About.vue'
import MyWork from '@/components/MyWork.vue'
import Contact from '@/components/Contact.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld, Title, About, MyWork, Contact
  },
  methods: {
    scrollMeTo(refName) {
      var element = this.$refs[refName];
      var top = element.offsetTop;

      window.scrollTo(0, top);
    }
  },
  data: {
    apps: [
        {
            name: "Food Vision",
            logo: "food-vision-logo.png"
        }
    ]
  }
}
</script>

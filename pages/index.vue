<template>
  <div class="container">
    <gauche />
    <droite 
      @open="openIntro"
    />
    <introduction 
      v-show="isVisible"
      @close="closeIntro"
    />
  </div>
</template>

<script>
import Droite from '@/components/Droite'
import Gauche from '@/components/Gauche'
import Introduction from '@/components/Introduction.vue'
export default {
  components: {
    Droite,
    Gauche,
    Introduction
  },
  data() {
    let isVisible = false
    return {
      isVisible
    }
  },
  methods: {
    openIntro() {
      this.isVisible = true
    },
    closeIntro() {
      this.isVisible = false
    }
  }
}
</script>

<style>

  * {
    margin:0;
    padding: 0;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }

  h1,h2,h3 {
    font-size: 1rem;
    font-weight: 500;
  }

  .container {
    display: flex;
    height: 100vh;
    line-height: 1.3rem;
  }
  
  h1 {
    font-weight: bold;
  }
</style>
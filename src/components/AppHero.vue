<script>
export default {
  data() {
    return {
      imgOne: "src/assets/vue.svg",
      imgTwo: "vite.svg"
    }
  }
}
</script>

<template>
    <div>
        <img :src="`${imgOne}`" alt="Logo Vue">
        <img :src="`${imgTwo}`" alt="Logo Vite">
    </div>
</template>

<style scoped>
div{
    display: flex;
    justify-content: space-around;
}
img{
    width: 9.375rem;
    margin: .3125rem .625rem;
}
</style>

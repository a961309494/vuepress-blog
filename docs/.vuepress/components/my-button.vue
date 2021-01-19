<template>
    <button @click="handleClick">今天天气可真好呀！</button>
</template>

<script>
export default {
    name: "my-button",
    methods:{
        handleClick(){
          console.log("click!")
        }
    }
}
</script>

<style scoped>

</style>

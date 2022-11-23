<script setup>
defineProps({
  paragraph: String,
  title: String,
  btn: String
})
</script>

<template>
    <div class="jumbotron">
        <h2> {{title}} </h2>
        <p> {{ paragraph }}</p>
        <hr>
        <button> {{btn}} </button>
    </div>
</template>

<style scoped>
.jumbotron {
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background-color: #e9ecef;
  border-radius: .3rem;
}

hr {
    width: 50%;
    margin-top: 25px;
    opacity: 0.2;
}

button {
    margin-top: 20px;
}
</style>
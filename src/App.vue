<script>
import bootstrap from 'bootstrap';

export default {
  data(){
    return{
      title: 'Hello World' ,
      paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis, facere iste tempore deserunt iusto distinctio corporis eum quibusdam numquam ullam, quaerat eligendi voluptatum quasi aliquam fugit possimus, tempora laudantium assumenda.'
    }
  }
}
</script>

<template>
  <div class=" d-flex justify-content-center align-items-center text-center ">
    <h1 class=" text-center">{{ title }}</h1>
    <span><i class="fa-solid fa-earth-europe"></i></span>
    <p>{{ paragraph }} </p>
  </div>
</template>

<style scoped>
  
</style>
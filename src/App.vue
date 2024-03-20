<script>
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
  <div>
    <h1 class="piango">{{ title }}</h1>
    <p>{{ paragraph }} </p>
  </div>
</template>

<style scoped>
  .piango{
    color: red;
    text-align: center;
    font-size: 3rem;
    margin-top: 3rem;
  }

  p{
    text-align: center;
    color: blue;
    margin-top: 50px;
  }
</style>
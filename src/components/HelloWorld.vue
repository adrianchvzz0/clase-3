<template>
  <div class="content-center">
    Hello World
   <h3> info: {{ info }} </h3> 
  </div>
    
</template>

<script>
export default {
  data(){
    return{
      info: 'Adrián, 20977, 5A'
    }
  }
}
</script>

<style>
.content-center {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100px;
    text-align: center; 
   
}
</style>
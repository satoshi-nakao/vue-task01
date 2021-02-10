<template>
  <div class="message1">
    <h1>{{ message }}</h1>
    <a :href="url">Firebase</a>
  </div>
</template>

<script>


export default {
  data:function(){
    return{
       message:"私のお気に入りのページです。",
       url:"https://firebase.google.com/"
      }
    }
  }

</script>

<style>
.message1 {
  text-align: center;
  color: violet;
  margin-top: 60px;
}
</style>

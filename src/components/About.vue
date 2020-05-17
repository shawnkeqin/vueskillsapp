<template>
    <div class="about">
        <h1>this is {{their_name}}, about page </h1>
        <p> hello shawn </p>
    </div> 
</template>

<script>
export default {
  name: 'Skills',
  data(){
    return{
   
     their_name: this.$route.params.name 
      
  }
  }
}
</script>
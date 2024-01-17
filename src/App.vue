<script>
export default {
  data() {
    return  {count: 0}
  },
  
};

</script>

<template>
 <div>
      <h1> 
        ciao
      </h1>
      <p>
      {{ count }}
      </p>
      <button @click="count++">
      incre count
      </button>
  </div> 
</template>

<style scoped>

</style>

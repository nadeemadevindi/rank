<template>
  <div>

     <form>
    <div class="form-group">
        <label for="exampleInputEmail1">Product Name</label>
      <input type="text"
      v-model="name" 
      class="form-control" 
      id="exampleInputEmail1" 
      placeholder="Product Name"
      v-validate="'required'"
      >
       
   
   </div>
  </form>
  
  </div>

  
</template>

<script>
export default {
 
}
</script>

<style>

</style>

<template>
<div class="container">
   <div class="square">
      <img src="../assets/hellno.jpg" alt="">
   </div>
   <div class="text">
      <h3>meow</h3>
      <h3>meoww</h3>
      <h3>meowww</h3>
      <h3>meowwww</h3>
      <h3>meowwwww</h3>
      <h3>meowwwwww</h3>
      <h3>meowwwwwww</h3>
   </div>
</div> 
</template>

<script>
export default {
   name: "Square"
}
</script>

<style scoped>
.container {
   background-color: #fff;
   border: 1px solid #000;
}

.square {
   width: 50%;
   height: 100%;
   background-color: rgb(173, 250, 238);
   float: left;
   margin-right: 10px;
   text-align: center;   
}

img {
   margin-top: 50px;
   width: 200px;
}

img:hover {
   filter: saturate(7);
   transition: 0.5s;
}

.text {
   text-align: center;   
}
</style>
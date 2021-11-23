<template>
<div class="container">
   <div class="text">
      <h3>meowwwwwww</h3>
      <h3>meowwwwww</h3>
      <h3>meowwwww</h3>
      <h3>meowwww</h3>
      <h3>meowww</h3>
      <h3>meoww</h3>
      <h3>meow</h3>
   </div>

   <div class="square">
      <img src="../assets/business-cat.jpg" alt="">
   </div>
</div> 
</template>

<script>
export default {
   name: "SquareII"
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
   float: right;
   text-align: center;   
}

img {
   margin-top: 50px;
   width: 200px;
}

img:hover {
   filter: invert(100%);
   transition: 0.5s;
}

.text {
   display: inline-block;
   width: 50%;
   text-align: center;
   margin: none;  
}
</style>
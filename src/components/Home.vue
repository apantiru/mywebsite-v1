<template>
  <div class="hello">
     <div class="menu"> 
       <div class="menu-item">
         <div class="menu-text">
           Solutions
         </div>
       </div>
       <div class="menu-item">
         <div class="menu-text">
           Pricing
         </div>
       </div>
       <div class="menu-item menu-center">
           FRACTAL
       </div>
       <div class="menu-item">
         <div class="menu-text">
           Parteners
         </div>
       </div>
       <div class="menu-item">
         <div class="menu-text">
           Company
         </div>
       </div>

     </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.menu{
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
  height: 60px;
}

.menu-item{
  flex:1;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}

.menu-text{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}

.menu-text:hover {
  border-bottom: 2px solid green;

}

.menu-center{
  font-size: 36px;
  color: #eaeaea;
}



</style>

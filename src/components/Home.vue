<template>
    <div >
        <h1>Home Component</h1>
        <Users/>
        <Products/>
    </div>
</template>

<style scoped>
  div{
       background-color: #dde5ec;
       height: 500px;
  }
</style>

<script>
import Users from "./Users";
import Products from "./Products";
     export default{
        name:"Home",
        components:{
          Users,
          Products
        }
     }
</script>


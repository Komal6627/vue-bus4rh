<template>
  <div>
    <h1>Learning Componenet</h1>
    <!-- <div>
              <h1>Hello this is 1st component in Vue</h1>
    <h2>{{data}}</h2>   -->
    <!-- <button v-on:click="hello('Hello this is click event')">Call
              </button> -->
    <!-- <button v-on:mouseover="hello('Hello this is click event')">Call</button>
        </div>

        <!-- <div>
            <h1 v-if="show">Condition Render</h1>
            <h1 v-else>Condition Render else block</h1>
            <button v-on:click="display"> Toggle</button>
        </div> -->

    <table>
      <tr>
        <td>Id</td>
        <td>name</td>
        <td>email</td>
      </tr>

       <tr v-for="items in users" :key="items.id">
        <td>{{items.id}}</td>
        <td>{{items.name}}</td>
        <td>{{items.email}}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'Sample',
  //    props:{
  //     data:String
  //   },
  // methods:{
  //   hello(dt){
  //       alert(dt)
  //   }
  // },
  // data(){
  //   return{
  //     show:true
  //   }
  // },

  // methods:{
  //   display(){
  //       this.show= !this.show
  //   }
  // },

  data() {
    return {
      users: [
        { id: 1, name: 'Komal', email: 'komal@gamil.com' },
        { id: 2, name: 'Hayat', email: 'hayat@gamil.com' },
        { id: 3, name: 'Dimple', email: 'dimple@gamil.com' },
        { id: 4, name: 'Amit', email: 'amit@gamil.com' },
      ],
    };
  },
};
</script>

<template>
  <img alt="Vue logo" src="./assets/pic1.jpg">
  <h1>{{ firstnameE }}{{lastnameE}}</h1>
  <h1>{{ firstnameT }}{{lastnameT}}</h1>
  <h2>{{nickname}}</h2>
  <h2>{{age}}</h2>
  <h2>{{classx}}</h2>
  <h2>{{major}}</h2>
  <ul>
    <li>{{hobby [0]}}</li>
    <li>{{hobby [1]}}</li>
    <li>{{hobby [2]}}</li>
    <li>{{hobby [3]}}</li>
    <li>{{hobby [4]}}</li>
  </ul>
  <ul>
    <li>{{profile.gender}}</li>
    <li>{{profile.height}}</li>
  </ul>
</template>

<script>

export default {
  name: 'App',
  data(){
    return{
      firstnameE: "Chatchawarinthan",
      lastnameE : "Chaithep",
      firstnameT : "ฌัชชวรินทร์ธาร",
      lastnameT : "ชัยเทพ",
      nickname : "แก้ม",
      age : "20" ,
      tel : "0903188307" ,
      classx : "IT5102",
      major : "Information Technology",
      hobby : ["เล่นเกม","นอน","อ่านหนังสือ","ปลูกต้นไม้","เลี้ยงปลา"],
      profile:{gender:"female",height:155}
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

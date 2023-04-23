<template>
  <div class ="home">
    <h1>Home</h1>
    <h2>THE MIDDAYS</h2>
    <p>Living for art's sake</p>
    <img id= "photo" src = "https://scontent.fcrk1-4.fna.fbcdn.net/v/t39.30808-6/336912915_652681156619509_43724911237146074_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=09cbfe&_nc_eui2=AeFSMe1wcUip1fkNkKfcAy189RpO2fEDHgj1Gk7Z8QMeCKEbmeUl7n8jvxqyCdolxIBoTVebR7wKmWUo7CcVZ3Zc&_nc_ohc=ozaFrKn_VhkAX9N2McY&_nc_ht=scontent.fcrk1-4.fna&oh=00_AfDTY5s5RewXjG0YKD6MLTk-BnOgb74TjM6e4apG7KvgyQ&oe=644B0967">
  </div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'Home'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  color: black;
  text-align: center;
}
h2{
  text-align: center;
}
#photo{  
  width: 1000px;
  border: 1px solid black;
  padding-left: 350px;
}
p{
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
}

</style>
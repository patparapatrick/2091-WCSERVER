<template>
  <div class ="about">
    <h1>About Us</h1>
    <img id= "me" src = "https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/336793526_6961571633858222_1469787756651267432_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=e3f864&_nc_eui2=AeH0ULlhzcugyDetPajJT2nfnfzKYsRJ-qOd_MpixEn6o4EJ_ttbsWHHLP9b2SMEgQwNKXSP5XN6ZC9CDUx2pg3D&_nc_ohc=Wsf6YGZKeNgAX-mtGMI&_nc_ht=scontent.fcrk1-3.fna&oh=00_AfDDjlrz0Ji5L0sA7_s_wkBSI2HiR5OAOCLF9sIHV52iCg&oe=6449AA26">
    <h5>Hi! We are The Middays, an indie alternative rock band based in Pampanga. Driven by passion and friendship, we crash our own boundaries through songwriting and performing.</h5>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      title: 'about'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
    text-align: center;
}
h2{
    text-align: center;
}
#me{
  width: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
}
h5{
    text-align: center;
}
p{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    text-align: center;
}

</style>
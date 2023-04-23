<template>
  <div class ="blog">
    <h1>Blog</h1>
    <img id= "pic" src = "https://themiddays.files.wordpress.com/2023/03/331071655_1266844663920046_3603682186715216265_n-1.jpg? w=10000">
    <h5>February 17, 2023</h5>
    <h2>Teaser: GONZU</h2>
    <h5>We posted our first teaser for our song titled “Gonzu” in our social media platforms.
</h5>
 <img id= "pic" src = "https://themiddays.files.wordpress.com/2023/03/317984388_582154453921064_2031784993863841662_n.jpg? w=10000">
 <h5>December 02, 2022</h5>
 <h2>LIVE! at Laverne Grillery Bistro</h2>
 <h5>We were invited to perform in Laverne Grillery Bistro in December 2 with other great artists.</h5>
  </div>
</template>

<script>
export default {
  name: 'blog',
  data () {
    return {
      title: 'Blog'
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
#pic {
  width: 1400px;
  text-align: center;
  border: 1px solid black;
  height: 500px;
}
h5{
    text-align: center;
}

</style>
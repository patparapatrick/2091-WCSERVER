
<template>
  <div class ="gallery">
    <h1>Gallery</h1>
    <div class="row">
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-5.fna.fbcdn.net/v/t39.30808-6/334509129_962967714703735_504562624551310583_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=730e14&_nc_eui2=AeHjB3uOcp1UdgZM0OAsPBnY2P0vmbeFzaDY_S-Zt4XNoJYBuIiht5Fb4_AAIdjeKFSHCtDaMe0-5-8481kxxk9B&_nc_ohc=5MYMjs_lIn0AX_dYiQr&_nc_ht=scontent.fcrk1-5.fna&oh=00_AfCOFfhswFTWmz8t1Q9GZIfwxQ3uPzheaiwAwdGL-Jjqpg&oe=644A60D2" style="width:100%">
        </div>
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/326943125_140857648614365_3662645952888800737_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeFHAsZrxOxwlmf-ugi1g7TVtnDebYh20D22cN5tiHbQPa3tfziEiMK3AsILaFWomsihLSet0D67DZPDjql8HX3T&_nc_ohc=9Gmq6erQCMUAX9IKivF&_nc_ht=scontent.fcrk1-3.fna&oh=00_AfDzCAUL4Ta0Kcuc5M0xk6OPwQc4ZFL5Yj3PplVTAMyKLw&oe=644A43D8" style="width:100%">
        </div>
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-5.fna.fbcdn.net/v/t39.30808-6/330330012_852402872492819_1237010539194402010_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeEloSmOili1h1zyXn5TE6G93kjbvPAKwQLeSNu88ArBAuRzGPZdxtLrEKjXhRfQRJdUMgeU3l1oUdwZfI2xcmW1&_nc_ohc=r4vx2AFXm5AAX9aTPpK&_nc_ht=scontent.fcrk1-5.fna&oh=00_AfDCYnTB6hZbmt7gjCC3skzbxevSURT7kTZJg-MbLZsogA&oe=644A4945" style="width:100%">
        </div>
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/330426855_160742933442671_6028745876637564787_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeGar3maEb8l5MwqSmFdHc9iycAteb1aesfJwC15vVp6x-Tnv7NHbKbI8C2_qsl7BU99LmAJI_Xqk4bFDYCbQ2hR&_nc_ohc=7pcaPjWhReoAX_KEvem&_nc_ht=scontent.fcrk1-3.fna&oh=00_AfBbkJl6OiL3xia4eJXNPs6rcZg6D9mwTE7NDjgR2PnNXQ&oe=644B1228" style="width:100%">
        </div>
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/332204816_953382685656883_5473518077080810162_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeFszJ8b9j6ZV4_EWBTe7eSVgg7DLQQSGoOCDsMtBBIag6aBlDACHlrfHIi167weE86eWjClRJ7BUfbWnDLo6uYN&_nc_ohc=sQFtxQh_f1wAX-Cazh_&_nc_ht=scontent.fcrk1-3.fna&oh=00_AfAi2L_IiynvzlHGMMcgJlvhv1s0SbJ5x44JuCUFWR4YMQ&oe=6449518A" style="width:100%">
        </div>
        <div class="column">
    <img id= "pic" src = "https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/330428459_929141928260160_7226580718547305524_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeG92w58ejshyFUCUz73YLR1vyUAMpcAMWa_JQAylwAxZtnVFVHL9ESk95AaEO7vDG4RZANMvhI4pu3HndesZwyF&_nc_ohc=rMqYXn0gFGEAX_VB6E-&_nc_ht=scontent.fcrk1-3.fna&oh=00_AfB7-ec1WVjAcBXUIt91FgPEtto85VV-E1r98_T-8_ZuKw&oe=644A7EB3" style="width:100%">
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'gallery',
  data () {
    return {
      title: 'gallery'
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
.column{
    float: left;
    width: 33.33%;
    padding: 5px;
    border: 1px solid black;
}

.row::after{
    content: "";
    clear:both;
    display: table;

}

    
</style>
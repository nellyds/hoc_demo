<template>
  <v-app>

    <v-content>
      <v-responsive :aspect-ratio="16/16">
      <div class="header">
<v-img class="img" data-aos="fade-left" data-aos-duration="1000" data-aos-delay="500" src="@/assets/background.png"> </v-img>
<v-img class="img" data-aos="flip-down" data-aos-duration="1000" data-aos-delay="1000" src="@/assets/shadow.png"></v-img>
<v-img class="img" data-aos="flip-left" data-aos-duration="1000" data-aos-delay="1500" src="@/assets/middle.png"></v-img>
<v-img class="img" data-aos="flip-right" data-aos-duration="1000" data-aos-delay="2000" src="@/assets/sun.png"></v-img>
<v-img class="img" data-aos="flip-down" data-aos-duration="1000" data-aos-delay="2500" src="@/assets/foreShadow.png"></v-img>
<v-img class="img" data-aos="flip-up" data-aos-duration="1000" data-aos-delay="3000" src="@/assets/fore.png"></v-img>
<v-img class="img" data-aos="flip-right" data-aos-duration="1000" data-aos-delay="3500" src="@/assets/light.png"></v-img>
<h1 class="text" data-aos="fade-down" data-aos-delay="2000" > House of Clay</h1>

</div>
      </v-responsive>

    </v-content>
  </v-app>
</template>

<script>

export default {
  name: "App",

  components: {
  },
  data(){
    return{
      		bgc: {
			bgColor: ''
		},
    		color: '#1976D2FF',
		mask: '!#XXXXXXXX',
		menu: false,
    }},
};
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Kirang+Haerang&display=swap');
body{
font-family: 'Kirang Haerang', cursive;
color:white;
}
.img{
  position: absolute;
}
.text{
  font-family: 'Kirang Haerang', cursive;
  color: white;
  margin-top: 20%;
  margin-left: 50%;
font-size: 2em;
position: absolute;
}
.highlight{
  border: solid 3px white;
}
.header{
  margin: auto;
}

</style>

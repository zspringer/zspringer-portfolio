<template>
  <div id="portfolio">
    <!-- <h1>{{ msg }}</h1> -->
    <h2>{{msg}}</h2>
    <v-layout column wrap class="my-5" align-center>
      <!-- <v-flex xs12 sm4 class="my-3">
         <div class="text-xs-center">
           <h2 class="headline">The best way to start developing</h2>
           <span class="subheading">
             Cras facilisis mi vitae nunc 
           </span>
         </div>
       </v-flex> -->
      <v-flex xs12>
        <v-container grid-list-xl>
          <v-layout row wrap align-center>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                  <v-card-text class="text-xs-center">
                    <!-- <v-icon x-large class="black--text text--lighten-2">color_lens</v-icon> -->
                    <!-- <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,w_300/v1502836114/Screen_Shot_2017-08-15_at_4.25.54_PM_ygl0us.png"></img> -->
                    <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,h_202,w_300/v1502836114/Screen_Shot_2017-08-15_at_4.25.54_PM_ygl0us.png"></img>
                  </v-card-text>
                  <v-card-title primary-title class="layout justify-center">
                    <div class="headline text-xs-center">Inspire</div>
                  </v-card-title>
                  <v-card-text>
                    Example of a project that accesses several API's called through several services and controllers to provide a daily landing page.
                    Data is persistent through a Node server deployed to Heroku. 
                  </v-card-text>
                </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <!-- <v-icon x-large class="black--text text--lighten-2">flash_on</v-icon> -->
                  <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,w_300/v1507606013/Screen_Shot_2017-10-09_at_9.26.17_PM_ft8vks.png"></img>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <a class="headline" href="https://zspringer.github.io/NFL_Roster">NFL</a>
                </v-card-title>
                <v-card-text>
                  Example of a project that utilizes the NFL API to create a list of players for a fantasy football team.  This project
                  was built with vanilla Javascript and Bootstrap.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <!-- <v-icon x-large class="black--text text--lighten-2">build</v-icon> -->
                  <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,h_202,w_300/v1507664722/Screen_Shot_2017-10-10_at_1.42.30_PM_akwlzt.png"></img>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <a class="headline text-xs-center" href="https://zdkanban.herokuapp.com" >Kanban</a>
                </v-card-title>
                <v-card-text>
                  Example of a collaborative team full stack applicationn using Vue, Node, Bootstrap and MongoDB to build Kanban boards to better help
                  users with project management.  This project is very similar to Trello.
                </v-card-text>
              </v-card>
            </v-flex>

            <v-flex xs12 md6>
              <v-card class="elevation-0 transparent">
                  <v-card-text class="text-xs-center">
                    <!-- <v-icon x-large class="black--text text--lighten-2">color_lens</v-icon> -->
                    <!-- <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,w_300/v1502836114/Screen_Shot_2017-08-15_at_4.25.54_PM_ygl0us.png"></img> -->
                    <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,h_202,w_300/v1507667916/Screen_Shot_2017-10-10_at_2.38.04_PM_wjz1ov.png"></img>
                  </v-card-text>
                  <v-card-title primary-title class="layout justify-center">
                    <a class="headline text-xs-center" href="https://tattoo-me.herokuapp.com/#/home">Tattoo-Me</a>
                  </v-card-title>
                  <v-card-text>
                    Tattoo-Me was a group capstone project which was a full stack application that used Vue, Node and a MongoDB.  This full scale application
                    featured two user groups, a person wanting a tattoo and an artist, and the idea was to use a for-profit business model that would allow
                    both parties to meet in the middle.  The user could preview the tattoo using their mobile camera before purchasing an artist's design
                    using Stripe for payment, and in turn would receive a hi-resulution tattoo image via email from the app. This app also had an integrated
                    Google Maps API for finding the closest tattoo parlor near the users location.
                  </v-card-text>
                </v-card>
            </v-flex>
            <v-flex xs12 md6>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <!-- <v-icon x-large class="black--text text--lighten-2">flash_on</v-icon> -->
                  <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,h_202,w_300/v1507680335/Screen_Shot_2017-10-10_at_6.04.55_PM_dafwvg.png"></img>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <a class="headline" href="http://vue-music-is-fun.herokuapp.com/#/">Vue Music</a>
                </v-card-title>
                <v-card-text>
                  Example of my first project built with Vue.js.  This project utilizes the iTunes API as well as Node.js to build
                  a playlist of short music clips persisted through a Node server and hosted at Heroku.
                </v-card-text>
              </v-card>
            </v-flex>
            <!-- <v-flex xs12 md4>
              <v-card class="elevation-0 transparent">
                <v-card-text class="text-xs-center">
                  <v-icon x-large class="black--text text--lighten-2">build</v-icon>
                  <img src="http://res.cloudinary.com/dmyvekzok/image/upload/c_scale,h_202,w_300/v1507664722/Screen_Shot_2017-10-10_at_1.42.30_PM_akwlzt.png"></img>
                </v-card-text>
                <v-card-title primary-title class="layout justify-center">
                  <a class="headline text-xs-center" href="https://zdkanban.herokuapp.com" >Blah</a>
                </v-card-title>
                <v-card-text>
                  Example of a collaborative team full stack applicationn using Vue, Node, Bootstrap and MongoDB to build Kanban boards to better help
                  users with project management.  This project is very similar to Trello.
                </v-card-text>
              </v-card>
            </v-flex> -->




          </v-layout>
        </v-container>
      </v-flex>
    </v-layout>
  </div>
</template>

<script>
  export default {
    name: 'portfolio',
    data () {
      return {
        msg: 'Portfolio'
      }

    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  /* h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
} */
</style>
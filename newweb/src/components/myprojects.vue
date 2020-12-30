<template>
  <v-container>
    <v-row align="center" justify="center" class="mb-6">
      <v-sheet
        outlined
        rounded
        color="#495057"
        class="pa-4"
        align="center"
        justify="center"
        elevation="2"
      >
        <h1 id="work">A few of the projects I have currently completed</h1>
      </v-sheet>
    </v-row>
    <v-row class="ma-6">
      <v-card class="mx-auto pa-4" max-width="344">
        <v-img src="@/assets/Okotokspizza.png"> </v-img>
        <v-card-actions>
          <v-btn text color="teal accent-4" @click="reveal = true">
            Learn More
          </v-btn>
        </v-card-actions>

        <v-expand-transition>
          <v-card
            v-if="reveal"
            class="transition-fast-in-fast-out v-card--reveal"
            style="height: 100%"
          >
            <v-card-text class="pb-0">
              <p class="display-1 text--primary">
                My First HTML and CSS Project
              </p>
              <p>
                This project was created for a client who needed a website for
                his pizza shop in Okotoks. This was completed at the end of
                learning HTML and CSS.
              </p>
              Check out the site at
              <a href="http://okotokslovespizza.ml">www.okotokslovespizza.ml</a>
            </v-card-text>
            <v-card-actions class="pt-0">
              <v-btn text color="teal accent-4" @click="reveal = false">
                Close
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-expand-transition>
      </v-card>

      <v-card class="mx-auto pa-4" max-width="344">
        <v-img src="@/assets/wetbatml.png"> </v-img>
        <v-card-actions>
          <v-btn text color="teal accent-4" @click="reveal1 = true">
            Learn More
          </v-btn>
        </v-card-actions>

        <v-expand-transition>
          <v-card
            v-if="reveal1"
            class="transition-fast-in-fast-out v-card--reveal"
            style="height: 100%"
          >
            <v-card-text class="pb-0">
              <p class="display-1 text--primary">
                MVP code Challenge for LaunchCode
              </p>
              <p>
                This is a full stack project as proof of concept. This was a
                challenge that was completed in 12 hours. I learned alot when
                doing this project. On this website you have the ability to
                create a quote, view all quotes, update a quote and delete a
                quote.
              </p>
              Check out the site at <a href="http://wetbat.ml">www.wetbat.ml</a>
            </v-card-text>
            <v-card-actions class="pt-0">
              <v-btn text color="teal accent-4" @click="reveal1 = false">
                Close
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-expand-transition>
      </v-card>

      <v-card class="mx-auto pa-4" max-width="344">
        <v-img src="@/assets/twatter.png"> </v-img>
        <v-card-actions>
          <v-btn text color="teal accent-4" @click="reveal3 = true">
            Learn More
          </v-btn>
        </v-card-actions>

        <v-expand-transition>
          <v-card
            v-if="reveal3"
            class="transition-fast-in-fast-out v-card--reveal"
            style="height: 100%"
          >
            <v-card-text class="pb-0">
              <p class="display-1 text--primary">Twitter Clone Project</p>
              <p>
                This was one of the major projects I have worked on. This was a
                very challenging project that allowed me to learn how a frontend
                communicates witht the backend. Feel free to create a new user
                and post some tweets.
              </p>
              Check out the site at
              <a href="http://billastweeter.ml">www.billastweeter.ml</a>
            </v-card-text>
            <v-card-actions class="pt-0">
              <v-btn text color="teal accent-4" @click="reveal3 = false">
                Close
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-expand-transition>
      </v-card>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    reveal:false,
    reveal1:false,
    reveal3:false
  }),
};
</script>

<style lang="scss" scoped>
.v-card--reveal {
  bottom: 0;
  opacity: 1 !important;
  position: absolute;
  width: 100%;
}
#work {
  width: 100%;
  color: white;
  text-shadow: 2px 3px 1px black;
}
</style>
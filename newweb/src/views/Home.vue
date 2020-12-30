<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <v-img
      dark
      max-height="500px"
      src="https://lh3.googleusercontent.com/proxy/0oL7iaYRHWKSFenPF9XDzK_cpoTMYJReVr0wkG3DklHymidSh419m3Arzwwg8acLD5lXrxDuc0do2TRf1TVqUaix7zrakydNqPDwtGk_bZPjOC01C64mrGDJpjgwC0B4eCztSySjaWzxDhgLrfURC98"
    >
      <v-layout fill-height align-center>
        <v-container>
          <v-row align="center" justify="center" class="white--text">
            <v-col cols="12">
              <div
                :class="{
                  'display-2 font-weight-bold ': $vuetify.breakpoint.smAndUp,
                  'title font-weight-bold': $vuetify.breakpoint.smAndDown,
                }"
              >
                Welcome to my page.
              </div>
              <div
                :class="{
                  headline: $vuetify.breakpoint.smAndUp,
                  'subtitle-1': $vuetify.breakpoint.smAndDown,
                }"
              >
                I Create Fullstack Applications.
              </div>
            </v-col>
          </v-row>
        </v-container>
      </v-layout>
    </v-img>
    <v-container>
      <v-row align="center" justify="center">
        <v-col xs="12" sm="8">
          <v-card outlined rounded>
            <v-card-title id="about" class="display-1" primary-title>
              About Me
            </v-card-title>
            <v-card-text>
              I lost my job as a petroleum technologist due to the impacts of
              Covid-19. I took this as an oppurtunity to change my career path
              completely. I have recently graduated from Innotech College as a
              fullstack developer. Nothing compares to the dopamine response of
              overcoming a challenge. That is why I am excited to begin my
              career in the tech industry. Everytime I learn something new I
              find that there is so much more to learn. I am looking forward to
              the upcoming challnges that I will face!
            </v-card-text>
            <v-card-title primary-title>
              Current Developer Skills
            </v-card-title>
            <v-list>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Databases</v-list-item-title>
                  <v-list-item-subtitle
                    >Ability to create a relational database for the backend of
                    a full stack application</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Wireframes (FIGMA)</v-list-item-title>
                  <v-list-item-subtitle
                    >Before building any application. Planning is completed
                    using Figma.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>MariaDB(DBeaver)</v-list-item-title>
                  <v-list-item-subtitle
                    >The relational database I use is
                    mariadb.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Flask</v-list-item-title>
                  <v-list-item-subtitle
                    >The framework that sits on top of python and communicates
                    between the front end and the backend.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>HTML, CSS, Javascript</v-list-item-title>
                  <v-list-item-subtitle
                    >Proficient in the foundations.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>VueJS/Vuetify</v-list-item-title>
                  <v-list-item-subtitle
                    >The framework that I use that sits on top of the HTML CSS
                    and Javascript</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>REST APIs</v-list-item-title>
                  <v-list-item-subtitle
                    >Representational State and transfer APIs that follow the
                    protocols of client-server, cache, uniform interface, and
                    layered system.
                  </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Python</v-list-item-title>
                  <v-list-item-subtitle
                    >Proficient in the programming launguage of
                    python.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Git Control</v-list-item-title>
                  <v-list-item-subtitle
                    >All projects are made with a git repository and save points
                    are frequent.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Git Control</v-list-item-title>
                  <v-list-item-subtitle
                    >All projects are made with a git repository and save points
                    are frequent.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Responsive Web Design</v-list-item-title>
                  <v-list-item-subtitle
                    >All projects are made with mobile responsiveness
                    first.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Apache</v-list-item-title>
                  <v-list-item-subtitle
                    >Apache configuration for the a
                    webserver.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>MS Office</v-list-item-title>
                  <v-list-item-subtitle
                    >Proficient in word, powerpoint, and
                    excel.</v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
              <v-list-item two-line>
                <v-list-item-content>
                  <v-list-item-title>Updated Resume</v-list-item-title>
                  <v-list-item-subtitle>
                    <a
                      href="@/public/UP_Bilal_Abdurahman.PDF" download="@/public/UP_Bilal_Abdurahman.PDF"
                      >Download a pdf copy of my resume.</a
                    ></v-list-item-subtitle
                  >
                </v-list-item-content>
              </v-list-item>
            </v-list>
          </v-card>
        </v-col>
        <v-col xs="12" sm="8" md="6" lg="4">
          <v-sheet
            outlined
            rounded
            color="#adb5bd"
            class="pa-4"
            align="center"
            justify="center"
          >
            <v-card class="ma-4 pa-4">
              <v-img src="@/assets/Portfolio-Logo.svg"> </v-img>
            </v-card>
            <v-card class="ma-4 pa-4">
              <v-img src="@/assets/hiking.jpg"> </v-img>
            </v-card>
          </v-sheet>
        </v-col>
        <v-row>
          <v-container id="portfolio">
            <v-sheet outlined rounded color="#adb5bd" class="pa-4">
              <myprojects></myprojects>
            </v-sheet>
          </v-container>
          <v-container>
              <v-parallax
    src="@/assets/animewall.jpg"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col
        class="text-center"
        cols="12"
      >
        <h1 class="display-1 font-weight-thin mb-4">
          I LOVE ANIME
        </h1>
      </v-col>
    </v-row>
  </v-parallax>
          </v-container>
          <v-container id="contact">
            <v-sheet
              outlined
              rounded
              color="#495057"
              class="pa-4"
              align="center"
              justify="center"
              elevation="2"
            >
              <h1 id="work">Contact info</h1>
            </v-sheet>
            <v-card v-for="(contact, i) in contactLinks" :key="i">
              <pcontactinfo :contact="contact"></pcontactinfo>
            </v-card>
          </v-container>
        </v-row>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import Pcontactinfo from "../components/Pcontactinfo.vue";
import Myprojects from "../components/myprojects.vue";
export default {
  name: "home",
  components: {
    Myprojects,
    Pcontactinfo,
  },
  data() {
    return {
      contactLinks: [
        {
          name: "Email",
          value: "billa.abdu@gmail.com",
          link: "mailto:billa.abdu@gmail.com",
          icon: "mdi-email",
        },
        {
          name: "LinkedIn",
          value: "Bilal Abdurhaman",
          link: "www.linkedin.com/in/bilal-abdurahman-220078a4",
          icon: "mdi-linkedin",
        },
        {
          name: "Github",
          value: "BilalA",
          link: "https://github.com/billag93/",
          icon: "mdi-github",
        },
        {
          name: "Instagram",
          value: "@thedarksaiyan",
          link: "https://www.instagram.com/thedarksaiyan/",
          icon: "mdi-instagram",
        },
      ],
    };
  },
};
</script>
<style lang="scss" scoped>
#work {
  width: 100%;
  color: white;
  text-shadow: 2px 3px 1px black;
}
</style>
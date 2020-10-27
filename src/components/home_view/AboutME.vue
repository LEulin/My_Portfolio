<template>
  <div class="text-center">
    <br>
    <v-row>
      <v-col cols="5">
        <v-card class="mx-auto" max-width="344">
          <v-img src="https://cdn.vuetifyjs.com/images/cards/forest-art.jpg"></v-img>

          <v-card-text>
            <h2 class="title primary--text">Magento Forests</h2>Travel to the best outdoor experience on planet Earth. A vacation you will never forget!
          </v-card-text>

          <v-card-title>
            <v-rating :value="4" dense color="orange" background-color="orange" hover class="mr-2"></v-rating>
            <span class="primary--text subtitle-2">64 Reviews</span>
          </v-card-title>

          <v-fade-transition>
            <v-overlay v-if="hover" absolute color="#036358">
              <v-btn>See more info</v-btn>
            </v-overlay>
          </v-fade-transition>
        </v-card>
        <!-- <v-img src="@/assets/coverphoto.jpg" class="coverPhoto"></v-img> -->
      </v-col>
      <v-col>
        <v-card class="card">
          <v-toolbar flat color="secondary" class="text-center" dark>
            <h1 class="display-1">ABOUT ME</h1>
          </v-toolbar>
          <v-tabs vertical>
            <v-tab>SCHOOL</v-tab>
            <v-tab>ORGANIZATION</v-tab>
            <v-tab>HOBBIES</v-tab>
            <v-tab>LIKES</v-tab>
            <v-tab>MY RESUME</v-tab>

            <v-tab-item>
              <v-card flat class="text-center">
                <v-card-text>
                  <v-img class="uscLogo" src="@/assets/uscLogo.jpg"></v-img>
                  <br>
                  <p>I am a proud Carolinian. University of San Carlos has been the best school I am very proud of.</p>
                </v-card-text>
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat class="text-center">
                <v-card-text>
                  <v-img class="pnLogo" src="@/assets/pn-logo.png"></v-img>
                  <br>
                  <p>Passerelles Numeriques has taught me to become a new versio of myself. Be optimistic and responsible in everything. I am proud PN scholar.</p>
                </v-card-text>
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat class="text-center">
                <v-card-text>
                  <v-img class="hobby" src="@/assets/dance.jpg"></v-img>
                  <p>Dancing is my favorite hobby. It removes my stress and I feel happy everytime I dance.</p>
                  <v-img class="hobby" src="@/assets/book.png"></v-img>
                  <p>Writing and reading my journal for me is my favorite thing to do. Because for me, taking notes about life events and world encouters are important.</p>
                </v-card-text>
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat class="text-center">
                <v-card-text>
                  <v-img class="like" src="@/assets/explore.png"></v-img>
                  <br>
                  <p>I like to discover and explore new things that can help to improve my skills and abilities, build my confidence and become a better version of myself.</p>
                </v-card-text>
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat class="text-center">
                <br>
                <v-btn class="danger mt-16 pa-2" href="./resume/resume.pdf">
                  <i class="mdi mdi-file-pdf"></i>Click here for my resume
                </v-btn>
              </v-card>
            </v-tab-item>
          </v-tabs>
        </v-card>
      </v-col>
    </v-row>
    <div id="about" class="text-center">
      <br>
    </div>
  </div>
</template>
<style scoped>
.coverPhoto {
  height: 400px;
  width: 300px;
  float: right;
}
.card {
  width: 600px;
  height: 400px;
}
.uscLogo {
  width: 180px;
  height: 180px;
  margin-left: 30%;
}
.pnLogo {
  width: 150px;
  height: 150px;
  margin-left: 30%;
}
.hobby {
  width: 150px;
  margin-left: 30%;
}
.like {
  width: 120px;
  margin-left: 30%;
}
.pdf {
  width: 200px;
  margin-left: 20%;
}
</style>

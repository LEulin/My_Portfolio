<template>
  <div>
    <h1 class="display-1 text-center">MY PORTFOLIO</h1>
    <br>
    <div class="text-center pa-5">
      <v-row>
        <v-col v-for="n in 6" :key="n" cols="4" md="4">
          <v-hover>
            <template v-slot:default="{ hover }">
              <v-card class="mx-auto" max-width="344">
                <v-img src="https://cdn.vuetifyjs.com/images/cards/forest-art.jpg"></v-img>

                <v-card-text>
                  <h2 class="title primary--text">Magento Forests</h2>Travel to the best outdoor experience on planet Earth. A vacation you will never forget!
                </v-card-text>

                <v-card-title>
                  <v-rating
                    :value="4"
                    dense
                    color="orange"
                    background-color="orange"
                    hover
                    class="mr-2"
                  ></v-rating>
                  <span class="primary--text subtitle-2">64 Reviews</span>
                </v-card-title>

                <v-fade-transition>
                  <v-overlay v-if="hover" absolute color="#036358">
                    <v-btn>See more info</v-btn>
                  </v-overlay>
                </v-fade-transition>
              </v-card>
            </template>
          </v-hover>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      overlay: false
    };
  }
};
</script>

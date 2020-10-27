<template>
  <div class="container text-center">
    <v-card class="pa-4" width="1000">
      <v-card-title class="text-center justify-center py-6">
        <h1 class="display-1">BASIC SKILLS</h1>
      </v-card-title>
      <v-tabs centered horizontal>
        <v-tab>LANGUAGES</v-tab>
        <v-tab>UI FRAMEWORKS</v-tab>
        <v-tab>TOOLS</v-tab>
        <v-tab-item centered>
          <v-card flat>
            <v-row>
              <v-col>
                <v-img class="logo" src="@/assets/java.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/ang.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/python.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/html.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/javascript.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/vue.png"></v-img>
              </v-col>
            </v-row>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-row>
              <v-col>
                <v-img class="logo" src="@/assets/CSS.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/boots.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/vueboots.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/vuetify.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/native.png"></v-img>
              </v-col>
            </v-row>
          </v-card>
        </v-tab-item>
        <v-tab-item>
          <v-card flat>
            <v-row>
              <v-col>
                <v-img class="logo" src="@/assets/sublime.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/vscode.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/gith.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/bitbucket.png"></v-img>
              </v-col>
              <v-col>
                <v-img class="logo" src="@/assets/command.png"></v-img>
              </v-col>
            </v-row>
          </v-card>
        </v-tab-item>
      </v-tabs>
    </v-card> 
  </div>
</template>

<style scoped>
.container {
  width: 950px;
}
.coverPhoto {
  height: 400px;
  width: 300px;
  margin-left: 40%;
}
.card {
  width: 1000px;
  height: 400px;
  margin-left: 0%;
}
.logo {
  width: 120px;
  height: 120px;
}
</style>

<script>
export default {
  data() {
    return {
      logos: []
    };
  }
};
</script>


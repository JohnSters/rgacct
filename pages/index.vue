<template>
  <v-container>
    <v-card class="landing hidden-sm-and-down" style="margin-top: 115px" flat>
      <v-img src="/logo/logo.svg"></v-img>
      <p class="blue-grey--text display-1 text-center mt-8">"Trust is earned when actions meets words"</p>
    </v-card>
    <v-card class="landing-mb hidden-md-and-up" style="margin-top: 150px" flat>
      <v-img src="/logo/logo.svg"></v-img>
      <p class="blue-grey--text  text-center mt-3">"Trust is earned when actions meets words"</p>
    </v-card>
    <div class="hidden-sm-and-down" id="tree1">
      <img src= "/tree.png">
    </div>
    <div id="tree2">
      <img src= "/tree.png">
    </div>
    <div class="hidden-sm-and-down" id="tree3">
      <img src= "/tree.png">
    </div>
  </v-container>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
html, body {
  margin:0;
  padding:0;
}

#tree1 {
  position:fixed;
  right: 22px;
  bottom: 44px;
  margin: 0;
  padding: 0;
}

#tree2 {
  position:fixed;
  right: 40%;
  bottom: 44px;
  margin: 0;
  padding: 0;
  transform: scaleX(-1);
}

#tree3 {
  position:fixed;
  right: 84%;
  bottom: 44px;
  margin: 0;
  padding: 0;
}
</style>

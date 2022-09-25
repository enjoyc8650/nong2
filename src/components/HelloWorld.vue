<template>

  <v-container>
    <v-row>
      <v-col
        
        v-for="n in 6"
        :key="n"
        cols="12"
        sm="4"
      >
        <v-card
          class="pa-6"
          outlined
          tile
          color="blue"
        >
          肯定还是
        </v-card>
      </v-col>
    </v-row>
  </v-container>

  <v-bottom-navigation :value="value" color="teal" grow>
    <v-btn>
      <v-icon>mdi-heart</v-icon>
      <span>主页</span>
    </v-btn>
    <v-btn>
      <v-icon>mdi-map-marker</v-icon>
      <span>分类</span>
    </v-btn>
    <v-btn>
      <v-icon>mdi-map-marker</v-icon>
      <span>更多</span>
    </v-btn>
    <v-btn>
      <v-icon>mdi-history</v-icon>
      <span>我的</span>
    </v-btn>
  </v-bottom-navigation>
  
</template>

<script>

export default {

}
</script>

<template>
  <v-container>
    <v-row>
      <v-col cols="12" md="4">
        <v-card color="#fff">
          <v-img
            src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
            height="200px"
          ></v-img>
          <v-card-title>Card Title</v-card-title>
          <v-card-subtitle>Card Subtitle</v-card-subtitle>
          <v-card-text>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          </v-card-text>
          <v-card-actions>
            <v-btn @click="handleClick">Action</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  methods: {
    handleClick() {
      alert('Button clicked!');
    }
  }
};
</script>

<template>
  <v-container fluid>
        <v-row>
          <v-col cols="12" sm="6">
            <!-- Example content -->
            <v-card>
              <v-card-title>Responsive Content</v-card-title>
              <v-card-text>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
                nec dolor nisl. Fusce ac tortor purus.
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>
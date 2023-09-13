<template>
  <div>
    <v-container>
      <v-row>
        <v-col
        v-for="count in 12"
        :key="count"
        cols="3"
        sm>
          <v-card class="pa-3" outlined>
            col
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {

}
</script>
<style lang="">

</style>

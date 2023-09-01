<template>
  <v-container fluid>
    <v-card class="pa-3">
      <v-row>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-spacer />
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
        <v-card class="pa-3" outlined>
          Col
        </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-spacer />
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
        <v-card class="pa-3" outlined>
          Col
        </v-card>
        </v-col>
      </v-row>
            <v-row>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
        <v-card class="pa-3" outlined>
          Col
        </v-card>
        </v-col>
      </v-row>
    </v-card>
    <v-card class="mt-5 pa-3">
      <v-layout>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
      </v-layout>
      <v-layout>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
        <v-flex>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-flex>
      </v-layout>
    </v-card>

    <!-- 3번째 카드 -->
    <v-card class="mt-5 pa-3">
      <!-- 첫번째 Row -->
      <v-row :style="{height: '120px'}" class="red" align="center">
         <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
          </v-col>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
      </v-row>
      <!-- 두번째 Row -->
      <v-row :style="{ height: '120px' }" class="yellow">
        <v-col align-self="end">
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col align-self="center">
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col align-self="start">
        <v-card class="pa-3" outlined>
          Col
        </v-card>
        </v-col>
      </v-row>
            <v-row>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
          <v-card class="pa-3" outlined>
            Col
          </v-card>
        </v-col>
        <v-col>
        <v-card class="pa-3" outlined>
          Col
        </v-card>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>
<script>
export default {

}
</script>
<style lang="">

</style>

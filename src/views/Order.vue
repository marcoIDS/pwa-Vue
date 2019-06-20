<template>
    <v-stepper v-model="e6" vertical>
    <v-stepper-step :complete="e6 > 1" step="1">
      Selecciona tamaño de tu pizza
      <small>Elije el tamaño de tu pizza</small>
    </v-stepper-step>

    <v-stepper-content step="1">
      <v-card color="#e1e9f7 lighten-1" class="mb-5" height="10px">
        <v-layout row wrap align-center>
        <v-flex xs6>
            <v-subheader>Tamaños</v-subheader>
        </v-flex>

        <v-flex xs6>
            <v-select
            v-model="select"
            :hint="`${select.state}, ${select.abbr}`"
            :items="items"
            item-text="state"
            item-value="abbr"
            label="Select"
            persistent-hint
            return-object
            single-line
            ></v-select>
        </v-flex>
        </v-layout>
      </v-card>
      <v-btn color="primary" @click="e6 = 2">Continue</v-btn>
      <v-btn flat>Cancel</v-btn>
    </v-stepper-content>

    <v-stepper-step :complete="e6 > 2" step="2">Configure analytics for this app</v-stepper-step>

    <v-stepper-content step="2">
      <v-card color="grey lighten-1" class="mb-5" height="200px"></v-card>
      <v-btn color="primary" @click="e6 = 3">Continue</v-btn>
      <v-btn flat>Cancel</v-btn>
    </v-stepper-content>

    <v-stepper-step :complete="e6 > 3" step="3">Select an ad format and name ad unit</v-stepper-step>

    <v-stepper-content step="3">
      <v-card color="grey lighten-1" class="mb-5" height="200px"></v-card>
      <v-btn color="primary" @click="e6 = 4">Continue</v-btn>
      <v-btn flat>Cancel</v-btn>
    </v-stepper-content>

    <v-stepper-step step="4">View setup instructions</v-stepper-step>
    <v-stepper-content step="4">
      <v-card color="grey lighten-1" class="mb-5" height="200px"></v-card>
      <v-btn color="primary" @click="e6 = 1">Continue</v-btn>
      <v-btn flat>Cancel</v-btn>
    </v-stepper-content>
  </v-stepper>
</template>

<script lang="ts">    
    import { Component, Vue} from 'vue-property-decorator'

    @Component({

    })

    export default class order extends Vue{        
        data () {
            return {
                e6: 1,
                select: { state: 'Grande', abbr: 'GD' },
                items: [
                { state: 'Grande', abbr: 'GD' },
                { state: 'Mediana', abbr: 'MD' },
                { state: 'Personal', abbr: 'PS' },
                ]
            }        
        }
    }
</script>

<style lang="">

</style>


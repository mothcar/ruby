<template>
  <v-container>
    <v-row class="text-center">
      
    </v-row>
  </v-container>
</template>

<script>
import logo from '../assets/logo.svg'

export default {
  name: 'HelloWorld',

  data: () => ({
    
  }),

  

  mounted() {
    // console.log('I am mounted...')
    this.hello()
  },

  created() {
    console.log('I am created...')
    console.log('this : ', this)
    this.dady()
  },





  methods: {
    hello() {
      console.log('I am hello...')
    },

    dady() {
      console.log('I am your father...')
    }
    
  },
}
</script>

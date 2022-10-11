<template>
  <!-- <div v-for="word in words" :key="`${word}-word`">{{word}}</div> -->
  <div>
    a
  </div>
</template>

<script>
export default {
  name: 'RandomWords',
  props:{
    input: String
  },
  data(){
    return {
      letters: ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z"],
      words: [],
      words_count: 0
    }
  },
  mounted(){
    this.generateWords()
  },
  updated(){
      this.generateWords()
  },
  methods:{
    generateWords(){
      setTimeout(()=>{
          if (this.words.length < 20){
            let word = this.generateWord()
            this.words.push(word)
            }
      }, 1500);
    },
    generateWord(){
      let word = "";
      let length = Math.random() * (6 - 1) + 1;
      for(let i = 0; i < length; i++){
        let index = Math.floor(Math.random() * this.letters.length);
        word +=this.letters[index]

      }
      return word      
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
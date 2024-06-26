<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    <button @click="increase">KLIKNIJ</button>
    <p>{{ licznik }}</p>
  </main>
</template>
<script>
export default 
{
  data(){
    return {licznik:0}
  },
  methods: {
    increase: function()
    {
      this.licznik++;
    }
  }
}
</script>
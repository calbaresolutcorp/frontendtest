<template>
<div >
<img  src="../assets/Discover.png" alt=""  />
  </div> 
</template>
<script>
export default {
  data(){
      return {
        message: "Hello World",
        boolVar: true,
        arrayVar: [1,2,3,4]
      }
  },
  methods: {
    getTotal(){
      var total = 0;
      for (const item of this.arrayVar) {
        total += item;
      }
      this.message = total;
    }
  },
  mounted() {
    this.getTotal();
  },
  created(){
  },
  beforeMount(){
  },
  updated(){
  },
  beforeUpdate(){
  }
}
</script>

<style >

</style>

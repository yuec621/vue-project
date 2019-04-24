<template>
    <div class="background" :style="note">
        
    </div>
</template>
<script>
export default {
    name:'Background',
    data(){
     return {
         note: {
            position:"fixed",
            backgroundImage: "url(" + require("../assert/background.jpg") + ") ",
            backgroundSize:"100% 100%",
            backgroundRepeat: "no-repeat",
            top:"0",
            left:"0"
        }

    }
}
}
</script>
<style  lang="scss">
  .background{
      width: 100%;
      height: 100%;
  }
     
</style>
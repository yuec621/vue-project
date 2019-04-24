<template>
    <div class="background" >
        <img class="week"  src="../assert/week.png" />  
        <div class="week-p">第几周</div>
          <img class="airplain"  src="../assert/airplain.png" />   
        <img class="begin"  src="../assert/begin.png" />    
    </div>
</template>
<script>
export default {
    name:'Background',
    data(){
     
}
}
</script>
<style lang="scss">
  .background{
      width: 100%;
      height: 100%;
      position:fixed;
      background: url("../assert/background.jpg") no-repeat;
      background-Size:100% 100%;
      top: 0;
      left: 0;
       .week{
           display:inline-block;
            margin: -3rem 0 0 16rem;
            width: 7rem;
            }   
      .airplain{
          display: inline-block;
          width: 18rem;
          height: 18rem;
          margin: -1rem auto;
      }
      .begin{
          position: relative;
          display: inline-block;
          margin: 2rem auto;
          width: 6rem;

    }
    .week-p{
        color: rgb(201, 113, 201);
        margin: -3.5rem 0 0 16rem;
    }
       
  }

     
</style>
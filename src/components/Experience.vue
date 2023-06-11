<!-- Experience.vue -->
<template>
    
        <!-- Your experience content goes here -->
        <section class="secondSection">
        <span class="text-gray">What I have done so far</span>
        <h1>Work Experience</h1>

        <div class="box">
            <div class="vertical"></div>
            <div class="vertical"></div>
            <div class="vertical"></div>
            <div class="vertical"></div>
        </div>
      </section>
   
</template>
  
<script>
export default {
    name: "AppExperience",
};
</script>
  
<style>
.secondSection{
    max-width: 80vw;
    margin: auto;
    height: 80vh;
  }

  .text-gray{
    color: gray;
  }

  .secondSection h1 {
    font-size: 1.9rem;
  }

  .secondSection .box {
    background: white;
    width: 80vw;
    height: 1px;
    margin: 35px 0;
  }

  .secondSection .vertical {
    
  }

</style>
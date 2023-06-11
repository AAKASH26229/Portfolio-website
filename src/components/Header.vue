<!-- Header.vue -->
<template>
    <header>
      <!-- Your header content goes here -->
      <main>
      <section class="firstSection">
        <div class="leftSection">
          Hi, My name is <span class="purple">Aakash Parate</span>
          <div>and I am a passionate</div>
          <div>web developer</div>
          <div class="buttons">
            <button>Download Resume</button>
            <button>Contact Me</button>
          </div>
          
        </div>
        <div class="rightSection">
          <img src="../assets/background.png" alt="background image">
        </div>
      </section>
      <hr>
    </main>
    </header>
  </template>
  
  <script>
  export default {
    name: "AppHeader",
  };
  </script>

  <style>
.firstSection{
    display: flex;
    justify-content: space-around;
    margin: 100px 0;
    align-items: center;
  }

  .firstSection > div{
    width: 30%;
  }
  
  .leftSection{
    font-size: 3rem;
  }
  
  .rightSection img{
    width: 80%;
   
  }
  
  .purple{
    color: chartreuse;
  }

main hr {
    border: 0;
    background: #9C97f1;
    height: 1.4px;
    margin: 60px 104px;
}
</style>
<!-- Navbar.vue -->
<template>
    <nav>
      <!-- Your navigation bar content goes here -->
      <div class="left">Portfolio</div>
            <div class="right">
              <ul>
                <li><a href="/Home">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact Me</a></li>
              </ul>
            </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: "AppNavbar",
  };
  </script>


<style>
*{
    margin: 0;
    padding: 0;
  }

  body{
    background-color: rgb(4, 4, 62);
    color: white;
    font-family: 'Poppins', sans-serif;
  }

  nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 75px;
    background-color: rgb(37, 40, 108);
  }

  nav ul {
    display: flex;
    justify-content: center;
  }

  nav ul li {
    list-style: none;
    margin: 0 23px;
  }

  nav ul li a {
    text-decoration: none;
    color: white;
  }

  nav ul li a:hover {
    color: blueviolet;
    font-size: 1.02rem;
  }

.left{
    font-size: 1.5rem;
}
</style>
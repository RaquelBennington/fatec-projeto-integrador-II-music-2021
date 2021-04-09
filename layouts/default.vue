<template>
  <div>
    <nav>
      <img src="../assets/logo.png" alt="logo">
      <ul>
        <li><nuxt-link to="/">Inicio</nuxt-link></li>
          <li><nuxt-link to="/destaques">Destaques</nuxt-link></li>
      </ul>
    </nav>
    <Nuxt />
  </div>
</template>

<style>
body {
  font-family: sans-serif;
}
  nav{
    display: flex;
    justify-content: space-between;
    background: #000;
    height: 80px;
    width: 100%;
  }

  nav img{
   margin: 0 15px;
   padding: 10px;

  }

  nav ul{
    align-items: center;
    margin-right: 20px;
   
  }

  nav ul li{
    display: inline-block;
    align-items: center;
    line-height: 80px;
    margin: 0 15px;
    color: white;
  }

  .hero{
    width: 100%;
    height: 230px;
    background-color: #000;
    color: white;
    text-align: center;
    font-size: 40px;
  }
</style>
<script>

</script>

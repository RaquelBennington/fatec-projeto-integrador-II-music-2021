<template>
 <div class="">
     <section class="hero">
       <h1>Vá de <strong>5G</strong>. E seja feliz</h1>
       <button class="primary">Fazer minha conta</button>     
  
    </section>

    <div class="container">
      <h1>É Musica que você quer?</h1>
      <p class="texto-topo"> Conheça os melhores lançamentos dos nossos artistas.</p>
    <button id="player" class="primary">Abrir web player</button>

    <div id="cont1" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Eai, vamo la porra teste, teste</div>
        </div>
      </div>
    </div>
      <div id="cont2" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Teste teste teste teste teste</div>
        </div>
      </div>
    </div>
     <div id="cont3" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Teste teste teste teste teste</div>
        </div>
      </div>
    </div>

     <div id="cont4" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Teste teste teste teste teste</div>
        </div>
      </div>
    </div>
      <div id="cont5" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Teste teste teste teste teste</div>
        </div>
      </div>
    </div>
     <div id="cont6" class="content">
      <div class="card">
        <div class="mediacard"></div>
        <div class="bottoncard">
          <div class="bottontext">Teste teste teste teste teste</div>
        </div>
      </div>
    </div>

    </div>
    
</div>
</template>

<script>
  export default {}

  
</script>

<style>
  .primary{
    border: 2px solid #000;
    background-color: #fff;
    color: #000;
    border-radius: 10px;
    width: 170px;
    height: 50px;
    text-align: center;
    padding: 0; 
    font-size: 18px;
  
  }
.content{
  display: flex;
  justify-content: center;
  align-content: center;
  width: 100%;
  height: 260px;
  margin: 15px;
}
.card{
  background-color: #fff;
  border-radius:15px;
  box-shadow: 0px 2px 25px rgba(26, 24, 53, 0.671);
}
.mediacard{
  background: url("../assets/image.jpg") center/cover;
  height: 200px;
  width: 100%;
  border-top-left-radius:15px;
  border-top-right-radius:15px;
}

/*-------------*/
.container{
  display: grid;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr;
  grid-template-columns: 240px 240px 240px 240px 240px;
  margin-left: 100px;
  
}

h1{
  font-size: 40px;
  grid-column-start: 2;
  grid-column-end: 5;
  grid-row-start: 1;
  grid-row-end: 2;
  justify-self: center;
}
.texto-topo{
  font-size: 20px;
   grid-column-start: 2;
   grid-column-end: 5;
   grid-row-start: 1;
   grid-row-end: 2;
   align-self: center;
    place-self: center;
}
#player{
   grid-column-start: 3;
   grid-column-end: 4;
   grid-row-start: 1;
   grid-row-end: 2;
    place-self: center;
    align-self: end;
    margin-bottom: 40px;
}
#cont1 {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    grid-row-end: 3; 
}
#cont2 {
   grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 3; 
}
#cont3{
   grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 2;
    grid-row-end: 3; 
}
#cont4{
     grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 4; 
}
#cont5{
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 3;
    grid-row-end: 4;  
}
#cont6{
  grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 3;
    grid-row-end: 4; 
}
</style>
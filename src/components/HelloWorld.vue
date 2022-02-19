<template>
  <div class="hello">
  <nav>
     <img class="logo" src="../assets/iconecafe.svg" />
     <h1>Melitta</h1>
     <img class="logo" src="../assets/iconecafe.svg" />
  </nav>
  <div class="cafe">
    <div>
    <h1>Melitta Café de qualidade<br></h1>
    <h3> Desde 1908 trazendo para você os melhores produtos para o melhor café que se pode tomar ;</h3>
    <h3>Experimente nossos café em pó e sinta o poder e a energia do café correr por suas veias.</h3>
    </div>
    <img class="cafecapa" src="../assets/cafecapa.jpg"/>
  </div>
  <div class="comprar">
    <div class="cardcafe">
    <img class="melittaespecial" src="../assets/melittaespecial.jpg" />
    <button class="button">Comprar</button>
    <h2 class="dica">café melita especial, torne seu dia especial tome nosso café especial</h2>
    </div>
    <div class="cardcafe">
    <img class="melittafazenda" src="../assets/melittafazenda.jpg" />
    <button class="button">Comprar</button>
    <h2 class="dica">café melita fazenda, o verdadeiro sabor do campo pra você se sentir em contato com  a natureza</h2>
    </div>
    <div class="cardcafe">
    <img class="melittatradicional" src="../assets/melita.jpg" />
    <button class="button">Comprar</button>
    <h2 class="dica">café melita, faz bem para sua saúde e deixa seu dia bem melhor</h2>
    </div>
  </div>
 <footer>Criado por:</footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
 
};
</script>


<style >
.hello{
   width: 100%;
  height: 100%;
}
nav{
  display: flex;
  justify-content:space-between;
  background-color: cadetblue;
  align-items: center;
  padding:0;
  margin:0;
}
.logo {
  width: 50px;
  height: 50px;
}
.cafe {
  display: flex;
  justify-content:center;
  width: 100%;
  height: 310px;
  background-color: burlywood;
  font-size: 26px;
}
h1{
  margin:0;
}
.cardcafe{
  display: flex;
  justify-content: center;
  align-items: center;
   width: 32.111%;
  height: 400px;
  margin: 10px;
  background-color: white;
  font-size: 18px;
}
.button {
  width: 200px;
  height: 100px;
  margin: 5px;
  font-size: 28px;
  border:solid 1px red;
  
}
.melittaespecial {
  width: 150px;
  height: 270px;
  margin: 10px;
}
.melittatradicional{
  width: 150px;
  height: 250px;
  margin: 10px;
}
.melittafazenda{
  width: 150px;
  height: 250px;
  margin: 10px 0 0 28px;
}
.cafecapa{
  width: 100%;
  height: 305px;
}
.comprar{
  display: flex;
  background-color: rgb(25, 209, 209);
  
}
.dica{
  width: 250px;
  height: 250px;
}
footer{
  background-color: burlywood;
}
</style>

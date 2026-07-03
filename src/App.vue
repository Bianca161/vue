<script setup>

</script>

<template>

  <section class="banner">
  <video autoplay muted loop playsinline src="/public/videos/planta.mp4"></video>

    <h1>Dê um novo lar para uma planta.</h1>
  </section>

  <section class="intro">
    <p>
      Cada planta tem uma história e merece continuar crescendo. Encontre a companheira ideal para
      sua casa, apartamento ou escritório e transforme qualquer ambiente em um espaço mais vivo,
      bonito e acolhedor.
    </p>

    <button>Ver plantas disponíveis</button>
  </section>

  <section class="sobre nós">
    <h2>Cultivando conexões com a natureza</h2>
    <div>
    <p>
      O GreenNest nasceu para aproximar pessoas e plantas. Muitas espécies são descartadas ou
      deixadas de lado por falta de espaço ou tempo de seus antigos cuidadores. Aqui, elas ganham
      uma nova oportunidade de florescer ao lado de alguém disposto a cuidar delas com carinho.
    </p>

    <img src="/public/imagens/flor.png" alt="flor" />
    </div>
  </section>

  <section class="adotar">
    <h3>Encontre sua próxima companheira verde</h3>

    <p>
      Explore nossa coleção de plantas disponíveis para adoção. Utilize os filtros para encontrar
      espécies ideais para iniciantes, ambientes internos ou locais com bastante iluminação.
    </p>

    <button>Ver plantas</button>
  </section>

  <footer>
<img src="/public/imagens/logo.png" alt="logo">

<p> &copy; Alguns direitos reservados</p>
  </footer>

</template>

<style scoped>
.banner{
  position: relative;
   width: 100%;
   min-height: 100vh;
  video{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
}

.banner h1{
  font-size: 5rem;
  color: #A6B985;
  align-items: center;
  justify-content: center;
  text-align: center;
  /*posição*/
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.intro{
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 3rem;
  color: #213435;
}
.intro button{
  background-color: #213435;
  color: #E1E3AC;
  border: none;
  padding: 1rem 2rem;
  font-size: 1.2rem;
  cursor: pointer;
  border-radius: 12px;
}

.sobre.nós{
  background-color: #213435;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 3rem;
  color: #213435;
}
.sobre.nós div{
  display: flex;
}
.sobre.nós h2{
  font-size: 2rem;
  color: #E1E3AC;
}
.sobre.nós p{
 color: #E1E3AC;
 font-size: 1.2rem;
}

.adotar{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 3rem;
  color: #213435;
}
.adotar button{
  background-color: #213435;
  color: #E1E3AC;
  border: none;
  padding: 1rem 2rem;
  font-size: 1.2rem;
  cursor: pointer;
  border-radius: 12px;
}
.adotar h3{
  font-size: 2rem;
  color: #213435;
}

footer{
  background-color: #213435;
}
footer p{
  color: #FFFFFF;
  text-align: center;
  padding: 1rem;
}
</style>

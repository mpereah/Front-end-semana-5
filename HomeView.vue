<template>
  <div class="home">
    <div class="hijo">
      <img alt="portada" src="../assets/portada2.jpg">
      <div class="texto">PASTELERIA GALACTICAKE</div>
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>

    <div id="imagenes">
      <div class="a">
      <img alt="pastel" src="@/assets/3lechescajeta.png">
      <h3 id="tinto">Pastel de Vino Tinto</h3>
      <label for="tinto">Precio $200.00</label><br>
      <button>agregar al carrito</button>
      </div>

      <div class="b">
      <img alt="pastel" src="@/assets/3lechesrompope.png">
      <h3 id="tinto">Pastel de 3 Leches con Cajeta</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

      <div class="c">
      <img alt="pastel" src="@/assets/3lechesvainilla.png">
      <h3 id="tinto">Pastel de 3 Leches con Vainilla</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

      <div class="d">
      <img alt="pastel" src="@/assets/cajeta.png">
      <h3 id="tinto">Pastel de Cajeta</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

      <div class="e">
      <img alt="pastel" src="@/assets/chocolate-fresa.png">
      <h3 id="tinto">Pastel de Chocolate con fresas</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

       <div class="f">
      <img alt="pastel" src="@/assets/pastelcafe.png">
      <h3 id="tinto">Pastel de Cafe</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

       <div class="g">
      <img alt="pastel" src="@/assets/vainilla-fresa.png">
      <h3 id="tinto">Pastel de Vainilla con Fresas</h3>
      <label for="tinto">Precio $250.00</label><br>
      <button>agregar al carrito</button>
      </div>

    </div>
  </div>

  <div class="container-contacto">
    <div class="formato">
      <img src="../assets/portada.jpg" alt="formato">
      <div class="datos">
        <h2>CONTACTO</h2>
        <div class="direccion">
          <p>Nevado 113 Col. Portales, Benito Juárez, CDMX.</p> 
          <p>Horarios de atención a clientes en sucursales: 
          Lunes a Sábado:  8 a.m. a 8 p.m. 
          Domingos: 9 a.m. a 8 p.m</p>
          <p>Teléfono: 1234562356</p>
        </div>
      </div>
    </div>
  </div>  


</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Hurricane&family=Rock+3D&display=swap');

.home{
  position: relative;
  display: inline-block;
  text-align: center;
  max-height: 200px;
}

.texto{
  position: absolute;
  top: 50%;
  left: 50%;
  font-size: 4rem;
  font-family: hurricane;
  transform: translate(-50%, -50%);
  color:black;
}

.container-contacto{
  position: relative;
  display: inline-block;
  text-align: center;
  max-height: 200px;
  opacity: 0.7;
  padding: 20px;
}

.datos{
  position: absolute;
  top: 50%;
  left: 50%;
  font-size: 1.3rem;
  font-family: sans-serif;
  transform: translate(-50%, -20%);
  color:fuchsia;
  text-shadow: 1px 3px 1px black;
}

#imagenes{
  width: 100%;
}  

#imagenes .a{
  display: inline-block;
  padding: 10px;
}

#imagenes .b{
  display: inline-block;
  padding: 20px;
}

#imagenes .c{
  display: inline-block;
  padding: 20px;
}

#imagenes .d{
  display: inline-block;
  padding: 20px;
}

#imagenes .e{
  display: inline-block;
  padding: 20px;
}

#imagenes .f{
  display: inline-block;
  padding: 20px;
}



</style>

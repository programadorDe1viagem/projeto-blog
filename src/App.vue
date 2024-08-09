<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img src="../src/assets/logo_filme.png" alt="logo" class="imgl">


      <img src="../src/assets/filme1.avif" alt="sair" class="img2">

      <select name="sair" id="">
        <option value="sair">Sair</option>
        <option value="config">Configurações</option>
      </select>
  
  </header>
  
  <main>

    <div class="blog">
      <div class="imgb">
        <img src="../src/assets/filme3.jpeg" alt="">
      </div>

      <div>
        <div class="descricao">
          <h1>Alerta vermelho</h1>
          <p>
            Um agente do FBI persegue o ladrão de arte mais procurado do mundo. Ele só não esperava ter seu alvo como parceiro para prender uma bandida muito esperta.
          </p>
        </div>

        <div class="autor">Autor do blog:    Robert</div>
        
      </div>
    </div>

    <div class="blog">
      <div class="imgb">
        <img src="./assets/filme4_563x450.jpeg" alt="">
      </div>

      <div>
        <div class="descricao">
          <h1>Wall-E</h1>
          <p>
            Wall-E é o último destes robôs, que se mantém em funcionamento graças ao auto-conserto de suas peças. Sua vida consiste em compactar o lixo existente no planeta, que forma torres maiores que arranha-céus, e colecionar objetos curiosos que encontra ao realizar seu trabalho.
          </p>
        </div>

        <div class="autor">Autor do blog:    Robert</div>
        
      </div> 
    </div>

    <div class="blog">
      <div class="imgb">
        <img src="./assets/harry.webp" alt="">
      </div>

      <div>
        <div class="descricao">
          <h1>Harry Potter</h1>
          <p>
            é um garoto órfão de 10 anos que vive infeliz com seus tios, os Dursley. Até que, repentinamente, ele recebe uma carta contendo um convite para ingressar em Hogwarts, uma famosa escola especializada em formar jovens bruxos.
          </p>
        </div>

        <div class="autor">Autor do blog:    Robert</div>
        
      </div> 
    </div>

    
  </main>
</template>

<style scoped>
main {
  margin: 0;
  padding: 0;
  position: absolute;
}

header{
  display: inline-flex;
}

.imgl{
  width: 80px;
  height: 80px;
  margin-right: 1300px ;
}

.img2{
  width: 50px;
  height: 40px;
}

select{
  width: 50px;
  height: 40px; 
}

.blog{
  background-color: aliceblue ;
  margin-left: 280px;
  margin-bottom: 50px;
  width: 900px;
  height: 800px;
  text-align: center
}

.imgb{
  padding: 20px;
}

.autor{
  margin-top: 80px
}

p{
  font-size: 20px;
}
</style>

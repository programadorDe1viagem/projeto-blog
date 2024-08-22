<script>
export default {
  name: 'App',
  data() {
    return {
      nome: "Robert Souza"
    }
  }  
}
</script>

<script setup>
import Componente from './components/ComponenteBlog.vue'

</script>

<template>
  <div id="cabecalho">
    <div class="cabecalho-col1">
    <h1>Etec</h1>
    </div> 

    <div class="sla">
      <div class="cabecalho-col1" id="cabecalho-login">
      <a class="login" href="">login - {{ nome }}</a>

      </div>
    </div>
  </div>
  <h2>post - 1</h2>
  <Componente />

  <h2>post - 2</h2>
  <Componente />

  <h2>post - 3</h2>
  <Componente />

  <!-- <div id="area_postagem">
    <div class="post">
      post 1
      <img src="./assets/logo.svg" alt="" width="400px">
      <h2>Titulo Da Postagem</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras elit sapien, ullamcorper vel rhoncus at, rhoncus gravida enim. Sed a blandit tellus. Donec porttitor dignissim mollis. Suspendisse hendrerit non risus tincidunt sollicitudin. Etiam consectetur, arcu ac posuere sodales, sapien erat tristique massa, a elementum sapien risus sed velit. Nam id vehicula tortor. In nunc lectus, egestas eu placerat sed, lacinia ac dolor. Ut sit amet magna non ex fermentum ornare id at mi. Integer purus magna, laoreet eget molestie vitae, convallis ut nibh. Vestibulum fermentum mi mi, sed hendrerit risus fermentum auctor. In in quam consequat, euismod justo at, faucibus tortor. Nam lacinia ipsum ut nisi dapibus, non volutpat leo luctus. Sed mollis felis enim, in congue velit tristique quis. Aliquam at neque at mi pulvinar dapibus. Integer mollis malesuada dui, in volutpat nisi porta venenatis. Aenean elit dolor, pretium a rutrum in, fringilla eget turpis.</p>
      <p class="autor">por Robert Souza</p>
    </div>
      
    <div class="post">
      post 2
      <img src="./assets/logo.svg" alt="" width="400px">
      <h2>Titulo Da Postagem</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras elit sapien, ullamcorper vel rhoncus at, rhoncus gravida enim. Sed a blandit tellus. Donec porttitor dignissim mollis. Suspendisse hendrerit non risus tincidunt sollicitudin. Etiam consectetur, arcu ac posuere sodales, sapien erat tristique massa, a elementum sapien risus sed velit. Nam id vehicula tortor. In nunc lectus, egestas eu placerat sed, lacinia ac dolor. Ut sit amet magna non ex fermentum ornare id at mi. Integer purus magna, laoreet eget molestie vitae, convallis ut nibh. Vestibulum fermentum mi mi, sed hendrerit risus fermentum auctor. In in quam consequat, euismod justo at, faucibus tortor. Nam lacinia ipsum ut nisi dapibus, non volutpat leo luctus. Sed mollis felis enim, in congue velit tristique quis. Aliquam at neque at mi pulvinar dapibus. Integer mollis malesuada dui, in volutpat nisi porta venenatis. Aenean elit dolor, pretium a rutrum in, fringilla eget turpis.</p>
      <p class="autor">por Robert Souza</p>
    </div>

    <div class="post">
      post 3
      <img src="./assets/logo.svg" alt="" width="400px">
      <h2>Titulo Da Postagem</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras elit sapien, ullamcorper vel rhoncus at, rhoncus gravida enim. Sed a blandit tellus. Donec porttitor dignissim mollis. Suspendisse hendrerit non risus tincidunt sollicitudin. Etiam consectetur, arcu ac posuere sodales, sapien erat tristique massa, a elementum sapien risus sed velit. Nam id vehicula tortor. In nunc lectus, egestas eu placerat sed, lacinia ac dolor. Ut sit amet magna non ex fermentum ornare id at mi. Integer purus magna, laoreet eget molestie vitae, convallis ut nibh. Vestibulum fermentum mi mi, sed hendrerit risus fermentum auctor. In in quam consequat, euismod justo at, faucibus tortor. Nam lacinia ipsum ut nisi dapibus, non volutpat leo luctus. Sed mollis felis enim, in congue velit tristique quis. Aliquam at neque at mi pulvinar dapibus. Integer mollis malesuada dui, in volutpat nisi porta venenatis. Aenean elit dolor, pretium a rutrum in, fringilla eget turpis.</p>
      <p class="autor">por Robert Souza</p>
    </div>
  </div> -->


</template>

<style scoped>

.cabecalho-col1{
  height: 30px;
}
p{
  width: 1000px;
}

h2{
  font-weight: bolder;
}

h1{
  font-size: 60px;
}

.autor{
  font-size: 0.8em;
}

.post{
  background-color: gainsboro;
  margin-top: 20px;
  padding: 20px;
}

.cabecalho-col1{
  display: inline-block;
}

.sla{
  text-align: right;
}

.login{
  font-size: 40px;
}


  
</style>

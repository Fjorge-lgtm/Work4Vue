<template>
    <div class="formulario">
      <h1>{{ msg }}</h1>
      <h3> Ainda não é possível conexão com um banco de dados.</h3> <br>
      <h4>Entre em contato pelo cel.: 62-996170120</h4> <br>
      <form>
        <div>
          <label for ="nome">Nome:</label>
          <input type = "text" id="nome" v-model = "nome" required>
        </div>
        <br>
        <div>
          <label for ="email">Email:</label>
          <input type = "text" id="email" v-model = "email" required>
        </div>
        <br>
        <button type = "sumit">Cadastrar</button>
              
      </form>
      
    </div>
</template>
  
  <script>
  export default {
    name: 'FormularioGeral',
    props: {
      msg: String,
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #a142b9;
  }
  </style>
  
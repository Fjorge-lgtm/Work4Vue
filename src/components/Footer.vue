<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        Temos um grande prazer em nos apresentar,<br>
         no entanto, muito por aprender, mas aos poucos,  <br>
        obtendo pequenas vitorias.
        
      </p>
      
    </div>
</template>
  
  <script>
  export default {
    name: 'FooterRodape',
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
  
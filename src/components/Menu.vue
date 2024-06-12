<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <p>
        Nossas expectativas com relação ao Vue.js são excelentes.<br>
           
      </p>
     
      <ul>
        <li><a href="https://www.youtube.com/channel/UCXYJLleUGbzahZUqi5zG4Ag" target="_blank" rel="noopener">Home</a></li>
        <li><a href="https://www.google.com.br/?gws_rd=ssl" target="_blank" rel="noopener">Pesquisa</a></li>
        <li><a href="https://github.com/Fjorge-lgtm/Site-Curriculo" target="_blank" rel="noopener">Contatos</a></li>
        <li><a href="https://agendadigital.website" target="_blank" rel="noopener">Serviços</a></li>
      </ul> 
    </div>
</template>
  
  <script>
  export default {
    name: 'MenuGeral',
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
  
<template>
    <div class="not-found">
      <h1>404 - Страница не найдена</h1>
      <p>К сожалению, страница, которую вы ищете, не существует.</p>
      <router-link to="/">Вернуться назад</router-link>
    </div>
  </template>
  
  <script>
  export default {
    name: 'NotFound'
  };
  </script>
  
  <style scoped>
  .not-found {
    text-align: center;
    margin-top: 50px;
  }
  
  .not-found h1 {
    font-size: 2em;
    margin-bottom: 20px;
  }
  
  .not-found p {
    font-size: 1.2em;
    margin-bottom: 20px;
  }
  
  .not-found a {
    text-decoration: none;
    color: #42b983;
    font-weight: bold;
  }
  </style>
  
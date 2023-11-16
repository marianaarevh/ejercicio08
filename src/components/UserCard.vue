<template>
    <div class="user-card">
      <div class="user-info">
        <h2>{{ username }}</h2>
        <h4>{{ email }}</h4>
        <p>{{ biography }}</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      username: {
        type: String,
        required: true
      },
      email: {
        type: String,
        required: true
      },
      biography: {
        type: String,
        required: true
      }
    }
  };
  </script>
  
  <style scoped>
  .user-card {
    border: 1px solid rgb(195, 204, 253);
    padding: 10px;
    margin: 10px;
    border-radius: 10px;
    display: flex;
  }
  
  .user-info {
    text-align: left;
    margin: 15px;
  }
  
  h2 {
    margin: 0;
  }
  </style>
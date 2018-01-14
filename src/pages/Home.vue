<template>
  <div class="main">
    <img class="personal-image" src="./../assets/dubai_me.jpeg" alt="">
    <div class="information-container">
      <div class="header">
        <p>| | |</p>
      </div>
      <div class="container">
        <h1 class="title item">Tomás Ruiz</h1>
        <h2 class="subtitle item">Software Developer</h2>
        <a href="#" class="action-button item">
          Who am i?
        </a>
      </div>
      <div class="footer">
        <p>CONTACT ME</p>
      </div>
    </div>
  </div>
</template>

<script>
export default { }
</script>

<style>
  .action-button{
    border: 2px solid #27251F ;
    color: #27251F ;
    font-family: 'Muli';
    font-size: 25px;
    margin-top: 1em;
    padding: 10px;
    text-decoration: none;
  }

  .action-button:hover{
    background-color: #27251F ;
    color: white;
  }

  .button-main {
    font-weight: 600;
    font-style: normal;
    font-variant: normal;
    text-transform: uppercase;
    text-decoration: none;
    text-align: center;
    text-indent: 0px;
  }

  .container {
    align-self: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .footer {
    align-self: flex-end;
    font-size: 20px;
    padding: 20px;
  }

  .header {
    align-self: flex-end;
    display: flex;
    justify-content: space-between;
    padding: 20px;
  }

  .information-container {
    display: flex;
    flex-direction: column;
    flex:1;
    justify-content: space-between;
    min-height: 100vh;
  }

  .item {
    align-self: center;
  }

  .main {
    display: flex;
    font-family: 'Muli';
  }
  .personal-image {
    height: 100vh;
    max-height: 100vh;
    width: auto;
  }

  .subtitle {
    color: #808080;
    font-family: Muli;
    margin-top: 5px;
  }

  .title {
    color: rgba(0,0,0);
    font-family: 'Muli', black;
    font-size:50px;
  }

  @media only screen and (max-width: 1020px) {
    .main {
      flex-direction: column-reverse;
    }
    .personal-image {
      display: none;
    }
  }
</style>

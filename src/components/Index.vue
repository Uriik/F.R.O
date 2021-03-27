<template>
  <div class="PrimaryContainer">
    <header class="Container flex">
      <div class="BarLogo">
        <h1 class="Logo">
          <img
            src="../assets/logo.png"
            alt="Foto Fabrica de Sinal, Fabrica de Renda Online"
          />
        </h1>
      </div>
    </header>

    <div class="Phone flex Justify-content-center">
      <img src="../assets/celular.png" alt="" />
    </div>

    <div class="LanceHouse flex Justify-content-center Flex-direction-column">
      <p class="UpMoney">Aumente sua renda sem sair de casa</p>
      <p class="legend-white">método comprovado</p>
    </div>

    <div class="SubscribeNow flex Justify-content-center">
      <a class="Button" href="https://ev.braip.com/ref?pl=pla40rmp&ck=che2gxdp&af=afigod37m" target="_blank">Assine agora!</a>
    </div>

    <div class="whatsapp-link">
      <a
        class=""
        href="https://api.whatsapp.com/send?phone=5511958497537&text=Olá%20gostaria%20de%20saber%20mais%20sobre%20o%20método.%20Quero%20alavancar%20meu%20negócio!"
        target="_blank"
      >
        <i class="fab fa-whatsapp"></i>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Index",
  msg: String,
};
</script>
<style>
.BarLogo{
    background-color: #22242C;
    height:70px;
    width: 100vw;
}
h1{
    margin: 0;
    padding: 0;
}
.Logo{
    padding-top: 15px;
    margin: 0 auto;
    height: 50px;
    width: 100px;
}
.Phone{
  display: flex;
  align-items: flex-start;
}

.Phone>img{
  width:100%;
  max-width: 400px;
    margin: 0 auto;
    margin-top: 10px;
    display: flex;
    align-items: flex-start;
}

.PrimaryContainer {
  background-color: #121317;
  min-height: 100vh;
}

.whatsapp-link {
  border-bottom-left-radius: 50%;
  box-shadow: 1px 1px 2px #888;
  border-top-left-radius: 50%;
  background-color: #fff;
  text-align: center;
  font-size: 30px;
  position: fixed;
  z-index: 1000;
  color: #fff;
  height: 45px;
  width: 45px;
  top: 100px;
  right: 0px;
  
}
.whatsapp-link a {
  justify-content: space-around;
  text-decoration: none;
  align-items: center;
  border-radius: 50%;
  color: #26d366;
  display: flex;
  height: 45px;
  width: 45px;
  
}

.UpMoney{
    margin-left: 40px;
    margin-right: 40px;
    margin-bottom: 5px;
    font-size: 1.8em;
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    color:#F7D268;
    text-align: center;
}
</style>
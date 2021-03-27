<template>
        <div class="FourContainer">

            <div class="ContainerPacket flex Flex-direction-column Align-items-center">

                <div class="TextAlReady flex Flex-direction-column Align-items-center ">
                    <h2 class="Already">Pronto para<br> começar?</h2>
                    <p class="legend-white">agarre essa oportunidade</p>
                </div>

                <div class="CardPacket flex Flex-direction-column Align-items-center">
                    <p class="TextPacket">{{plan.title}}</p>
                    
                    <p class="TextValorPacket"><span class="ValorPk">12xR$ </span>{{plan.value}}</p>
                    <span class="TotalValue"> ou R$ 297,00 à vista</span>
                    <p class="TextBonus">Análise de métricas</p>
                    <p class="TextBonus">Método de engajamento</p>
                    <p class="TextBonus">Estética de venda</p>
                    <p class="TextBonus">Anúncios patrocinados</p>
                    <p class="TextBonus">Isca digital</p>
                    <a class="ButtonBot" href="https://ev.braip.com/ref?pl=pla40rmp&ck=che2gxdp&af=afigod37m" target="_blank">assine agora!</a>
                </div>
            </div>
        </div>
</template>

<script>

export default {
  name: 'PacketPremium',
  data(){
      return{
          plan:{
      title: "Pacote Premium",
      value: "29,82"
  }
      }
      
  }
  

}
</script>

<style>

.FourContainer{
    height: auto;
    background-color: #121317;
    padding: 3rem 20px;
}
.ContainerPacket{
    align-self:center ;
}

.Already{

    font-weight: bold;
    font-size: 2.0em;
    text-align: center;
    color:#F7D268;
    margin-bottom: 5px;
    
}
.GetOpt{

    font-weight: 300;
    font-size: 1.0em;
    text-transform: uppercase;
    text-align: center;
    color:white;
    margin: 10px 0 15px 0;
}

.CardPacket{
    background-color: #F7D268;
    margin: 15px;
    padding:15px;
    border-radius: 15px;
    width:100%;
    max-width: 370px;
    min-height: 310px;
    box-sizing: border-box;
    
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
}

.TextPacket{

    font-weight: bold;
    font-size: 1.3em;
    text-transform: uppercase;
    margin: 10px 0 0 0;
    padding: 0;
}

.TextValorPacket{
    font-family: 'Open Sans', sans-serif;
    font-weight: bold;
    font-size: 2.5em;
    
    padding: 10px;
    line-height: 32px;
    display: flex;
}


.TextBonus{

    font-weight: 400;
    font-size: 0.9em;
    margin: 10px 0 0 0;
    padding: 0;
}
.ValorPk{
    font-family: 'Open Sans', sans-serif;
    font-weight: 300;
    font-size: 0.3em;
    line-height: 13px;
}
.TotalValue{
    font-size: 0.7rem;
    margin-bottom: 20px;
}

.ButtonBot{
    margin-top: 10px;
    border:solid 1px #DBA200;
    border-radius: 10px;
    text-decoration: none;
    color: #F7D268;
    text-transform: uppercase;
    font-weight: bold;
    text-align: center;
    padding: 15px;
    background-color:#121317 ;
    box-sizing: border-box;
    width: 100%;
    animation: pulse-black-true 2s infinite;
    box-shadow: 0 0 0 0 rgba(247, 210, 104, 0.7);
}

</style>
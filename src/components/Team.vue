<template>
    <div class="ThirdContainer  flex">

        <div class="ContainerTeam flex Flex-direction-column">
            <div class="WeTeam">
                <h2>Nosso Time</h2>
            </div>

            <div class="TeamItem">
                <img src="../assets/ceo.png" alt="">
                <p class="NameFunction">Diego Martone - CEO</p>
                <p class="TextFunction"> 25 anos, trabalhava de porteior e foi no ano de 2017 que resolvi mudar de vida e ir pro lado empreendedorismo, no ano de 2019 foi a virada de chave onde fiz meu primeiro MILHÃO</p>
            </div>

            
                <div class="TeamItem flex align-self-end Flex-direction-column">
                    <img class="image align-self-end"  src="../assets/co-funder.png" alt="">
                    <p class="NameFunction align-self-end">Sergio Biancardi - CO-FOUNDER</p>
                    <p class="TextFunction text-aling"> 22 anos. Eu ganhava 700 reais por mês e ai que percebi que para realizar meu sonhos não dava pra trabalhar para os outros, faculdade, pós graduação ou diversos cursos. Eu só precisaia me dedicar 100% ao meu próprio negócio. No ano de 2019 fiz meu primeiro MILHÃO</p>
                </div>
           

            <div class="TeamItem">
                <img src="../assets/affiliate.png" alt="">
                <p class="NameFunction">Gabriel Ribeiro - Afiliado</p>
                <p class="TextFunction"> Olá, me Gabriel Ribeiro, tenho 21 anos de idade. Meu primeiro emprego foi trabalhando com entregas de laticínios, no período noturno em São Paulo capital onde fiquei dos 18 até os 19 anos. Eu ganhava 800 reais por mês e foi lá que percebi que para realizar meus sonhos, não dava pra trabalhar para os outros! Comecei a empreender desde então, vi que podia ganhar MUITO sem precisar ter faculdade. Eu só precisaria <strong>me dedicar</strong> 100% ao meu próprio negócio. No ano de 2020, conheci o marketing digital, onde em 7 meses já faturei mais 60 mil reais e pude entender que, eu poderia trabalhar aonde eu quisesse, com quem eu quisesse, a hora que eu quisesse e realmente poder alavancar meus ganhos! Se você tem vontade de trabalhar assim também, método FRO irá te ajudar.</p>
            </div>
        </div>
    </div>
</template>
<script>

export default {
  name: 'Team',
  msg: String
}
</script>
<style scoped>
.ThirdContainer{
    height: auto;
    padding: 3rem 20px ;
    background-color: #E8E8E8;
}

.TeamItem{
    margin-bottom: 5px;
}

.WeTeam, p{
    color: black;
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    font-size: 1.4em; 
}
.NameFunction{
    color: black;
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    font-size: 1.2em; 
    margin: 0;
}
.TextFunction{
    color: black;
    font-family: 'Raleway', sans-serif;
    font-weight: 400;
    font-size: 1rem; 
    margin-top: 5px;
    margin: 5px 0 0 0 ;
    text-align: justify;
}

.text-aling{
    text-align: justify;
}

</style>
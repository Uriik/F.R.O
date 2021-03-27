<template>
    <div class="SecondContainer">
        <div class="Benefits flex Justify-content-center">
            <h2>Vantagens</h2>
        </div>

        <div class="Learn">
            <div class="Card flex">
                <p class="Numbers">1.</p>
                <div class="ContainerCard flex">
                    <p class="TitleCards"> Aprenda praticando</p>
                    <p class="TextCards"> A teoria é importante, mas a prática MUDA TUDO. Com o F.R.O. você não fica só observando!</p>
                </div>    
            </div>

            <div class="Card flex">
                <p class="Numbers">2.</p>
                <div class="ContainerCard flex">
                    <p class="TitleCards"> Mentoria em grupo</p>
                    <p class="TextCards"> Aprenda com quem é lider em resultado no mercado. Descubra técnicas inovadoras, entenda, conceitos e processos e potencialize seus ganhos.</p>
                </div>    
            </div>

            <div class="Card flex">
                <p class="Numbers">3.</p>
                <div class="ContainerCard flex">
                    <p class="TitleCards"> Suporte personalizado</p>
                    <p class="TextCards"> Você nunca estará sozinho. Temos uma equipe preparada para te orientar no que precisar</p>
                </div>    
            </div>

            <div class="Card black flex">
                <p class="Numbers">4.</p>
                <div class="ContainerCard flex">
                    <p class="TitleCards"> Custo benefício</p>
                    <p class="TextCards"> A melhor escolha para seus resultados e para seu bolso!</p>
                </div>    
            </div>
        </div>
    </div>

</template>

<script>

export default {
  name: 'Section',
  msg: String
}
</script>

<style >

.SecondContainer{
    background-color: #F7D268;
    padding: 2rem 0;
    height: auto;
}

.Benefits{
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    font-size: 1.4em;
}
.Numbers{
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    font-size: 1.8em;
    padding: 0 15px;
    
    
}
.TitleCards{
    font-family: 'Raleway', sans-serif;
    font-weight: bold;
    font-size: 1.0em;
    margin-top: 7px;
    margin-bottom: 5px;
    margin-right: 3px;
    
}
.TextCards{
    font-family: 'Raleway', sans-serif;
    font-weight: 400;
    font-size: 1rem;
    margin: 0 auto;
    margin-right:3px;
}
.Card{
    padding:  15px;
    margin-top: 8px;
    height: auto;
    background-color:white;
    border-radius: 10px;
    box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);

}
.black{    
    background-color:#121317;

}
.Card.black .Numbers{    
    color: #F7D268;
}
.Card.black .TitleCards{
    color: #F7D268;
}
.Card.black  .TextCards{
    color:#F7D268 ;
}

.Learn{
    padding-left: 20px;
    padding-right: 20px;
}
.ContainerCard{
    flex-flow: column nowrap;
}

</style>
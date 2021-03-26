<template>
        <div class="FourContainer">

            <div class="ContainerPacket flex Flex-direction-column Align-items-center">

                <div class="TextAlReady flex Flex-direction-column Align-items-center ">
                    <p class="Already">Pronto para<br> começar?</p>
                    <p class="GetOpt">agarre essa oportunidade</p>
                </div>

                <div class="CardPacket flex Flex-direction-column Align-items-center">
                    <p class="TextPacket">pacote premium</p>
                    <p class="TextValorPacket"><span class="ValorPk">12xR$ </span>29,70</p>
                    <p class="TextBonus">Análise de métricas</p>
                    <p class="TextBonus">Método de engajamento</p>
                    <p class="TextBonus">Estética de venda</p>
                    <p class="TextBonus">Anúncios patrocinados</p>
                    <p class="TextBonus">Isca digital</p>
                    <a class="ButtonBot" href="">assine agora!</a>
                </div>

                <div class="ContactBot flex Flex-direction-column align-self-start">
                    <p class="ContactText">Contato</p>
                    <p class="ExContact">(13) 0000-00000</p>
                    <p class="ExContact">mail@exemplo.com</p>
                </div>

                <div class="FollowMe flex Flex-direction-column">
                    <p class="TextFollow">Siga-me</p>
                    <div class="Midias flex">
                        <a class="Facebook" href="#"><i class="fab fa-facebook-square"></i></a>
                        <a class="Instagram" href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
            </div>

        </div>
</template>

<script>

export default {
  name: 'PacketPremium',
  msg: String
}
</script>
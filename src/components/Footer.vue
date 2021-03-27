<template>
<footer>
<div class="ContactBot flex Flex-direction-column align-self-start">
                    <p class="ContactText">Contato</p>
                    <a href="tel:11958497537" class="ExContact">(11) 95849-7537</a>
                    <a href="mailto:ribeirogabriel455@gmail.com" class="ExContact">ribeirogabriel455@gmail.com</a>
                </div>

                <div class="FollowMe flex Flex-direction-column">
                    <p class="TextFollow">Siga-me</p>
                    <div class="Midias flex">
                        <a class="telegram"  href="https://t.me/idk_gabriel"><i class="fab fa-telegram"></i></a>
                        <a class="Instagram" href="https://www.instagram.com/idk_gabriel/"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>

      <div class="FooterBot flex Justify-content-center Align-items-center">
        <small class="Ft">&copy; Copyright 2058, Example Corporation</small>
      </div>
</footer>

</template>

<script>

export default {
  name: 'Footer',
  msg: String
}
</script>
<style >
footer,.FooterBot{
    padding: 3rem 20px 15px 20px;
    background-color: #1b1c20;
}

small{
    color: #F7D268;

    font-weight: 400;
    font-size: 0.8em;
}



.ContactBot{
    width: 100%;
}
.ContactText{
    color: #F7D268;
    font-weight: 600;
    font-size: 1rem;
    margin: 5px 0 5px 0;
    padding: 0;
}
.ExContact{
    color: #F7D268;

    font-weight: 300;
    font-size: 1rem;
    margin: 5px 0 5px 0;
    padding: 0; 
}
.FollowMe{
    
    width: 100%;
}
.TextFollow{
    color: #F7D268;

    font-weight: 600;
    font-size: 1.0em;
    margin: 0;
    padding: 0;
}


.Instagram{
    width: 30px;
    height: 30px;
    margin-left: 25px;  
}

.Midias{
    padding-top: 10px;

}

.fa-telegram{
    color:#F7D268;
    font-size: 2.7em;
}
.fa-instagram{
    color:#F7D268;
    font-size: 2.7em;
}
.fabInst{
    color:#F7D268;
    font-size: 3.0em;
}

</style>
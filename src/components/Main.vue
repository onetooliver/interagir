<script>
  import CardMain from './icons/CardMain.vue' 
</script>
<template>
  <main>
    <section>
      <div class="column-left">
        <svg xmlns="http://www.w3.org/2000/svg" width="1220" height="617" viewBox="0 0 1220 617" fill="none">
        <path d="M0 0H1111C1171.2 0 1220 48.801 1220 109V508C1220 568.199 1171.2 617 1111 617H0V0Z" fill="#EFF8ED"/>
        </svg>
      </div>
      <div class="container d-flex align-items-center">
        <div class="col-6 text-main  ">
          <h1>Colégio Interagir</h1>
          <h3>Construindo o futuro do seu filho bem pertinho de você</h3>
          <a href="https://calendly.com/neto-nelsonfsa/30min" class="btn btn-outline-success mt-5" target="_blank"  > Agendar visita</a>
        </div>
        <div class="col-5">
          <img class="img-banner" src="../../public/assets/bannerMain.png"/>
        </div>
      </div> 
    </section> 
    <section>
      <CardMain/>
    </section>
  </main>
</template>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap');
  
  .column-left {
    position: relative;
    z-index:-1;
  }
  
  .container{
    top:0;
    margin-top:-35em;
    z-index:5;
    
  }
  .text-main{
    
    font-family: 'Montserrat', sans-serif;
    margin-top:-12em;
  }
  .text-main h1{
    font-size:5em;
  }
  .text-main h3{
    font-size:1.5em;
  }
  .text-main a{
    font-size:1.5em;
  }
  
  .img-banner{
    width:50em;
    height:50em;
    margin-top:-10em;
  }
</style>

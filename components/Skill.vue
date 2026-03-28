<script setup>

</script>

<template>
    <h1 class="box2">My Skill</h1>
    <div class="box1">

<h2 class="box3">Multimedia & Boardcasting</h2>
    <div class="skill1">
        <p>kameramen Studio & Outdoor</p>
        <div class="bar">
         <div class="isi kameramen">80%</div>   
        </div>

        <p>Operasional Produksi Studio TV</p>
        <div class="bar">
            <div class=" isi produksi">90%</div>
        </div>
        <p>vMix</p>
        <div class="bar">
            <div class="isi vmix">80%</div>
        </div>
        <p>OBS Studio</p>
        <div class="bar">
            <div class="isi studio">80%</div>
        </div>
    </div> <hr>
    <h2>Keahlian Web & IT(Dasar)</h2>
    <div class="skill2">
        <p>HTML:5</p>
        <div class="bar">
            <div class="isi html">70%</div>
        </div>
        <p>CSS</p>
        <div class="bar">
            <div class="isi css">60%</div>
        </div>
        <p>JavaScript</p>
        <div class="bar">
            <div class="isi javascript">60%</div>
        </div>
        <p>Visual Studio Code</p>
        <div class="bar">
            <div class="isi visual">80%</div>
        </div>
    </div>
    </div>
</template>

<style scoped>
.box1{
    display: flex;

}
.box2{
    text-align: center;
}

.skill1 {
    width: 400px;
  
  }
.bar {
    background: #464141;
    border-radius: 20px;
    margin-bottom: 15px;
  }
  .isi {
    height: 25px;
    line-height: 25px;
    color: rgb(240, 233, 233);
    text-align: right;
    padding-right: 10px;
    border-radius: 20px;
  }
  .kameramen {
    width: 80%;
     background: #e34c26;
    color: black;
  }

  .produksi {
    width: 90%;
     background: #e34c26;
    color: black;
  }
  
  .vmix {
    width: 80%;
     background: #e34c26;
    color: black;
  }
.studio{
    width: 80%;
    background: #e34c26;
    color: black;
}
.skill2 {
    width: 400px;
  }

.html{
    width: 70%;
    background: #e34c26;
    color: black;
}
.css{
    width: 60%;
    background: #e34c26;
    color: black;
}
.javascript{
    width: 60%;
    background: #e34c26;
    color: black;
}
.visual{
    width: 80%;
    background: #e34c26;
    color: black;
}
</style>
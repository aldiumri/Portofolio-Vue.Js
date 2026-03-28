<script setup>
import { ref } from 'vue';
import Halaman from './components/Halaman.vue';
import About from './components/About.vue';
import Skill from './components/Skill.vue';
import Work from './components/Work.vue';

 

 const currentPage = ref('halaman')

 const pages = {
    halaman: Halaman,
    about: About,
    skill: Skill,
    work: Work
 }
</script>

<template>
    <div class="container">
        <button @click="currentPage = 'halaman'" class="hal">Halaman</button>
        <button @click="currentPage = 'about'" class="ab">About</button>
        <button @click="currentPage = 'skill'" class="skill">Skill</button>
        <button @click="currentPage = 'work'" class="work">Work</button>
        
    </div>
    <component :is=" pages[currentPage]"/>
</template>

<style scoped>
.container{
    display: flex;      
    justify-content: space-between;
    border-radius: 25px;
    color: aqua;
    padding: 50px;
}
.hal{
    color: black;
    background-color: aqua;
}
.ab{
    color: black;
    background-color: aqua;
}
.skill{
    color: black;
    background-color: aqua;
}
.work{
    color: black;
    background-color: aqua;
}
</style>
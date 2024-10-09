<script setup>
import Card from './Card.vue';

import akira from '../assets/akira.jpg';
import hxh from '../assets/hxh.jpg';
import evangelion from '../assets/evangelion.jpg';
import cowboy from '../assets/cowboy.jpg'

</script>

<template> 
<h2>Mis animes favoritos</h2>

<div class="row">

<Card :img="akira"/> 
<Card :img="hxh"/>
<Card :img="evangelion"/>
<Card :img="cowboy"/>
    
</div>

</template>

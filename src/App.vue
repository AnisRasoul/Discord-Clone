<script>
import navbar from './components/navbar.vue';
import discord from './components/discord.vue';
import disfoot from './components/disfoot.vue';
import intro from './components/intro.vue';
export default {
  components: {
    navbar,
    discord,
    disfoot,
    intro,
  }
}
</script>

<template>

 <navbar/>
<intro/>
<discord/>
 <disfoot/>
 
</template>

<style scoped>

</style>

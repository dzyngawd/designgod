<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I am a product designer based in Lagos, Nigeria.
    <br>
    I strive to create visually compelling interfaces that are intuitive and easy to navigate on mobile and desktop screens. 
    <br> This site is still under construction 🚧, but you can view the projects I've worked on here:
      <a href="https://designgawd.notion.site/My-name-is-Tomiwa-Ajiboye-299b5aae25e34bc6bcc75c9ffe4a5648" target="_blank" rel="noopener">Portfolio</a>
    </p>
    
    <h3>Connect with me</h3>
    <ul>
      <li><a href="https://twitter.com/D_zyn__gawd" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://www.instagram.com/tomiwa__/" target="_blank" rel="noopener">Instagram</a></li>
      <li><a href="https://medium.com/@designgod" target="_blank" rel="noopener">Medium</a></li>
      <li><a href="https://www.linkedin.com/in/abdulraheem-ajiboye-76a9a1140/" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="https://open.spotify.com/user/1qjnho469cr3mtam3fjrh9uoe" target="_blank" rel="noopener">Spotify</a></li>
    </ul>  


  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  padding-top: 20px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  padding-top: 12px;
}
a {
  color: #d18693;
}
</style>

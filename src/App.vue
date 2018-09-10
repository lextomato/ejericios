<template lang="pug">
  #app
    section(id="panel-H" class="panel-H")
      header(id="header" class="header contenedor")
        img(src="../images/movi.jpg" class="logo-img")
        input(type="text" name="buscardor" placeholder="Busca tu peli, actor, actriz o director favorito" class="buscador")
        div(class="user")
          h2 {{ msg }}
          img(src="../images/user.png" width="50px" class="user-img")
          a(href="#" class="btnUser") ▼
    div(class="contenedor")
      section(id="panel-V" class="panel-V")
        li
          img(src="./assets/home.png")
          a Home 
        li
          img(src="./assets/trend.png")
          a Trending
        li
          img(src="./assets/fav.png")
          a Más likes
        li
          img(src="./assets/settings.png")
          a Ajustes 
      section(id="contenido" class="contenido")
        li
          h2 Ahora en el cine
          div(class="cajaCaja")
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
        li
          h2 Aclamadas por la critica
          div(class="cajaCaja")
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
        li
          h2 No te debes perder
          div(class="cajaCaja")
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula
            div(class="cajaImg")
              img(src="./assets/peli.jpg")
              div(class="encima")
                h3 Monsters INK
                p Monsters se trata de una pelicula para niños y jovenes muy divertida, todos los amigos compartiran muchas aventuras y desafios durante toda la pelicula        
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Lextomato'
    }
  }
}
</script>

<style lang="scss">
  @import './scss/main.scss'
</style>

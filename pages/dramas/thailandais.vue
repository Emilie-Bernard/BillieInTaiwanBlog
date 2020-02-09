<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas Thailandais"
      subtitle="Tout est mignon"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
      <template v-slot:default> 
      <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/dramas'><button class="button " style="font-size:30px;">Tous</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/chinois'><button class="button is-danger" style="font-size:30px;">Chine</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/coreens'><button class="button is-primary" style="font-size:30px;">Corée</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/taiwanais'><button class="button is-warning" style="font-size:30px;">Taiwan</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/japonais'><button class="button is-japon" style="font-size:30px;">Japon</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/thailandais'><button class="button is-thailande" style="font-size:30px;">Thailande</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/categories/dramas'><button class="button is-dark" style="font-size:30px;">Articles</button></router-link></div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                La liste des dramas thailandais que j'ai eu l'occasion de visionner
              </p>
              <p class="subtitle">
                Petit à petit nous sombrons dans le monde infini des dramas 
              </p>
              <div class="content">
              <p>
              ⭐ = drama que j'ai adoré
              <br>
              😍 = drama que j'ai aimé
              <br>
              😄 = drama qui m'ont plus
              </p>
                <p>
                  <strong> 0-9 </strong>
                  <br>
                  <span style="color:#56dcd8">2 Moons The Series ⭐</span>
                </p>
                <p>
                  <strong> A - B - C - D - E </strong>
                  <br> 
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#56dcd8">Full House ⭐</span>
               </p>
               <p>
                  <strong> G - H - I - J </strong>
                  <br>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                  <span style="color:#56dcd8">Kiss Me ⭐</span>
                </p>
               <p>
                  <strong> L - M- N - O - P - Q - R - S - T - U - V - W - X - Y - Z </strong>
                  <br>
               </p>
              </div>
            </article>
          </div>
        </div>
      </template>
    </main-section>
  </div>
</template>

<script>
export default {
  name: 'DramasThailandais',
  head() {
    return {
      title: `Dramas Thailandais | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

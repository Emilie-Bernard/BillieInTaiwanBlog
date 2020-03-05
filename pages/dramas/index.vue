<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas"
      subtitle="Une fois commencé on ne s'arrête plus"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
      <template v-slot:default>
          <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/dramas/allseen'><button class="button is-danger" style="font-size:30px;">La liste des dramas vu sans article</button></router-link></div>
         </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Tous les articles écrit sur les dramas que j'ai visionnés
              </p>
              <p class="subtitle">
                Petit à petit les articles s'écrivent
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
                  <strong> 0-9 - R </strong>
               </p>
               <p>
                  <strong> S </strong>
                  <b><a href="https://www.billieintaiwan.com/someday-or-one-day"><span style="color:#f0ad4e">Someday or One Day ⭐⭐</span></a></b><br>
               </p>
               <p>
                  <strong> T </strong>
                  <b><a href="https://www.billieintaiwan.com/the-ghost-bride"><span style="color:#f0ad4e">The Ghost Bride 😍</span></a></b><br>
               </p>
               <p>
                  <strong> V - Z </strong>
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
  name: 'Dramas',
  head() {
    return {
      title: `Dramas | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

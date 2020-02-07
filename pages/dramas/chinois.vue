<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas Chinois"
      subtitle="Doucement mais surement"
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
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                La liste des dramas chinois que j'ai eu l'occasion de visionner
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
                  
                </p>
                <p>
                  <strong> A </strong>
                  <br> 
                   <span style="color:#d9534f">A Love So Beautiful ⭐ </span>
                </p>
                <p>
                  <strong> B </strong>
                  <br>
                  
                <p>
                  <strong> C </strong>
                  <br>
                  <span style="color:#d9534f">Cruel Romance ⭐⭐</span>
                  </p>
                <p>
                  <strong> D </strong>
                  <br>
                  <span style="color:#d9534f">Dear Prince ⭐</span>
                <p>
                  <strong> E - F - G - H - I - J - K </strong>
                  <br>
                </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#d9534f">Lady & Liar 😍</span><br>
                  <span style="color:#d9534f">Let's Go Watch Meteor Shower 😄</span> <br>
                  <span style="color:#d9534f">Let's Watch The Meteor Shower Together Again 😄</span><br>
                  <span style="color:#d9534f">Love at Second Sight</span><br>
                  <span style="color:#d9534f">Love O2O 😄</span><br>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#d9534f">Meteor Garden ⭐</span><br>
                  <span style="color:#d9534f">My Amazing Boyfriend 😄</span><br>
                  <span style="color:#d9534f">My Little Princess 😄</span> 
               </p>
               <p>
                  <strong> N </strong>
                  <br>
               <p>
                  <strong> O </strong>
                  <br>
                  <span style="color:#f0ad4e">Office Girls 😄</span><br>
                  <span style="color:#f0ad4e">Once More Heartbeat 😄</span>
               </p>
               <p>
                  <strong> P </strong>
                  <br>
                   <span style="color:#d9534f">Prince of Lan Ling 😄</span> 
               </p>
               <p>
                  <strong> Q - R </strong>
                  <br>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#d9534f">Scarlet Heart ⭐</span> - <span style="color:#d9534f">Scarlet Heart 2 😍</span>
               </p>
               <p>
                  <strong> T - U - V - W - X - Y - Z</strong>
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
  name: 'DramaChinois',
  head() {
    return {
      title: `Drama Chinois | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

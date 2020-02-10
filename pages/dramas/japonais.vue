<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas Japonais"
      subtitle="Comique > Romantisme"
      image="uploads/drama-hero.jpg"
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
                La liste des dramas japonais que j'ai eu l'occasion de visionner
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
                  <span style="color:#EBC0DE">35 sai no Koukousei ⭐</span>
                  <br>
                  <span style="color:#EBC0DE">100 Scene No Koi 😄</span>
                </p>
                <p>
                  <strong> A </strong>
                  <br> 
                  <span style="color:#EBC0DE">Abarenbo Mama 😍</span><br>
                  <span style="color:#EBC0DE">Again!!</span><br>
                  <span style="color:#EBC0DE">Asuko March</span><br>
                  <span style="color:#EBC0DE">Atashinchi no Danshi 😍</span><br>
                  <span style="color:#EBC0DE">Attention Please 😄</span> 
                </p>
                <p>
                  <strong> B - C - D - E </strong>
                  <br> 
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#EBC0DE">First Kiss</span>
               </p>
               <p>
                  <strong> G </strong>
                  <br>
                  <span style="color:#EBC0DE">Gokusen 😍</span><br>
                  <span style="color:#EBC0DE">Gokusen 2 😄</span><br>
                  <span style="color:#EBC0DE">GTO  😍</span>
               </p>
                <p>
                  <strong> H </strong>
                  <br>
                  <span style="color:#EBC0DE">Hana Nochi Hare  😄</span><br>
                  <span style="color:#EBC0DE">Hana Yori Dango ⭐⭐</span><br>
                  <span style="color:#EBC0DE">Hana Yori Dango 2 ⭐</span><br>
                  <span style="color:#EBC0DE">Hanazakari no Kimitachi e ⭐</span>
               </p>
                <p>
                  <strong> I </strong>
                  <br>
                  <span style="color:#EBC0DE">Ikemen desu ne</span><br>
                  <span style="color:#EBC0DE">Itazura na Kiss ~ Love in TOKYO</span><br>
                  <span style="color:#EBC0DE">Hana Yori Dango 2 ⭐</span><br>
                  <span style="color:#EBC0DE">Hanazakari no Kimitachi e ⭐</span>
               </p>
               <p>
                  <strong> J </strong>
                  <br>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                  <span style="color:#EBC0DE">Kimi wa Pet </span><br>
                  <span style="color:#EBC0DE">Koishite Akuma </span>
                </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#EBC0DE">LIAR GAME</span>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#EBC0DE">Mei-chan no Shitsuji 😄</span><br>
                  <span style="color:#EBC0DE">My Boss My Hero 😍</span>
               </p>
               <p>
                  <strong> N </strong>
                  <br>
                  <span style="color:#EBC0DE">Nihonjin no Shiranai Nihongo 😄</span><br>
                  <span style="color:#EBC0DE">Nodame Cantabile 😄</span>
               </p>
               <p>
                  <strong> O </strong>
                  <br>
               </p>
               <p>
                  <strong> P </strong>
                  <br>
                   <span style="color:#EBC0DE">Parfait Tic !</span><br>
                  <span style="color:#EBC0DE">Proposal Daisakusen 😍</span>
               </p>
               <p>
                  <strong> Q </strong>
                  <br>
               </p>
               <p>
                  <strong> R </strong>
                  <br>
                  <span style="color:#EBC0DE">Rich Man, Poor Woman 😍</span>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#EBC0DE">Switch Girl!! 😍</span>
               </p>
               <p>
                  <strong> T </strong>
                  <br>
                  <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi ⭐</span> <br>
                  <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi 2 ⭐</span>
               </p>
               <p>
                  <strong> U - V - W - X </strong>
                  <br>
               </p>
               <p>
                  <strong> Y </strong>
                  <br>
                  <span style="color:#EBC0DE">Yamato Nadeshiko Shichi Henge</span><br>
                  <span style="color:#EBC0DE">Yankee-kun to Megane-chan 😄</span>
               </p>
               <p>
                  <strong> Z </strong>
                  <br>
                  <span style="color:#EBC0DE">Zettai Kareshi</span>
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
  name: 'DramasJaponais',
  head() {
    return {
      title: `Dramas Japonais | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

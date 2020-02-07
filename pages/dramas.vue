<template>
  <div id="dramas-page" class="page-wrapper dramas-page content-page">
    <site-hero
      title="Dramas"
      subtitle="Une fois commencé on ne s'arrête plus"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
          <div class="tile is-ancestor">
            <div class="tile is-parent is"><button class="button is-danger" style="font-size:30px;">Chine</button></div>
            <div class="tile is-parent is"><button class="button is-primary" style="font-size:30px;">Corée</button></div>
            <div class="tile is-parent is"><button class="button is-warning" style="font-size:30px;">Taiwan</button></div>
            <div class="tile is-parent is"><button class="button is-japon" style="font-size:30px;">Japon</button></div>
            <div class="tile is-parent is"><button class="button is-thailande" style="font-size:30px;">Thailande</button></div>
           
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                La liste de mes Dramas visualisés
              </p>
              <p class="subtitle">
                L'addiction monte vite, le nombre aussi !
              </p>
              <div class="content">
                <p>
                  <strong> 0-9 </strong>
                  <span style="color:#56dcd8">2 Moons The Series ⭐</span> - <span style="color:#117BAA">18 vs. 29</span> - <span style="color:#EBC0DE">35 sai no Koukousei ⭐</span> - <span style="color:#117BAA"> 49 Days 😍 </span> - <span style="color:#EBC0DE">100 Scene No Koi 😄</span>
                  <strong> A </strong>
                  <span style="color:#EBC0DE">Abarenbo Mama 😍</span> - <span style="color:#117BAA">Aftermath</span> - <span style="color:#EBC0DE">Again!!</span> - <span style="color:#117BAA">A Gentleman's Dignity ⭐</span> - <span style="color:#117BAA">A Girl Who Sees Smells ⭐</span> - <span style="color:#117BAA">A Korean Odyssey ⭐ </span>- <span style="color:#f0ad4e">Alice in Wonder City 😄</span> - <span style="color:#d9534f">A Love So Beautiful ⭐ </span>- <span style="color:#117BAA">A Love To Kill </span> - <span style="color:#117BAA">Angry Mom ⭐</span> - <span style="color:#117BAA">Another Oh Hae Young ⭐ </span>- <span style="color:#117BAA">Another Parting 😍</span> - <span style="color:#f0ad4e">Apple In Your Eye</span> - <span style="color:#117BAA">Arang and the Magistrate 😍</span> - <span style="color:#117BAA">Arthdal Chronicles 😍</span> - <span style="color:#EBC0DE">Asuko March</span> - <span style="color:#EBC0DE">Atashinchi no Danshi 😍</span> - <span style="color:#f0ad4e">Attention, Love! ⭐</span> - <span style="color:#EBC0DE">Attention Please 😄</span> -  <span style="color:#f0ad4e">Autumn's Concerto ⭐</span> - <span style="color:#117BAA">A Witch's Love 😍</span>
                  <strong> B </strong>
                  <span style="color:#f0ad4e">Back to 1989 ⭐</span> - <span style="color:#f0ad4e">Back to Home ⭐</span> - <span style="color:#117BAA">Bad Family ⭐</span> - <span style="color:#117BAA">Bad Guys 😍</span> - <span style="color:#117BAA">Bad Love 😍</span> - <span style="color:#117BAA">Beautiful Gong Shim 😍</span> - <span style="color:#117BAA">Beautiful Mind ⭐</span> - <span style="color:#f0ad4e">Before We Get Married </span>- <span style="color:#f0ad4e">Behind Your Smile</span> - <span style="color:#117BAA">Bel Ami</span> - <span style="color:#117BAA">Be Positive 😄</span> - <span style="color:#f0ad4e">Better Man ⭐</span> -   <span style="color:#117BAA">Birth of a Beauty</span> - <span style="color:#117BAA">Boys Before Flowers</span> - <span style="color:#f0ad4e">Boysitter 😄</span> - <span style="color:#117BAA">Bridal Mask 😍</span> - <span style="color:#117BAA">Bride of the Century ⭐</span> - <span style="color:#f0ad4e">Bromance ⭐</span>
                  <strong> C </strong>
                  <span style="color:#117BAA">Can You Hear My Heart? 😄</span> - <span style="color:#117BAA">Cheese in the Trap </span> - <span style="color:#117BAA">Cheongdamdong Alice 😍</span> - <span style="color:#117BAA">Choco Bank</span> - <span style="color:#117BAA">Cinderella and the Four Knights ⭐</span> - <span style="color:#117BAA">City Hunter ⭐</span> -   <span style="color:#d9534f">Cruel Romance ⭐⭐</span> - <span style="color:#117BAA">Cunning Single Lady 😍</span>
                  <strong> D </strong>
                  <span style="color:#d9534f">Dear Prince ⭐</span> - <span style="color:#117BAA">Descendants of the Sun 😍</span> - <span style="color:#f0ad4e">Devil Beside You ⭐</span> - <span style="color:#117BAA">Discovery of Love 😍</span> - <span style="color:#f0ad4e">Down With Love 😍</span> - <span style="color:#117BAA">Dr. Frost 😄</span> -  <span style="color:#117BAA">Dramaworld ⭐</span>- <span style="color:#117BAA">Dream High ⭐</span> - <span style="color:#117BAA">Dream High 2 😍 </span>- <span style="color:#117BAA">Dream Knight 😍</span> - <span style="color:#f0ad4e">Déjà Vu 😍</span>
                  <strong> E </strong>
                </p>
              </div>
            </article>
          </di>
        </div>
      </template>
     <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Derniers posts
        </h3>
        <!-- Latest Posts -->
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
import { setPageData } from '../helper'
export default {
  data() {
    return {
      allCats: []
    }
  },
  fetch({ store, params }) {
    setPageData(store, { resource: 'category', slug: params.single })
  },
  async created() {
    this.allCats = await this.$cms.category.getAll()
  }
}
</script>

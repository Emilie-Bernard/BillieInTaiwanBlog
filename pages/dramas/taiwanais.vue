<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas Taiwanais"
      subtitle="Pastel et simplicité"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
      <template v-slot:default> 
      <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/dramas'><button class="button " style="font-size:30px;">Tous</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/chinois'><button class="button is-danger" style="font-size:30px;">Chine</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/coreens'><button class="button is-primary" style="font-size:30px;">Corée</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/japonais'><button class="button is-japon" style="font-size:30px;">Japon</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/thailandais'><button class="button is-thailande" style="font-size:30px;">Thailande</button></router-link></div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                La liste des dramas taiwanais que j'ai eu l'occasion de visionner
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
                   <span style="color:#f0ad4e">Alice in Wonder City 😄</span> <br>
                   <span style="color:#f0ad4e">Apple In Your Eye</span><br>
                   <span style="color:#f0ad4e">Attention, Love! ⭐</span><br>
                   <span style="color:#f0ad4e">Autumn's Concerto ⭐</span>
                </p>
                <p>
                  <strong> B </strong>
                  <br>
                  <span style="color:#f0ad4e">Back to 1989 ⭐</span><br>
                  <span style="color:#f0ad4e">Back to Home ⭐</span><br>
                  <span style="color:#f0ad4e">Before We Get Married </span><br>
                  <span style="color:#f0ad4e">Behind Your Smile</span><br>
                  <span style="color:#f0ad4e">Better Man ⭐</span><br>
                  <span style="color:#f0ad4e">Boysitter 😄</span><br>
                  <span style="color:#f0ad4e">Bromance ⭐</span>
                <p>
                  <strong> C </strong>
                  <br>
                  </p>
                <p>
                  <strong> D </strong>
                  <br>
                  <span style="color:#f0ad4e">Devil Beside You ⭐</span><br>
                  <span style="color:#f0ad4e">Down With Love 😍</span><br>
                  <span style="color:#f0ad4e">Déjà Vu 😍</span>
                <p>
                  <strong> E </strong>
                  <br>
                  <span style="color:#f0ad4e">Easy Fortune Happy Life 😄</span> 
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#f0ad4e">Fabulous Boys</span><br>
                  <span style="color:#f0ad4e">Fall in Love With Me ⭐</span><br>
                  <span style="color:#f0ad4e">Fated To Love You 😍</span><br>
                  <span style="color:#f0ad4e">Five Missions ⭐</span>
               </p>
               <p>
                  <strong> G </strong>
                  <br>
                  <span style="color:#f0ad4e">GTO TAIWAN 😍</span>
               </p>
               <p>
                  <strong> H </strong>
                  <br>
                  <span style="color:#f0ad4e">Hello Again! 😍</span><br>
                  <span style="color:#f0ad4e">Hi My Sweetheart ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 2: Cross The Line 😍</span><br>
                  <span style="color:#f0ad4e">HIStory 2: Right or Wrong ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 3: Make Our Days Count ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 3: Trapped ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: My Hero ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: Obsessed ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: Stay Away From Me ⭐</span><br>
                  <span style="color:#f0ad4e">Home Sweet Home 😍</span>
               </p>
               <p>
                  <strong> I </strong>
                  <br>
                  <span style="color:#f0ad4e">I Am Sorry, I Love You 😍</span><br>
                  <span style="color:#f0ad4e">Inborn Pair ⭐</span><br>
                  <span style="color:#f0ad4e">In Time With You ⭐</span><br>
                  <span style="color:#f0ad4e">Iron Ladies 😍</span><br>
                  <span style="color:#f0ad4e">It Started With a Kiss</span>
               </p>
               <p>
                  <strong> J </strong>
                  <br>
                  <span style="color:#f0ad4e">Jin Da Hua De Hua Li Mao Xian 😄</span><br>
                  <span style="color:#f0ad4e">JOJO's World 😄</span><br>
                  <span style="color:#f0ad4e">Just You ⭐</span>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#f0ad4e">Le Jun Kai 😄</span><br>
                  <span style="color:#f0ad4e">Leo 😄</span><br>
                  <span style="color:#f0ad4e">Lion Pride 😍</span><br>
                  <span style="color:#f0ad4e">Love, Now 😄</span><br>
                  <span style="color:#f0ad4e">Love @ Seventeen 😄</span><br>
                  <span style="color:#f0ad4e">Love Around 😍</span><br>
                  <span style="color:#f0ad4e">Love Buffet</span><br>
                  <span style="color:#f0ad4e">Love By Design 😍</span><br>
                  <span style="color:#f0ad4e">Love Cheque Charge</span><br>
                  <span style="color:#f0ad4e">Love Keeps Going</span><br>
                  <span style="color:#f0ad4e">Love of Sandstorm</span><br>
                  <span style="color:#f0ad4e">Love Or Bread</span><br>
                  <span style="color:#f0ad4e">Love You ⭐</span>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#f0ad4e">Marry Me Or Not? ⭐</span><br>
                  <span style="color:#f0ad4e">Material Queen 😄</span><br>
                  <span style="color:#f0ad4e">Memory Love 😍</span><br>
                  <span style="color:#f0ad4e">Meteor Garden ⭐</span><br>
                  <span style="color:#f0ad4e">Miss In Kiss ⭐</span><br>
                  <span style="color:#f0ad4e">Miss No Good 😍</span><br>
                  <span style="color:#f0ad4e">Miss Rose 😄</span><br>
                  <span style="color:#f0ad4e">Momo Love 😄</span><br>
                  <span style="color:#f0ad4e">Moon River 😄</span><br>
                  <span style="color:#f0ad4e">Murphy's Law of Love 😍</span>
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
                   <span style="color:#f0ad4e">Pleasantly Surprised 😍</span><br>
                   <span style="color:#f0ad4e">Prince Of Wolf ⭐</span><br>
                   <span style="color:#f0ad4e">Prince Turns to Frog</span><br>
                   <span style="color:#f0ad4e">Prince William</span>
               </p>
               <p>
                  <strong> Q </strong>
                  <br>
               </p>
               <p>
                  <strong> R </strong>
                  <br>
                  <span style="color:#f0ad4e">Refresh Man 😄</span>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#f0ad4e">Say Again Yes I Do 😍</span><br>
                  <span style="color:#f0ad4e">See You in Time </span><br>
                  <span style="color:#f0ad4e">Single Ladies Senior 😍</span><br>
                  <span style="color:#f0ad4e">Skip Beat !</span><br>
                  <span style="color:#f0ad4e">Smiling Pasta 😍</span><br>
                  <b><a href="https://www.billieintaiwan.com/someday-or-one-day"><span style="color:#f0ad4e">Someday or One Day ⭐⭐</span></a></b><br>
                  <span style="color:#f0ad4e">Summer's Desire ⭐</span><br>
                  <span style="color:#f0ad4e">Sunshine Angel</span><br>
                  <span style="color:#f0ad4e">Swimming Battle 😄</span>
               </p>
               <p>
                  <strong> T </strong>
                  <br>
                  <span style="color:#f0ad4e">The Crossing Hero 😍</span> <br>
                  <b><a href="https://www.billieintaiwan.com/the-ghost-bride"><span style="color:#f0ad4e">The Ghost Bride 😍</span></a></b><br>
                  <span style="color:#f0ad4e">The Magicians of Love 😄</span><br>
                  <span style="color:#f0ad4e">The Masked Lover ⭐</span><br>
                  <span style="color:#f0ad4e">The Perfect Match 😄</span><br>
                  <span style="color:#f0ad4e">The Pursuit of Happiness 😍</span><br>
                  <span style="color:#f0ad4e">The Way We Were 😍</span><br>
                  <span style="color:#f0ad4e">They Kiss Again ⭐</span><br>
                  <span style="color:#f0ad4e">ToGetHer 😄</span><br>
                  <span style="color:#f0ad4e">Tokyo Juliet 😄</span><br>
                  <span style="color:#f0ad4e">Triad Princess ⭐</span>
                  </p>
               <p>
                  <strong> V </strong>
                  <br>
                  <span style="color:#f0ad4e">V-Focus ⭐</span>
               </p>
               <p>
                  <strong> W </strong>
                  <br>
                  <span style="color:#f0ad4e">When I See You Again 😍</span><br>
                  <span style="color:#f0ad4e">Who's The One 😄</span> <br>
                  <span style="color:#f0ad4e">Why Why Love</span>
               </p>
               <p>
                  <strong> X </strong>
                  <br>
                  <span style="color:#f0ad4e">Xiao Hua De Tie Shen Gao Shou</span>
               </p>
               <p>
                  <strong> Y </strong>
                  <br>
                  <span style="color:#f0ad4e">Ying Ye 3 + 1 😍</span><br>
                  <span style="color:#f0ad4e">Yong-Jiu Grocery Store 😄</span>
                  </p>
               <p>
                  <strong> Z </strong>
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
  name: 'DramasTaiwanais',
  head() {
    return {
      title: `Dramas Taiwanais | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

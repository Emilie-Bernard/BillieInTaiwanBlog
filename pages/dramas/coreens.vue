<template>
  <div id="dramas-page" class="page-wrapper dramas-page">
    <site-hero
      title="Dramas Coréens"
      subtitle="Pour satisfaire tous vos besoins"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
      <template v-slot:default>
          <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/dramas'><button class="button " style="font-size:30px;">Tous</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/chinois'><button class="button is-danger" style="font-size:30px;">Chine</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/taiwanais'><button class="button is-warning" style="font-size:30px;">Taiwan</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/japonais'><button class="button is-japon" style="font-size:30px;">Japon</button></router-link></div>
            <div class="tile is-parent is"><router-link to='/dramas/thailandais'><button class="button is-thailande" style="font-size:30px;">Thailande</button></router-link></div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                La liste des dramas coréens que j'ai eu l'occasion de visionner
              </p>
              <p class="subtitle">
                L'addiction monte vite, le nombre aussi !
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
                  <span style="color:#117BAA">18 vs. 29</span><br>
                   <span style="color:#117BAA"> 49 Days 😍 </span> 
                </p>
                <p>
                  <strong> A </strong>
                  <br> 
                   <span style="color:#117BAA">Aftermath</span> <br>
                   <span style="color:#117BAA">A Gentleman's Dignity ⭐</span> <br>
                   <span style="color:#117BAA">A Girl Who Sees Smells ⭐</span> <br>
                   <span style="color:#117BAA">A Korean Odyssey ⭐ </span><br>
                   <span style="color:#117BAA">A Love To Kill </span> <br>
                   <span style="color:#117BAA">Angry Mom ⭐</span> <br>
                   <span style="color:#117BAA">Another Oh Hae Young ⭐ </span><br>
                   <span style="color:#117BAA">Another Parting 😍</span> <br>
                   <span style="color:#117BAA">Arang and the Magistrate 😍</span> <br>
                   <span style="color:#117BAA">Arthdal Chronicles 😍</span> <br>
                   <span style="color:#117BAA">A Witch's Love 😍</span><br>
                </p>
                <p>
                  <strong> B </strong>
                  <br>
                   <span style="color:#117BAA">Bad Guys 😍</span> <br>
                   <span style="color:#117BAA">Bad Love 😍</span> <br>
                   <span style="color:#117BAA">Beautiful Gong Shim 😍</span> <br>
                   <span style="color:#117BAA">Beautiful Mind ⭐</span> <br>
                   <span style="color:#117BAA">Bel Ami</span> <br>
                   <span style="color:#117BAA">Be Positive 😄</span> <br>
                   <span style="color:#117BAA">Birth of a Beauty</span> <br>
                   <span style="color:#117BAA">Boys Before Flowers</span> <br>
                   <span style="color:#117BAA">Bridal Mask 😍</span> <br>
                   <span style="color:#117BAA">Bride of the Century ⭐</span>
                <p>
                  <strong> C </strong>
                  <br>
                  <span style="color:#117BAA">Can You Hear My Heart? 😄</span><br>
                  <span style="color:#117BAA">Cheese in the Trap </span> <br>
                  <span style="color:#117BAA">Cheongdamdong Alice 😍</span><br>
                  <span style="color:#117BAA">Choco Bank</span> <br>
                  <span style="color:#117BAA">Cinderella and the Four Knights ⭐</span><br>
                  <span style="color:#117BAA">City Hunter ⭐</span> <br>
                  <span style="color:#117BAA">Cunning Single Lady 😍</span>
                </p>
                <p>
                  <strong> D </strong>
                  <br>
                  <span style="color:#117BAA">Descendants of the Sun 😍</span> <br>
                  <span style="color:#117BAA">Discovery of Love 😍</span> <br>
                  <span style="color:#117BAA">Dr. Frost 😄</span> <br>
                  <span style="color:#117BAA">Dramaworld ⭐</span><br>
                  <span style="color:#117BAA">Dream High ⭐</span> <br>
                  <span style="color:#117BAA">Dream High 2 😍 </span><br>
                  <span style="color:#117BAA">Dream Knight 😍</span>
                <p>
                  <strong> E </strong>
                  <br>
                   <span style="color:#117BAA">Emergency Couple 😍</span> <br>
                   <span style="color:#117BAA">Empress Ki 😄</span> <br>
                   <span style="color:#117BAA">EXO NEXT DOOR ⭐</span>
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#117BAA">Faith ⭐</span> <br>
                  <span style="color:#117BAA">Falling For Do Jeon 😍</span><br>
                  <span style="color:#117BAA">Falling for Innocence 😍</span><br>
                  <span style="color:#117BAA">Fated to Love You ⭐</span><br>
                  <span style="color:#117BAA">Flower Boy Next Door 😍</span> <br>
                  <span style="color:#117BAA">Fluttering Warning 😄</span><br>
                  <span style="color:#117BAA">Full House</span> <br>
                  <span style="color:#117BAA">Full House Take 2</span>
               </p>
               <p>
                  <strong> G </strong>
                  <br>
                  <span style="color:#117BAA">Go Back Couple 😍</span> <br>
                  <span style="color:#117BAA">Goblin ⭐</span> <br>
                  <span style="color:#117BAA">Goodbye Wife</span> <br>
                  <span style="color:#117BAA">Good Doctor 😄</span> <br>
                  <span style="color:#117BAA">Goong 😄</span> <br>
                  <span style="color:#117BAA">Gu Family Book 😍</span>
               </p>
               <p>
                  <strong> H </strong>
                  <br>
                  <span style="color:#117BAA">Healer ⭐</span> <br>
                  <span style="color:#117BAA">Hello Monster ⭐</span> <br>
                  <span style="color:#117BAA">High Schooler King of Life 😍</span><br>
                  <span style="color:#117BAA">Hotel Del Luna 😍</span><br>
                  <span style="color:#117BAA">Hwang Jin Yi 😍</span> <br>
                  <span style="color:#117BAA">Hyde, Jekyll, Me ⭐</span>
               </p>
               <p>
                  <strong> I </strong>
                  <br>
                  <span style="color:#117BAA">I am... 😄</span> <br>
                  <span style="color:#117BAA">I Miss You</span> <br>
                  <span style="color:#117BAA">I Need Romance 😍</span> <br>
                  <span style="color:#117BAA">I Need Romance 2012 😄</span> <br>
                  <span style="color:#117BAA">IRIS</span> <br>
                  <span style="color:#117BAA">It's Okay, It's Love ⭐</span>
               </p>
               <p>
                  <strong> J </strong>
                  <br>
                  <span style="color:#117BAA">Jealousy Incarnate ⭐</span>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                  <span style="color:#117BAA">K-POP - The Ultimate Audition 😍</span> <br>
                  <span style="color:#117BAA">Kill Me, Heal Me 😍</span> 
               </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#117BAA">Legend of the Blue Sea ⭐</span><br>
                  <span style="color:#117BAA">Let's Fight Ghost 😍</span><br>
                  <span style="color:#117BAA">Lie to Me 😍</span><br>
                  <span style="color:#117BAA">Lucky Romance ⭐</span>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#117BAA">Ma Boy 😍</span> <br>
                  <span style="color:#117BAA">Madame Antoine ⭐</span> <br>
                  <span style="color:#117BAA">Marriage Contract 😄</span> <br>
                  <span style="color:#117BAA">Marriage Not Dating 😍</span> <br>
                  <span style="color:#117BAA">Marry Him If You Dare 😄</span><br>
                  <span style="color:#117BAA">Mary Stayed Out All Night</span> <br>
                  <span style="color:#117BAA">Master's Sun ⭐</span><br>
                  <span style="color:#117BAA">Mirror of the Witch 😍</span> <br>
                  <span style="color:#117BAA">Mischievous Kiss 😍</span> <br>
                  <span style="color:#117BAA">Missing Korea 😍</span> <br>
                  <span style="color:#117BAA">Moonlight Drawn by Clouds 😍</span><br>
                  <span style="color:#117BAA">Moon Lovers: Scarlet Heart Ryeo</span><br>
                  <span style="color:#117BAA">Moorim School 😍</span><br>
                  <span style="color:#117BAA">My Girl</span> <br>
                  <span style="color:#117BAA">My Lovely Sam-Soon 😍</span> <br>
                  <span style="color:#117BAA">My Only Love Song ⭐</span>
               </p>
               <p>
                  <strong> N </strong>
                  <br>
                  <span style="color:#117BAA">Nightmare Teacher 😄</span>
               </p>
               <p>
                  <strong> O </strong>
                  <br>
                 <span style="color:#117BAA">Oh My Ghost ⭐</span> <br>
                 <span style="color:#117BAA">Oh My Venus ⭐</span><br>
                 <span style="color:#117BAA">One More Happy Ending ⭐</span><br>
                 <span style="color:#117BAA">One Percent of Anything 😍</span>
               </p>
               <p>
                  <strong> P </strong>
                  <br>
                  <span style="color:#117BAA">Paradise Ranch</span><br>
                  <span style="color:#117BAA">Personal Taste 😍</span> <br>
                  <span style="color:#117BAA">Pinocchio</span><br>
                  <span style="color:#117BAA">Please Come Back, Mister 😍</span> <br>
                  <span style="color:#117BAA">Prime Minister and I</span><br>
                  <span style="color:#117BAA">Princess Hwapyung's Weight Loss 😍</span><br>
                  <span style="color:#117BAA">Protect the Boss</span>
               </p>
               <p>
                  <strong> Q </strong>
                  <br>
                  <span style="color:#117BAA">Queen In Hyun's Man 😍</span><br>
                  <span style="color:#117BAA">Queen of the Ring 😍</span>
               </p>
               <p>
                  <strong> R </strong>
                  <br>
                  <span style="color:#117BAA">Reply 1988 😍</span><br>
                  <span style="color:#117BAA">Reply 1994 ⭐</span> <br>
                  <span style="color:#117BAA">Reply 1997 😍</span><br>
                  <span style="color:#117BAA">Rooftop Prince ⭐</span> <br>
                  <span style="color:#117BAA">Ruby Ruby Love 😍</span>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#117BAA">Sassy, Go Go 😄</span> <br>
                  <span style="color:#117BAA">Sassy Girl Chun Hyang ⭐</span><br>
                  <span style="color:#117BAA">School 2017 😄</span> <br>
                  <span style="color:#117BAA">Secret Garden ⭐</span> <br>
                  <span style="color:#117BAA">Secret Love ⭐</span><br>
                  <span style="color:#117BAA">Seven First Kisses 😍</span><br>
                  <span style="color:#117BAA">She is Nineteen</span><br>
                  <span style="color:#117BAA">She Was Pretty ⭐</span><br>
                  <span style="color:#117BAA">Snow Lotus 😍</span><br>
                  <span style="color:#117BAA">Splash Splash Love 😍</span> <br>
                  <span style="color:#117BAA">Star of the Universe 😍</span><br>
                  <span style="color:#117BAA">Stars falling from the sky 😍</span> <br>
                  <span style="color:#117BAA">Sungkyunkwan Scandal 😍</span><br>
                  <span style="color:#117BAA">Surplus Princess 😍</span><br>
                  <span style="color:#117BAA">Sweden Laundry</span>
               </p>
               <p>
                  <strong> T </strong>
                  <br>
                  <span style="color:#117BAA">Take Care of the Young Lady ⭐</span><br>
                  <span style="color:#117BAA">The 1st Shop of Coffee Prince ⭐</span><br>
                  <span style="color:#117BAA">The Accidental Couple</span><br>
                  <span style="color:#117BAA">The Greatest Love 😍</span> <br>
                  <span style="color:#117BAA">The King 2 Hearts</span><br>
                  <span style="color:#117BAA">The Queen's Classroom 😍</span> <br>
                  <span style="color:#117BAA">The Sound of Your Heart 😍</span><br>
                  <span style="color:#117BAA">The Strange Housekeeper 😍</span><br>
                  <span style="color:#117BAA">Tree of Heaven</span> <br>
                  <span style="color:#117BAA">Trot Lovers 😍</span> <br>
                  <span style="color:#117BAA">Twenty Again 😍</span><br>
                  <span style="color:#117BAA">Two Cops ⭐</span>
               </p>
               <p>
                  <strong> V </strong>
                  <br>
                  <span style="color:#117BAA">Vagabond 😄</span><br>
                  <span style="color:#117BAA">Voice  ⭐</span>
               </p>
               <p>
                  <strong> W </strong>
                  <br>
                  <span style="color:#117BAA">W ⭐</span><br>
                  <span style="color:#117BAA">Wanted 😍</span><br>
                  <span style="color:#117BAA">Warm and Cozy 😄</span> <br>
                  <span style="color:#117BAA">Who Are You - School 2015 ⭐</span> <br>
                  <span style="color:#117BAA">Wild Romance 😍</span>
               </p>
               <p>
                  <strong> X </strong>
                  <br>
               </p>
               <p>
                  <strong> Y </strong>
                  <br>
                  <span style="color:#117BAA">You're Beautiful 😍</span> <br>
                   <span style="color:#117BAA">You've Fallen for Me 😍</span> <br>
                   <span style="color:#117BAA">You Who Came From the Stars ⭐</span>
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
  name: 'DramasCoreens',
  head() {
    return {
      title: `Dramas Coréens | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

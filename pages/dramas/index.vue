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
                La liste de mes Dramas visualisés
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
                  <span style="color:#56dcd8">2 Moons The Series ⭐</span> - <span style="color:#117BAA">18 vs. 29</span> - <span style="color:#EBC0DE">35 sai no Koukousei ⭐</span> - <span style="color:#117BAA"> 49 Days 😍 </span> - <span style="color:#EBC0DE">100 Scene No Koi 😄</span>
                </p>
                <p>
                  <strong> A </strong>
                  <br> 
                  <span style="color:#EBC0DE">Abarenbo Mama 😍</span> - <span style="color:#117BAA">Aftermath</span> - <span style="color:#EBC0DE">Again!!</span> - <span style="color:#117BAA">A Gentleman's Dignity ⭐</span> - <span style="color:#117BAA">A Girl Who Sees Smells ⭐</span> - <span style="color:#117BAA">A Korean Odyssey ⭐ </span>- <span style="color:#f0ad4e">Alice in Wonder City 😄</span> - <span style="color:#d9534f">A Love So Beautiful ⭐ </span>- <span style="color:#117BAA">A Love To Kill </span> - <span style="color:#117BAA">Angry Mom ⭐</span> - <span style="color:#117BAA">Another Oh Hae Young ⭐ </span>- <span style="color:#117BAA">Another Parting 😍</span> - <span style="color:#f0ad4e">Apple In Your Eye</span> - <span style="color:#117BAA">Arang and the Magistrate 😍</span> - <span style="color:#117BAA">Arthdal Chronicles 😍</span> - <span style="color:#EBC0DE">Asuko March</span> - <span style="color:#EBC0DE">Atashinchi no Danshi 😍</span> - <span style="color:#f0ad4e">Attention, Love! ⭐</span> - <span style="color:#EBC0DE">Attention Please 😄</span> -  <span style="color:#f0ad4e">Autumn's Concerto ⭐</span> - <span style="color:#117BAA">A Witch's Love 😍</span>
                </p>
                <p>
                  <strong> B </strong>
                  <br>
                  <span style="color:#f0ad4e">Back to 1989 ⭐</span> - <span style="color:#f0ad4e">Back to Home ⭐</span> - <span style="color:#117BAA">Bad Family ⭐</span> - <span style="color:#117BAA">Bad Guys 😍</span> - <span style="color:#117BAA">Bad Love 😍</span> - <span style="color:#117BAA">Beautiful Gong Shim 😍</span> - <span style="color:#117BAA">Beautiful Mind ⭐</span> - <span style="color:#f0ad4e">Before We Get Married </span>- <span style="color:#f0ad4e">Behind Your Smile</span> - <span style="color:#117BAA">Bel Ami</span> - <span style="color:#117BAA">Be Positive 😄</span> - <span style="color:#f0ad4e">Better Man ⭐</span> -   <span style="color:#117BAA">Birth of a Beauty</span> - <span style="color:#117BAA">Boys Before Flowers</span> - <span style="color:#f0ad4e">Boysitter 😄</span> - <span style="color:#117BAA">Bridal Mask 😍</span> - <span style="color:#117BAA">Bride of the Century ⭐</span> - <span style="color:#f0ad4e">Bromance ⭐</span>
                <p>
                  <strong> C </strong>
                  <br>
                  <span style="color:#117BAA">Can You Hear My Heart? 😄</span> - <span style="color:#117BAA">Cheese in the Trap </span> - <span style="color:#117BAA">Cheongdamdong Alice 😍</span> - <span style="color:#117BAA">Choco Bank</span> - <span style="color:#117BAA">Cinderella and the Four Knights ⭐</span> - <span style="color:#117BAA">City Hunter ⭐</span> -   <span style="color:#d9534f">Cruel Romance ⭐⭐</span> - <span style="color:#117BAA">Cunning Single Lady 😍</span>
                </p>
                <p>
                  <strong> D </strong>
                  <br>
                  <span style="color:#d9534f">Dear Prince ⭐</span> - <span style="color:#117BAA">Descendants of the Sun 😍</span> - <span style="color:#f0ad4e">Devil Beside You ⭐</span> - <span style="color:#117BAA">Discovery of Love 😍</span> - <span style="color:#f0ad4e">Down With Love 😍</span> - <span style="color:#117BAA">Dr. Frost 😄</span> -  <span style="color:#117BAA">Dramaworld ⭐</span>- <span style="color:#117BAA">Dream High ⭐</span> - <span style="color:#117BAA">Dream High 2 😍 </span>- <span style="color:#117BAA">Dream Knight 😍</span> - <span style="color:#f0ad4e">Déjà Vu 😍</span>
                <p>
                  <strong> E </strong>
                  <br>
                  <span style="color:#f0ad4e">Easy Fortune Happy Life 😄</span> - <span style="color:#117BAA">Emergency Couple 😍</span> - <span style="color:#117BAA">Empress Ki 😄</span> - <span style="color:#117BAA">EXO NEXT DOOR ⭐</span>
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#f0ad4e">Fabulous Boys</span> -<span style="color:#117BAA">Faith ⭐</span> - <span style="color:#117BAA">Falling For Do Jeon 😍</span> - <span style="color:#117BAA">Falling for Innocence 😍</span> - <span style="color:#f0ad4e">Fall in Love With Me ⭐</span> - <span style="color:#117BAA">Fated to Love You ⭐</span> - <span style="color:#f0ad4e">Fated To Love You 😍</span> - <span style="color:#EBC0DE">First Kiss</span> - <span style="color:#f0ad4e">Five Missions ⭐</span> - <span style="color:#117BAA">Flower Boy Next Door 😍</span> - <span style="color:#117BAA">Fluttering Warning 😄</span> - <span style="color:#117BAA">Full House</span> - <span style="color:#56dcd8">Full House ⭐</span> - <span style="color:#117BAA">Full House Take 2</span>
               </p>
               <p>
                  <strong> G </strong>
                  <br>
                  <span style="color:#117BAA">Go Back Couple 😍</span> - <span style="color:#117BAA">Goblin ⭐</span> - <span style="color:#EBC0DE">Gokusen 😍</span> - <span style="color:#EBC0DE">Gokusen 2 😄</span> - <span style="color:#117BAA">Goodbye Wife</span> - <span style="color:#117BAA">Good Doctor 😄</span> - <span style="color:#117BAA">Goong 😄</span> - <span style="color:#EBC0DE">GTO  😍</span> - <span style="color:#f0ad4e">GTO TAIWAN 😍</span> - <span style="color:#117BAA">Gu Family Book 😍</span>
               </p>
               <p>
                  <strong> H </strong>
                  <br>
                  <span style="color:#EBC0DE">Hana Nochi Hare  😄</span> - <span style="color:#EBC0DE">Hana Yori Dango ⭐⭐</span> - <span style="color:#EBC0DE">Hana Yori Dango 2 ⭐</span> - <span style="color:#EBC0DE">Hanazakari no Kimitachi e ⭐</span> - <span style="color:#EBC0DE">Hanazakari no Kimitachi e</span> - <span style="color:#EBC0DE">Hanazakari no Kimitachi e SP 😍</span> - <span style="color:#117BAA">Healer ⭐</span> - <span style="color:#f0ad4e">Hello Again! 😍</span> - <span style="color:#117BAA">Hello Monster ⭐</span> - <span style="color:#117BAA">High Schooler King of Life 😍</span> - <span style="color:#f0ad4e">Hi My Sweetheart ⭐</span> - <span style="color:#f0ad4e">HIStory 2: Cross The Line 😍</span> - <span style="color:#f0ad4e">HIStory 2: Right or Wrong ⭐</span> - <span style="color:#f0ad4e">HIStory 3: Make Our Days Count ⭐</span> - <span style="color:#f0ad4e">HIStory 3: Trapped ⭐</span> - <span style="color:#f0ad4e">HIStory: My Hero ⭐</span> - <span style="color:#f0ad4e">HIStory: Obsessed ⭐</span> - <span style="color:#f0ad4e">HIStory: Stay Away From Me ⭐</span> - <span style="color:#f0ad4e">Home Sweet Home 😍</span> - <span style="color:#117BAA">Hotel Del Luna 😍</span> - <span style="color:#117BAA">Hwang Jin Yi 😍</span> - <span style="color:#117BAA">Hyde, Jekyll, Me ⭐</span>
               </p>
               <p>
                  <strong> I </strong>
                  <br>
                  <span style="color:#117BAA">I am... 😄</span> - <span style="color:#f0ad4e">I Am Sorry, I Love You 😍</span> - <span style="color:#EBC0DE">Ikemen desu ne</span> - <span style="color:#117BAA">I Miss You</span> - <span style="color:#f0ad4e">Inborn Pair ⭐</span> - <span style="color:#117BAA">I Need Romance 😍</span> - <span style="color:#117BAA">I Need Romance 2012 😄</span> - <span style="color:#f0ad4e">In Time With You ⭐</span> - <span style="color:#117BAA">IRIS</span> - <span style="color:#f0ad4e">Iron Ladies 😍</span> - <span style="color:#117BAA">It's Okay, It's Love ⭐</span> - <span style="color:#EBC0DE">Itazura na Kiss ~ Love in TOKYO</span> - <span style="color:#f0ad4e">It Started With a Kiss</span>
               </p>
               <p>
                  <strong> J </strong>
                  <br>
                  <span style="color:#117BAA">Jealousy Incarnate ⭐</span> - <span style="color:#f0ad4e">Jin Da Hua De Hua Li Mao Xian 😄</span> - <span style="color:#f0ad4e">JOJO's World 😄</span> - <span style="color:#f0ad4e">Just You ⭐</span>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                  <span style="color:#117BAA">K-POP - The Ultimate Audition 😍</span> - <span style="color:#117BAA">Kill Me, Heal Me 😍</span> - <span style="color:#EBC0DE">Kimi wa Pet </span> - <span style="color:#56dcd8">Kiss Me ⭐</span> - <span style="color:#EBC0DE">Koishite Akuma </span>
               </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#d9534f">Lady & Liar 😍</span> - <span style="color:#117BAA">Legend of the Blue Sea ⭐</span> - <span style="color:#f0ad4e">Le Jun Kai 😄</span> - <span style="color:#f0ad4e">Leo 😄</span> - <span style="color:#117BAA">Let's Fight Ghost 😍</span> - <span style="color:#d9534f">Let's Go Watch Meteor Shower 😄</span> - <span style="color:#d9534f">Let's Watch The Meteor Shower Together Again 😄</span> - <span style="color:#EBC0DE">LIAR GAME</span> - <span style="color:#117BAA">Lie to Me 😍</span> - <span style="color:#f0ad4e">Lion Pride 😍</span> - <span style="color:#f0ad4e">Love, Now 😄</span> - <span style="color:#f0ad4e">Love @ Seventeen 😄</span> - <span style="color:#f0ad4e">Love Around 😍</span> - <span style="color:#d9534f">Love at Second Sight</span> - <span style="color:#f0ad4e">Love Buffet</span> - <span style="color:#f0ad4e">Love By Design 😍</span> - <span style="color:#f0ad4e">Love Cheque Charge</span> - <span style="color:#f0ad4e">Love Keeps Going</span> - <span style="color:#d9534f">Love O2O 😄</span> - <span style="color:#f0ad4e">Love of Sandstorm</span> - <span style="color:#f0ad4e">Love Or Bread</span> - <span style="color:#f0ad4e">Love You ⭐</span> - <span style="color:#117BAA">Lucky Romance ⭐</span>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#117BAA">Ma Boy 😍</span> - <span style="color:#117BAA">Madame Antoine ⭐</span> - <span style="color:#117BAA">Marriage Contract 😄</span> - <span style="color:#117BAA">Marriage Not Dating 😍</span> - <span style="color:#117BAA">Marry Him If You Dare 😄</span> - <span style="color:#f0ad4e">Marry Me Or Not? ⭐</span> - <span style="color:#117BAA">Mary Stayed Out All Night</span> - <span style="color:#117BAA">Master's Sun ⭐</span> - <span style="color:#f0ad4e">Material Queen 😄</span> - <span style="color:#EBC0DE">Mei-chan no Shitsuji 😄</span> - <span style="color:#f0ad4e">Memory Love 😍</span> - <span style="color:#f0ad4e">Meteor Garden ⭐</span> - <span style="color:#d9534f">Meteor Garden ⭐</span> - <span style="color:#117BAA">Mirror of the Witch 😍</span> - <span style="color:#117BAA">Mischievous Kiss 😍</span> - <span style="color:#117BAA">Missing Korea 😍</span> - <span style="color:#f0ad4e">Miss In Kiss ⭐</span> - <span style="color:#f0ad4e">Miss No Good 😍</span> - <span style="color:#f0ad4e">Miss Rose 😄</span> - <span style="color:#f0ad4e">Momo Love 😄</span> - <span style="color:#117BAA">Moonlight Drawn by Clouds 😍</span> - <span style="color:#117BAA">Moon Lovers: Scarlet Heart Ryeo</span> - <span style="color:#f0ad4e">Moon River 😄</span> - <span style="color:#117BAA">Moorim School 😍</span> - <span style="color:#f0ad4e">Murphy's Law of Love 😍</span> - <span style="color:#d9534f">My Amazing Boyfriend 😄</span> - <span style="color:#EBC0DE">My Boss My Hero 😍</span> - <span style="color:#117BAA">My Girl</span> - <span style="color:#d9534f">My Little Princess 😄</span> - <span style="color:#117BAA">My Lovely Sam-Soon 😍</span> - <span style="color:#117BAA">My Only Love Song ⭐</span>
               </p>
               <p>
                  <strong> N </strong>
                  <br>
                  <span style="color:#117BAA">Nightmare Teacher 😄</span> - <span style="color:#EBC0DE">Nihonjin no Shiranai Nihongo 😄</span> - <span style="color:#EBC0DE">Nodame Cantabile 😄</span>
               </p>
               <p>
                  <strong> O </strong>
                  <br>
                  <span style="color:#f0ad4e">Office Girls 😄</span> - <span style="color:#117BAA">Oh My Ghost ⭐</span> - <span style="color:#117BAA">Oh My Venus ⭐</span> - <span style="color:#f0ad4e">Once More Heartbeat 😄</span> - <span style="color:#117BAA">One More Happy Ending ⭐</span> - <span style="color:#117BAA">One Percent of Anything 😍</span>
               </p>
               <p>
                  <strong> P </strong>
                  <br>
                  <span style="color:#117BAA">Paradise Ranch</span> - <span style="color:#EBC0DE">Parfait Tic !</span> - <span style="color:#117BAA">Personal Taste 😍</span> - <span style="color:#117BAA">Pinocchio</span> - <span style="color:#f0ad4e">Pleasantly Surprised 😍</span> - <span style="color:#117BAA">Please Come Back, Mister 😍</span> - <span style="color:#117BAA">Prime Minister and I</span> - <span style="color:#d9534f">Prince of Lan Ling 😄</span> - <span style="color:#f0ad4e">Prince Of Wolf ⭐</span> - <span style="color:#117BAA">Princess Hwapyung's Weight Loss 😍</span> - <span style="color:#f0ad4e">Prince Turns to Frog</span> - <span style="color:#f0ad4e">Prince William</span> - <span style="color:#EBC0DE">Proposal Daisakusen 😍</span> - <span style="color:#117BAA">Protect the Boss</span>
               </p>
               <p>
                  <strong> Q </strong>
                  <br>
                  <span style="color:#117BAA">Queen In Hyun's Man 😍</span> - <span style="color:#117BAA">Queen of the Ring 😍</span>
               </p>
               <p>
                  <strong> R </strong>
                  <br>
                  <span style="color:#f0ad4e">Refresh Man 😄</span> - <span style="color:#117BAA">Reply 1988 😍</span> - <span style="color:#117BAA">Reply 1994 ⭐</span> - <span style="color:#117BAA">Reply 1997 😍</span> - <span style="color:#EBC0DE">Rich Man, Poor Woman 😍</span> - <span style="color:#117BAA">Rooftop Prince ⭐</span> - <span style="color:#117BAA">Ruby Ruby Love 😍</span>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#117BAA">Sassy, Go Go 😄</span> - <span style="color:#117BAA">Sassy Girl Chun Hyang ⭐</span> - <span style="color:#f0ad4e">Say Again Yes I Do 😍</span> - <span style="color:#d9534f">Scarlet Heart ⭐</span> - <span style="color:#d9534f">Scarlet Heart 2 😍</span> - <span style="color:#117BAA">School 2017 😄</span> - <span style="color:#117BAA">Secret Garden ⭐</span> - <span style="color:#117BAA">Secret Love ⭐</span> - <span style="color:#f0ad4e">See You in Time </span> - <span style="color:#117BAA">Seven First Kisses 😍</span> - <span style="color:#117BAA">She is Nineteen</span> - <span style="color:#117BAA">She Was Pretty ⭐</span> - <span style="color:#f0ad4e">Single Ladies Senior 😍</span> - <span style="color:#f0ad4e">Skip Beat !</span> - <span style="color:#f0ad4e">Smiling Pasta 😍</span> - <span style="color:#117BAA">Snow Lotus 😍</span> - <span style="color:#f0ad4e">Someday or One Day ⭐⭐</span> - <span style="color:#117BAA">Splash Splash Love 😍</span> - <span style="color:#117BAA">Star of the Universe 😍</span> - <span style="color:#117BAA">Stars falling from the sky 😍</span> - <span style="color:#f0ad4e">Summer's Desire ⭐</span> - <span style="color:#117BAA">Sungkyunkwan Scandal 😍</span> - <span style="color:#f0ad4e">Sunshine Angel</span> - <span style="color:#117BAA">Surplus Princess 😍</span> - <span style="color:#117BAA">Sweden Laundry</span> - <span style="color:#f0ad4e">Swimming Battle 😄</span> - <span style="color:#EBC0DE">Switch Girl!! 😍</span>
               </p>
               <p>
                  <strong> T </strong>
                  <br>
                  <span style="color:#117BAA">Take Care of the Young Lady ⭐</span> - <span style="color:#117BAA">The 1st Shop of Coffee Prince ⭐</span> - <span style="color:#117BAA">The Accidental Couple</span> - <span style="color:#f0ad4e">The Crossing Hero 😍</span> - <span style="color:#117BAA">The Greatest Love 😍</span> - <span style="color:#117BAA">The King 2 Hearts</span> - <span style="color:#f0ad4e">The Magicians of Love 😄</span> - <span style="color:#f0ad4e">The Masked Lover ⭐</span> - <span style="color:#f0ad4e">The Perfect Match 😄</span> - <span style="color:#f0ad4e">The Pursuit of Happiness 😍</span> - <span style="color:#117BAA">The Queen's Classroom 😍</span> - <span style="color:#117BAA">The Sound of Your Heart 😍</span> - <span style="color:#117BAA">The Strange Housekeeper 😍</span> - <span style="color:#f0ad4e">The Way We Were 😍</span> - <span style="color:#f0ad4e">They Kiss Again ⭐</span> - <span style="color:#f0ad4e">ToGetHer 😄</span> - <span style="color:#f0ad4e">Tokyo Juliet 😄</span> - <span style="color:#117BAA">Tree of Heaven</span> - <span style="color:#f0ad4e">Triad Princess ⭐</span> - <span style="color:#117BAA">Trot Lovers 😍</span> - <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi ⭐</span> - <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi 2 ⭐</span> - <span style="color:#117BAA">Twenty Again 😍</span> - <span style="color:#117BAA">Two Cops ⭐</span>
               </p>
               <p>
                  <strong> V </strong>
                  <br>
                  <span style="color:#f0ad4e">V-Focus ⭐</span> - <span style="color:#117BAA">Vagabond 😄</span> - <span style="color:#117BAA">Voice  ⭐</span>
               </p>
               <p>
                  <strong> W </strong>
                  <br>
                  <span style="color:#117BAA">W ⭐</span> - <span style="color:#117BAA">Wanted 😍</span> - <span style="color:#117BAA">Warm and Cozy 😄</span> - <span style="color:#f0ad4e">When I See You Again 😍</span> - <span style="color:#f0ad4e">Who's The One 😄</span> - <span style="color:#117BAA">Who Are You - School 2015 ⭐</span> - <span style="color:#f0ad4e">Why Why Love</span> - <span style="color:#117BAA">Wild Romance 😍</span>
               </p>
               <p>
                  <strong> X </strong>
                  <br>
                  <span style="color:#f0ad4e">Xiao Hua De Tie Shen Gao Shou</span>
               </p>
               <p>
                  <strong> Y </strong>
                  <br>
                  <span style="color:#EBC0DE">Yamato Nadeshiko Shichi Henge</span> - <span style="color:#EBC0DE">Yankee-kun to Megane-chan 😄</span> - <span style="color:#f0ad4e">Ying Ye 3 + 1 😍</span> - <span style="color:#f0ad4e">Yong-Jiu Grocery Store 😄</span> - <span style="color:#117BAA">You're Beautiful 😍</span> - <span style="color:#117BAA">You've Fallen for Me 😍</span> - <span style="color:#117BAA">You Who Came From the Stars ⭐</span>
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
  name: 'Drama',
  head() {
    return {
      title: `Drama | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

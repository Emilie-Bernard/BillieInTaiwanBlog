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
                La liste de tous les dramas que j'ai visualisés
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
                  <span style="color:#56dcd8">2 Moons The Series ⭐</span><br>
                  <span style="color:#117BAA">18 vs. 29</span><br>
                  <span style="color:#EBC0DE">35 sai no Koukousei ⭐</span><br>
                  <span style="color:#117BAA"> 49 Days 😍 </span><br>
                  <span style="color:#EBC0DE">100 Scene No Koi 😄</span>
                </p>
                <p>
                  <strong> A </strong>
                  <br> 
                  <span style="color:#EBC0DE">Abarenbo Mama 😍</span><br>
                  <span style="color:#117BAA">Aftermath</span><br>
                  <span style="color:#EBC0DE">Again!!</span><br>
                  <span style="color:#117BAA">A Gentleman's Dignity ⭐</span><br>
                  <span style="color:#117BAA">A Girl Who Sees Smells ⭐</span><br>
                  <span style="color:#117BAA">A Korean Odyssey ⭐ </span><br>
                  <span style="color:#f0ad4e">Alice in Wonder City 😄</span> <br>
                  <span style="color:#d9534f">A Love So Beautiful ⭐ </span><br>
                  <span style="color:#117BAA">A Love To Kill </span><br>
                  <span style="color:#117BAA">Angry Mom ⭐</span><br>
                  <span style="color:#117BAA">Another Oh Hae Young ⭐ </span><br>
                  <span style="color:#117BAA">Another Parting 😍</span><br>
                  <span style="color:#f0ad4e">Apple In Your Eye</span><br>
                  <span style="color:#117BAA">Arang and the Magistrate 😍</span><br>
                  <span style="color:#117BAA">Arthdal Chronicles 😍</span><br>
                  <span style="color:#EBC0DE">Asuko March</span><br>
                  <span style="color:#EBC0DE">Atashinchi no Danshi 😍</span><br>
                  <span style="color:#f0ad4e">Attention, Love! ⭐</span><br>
                  <span style="color:#EBC0DE">Attention Please 😄</span><br>
                  <span style="color:#f0ad4e">Autumn's Concerto ⭐</span><br>
                  <span style="color:#117BAA">A Witch's Love 😍</span>
                </p>
                <p>
                  <strong> B </strong>
                  <br>
                  <span style="color:#f0ad4e">Back to 1989 ⭐</span><br>
                  <span style="color:#f0ad4e">Back to Home ⭐</span><br>
                  <span style="color:#117BAA">Bad Family ⭐</span><br>
                  <span style="color:#117BAA">Bad Guys 😍</span><br>
                  <span style="color:#117BAA">Bad Love 😍</span><br>
                  <span style="color:#117BAA">Beautiful Gong Shim 😍</span><br>
                  <span style="color:#117BAA">Beautiful Mind ⭐</span><br>
                  <span style="color:#f0ad4e">Before We Get Married </span><br>
                  <span style="color:#f0ad4e">Behind Your Smile</span><br>
                  <span style="color:#117BAA">Bel Ami</span><br>
                  <span style="color:#117BAA">Be Positive 😄</span><br>
                  <span style="color:#f0ad4e">Better Man ⭐</span><br>
                  <span style="color:#117BAA">Birth of a Beauty</span><br>
                  <span style="color:#117BAA">Boys Before Flowers</span><br>
                  <span style="color:#f0ad4e">Boysitter 😄</span><br>
                  <span style="color:#117BAA">Bridal Mask 😍</span><br>
                  <span style="color:#117BAA">Bride of the Century ⭐</span><br>
                  <span style="color:#f0ad4e">Bromance ⭐</span>
                <p>
                  <strong> C </strong>
                  <br>
                  <span style="color:#117BAA">Can You Hear My Heart? 😄</span><br>
                  <span style="color:#117BAA">Cheese in the Trap </span><br>
                  <span style="color:#117BAA">Cheongdamdong Alice 😍</span><br>
                  <span style="color:#117BAA">Choco Bank</span><br>
                  <span style="color:#117BAA">Cinderella and the Four Knights ⭐</span><br>
                  <span style="color:#117BAA">City Hunter ⭐</span><br>
                  <span style="color:#d9534f">Cruel Romance ⭐⭐</span><br>
                  <span style="color:#117BAA">Cunning Single Lady 😍</span>
                </p>
                <p>
                  <strong> D </strong>
                  <br>
                  <span style="color:#d9534f">Dear Prince ⭐</span><br>
                  <span style="color:#117BAA">Descendants of the Sun 😍</span><br>
                  <span style="color:#f0ad4e">Devil Beside You ⭐</span><br>
                  <span style="color:#117BAA">Discovery of Love 😍</span><br>
                  <span style="color:#f0ad4e">Down With Love 😍</span><br>
                  <span style="color:#117BAA">Dr. Frost 😄</span><br>
                  <span style="color:#117BAA">Dramaworld ⭐</span><br>
                  <span style="color:#117BAA">Dream High ⭐</span><br>
                  <span style="color:#117BAA">Dream High 2 😍 </span><br>
                  <span style="color:#117BAA">Dream Knight 😍</span><br>
                  <span style="color:#f0ad4e">Déjà Vu 😍</span>
                <p>
                  <strong> E </strong>
                  <br>
                  <span style="color:#f0ad4e">Easy Fortune Happy Life 😄</span><br>
                  <span style="color:#117BAA">Emergency Couple 😍</span><br>
                  <span style="color:#117BAA">Empress Ki 😄</span><br>
                  <span style="color:#117BAA">EXO NEXT DOOR ⭐</span>
                </p>
                <p>
                  <strong> F </strong>
                  <br>
                  <span style="color:#f0ad4e">Fabulous Boys</span><br>
                  <span style="color:#117BAA">Faith ⭐</span><br>
                  <span style="color:#117BAA">Falling For Do Jeon 😍</span><br>
                  <span style="color:#117BAA">Falling for Innocence 😍</span><br>
                  <span style="color:#f0ad4e">Fall in Love With Me ⭐</span><br>
                  <span style="color:#117BAA">Fated to Love You ⭐</span><br>
                  <span style="color:#f0ad4e">Fated To Love You 😍</span><br>
                  <span style="color:#EBC0DE">First Kiss</span><br>
                  <span style="color:#f0ad4e">Five Missions ⭐</span><br>
                  <span style="color:#117BAA">Flower Boy Next Door 😍</span><br>
                  <span style="color:#117BAA">Fluttering Warning 😄</span><br>
                  <span style="color:#117BAA">Full House</span><br>
                  <span style="color:#56dcd8">Full House ⭐</span><br>
                  <span style="color:#117BAA">Full House Take 2</span>
               </p>
               <p>
                  <strong> G </strong>
                  <br>
                  <span style="color:#117BAA">Go Back Couple 😍</span><br>
                  <span style="color:#117BAA">Goblin ⭐</span><br>
                  <span style="color:#EBC0DE">Gokusen 😍</span><br>
                  <span style="color:#EBC0DE">Gokusen 2 😄</span><br>
                  <span style="color:#117BAA">Goodbye Wife</span><br>
                  <span style="color:#117BAA">Good Doctor 😄</span><br>
                  <span style="color:#117BAA">Goong 😄</span><br>
                  <span style="color:#EBC0DE">GTO  😍</span><br>
                  <span style="color:#f0ad4e">GTO TAIWAN 😍</span><br>
                  <span style="color:#117BAA">Gu Family Book 😍</span>
               </p>
               <p>
                  <strong> H </strong>
                  <br>
                  <span style="color:#EBC0DE">Hana Nochi Hare  😄</span><br>
                  <span style="color:#EBC0DE">Hana Yori Dango ⭐⭐</span><br>
                  <span style="color:#EBC0DE">Hana Yori Dango 2 ⭐</span> <br>
                  <span style="color:#EBC0DE">Hanazakari no Kimitachi e ⭐</span><br>
                  <span style="color:#EBC0DE">Hanazakari no Kimitachi e</span><br>
                  <span style="color:#EBC0DE">Hanazakari no Kimitachi e SP 😍</span><br>
                  <span style="color:#117BAA">Healer ⭐</span><br>
                  <span style="color:#f0ad4e">Hello Again! 😍</span><br>
                  <span style="color:#117BAA">Hello Monster ⭐</span><br>
                  <span style="color:#117BAA">High Schooler King of Life 😍</span><br>
                  <span style="color:#f0ad4e">Hi My Sweetheart ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 2: Cross The Line 😍</span><br>
                  <span style="color:#f0ad4e">HIStory 2: Right or Wrong ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 3: Make Our Days Count ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory 3: Trapped ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: My Hero ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: Obsessed ⭐</span><br>
                  <span style="color:#f0ad4e">HIStory: Stay Away From Me ⭐</span><br>
                  <span style="color:#f0ad4e">Home Sweet Home 😍</span><br>
                  <span style="color:#117BAA">Hotel Del Luna 😍</span><br>
                  <span style="color:#117BAA">Hwang Jin Yi 😍</span><br>
                  <span style="color:#117BAA">Hyde, Jekyll, Me ⭐</span>
               </p>
               <p>
                  <strong> I </strong>
                  <br>
                  <span style="color:#117BAA">I am... 😄</span><br>
                  <span style="color:#f0ad4e">I Am Sorry, I Love You 😍</span><br>
                  <span style="color:#EBC0DE">Ikemen desu ne</span><br>
                  <span style="color:#117BAA">I Miss You</span><br>
                  <span style="color:#f0ad4e">Inborn Pair ⭐</span><br>
                  <span style="color:#117BAA">I Need Romance 😍</span><br>
                  <span style="color:#117BAA">I Need Romance 2012 😄</span><br>
                  <span style="color:#f0ad4e">In Time With You ⭐</span><br>
                  <span style="color:#117BAA">IRIS</span><br>
                  <span style="color:#f0ad4e">Iron Ladies 😍</span><br>
                  <span style="color:#117BAA">It's Okay, It's Love ⭐</span><br>
                  <span style="color:#EBC0DE">Itazura na Kiss ~ Love in TOKYO</span><br>
                  <span style="color:#f0ad4e">It Started With a Kiss</span>
               </p>
               <p>
                  <strong> J </strong>
                  <br>
                  <span style="color:#117BAA">Jealousy Incarnate ⭐</span><br>
                  <span style="color:#f0ad4e">Jin Da Hua De Hua Li Mao Xian 😄</span><br>
                  <span style="color:#f0ad4e">JOJO's World 😄</span><br>
                  <span style="color:#f0ad4e">Just You ⭐</span>
               </p>
               <p>
                  <strong> K </strong>
                  <br>
                  <span style="color:#117BAA">K-POP - The Ultimate Audition 😍</span><br>
                  <span style="color:#117BAA">Kill Me, Heal Me 😍</span><br>
                  <span style="color:#EBC0DE">Kimi wa Pet </span><br>
                  <span style="color:#56dcd8">Kiss Me ⭐</span><br>
                  <span style="color:#EBC0DE">Koishite Akuma </span>
               </p>
               <p>
                  <strong> L </strong>
                  <br>
                  <span style="color:#d9534f">Lady & Liar 😍</span> <br>
                  <span style="color:#117BAA">Legend of the Blue Sea ⭐</span><br>
                  <span style="color:#f0ad4e">Le Jun Kai 😄</span><br>
                  <span style="color:#f0ad4e">Leo 😄</span><br>
                  <span style="color:#117BAA">Let's Fight Ghost 😍</span><br>
                  <span style="color:#d9534f">Let's Go Watch Meteor Shower 😄</span><br>
                  <span style="color:#d9534f">Let's Watch The Meteor Shower Together Again 😄</span><br>
                  <span style="color:#EBC0DE">LIAR GAME</span><br>
                  <span style="color:#117BAA">Lie to Me 😍</span><br>
                  <span style="color:#f0ad4e">Lion Pride 😍</span><br>
                  <span style="color:#f0ad4e">Love, Now 😄</span><br>
                  <span style="color:#f0ad4e">Love @ Seventeen 😄</span><br>
                  <span style="color:#f0ad4e">Love Around 😍</span><br>
                  <span style="color:#d9534f">Love at Second Sight</span><br>
                  <span style="color:#f0ad4e">Love Buffet</span><br>
                  <span style="color:#f0ad4e">Love By Design 😍</span><br>
                  <span style="color:#f0ad4e">Love Cheque Charge</span><br>
                  <span style="color:#f0ad4e">Love Keeps Going</span><br>
                  <span style="color:#d9534f">Love O2O 😄</span><br>
                  <span style="color:#f0ad4e">Love of Sandstorm</span><br>
                  <span style="color:#f0ad4e">Love Or Bread</span> <br>
                  <span style="color:#f0ad4e">Love You ⭐</span><br>
                  <span style="color:#117BAA">Lucky Romance ⭐</span>
               </p>
               <p>
                  <strong> M </strong>
                  <br>
                  <span style="color:#117BAA">Ma Boy 😍</span><br>
                  <span style="color:#117BAA">Madame Antoine ⭐</span><br>
                  <span style="color:#117BAA">Marriage Contract 😄</span><br>
                  <span style="color:#117BAA">Marriage Not Dating 😍</span><br>
                  <span style="color:#117BAA">Marry Him If You Dare 😄</span><br>
                  <span style="color:#f0ad4e">Marry Me Or Not? ⭐</span><br>
                  <span style="color:#117BAA">Mary Stayed Out All Night</span><br>
                  <span style="color:#117BAA">Master's Sun ⭐</span><br>
                  <span style="color:#f0ad4e">Material Queen 😄</span><br>
                  <span style="color:#EBC0DE">Mei-chan no Shitsuji 😄</span><br>
                  <span style="color:#f0ad4e">Memory Love 😍</span><br>
                  <span style="color:#f0ad4e">Meteor Garden ⭐</span><br>
                  <span style="color:#d9534f">Meteor Garden ⭐</span><br>
                  <span style="color:#117BAA">Mirror of the Witch 😍</span><br>
                  <span style="color:#117BAA">Mischievous Kiss 😍</span><br>
                  <span style="color:#117BAA">Missing Korea 😍</span><br>
                  <span style="color:#f0ad4e">Miss In Kiss ⭐</span><br>
                  <span style="color:#f0ad4e">Miss No Good 😍</span><br>
                  <span style="color:#f0ad4e">Miss Rose 😄</span><br>
                  <span style="color:#f0ad4e">Momo Love 😄</span><br>
                  <span style="color:#117BAA">Moonlight Drawn by Clouds 😍</span><br>
                  <span style="color:#117BAA">Moon Lovers: Scarlet Heart Ryeo</span><br>
                  <span style="color:#f0ad4e">Moon River 😄</span><br>
                  <span style="color:#117BAA">Moorim School 😍</span> <br>
                  <span style="color:#f0ad4e">Murphy's Law of Love 😍</span><br>
                  <span style="color:#d9534f">My Amazing Boyfriend 😄</span><br>
                  <span style="color:#EBC0DE">My Boss My Hero 😍</span><br>
                  <span style="color:#117BAA">My Girl</span><br>
                  <span style="color:#d9534f">My Little Princess 😄</span><br>
                  <span style="color:#117BAA">My Lovely Sam-Soon 😍</span><br>
                  <span style="color:#117BAA">My Only Love Song ⭐</span>
               </p>
               <p>
                  <strong> N </strong>
                  <br>
                  <span style="color:#117BAA">Nightmare Teacher 😄</span><br>
                  <span style="color:#EBC0DE">Nihonjin no Shiranai Nihongo 😄</span><br>
                  <span style="color:#EBC0DE">Nodame Cantabile 😄</span>
               </p>
               <p>
                  <strong> O </strong>
                  <br>
                  <span style="color:#f0ad4e">Office Girls 😄</span><br>
                  <span style="color:#117BAA">Oh My Ghost ⭐</span><br>
                  <span style="color:#117BAA">Oh My Venus ⭐</span><br>
                  <span style="color:#f0ad4e">Once More Heartbeat 😄</span><br>
                  <span style="color:#117BAA">One More Happy Ending ⭐</span><br>
                  <span style="color:#117BAA">One Percent of Anything 😍</span>
               </p>
               <p>
                  <strong> P </strong>
                  <br>
                  <span style="color:#117BAA">Paradise Ranch</span><br>
                  <span style="color:#EBC0DE">Parfait Tic !</span><br>
                  <span style="color:#117BAA">Personal Taste 😍</span><br>
                  <span style="color:#117BAA">Pinocchio</span><br>
                  <span style="color:#f0ad4e">Pleasantly Surprised 😍</span><br>
                  <span style="color:#117BAA">Please Come Back, Mister 😍</span><br>
                  <span style="color:#117BAA">Prime Minister and I</span> <br>
                  <span style="color:#d9534f">Prince of Lan Ling 😄</span><br>
                  <span style="color:#f0ad4e">Prince Of Wolf ⭐</span> <br>
                  <span style="color:#117BAA">Princess Hwapyung's Weight Loss 😍</span><br>
                  <span style="color:#f0ad4e">Prince Turns to Frog</span> <br>
                  <span style="color:#f0ad4e">Prince William</span><br>
                  <span style="color:#EBC0DE">Proposal Daisakusen 😍</span><br>
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
                  <span style="color:#f0ad4e">Refresh Man 😄</span><br>
                  <span style="color:#117BAA">Reply 1988 😍</span><br>
                  <span style="color:#117BAA">Reply 1994 ⭐</span><br>
                  <span style="color:#117BAA">Reply 1997 😍</span><br>
                  <span style="color:#EBC0DE">Rich Man, Poor Woman 😍</span><br>
                  <span style="color:#117BAA">Rooftop Prince ⭐</span><br>
                  <span style="color:#117BAA">Ruby Ruby Love 😍</span>
               </p>
               <p>
                  <strong> S </strong>
                  <br>
                  <span style="color:#117BAA">Sassy, Go Go 😄</span><br>
                  <span style="color:#117BAA">Sassy Girl Chun Hyang ⭐</span><br>
                  <span style="color:#f0ad4e">Say Again Yes I Do 😍</span><br>
                  <span style="color:#d9534f">Scarlet Heart ⭐</span><br>
                  <span style="color:#d9534f">Scarlet Heart 2 😍</span><br>
                  <span style="color:#117BAA">School 2017 😄</span><br>
                  <span style="color:#117BAA">Secret Garden ⭐</span><br>
                  <span style="color:#117BAA">Secret Love ⭐</span><br>
                  <span style="color:#f0ad4e">See You in Time </span><br>
                  <span style="color:#117BAA">Seven First Kisses 😍</span><br>
                  <span style="color:#117BAA">She is Nineteen</span><br>
                  <span style="color:#117BAA">She Was Pretty ⭐</span><br>
                  <span style="color:#f0ad4e">Single Ladies Senior 😍</span><br>
                  <span style="color:#f0ad4e">Skip Beat !</span><br>
                  <span style="color:#f0ad4e">Smiling Pasta 😍</span> <br>
                  <span style="color:#117BAA">Snow Lotus 😍</span><br>
                  <span style="color:#f0ad4e" href="https://www.billieintaiwan.com/someday-or-one-day">Someday or One Day ⭐⭐</span><br>
                  <span style="color:#117BAA">Splash Splash Love 😍</span><br>
                  <span style="color:#117BAA">Star of the Universe 😍</span><br>
                  <span style="color:#117BAA">Stars falling from the sky 😍</span><br>
                  <span style="color:#f0ad4e">Summer's Desire ⭐</span><br>
                  <span style="color:#117BAA">Sungkyunkwan Scandal 😍</span><br>
                  <span style="color:#f0ad4e">Sunshine Angel</span><br>
                  <span style="color:#117BAA">Surplus Princess 😍</span><br>
                  <span style="color:#117BAA">Sweden Laundry</span><br>
                  <span style="color:#f0ad4e">Swimming Battle 😄</span><br>
                  <span style="color:#EBC0DE">Switch Girl!! 😍</span>
               </p>
               <p>
                  <strong> T </strong>
                  <br>
                  <span style="color:#117BAA">Take Care of the Young Lady ⭐</span><br>
                  <span style="color:#117BAA">The 1st Shop of Coffee Prince ⭐</span><br>
                  <span style="color:#117BAA">The Accidental Couple</span><br>
                  <span style="color:#f0ad4e">The Crossing Hero 😍</span><br>
                  <span style="color:#117BAA">The Greatest Love 😍</span><br>
                  <span style="color:#117BAA">The King 2 Hearts</span><br>
                  <span style="color:#f0ad4e">The Magicians of Love 😄</span><br>
                  <span style="color:#f0ad4e">The Masked Lover ⭐</span><br>
                  <span style="color:#f0ad4e">The Perfect Match 😄</span><br>
                  <span style="color:#f0ad4e">The Pursuit of Happiness 😍</span><br>
                  <span style="color:#117BAA">The Queen's Classroom 😍</span><br>
                  <span style="color:#117BAA">The Sound of Your Heart 😍</span><br>
                  <span style="color:#117BAA">The Strange Housekeeper 😍</span><br>
                  <span style="color:#f0ad4e">The Way We Were 😍</span><br>
                  <span style="color:#f0ad4e">They Kiss Again ⭐</span><br>
                  <span style="color:#f0ad4e">ToGetHer 😄</span><br>
                  <span style="color:#f0ad4e">Tokyo Juliet 😄</span><br>
                  <span style="color:#117BAA">Tree of Heaven</span><br>
                  <span style="color:#f0ad4e">Triad Princess ⭐</span><br>
                  <span style="color:#117BAA">Trot Lovers 😍</span><br>
                  <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi ⭐</span><br>
                  <span style="color:#EBC0DE">Tsubasa no Oreta Tenshitachi 2 ⭐</span><br>
                  <span style="color:#117BAA">Twenty Again 😍</span><br>
                  <span style="color:#117BAA">Two Cops ⭐</span>
               </p>
               <p>
                  <strong> V </strong>
                  <br>
                  <span style="color:#f0ad4e">V-Focus ⭐</span><br>
                  <span style="color:#117BAA">Vagabond 😄</span><br>
                  <span style="color:#117BAA">Voice  ⭐</span>
               </p>
               <p>
                  <strong> W </strong>
                  <br>
                  <span style="color:#117BAA">W ⭐</span><br>
                  <span style="color:#117BAA">Wanted 😍</span><br>
                  <span style="color:#117BAA">Warm and Cozy 😄</span><br>
                  <span style="color:#f0ad4e">When I See You Again 😍</span><br>
                  <span style="color:#f0ad4e">Who's The One 😄</span><br>
                  <span style="color:#117BAA">Who Are You - School 2015 ⭐</span><br>
                  <span style="color:#f0ad4e">Why Why Love</span><br>
                  <span style="color:#117BAA">Wild Romance 😍</span>
               </p>
               <p>
                  <strong> X </strong>
                  <br>
                  <span style="color:#f0ad4e">Xiao Hua De Tie Shen Gao Shou</span>
               </p>
               <p>
                  <strong> Y </strong>
                  <br>
                  <span style="color:#EBC0DE">Yamato Nadeshiko Shichi Henge</span><br>
                  <span style="color:#EBC0DE">Yankee-kun to Megane-chan 😄</span><br>
                  <span style="color:#f0ad4e">Ying Ye 3 + 1 😍</span><br>
                  <span style="color:#f0ad4e">Yong-Jiu Grocery Store 😄</span><br>
                  <span style="color:#117BAA">You're Beautiful 😍</span><br>
                  <span style="color:#117BAA">You've Fallen for Me 😍</span><br>
                  <span style="color:#117BAA">You Who Came From the Stars ⭐</span>
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
  name: 'Dramas',
  head() {
    return {
      title: `Dramas | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

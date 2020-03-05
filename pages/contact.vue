<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="Contactez-moi"
      subtitle="Quelque chose à dire ?"
      image="/uploads/contact-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                Bonjour !
              </p>
              <p class="subtitle">
                N'hésitez pas à m'envoyer un message par mail à l'adresse suivante : bearimnal@gmail.com
              </p>
              <figure class="image is-1by1 ">
                <opti-image
                  :src="require('~/assets/uploads/contact-person.jpg').src"
                  :srcset="
                    require('~/assets/uploads/contact-person.jpg').srcSet
                  "
                />
              </figure>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Pour tous sujets en raport avec le blog :
                  </strong>
                </p>
                <p>
                  Que ce soit des recommendations, un besoin de présicion ou si vous souhaitez que je fasse un article sur un sujet. Contactez-moi pour me faire parvenir votre demande.
                </p>
              </div>
            </article>
          </div>
 <!--         <div class="tile is-parent is-8">
           <article class="tile is-child box">
              <contact-form />
            </article>
          </div>-->
        </div>
      </template>
    </main-section>
  </div>
</template>
<script>
import ContactForm from '~/components/ContactForm'
export default {
  head() {
    return {
      title: `Contact | ${this.$siteConfig.siteName}`
    }
  },
  components: { ContactForm }
}
</script>

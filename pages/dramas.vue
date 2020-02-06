<template>
  <div id="dramas-page" class="page-wrapper dramas-page content-page">
    <site-hero
      title="Dramas"
      subtitle="Tous les dramas vu et mon avi"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
          <div>
        <b-btn variant="outline-info">Taiwan/<b-btn>>
      <b-button variant="outline-info">Corée</b-button>
      <b-button variant="outline-light">Japon</b-button>
      <b-button variant="outline-warning">Chine</b-button>
      <b-button variant="outline-info">Thailande</b-button>
      <b-button variant="outline-light">Autres</b-button>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent is">
            <article class="tile is-child box">
              <p class="title">
                  Taiwanais
              </p>
              <p class="subtitle">
                Ma liste des dramas taiwanais vu
              </p>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                  Coréens
              </p>
              <p class="subtitle">
                Ma liste des dramas coréens vu
              </p>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent is">
            <article class="tile is-child box">
              <p class="title">
                  Chinois
              </p>
              <p class="subtitle">
                Ma liste des dramas chinois vu
              </p>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
        </div>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                  Japonais
              </p>
              <p class="subtitle">
                Ma liste des dramas japonais vu
              </p>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                  Thailandais
              </p>
              <p class="subtitle">
                Ma liste des dramas thailandais vu
              </p>
              <br />
              <div class="content">
                <p>
                  <strong>
                    Edit this page in<code>/pages/contact.vue</code>to fit your
                    needs.
                  </strong>
                </p>
                <p>
                  This form doesn't actually work but would be easy enough to
                  slap an action on to have it post wherever you'd like. Or put
                  the netlify attribute on it and have netlify handle all your
                  form submissions...
                </p>
              </div>
            </article>
          </div>
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

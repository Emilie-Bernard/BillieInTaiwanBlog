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
            <div class="tile is-parent is"><button class="button is-primary" style="font-size:30px;">Japon</button></div>
            <div class="tile is-parent is"><button class="button is-danger" style="font-size:30px;">Thailande</button></div>
           
        </div>
        <!-- Posts in Category -->
        <posts-grid :category="[$store.state.name]" :per-row="2" />
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

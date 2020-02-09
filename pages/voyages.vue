<template>
  <div id="voyages-page" class="page-wrapper voyages-page">
    <site-hero
      title="Voyages"
      subtitle="C'est en voyageant qu'on se découvre soi-même"
      image="/uploads/voyages-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
    <template v-slot:default> 
      <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/categories/voyagess'><button class="button is-dark" style="font-size:30px;">Articles</button></router-link></div>
        </div>
      
      </template>
    </main-section>
  </div>
</template>

<script>
export default {
  name: 'Voyages',
  head() {
    return {
      title: `Voyages | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

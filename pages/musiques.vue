<template>
  <div id="musiques-page" class="page-wrapper musiques-page">
    <site-hero
      title="Musiques"
      subtitle="Des milliers d'artistes taiwanais à encore découvrir"
      image="/uploads/musiques-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
    <template v-slot:default> 
      <div class="tile is-ancestor">
            <div class="tile is-parent is"><router-link to='/categories/musiques'><button class="button is-dark" style="font-size:30px;">Articles</button></router-link></div>
        </div>
      
      </template>
    </main-section>
  </div>
</template>

<script>
export default {
  name: 'Musiques',
  head() {
    return {
      title: `Musiques | ${this.$siteConfig.siteName}`
    }
  }
}
</script>

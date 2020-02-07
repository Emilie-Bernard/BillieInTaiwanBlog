<template>
  <div id="musiques-page" class="page-wrapper musiques-page">
    <site-hero
      title="Musiques"
      subtitle="Des milliers d'artistes taiwanais à encore découvrir"
      image="/uploads/drama-hero.jpg"
    ></site-hero>
    <main-section theme="one-column">
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

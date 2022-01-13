<template>
  <section>
    <Hero />
    <Why />
    <Types />
    <Stats />
    <CaseStudies />
    <CTA />
    <Contact />
    <Footer />
  </section>
</template>

<script>
import Logos from "~~/components/Logos.vue";
import Footer from "~~/components/Footer.vue";
import VueTyper from 'vue-typer'
export default { components: { Logos, Footer } }
</script>
<style>
html {
  scroll-behavior: smooth;
}
/* Animation */
.anim-typewriter{
  animation: typewriter 4s steps(44) 1s 1 normal both,
             blinkTextCursor 500ms steps(44) infinite normal;
}
@keyframes typewriter{
  from{width: 0;}
  to{width: 24em;}
}
@keyframes blinkTextCursor{
  from{border-right-color: rgba(255,255,255,.75);}
  to{border-right-color: transparent;}
}
</style>

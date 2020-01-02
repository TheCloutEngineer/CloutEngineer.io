<template>
  <Layout>
    <div class="about">
      <div class="about-text">
        <h1>About Me</h1>
        <p>Software Engineer at GSK. Currently, exploring the APIs and cloud development space. I also have experience working on Web Components using <a href="https://lit-element.polymer-project.org/">Lit Elements</a> and <a href="https://material.io/design/">Material Designs</a> by Google on GSK Platforms UI team.</p>
      </div>
      <div class="about-photo">
        <g-image src="~/assets/images/person.jpg" width="300" />
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About Me'
  }
};
</script>

<style lang="scss" scoped>
.about {
  &-text {
    text-align: left;
  }
}
@media screen and (min-width: 768px) {
  .about {
    display: flex;
    flex-wrap: wrap;
    &-text {
      margin-right: 30px;
      max-width: 350px;
    }
  }
}
@media screen and (min-width: 1024px) {
  .about-text {
    margin-right: 50px;
    max-width: 600px;
  }
}
</style>


<template>
  <Layout>
    <article>
      <h1 class="title"></h1>
      <div class="content"></div>
    </article>
  </Layout>
</template>

<script>
export default {
  mounted() {
    console.log(this);
  },
};
</script>

<style scoped>
article {
  padding: 3rem;
}
article h1.title {
}
article .content {
  max-width: 700px;
  margin: 0 auto;
}
</style>

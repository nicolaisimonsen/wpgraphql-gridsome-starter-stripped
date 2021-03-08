<template>
  <Layout>
    <section></section>
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
section {
  padding: 3rem;
}

section article {
  padding: 1.25rem;
  border-radius: 12px;
  box-shadow: rgb(0 0 0 / 10%) 0px 1px 3px 0px, rgb(0 0 0 / 6%) 0px 1px 2px 0px;
  background: rgb(255, 255, 255);
  margin: 30px auto;
}

section article h1 {
  margin-bottom: 0;
  line-height: 1;
}
section article p {
  font-size: 0.85em;
}
section article p span {
  color: #777;
}

section article a {
  margin-top: 15px;
  display: inline-flex;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: center;
  justify-content: center;
  user-select: none;
  position: relative;
  white-space: nowrap;
  border-radius: 0.375rem;
  padding: 15px 40px;
  color: #000;
  text-decoration: none;
  background: rgb(226, 232, 240);
}
section article a:hover {
  color: #fff;
  background: rgb(251, 107, 52);
}
</style>

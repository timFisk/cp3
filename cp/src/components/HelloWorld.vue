<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      I'm not sure how to make this good. I think my site a the link is better.
      <a href="http://notthekid.com/creativeProject/" target="_blank" rel="noopener"
        >notthekid.com</a
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: blue;
}
</style>

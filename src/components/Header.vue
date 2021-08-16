<template>
  <div>
    <ul>
      <li v-for="categorie in header_categories" :key="categorie"><a>{{ categorie }}</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    header_categories: Array
  }
}
</script>

<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>
<template>
  <div class="hello">
    <h1>📝Memopad</h1>
    <section class="textarea-wrap">
      <textarea v-model="text" />
    </section>
  </div>
</template>

<script>

export default {
  name: 'Main',
  data() {
    return {
      text: "",
    }
  },
   
}
</script>

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
  color: #42b983;
}
.textarea-wrap {
  width: 100%;
}

textarea {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: 1.2rem;
  width: 100%;
  height: 200px;
  border: black solid 1px;
  margin: auto;
  padding: 5px;
}
</style>

<template>
  <div>
  <h1>Welcome to StarWarsExplorer</h1>
  <table>
    <tr>
      <th >name</th>
      <th >hair_color</th>
      <th >skin_color</th>
      <th >homeworld</th>
    </tr>
    <tr>
      <td>foo</td>
      <td>bar</td>
      <td>car</td>
      <td>dar</td>
    </tr>
  </table>
    <button class="btn">Load more</button>
  </div>
</template>

<script>
export default {
  name: 'StarWarsExplorer',
  props: {
    msg: String
  }
}
</script>

// TODO:
// 0. Navigate to https://swapi.dev/api and explore the api
// 1. Upon loading this view collect the data from https://swapi.dev/api/people and display it in a table.
// 2. At the bottom of the page add `Load more` button which will fetch more data and append it to the table.
// 3. Make columns `name` and `hair_color` sortable
// 4. Add a date column (%Y-%m-%d) based on `edited` date
// 5. Resolve `homeword` field into the homeworld's name (https://swapi.dev/api/planets/20/ -> Stewjon)


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
  color: #42b983;
}
</style>

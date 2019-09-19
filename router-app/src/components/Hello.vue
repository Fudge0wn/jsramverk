<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{brodtext}}</h3>
  </div>
</template>

<script>
  export default {
    name: 'Hello',
    data () {
      return {
        msg: 'Min Me-app!',
        brodtext: "Hejsan. Här är min blygsamma me-app, skapad med Vue. Jag hoppas kunna göra den finare i senare kmom."
      }
    }
  }
</script>

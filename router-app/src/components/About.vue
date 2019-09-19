<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <h1>{{ msg2 }}</h1>
    <h1>{{ msg3 }}</h1>
    <h2>{{ msg4 }}</h2>
    <h3>{{ msg5 }}</h3>
    <h2>{{ msg6 }}</h2>
    <h3>{{ msg7 }}</h3>
    <h2>{{ msg8 }}</h2>
    <h3>{{ msg9 }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'Reports',
    data () {
      return {
        msg: 'Kmom01 - first me site.',
        msg3: "##Build Setup",
        msg4: "install dependencies:",
        msg5: "npm install",
        msg6: "serve with hot reload at localhost:8080:",
        msg7: "npm run dev",
        msg8: "build for production with minification:",
        msg9: "npm run build"
      }
    }
  }
</script>

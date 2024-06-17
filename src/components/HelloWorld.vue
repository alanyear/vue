//HelloWorld.vue

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <a href="https://www.baidu.com">Go to baidu</a>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

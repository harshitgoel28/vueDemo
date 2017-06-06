<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  <vuep :template="code" :options="{ mode: 'htmlmixed' }"></vuep>
  </div>
</template>
<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Editor',
      code: ''
    }
  }
}
</script>

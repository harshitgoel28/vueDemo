<template>
  <div class="editor">
    <h1>{{ msg }}</h1>
  <vuep :template="code" :options="{ mode: 'htmlmixed' }"></vuep>
  </div>
</template>
<script>
export default {
  name: 'editor',
  data () {
    return {
      msg: 'Editor',
      code: ''
    }
  }
}
</script>

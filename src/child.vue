<template>
  <div>
    <slot :data="items"></slot>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: ['测试1', '测试2', '测试3']
    }
  }
}
</script>


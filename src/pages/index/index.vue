<template>
  <view class="index">
    <text>{{ msg }}</text>
    <button on:click={{ddd}}>click</button>
  </view>
</template>

<script>
import { ref } from 'vue'
import './index.less'

export default {
  setup () {
    const msg = ref('Hello world 1')
    return {
      msg
    }
  }
}
</script>

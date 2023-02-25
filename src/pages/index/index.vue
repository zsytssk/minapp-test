<template>
  <view class="index">
    <text>{{ msg }}</text>
    <button on:click={{ddd}}>click</button>
  </view>
</template>

<script>
import { ref } from 'vue'
import './index.less'
import Taro from '@tarojs/taro'

export default {
  setup () {
    global.Taro = Taro
    const msg = ref('Hello world 1')
    return {
      msg
    }
  }
}
</script>

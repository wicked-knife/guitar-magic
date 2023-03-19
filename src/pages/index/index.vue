<template>
  <view class="content">
    <view>
      <text class="title">{{ title }}</text>
    </view>
  </view>
</template>

<script>
import {Interpreter } from '@/static/e.js'
export default {
  data() {
    return {
      title: "Hello",
    };
  },
  onLoad() {
    console.log(Interpreter);
  },
  methods: {},
};
</script>

<style>

</style>

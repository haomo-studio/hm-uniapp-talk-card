<template>
  <div class="hm-talk-card">
    <div class="head">
      <div class="state">
        <div class="imghead">
          <image class="avator" :src="options.avator" />
          <text class="name">{{ options.name }}</text>
        </div>
        <image class="stateimg" :src="options.stateimg" />
      </div>
      <div class="main">
        <text class="text">{{ options.text }}</text>
      </div>
      <div class="body">
        <div class="block">
          <image class="iconfriendsHelp" :src="options.iconfriendsHelp" />
          <text class="num">{{ options.num }}</text>
          <text class="like">{{ options.like }}</text>
        </div>
        <div class="group">
          <image class="iconTest" :src="options.iconTest" />
          <text class="commentNum">{{ options.commentNum }}</text>
          <text class="comments">{{ options.comments }}</text>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HmTalkCard',
  props: {
    dataId: {
      type: String,
      default: 'hm-talk-card'
    },
    options: {
      type: Object,
      default: function() {
        return {
          avator:
            './images/img_25252_0_2.png',
          name: '黄三环',
          stateimg:
            './images/img_25252_0_3.png',
          text: '1582年，“咖啡”一词通过荷兰语koffie进入英语…',
          iconfriendsHelp:
            './images/img_25252_0_0.png',
          num: '234',
          like: '喜欢',
          iconTest:
            './images/img_25252_0_1.png',
          commentNum: '67',
          comments: '条评论'
        };
      }
    }
  },
  data() {
    return {};
  },
  methods: {}
};
</script>
<style>
@import './index.response.css';
</style>

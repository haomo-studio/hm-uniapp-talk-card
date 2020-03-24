> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 预览

![预览图片](http://downloads.haomo-tech.com/uniapp/hm-talk-card.png)

[在线效果预览](http://template.uniapp.haomo-tech.com/pages/haomo/test-component/hm-talk-card)

更多毫末科技的uni-app跨端模板，请见[毫末科技uni-app跨端模板](https://haomo-tech.com/sale.html)

## 技术支持

* [uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=1482)

* [npm包](https://www.npmjs.com/package/hm-uniapp-talk-card)

* [github地址](https://github.com/haomo-studio/hm-uniapp-talk-card)

* [gitee地址](https://gitee.com/haomo/hm-uniapp-talk-card)

毫末科技将长期迭代本组件。需要技术支持，请进钉钉群（群号30423559）：

<img width="250" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app毫末动态卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

## 使用

请使用HBuilderX导入组件。

在script中引用：

```javascript
import HmTalkCard from '@/components/hm-talk-card/index.vue'
export default {
    components: { HmTalkCard }
}
```

在template中使用：

```html
<template>
  <div class="test-component">
    <hm-talk-card :options="options"></hm-talk-card>
  </div>
</template>
<script>
import HmTalkCard from '@/components/hm-components/hm-talk-card/index.vue'

export default {
  components: {
    HmTalkCard
    },
  data() {
    return {
      options: {
          avator:
            '/static/hm-talk-card/images/img_25252_0_2.png',
          name: '黄三环',
          stateimg:
            '/static/hm-talk-card/images/img_25252_0_3.png',
          text: '1582年，“咖啡”一词通过荷兰语koffie进入英语…',
          iconfriendsHelp:
            '/static/hm-talk-card/images/img_25252_0_0.png',
          num: '234',
          like: '喜欢',
          iconTest:
            '/static/hm-talk-card/images/img_25252_0_1.png',
          commentNum: '67',
          comments: '条评论'
        }
    };
  },
  methods: {
  }
};
</script>
<style>
</style>

```

## 属性说明

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| options        | Object  | -      | 卡片属性                                                                   |

options对象各个属性说明如下：

| 属性名        | 类型     | 默认值 | 说明                                                                       |
|-----------   |---------|--------|----------------------------------------------------------------------------|
| avator        | String  | -      | 头像图片                                                                   |
| name        | String  | -      | 姓名                                                                   |
| stateimg        | String  | -      | 图片                                                                   |
| text        | String  | -      | 内容文字                                                                   |
| iconfriendsHelp        | String  | -      | 图片                                                             |
| num        | String  | -      | 喜欢数量                                                             |
| iconTest        | String  | -      | 评论图片                                                             |
| commentNum        | String  | -      | 评论数量                                                             |

## 事件说明

| 事件称名   | 事件说明           | 返回参数 |
|----------|--------------------|----------|
| @click   | 点击 Card 触发事件 | -        |

## 更新日志

### 0.0.1(2020-03-24)

* 完成第一个版本

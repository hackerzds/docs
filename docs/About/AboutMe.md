---
layout: page
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/XXGGG.png',
    name: '谢夏戈',
    title: 'XXGGG',
    links: [
      { icon: 'github', link: 'https://github.com/XXGGG' },
      { icon: 'twitter', link: 'https://twitter.com/TWI_XXGGG' },
      { icon: 'youtube', link: 'https://space.bilibili.com/5276030' }
    ]
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      👋 我叫 谢夏戈
    </template>
    <template #lead>
    <p>96年。我的编程技术栈大部分是关于Web前端的，目前正在学习更多前端知识以及部分后端知识和计算机知识。本博客正是用于记录我的学习途径和学习进度。</p>
</template>
</VPTeamPageTitle>
<VPTeamMembers
    :members="members"
  />
</VPTeamPage>

---
home: true
heroImage: https://security-1310978225.cos.ap-beijing.myqcloud.com/public/img/home.svg
features:
- title: 实用
  details: 收录互联网中各类文章
- title: 详细
  details: 全面的修复及验证方法
- title: 开源
  details: 每个人都可以自由搭建

head: [
    # ['link', { rel: 'icon', href: 'https://security-1310978225.cos.ap-beijing.myqcloud.com/public/img/home.svg' }],
    ['meta', { name: 'referrer', content: 'never' }],
    ['meta', { name: 'keywords', content: '知识库,漏洞复现,PeiQi文库,代码审计,渗透测试' }],
  ]
---

</br>
</br>
<a-alert type="info" message="提示" description="由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，文章作者不为此承担任何责任。PeiQi文库 拥有对此文章的修改和解释权如欲转载或传播此文章，必须保证此文章的完整性，包括版权声明等全部内容。未经作者允许，不得任意修改或者增减此文章内容，不得以任何方式将其用于商业目的。" showIcon>
</a-alert>

</br>
</br>

<template>
  <a-steps>
    <a-step status="finish" title="Login Github">
      <a-icon slot="icon" type="github" />
    </a-step>
    <a-step status="finish" title="Star">
      <a-icon slot="icon" type="star" />
    </a-step>
    <a-step status="process" title="Reading">
      <a-icon slot="icon" type="loading" />
    </a-step>
    <a-step status="wait" title="Thank">
      <a-icon slot="icon" type="smile-o" />
    </a-step>
  </a-steps>
</template>
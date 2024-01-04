---
layout: blocks
title: Homepage
date: 2024-01-042T23:00:00.000+00:00
page_sections:
  - template: navigation-header-w-button
    block: header-2
    logo: "/uploads/2018/06/21/forestry-full.svg"
    navigation:
      - link: "/"
        link_text: Ubuild
      - link: "#swap"
        link_text: Swap
      - link: "#customize"
        link_text: Customize
      - link: "#responsive"
        link_text: Responsive
      - link: "#blocks"
        link_text: Blocks
    cta:
      url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
      button_text: Import
  - template: hero-banner-w-image
    block: hero-2
    slug: features
    headline: Jo<br><strong>A Jin</strong>
    content: 블로그 입니다.
    cta:
      enabled: true
      url: https://github.com/waiajin
      button_text: "GitHub로 이동"
    image:
      image: "/uploads/2018/06/21/product-shot-1.png"
      alt_text: Product Shot
    background_image: "/uploads/2018/06/21/hero-2-bg.png"
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: swap
    headline:
      <strong>블록 &amp; 블록<span class="light">&nbsp;</span></strong><span
      class="light">에 대한 내용은 여기에</span>
    content: 간략한 세부 설명 요약은 이러이러하다.
    media:
      image: "/uploads/2018/06/21/blocks-split.png"
      alt_text: 블록왼쪽에 들어가는 이미지에 대한 설명
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: customize
    headline: <strong>블록2 진한글씨</strong><span class="light">&nbsp;에 대해서 설명</span>
    content: 블록2에 대한 자세한 세부 설명 및 요약 내용은 여기서 확인하세요.
    media:
      image: "/uploads/2018/06/21/edit.gif"
      alt_text: 블록2에 들어가는 이미지에 대한 설명
  - template: 1-column-text
    block: one-column-1
    slug: responsive
    headline: 16 Fully Responsive Design Blocks
    content: |
      아마 관련된 내용은 여기에 들어갈 것으로 보이고 링크를 달때는 <a href="https://forestry.io">이렇게</a> 코드를 이용해서 답니다.
  - template: full-width-media-element
    block: media-1
    image: "/uploads/2018/06/21/theme.png"
    caption: All Available Blocks
    slug: blocks
  - template: detail-content
    block: text-1
    headline: Steps to Build a Site!
    content:
      <p>uBuild is an open-source Jekyll based demo that doubles as a builder tool inside the Forestry content manager.</p><ol><li><p><a href="https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll">Import this demo in Forestry</a>.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
      article</a> and create your own Blocks.</p></li><li><p>Add and customize the available Blocks and preview them as you go along.</p></li></ol>
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎ Jo A jin
---

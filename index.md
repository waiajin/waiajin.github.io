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
        link_text: 메뉴1
      - link: "#swap"
        link_text: 메뉴2
      - link: "#customize"
        link_text: 메뉴3
      - link: "#responsive"
        link_text: 메뉴4
      - link: "#blocks"
        link_text: 메뉴5
    cta:
      url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
      button_text: Import
  - template: hero-banner-w-image
    block: hero-2
    slug: features
    headline: Jo<br><strong>A Jin</strong>
    content: 블로그 입니다..
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
    headline: 중간에 오는 헤드라인입니다.
    content: |
      아마 관련된 내용은 여기에 들어갈 것으로 보이고 링크를 달때는 <a href="https://forestry.io">이렇게</a> 코드를 이용해서 답니다.
  - template: full-width-media-element
    block: media-1
    image: "/uploads/2018/06/21/theme.png"
    caption: 하단에 보이는 이미지
    slug: blocks
  - template: detail-content
    block: text-1
    headline: 예시 방법입니다
    content: <p>아래에서 설명하는 세가지 방법을 따라주세요.</p><ol><li><p><a href="https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll">첫번째는 링크를 통해 확인합니다</a>.</p></li><li><p>두번째는 <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">링크</a>를 따라 이동합니다.</p></li><li><p>세번째는 이것입니다.</p></li></ol>
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎ Jo A jin
---

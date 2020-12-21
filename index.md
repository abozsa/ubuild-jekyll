---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/12/21/white_on_dark.svg"
  navigation:
  - link: "/"
    link_text: Home
  - link: "#swap"
    link_text: Platform
  - link: "#customize"
    link_text: Industries
  - link: "#responsive"
    link_text: Resources
  - link: "#blocks"
    link_text: Company
  - link: ''
    link_text: We're hiring!
  cta:
    url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
    button_text: Book a demo!
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: Stop attacks at first sight
  content: With our fantastic software
  cta:
    enabled: true
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: Watch Video
  image:
    image: "/uploads/2018/06/21/product-shot-1.png"
    alt_text: Product Shot
  background_image: "/uploads/2020/12/21/c67a9bad-834a-4da3-abec-31cf44f3d619.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: swap
  headline: "<strong>Communication Insights</strong>"
  content: 'ActiveGuard adapts to your organization, learning the required context
    to stop targeted and socially engineered attacks. This context consolidates communication
    profiles of each member of your organization, maps internal, cross-functional
    and external relationships and enables real-time third-party risk assessment.<em>How
    this is applied in practice</em>: Phishing and other kinds of attacks reach employee
    mailboxes because current defenses only look for characteristics that are cheap
    for attackers to change (e.g. SPF) and don’t consider the context of the conversation.
    Communication insights gathered from past conversations enable ActiveGuard to
    know exactly if a given email was sent by a business partner or whether it merely
    imitates such a trusted relationship, for example by using lookalike domains.'
  media:
    image: "/uploads/2018/06/21/blocks-split.png"
    alt_text: uBuild Blocks Mock-Up
- template: content-feature
  block: feature-1
  media_alignment: Right
  slug: customize
  headline: "<strong>Proactive Defense</strong>"
  content: 'ActiveGuard matches the risk profile of every email against the behavioral
    norms of your organization in real-time. Any deviation from the norm is an anomaly
    and triggers a series of configurable actions (e.g. Quarantine). Such an approach
    identifies attacks at first sight, does not depend on any third-party threat intelligence
    data (e.g. signatures) and thus provides truly proactive protection.<em>How this
    is applied in practice to fight phishing</em>: Attackers that aim to phish your
    employees need to embed links into their emails. Comparing link domains with an
    organization’s communication history allows ActiveGuard to deduce relevancy and
    identify links to phishing sites before they appear on any blacklist. Similarly,
    ActiveGuard stopped all Emotet malware attacks against its customers.<em>How this
    is applied in practice to fight malware</em>: The reason why Emotet was so successful
    was the ability of attackers to attach macro-laden documents email conversations
    that their victims had in the past. Emotet however could not fool ActiveGuard.
    Static analysis discovered the dangerous macros in the documents and contextual
    intelligence could show that the sender was neither known nor trusted and such
    attack surface must not be allowed. The second wave of Emotet used encrypted archives
    to bypass detection. ActiveGuard cracked these archives open and discovered the
    attack.'
  media:
    image: "/uploads/2018/06/21/edit.gif"
    alt_text: Customize Blocks
- template: 1-column-text
  block: one-column-1
  slug: responsive
  headline: 16 Fully Responsive Design Blocks
  content: |
    The Design Blocks can be used without Forestry but to harness the power
    of Blocks we recommend using <a href="https://forestry.io">Forestry</a>. Once the site is imported you can immediately
    create new sites and make them fully customizable.
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: All Available Blocks
  slug: blocks
- template: detail-content
  block: text-1
  headline: Steps to Build a Site!
  content: <p>uBuild is an open-source Jekyll based demo that doubles as a builder
    tool inside the Forestry content manager.</p><ol><li><p><a href="https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&amp;provider=github&amp;engine=jekyll"
    target="_blank">Import this demo in Forestry</a>.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/"
    target="_blank">our article</a> and create your own Blocks.</p></li><li><p>Add
    and customize the available Blocks and preview them as you go along.</p></li></ol>
- template: navigation-header
  block: header-1
  logo: ''
  navigation: []
- template: simple-footer
  block: footer-1
  content: Made with ❤︎ in Canada

---

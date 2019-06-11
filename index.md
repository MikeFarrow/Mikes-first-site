---
title: Home
sections:
  - component: hero_block.html
    content: >-
      This is my home page, it tells you a bit about my passions, my work and my
      life.
    section_id: hero
    title: 'Hi, I''m Mike'
    type: heroblock
  - actions:
      - label: Contact Me
        url: contact.html
    component: content_block.html
    content: >-
      This is the "about" excerpt. It can be used to provide a paragraph about
      yourself that people can read on the homepage to get a sense of who you
      are. There also exists a dedicated about page where you can write more
      about yourself for those who are interested.
    section_id: about
    title: About
    type: contentblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 4
    section_id: recent-posts
    title: Recent Posts
    type: postsblock
menus:
  main:
    title: Home
    weight: 1
layout: home
---


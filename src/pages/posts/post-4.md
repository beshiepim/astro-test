---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'My Fourth Blog Post'
pubDate: 2025-01-03
description: 'This post will appear on its own!'
author: 'Astro Learner'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "blogging"]
---
This post should appear with my other blog posts because `import.meta.glob()` is returning a list of all my posts in order to create my list dynamically.

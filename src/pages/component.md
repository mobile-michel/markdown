---
# Example: src/pages/index.md
title: .md file with two components
author: Michel Maillard
age: 57
date: 19 April 2022
layout: ../layouts/pageLayout.astro
setup: | 
  import Author from '../components/author.astro'
  import Biography from '../components/biography.astro'
---
## Component nested

This is a test *.md page.

<Author author={frontmatter.author} age={frontmatter.age}/>

<Biography title={frontmatter.title} date={frontmatter.date}>

  **Some Markdown inside a component**

  {frontmatter.author} lives in Toronto, Canada and enjoys photography.

</Biography>
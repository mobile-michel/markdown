---
# Example: src/pages/index.md
title: Index page
author: Michel Maillard
age: 57
city: St-Cergue, Switzerland
date: 19 April 2022
layout: ../layouts/pageLayout.astro
---
### Hi there!

This is your first markdown page. It probably isn't styled much, although
Markdown does support **bold** and *italics.* 

To learn more about adding a layout to your page, read the next section on **Markdown Layouts.**

{frontmatter.author} is {frontmatter.age} and lives in {frontmatter.city}.

```
{frontmatter.author} is {frontmatter.age} and lives in {frontmatter.city}
```
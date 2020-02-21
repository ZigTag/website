---
date: 2020-02-20T22:10:00-0800
title: "How this website is hosted"
draft: false
---

**Foreword: I am not sponsored, nor endorsed by any of the companies/programs shown here**

#### Introduction

Hello, welcome to my first real blog post. Today, were going over how this website was made. All of it is generated using [Hugo](https://gohugo.io/). Hugo is a program that will generate a website from Markdown files. It makes making a website a breeze, this blogpost was entirely written in markdown.  

All of the source code can be found [here](https://github.com/ZigTag/website).  

#### History

The host originally was [GitHub Pages](https://pages.github.com/), it was kinda a pain to host the website since github expected the `index.html` to be in the top layer of the github repo, so the source code had to be in a seperate repo from the compiled source.

Then I had bought my domain using [Google Domains](https://domains.google/). It was very easy to get working and set up. I had tried to use the domain with GitHub Pages, but I didn't want to read documentation. Then I suddenly remembered that I had seen people use [Netlify](https://www.netlify.com/) before. So I had decided to sign up for it to see what it was all about.

Once I had signed up, it was relatively intuitive to get my git repo hosted using their service. I had to go through some prompts but it wasn't hard. Once I had gotten the git repo set up I had added my domain and they provide a free SSL certificate.

Once all that was done my website was accessable at the proper url and it was all set up properly. It was pretty pain free to get working.
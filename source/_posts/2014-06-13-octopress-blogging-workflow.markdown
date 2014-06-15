---
layout: post
title: "Octopress Blogging Workflow"
date: 2014-06-13 09:57:43 -0500
comments: true
categories: [blog, octopress] 
---

1. Create a new post: ```rake new_post[<Title>]```  

2. Add content by editing ```source/_posts/<date>-<Title>.markdown```

3. Preview changes:
 * If using [Pow](http://pow.cx), run ```rake generate``` and open [octopress.dev](http://octopress.dev) in a browser
 * Otherwise, run ```rake preview``` and open [localhost:4000](http://localhost:4000) in a browser

4. Publish post and push changes to Github:      

        rake generate
        rake deploy
        git add .
        git commit -m "<commit message>"
        git push origin source
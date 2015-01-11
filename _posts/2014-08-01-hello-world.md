---
layout: post 
title : hello world
description : my favourite test string
blog_title : this is a test blog
blog_content : this is a test blog, try to use html5 tags and use template
---
<h2 style="font-color:red"> {{ page.title }}</h2>
 <p style="font-weight:bold"> My First Post</p>
 <p> {{ page.date | date_to_string }}</p>

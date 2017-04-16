---
layout: page
title: Bryan Swan
tagline: Data Developer
---
{% include JB/setup %}



## Works Completed

`https://www.youtube.com/user/swanbryan` You can view my other work
    
    
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do




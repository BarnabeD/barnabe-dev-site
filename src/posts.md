---
layout: page
title: Posts
permalink: /posts/
---

<ul>
  <% site.posts.each do |post| %>
    <li>
      <a href="<%= post.url %>"><%= post.title %></a>
    </li>
  <% end %>
</ul>

If you have a lot of posts, you may want to consider adding [pagination](https://www.bridgetownrb.com/docs/content/pagination)!

<%= link_to 'retour', "index.md" %>

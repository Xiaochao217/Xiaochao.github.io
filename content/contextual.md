---
title: "随机文章"
layout: "single"
---

<script>
fetch('/index.json')
  .then(response => response.json())
  .then(posts => {
    const articles = posts.filter(post => post.permalink);
    const randomPost = articles[Math.floor(Math.random() * articles.length)];
    window.location.href = randomPost.permalink;
  });
</script>

正在随机挑选一篇文章……

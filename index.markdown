<!-- index.md -->
---
layout: home
title: DeepDive
---

<style>
.post-list-heading { 
  font-size: 1.2em; 
  margin-top: 2em; 
  margin-bottom: 1em;
  color: #666;
}

.post-list li a::before { content: "[ "; }
.post-list li a::after { content: " ]"; }

.post-meta { 
  font-size: 0.9em; 
  color: #888; 
  margin-left: 10px;
}

.category-section {
  margin-bottom: 2em;
}

.search-box {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  font-family: inherit;
}
</style>

<!-- <input type="text" class="search-box" placeholder="Search posts..." id="searchBox"> -->

<!-- <div class="category-section">
  <h2 class="post-list-heading">Recent Posts</h2>
  <ul class="post-list">
    {% for post in site.posts limit:5 %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
</div>

<div class="category-section">
  <h2 class="post-list-heading">Mathematics</h2>
  <ul class="post-list">
    {% for post in site.mathematics %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>

<div class="category-section">
  <h2 class="post-list-heading">Computer Science</h2>
  <ul class="post-list">
    {% for post in site.computer-science %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div> -->

<!-- <div class="category-section">
  <h2 class="post-list-heading">Tutorials</h2>
  <ul class="post-list">
    {% for post in site.tutorials %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div> -->

<!-- <script>
document.getElementById('searchBox').addEventListener('input', function(e) {
  const searchTerm = e.target.value.toLowerCase();
  const posts = document.querySelectorAll('.post-list li');
  
  posts.forEach(post => {
    const text = post.textContent.toLowerCase();
    post.style.display = text.includes(searchTerm) ? 'block' : 'none';
  });
});
</script> -->
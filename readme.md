asdvc asdfasdfasx


# 1
asdfasdasdf akjsdghf sd


# 2
asdfsa dfjkasgldhfhjagds fjkasgd

# 3
adsfjhags djhfg askjdfg kasdjhgf 


{% for post in site.posts %}
  <article>
    <h2>
      <a href="_posts/{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.content }}
  </article>
{% endfor %}

# Frank's Website posts
# My Projects
Here is a list of projects that I have been working on
# My Interests
I'm interested in Robotics, Automation, Artificial Intelligence, Drones and many
other technical topics.
# My Blog
I'm really excited to blog my journey on Github.com
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post:title }}</a>
    </li>
  {% endfor %}
</ul>

# Get in Touch
<ul>
  <li>
    <a href="https://github.com/{{ site.github_username}}">GitHub</a>
  </li>
</ul>

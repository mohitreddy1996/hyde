---
layout: page
title: Contact Me
---

Feel free to contact me for any queries/suggestions/discussions or simply for a chat :). I would be more than happy to speak with you.

Contact/Connect with me on any of the following platforms.

<div id="container" style="text-align: center;">
  <ul style="list-style-type: none;">

  	{% if site.emailid %}
      <li style="display: block;">
        <a href="mailto:{{ site.emailid }}" target="_blank">
          <i class="fa fa-envelope"></i> Mail
        </a>
      </li>
    {% endif %}

    {% if site.twitter_username %} 
      <li style="display: block;">
        <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank">
          <i class="fa fa-twitter"></i> Twitter
        </a>
      </li>
    {% endif %}

    {% if site.github_username %}
      <li style="display: block; flex: 0 1 auto;">
        <a href="https://github.com/{{ site.github_username }}" target="_blank">
          <i class="fa fa-github"></i> Github
        </a>
      </li>
    {% endif %}

    {% if site.linkedin_username %}
      <li style="display: block; flex: 0 1 auto;">
        <a href="https://linkedin.com/in/{{ site.linkedin_username }}" target="_blank">
          <i class="fa fa-linkedin"></i> Linkedin
        </a>
      </li>
    {% endif %}

    {% if site.googleplus_username %}
      <li style="display: block; flex: 0 1 auto;">
        <a href="https://plus.google.com/{{ site.googleplus_username }}" target="_blank">
          <i class="fa fa-google-plus"></i> Google Plus
        </a>
      </li>
    {% endif %}

    {% if site.facebook_username %}
      <li style="display: block; flex: 0 1 auto;">
        <a href="https://facebook.com/{{ site.facebook_username }}" target="_blank">
          <i class="fa fa-facebook"></i> Facebook
        </a>
      </li>
    {% endif %}
  </ul>
</div>

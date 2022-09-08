---
layout: default
title: Home
nav_order: 1
description: "to be defined."
permalink: /
---

# Welcome to {{ site.title }}.
{: .fs-9 }

Lorem ipsum dolor sit amet.
{: .fs-6 .fw-300 }

[A colorful button](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } 
[Another button](https://github.com/just-the-docs/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

**New: something bold - See [the link](https://github.com/just-the-docs/just-the-docs/blob/main/CHANGELOG.md) for a detailed breakdown!**

## Getting started

Use inline code `_config.yml` to [do stuff](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/) and also use

```yaml
more: fancy/code
```

<small>write small</small>

Add a line:

---

## About the project

Octo Brocoli was created &copy; 2017-{{ "now" | date: "%Y" }} by [the broccoli crew](http://broccoli.crew).

### License

Octo Broccoli is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email. All content for this page can be found and discussed via our [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>



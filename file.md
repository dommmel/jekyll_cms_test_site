---
layout: default
tags: tasashis
nerds:
- application: kernel
  version: 2.15.asd3
  path: "/usr/local/lib/erlang/lib/kernel-2.15.3"
- application: stdlib
  version: 1.18. asda3
  path: "/usr/local/lib/erlang/lib/stdlib-1.18.3"
- application: sasl
  version: 2.2.1sasasdasdda
  path: "/usr/local/lib/erlang/lib/sasl-2.2.1"
---

{{ page.tags | e }}

<ul>
{% for nerd in page.nerds %}
  <li>{{ nerd.version | e }}</li>
{% endfor %}
</ul>
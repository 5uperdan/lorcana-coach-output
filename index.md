---
title: Lorcana Coach
---

Reviews of danny's games on [duels.ink](https://duels.ink), Disney Lorcana in ranked Core Constructed. Each decision
is judged on what could be known when it was made, not on how the game turned out. Newest first.

{% assign reviews = site.pages | where_exp: "p", "p.path contains 'reviews/'" | sort: "path" | reverse %}
{% for p in reviews %}- [{{ p.title | remove_first: "Review: " }}]({{ p.url | relative_url }})
{% endfor %}

---
layout: page
title: Mustang Sally
subtitle: Mustang LT Amp Tones
description: Mustang LT Amp Tone recipes
---

Welcome to Mustang Sally, a community site for Mustang LT Amp owners to share their own tones with other Mustang LT owners. This site is not affiliated with Fender in any way.

If you want to share you own tones, please take a look at the [Contribute](/mustang-sally/contribute/) page for instructions.

## Latest Tones

<div class="columns is-multiline">
{% assign tones = site.tones | sort: "date" %}
{% for item in tones limit: 3 %}
    <div class="column is-4">
        {% include box.html %}
    </div>
{% endfor %}
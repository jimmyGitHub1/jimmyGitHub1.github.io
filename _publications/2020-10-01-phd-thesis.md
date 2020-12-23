---
title: "Reversing an Imperative Concurrent Programming Language (PhD thesis)"
collection: publications
permalink: /publication/2020-10-01-phd-thesis
excerpt: '<a href="https://leicester.figshare.com/articles/thesis/Reversing_an_Imperative_Concurrent_Programming_Language/12656219">[URL]</a>'
date: 2020-07-15
venue: 'Leicester Research Archive, PhD Thesis, University of Leicester'
citation: 'J. Hoey. Reversing an Imperative Concurrent Programming Language. PhD Thesis, University of Leicester. 2020.'
---
hello this is a single publication

    {% if post.excerpt and site.read_more != 'enabled' %}
    <p class="archive__item-excerpt" itemprop="description">{{ post.excerpt | markdownify }}</p>
    {% elsif post.excerpt and site.read_more == 'enabled' %}
    <p class="archive__item-excerpt" itemprop="description"><p>{{ post.excerpt | markdownify | remove: '<p>' | remove: '</p>' }}<strong><a href="{{ base_path }}{{ post.url }}" rel="permalink"> Read more</a></strong></p></p>
    {% endif %}

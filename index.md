---
layout: page
title: Doma
---

# DOMA

Vítejte na webu pro lidi žijící vzájemně v sousedství a s přáním žít více v komunitě a vzájemné souhře.

Tento komunitní web je určen jako nástroj pro vzájemné zápůjčky nářadí, nástrojů, atd., abyste nemuseli kupovat nic, co nevyužijete častěji. Vzájemně si zde pomůžete, nabídněte, co máte či umíte a naopak. Sdílejte zde rady, návody, hodnocení výrobků v oblasti kutilství. Svolávejte skupinové a další možné aktivity.

## Příspěvky

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-98744071-1', 'auto');
  ga('send', 'pageview');

</script>
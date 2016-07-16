---
layout: default
---

<header class="main-header {% if page.cover %}" style="background-image: url({{ page.cover }}) {%else%}no-cover{% endif %}">
    <nav class="main-nav overlay clearfix">
        <a class="back-button icon-arrow-left" href="{{ site.baseurl }}">Inicio</a>
        <a class="subscribe-button icon-feed" href="{{ site.baseurl }}feed.xml">Subscribirse</a>
    </nav>
    <div class="vertical">
        <div class="main-header-content inner">
            <h1 class="page-title">{{ site.name }}</h1>
            <h2 class="page-description">
                Sobre nosotros.
            </h2>
        </div>
    </div>
    <a class="scroll-down icon-arrow-left" href="#content" data-offset="-45"><span class="hidden">Scroll hacia abajo</span></a>
</header>

This is a static page. It could be an 'about page' if you'd like.

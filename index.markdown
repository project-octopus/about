---
date: 2015-01-20 15:46:03+00:00
layout: page
title: About Project Octopus 
---

About Project Octopus
=====================

Octopus organizes provenance and use information about works found
anywhere on the web, creating the first whole web observatory of
cultural flows and dashboard for creators and fans.

The web is rich with latent provenance information, generated as a side
effect of publishing on the web. But such publication lacks mechanisms
to enrich, correct, search and crosslink provenance information. Even
so, publication may be underutilized as a mechanism for asserting
relationships between agents and works, relative to a dedicated
provenance system with an explicit registration feature.

We are building the Octopus service, which enables its users and
partners to structure and maintain latent provenance information, and to
aggregate use information. Octopus can be thought of as a graph of
provenance information, with at the most basic level, works and
publication contexts as its nodes and relationships among works (e.g.,
adaptation and depiction) and between works and publication contexts
(e.g., on a particular web page) as its edges. Each node and edge has
properties which allow adding and refining information such as the
creator and license of a work, type of adaptation (e.g., a cropped
photo), and additional forms of use information (e.g., views in a
particular publication context).

We think it will be fruitful to create a new provenance system,
dedicated to tracking use of works and sourcing provenance information
from across the web, creating the first whole web observatory of
cultural flows and dashboard for creators and fans — Octopus. The first
phase of Octopus is to build a centralized web site which includes
interfaces for maintaining a basic set of provenance information
concerning digital works and publication. You are now on that site.

Blog
----

<div class="posts">
{% for post in site.posts %}
<article class="post">
<h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
<div class="entry">
<small>{{ post.date | date_to_long_string }}</small> {{ post.content | strip_html | truncatewords:40}}
<a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
</div>
</article>
{% endfor %}
</div>

Team
----

Octopus is a joint initiative of [Kennisland](http://www.kl.nl) and
[PeerPractice](http://www.peerpractice.org). The core team developing
the concept and launching a prototype service by the end of 2014
cumulatively has many decades experience in provenance system
development and policy. It includes:

[Christopher Adams](https://github.com/christopheradams). Developer at
PeerPractice, developer at Fabricatorz with extensive experience
building systems for the art, design, and publishing industries.

[Tessa Askamp](https://www.kl.nl/mensen/tessa-askamp/). Researcher and
organizer at Kennisland focused on open source, copyright, and
licensing.

[Paul Keller](https://www.kl.nl/mensen/paul-keller/). Vice Chair at
Kennisland, Keller is a global leader on copyright, open access, digital
heritage, and new media, and is public project lead for Creative Commons
Netherlands.

[Mike Linksvayer](http://en.wikipedia.org/wiki/Mike_Linksvayer). Advisor
at PeerPractice. Co-founder of Bitzi, an early open data/community
curation provenance system. Also previously Vice President and Chief
Technology Officer at Creative Commons.

[Catharina Maracke](http://www.peerpractice.org/people/). Founder of
PeerPractice, Associate professor at the Graduate School for Media and
Governance, Shonan Fujisawa Campus, at Keio University and fellow at the
Berkman Center for Internet & Society and Harvard Law School. Maracke
previously served as International Director at Creative Commons.

[Jon Phillips](http://en.wikipedia.org/wiki/Jon_Phillips). CTO at
PeerPractice, founder of Fabricatorz and founder of Openclipart, the
largest community curated vector art repository. Previously Community
Director at Creative Commons.

[Maarten Zeinstra](https://www.kl.nl/mensen/maarten-zeinstra/).
Technology broker and copyright advisor at Kennisland, projects include
Europeana, Communia, Creative Commons, outofcopyright.eu, openimages,eu,
and Images for the Future.

[Kennisland](https://www.kl.nl/) is an Amsterdam based think tank with
more than 10 years of experience in licensing systems for the cultural
heritage sector. Kennisland has been working with individual
institutions as well as aggregation platforms such as
[Europeana](http://www.europeana.eu) and the [DPLA](http://dp.la) to
develop and deploy rights information systems.

[PeerPractice](http://www.peerpractice.org) is a boutique consulting
firm specialized in international intellectual property and information
technology law as well as related legal, management and policy
strategies.

Join us
-------

Submit urls to your creative works, especially if they have been used
somewhere: [project-octopus.org](http://project-octopus.org) or Poke
around our [source code](https://github.com/project-octopus) :). You can
also follow us [on twitter](http://twitter.com/helloocto).



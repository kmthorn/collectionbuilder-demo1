---
title: Glossary
layout: about
permalink: /glossary.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---


<!-- How should I be thinking about coding this layout design with a mobile first approach? Whenever I have two columns the text doesn't wrap because it's contained in its own column. My goal is to not have a lot of white space under the image, and to have the text wrap to go underneath it. -->
<div class="row about-narrow">
<div class="col-md-5" markdown="1">
## About the Digital Exhibit

This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.

The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti. Later they became collector’s items, and by the middle of the 19th century they had become miniature masterpieces of woodblock printed art. Senjafuda depict a dizzying variety of themes with meticulous craftsmanship and vivid, stylish graphic design.

Yōkai simply means “monster,” but it’s best understood as referring specifically to monsters (and sometimes ghosts) as imagined in early modern Japan, particularly as depicted in wood-block prints. From Mizuki Shigeru to Studio Ghibli, from The Ring to Yōkai Watch, Japanese popular culture (including anime, manga, books, and film) is full of yōkai imagery.

The University of Oregon’s collection of senjafuda is one of the largest in the world. It includes many senjafuda depicting yōkai. This exhibit uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.

</div>
<div class="col-md-7" markdown="1">
{% include feature/image.html objectid="coll001" width="100" %}
{% include feature/image.html objectid="coll002" width="100" %}
{% include feature/image.html objectid="coll003" width="100" %}
{% include feature/image.html objectid="coll004" width="100" %}
</div>
</div>

<!-- Trying to figure out how to have a 2 row with first row containing two col. The second row contains only 1 col.-->
<div class="row about-narrow">
<div class="col-md-6" markdown="1">
{% include feature/image.html objectid="coll002" width="100" %}
</div>

<div class="col-md-5 about-imgpara" markdown="1">
## MEHHHHH About the Collections
This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.
</div>
</div>

<div class="row about-narrow py-1">
<div class="col" markdown="1">
The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti. Later they became collector’s items, and by the middle of the 19th century they had become miniature masterpieces of woodblock printed art. Senjafuda depict a dizzying variety of themes with meticulous craftsmanship and vivid, stylish graphic design.

Yōkai simply means “monster,” but it’s best understood as referring specifically to monsters (and sometimes ghosts) as imagined in early modern Japan, particularly as depicted in wood-block prints. From Mizuki Shigeru to Studio Ghibli, from The Ring to Yōkai Watch, Japanese popular culture (including anime, manga, books, and film) is full of yōkai imagery.

The University of Oregon’s collection of senjafuda is one of the largest in the world. It includes many senjafuda depicting yōkai. This exhibit uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.
</div>
</div>
<div class="row">
<div class="col-md-12 mt-2 text-center">
    <p class="text-dark">
        <small><em>built with</em>
            <a href="https://collectionbuilder.github.io/" target="_blank" rel="noopener" title="CollectionBuilder">
                <img src="{{ '/assets/img/collectionbuilder-logo.png' | relative_url }}" class="img-fluid" alt="CollectionBuilder logo" >
            </a>
        </small>
    </p>
</div>
</div>



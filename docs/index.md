---
layout: default
title: Home
---

{% include homepage/hero.html %}

{% include section-main.html
   title="What Is SOUL?"
   markdown="home-introduction.md"
   bg="mountains.jpg"
   link="/about/introduction.html"
   button="Read the Full Introduction"
   flip="md:flex-row" 
%}

{% include section-main.html
   title="Our Philosophy"
   markdown="home-philosophy.md"
   bg="teamwork.jpg"
   link="/about/philosophy.html"
   button="Explore the Philosophy"
   flip="md:flex-row-reverse" 
%}

{% include section-main.html
   title="Radical Transparency"
   markdown="home-transparency.md"
   bg="transparency.jpg"
   link="/about/transparency.html"
   button="View Our Pledge"
   flip="md:flex-row" 
%}

{% include section-main.html
   title="Get Involved"
   markdown="home-quick-start.md"
   bg="network_2.jpg"
   link="/get-started/quick-start-guide.html"
   button="Quick-Start Guide"
   flip="md:flex-row-reverse" 
%}

{% include homepage/contact.html %}


---
layout: default
---

{%assign discord = site.data.siteconfig[0] %}
{%assign linkedin = site.data.siteconfig[1] %}
{%assign twitter = site.data.siteconfig[2] %}
{%assign medium = site.data.siteconfig[3] %}
{%assign litepaper = site.data.siteconfig[4] %}
{%assign webapp = site.data.siteconfig[5] %}
{%assign video = site.data.siteconfig[6] %}

<!-- <Home Card> -->

 <div class="land">
  <section class="land_formsection">
    <h1 class="text--bold">Building a safer web 3.0 future for all</h1>
    <p>Ending scam &amp; spam in crypto once and for all.</p>
  </section>
  <div class="land_links">
    <ul>
      <li><a href="{{webapp.link}}" target="_blank" rel="noopener noreferrer" class="link button">TRY THE DEMO</a></li>
      <li><a href="{{litepaper.link}}" target="_blank" rel="noopener noreferrer" class="link button">Lite Paper</a></li>
    </ul>
  </div>
  <img class="land_image" src="{{'/assets/images/splash-logo.webp' | relative_url}}"
    alt="Chocolate X Polkadot and Kusama">
  </div>
  


<!-- <Home Card/> -->


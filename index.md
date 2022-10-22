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
  <div class="supporters">
    <h2 class="text--bold">Supporters</h2>
    <div class="div-crop">
    <a class="flex" target="_blank" href="https://substrate.io/ecosystem/substrate-builders-program/"><img class="sbp-image" src="https://avatars.githubusercontent.com/u/79968355?v=4" alt="sbp-logo"/></a>
    </div>
  </div>
  <div class="container_last">
    <iframe src="https://embeds.beehiiv.com/fa097289-2153-4053-98fe-67403641861d" data-test-id="beehiiv-embed"
      width="100%" height="400" frameborder="0" scrolling="no" style="margin: 0; background-color: transparent"></iframe>
  </div>

<!-- <Home Card/> -->

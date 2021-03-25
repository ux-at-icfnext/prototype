---
title: Home
permalink: /

layout: home

hero:
  image: https://via.placeholder.com/2048x820.png
  callout:
    alt: "Placeholder:"
    text: This is the default hero
  button:
    href: /callout/
    text: Placeholder
  link:
    text: Link to more about that priority
    href: /link/
  content: USWDS doesn't have a slider -- that will be custom. This is just to demostrate out of the box functionality.

card:
  - heading: "Find Treatment"
    body: "Millions of Americans have a substance use disorder."
    button: "Find a facility near you"
    image: "https://via.placeholder.com/80x60?text=image"
    image-alt: "My Image"
  - heading: "National Suicide Prevention Lifeline "
    body: "Free and confidential support for people in distress, 24/7."
    button: "1-800-273-TALK (8255)"
    image: "https://via.placeholder.com/80x60?text=image"
    image-alt: "My Image"
    card-type: "usa-card--flag"


---

{% include snippets/gethelp.html %}
{% include snippets/topics.html %}
<div class="grid-container">
    <div class="grid-row">
        <div class="tablet:grid-col-6">{% include snippets/publicmessages.html %}</div>
        <div class="tablet:grid-col-6">{% include snippets/practitioner-training.html %}</div>
    </div>
</div>



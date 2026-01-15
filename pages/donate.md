---
title: Donate to {B/qKC}
layout: about
permalink: /donate/
# include CollectionBuilder info at bottom
credits: true
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
position: center
# major heading to display over featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
---

# Supporting this archive

{B/qKC} is a fiscally-sponsored artist project. {B/qKC} is kept open by people like *you* who choose to donate to this work. By limiting the people we accept donations, grants and sponsorships from, we remain accountable to the people who truly believe in our work.

We have had over 100+ donations in the two years before launching this website in early 2026. We would *love* to encourage folks to contribute monthly/regularly.

The options below are through {B/qKC}'s fiscal sponsor, The Field. Your donation through this organization will be registered as tax-deductible. 

*Please contact us for more donation options.*

---
## Our donors

*Thank you to our long list of donors to-date. Every donation has allowed this project to bloom in new directions.*

<ul class="donor-list">
  {% for donor in site.data.donors %}
    {% assign date_parts = donor.donation_date | split: "/" %}
    {% assign year = date_parts[2] %}

    <li>
      {{ donor.donor_first }} {{ donor.donor_last }}, {{ year }}
      {% if donor.message_to_artist %}
        <br><em>{{ donor.message_to_artist }}</em>
      {% endif %}
    </li>
  {% endfor %}
</ul>


---
## Our grantors and sponsors

*Thank you to our granting and sponsoring organizations, who have believed in the power of this work.*

### Sustaining

$40,000 (total commitment) <br>
**Rooted Power Fund** – Annual Sustainability Grant

### Major

$15,000 <br>
**The Opportunity Agenda** – Culture & Narrative Fellowship

$8,500 + "DWeb For Creators" course ($2500) + consulting<br>
**Gray Area, TechSoup, and Filecoin Foundation for the Decentralized Web** – Cultural Memory Lab

$9,000 <br>
**The University of Kansas** – Stories For All Grant

### Supporting

$5,000 <br>
**Diaspora Solidarities Lab** – Community Fellows Program

$4,000 + in-kind event space usage <br>
**Blaqout** – *sponsorsed events for 2023/2024*

$3,500 <br>
**ArtsKC** – Inspiration Grant

$1,000 <br>
**Health Forward Foundation** – *sponsor of popular education series* <br>
**Vivent Health** – *sponsored events for 2023/2024*

### Community

**Bay Area Video Coalition** <br>
**Tintoretta Tattoo Studio** <br>
**Charlotte Street** <br>

---

*Thank you to Astringent Press, Oddities Prints, Plot Twist Consulting, BLK + BRWN., PH Coffee, Waterbird Coffee, and Café Corazón who have offered in-kind support to this work!*

---


## Organizations looking to sponsor or donate
Any organizations looking to support this work should contact us directly. Please us the button below to email us.
<div style="text-align: center; margin: 2rem 0;">
  {% include feature/button.html 
     text="Inquire" 
     link="mailto:nasiranthonymontalvo@gmail.com" 
     color="success" %}
</div>

---

## Donating my material to the archive
We are currently able to digitize materials related to Soakie's! 

Unfortunately, we are not readily available to digitize additional archival materials at this time, but hope to soon! This project has traditionally been pursued in volumes, and it is the current mission of {B/qKC} to permanently memorialize Soakie's in various shapes and forms.

For information on our digitization policy, please contact us.

<div style="text-align: center; margin: 2rem 0;">
  {% include feature/button.html 
     text="Inquire" 
     link="mailto:nasiranthonymontalvo@gmail.com" 
     color="success" %}
</div>

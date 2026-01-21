---
title: Data
layout: about
permalink: /data/
toc: true
custom-foot: js/table-js.html
about-featured-image: starlacoll012
# set background-position for featured image, "center", "top", "bottom"
position: center
# major heading to display over featured image
heading: "Our Data"
# paragraph text below heading in featured image
sub-heading: a deep dive into {B/qKC}'s decentralized, digital archival methods
padding: 6em
---

# Charting a new path forward for digital community archives!
In accordance with our [mission](/about/), {B/qKC} aims to be the *true* steward of our archive, and make this database openly accessible for years to come. 

Rather than relying on a third-party service like Google, DropBox, or Squarespace–with rising costs for usage and ethical concerns around our data and their corporate practices–we've chosen to build this site using **open, decentralized and self-hosted infrastructure**.

## Huh? Why all this in the first place?

It's hard to imagine our world without central governing authorities–which has ultimately translated to how a majority of us use the web. 

Need to search something? You Google it. <br>
Need to share something online? You Tweet or Instagram it. <br> 
Need to store something? You upload them to an arbitrary "cloud."

<div class="float-img float-right">
<blockquote class="quote-box">
  <p class="quote-text">“The platforms that host our networked public sphere and inform us about the world are unelected, unaccountable, and often impossible to audit or oversee.”</p>
  <p class="quote-attrib">— Chelsea Barabas, Neha Narula, Ethan Zuckerman,<a href="https://www.dci.mit.edu/projects/the-decentralized-web-defending-internet-freedom-through-decentralization-back-to-the-future" target="_blank"> "The Decentralized Web: Defending Internet Freedom through Decentralization: Back to the Future?" (2017)</a>
</p>
</blockquote>
</div>

We won't deny these haven't been positive developments in some ways. Billions of people across the World have access to the Web in ways we never have before, without at all having to become experts. But therein lies the problem.

Ease of use has translated into intense consolidation of the internet. Just a few companies (Meta, Alphabet Inc., Amazon) have control over most of the web, meaning they can also control:

- what users get access,
- what content is promoted or hidden,
- and whether entire archives can disappear overnight.

Billionaire Elon Musk, for example, infamously purchased Twitter in October 2022 for $44 billion, and became its CEO. With nothing standing in his way besides capital, Musk was able to completely reinvent, albeit extremely controversially, one of the web's most used applications–all the while aligning himself with political leaders in the process.

However, there is a growing movement to "decentralize the web" by divorcing from these corporations and using technology to put power into the hands of the people.

## So what does "decentralized" mean here?

At its core, **decentralization means distributing power instead of concentrating it in one place**.

In a centralized system, a company, like Google, for example, owns massive data centers, their own proprietary software, and sets the rules for how users will engage with their materials–including how they can use our data in exchange for the use of their services.

In 2022, Alphabet (Google’s parent company) made [$224 billion](https://proton.me/blog/google-privacy-washing)–nearly 80% of its total revenue–from advertising: which includes Google Search, Google networks, and YouTube ads. Our personal data directly fuels this advertising revenue.


<div class="image-container">
<img src="/assets/img/Centralized-Vs-Decentralized-Vs-Distributed-systems.png" alt="a blue diagram with three different topologies illustrating the differences between centralized, decentralized and distributed networks." class="img-fluid">
<figcaption class="figure-caption text-center text-muted">
    An overview of centralized, decentralized, and distributed networks, illustrating the key differences in their structures and control mechanisms. In a centralized network, all nodes are connected under a single, central authority In a decentralized network, no single authority server controls the nodes; they operate with individual entity, typically with multiple hubs. (Truong, Nguyen & Jayasinghe, Upul & Um, Tai-Won & Lee, Gyu Myoung. (2016). A Survey on Trust Computation in the Internet of Things)
</figcaption>
</div>

<br>
We've deliberately gone against a centralized framework–opting for open-access tools and a decentralized storage model that allows us to remain in control of our data and share it with you (and of course, keeps yours safe while you browse).

---
# How this website works (in plain language)

This archive might look like a regular-degular website, but under the hood, it's built very differently and with deep intention!

## 1. The Website – Built with CollectionBuilder (Lib-Static methodology)

<div class="image-container">
    <img src="/assets/img/lib-static-values.png" alt="a table explaining the Lib-Static Methodology, broken into four keypoints." class="img-fluid">
    <figcaption class="figure-caption text-center text-muted">
        Collection-Builder is a project meant to follow the Lib-Static approach. The Lib-Static approach, created in 2018 by Evan Williamson, Devin Becker and Olivia Wikle, "focuses on practical, sustainable workflows using data-driven static web templates hosted on simplified infrastructure while leveraging (and building) the in-house specialized skills of librarians in metadata, data, and organization. This provides librarians unique agency and ownership over their systems, as well as meaningful opportunities for professional development leading to fundamental digital skills." (Lib-Static)
    </figcaption>
</div>


<br>
To start, this website is built using an open source tool called [CollectionBuilder](https://collectionbuilder.github.io/). Created by librarians at the University of Idaho, CollectionBuilder is a set of flexible, static web templates that are populated purely from our archive's metadata.

This means:
- There's no third-party service involved: bye-bye annual subscription fees and murky T's & C's!
- Pages are simple HTML files, allowing for more useabiltiy and access!
- The site is pretty fast (you let us know!), stable, and inexpensive to maintain!

## 2. The Archive – Files being served via IPFS (InterPlanetary File System)

<div class="image-container">
<img src="/assets/img/Centralized-data-storage-system-vs-IPFS-interplanetary-file-system-1-1024x576.webp" alt="" class="img-fluid">
<figcaption class="figure-caption text-center text-muted">
    A graphic illustrating the fundamental differences between a traditional centralized client-server system and the decentralized architecture of the InterPlanetary File System (IPFS). (Extrimian, "IPFS (InterPlanetary File System) Wiki," 2024)
</figcaption>
</div>

<br>
All of the images, media and data files part of {B/qKC} are being loaded from the [InterPlanetary File System (IPFS)](https://ipfs.tech/), a decentralized peer-to-peer file system.

Instead of files living on one server in one massive data center:
- files each get their own unique "fingerprint,"
- mulitple copies of these files can exist across different nodes in the IPFS network,
- no single entity controls access to IPFS.

This makes our archive highly resistant to deletion or takedown, and ensures files remain accessible even if a node in the network goes down. That also means if this website were to shutdown, the archive would still be accessible!

## 3. The Cloud – We run our own digital space

<div class="image-container">
<img src="/assets/img/internet_topologies_with_ynh-0393b688fbcafc252b94fa13ef9635c6.png" alt="" class="img-fluid">
<figcaption class="figure-caption text-center text-muted">
    A graphic from YunoHost illustrating the concept of "self-hosting": meaning, in this case, owning and administrating your own server, typically at home, to host your personal data and services yourself instead of relying exclusively on third parties. (YunoHost Docs, "About self-hosting")
</figcaption>
</div>

<br>
This website is self-hosted on our own physical server using [YunoHost](https://doc.yunohost.org/en/admin/about_self_hosting/#:~:text=Self%2Dhosting%20means%20owning%20and%20administrating%20your%20own,instead%20of%20relying%20exclusively%20on%20third%20parties)–an open-source technology designed to make ethical self-hosting possible.

This means no Amazon Web Services, no Google Cloud, no third-party entity quietly watching your traffic or collecting data from you.

By choosing to host this website on our server, we get to control how this site operates, how data is handled, and stay accountable to the people whose stories live here.

<blockquote class="quote-box">
  <p class="quote-text">GOOD TO KNOW: {B/qKC} uses the 3-2-1-1-0 preservation strategy: meaning there are 3 copies of all our archival materials (2 of these on IPFS and our server), stored on 2 different types of media, with 1 copy off-site, 1-copy offline, and all with 0 backup errors.</p>
</blockquote>

---

# Our ultimate why

## We refuse to help Big Tech power destructive data centers and use our data for nefarious ends.  

In the 2020's, alone, we've seen Big Tech's concentrated, profit-driven power consistently put technological advancements over human beings. Some stark examples:

- [Google and Amazon's Project Nimbus](https://tech.co/news/what-is-project-nimbus-google): a $1.2 billion contract between Google and Amazon with the Israeli government and its military, signed in 2021, aiming to provide cloud computing infrastructure, artificial intelligence (AI) and other technology services for its war on Gaza

- [ICE and Palantir use 'probability' to detain people](https://newrepublic.com/post/205333/ice-palantir-app-raid-deportation): Palantir helped developed an application for ICE as part of a $29.9 million agreement called "Enhanced Leads Identification & Targeting for Enforcement (ELITE)": described as "a targeting tool designed to improve capabilities for identifying and prioritizing high-value targets through advanced analytics."

- [Data Center boom will excaerbate Earth's deterioration](https://news.cornell.edu/stories/2025/11/roadmap-shows-environmental-impact-ai-data-center-boom): Cornell researchers have found that, by 2030, the current rate of AI growth would annually put 24 to 44 million metric tons of carbon dioxide into the atmosphere, the emissions equivalent of adding 5 to 10 million cars to U.S. roadways. It would also drain 731 to 1,125 million cubic meters of water per year–equal to the annual household water usage of 6 to 10 million Americans. 

## We choose to remain the stewards of our stories.

We must continuously ask ourselves who benefits from our technological uses, and who stands most at-risk.

As a Black queer digital community archive, we push against the notion that technological advancement is worth losing our planet and the people within it.

For archivists and memory workers (or otherwise) looking for advice on how to "deGoogle" their collections, please reach out!

{% include feature/button.html text="Contact Us" link="/contact/" color="success" %}

<br>
# Archival Metadata (check out our [Copyright & Terms](/copyright/) before you download!)
The table below provides sorting and basic search of the archive's contents. 
Use the "CSV" button below to download the filtered metadata you see on the page. 
Alternatively, click the "Download" button at the top right to view the full archive's metadata in various formats. 


{% include data-download-modal.html no_toc=true %}

{% include data-table.html %}

---
layout: submissions
---

## EDRLab: Position Paper


### About EDRLab and its BDCoMa WG


The European Digital Reading Lab (EDRLab) is a development lab whose aim
is to deploy a set of open and interoperable digital publishing
technologies in Europe, around an open, flexible and accessible standard
applicable to all kinds of digital publications. EDRLab is member of the
W3C and a major contributor to the future Web Publications (WP) / EPUB 4
standards.

In June 2017, EDRLab gathered several actors linked to the comics
industry to discuss their needs respective to the **digital publishing
of visually-rich stories**. Spanning the whole spectrum from publishers
to developers of authoring tools, reading systems and digital platforms,
including authors and public libraries, all stakeholders agreed on the
following observations and issues, which led to the creation of the BD
Comics Manga Working Group (BDCoMa WG) and the definition of specific
goals.

In practice, the BDCoMa WG aims to pursue the constant, long-term effort
started in 2013 by former IDPF members in the framework of regular
conferences (Frankfurt, IDPF BEA, EPUB Summit...) and the first IDPF
Workshop on Sequential Art held in 2014.

### Observations: a booming but fragmented market

Although the ebook market grows at different rates - and has therefore
reached different levels of maturity - in different parts of the world,
regional ebook markets are formally similar and essentially rely on
"homothetic" publications produced in the EPUB 2 or EPUB 3 format, i.e.
digital reproductions of the paper book equivalents without any form of
enrichment. By contrast, the visual narrative market grows extremely
fast but remains split into **multiple local markets**.

-   In Japan, the digital manga market is mainly homothetic and
    EPUB-based, accounting for about 50% of the whole 3.5B€ manga
    market.
-   In the US, digital publications represent an estimated 17% of all
    comics and graphic novel sales (10% by title + 7% by subscription).
    The market is dominated by ComiXology (Amazon) and other
    subscription-based publisher platforms relying on a proprietary
    format.
-   The 500M€ French-Belgian market has not yet reached the milestone of
    a 2% conversion rate from print to digital. Authors mostly publish
    natively digital comics on free platforms, sometimes still
    Flash-based.
-   In South Korea, the successful monetization of webcomic blogs
    spurred the growth of the "webtoon" market which, after less than 10
    years, is now estimated to have the same value as the French-Belgian
    one. The webtoon revolution is currently spreading to Japan, China
    and the rest of South Asia, but also the US, absent any efforts to
    standardize the format.

It should be noted that some large-scale digital productions - produced
in non-EPUB formats - have already gained major recognition, as
evidenced by both international awards (International Angouleme
Festival, Eisner Awards, Apple Design Awards\...) and sale figures, with
numbers going up to several million copies.

### Issues: a lack of standardization

-   **The weight of proprietary solutions implies that readers are
    mostly captive to the digital platforms where they choose to buy and
    read comics**. Nothing guarantees that the situation will remain the
    same in the coming years, especially since publishers do not
    necessarily benefit from keeping exclusive relationships with
    specific digital platforms, and sometimes even refuse to publish
    major intellectual properties on them.
-   **There exists no technical standard for expressing the variety of
    visual narratives (comics, manga, bande dessinée, webtoons and other
    scroll-based comics, turbomedia, etc.) in a digital form**, which
    effectively accounts for the weight of proprietary solutions. The
    EPUB format does not seem to have met the needs of both authors and
    publishers so far, with the exception of homothetic digital manga in
    Japan.
-   After 25 years of experimentations in the field of digital creation,
    we now have a large enough body of use cases to define precisely
    what needs should be met and draw a line between what can be
    standardized and what must remain out of scope.

### Goals

Based on the above, EDRLab formed the BDCoMa WG to **propose a standard,
universal language for expressing digital graphic stories** with 4 very
clear objectives:

-   The very first main goal is to ensure publishers and authors that
    the **visual experience** they want readers to have will be
    perfectly rendered to them;
-   Allow publishers to **industrialize the creation of simple to
    visually complex digital comics** by drastically diminishing their
    production costs;
-   Favor the production and distribution of publications and associated
    metadata on the **greatest possible number of platforms** and make
    them accessible via the **greatest possible number of devices
    (including Readium based reading applications)**;
-   Ensure that publications can be sold and read **forever**,
    independently of the evolution of software technologies.

### Guiding Principles

To do so, the BDCoMa WG made 2 core technical choices:

-   The format for digital comics needs to **build on existing
    standards**. The work being carried out on Web Publications and EPUB
    4 will represent a huge achievement for standardized digital
    publications. It already provides answers to many issues facing a
    publisher willing to express their works in a digital language. The
    format for digital comics should therefore be seen as **an extension
    of WP/EPUB 4 dedicated to visually-rich documents beyond
    Fixed-Layout EPUB**.
-   The format needs to **rely on a declarative approach**. This way, it
    is up to the reading device to implement its own reading software,
    which ensures that the evolution of technologies in general and
    computer languages in particular does not make it impossible to read
    a document in the future. Only reading systems will need to be
    maintained with backward compatibility in mind, not the publications
    themselves.

### Output

This explains why the BDCoMa WG will refer to the format for which it
established a number of specifications as an "**EPUB 4 for comics**".
Technically, it consists in an EPUB package containing a JSON file
describing the story, a few HTML files and a number of separate resource
files (images, video, audio, text, etc.).

Besides the short-term needs for the digital expression of visual
narratives, the BDCoMa WG believes that those specifications will also
be useful to other forms of rich publications: audiobooks, picture
books, cookbooks, poems, magazines, educational materials, etc. The
format could even be the basis for open source slideshow presentations.

### W3C Tokyo Summit Presentation

We therefore propose:

-   to describe the scope of the BDCoMa WG's work, meant to meet the
    needs that the group identified based on specific use cases;
-   to present an introduction to the specifications that the WG
    developed and detail the roadmap established with the official
    support of international publishers;
-   to showcase innovative technologies and prototypes currently being
    developed at different levels of the book chain industry, from
    authoring tools to reading engines;
-   to discuss the BDCoMa WG's technical choices with the variety of
    attendees (W3C members, publishers, industrial partners\...), in
    particular the possibly controversial implications of a declarative
    approach.

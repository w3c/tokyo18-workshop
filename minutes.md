---
layout: home
---

# Workshop on Digital Publication Layout and Presentation — Minutes
{: .no_toc}



**Date:** 2018-09-18, 2018-09-19

See also the [Agenda](https://www.w3.org/publishing/events/tokyo18-workshop/schedule.html) and the [IRC Log](https://www.w3.org/2018/09/17-tokyows-irc.txt)

## Attendees
{: .no_toc}
**Present:** Ivan Herman, Bobby Tung, Reinaldo Ferraz, Brian Birtles, Richard Ishida, Rachel Andrew, Laurent Le Meur, Rachel Nabors, Vincent Wartelle, Elika Etemad, Shinya Takami, Toshiaki Koike, Jun Gamo, Nathaniel McCully, Shinsuke Inamori, Luc Audrain, Mitsuhiro Nakao, Tomoyuki Kudou, Hiroshi Tanaka, Katsuhiro Ogata, Hiroshi Takase, Yasuhiro Kanai, Tsuneyoshi Kamae, Makoto Murata, Wendy Reid, Shinyu Murakami, Samuel Petit, Florian Rivoal, Florian Dupas, Yu-Wei Chang, Tatsuo Kobayashi, Yasuo Kida, Daihei Shiohama, Junichi Yoshii, Myles Maxfield, Jean-Christophe Burie, Koji Ishii, Pablo Defendini, Wen Hsi Yeh, Satoko Takahashi, Dave Cramer, Theresa O’Connor, Hyunwoo Nam, Marius Bredsdorff, Stanley Chien, Ming Shing Kuo, Hiroki Kamata, Junko Kamata, Yukio Tomikura, Chenchung Chien, Taro Yamamoto, Kazuyuki Ashimura, Masaki Itou, Atsushi Shimono, Yuichi Kinoshita, Naomi Yoshizawa, Mike Smith, Hui Jing Chen

**Chair:** Luc Audrain, Florian Rivoal, Makoto Murata

**Scribe(s):** Kazuyuki Ashimura, Dave Cramer, Elika Etemad, Florian Rivoal

## Content:
{: .no_toc}

* TOC
{:toc}
---


### 1. Introduction
{: #section1}

> *Kazuyuki Ashimura:* Florian gives logistical information including the lunch and the reception.

### 2. W3C Welcome (Ivan Herman)
{: #section2}

> *Ivan Herman:* See [slides online](https://www.w3.org/2018/Talks/Tokyo-IH/Presentation.pdf)

**Ivan Herman:** give brief introduction on what the W3C is like  
… work at W3C is based on the cooperation of Members  
… consensus is the center of our discussion  
… "W3C" doesn't develop standards; "W3C Members" do  
… AC Rep. to serve as liaison to W3C  
… Advisory Board (AB) is elected by W3C Membership and meets quarterly with the W3C CEO  
… Technical Advisory Group (TAG) with a focus on the architecture of the Web  
… also note the W3C Royalty Free Patent Policy  
… horizontal reviews  
… accessibility, internationalization, privacy, and security  
… publishing@w3c  
… publications as first class entities on the Web  
… broadening W3C Membership - many companies involved  
… history  
… W3C and IDPF cooperation since 2013  
… established an IG  
… W3C was also part of the IDPF/IMS "EDUPUB" initiative  
… and then W3C and IDPF are "merged" in Feb. 2017  
… publishing@W3C groups: Publishing BG, EPUB 3 CG, Publishing WG  
… actually more  
… number of issues  
… relevant to publishing but not only for publishing  
… e.g.:  
… pagination and general page control - CSS  
… accessibility - ARIA, AG  
… goal of the workshop  
… identify the technical problems and features that should be worked on in one of the existing W3C WGs  
… hopefully identify experts that can join the group to do the work  
… if such a group doesn't exist, discuss whether a separate WG needed  
… how W3C works  
… Members move things forward!  

> *Elika Etemad:* Ivan shows a photo of a conference panel: this is not how W3C works. It's not a bunch of experts giving opinions.

> *Elika Etemad:* Ivan shows a photo of a conference table with a variety of people sitting around it and lots of computer paraphernalia: This is how W3C works. It is a collaborative effort, everyone working together, lots of coffee and tea.

### 3. Current Status and Pain Points
{: #section3}

#### 3.1. The diversity of E-publishing worldwide (Luc Audrain)
{: #section3-1}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/UnfixedFixedLayout20180918.pdf)

**Luc Audrain:** where are we in digital publications?  
… we have success with reflowable epubs  
… but what about complex books?  
… we have EPUB fixed layout (FXL)  
… we could not do this kind of book without FXL  
… our first FXL book was in 2011  
… we have now produced many thousands of FXL books  
… one example is education, where the pedagogy is "inside the layout"  
… and we have comics/manga  
… some books have many images, so each page is just an image  
… and others have text + images, so the text is still searchable  
… (covers technical details of FXL)  
… "digital sequential art"  
… there was ascii art before there was html  
… now there is turbo media, webtoons, applications  
… there's a worldwide market, but with lots of diversity  
… EPUB used in japan for manga, proprietary formats in US, EPUB and apps in Europe  
… What are the problems?  
… FXL isn't responsive, isn't webby, isn't accessible  
… we (can) lose the semantics  
… and there's conflict between the authors's intent of the layout and the user's experience  
… there is no international standards for visual narratives in digital form  
… thank you!  

#### 3.2. EDRLab’s Work to Unify Digital Graphic Stories (Samuel Petit)
{: #section3-2}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/UnifyVisualNarrative.pdf)

**Samuel Petit:** I'm collecting all the use cases of comics around the world so that we can have a standard that can accommodate them all  
… The BDCoMa (Bandes Desinées, Comics, Manga) group is producing a "format", it's a ckind of web publication for comics  
… IT's set as an extension to ePub  
… with a declarative approach  
… THis extension comes with resources: images, music, HTML, etc. Whatever you want.  
… The goals of the Wg  
… 1st is most important, it's  Total artistic control on the reader experience  
… e.g. if you have an epub reader that simulates page turns, the authors want to offer a transition, it will not work. That's a big issue.  
… Problem is that advanced digital publications have high cost  
… So 2nd goal is low production cost  
… Another goal is sustainability  
… This is why we are against a JS approach  
… Want authors to have things compatible in the long term  
… Paper book, can read 2000 years later. Same problem.  
… We have a retailers platform, briefly, we are a digital platform and have a large distribution chain in France  
… Sequencity is partner in France  
… I am  co-edirector of SAIL, building artificial intelligence to understand the content of comics  
… There is a young startup producing authoring tools, Kwalia. Important b/c authoring is an important part of the production chain  
… OK, so main use cases  
… Main one is page, you are familiar with this is the epub world  
… Classical maga, comics, use page  
… After that is the scrolling page  
… Some pages immediately, in epub we have a problem  
… Another use case is guided navigation  
… On small screens, guided navigation from panel to panel  
… It's a problem in terms of artistic presentation  
… It's a bad solution to read comics, but sometimes we need it. So it has to be part of the standardization.  
… Let's talk about scrolling content, and intra-page navigation  
… When you have scrolling content, you know that perfectly you have a fast market in Korea, also other areas.  
… IT's a comic which scrolls (shows example from Korea)  
… It's very very adapted to mobile  
… You read by scrolling the content  
… We have that also in France, but we didn't succeed to create a market  
… here you have a blog in animated gif, a very beautiful blog  
… Here is another author who is doing a very long scrolling story  
… Scrolling capability in epub would bring a lot of artistic possibilities  

> *Elika Etemad:* [https://www.w3.org/TR/css-scroll-snap-1/](https://www.w3.org/TR/css-scroll-snap-1/)

**Samuel Petit:** That's the starting point. Problem comes just after  
… Something authors want to do, don't have in Epub  
… is simply to have starting point and have set direction in scroll  
… If you need to have a viewport ratio that's fixed, what then?  
… Some artists want padding between the drawing and the viewport to maintain this ratio.  
… Next is scrolling, sometimes need smooth scrolling, sometimes with snap points  
… Another issue is parallax, some comics use this technique  
… Here's an example of a french company which is doing black and white comics, you see they are using animation and parallax effects  
… This won the da Vinci prize in Japan  
… It's a page-fill ergonomic, but in fact it's scroll with parallax effects, and in some pages some animations  
… The animation is not a video inside an epub, this is an app  
… Unfortunately app is not available in latest version of iOS.  
… This is why we need a standard.  
… There is one more use case, it's when you add some effects  
… Here's an example, it is scrolling, but if you look closely some animated content, some parallax effects.  
… Very small animation, very small effects  

> *Elika Etemad:* (SP scrolls through the comic, e.g. fish slightly move)

**Samuel Petit:** We're finished with intra-page navigation, now inter-page navigation  
… Classical use cases, well, today the epub reading app has a transition. You turn the page, and you have an effect that is not decided by the author.  
… We remove the transition effect of the reading app, and let the author decide the transition effect.  
… Useful effect we want to add, there are basically two things. One is effect like fade, slide, change the sequence of images  
… two type of effect: time-based or control-based (e.g. as swiping, depends on speed of swipe)  
… Symmetric or non-symmetric effect  
… Back to navigation, a classic use case is turbomedia  
… One of the most basic the transition is a cut  
… A simple cut (shows examples where parts of the comic are added on, enew frames or word bubbles)  
… And of course, that kind of transition must work on all kinds of page.  
… Another topic was guided view.  
… Most powerful platforms in US are using a combination of transitions and guided navigation.  
… Multiple renditions is another issue  
… multilingual, multiple version s e.g. version 2,  
… responsive to environment, e.g. mobile vs tablet  
… Another concern is sections  
… Chapter by chapter, ur subscription  
… We are working on that.  
… New version of digital comics taxonomy, v3  
… focus on reading experience  
… This is part of the work in the manga working group  
… https://github.com/edrlab/bd-comics-manga  
… EDRlab is more than European, now global. We think we need members from Japan, Korea, the rest of the world.  
… Thank you.  

#### 3.3. Simple structure for fixed layout epub (Shinya Takami)
{: #section3-3}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/simple-fxl-epub180910.pdf)

**Shinya Takami:** Technical director of Rakuten Kobo in 2012, of d-Magazzine in 2014  
… Unfortunately in Japan, over 86% of ebook sales is fixed layout  
… We try to convert text-based content in the past, but we couldn't reach the quality that publishers want  
… In this time efficiency of production, distribution, and presentation... opportunity is important  

> *Elika Etemad:* (Shinya shows graphs of ebook market)

**Shinya Takami:** Before, we had domestic format in Japan  
… Changed to EPUB3 in Japan  
… EPUB is mainly used as a package mechanism  
… In Japan we have a standard FXL-EPUB  
… Fixed layout standard structure. But it's a little bit complicated, and we have XSHTML and CSS and image  
… Some SVG, something like that  
… But it's to complex to parse or convert  
… So many ebook services in japan convert epub to images and some settings for their reading system  
… So we have to convert EPUB to other formats  
… OPF is enough for conversion  
… XHTML and CSS are not used in many fixed layout services  
… Problem is SVG was very useful for fitting image in the screen  
… But the latest browsers behavior is different  
… Our Japanese standard is not the same as W3C's standard, so we have to change something.  
… I want to propose fixed layout  structure that is simpler.  
… spine & manifest link to JPEG, XHTML, PDF, Video directly  
… Current epub requires fallback to XHTML  
… We have some problems...  
… image map feature is used in ToC page  
… and also expected to use for advertisement  
… If we have only images and OPF, we have no way to indicate these maps  
… So maybe some alternatives to image map are needed  
… I think it's important to make these able to parse epub for new services, but currently the epub have to have some fallbacks for such images.  
… Want to discuss these fallbacks  
… We have to discuss alternative image map features for such simple epubs  
… Any good solutions? Enjoy to discuss. Thank you.  

#### 3.4. Questions, Discussion
{: #section3-4}

**Kazuyuki Ashimura:** I work for media and entertainment group  
… there was discussion of time synchronized navigation  
… there should be joint discussion among the publishing groups and MEIG, also TTWG  
… we have been working on timed media  
… perhaps we could discuss during TPAC  

**Ivan Herman:** we can try to fit into TPAC schedule  

**Bobby Tung:** two questions  
… IDPF had region-based navigation within your presentation spec  

**Samuel Petit:** It was never really used  
… it's a fine line between too ambitious and not ambitious enough  
… too ambitious a standard is too hard to implement, not ambitious enough is not compelling or useful  
… it was part of AHL group which was a failure  
… the use cases were not well understood at that time  

**Bobby Tung:** some browsers support animated PNG  

**Florian Dupas:** You were asking whether we were investigating new formats for animations in a file to replace GIFs  

**Bobby Tung:** the GIF format is too old, not enough colors  
… can we find a common file format for animated images?  

**Florian Dupas:** We're using aPNGs, as there is more capability for transparency  
… we need to allow for any kind of resource  
… it's not the job of the device to filter the formats  
… any formats should be accepted  
… the reading engine decides whether it can play it, and you need to provide a fallback  
… we are pushing for aPNG  

**Samuel Petit:** he's an active member of the manga WG  

**Richard Ishida:** what are i18n standards you're coming across?  
… there are differences in reading direction between Japanese and english, and then there's Mongolian  
… is there a market for RTL scripts?  
… the absolute position stuff will be problematic if translated into RTL  
… what are the i18n barriers you've come across  

**Luc Audrain:** the text hasn't been addressed as text, it's image  
… that was a hope from AHL to manage image and text in same pub, but we haven't done that  

**Samuel Petit:** rising markets like Korea and US can lead to propriety formats  
… we need next steps that are not too far, not too long-term  
… to quickly put in the market something standard, something open source  
… it's not a response to your question, but it's why we need to start from what we have today, EPUB3  
… we have to build just above that, quickly  

**Makoto Murata:** I'd like to respond to Richards question  
… one example had RTL scroll, one had LTR  
… do you find one direction uncomfortable?  

**Florian Rivoal:** I have a web-centric point of view  
… you say we need to solve from what we have now, which is EPUB3  
… but what we have is the web  
… we should start there  
… when you did intra-page navigation some of it is already possible, or soon will be possible, or would be reasonable to add to CSS or Web Animations  
… what's missing in the web is transition between pages, as web doesn't have that concept  
… for intra-page nav are you looking at what is already in CSS  

**Samuel Petit:** it will be close to web, this will be in Laurent's presentation  
… a web engine will need to read JSON  

**Florian Rivoal:** that scares me when you say similar, rather than the same  

**Laurent Le Meur:** I will talk about this later  

**Florian Rivoal:** when you said you are looking for simpler format for FXL  
… what if you start from the web, you can use HTML as container for images, and use scroll-snap and viewport images  
… have you looked to use modern HTML/CSS as a replacement for FXL  

**Shinya Takami:** it might be different for modern animated content  
… maybe we need both  

**Florian Rivoal:** I was thinking we could use HTML rather than EPUB spine  

**Ivan Herman:** one goal of the Web Publications work (WPUB) is to introduce the idea of one "thing" on the web which has multiple resources  
… which might help with inter-page transitions  
… also, WPUB can use any resource on the web as content, so we could have a sequence of images, just as we could have a sequence of audio books  
… the main resources could be audio files, or could be graphics files  

**Makoto Murata:** a remark from historical viewpoint  
… with FXL, we deviated from OWP, we abused spine and abused `itemref`  
… so scrolling can't use browser engines  
… the collection of pages is not html  
… so Japanese manga engines do not use browser engines  
… a long time ago, B&N proposed something similar a long time ago  
… "if you already deviate from OWP, why not go all the way?"  
… just do images in spine  
… so now we have strange mixture of OWP and traditional representation.  
… I have a mixed feeling.  

### 4. Web-Centric Manga & Comics
{: #section4}

#### 4.1. Building Comics With HTML, CSS, SVG, and Responsive Design (Pablo Defendini)
{: #section4-1}

> *Ivan Herman:* See [slides online](https://www.dropbox.com/sh/59lnjz59d7z0ypr/AAA_N85zkejOyY6asbD_ZFsja?dl=0)

**Pablo Defendini:** Discuss ... and drawbacks in ways that comics are created  
… digitalcomics.co  
… Common approaches to digital comics  
… Panel by panel presentations  
… Page of print comic is larger than most devices, problem on mobile devices especially earlier  
… Can cut page into panels, view comic panel by panel  
… Problem is that they undermine the storytelling experience by slicing up page meant to be viewed as a whole  
… Another approach is Balak Framework  
… Beyond adapting print comics for screen, take advantage of new medium  
… Experiments by depicting time by layering panels on top of each other, or shifting them over time  
… Limitation is no handling of varying viewport sizes  
… Static page monitor is not scalable. Similar to old Web, best viewed on Internet Explore -- best viewed on iPAd-sized device.  
… Not a great experience for viewing comics created for print  
… Have to letterbox it to fit  
… Web designers have realized that targeting only one screen size, we design fluid scenes that can adapt to multitude of viewing conditions.  
… Panel-presentation undermine full-page layout design, to reinforce the narrative  
… Visual juxtaposition of multiple panels on a page ...  
… You can see story how it progresses panel by panel,  
… But don't se relationship of the panels to each other on the page  
… Another problem with comics is that they are essentially photographs  
… They are large files that take a long time to download, more expensive for reader and publisher  
… Also loses semantics, not accessible.  
… Also relies on print-centric conventions.  
… E.g. this page shows a double-page spread. Double-page spreads enhance the reader experience in print  
… But on a tablet, becomes a point of friction. Effect of largeness changed to smallness, or need to reorient tablet  
… Need a new approach.  
… Screen connected to internet has very different characteristics than digital devices which have varying viewport sizes and unpredictable viewing conditions  
… Bandwidth, language, and screen resolution are just some of the variables need to take into account.  
… Can rely on Web development techniques for building comics  
… First, break the comic into constituent parts, so that we can reassemble in the browser.  
… Use HTML and CSS and responsive web design techniques, can build one page that can adapt to a world where we don't know what is happening.  
… Let me show you some demos  
… ... resolution-independent images (SVG)  
… Here's a simple layout, using CSS to make it responsive, but all panels are exactly the same  
… But using CSS Grid and Flexbox, we can do more sophisticated layouts, but also collapse them into mobile-friendly layouts.  
… You can explore on digitalcomics.co  
… Next is live text.  
… We can use live text instead of images of words. Text can be resized, searched, translated, and is more accessible.  
… Makes globalized comics easier to create for publishers.  
… Here you can see different examples, all live text in the word balloons.  
… Can resize as necessary, and it keeps its layout  
… Can move the word balloons around as you see fit, to adapt to different viewing conditions  
… Can use search, highlighting, etc. Every advantage of real text.  
… Finally, using resolution-independent artwork (vector images) makes comics accessible, lightweight, and scalable.  
… Some things will always need be raster-based, but so many aspects of comics can be done with vectors  
… Crisper images at all sizes, and lower bandwidth costs for users and publishers.  
… You can see to-planes.com uses some of these techniques  

> *Elika Etemad:* Pablo shows a comic panel where the relationship of background/foreground shifts as there is more or less width for the panel

**Pablo Defendini:** Once you start building comics out of HTML and CSS, can recreate anything that's been done on a physical page.  
… What are the storytelling implications of mobile layout, tablet layout, desktop layout?  
… Cliffhangers and reveals happen in different ways on different sizes.  
… Use layout in service of the story  
… Thank you.  

#### 4.2. Layering and Layout at Authoring Time (Katsuhiro Ogata)
{: #section4-2}

> *Rich:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/ogata.pdf)

**Katsuhiro Ogata:** I am trainer in Pokémon Go  
… Anyway, smaller company, agent company that also edits manga planning  
… eBook initiative in Japan, Torico, Naver are clients  
… Today I will tell you what I have [?]  
… I did questionnaire on Twitter. How are manga delivered in japan?  
… 23% images with rasterized text  
… 20% balloons without text, and text files  
… 57% compound format (psd, clip, mdp, etc.) containing ...  
… What are the advantages and disadvantages of these three types of data?  
… Image containing rasterized text (jpg, png, etc)  
… Advantage: can be published immediately  
… if there are no errors  
… Disadvantage: If there are errors, you must ask the manga artist to correct it  
… Also, Translation cannot be done  
… Also, if manga uses non-commercial fonts, can be a big problem in a later stage  
… This way should not be adopted. It is not more accessible than anything else.  
… Next is image without text. Manga artist give text files to manga editors along with image files  
… Image file balloons are blank  
… The manga editors use the text file and associate text chunks with each balloon  
… Advantages: Editors can correct mistakes themselves  
… Organize text for easy reading for the reader.  
… No worries about font licenses  
… Disadvantage is that it takes a lot of time.  
… It's a good way to work, but time consuming and boring work.  
… Next is compound format, e.g. PSD  
… Compound format containing both image and text  
… 57% use this approach  
… All have image data containing a text layer  
… Editors can receive characters with the same position, font, and font size as the manga artist designed  
… After proofreading, the editor outputs jpg/png/etc and publishes  
… Advantages: It is efficient because you can use text entered by the manga artist  
… easy to use on internet, book printing, or translation  
… As long as font used by manga artist and fonts by editors match, can publish  
… Disadvantages: It is very rare for the manga artist to publish that received data as they are, as fonts are different from delivery specifications  
… clip and mdp are not stable data formats for delivery. They are is similar to RAW image data in photographs  
… Danger that if you mistake the output setting a bit, dat different from a manga artists' intention will be created.  
… All of these formats are  proprietary, so we cannot exchange data across vendors  
… Conclusion, Japanese manga editors are exhausted with inefficient and useless work.  
… Most efficient way is to agree on the type  fonts before hand and use an image format containing text layer.  
… If there is an open standard for image formats equipped with text layers, the life of Japanese manga editors will be easier.  
… It might be SVG.  

#### 4.3. Advanced Techniques for Web-based Comics (Rachel Nabors)
{: #section4-3}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/rachel-nabors-talk-w3c.pdf)

**Rachel Nabors:** I used to work in comics, now in web development.  
… Big fan of Japanese comics community, so special day.  
… You've heard about layout today from our speakers.  
… But stories exist on multiple ...  
… Spectrum of storytelling  
… We have static comics, and we have animated film, but it is a continuum, there are comics mixed with motion  
… You've seem some examples today  
… This is what a motion comic looks like.  
… Can publish to native android, iOS formats.  
… But don't have any HTML+CSS format  
… Here you are clicking through the comic.  
… It's like a glorified storyboard.  
… What makes comics exciting on the web is interaction component  
… visual novels are doing this already  
… And games are ultimate mix of animation and storytelling  
… THis is an example of a visual novel / game / comic book ... hard to describe what it is  
… It was all written as flash, but reproduced with images  
… This is an introduction animation to a portion of which is a game  
… This is a portion where it suddenly turns into a game: collect inventory items to get to the next page  
… So popular that kickstarter funded it  
… THis has gone on to inspire other people  
… This is a Russian artist who created comic inspired by Wizard of OZ  
… Here using Drag and Drop API to create a clean-up game  
… In the past we needed flash, but no longer true  
… Here is Emily Caroll, a horror cartoonist  
… Uses links on images that take you to different comics  
… Here is hobolobo, a sophisticated comic with sound  
… Really interesting examples come from comics who became web developers  
… Rich and sophisticated experiences  
… This example turns a browser into a synthesizer. No imported media, wuicktime, etc.  
… We have declarative animations with CSS, here's an example of Alice in Wonderland I made with adobe  
… Very efficient animations  
… For more sophisticated examples, use Web Animations API working on by Mozilla  
… Scroll snap  
… with css-scroll-snap spec  
… Pointer Events ... we don't know how user will interact with page, but pointer events gives a standard interface to accept such input whether by mouse or touch or future tech  
… CSS and SVG also have useful filters like blur, opacity, rotate, grayscale  
… We saw how SVG can be used to make clear line work stand out  
… But can also use it with layering to create high-resolution contrast and low-resolution color  
… If you layer SVGs and bitmaps -- high-resolution linework and low-resolution art  
… So you can have very high-resolution color graphics as well as ...  
… Also have `<canvas>`, which can recreate many capabilities of Flash  
… Here is ?? example, Neurotic neurons: An interactive explanation  
… You can interact with things on the screen  
… This is a style of storytelling humans can finally do really well  
… AnimationCC exports well to canvas, so very handy  
… What is the problem with this, why do we not see these things everywhere?  
… Flash gave one of the best interfaces for this, not the best ever, but very good  
… But Flash is not supported on phones or tablets.  
… after banned from iphone, browsers limit it on all devices  
… but HTML+CSS+JS have evolved to include many of these capabilities  
… But they are not very author-friendly  
… THere are some tools that export to SVG, but they are very fragile, lost when company goes away, and not sufficiently ambitious  
… Here is an example... it was created by google webdesigner  
… But not responsive, not scalable, and not really capable of doing what was necessary  
… real loss  
… Adobe Edge Animate from the experimental line  
… Existed long enough to be adopted by some artists, but then was shut down so leaving them with an outdated tool that is increasingly obsolete  
… Every time a tool dies, we lose the content that it created.  
… Open source tooling might actually live the longest.  
… Ren'py is an open-source tool written in python  
… This tooling platform is appealing enough that artists learn enough to create and contribute to the community  
… Javascript frameworks.  
… This is a retelling of sleeping beauty. Uses a JS framework in the background  
… We have JS frameworks that should make building the next interactive framework easy  
… Best part is that the foundations can be used for building fo native  
… And frameworks like react/view/??? can export to native as well as web  
… Graphic novel that won awards, no reason this can't be done with Web technology  
… There are so many things here that we can do on the Web, no reason that it needs to be limited to a studio in Toronto with a dedicated developer team  
… Web is the ultimate platform  
… ApIs for sound, motion, interaction  
… open source JS frameworks ...  
… Formats are cleverly put to use around the world  
… Here is a comic training moment to avoid problems in war-torn areas  
… Here is a magazine-type storytelling using animation  
… The Web provides a lot of opportunities for us. We don't know what it's limits are yet.  
… Who knows what we have ahead of us? Lot of room for expansion.  
… Thank you  

#### 4.4. Reading engines for Visual Narratives (Laurent Le Meur)
{: #section4-4}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/ReadingEngines.pdf)

**Laurent Le Meur:** We are about digital reading, but reading what? EPUB 3 and 2, reflow and fixed layout  
… CBZ comics (zipped sequence of images, essentially used for scanned comics)  
… Audiobooks  
… Web publications and EPUB [next version]  
… We want to read visual narratives.  
… What are visual narratives?  
… We have studied inside EDRLab a new format  
… Why a new format?  
… First, a guarantee of the visual experience as driven by the author  
… Author wants to express something in images, text  
… It must be multi-platform: want to have something that works well on native and on web  
… Simplicity of authoring  
… It would be good to have an author able to create some visual narrative, as we call it, with a simple text editor.  
… And it should work online and offline  
… Mobile first, but to accommodate digitized works based on printed works  
… Very serious about long-term preservation  
… A choice: we made a choice to work based on Web Publications  
… work done by W3C  
… You can see our work as an extension of web publication  
… It is exposed on github  
… Warning: this may hurt some web developers, because there will be no CSS, HTML, JS. JSON only  
… Please we remind we're talking about a exchange format that must be processed by both Web apps and apps with no web view  
… What we're doing is a sort of fuel for web applications  
… We're designing JSON format with what the author wants to express  
… JSON can be embedded in a web shell  
… It's extension of Web Publication Manifest as developed by W3C  
… What the web application is using, getting the novel on the screen  
… If you replace HTML/CSS/JS with something that is native, same thing  
… You can replace the JSON content get a different visual narrative that is using the same web development  
… Take what the authors want to express, make it independent of Web work, of native work  
… You don't have the same problem as exporting only HTML+CSS+JS  
… can export just JSON, or export JSOn + HTMl + CSS + JS  
… We have been focusing on the most useful effects that we find in the industry  
… Want to standardize transitions, scroll, parallax, what ?? had been talking about earlier  
… First, the model  
… Visual narrative: comics, manga, poetry, everything visual  
… It is made of pages, a step in the reading experience  
… with fragments  
… and assembled into larger units, sections  
… How implement?  
… First some JSON like a web publication manifest  
… describes reading order, images, optional resources  
… Add to this things like transitions between pages  
… Different types: crossfade, slide, wipe, split,  
… Or image sequence or animated image  
… transitions can be asymmetric  
… other priorities by the suer  
… If you look at the reading order, you see some PNG, page 1, 2, 3  
… Add some properties, a transition property for the type of transition and its parameters  
… Very easy to express with any automated tool, even with a text editor  
… Transition is animated with images, which are listed  
… If we want to express a scroll, the scroll can be vertical or horizontal  
… there will be constraints on the screen, portrait/landscape  
… there might be some scaling needed  
… author wants to position the start point  
… here are some examples  
… fit to height  
… fit tor ratio  
… If author wants to start at 50% of the scroll  
… Can put snap points at 10, 20%, etc of the scroll, can just list these positions  
… If you want to have fragment-based navigation  
… We designed it to an ordered collection of fragments to drive the navigation  
… Reuse media fragments syntax  
… We just decided that no fragment can belong to two different resources  
… If you want to do it, you must have one image, a bigger image  
… Some things which were unsuccessful in EPUB3 were due to complexity, so we tried to simplify  
… You see the href here as a media fragment URL  
… You can add a transition from the first fragment to the second one, from the second to the third  
… Ww could add more transitions, but want to keep it simple atm  
… Sections enable easy in-book-update  
… Express very simply  
… Instead of a direct reading order, have a reading order with this section  
… This section will come later, see.  
… a chapter which will be published later  
… Layers and Parallax  
… We talked about ext and image in layers  
… A page can be a collection of layers  
… A layer is an array of images (raster or vector)  
… Parallax is more complicated  
… We know that there are layers, but a speed that differs, different linear path, opacity, snap points & triggers,  
… At a certain position in the scroll, trigger a sound or some animation  
… More difficult to express but it will come soon  
… We are also studying other features, like metadata for comics  
… Alternate versions e.g. if you have something b/w and you want to go to color version  
… or from Japanese to French version  
… Multiple renditions still useful for many reasons  
… Accessibility, visual narrative in images, but you want to read it for somebody who is blind  
… Developing a native reader, it will be good using this model  
… You can do it with great performance e.g using a game engine  
… But if you are developing a web reader, you've got choices  
… ONe is DOM manipulation + (CSS or Web Animations API) + JS  
… Or you can use a canvas and just do whatever you like  
… Summary - there are narratives you can structure using JSON-LD  
… Using any kind of authoring software  
… with long term preservation in mind  
… Let developers create optimized reading engines, using the technology of today and technology of tomorrow  

#### 4.5. Questions, Discussions
{: #section4-5}

**Taro Yamamoto:** Seems to pub emphasis on interactivity on the Web. Reminds me of long tradition of ???  
… Do you think the reason is future comics have anything to do with those traditions in the past?  
… If so, what do you think we can learn from the past?  

**Pablo Defendini:** interactive fiction is having a moment right now  
… we talk a lot about tech and tools  
… the fundamentals of how you write comics are the fundamentals, they are how you communicate  
… they're first principles  
… they apply regardless of technology  

**Rachel Nabors:** that's an interesting history I didn't know about  
… now is a good time to look back at those things, when interaction touched storytelling  
… and to come together across communities and cultures, so this current blooming is sustainable  

**Laurent Le Meur:** when we talk about interactive stories  
… we try not to be too directive  
… the interactivity is the reading path between states  
… if we consider that interactivity goes further, like games, then we are in a different line of work and shouldn't go there  

**Rachel Nabors:** pages are becoming more arbitrary  
… what is a page any more? what is a chapter?  
… media is becoming more like cinema  
… i'm inspired by the french turbomedia movement  

**Pablo Defendini:** a page is becoming increasingly arbitrary, as you said, but there's still value there. it's a tool.  
… you can use it as an author, you can guide stopping points  

**Florian Rivoal:** we're still exploring  
… we see avant-garde artists creating beautiful work  
… the following generation will learn from the inventors  
… but they will be less deep in the technology  
… we need authors who aren't devs to be able to do the work  
… and think of storing some of these things as HTML or SVG doesn't seem hard  
… for other types of work, it seems harder, but you can put images on a grid  
… for the things Rachel showed, it is much harder to think of how to have interchangeable html  
… but a lot could be done with HTML  
… or we can step out of HTML like laurent did, to define something that could compile to OWP stuff  
… do we want the web platform as authoring format, or as a delivery format?  
… by natural inclination is to be on the web, but authoring tools fo the Web are *hard*  

**Pablo Defendini:** we're getting there. there are new tools bridging that gap.  
… the bridge between visual designer and front-end coder  
… we're starting to see tools  

**Nathaniel McCully:** I have  question about the tooling  
… Rachel's point on open-source tooling is a good one  
… but there's problems maintaining tools, especially when the market is small  
… you need a community  

**Luc Audrain:** I'd like to react to florian re in the web  
… I don't see the EDRLab proposal as being out of the web  
… it's a different layer of abstraction  
… as an author I want to do a transition  
… if I am in html, I need to learn css transitions  
… but in intermediate language I can just describe my intent, and have it translated to any kind of application engine  
… this is not comparable... we can't compare the intent of the author ... I don't want it to have to be described in JS  
… today already it can be expressed in many ways  

**Laurent Le Meur:** I want to insist on that. You will team with a developer.  
… here, we want to say the developer is shared with different authors  
… one framework for many contents  
… it's not against the craft of building web pages  
… if something is out of the bounds of the framework, we'll do something custom  
… but if it's in the 80% of narratives, it will be quicker to use the framework, and it might be easier to maintain and preserve  
… it's a different way to work, but the achievement is just the same  

**Rachel Nabors:** you mentioned the examples I showed might be beyond those existing formats  
… I would hate to think that we are the masters of the craft already  
… when you build tooling, you are commodification  
… designers are being split from developers, using tools like framers  
… we don't know what will happen next. I hope the authors of tomorrow will be inspired to do things that the tools can't do  
… and I hope we arrange things so the specs won't be a limiting factor  

**Samuel Petit:** to avoid a misunderstanding, what we are showing today we are not trying to do everything  
… we are just trying to list what recurs  
… there is tension between freedom of the web and industry, which seeks to limit production costs  
… what we have shown today is really a step for the industry to go further  
… it's a modest goal, with production cost always in mind  
… I'm coming from comics paper world  
… you have the same thing, with fanzine you do many things with original paper, silkscreen,  
… but as a larger publisher you focus on costs  

**Rachel Nabors:** Artists like to get paid, too :) We are on your side.  
… I want to see experimentation, but monetization has to happen quickly  

**Richard Ishida:** talking about monetization, we were talking about translation  
… in Arabic/Hebrew world  
… I imagine pages can move in different directions  
… you can have responsible layouts that have pages move in different directions  
… in one demo there were very narrow speech bubbles, with Japanese vertical text  
… in another example there were simple but connected speech bubbles, that assumed a text direction  
… is this an issue we can't get around  
… can we use tech to get around that? even in a single frame?  

**Pablo Defendini:** I don't think it's a fundamental issue  
… there's a tech solution  
… you can use media queries or something, and then show proper balloon  
… that stuff is interesting, and speaks to opportunities rather than limitations  

**Rachel Nabors:** I work for a large company that does lots of i18n. it can be done.  

**Katsuhiro Ogata:** first of all, order of frames within comics is important  
… Japanese comics use RTL  
… even in translation  
… english only is LTR  
… for a lot of people in western world are used to LTR progression  
… so to sell to the rest of world, should be in that order  
… but many people in the world are used to RTL  

**Paolo:** that should be the decision of the person creating the work.  
… grid or flexbox would allow you to do that  
… if you mess with the stylesheets you can do either, depending on your intent  
… it's not a technical problem, it's a publisher-level problem  

**Kazuyuki Ashimura:** I liked Rachel's 2D diagram, and believe there should be many topics for collaboration between published media and streaming media  

### 5. Advanced Typography with Web Technologies
{: #section5}

#### 5.1. Rich Dynamic Design with Modern CSS (Hui Jing Chen)
{: #section5-1}

> *Ivan Herman:* See [slides online](https://www.chenhuijing.com/slides/41-w3c-workshop-2018/)

**Hui Jing Chen:** CSS Shapes allows floats in shapes other than rectangles  

> *Elika Etemad:* (Hui Jing Chen shows example of person cutout, with text floating around)

> *Elika Etemad:* (Hui Jing Chen shows example of text flowing down a rabbit hole for an Alice example. It shifts with scrolling)

**Hui Jing Chen:** It gracefully falls back to rectangular float shapes when not supported in older browsers  
… Writing Modes allows vertical text  
… Alters flow of text at block and inline level  
… writing-mode property  
… text-orientation allows upright or rotated typesetting in vertical lines  
… text-combine-upright allows combining characters into a 1em space in horizontal layout (tate-chu-yoko)  
… With CSS it's possible to create a single document which can be rendered in either horizontal layout or vertical layout  
… CSS logical properties makes this easier, the same code for margins, padding, borders will work in both writing modes  
… A question in QA was about laying out content in different directions  
… Combination of writing-mode and/or flex-direction can determine the flow of content on your page  
… The content does not need to flow top-to-bottom  
… writing-mode changes the flow of text  
… Flex directions allow changing just the ordering of a set of boxes  
… Can go left to right, right to left, top to bottom, even bottom to top  
… and wrap into multiple lines  
… Another major development is CSS Grid  
… Has been supported stably in major browsers for over a year  
… Allows placing items into a grid, and even allows overlap  
… It is easy to lay out elements on top of each other, and can use blend modes, transparency, and clip paths to create interesting overlapping effects.  
… Placing items on a page becomes as straightforward as placing items on a chessboard  
… and can be made flexible to stretch and fit different window sizes  
… Media queries allows significant changes in layout for different ranges of window sizes  
… Responsive images is another feature which loads different images, or different resolutions of the same image, based on the available space and screen resolution  
… Viewport units can be used to size items to a percentage of the viewport  
… Media queries can also choose between different aspect ratios, so layouts can be fluid within a range, but also be rearranged based on the orientation of the window.  
… Thank you  

#### 5.2. Breaking Bad: The Dark Secrets of Web Typography (Dave Cramer)
{: #section5-2}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/W3C-Workshop-2018-09-Cramer.pdf)

**Dave Cramer:** I went to my first W3C meeting  in 5 and a half years ago  
… Workshop on print, met Håkon and Bert and other mythical figures in CSS  
… 5 yrs ago I went to another W3C workshop in Paris  
… I worried that Web would be dominated by frameworks  
… TOld to go to China next month for TPAC  
… 5 years later at another w3c workshop , what has changed in 5 years?  
… Jen Simmons describes history of web as going through phases  
… no design,flash, fluid layout, fixed-width layout, responsive design, intrinsic design  
… But as publishers we can't just start using grid today  
… First of all, our content is very big  
… Here's a blog post that includes the entire text of Moby Dick in a single web page  
… this image was Tokyo Tower , i.e. 170m tall image  
… Usability demands that we present content in more digestible pieces  
… print and epub use pieces called pages  
… In epub world we can't use a lot of modern web capabilities  
… in original kindle, couldn't even put top margin and left margin on the same element  
… In spite of the best efforts of ppl in this room, big divide between world of publishing and world of the web  
… As publisher, I'm afraid to use parts of CSS even from 2.1  
… These are print book sizes (shows rectangles)  
… On the web, can change the size of the page in a second. In print world, takes 6 months to a year  
… In my day job, set books in CSS  
… Usually works ok< but there are some exceptions  
… This book, for example, has annotations.  
… But annotation themselves have annotations  
… We had to redesign this layout when we did the print  

> *Elika Etemad:* (Dave shows examples from David Foster Wallace)

**Dave Cramer:** We never did an ebook of this one, because we couldn't figure out how  
… Tried some experiments with grid, but many reading systems don't support this  
… So stuck doing same simple things with ebooks  
… This is a choose your own adventure novel, called Chose Your Own Disaster  
… I made it more disastrous by setting right-to-left  
… But simple isn't easy.  
… It's more fun to talk about animations, shapes, exclusions  
… But there's still a lot of fundamental work to do in typography  
… in ways that apply to books, print, and web  
… Books have pages, to help not hurt the reader  
… But sometimes things paginate badly  
… Some breaks are ... , like at beginning of chapter  
… Others are contextual  
… Try to avoid breaking in bad places  

> *Elika Etemad:* (Dave quotes from Chicago Manual of Style)

**Dave Cramer:** Don't remove title from a section, e.g.  
… Need to describe when it's ok to split things up, when it's ok  
… Browsers not very good at it currently  
… But publishers are very aware of these problems  
… My goal is to teach these things to browsers  
… Many types of breaks  
… Even a single line can break badly, ends up typeset too tight or too loose wen justified  
… We don't have much control over justification  
… Here's another problem, a short partial word at the end of the paragraph  
… This is not great, various approaches to fixing it  
… Would be really useful to have things like hyphenation exception dictionaries  
… and other ways of solving problems  
… Also have problems breaking pages  
… Here is a widow, single line stranded at the top of the page  
… CSS has a 'widows' property, to pull down another line of text so it's not alone  
… But that breaks a more fundamental rule, that spreads should have the same height on both pages  
… In this example, typesetter fixed that problem by tweaking a paragraph so that it wraps to an extra line  
… Even on a larger scale, we want to optimize chapters  
… WE don't want a chapter to end with one line of text  
… Also see that kind fo thing that on the Web, you have a page with a scrollbar and it scrolls to expose one word.  
… Or disclosure triangle exposing just one word, or one or two calendars  
… Sometimes think on scale of entire books  
… Books are printed on giant sheets of paper, cut and folded to create a book  
… So only certain multiples of pages are OK  
… There's another level of optimization we don't know how to do yet  
… On the Web scale, have milliseconds to redo a layout  
… If I have a few days, like in print world, can do some nice fixes  
… Slow books  
… Thank you  

#### 5.3. The Versatile Web (Myles C Maxfield)
{: #section5-3}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/Myles.pdf)

**Myles Maxfield:** I'm an engineer on Webkit, member of CSS Working Group  
… The Web is incredibly powerful, can do a huge number of things  
… Go through a walking tour of amazing things it can do  
… Layout modes to describe your content layout, typography, internationalization, responsive design  
… CSS Grid — it's really easy to get it to work  
… Put display grid on your content, and your content will participate in a grid  

> *Elika Etemad:* (Myles shows off some examples from Jen Simmons)

**Myles Maxfield:** There are additional properties that control spacing and positioning, but very straightforward  
… Flexbox is similar, lines up items along an axis, can control spacing and sizing  
… Multicolumn is also super easy: ask for number of columns, or preferred width of columns  
… You can add this property  
… CSS properties are additive, you can combine them together  
… You can describe content in SVG,  
… Letters in this green bar are described as vector images, always sharp. Looks great on Retina device  
… Can use SVG to make infographics, diagrams, etc. using basic geometrical shapes  
… MathML allows typesetting math equations  
… Line Grids are something that have been around since dawn of history  
… CSS proposal creates a grid with a signal declaration, asks lines to snap to grid  
… Shapes allows content to flow around non-rectangular shapes  
… Can choose a polygon, or draw a shape, or use an image  
… exclusions are similar to shapes, but can put in the middle of your content  
… Most of these things are additional properties, can have e.g. multicol layout with exclusions  
… So typography  
… Complex text shaping is done: browser just handles it  
… :First-letter allows styling the first letter  
… Can turn first line of content into small-caps  
… drop-caps with `initial-letter` property  
… combining e.g. `::first-letter { color: red; initial-letter: 4; }`  
… Hanging punctuation  
… The browser has knowledge about the language (if you mark it up) so can figure out correct set of rules to use  
… Hyphenation is similar, `hyphens: auto` turns on hyphenation using correct dictionary  
… widows/orphans control are another set of setting  
… font-features allow improving typographic quality  
… Here are some examples: font-variant: diagonal-fractions, small-caps,  
… font variations mean you don't have to choose between font-weight: 600 and 700, can use 697 if you want  
… fill and stroke allow outlines on text, etc.  
… can load color fonts  
… Internationalization ... RTL text just works, can set base direction with HTML `dir` attribute  
… Writing modes allows top to bottom right to left, or top to bottom left to right  
… Ruby markup allows ruby annotations, 'ruby-position' to change which side of the text  
… text-emphasis can add dots  
… Everything I talked about here are additional CSS properties that the browser uses  
… They all work together to create sophisticated layouts  
… All of these are controllable conditionally, using media queries  
… Can switch from a grid layout to a flex layout  
… or totally change layout between screen and print  
… change colors  
… disable animations  
… etc.  
… Relative units, media queries work great for discrete positions, but you can change the line height based on the browser window width, using more spacing for wider measures fluidly and automatically  
… CSS variables  
… Browser makes these features work seamlessly together, and that's what we do  

#### 5.4. Auto Font Alternating System (Satoko Takahasi)
{: #section5-4}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/20180918AutoFont_DNP.pdf)

**Satoko Takahasi:** Automatically use fonts to express text better  
… Useful for printing but also for web and ebooks  
… Typefaces are important for communication  
… DNP research and development on typography  
… Created font alternating system  
… Firstly, I like to talk about the system function  
… The system can automatically replace font according to topics of users's feeling  
… For example, if I have tender words, display in rounded sans-serif typeface  
… If I have Japanese topics, I can display in Japanese calligraphic typeface  
… This shows an image that the system uses on messenger  
… Left picture is regular system, basic font  
… right picture is using our system, it is displayed in different fonts  
… Next I like to talk about system features  
… Just one, the system does this users motion from the sentence  
… Also judges user's feelings from emoticons  
… Users can also choose other fonts  
… If the system suggests a font, also users can choose another font  
… You can edit each word to activate auto replacement on the system  
… I'd like to show a demonstration  
… We developed a prototype of the system  

> *Elika Etemad:* (Satoko Takahasi demonstrates by typing some words, automatically changed to different font)

**Satoko Takahasi:** I type a word, happy  
… I type about sushi  
… I type about horror movie  
… If you want to see more demonstrations, you can watch a movie on youtube  
… This shows the font list that the system is using  
… System uses 12 fonts  
… Chooses which word to replace with which font  
… Here is example in English  
… Next I'd like to talk about practical application  
… This shows that image of the system used in chatbot  
… THe system gives more humanity to the chatbot  
… This shows that the image the manga-style messenger, using word balloons with different styles  
… If the system used in ebook creation program  

> *Elika Etemad:* (Satoko Takahasi shows example of before/after the system for a manga panel)

**Satoko Takahasi:** Basic font is replaced with more stylized one  

#### 5.5. Questions, Discussions
{: #section5-5}

**Florian Rivoal:** Not really a question, but a comment  
… Many things in the presentations we saw now reminded me of what Jen Simmons said  
… Florian: In print, we draw pretty things, decide exactly what the user sees  
… In the web, it is more like a sculpture. You can fully design the document, you do not chose how the reader decide to view the document. But we are still in control.  
… The designer doesn't choose *one* view: designs many views  
… reader decides how they are going to read, but author has not lost control, controlling different aspects  

**Kazuyuki Ashimura:** I tend to agree with Florian  
… Thank you very much for your presentation.  
… was wondering about emotion features for publishing  
… we have some W3C specifications dedicated to marking up emotions etc.  
… How to handle and how to record emotion information  
… what bout combining emotions?  
… partly angry partly happy?  
… My point I think is actual human doesn't have completely one emotion, can be kind of angry, kind of happy, kind of confused, kind of disgusted  
… That kind of combination  

> *Dave Cramer:* [https://www.w3.org/TR/emotionml/](https://www.w3.org/TR/emotionml/)

**Kazuyuki Ashimura:** (in Japanese) there is a standard to express mixed feelings (e.g. 20% surprised, 80% happy), which could be used as input to the dynamic font system  

**Taro Yamamoto:** I'm very interested in this area of emotion expression and font substitution  
… But this type of technology implies, the mapping from one emotive expression such as angry anger or something to some font style  
… This is one to one mapping  
… On the side of the recipient, according to the mapping selected by the system, the font style is chosen and displayed on recipient side  
… But in order for this to be successful, the mapping itself should be based on common set of mapping relationships  
… Should be commonly understood  
… The context of the mapping and semantic relationships should need to be commonly understood on both sides consistently  
… otherwise emotive intent will not be correctly understood  
… For example, you say I wanted to have sushi.  
… The semantic is mapping to a style or font  
… But I think maybe, he wants to have sushi now  
… But what on the recipient side now, from notion of sushi might be different depending on place you live  
… Sentence in Kansai, you may imagine a kansai style sushi  
… but recipient maybe lives in Tokyo, and imagines Tokyo style sushi  
… So it is necessary for us to be able to evaluate faithfully, to what degree of fidelity, the intended semantic of a context can be conveyed from the sender to the recipient  
… I think there will be many vague and difficult things, issues included in this kind of technology  
… About this kind of difficulty I have now, I can imagine what do you think about this.  

**Satoko Takahasi:** Difficult to express... of course it's true that when sender sees something, and what other person gets might be different  
… After awhile sender might feel something else  
… Kind of experiment, throw a stone and see what happens. What kind of help to express this kind of emotion  

**Taro Yamamoto:** Too difficult to answer everything here but we should continue discussing it  

**Ivan Herman:** I want to come back to the point Florian made at the beginning, about CSS-related things  
… will play devil's advocate  
… Each of them is super easy, but as a user of CSS am overwhelmed.  
… When I hear Dave say that there are certain elements of CSS2 that he's afraid to use... if he can't use it, I don't want to touch it  
… Level of complexity that CSS has today that is frightening  
… You see new modules coming up once a week  
… I don't know where it ends, and how anyone can grasp its entirety  
… Many things you can rely on them  
… No publisher can rely on MathML today. There is no reliable implementation.  
… Some browsers ignore it, some have partial implementation..  
… you spoke about hyphenation. I cannot rely on it, because not supported across the board  
… problem in the higher level things, don't know how to manage it  
… In this community, it's a big problem  

**Dave Cramer:** CSS2.1 comment was because epub reading systems are often homemade layout engines or are hacking the layout system so much that stuff breaks  
… That's not the fault of CSS, but result of how reading systems have evolved  

**Myles Maxfield:** Because it has developed over decades and is additive, and can have progressive enhancement. DOn't have to have it all in your head.  
… There are many pieces to the Web platform. Many implementations, not all support everything  
… Every implementation would like to support everything but we haven't gotten there yet  

**Hui Jing Chen:** Agree, you don't need to know every of the 503 properties we have now to get something to work  
… If you're reluctant to support properties because unsure of support, CSS offers feature query -- `@supports` rule -- to make some declarations conditional on support  
… View of digital as a platform  
… underlying view that we're trying to push forward is that the design doesn't have to look the same on every device  
… You give your user multiple perspectives on the same content  
… it is medium for transmission of content  
… Not practical expectation for medium like the web to look the same on every device  
… It is much safer than before to use newer CSS properties to worry that lack of support to break your design, because means and methods to ensure that a decent experience can be had across any device regardless of whether old or new  
… to re-iterate Myles's point, you don't have to learn all of it to use it  
… I'm in the same boat about browser support  
… e.g. I looked at hyphens, it is supported everywhere except Opera Mini  
… Flexbox and Grid were quickly adopted by all browsers  

**Florian Rivoal:** Did you mark up the language?  

**Ivan Herman:** Yes, but it wasn't French, it was Hungarian (all languages are different)  
… In general, I understand all that, but nevertheless, we have a problem if it becomes very difficult for an average designer who is not deeply into the technology  
… to understand what is going on  
… Get a partially-designed site from someone else, try to change/improve it  
… Maybe it's a documentation issue, but something bothers me, that makes it overly complex  

**Florian Rivoal:** Won't try to pretend CSS is very simple. Many properties, lots of moving parts  
… But in another sense CSS has become simpler  
… We were in the past abusing CSS features that were not designed for what we're trying to do, to build very complex layouts  
… Using floats and line heights and inline-block and all kinds of stuff to make this work  
… It was very hard, and had to teach each other complicated tricks  
… But it is no longer necessary, can directly express desired layouts in Flexbox and Grid  
… Doing the same designs in Flexbox/Grid is much simpler  
… So tools are more complicated, but answers to design problems are much simpler  

**Bobby Tung:** I remember being very excited that drop-cap was implemented by Webkit  
… Finally it works, great to work with CSS  
… but actually many systems were developed many years ago  
… If one browser implements it, others will follow suit, but it's more complicated for epub reading systmes  
… So publishers will be concerned to publish epub files with minimal typography, will not want to use latest features because it's not safe  

**Dave Cramer:** I like the idea of having the computer do the work  

**Rachel Andrew:** To follow up from what Florian says  
… I've been teaching CSS for 19 years now  
… what we're gettin now is much more consistent models, esp. layout  
… And that's making things an awful lot easier  
… I can get students to do in a day is way ahead than what I could do 5 years ago  
… So much easier than using tools not designed to do layout to do layout  
… For ppl using CSS for a long time it's actually harder to learn, because have to unlearn first.  
… But for new people, the basics are actually much easier now.  

**Laurent Le Meur:** About reading systems that don't implement CSS correctly  
… Some reading systems are built from scratch. Have to implement all of CSS  
… Some of the older reading systems that have poorly-compliant rendering engines may have significant market share/  
… Some reading systems built on a Web engine, and they implement all of CSS  
… So everything built on Readium and many other engines are using 100% CSS  
… So one can not say that most reading systems don't implement CSS, most do.  

**Dave Cramer:** Also different markets have different mixes of implementations  
… Using webkit from 5 yrs ago is much different from Webkit from Last week  

**Richard Ishida:** I understand where Ivan is coming from, you're more deeply involved in CSS  
… There are new things that really simplified my life, but have to learn it  
… Documentation is a big deal. I remember learning CSS and trying to figure things out  

> *Elika Etemad:* ???: You go from one tutorial to another, where's the place where I can go to look at the spec, it's not really friendly for learning

**Rachel Nabors:** Role of design systems in CSS means that individual designers don't kneed to learn all of CSS  
… Design specialists build much, and others re-use  
… You see this in open source frameworks. We're not rewriting CSS from scratch every single time. Collaborative system, each person does what they do best  

**Florian Rivoal:** Combination of CSS is easier due to better layout, and also progressive enhancement is good  
… In the past, doing an advanced design was a pile of hacks. If any piece didn't work, everything broke.  
… With new capabilities, can have better graceful degradation.  
… Because using features in way that they were intended, the fallback is not as nice but is not totally broken  
… your content will still be there and be readable  

**Florian Rivoal:** Ruby is a good example. _If_ system supports ruby, get ruby annotations. If not support ruby, get parenthesized annotations. Not as nice, but it still works  

> *Elika Etemad:* Luc move to EPUB 3, better typography than EPUB2.

**Florian Rivoal:** But take example of initial-letter, only in one browser engine  
… How long do we wait for interesting specifications to be deployed, for features that are important to publications?  
… It's a difficulty for us  
… Though we do our best effort to promote CSS as being more and more powerful, we have this difficulty  
… Another point, CSS works because of a programmer, an algorithm that applies.  
… I don't know if this algorithm is specified anywhere  
… Probably not  
… We don't speak about this  
… For the same CSS there may be some differences, because the engines are different  
… I don't know if there's some work in W3C  

**Florian Rivoal:** initial-letter, yes, still missing from most browser  
… But if you're trying to build a document with CSS and trying to use initial letter  
… the reader may not see initial letter in one case, but the document is still there  
… Maybe you don't like that it's not there, you use the alliterative: make JPEg of your page  
… But then it's unreadable on a phone because text is too tiny  
… You can't control everything, but you get adaptability  
… Second question about algorithms, yes, this is what the CSSWG does.  
… Our job is to specify the features in extremely precise detail so that the implementations will all be the same  
… If there are differences, we investigate and make the spec more precise  
… to get the browsers to align  

**Florian Rivoal:** if there is a point of non-interop, and the spec is ambiguous, then tell us, we will fix it. That's our job in the CSSWG.  

**Koji Ishii:** there is difference between browser world and epub world  
… In browser world, there is some pressure to implement new features  
… e.g. caniuse database, competing with other browsers to match what they implement  
… or in bug system, get requests for a features from developers  
… but epub reader world, there is no such thing  
… maybe W3C community can improve this  
… create database to show which reading system uses which version of which engine, supports which features  
… encourage users, reading system devs, to update these systems  

**Dave Cramer:** Testing is the big elephant in the room  
… For EPUB 3, there was only manual testing  
… There are 50-60 different reading system, behaviors vary from platform to platform  
… EPUB community group is very aware of this  
… What to put much more effort on testing and documentation, and encourage systems to support more of the spec  

**Koji Ishii:** It's not possible for any single person to create all this data  
… Need to create an ecosystem, get vendors to participate, to encourage vendors to implement new properties  

**Dave Cramer:** Have had discussions with Web Platform Tests people  
… would love to run all the HTML/CSS tests on epub systems automatically, but a lot of work to be done there  

### 6. Internationalization Concerns
{: #section6}

#### 6.1. Internationalization at W3C (Richard Ishida)
{: #section6-1}

> *Ivan Herman:* See [slides online](https://www.w3.org/International/talks/1809-tokyo/)

**Richard Ishida:** The internationalization activity at w3c, called i18n for short  
… We believe that the importance of the Web for all people of all countries of all languages  
… Work is divided into three areas  
… Language enablement -- to understand where gaps are for suers of the global web  
… Developer support - build standards and apps  
… We have recently started the W3C Internationalization Initiative  
… Two goals, one to increase participation in W3C from underrepresented regions  
… Second, to increase sponsorship of i18n activities at w3c  
… We have some some sponsorships already, APL from Japan, Monotype, Paciello Group, and Alibaba Group  
… Language enablement  
… Here are some of the things we're currently doing, going to focus mostly on here  
… Language enablement  
… This is a fairly new thing, a language matrix  
… Across the top we have a number of categories of typographic features, such as line breaking, justification, etc.  
… Down the side we ave a list of languages  
… Want to note problems in supporting these languages  
… Figure out features that need to be developed for CSS or SVG, provide the typographic information needed  
… From the current state, we have 32 languages that need work  
… for advanced publishing  
… Orange squares, 25, need work for basic features  
… 2 language that just don't work well on the Web at all  
… 47% still need investigation  
… So we're trying to find experts, to get the information of where we stand in supporting a _World Wide_ Web  
… We started this work a long time ago with teh Japanese Language Requirements document  
… Develop a document that was not technology-specific, to simply describe how Japanese typesetting works  
… Then follow that approach for other langauges  
… Since then we have developed Hangul klreq, Chinese clreq  
… Arabic alreq, Ethiopic elreq ongoing  
… We have Indic ilreq, and I wrote a first draft of Tibetan tlreq  
… Breaking news is new Mongolian mlreq  
… Still need more help for all of these  
… These documents take awhile, and it's a lot of work. Not much happens in the meantime  
… So earlier this year, we had a rethink, and decided to produce a different doc, a gap analysis  
… Here's the Japanese Gap Analysis  
… Idea is to look at for a particular set of languages, how each of these typesetting requirements to see what's supported, what still needs work  
… And to prioritize  
… both spec work, testing and implementations  
… Squares in Japanese, you can see it takes you to the proper place in Japanese layout gap analysis  
… Can see how problem is solved, unsolved.  
… Figure out which is high priority items  
… I expect that in the future, more piecemeal progress  
… The next step, we still weren't getting enough participation in these activities  
… Third is networks  
… Example is Southeast Asian Task Force  
… We had nothing  
… The main thing was to gather experts, and ask them questions  
… We can see questions relevant to CSS, or other things, to get answers and have discussions, figure out necessary changes e.g. to CSS specs  
… Intend to roll this out to other task forces  
… People who participate in these task forces, get a notification relevant to their task force  
… Also have started tagging CSS issue and HTML issues and so on  
… If there are changes to such issues, also get notifications for those  
… Have an issue tracker  
… You can see a summary, can filter it to show what are the questions we have about Mongolian  
… As it happens, the SE Asian TF is documenting some stuff  
… We have a Khmer Gap Analysis, Lao Gap Analysis, Javanese Gap Analysis  
… More breaking news, put a new Japanese Language Task Force infrastructure  
… To work on JLREQ errata, to publish new informative documents, create Japanese gap analysis, discuss issues  
… You can get involved as a follower or as a contributor  
… The amount of work needed is can be very small  
… Also needed a place to find the information that's accumulating, so creating a text layout index  
… Each section talks about a typesetting aspect and links to requirements docs, other resources, spec links, tests, etc.  
… Also have a type samples repo, anyone can submit samples of typography in the wild  
… We also do Developer Support  
… We review specifications at W3C, send comments to specification working groups  
… We track those comments to make sure spec editors receive the advice they need, resolve the issues we have.  
… We have spec development guidelines to help spec editors remember to accommodate i18n  
… and a self-review checklist to help them check on common i18n requirements  
… In development is how to transfer information about base direction in data format like JSON  
… We also have a number of articles, for content authors predominantly  
… Of how to sue internationalization tools  
… Here's an example of vertical text  
… On the righthand side you'll see notes on whether things work in various browsers or not, other useful info for authors  
… We also have test suites, and results of those tests in major browsers  
… Again, we have a techniques index  
… Can drill down and find information on how to do things  
… We have an i18n checker, quickly check if you have made errors or other problems. Link to more information on how to fix  
… So, to finish, next steps  
… We need to widen participation of experts in langue requirement groups  
… Significantly increase scope and output of language enablement  
… Extend i18n test framework to support tests and paged media  
… Things YOU can do  
… Join a layout network to help provide expertise  
… Contribute to gap analysis  
… Thank you!  

> *Elika Etemad:* (Richard lists other ways to help, see slides)

#### 6.2. Implement Bopomofo by OpenType font feature (Bobby Tung)
{: #section6-2}

> *Ivan Herman:* See [slides online](https://w3c.github.io/tokyo18-workshop/slides/bomofo.pdf)

**Bobby Tung:** What is Bopomofo?  
… It is a phonetic system for Mandarin education in Taiwan, and a major input method for Han characters  
… it is typically written alongside Han characters, like Japanese kana ruby  
… Rules for bopomofo are published online, if you want to learn  
… (see [https://bit.ly/2w3LEph](https://bit.ly/2w3LEph))  
… want to talk about how to achieve the correct layout  
… HTML can mark up bopomofo correctly  
… But positioning of characters, particularly tone marks, is problematic  
… There are several variants of markup, the best one for accessibility only supported by Firefox  
… We have some issues  
… Tone marks are encoded into Unicode  
… Noto Hans Sans and Helvetical include these code points in their fonts  
… How to position tone marks in horizontal writing...  
… Tone marks are very small, but it's hard to read for readers here  
… Vertical writing, the note mark should move to the side  
… in some cases before the syllable  
… I was told in CSSWG that the tone marks position should be built with OpenType features  
… When found a good way, bring back to CSSWG for next step  
… But I don't know anything about opentype. Don't know what opentype feature should be used. Do we make a sample font for that? Should we add new features to OpenType for those?  
… add browser feature for that?  
… Somebody from Mozilla found the issue, harfbuzz OpenType engine fixed, and now works in Firefox  
… But not others, so went and asked other experts for help...  
… You can see, this is almost done. In vertical writing, tone marks are in the correct position  
… We also received feedback from WikiMedia community in Taiwan  
… They want to ...  
… Recently we got everything done, so you can check the github repo  
… We also filed bugs for Webkit, Blink, Edge  
… You can see case numbers  
… Dr. Ken Lunde from Adobe allow me to say that next version of Noto Sans and ?, will improve those features  
… That's great because these fonts are widely-used open license fonts for Chinese  
… Conclusions, font issues are outside W3C  
… If there are font issues, don't know where to handle  
… Should we have a font community group to liaison with CSSWG and OpenType etc.?  
… Could we solve other CJK issues in the same way?  
… For example,  Every 5 years I come to Japan we talk about Kanbun issue, but no progress on it  
… How to publish the solution in a standardized way, should it be an i18n note? Something else?  
… Need browsers to see this information  
… Many thanks for everyone who helped this project  
… Thank you.  

#### 6.3. Questions, Discussions
{: #section6-3}

**Myles Maxfield:** Richard, you said two languages don't work well on the Web. Which two are they?  

**Richard Ishida:** Might be 1.5, actually. ONe of them was Mongolian, and the reason I put that because the ? model ??  
… We're not quite sure yet. there's no completely interoperable set of variants across fonts (???)  
… So that's a half  
… The other one is Javanese  
… where they break lines on orthographic syllables, involves stacks and other things  
… and browsers don't know how to deal with that. Since no spaces, text runs off the right hand side of the page  
… Those are the two I've found so far  

**Myles Maxfield:** Why did you choose to use font features to solve tone mark problem, rather than other technology?  

**Bobby Tung:** People in the CSSWG gave this advice  
… Ask Japanese community, for me main layout issue for Taiwanese was bopomofo. Wanted to figure out what is the next issue to work on.  
… tategaki was most important, but it's almost done  
… What's the *next* most important issue for Chinese + Japanese typesetting, that we need to solve in W3C?  

**Elika Etemad:** Wanted to first say thank you very much for following through on this issue of tone mark placement. It was not straightforward, and I am very impressed at how well you followed through to make sure it worked.  
… secondly wanted to answer question of why this is a font feature not a layout feature.  

**Florian Rivoal:** Wanted to address issue of font community group. yes, we need a better liaison with font groups  
… Often in CSSWG we realize there is some problem with OpenType format, or with how fonts are implemented, but we don't know how to follow up  
… e.g. we are missing some baselines that we need to do initial-letter properly  

**Makoto Murata:** OpenType spec is maintained by Adobe and Microsoft  

**Kazuyuki Ashimura:** Thank you very much for your presentation  
… I don't disagree with your approach, but have a similar question to Myles  
… but, for example, [Speech Synthesis Markup Language (SSML) 1.1](https://www.w3.org/TR/speech-synthesis11/) has mechanism to handle additional metadata like pronunciation and tones  
… Maybe think about how to deal with pronunciation and metadata in addition to how to express the font would be useful  
… ruby Bopomofo with right tone marks is correct for accessibility  
… SSML 1.1 can use bopomofo or IPA pronunciation alphabet :)  

### 7. Accessibility Concerns
{: #section7}

#### 7.1. When AI enters publishing process... (Vincent Wartelle)
{: #section7-1}

> *ivan>Se:* [slides online](https://w3c.github.io/tokyo18-workshop/slides/ISIcrunch_PPT_W3C-Tokyo_v4.pdf)

**Vincent Wartelle:** I was asked by ? to talk about the new project, artificial intelligence in publishing process  
… We'll talk about the ebook communication. We are fully committed to ebooks, creating epubs for education publishers  
… Production of ebook community  
… We'll see challenges and goals, why we chose AI  
… Just a background, we're very happy to see that the digital textbooks or digital books should continue to grow  
… as I mentioned  

> *r12a-fallback:* r12a-fallback has joined #tokyows

**Vincent Wartelle:** But more happy to see textbooks, much more important. In France for example it's 38% growth  
… Means use of digital textbooks is a growing market, and we have need of a lot of production features, because very specific market  
… Our platform, we take a PDF, make EPUB 3 with HTML and CSS. We have application to insert interactivity  
… Textbooks have a lot of external resources for exercises etc.  
… But ...  
… Rich interactive ebooks.  
… Proofing process  
… Studio underlies the AI system  
… Summarize, we focus on education, use epub3, fixed layout, and production  
… Upcoming needs.  
… We produce for French education publishers since 2013  
… smartphone market, especially emerging market, is something to handle in the future  
… high demand for individual resources.  
… Not enough to just have the book, can create a lot of resources from the book as well  
… Need to build new service, Resources Database  
… of resources to freely reuse by teachers and government  
… Last we have to extend the usage to disable audience. Education means education for everyone  
… So we have to address accessibility.  
… It's very difficult to do that in the old fixed layout  
… When you reach education book, read in spreads, beautiful design work should be respected  
… easy to automate, easy to add interactivity  
… Problem we face is, because it is display-orientated based on the print world, really difficult to adapt to mobile. Not accessible, not at all. And not content-aware.  
… Delivers a lot of content, but...  
… That's why we began to create what we call Hybrid EPUB  
… Just show a sample of that  
… This is a book in our reading app  
… This is an automatic book  
… Two-page spreads  
… we have something similar to a reflow system on top of spreads  
… Inside a section of the page, that we've captured, zoom into a reflow view  
… You can have text, and you can also have images  
… But this here is a formula... rendered as an image.  
… This is done manually, and this is the problem actually.  
… So goals for tomorrow  
… We build a reflow production plan  
… Need to produce 300-400 books in 3 months time  
… Books tend to be ready very very late, and need to deliver by September  
… Need to be as responsive as possible  
… Need to be accessible ready  
… Semantics should be rich as well  
… And of course has to be cost-effective.  
… This is why the answer is AI  
… We use Ai to help us build such a system.  
… What we need to achieve, we need to know what we have.  
… Things like this, we have simple boxes which separate text from image  

> *Elika Etemad:* (Vincent shows a page with photos and some text in various areas, rectangles drawn around each and categorized as text box or image box)

**Vincent Wartelle:** You could also define boxes with semantic view on the page  
… boxes within boxes  
… you can drill into boxes, define boxes to extend between exercise instruction and image which is illustrative of exercise  
… Second output is define classes  
… Classes mean defining semantics, able to capture using analysis  
… This is a simple branch of the page before  
… Then you have to use different algorithm to do that.  
… first is object detection, some already well-known algorithms  
… Then we have semantic segmentation, which uses FCN  
… We have instance segmentation which is a mix of the 2 previous models  
… and we have a natural language process.ing  
… E.g. we need to understand the words in the instructions, because, e.g. it links to another resource.  
… E.g. instructions says "listen to ...", need to know that this links to another resource  
… Third point is to set up mixed data sets.  
… We have more than 1 million images  
… We think we need another data set, which is web scraping.  
… Some websites are very relevant for our algorithm, because they are already structured  
… and is similar to our research  
… Database of exercises  
… Would be interesting to see what is full range of exercises used in education  
… We could use similar data sets as ?  
… It should not be exactly images of education book, but maybe ? or ? would be interesting to analyze  
… So the team now, project started in July and team includes Data scientist which come from different background  
… specialist of data learning  
… We've made some integration of research laboratory  
… we work with ??? which is the atomic energy research center in France  
… and keen on data visualization  
… We have ? which work on data analysis  
… And of course team of developers, which build the whole system to create a future  
… So the roadmap that we have in mind is preliminary study that we've already started  
… running datasets  
… framework validation should be expected ...  
… We're thinking to enter production in 24 months  
… Thanks to our first clients éditions didier  
… Thanks very much  

#### 7.2. Needs and solutions for visual rich publications to be indexable, accessible, searchable (Jean-christophe Burie)
{: #section7-2}

> *ivan>Se:* [slides online](https://w3c.github.io/tokyo18-workshop/slides/W3C-Tokyo_JCBURIE.pdf)

**Jean-Christophe Burie:** Want to be able to index the content of comics  
… The content of manga and french bandes dessinées  
… The content has much text and graphics  
… However, descriptions are usually very semantically poor  
… Publishers only provide some minimal metadata: title, author, editor  
… Very difficult to provide wide description of the content  
… It is very time consuming, and no rule sin the publishing standards for semantic information.  
… It could be interesting to have better access to the content  
… We need to extract semantic content from comics,  
… Why? New devices allow new interactions  
… We can now have interaction with the user. We need tools.  
… But we need to index precisely the content  
… If we have to do that for each new album, it takes too much time.  
… can we automatically do this?  
… THis is what we tried to do.  
… Comic books, it's not a trivial problem  
… Each type have completely different styles, and each author has own styles and own way to draw the characters  
… So we have extra information, graphical information, everything is important  
… Even for the text, we have many different presentations styles of text  
… Develop some ??? using AI and machine learning to understand the content to index the content  
… So, we have begun to look at this topic 7 yrs ago  
… Here we have basic element extraction  
… Al this information can be used  
… Want to understand the content of the panel  
… We have to figure out how to recognize the text, so full text indexing  
… We are able to detect the reading order  
… succession of each  
… Can create link between speech balloon and the character  
… We try to recognize the character. Who is this?  
… 5th, try to recognize the object or place of action. Is it in Tokyo? Somewhere else?  
… So this research concern both digitized comics  
… We have many comics we can digitize, so what can we do ?  
… Other comics are specifically created for digital  
… We have some different approaches  
… To be able to solve problems  
… Figure out difference in style, e.g. between American comics, mangas, bandes dessinée  
… We need a very rich language for description,to have keyword searches and interactions with the user on new devices  
… These three are kind of format are able to index the parts of the comics  
… Three examples are ComicsLM  
… we decided to use them to index  
… Comic Book Markup Language was proposed by John Walsh in 2012  
… Description language using XML syntax  
… CBML  
… Here is the example of a representation of this page  
… So description is able to describe the text and the author  
… and we have some description of the whole page. Here is another one.  
… You can see the captions and balloons  
… Description of the balloon who is speaking, etc.  
… We have some tags to describe basic elements of the comic: panel, balloon, character,  
… We also have some drawbacks  
… Description is purely semantic  
… No information on location of hte items  
… Idea was to manually describe the content of the comics  
… Also not possible to describe all the elements  
… So we have to add some information  
… Here we add information about the face, where is it  
… in the panel  
… If you want to display a double page, reading direction, etc.  
… Well understood the content of the page  
… We nee to know this information  
… Drawbacks of CBML, it has been created to describe digitized contents  
… But born-digital contents, there are several layers, and sometimes short animation  
… For which uses?  
… Can create panel by panel reading for any document  
… improve text-to-speech, braille translation, enhancing contrast of the text, or ad color of text for dyslexic people  
… What you can do is t create services between reader and content, e.g. provide contextual information on character, place  
… But we need to extract the maximal information to make this possible  
… And we need a standard to describe all this information.  
… Conclusion,  
… content of comics is rich  
… New devices offer more opportunities  
… Automatic analysis is needed, but need to develop specific algorithms based on AI and machine learning  
… Need a standard to index correctly the comics  
… Thank you  

#### 7.3. Questions, Discussions
{: #section7-3}

**Tsuneyoshi Kamae:** Can W3C allow or improve the browser so you can implement multiple text-to-speech systems?  
… I like to use when female speaks, a female voice, when male speaks, a male voice  
… This is an easy question  
… Second I want to learn from the author view  

**Florian Rivoal:** I would like to answer the first question.  
… There's a CSS module not about describing the visual layout, but also the audio rendering  
… You can choose which voice, etc.  
… The model is reasonably complete, but nobody has implemented it  

**Tsuneyoshi Kamae:** It's an idea and we're thinking about it. For now we're going to detect some characters. The next step is to organize the characters,  
… Describe this one is a woman, child, etc.  
… We can imagine that we can do this, but we are not there yet.  

**Kazuyuki Ashimura:** As former Activity Lead for Voice activity  
… Speech synthesis, can switch speaker A (female) and speaker B (male)  
… can specify length of of utterance and also can specify the length/speed of the utterance  
… How to indicate that capability?  

**Ivan Herman:** It it something that's also implemented? Comes back to what Florian said  
… CSS has Speech module, but is kind of old capability but not really maintained  
… SSML 1.1 is not really maintained in CSS  

**Ivan Herman:** Is it something that works in browsers?  

**Kazuyuki Ashimura:** Yes. Via speech api  

**Ivan Herman:** The reason I'm asking that is, as I said sometime today, what we do now we realize that audio books is something newer that web applications handle well  
… We need to add something to make that usable  

**Kazuyuki Ashimura:** How to integrate that with data publishing would be the key  

**Ivan Herman:** Something we need to discuss  

> *Elika Etemad:* ?: We work with a company called ???, we have developed an API between rendering, automatic incorporation into EPUB3, etc.

> *Elika Etemad:* ?: you have a feature which could say, this want to be spoken by a man, this one by a female. We use this already

**Tsuneyoshi Kamae:** We do something like this, but ideally when in a comic there are two guys or even girls fighting each other, sometimes like to mix two voices together  
… In the picture can figure out  

> *Elika Etemad:* ?: Need both of what we do, recognize what's happening and describe it to adapt for rendering

> *Elika Etemad:* ?????: Very quick comment about navigation, just to say that the description of CML is have a very ? many many information in the CML, more than the basic stuff we have in the actual guided navigation

### 8. Evolving CSS
{: #section8}

#### 8.1. Difficulties of Browser-Based Pagination & Print (Shinyu Murakami)
{: #section8-1}

> *Ivan Herman:* See [slides online](http://bit.ly/w3css201809)

**Shinyu Murakami:** I am Shinyu Murakami from Vivliostyle  
… my topic is CSS typesetting,  
… My slides are in HTML, and are an example of vivliostyle. It's not fixed layout, it's reflowable  
… here's the table contents with page numbers via CSS generated content  
… as the font size changes the page numbers change as the presentation gets longer  
… my background: developing typesetting languages  
… I developed XTR, a text formatter, in the early 1990s  
… I worked for AntennaHouse for 15 years, supporting both XSL-FO and CSS  
… now I work for Vivliostyle on CSS typesetting  
… CSS is print formatting of publications via CSS  
… there is dedicated software, some using browsers and some not  
… many books are already made  
… technical books from O'Reilly Media  
… this article by Sanders Kleinfield shows how they work, using AntennaHouse formatter  
… the Japanese version of Lea Verou's CSS Secrets book was done with Vivliostyle  
… the layout is entirely html and css  
… Dave Cramer of Hachette uses CSS typesetting for trade books  
… and wrote about this on XML.com  
… manuals and catalogs are produced with CSS typesetting  
… these often use AntennaHouse formatter  
… another example is Wiley online journals  
… here's a sample using Vivliostyle  
… there are several CSS typesetting engines which convert HTML to PDF  
… the main commercial products are Prince, PDFReactor, AntennaHouse, and Versa-Type of Trim-marks Inc. (name changed from Vivliostyle)  
… Open Source engines include  
… WeasyPrint  
… Vivliostyle, which I work on, started with vivliostyle foundation  
… page.js, a new open-source project from pagedmedia.org  
… some formatters are based on browsers  
… they have the advantage of having browser support for most css standards  
… responsive or adaptive design is possible  
… houdini APIs can be used to make next-generation engines  
… but support for print and PDF is not good  
… quality is poor  
… there are problems with font embedding  
… can't embed open type/CFF fonts; they are embedded as type 3, which are not usually accepted by printing houses  
… they are limited to RGB color, instead of CMYK  
… due to subpixel rendering, Chrome cannot output thin border (less than 1px)  
… and they do not support PDF standards like PDF/X1 or PDF accessibility  
… on the other hand, CSS typesetting engines that do not use browser engines have incompatibilities in which paged media drafts they support  
… Pagination on the web needs to be standardized  
… scroll vs pagination should be a user choice  
… in pagination mode, same page layout spec as printing should be used  
… thank you!  

#### 8.2. New Tools for CSS Layout (Rachel Andrews)
{: #section8-2}

> *Ivan Herman:* See [slides online](https://noti.st/rachelandrew/tJeWKI/new-tools-for-css-layout)

**Rachel Andrew:** a bit about me  
… I do web stuff  
… I'm a webdev  
… I've done a lot of teaching and writing about CSS  
… and I get feedback from webdevs back to the CSSWG  
… I want to introduce the major layout methods on the web today  
… we talk a lot about flexbox and grid, but we have other layout modes  
… and other concepts that brought things together  
… the problem today is helping people get past the old hacks  
… that we now have an actual system  
… we've got flexbox, for layout in one dimension , a row OR column  
… which depends on writing mode  
… alignment in flexbox is about distribution of space  
… we're thinking about logical directions, rather than left or right  
… flex is useful even to center single items in both dimensions  
… Flexbox came along first, and people thought it would solve everything  
… but people tried to use flex to make grids, as people had tried to use floats before  
… and that was fragile  
… but now we have CSS grid, for proper two-dimensional layout  
… in rows and columns  
… the things you learn from flex carry over from grid, like box alignment  
… grid allows layout on block and inline axis at the same time  
… you define grid on a parent  
… here we're using the fr unit  
… the direct children of the grid container become grid items  
… be sure to use the firefox grid inspector if you work on this  
… the same alignment properties I used with flex work for grid, too  
… like justify-content and align-content  
… note I'm using inline-size and block-size rather than width and height, so we can easily change writing modes  
… the alignment properties give you a consistent way of aligning things, whether in one or two dimensions  
… this is a true system for layout!  
… for the first time.  
… flex, grid, multicol have consistent sizing, they all use box alignment  
… you can create a design system  
… this element should be flex, this one should be grid... and they can all line up.  
… it makes my job easier.  
… CSSWG is now working on subgrids for level 2 of grid  
… I've written an article on subgrid  
… what's next?  
… logical properties and values  
… Firefox has the best support at the moment  
… what's next? Box alignment in block layout.  
… and I want to know what's important to you?  
… I think regions is a missing piece  
… what are you struggling with? what hasn't been solved yet?  
… all my examples and code are at the URL on the slide.  
… thank you!  

#### 8.3. Designing CSS (Elika Etemad)
{: #section8-3}

> *Ivan Herman:* See [slides online](http://fantasai.inkedblade.net/style/talks/designing-css/#title)

**Elika Etemad:** I'm on the CSSWG for the last 14 years  
… I'm going to talk about designing CSS, rather than designing with CSS  
… I've worked on a lot of specs :)  
… we have some principles of web architecture  
… 1. web is cross-device and cross-platform  
… it should adapt to screens, braille, terminals, print, speech, etc.  
… it should adapt to lores, highres, big screens little screens  
… it needs to be cross-platform.  
… it should adapt to Mac, Linux, Windows, mobile OSs, etc  
… it has to work on multiple implementations  
… it should work on gecko, presto, trident, webkit, servo...  
… new tech for the web should work on multiple browser architectures  
… it has to work with different input devices--mouse, keyboard, voice...  
… 2. The web is the world-wide web  
… it needs to work for all writing modes, all languages, and handle hybrids  
… like mixing languages in documents  
… we might not mix Mongolian and Hebrew, but we do see Arabic and Chinese quite a bit  
… 3. It must be forward and backward compatible  
… it needs to be forward-compatible with future features  
… adding new stuff shouldn't break existing implementations  
… forwards-compatible parsing  
… so you just discard stuff you don't understand when parsing  
… if you don't recognize things, just skip over it and keep going  
… and we have levels not versions  
… the web has one format, which are decades old  
… we can add features, we can refine slightly, but we can't change existing stuff because it would BREAK THE WEB  
… 4. No Data Loss  
… our goal is by default you see all the things  
… visible by default, readable by default  
… 5. Separation of content and style  
… html for content and structure, css for presentation  
… css is a bunch of annotations on the html  
… why?  
… efficiency. putting font tags on every page takes a long time. We tried that and it wasn't fun  
… maintenance. better to fix things in only one place.  
… memory and bandwidth. extracting common elements into a single file avoids repetition  
… accessibility. this allows better support for speech and search; the semantics don't get distorted by styling considerations  
… variability. you can change your design over time.  
… your blog might go through five redesigns, but you don't have to touch the markup  
… how do we do this?  
… we thing about what parts of rendering are structure  
… here's an example from ruby  
… where we can use CSS to choose between different methods of displaying ruby, although the underlying annotation markup is the same  
… here's CSS Zen Garden from a long time ago, which demonstrated the separation of content and style  
… and people submitted different styles for the same content  
… so these five premises are our foundation  
… our fundamental goal is accessibility of information  
… constraints of CSS  
… you're designing a layout size where you don't know the display size or orientation, you might not know the content, or the fonts, or the language  
… you need to create beautiful layouts with no post-processing  
… so we have design principles  
… 1. Flexible. They can't be based on fixed sizes.  
… 2. Powerful. We want interesting layouts that help us understand complex information  
… 3. Robust. It should't break if something goes wrong, like a missing font  
… 4. Understandable.  
… 5. Performant. This pages are loading in real time.  
… how do we do that?  
… here's an example of multi-col layout  
… you can say you want two columns  
… or you can say the columns can be a certain width, and the browser makes as many columns as will fit  
… you could limit the max number  
… here are initial letters, where there's a lot of calculation but you want it simple for the author  
… so we use font metrics  
… and we make sure we avoid overlap  
… we use automatic sizes in CSS  
… here's Jen Simmon's reinterpretation of an old graphic poster  
… but her version is adaptable to different sizes  
… with min-content and max-content and auto  
… design pitfalls of CSS  
… 1. Iterative layout  
… 2. Unsolvable constraints  
… 3. Expensive algos  
… 4. data loss  
… challenges: shape inside  
… what happens if you have text inside. what happens if the font gets bigger. How do you avoid overflow?  
… exclusions have a similar problem  
… where a cycle may be created  
… we want to do regions, but the current proposals require empty elements, which violates separation of content and style  
… the initial grid layout had overlap problems, but we figured out something different which met CSS's design criteria  
… one web for all.  

#### 8.4. Advanced CJK typography, from DTP to Web Layout (Nate McCully)
{: #section8-4}

**Nathaniel McCully:** I work for Adobe Systems  
… I'm going to talk about advanced CJK typography  
… and give some background  
… if your goal for web and css rendering is accessibility and legibility you might not be interested in what I'm saying, because we've accomplished that  
… but there's been lots of evolution in CSS, the expression of art in the presentation of text and images  
… the goals are shifting and changing  
… we can worry about details now  
… CSS gives us lots of cool controls over layout  
… why are so few Japanese websites taking advantage of them?  
… what is it about graphic design in japan that makes it difficult to do in HTML/CSS?  
… maybe the level of detail is difficult for CSS?  
… Let's look at some examples  
… I googled beautiful web design  
… but this site is not particularly beautiful  
… with horrendous typography  
… it's the lowest common denominator  
… here's a site for hot springs  
… where the print brochures are very high-design  
… but on the web it looks great, but it's images not life text  
… and the text has some problems--horizontal comma in vertical writing, for example  
… so I asked a friend, who pointed me to a different site  
… which has much better vertical text  
… but each thing is a span, with lots of negative letter spacing  
… and it reminded me of desktop publishing in the 1990s  
… in Quark and InDesign, every run of text had be hand-kerned  
… because the programs didn't support Japan's design language  
… so we set out to fix that  
… we've been here before  

> *Elika Etemad:* [http://sosus.co.jp/](http://sosus.co.jp/)

**Nathaniel McCully:** so we can learn about what the web can do  
… in the 90s, DTP still lacked critical features  

> *Elika Etemad:* [https://tadaya.net/](https://tadaya.net/)

**Nathaniel McCully:** the fonts had problems  
… everything used roman baselines  
… origin was in the wrong place  
… Grid layout in DTP  
… there was an exchange of ideas between Euro and Japanese grid systems  
… but the grid systems in DTP software wasn't good enough to do what phototypesetting operators in japan were doing  
… they were using the em-box  
… there was an offset from the bottom of the embox to the roman baseline, which caused trouble with digital fonts  
… we looked at people in Japan using proprietary systems what they used  
… they showed us a grid based on body-text sizes, so there was an implicit character grid  
… everything else is sized relative to the character grid  
… the units were in millimeters  
… or units that would convert to mm (q)  
… so there needs to be a way to express design in emboxes  
… DTP evolved  
… it's all about control of white space  
… even the initial opening dialog in InDesign which asked for margins did not help people. the margins came from the design, not before the design  
… here's some calligraphy, which says "steep cliff" and you can see it in the calligraphy  
… the interplay of space is very important  
… I'm interested in history, and so looked for analogs from before typesetting  
… even ads today have very focused white space, following a set of rules which are NOT ascent/descent/baseline  
… we don't yet have consistency between browsers  
… the designer needs to express their intent as input to the algorithm  
… every result must be faithful to the design, which means we need better layout algorithms and standards  
… and there are still missing components  
… like having actual Japanese font metrics rather than using latin metrics  
… thank you!  

#### 8.5. Questions, Discussions
{: #section8-5}

**Laurent Le Meur:** re: paged media  
… we are readium developers  
… we have to do dynamic pagination for EPUB in reflow mode  
… CSS paged media we would like to use it, but we can't because there's uneven support of the technology in the browsers  
… no support for size property in paged media, for example  
… so in readium we use multicol to paginate  
… and the implementations are flowed, especially for i18n  
… we can't stack pages horizontally in vertical writing, except in safari  
… but we don't see much movement from the browsers  
… we want publications to be first-class citizens of the web  
… but we need some basic features evenly in all browsers, and CSS paged media is one of the technologies, along with grid and flex  
… we need implementations too  

**Elika Etemad:** I agree :)  
… the problem is that most browser devs are not excited about this  
… they don't perceive the need from their customer base, as they don't see ebooks as their issue  
… it's been a low priority for my entire history  
… the only  progress was when HP had a rep on the CSSWG and working on the spec, and paying a dev to fix printing bugs in Mozilla  
… Apple is the most interested, because they have iBooks  
… my advice is to follow the model of the Japanese publishing industry used for writing modes  
… getting in front of browser dev teams, saying we are your customers  
… and so the devs and their management understand  
… and they also needed to put resources into underfunded activities like building a test suite and sponsoring spec work  
… it was a big project, and Japanese industry helped make it happen  

**Florian Rivoal:** I agree with both of you  
… the difficulty with multicol and columns going to the wrong place  
… it's a problem on the web too  
… I have a half-written draft of a cleaner webkit fix  
… if it's only happening because of interested individuals, it will move slowly  
… you need resources to push things forward  
… there are companies that work on browser engines that could be paid like Igalia  

**Luc Audrain:** someday it might be possible to do very sophisticated layouts directly in HTML and CSS  
… another pass would be as all these sophisticated books are done in InDesign, would it be possible to imagine a conversion of an InDesign page layout  
… to convert it to HTML/CSS but maybe it will lack some implementations  
… and then this conversion could give us a pretty good version of the page as it is in InDesign  
… and then it will adapt automatically  
… is this something we could figure out?  

**Nathaniel McCully:** I would love for that to happen  
… but designers who care about design intent in print often don't understand fluid design  
… we need to help the design community understand that dynamically changing design needs tools like the grid inspector  
… the coding of each css feature is still unreachable to many people  
… manga and visual storytelling, maybe they're already in that mindset, placing a dynamic thing into a 2d model  
… those are the people who will figure this out  

**Rachel Andrew:** the problem with visual builders of web stuff  
… we have the same issue with dreamweaver or wysiwyg HTML editors  
… and then they freak out when it changes size  
… it's hard for the tools to help with adapting stuff  
… maybe it's easier now we have grid  
… they think the example layout they design will be seen by everyone  

**Elika Etemad:** I don't think that converting from InDesign to what you talk about  
… it's built on fixed-size boxes  
… and regions  
… and we don't have those things in CSS  
… the reflow in CSS is very sophisticated  
… that can't be expressed in InDesign  
… you could probably do media queries and scaling  
… but when you have overlap or flex fractions, and minmax  
… and different levels of squishiness, indesign doesn't know about that  
… but I don't think that InDesign is the tool for this  

### 9. Wrap-up Discussions
{: #section9}

**Samuel Petit:** Wanted to ask for feedback about our vocabulary for comics presentation.  

**Makoto Murata:** On Behalf of APL, want to make a comment.  
… We like the idea of making an open standard for describing this kind of art, but not ready to discuss details of such things.  
… Starting with taxonomy is a good idea.  
… We're interested in maybe pursuing in a Community Group at W3C  

**Ivan Herman:** Community Group at W3C is simple thing, they create reports, not standards. They're an incubation space for developing together, provides just some basic infrastructure like wiki, mailing list. Takes about 1hr to create, and is free to participate.  

**Laurent Le Meur:** We at EDRLab are committed to join a CG at W3C, seems like a good idea.  
… We got a lot of feedback, and would be interesting to work on a complete CSS implementation  
… Good place to make the taxonomy, use case list, etc. more visible and to make it more in the direction of the Web.  
… We completely agree and we will do it!  

**Laurent Le Meur:** Discussed with Rachel that authors should be involved in such a work  
… Working on a taxonomy is the best time to join.  
… So even if authors are afraid of technical environment of W3C, working on taxonomy can be more approachable  

**Samuel Petit:** we at IDPF co-organized with Hachette and Kodansha a workshop  
… We succeeded to have ? on stage  
… It is always difficult in technical points, but if the point is taxonomy and use cases, this is more understandable for authors and is a better starting point  

**Ivan Herman:** So let's agree that we will will work on this next week. Write a text on what you want to achieve, and we will distribute to workshop participants to start.  

**Florian Rivoal:** We could have a breakout session at TPAC, and can announce the session at TPAC. Hard to do anything else.  

**Richard Ishida:** As an outsider, it seems like you are all going in different directions  
… Seems like movement needs to harmonize the different actors and parts of the technology  
… Lots of different things happening, but all happening to solve a problem that's real  
… Might have better leverage if more coordinated  

> *Elika Etemad:* ???: Two tracks in the workshop it seems. One is digitizing comics. Other is evolution of ebook layout, mostly text-heavy work on screen.

> *Elika Etemad:* ???: I think we would have to create two trends.

> *Elika Etemad:* ???: We can't mix in the CG things about responsive layout and the fixed-layout comics

**Ivan Herman:** CG would be a first forum for this discussion.  
… It might turn out that there are two directions that represent distinct work, then there's room for another CG.  
… Additionally, we have to be very careful that the work you do — whether one or two CGs, doesn't matter — make sure that it is synchronized with the relevant WGs  
… Set up a regular exchange of information  
… Once you have figured out where to apply the pressure, don't let up.  

**Dave Cramer:** My concern about splitting is that this really is One Web.  
… There were lots of good presentations about different points on the spectrum between responsive presentations and fixed layout, don't want to artificially divide the community  

**Florian Rivoal:** If our goal is to find one true format for books, then it's going to be a huge project.  
… But that is not my impression of what EDRLab is trying to do  
… More that they are trying to solve some specific subset of the problem.  
… If we try to solve everything, effort will fail.  
… But cost-effective production of commonly-found paradigms, then it's quite possible.  
… and we can put things out of scope and achieve something.  

**Luc Audrain:** I completely agree. We have to focus.  
… Also with respect to fixed layout for e.g. textbooks etc, we don't need a new Community Group, we need to join the CSS Working Group. The publishing industry needs to be there, to apply the pressure.  

**Ivan Herman:** How do we convince the publishing industry that this is what has to happen.  
… If we just say something, say that "we should do this" and stop there, then nothing happens.  
… We need to find the people who can get involved, and get them involved.  
… And not done yet, need to find way to communicate with publishing industry in useful, proactive way.  
… You who are in this industry, how can we convince people that this must be done?  

**Florian Rivoal:** Yes, we have to make it happen; yes we have to do work.  
… But also, want to point out that not everything happens in a conference room.  
… CSSWG operates in a hybrid manner.  
… Yes we have F2F meetings, and some work happens there. But other work happens in telecons. Other work happens in GitHub.  
… Some groups focused on one work mode, CSS WG works in multiple. If you don't like meetings don't have to attend meetings. If you work best in meetings, come attend the meetings.  

**Ivan Herman:** Inviting to join the *virtual* table.  

**Nathaniel McCully:** I was inspired to see the creativity in the Web space, in the media space. It's exciting to see what's possible.  
… I think proofs of concept, small groups of people trying to achieve something, and then getting the word out will draw people to it.  
… Way to convince people, friends, publishing industry to join and participate.  
… That kind of draw, plus stick of if you don't adapt you die, is a good motivation.  

**Luc Audrain:** I'm afraid such sophisticated books are a very small portion of the industry.  
… It's a very big use case for us to be able to have some transformation from the indesign page to something that is CSS implementation.  

**Nathaniel McCully:** You come from an industry that is one of the most conservative that I have ever seen. very hard to convince anyone to move anywhere.  
… But competition is a way to encourage innovation.  
… Define yourself as leaders, as thought leaders.  

**Luc Audrain:** We are successful with paper books.  

**Florian Rivoal:** Aside from Hachette, another company that has embraced the Web is O'Reilly.  
… Yes, their layouts are relatively simple. Easier to be pioneers in their approach. Using HTMl + CSS in production.  

**Ivan Herman:** There are different publishers which have different roles and business models than books.  
… THe publishing industry is way more diverse than we laypeople realize  

**Florian Rivoal:** It has multiple business models, but some business models would only be possible in moving to the Web.  

**Luc Audrain:** We will have this as the next item on the agenda of publishing business group  

**Ivan Herman:** For those of you who represent bigger publishers, a way to join work at W3C without joining as a full member, can join the business group.  
… I think there were some other ideas and problems that came up in these 1.5 days  
… e.g. Bobby's issue about fonts and relationship with font community  
… Worth discussing what and how to do there.  

**Florian Rivoal:** Nat's presentation showed fonts being more and more important  
… should relate better fonts community and w3c community  

**Makoto Murata:** SC29 is committee responsible for maintaining OpenType specification  
… And second is JIS, I called today they are willing to have a relationship with W3C  

**Elika Etemad:** having some kind of community for fonts is important  
… it comes on many topics, such as what bobby discussed  
… it also comes up because we lack font metrics for many writing systems, and cannot do good layout without that  
… so we need a relation / liaison with font people  
… I was at the Typo conference, talking about this need  
… and font people also didn't know how to report problems back to us  
… I think this all together could be a community of people who work on fonts, and for people in the css and the web.  
… we need to talk to people who make the open type specification, but also to font authors, so that we can have discussion about problematic fonts  

**Ivan Herman:** so what should we do next? It sounds like we need to formal liaison, but also more.  

**Elika Etemad:** Maybe similarly to JL-TF, we may need a community of experts, so that we can talk to them  
… I have never succeeded in finding where they are, what their home page is  

**Ivan Herman:** Maybe talk to Vlad  

**Elika Etemad:** also Chris Lilley  

**Nathaniel McCully:** CC me  

**Florian Rivoal:** I'm happy to be in the loop too  

**Myles Maxfield:** isn't there a web fonts working group?  

**Ivan Herman:** Yes, Chris is that group's team contact, and Vlad is the co-chair  
… but the scope of that group is different  

**Bobby Tung:** I think it is a good time to get people together  

**Florian Rivoal:** Short repeat of what said yesterday, but as talking about what to do next, want to remind people of r12a's invitation to join the JLTF and other Internationalization Activities  

**Elika Etemad:** And if you don't know how to get involved, talk to Richard Ishida or Kida-san  

**Richard Ishida:** When I was learning about paged media was paged media for epub or paged media for PDF.  
… I ended up with the wrong at-rules. One for print, but then I had to write the same rules for epub as for PDF generation in a different part of the style sheet, and it seemed there should be a single paged media media query and maybe get rid of the print one  

**Florian Rivoal:** I have an entire presentation on that topic, but short version is that media types like print are not granular enough  
… We have moved from media types to media features, you can ask "is this interactive?" "can I click on small things?" "Can I change it after it's rendered? Does it have fast enough updates to animate?"  
… We have a fair range of things in the spec, but that's the general approach  
… If you notice features of the media environment that you need to query but can't, then let us know in the CSSWG.  

> *Elika Etemad:* [https://www.w3.org/TR/mediaqueries-4/#mf-overflow-block](https://www.w3.org/TR/mediaqueries-4/#mf-overflow-block)

**Dave Cramer:** Wanted to go back to organizational questions from a moment ago.  
… Talked about having a group to discuss font issues and interface with CSSWG + Font vendors + OpenType  
… Talked about group to discuss manga and comics and digitization  
… we came up with many suggestions in the workshop, how do we document them?  
… Many *LREQ groups, but who will be end-user of information they generate?  

> *Florian Rivoal:* If you would like to know more, here is a video of a [20 minute presentation I made about the question richard asked about Media Queries](https://www.dotconferences.com/2017/11/florian-rivoal-media-queries-4).

**Dave Cramer:** How do we organize and coordinate these groups, and make sure information flows form one to the other?  

> *Makoto Murata:* ISO/IEC JTC1/SC29

**Ivan Herman:** Very good question, I don't have a direct answer. It's a problem at the W3C level  
… All the groups directly on publications or in the CGs, have a one-stop place where there is a one-stop place with a good set of references.  
… Requires a lot of work for people to gather these  

**Elika Etemad:** I think there are several approaches to coordination  
… don't have groups that too small, there won't be enough people to link the communities, and not enough overlap among the topics to create integration  
… to have coordination between two groups, you need either someone who is in both groups, or 2 people in each group who frequently talk to eachother  
… just joining the group and being passive isn't quite sufficient to establish a link, you need to be meaningfully involved in both  
… example: Dave Cramer links CSS-WG and Publishing  
… example2: Rachel Andrew links the CSS-WG and the broader web developer community  
… example3: I was the liaison between CSS and EPUB  
… so formal liaison is the solution, but for them to work active involvement is required  

**Ivan Herman:** there are many people who are active in Publishing CG / WG / BG, but we need to be systematic when following that pattern  

**Laurent Le Meur:** For coordination at the top, we need a new publishing champion  
… for the rest, we need blogs, hash tags  

**Bobby Tung:** different topic: based on the presentations yesterday, should we work on the description language for manga?  

**Makoto Murata:** APL isn't interested  

**Laurent Le Meur:** XML is not very popular at the moment  
… so I think it would have to be out of W3C  

**Ivan Herman:** I don't think that's true. If there is a community, we can have a group. XML is gone on the front end, but there's nothing stopping it in the backend, interchange, etc  
… it is true that front-end web development has moved away from XML, but let's not overgeneralize  

**Dave Cramer:** back on coordination  
… I would like to have a some a repository where we can post issues to triage things  

**Elika Etemad:** who is "we"?  
… there are plenty of repos to track issues on many topics. What is the new repo for?  

**Dave Cramer:** sometimes it's not clear where some issues fit, so a place to do triage  

**Elika Etemad:** but what's the scope? this work shop? all workshops? anything publishing ? any topic?  

**Ivan Herman:** the publishing business group is sort of meant to serve that role, maybe it could have a repo  

**Dave Cramer:** maybe  

**Ivan Herman:** Luc, please talk to the co-chair of the business group:-)  

### 10. closing
{: #section10}

**Ivan Herman:** [explains what happens next] report will be posted in 2 or 3 weeks, minutes will be cleaned up, community group will be created, and everybody who was registered will be notified by email  

---



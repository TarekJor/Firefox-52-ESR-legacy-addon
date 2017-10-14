# Firefox53ESR-legacy-addons (WIP) created: 2017-10...
# Index 
- [Why? (reason of this)](#why-reason-of-this)
- [Main Objective](#main-objective)
- [Why?, really](#why)
- [Introduction](#introduction)
- [Firefox Places  bookmarks, history- query syntax](#firefox-places-bookmarks-history--query-syntax)
- [Addons Mozilla (AMO) state](#addons-mozilla-amo-amo-for-now-state)
- [Method of Archiving](#method-of-archiving)
- [AMO and killed addons](#amo-and-killed-addons)
- [Notice](#notice)
- [Distribution statement](#distribution-statement)
- [Objectives focus](#objectives-focus)
- [Projects ideas-collaboration](#projects-ideas-collaboration)
- [Sources](#sources)
- [Other failures and bad decisions by Mozilla](#other-failures-and-bad-decisions-by-mozilla)
- [Hall Of Fame Addons XUL-based that will be purged probably](#list-of-huge-valuable-and-hall-of-fame-addons-that-would-be-purged-xul-based-when-mozilla-firefox-57-build-reach-stable-deploy)
- [Repository structure](#repository-structure-on-xpi)
- [Examples of authors killing creations](#examples-of-authors-killing-creations)
- [Important bugfixes on Firefox Places bookmarks, history](#important-bugfixes-on-firefox-places-bookmarks-history-and-other-key-features)
- [About current development community-teams state on modern webBrowsers](#about-current-development-team-state-on-modern-webbrowsers)
- [About history expiration (key though)](#about-history-expiration-key-though)
- [Sync and unify databases](#sync--unification-database1)
- [Observation (WIP) state](#observation-wip-state)

## Why? (reason of this)

Mozilla will be (soon) this November-2017 purge XUL support for addons, force "WebExtensions" only (without being a replacer, non-proper mature technology and disrespectul to community devs (veterans, and loyal supporters) => THIS IS A BAD MOVE, Mozilla.

## Main Objective
Convince Mozilla and Mozillians to create some legacy.mozilla.org/addons domain to migrate all deprecaed, obsolete and abandonware froma addons.mozilla.org (then they clean up main site, but without purging addons)
Seems some developers are angry and they are using "IKIBIM" (I Kill It Because Is Mine") logic and purging they creations from Mozilla site (and there is not mirror, so what we could do (webArchiving vs copyRight, the decision is clear).

## Introduction 
A curated list and XPI files of Mozilla Firefox browser extensions, addons, themes from addons.mozilla.org, before XUL-based purge blackout

## Why?
*First and example of what we loose on new software (Rapid Development, rapid deprecation (with deprecated features, and functionality capped without blink, no hesitation)

### Firefox Places (bookmarks, history) & query syntax

Firefox is the only browser that support tag bookmarks in a consistent way without folder=tags cheating and good implemented (could be improved, yes)
Firefox addons killed with good functionality like
related to **"Patch For Library" and "TagSieve" and "SearchPlaces" addons**
[Firefox Places query-syntax on MozillaZine thread ](http://forums.mozillazine.org/viewtopic.php?t=629560)

this allow use powerfull tagging in firefox places without external apps or web/apps, locally (is a plus) and using places.sqlite as urls container (easy enought) in addition to this Pinboard Diigo, Delicious (RIP) and others seems to allow some type of tagging and formats, yeah i know exist a very large number of cms-based, proyects, Delicious clones, desktop apps, etc but hey, this is cross platform and is on local desktop browser (easy to mantain) fast enough and connected to browser

tagging is a must-have for me and smartFolders or virtualFolders as "auto.tagging" container too 

*I interested on browsers customization because we use them all the time, the most of the time, and productivity integration with addons and configs is a must have for me in my research and work (so yes, i am a browser poweruser who makes magic with software)

## [Addons Mozilla (AMO)](http://addons.mozilla.org/) (AMO for now) state
aprox 20.900 extensions (addons) 
aprox 1000 pages with 20 extensions (per.page)
seems that only  first 1000 addons ordered by users usage number are relevant at first batch.

If a Diogenes Syndrome method is applied we could go until page.300 (6000 addons) total is 20.900 so is about a 33% saved and relevant (not bad meme here)
- Curation and hierarchy is a need because even "saving everything" approach, for me webArchiving must be useful not only "Diogenes Syndrome"
- Curation by hierarchy of "important ones"
logic: more users (more key feature, more value, more needed etc) => this is false globally but applies good for relevance => popularity => masses => users volume usage so (more quality, importance)
  
- **Most used addon is (by far) Adblock Plus with 14.4M (millions) of users (aprox)**
- Followed by **Video Download Helper 3.7M (millions) and NoScript 1.7M (millions) of users (aprox)** we see that difference is notable even in most used addons (it is known that **AdBlock is a demanded "IT friend install me an ad blocker"**), **uBLock** is about **4M (millions)** Adblock is better than uBlock? (i think not) but this is because "inertia" of "who first arrive" or "veteran" and **AdBlock** name seems more "known than > *uBlock* (seems to be an explaination)

 (this is for explain the selected method of curation) and at least "non automation" beyond less x user usage number: [updated to 2017-10]
- At page 10 (10*20) => 200 addons later aprox usage is about 50k (50.000 users)
- At page 50 (50*20) => 1000 addons later aprox usage is about 6k (6000 users)
- 1000 addons and 6000 users as bottom limit (seems fine) to "keep confidence" about archiving "useful addons"
because logic: "if users ( a decent number don't use an addon, therefore is not useful, good etc")
 - At page 100 (2000 users per addon) and 2000 addons later (minor addons maybe useful, but non key features i think
- At page 200 (aprox 400 users per addon) and 4000 addons later (i dont see much valuable but, we could SaveThem'all hahaha
- At page 300 (aprox 150 users per addon) and 6000 addons later (maybe some gems, which nobody knows has good ideas for new features)
- At page 500 (aprox 30 users per addon, this is low enought to say, addons beyond this dont deserve our time, with exception of abandon but interesting or exceptions "exceptionale" so this would be my limit

Conclusion: 
## Method of archiving
 
I use webScraping and webMining to extract a graph of words and structured data from Mozilla and group addons with keywords in a graph then y design a tree of features and take ideas for example:

 - cookies, management, backup, edit, etc 
 - password, with tags, sync, keepass, integration
 - bookmarks, tags, sync, edit, gui 
 - custmization, theme 
 - search, engine, backup 
 - backup, FEBE, CLEO, OPIE, places, CSV, import, export
  
  
*this is easy, fast and never backup "shit" addons, take bes on one niche or category, for example **InstantFox** on custom search/engines
 
## AMO and killed addons

What about addons not listed because mozilla or author kill them (like SearchPlaces, Zotero (the integrated Firefox version, now is standalone) or others like Patch For Library (which is important for me for personal purposes), well, you must reverse search on web archives or MozillaZine, gHacks old news, to retrieve "some useful addons" like Shelve, that masses never know about.

## Notice
Current state of this (document) is imperfect and RAW as RAW meat, but will be updated (cooked) continuously.

This document is produced (now) with voice dictation, Markdown microsyntax with symbols is easy for keyboard but for now not best to add symbols and block delimiters (yeah, that explains the ugly RAW format and disorder), but in terms of productivity this was created on a few minutes (as raw sketch notes), think about it .

### Notice: (WIP) (non well-formatted, yet, bad grammar and typos for sure)
## Distribution statement

I respect author rights as original source code creator open source licenses, credit etc, but NO about "copyright" literal as "distribution" exclusivity => STATEMENT: I reject totally deeply ( add more adverbs and adjectives here) the logic: "I kill it, I abandon it because it is my creation", "I kill it because it is mine" this is not acceptable for my as some software has unique and useful social value beyond individual selfish reasons, and this are open source and GPL, etc based packages.

## Objectives (focus)

- FirefoxPLaces enhancements (bookmarks, history) => key features as SearchPlaces, ParentFolder, GoParentFolder, advanced search and considering fork places or something, (Mozilla seems to go Chromium-twin path, and places+tagging is a distintive and differential feature)

- XUL customization (bars, sliders, sidebars, external apps, ChatZilla, FireSSH, FireFTP, etc, integrations

- Rescue FEBE, CLEO, OPIE as backup profile key features
- FEBE => key feature (must be on stable build as internal non an addon!!!)
- SearchPlaces => non replacers yet, even Patch For Library (addon) to edit places.uris is deleted by author on addons.mozilla.org.
- Pre Firefox57 refugees have stable addons repository and backup 
- Cookies Manager and other cookies tools
- Roomy Bookmarks Toolbar and other addons for customization.
- Classic Theme Restorer
- Scripts and UserChrome.css hacks and customization and Stylish Userstyles.
... to be continued
## Projects ideas-collaboration

- **ArchiveTeam fellas** (help to bulk archive addons, descriptions and source.code) for further analysis and experiments (useful software)
- Integration **WaterFox** team (seems solid at least to support a **Firefox 53 ESR** (pre 56-57 build) with **XUL-based legacy addons support**
- **Pale Moon** (seems outdated or obsolete, more research is needed)

Any fella who wants contribute 

## Sources
- [MozillaZine](http://mozillazine.com/) -  (Firefox powerUsers community)
- [Reddit](http://reddit.com) (subreddits: Firefox, Mozilla, WaterFox... etc)
- [AMO](http://addons.mozilla.org/) (primary source)
- [ChromeWebstore](https://chrome.google.com/webstore) (WebExtensions replacers and Chromium|Blink-alternatives) (yeah is the enemy-competitor :P)
- Www/mirrors around the web, ftps etc
- [GHacks](http://ghacks.com)- For news about Firefox, Waterfox etc (seems **Martin Brickmann** is very interested on Firefox, browsers etc), good source
- 
## Other failures and bad decisions by **Mozilla**
- FirefoxOS aka Boot2Gecko
- Australis (for me that is a good decision, is not a mistake
- Kill XUL-based addons without proper replacers

## List of HUGE VALUABLE and "Hall Of Fame" addons that would be purged (XUL-based) when Mozilla Firefox 57 build reach stable deploy
(examples)

- **SyncPlaces** => "replacers" as third party sync (**EverSync**,**Xmarks**) and **Firefox Sync** (aka Firefox Accounts, **Firefox Weave**)
- **CheckPlaces** => partially replaced with **Bookmarks-Organizer**
- **TagShifter** => **TagSieve** - search ith tags (boolean operations and filters from sideBar)
- **Cookies Manager**
- **Form History Control** - Edit forms history and backup, export, import
- **FireFTP** 
- **FireSSH**
- **DownThemAll** - a core addon (insert here core feature statement).
- **FEBE** - a core addon for backups schedule, (must be a core feature for god shake) by Chuck Baker.
- **SQLite Manager**  - yeah, this is so useful and will be obsolete.
... to be continued
**Observation:** Most veteran authors are "angry" "preparing silencers" (non literally I suppose) about **Mozilla move of deprecating XUL-based support without proper replacer on functional and features context**.
Mozilla logic (lack of logic): I remove one technology without replacing ith proper one ( the real reason is scary, about Chromium-like, lack of personality, it is a conspiracy LOL)

## Repository structure on ../xpi

Original files (untouched, checksum-friendly) XPI (zip-based format) last stable versions.
Content:
- Addons (aka extensions, legacy XUL-based)
- completeThemes (not **Persona Themes** lighweight make up)

Personal list of must have (my opinon), not "complete list" by now.
Maybe CSV text file (name,version,author,Firefox version compatibility) to manage more easy and a Google Docs SpreadSheet to social collaboration (WIP)

## Examples of authors killing creations
### logic: I kill it because I created it

[PatchForLibrary](https://addons.mozilla.org/en-US/firefox/addon/patch-for-library/) => by  **White Alice0775**
[SearchPlaces](https://addons.mozilla.org/en-US/firefox/addon/SearchPlaces/)=> by **Andy Halford**

## Important bugFixes on Firefox places (bookmarks, history) and other key features
... be continued

## About current development team state on modern webBrowsers

Chromium, Webkit, Firefox, Mozilla, Opera, all main browsers are in hands of "non be evil" companies, corporations, even Mozilla last moves seems the opposite Philosophy of users and devs first (devs are users too) and XUL-addons are used mostly by powerUsers daily and are powerful enought to deserve proper respect, support and replacing before killing them

There is not a browser development powered by a real P2P community (Chromium Waterfox or Mozilla is at the end corporation-driven), all are forks that follow big brother (in all senses), i think would be great if open source community joins to improve the browser development (in terms of code management, compatibility, customization, performance) etc

## About History expiration (key though) 

When I see, Chromium and Chrome force limitation about remember history (90 days or three months old) i have backups but that makes me angry even today (withut proper advice or notice), some see browser history as a "diary of web browsing" and it is useful for agile bookmarking etc (wihout the compulsive star syndrome of push bookmark button million times) that was a key moment, i realize that i want to preserve my data and control expirations, and prevent "SHIT" and "mess" with my things by "smart app" that though for me and decides for me.

Next key moment is when I realize sync services(*1) like Chrome Sync or Firefox Sync even Pinboard(interesting) or Xmarks (creepy) make me dependant of third party services, non zero-knowledge, non privacy-friendly and even bad performance, because if you have bookmarks, urls or history ith about 10k order (n*10k) all seems to work bad

But even **bookmarking on current modern browsers is bad and old**, lack of features (and I think it is a core one).

## Sync & unification database(1)

Eventually I **feel forced to self hosted customized web apps**, and my **own server**, but integration with browser is a need for me (visited links mark, bookmarked links markx etc....) and sync across devices, mobile etc, so internal sync is a need (but I prefer my own hosted like **NextCloud**, **Owncloud** solutions or others than a **Xmarks** or **EverSync**, **Firefox Sync** **Chrome Sync*  or external service like **Pinboard** as API solution.

# Observation (WIP state)

This document is an expression of some chaos, ideas and thoughs, but chaos tends to relation and order, so check out in a few weeks and see the light (RAW state will become "state of art" ;)

PD: Initially this is a "mess" as diffuse graph of chaotic thoughs, but eventually will have many sense

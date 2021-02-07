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

## [Why? (reason of this)](#main-objective)

Mozilla will be (soon, this November-2017)
- Purge XUL, XPCOM support for addons (Firefox extensions, themes)
- Force "WebExtensions" only for addons development (WebExtensions technology are not a total a replacer, and are non-proper mature technology
- Very disrespectul to community devs (veterans, and loyal supporters) => THIS IS A BAD MOVE, Mozilla.

As an example effort what we will loose on new software (Rapid Development, Rapid deprecation) driven (deprecated features, not end user support and functionality capped without blink, no hesitation)
As an example to archive "SHIT" even beyond "copyright" demands or author desires (existence of utility it is more important than selfish reasons)

## Introduction 
A curated list and XPI files of Mozilla Firefox browser extensions, addons, themes from addons.mozilla.org, before XUL-based purge blackout.
Thougs about webArchiving and references, while working in this project
Thoughs about social collaboration and open source development context, egos and shit, ForkSyndrome (but not in co-working environment)

## Objective
- First, archive personal used addons for backup purposes, in case they dissapear soon from official repos
- Convince some Mozillians => Mozilla, to create some legacy.mozilla.org/addons domain to migrate all deprecaed, obsolete and abandonware from addons.mozilla.org (then they clean up main site, but without purging addons)
- STOP the "IKIBIM", some developers are angry and they are using "IKIBIM" (I Kill It Because Is Mine") logic and purging they creations from Mozilla site (and there is not mirror, so what we could do (webArchiving vs copyRight, the decision is clear).
- Easy life for Firefox users as pre-FF57 refugees, whom want preserve workplace for a few month or years using "**Firefox 53 ESR builds**"

## Repository structure [WIP]

/xpi => xpi files
	- checksum identical from addons.mozilla.org source
	- last stable version, & sometimes last beta version

/www => archive snapshots of url.resources 
	- posts, threads, etc 
	- mirrors from archive.is or Wayback Machine
	- local onePage oneFile snapshots in formats (.MHT, .MHTML, .MAFF)
	- * oneFile formats are more easy to share and mantain (contain HTML, CSS etc, and rendered page)

/metadata => www log and references [WIP]
	- XPI log and references
	- database => Naming + lastVersionCompatible
	- Naming using "FEBE-like" schema (camelCase.name + {version}) => example NoScript{5.1.2}.xpi
## Key features 
- Firefox Places component (bookmarks, history) enhancements and compatibility
- SearchPlaces, CheckPlaces, SyncPlaces, Bookmarks Organizer
- webarchiving standAlone on Firefox locally: MHT, UnMHT, MAFF, Zotero, Shelve, ScrapBook preserved
- HallOfFame addons like FEBE, Classic Theme Restorer, FireFTP, FireSSH... etc (see extension.list [WIP])


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

## Sources (see [sources](/md/SOURCEs.md))
## Questions (see [questions](/md/QUESTIONs..md))
## [IDEAs to improve Mozilla and Firefox(/md/IDEAs to improve Mozilla and Firefox.md]
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

There is not a browser development powered by a real P2P community (Chromium, Opera or Mozilla are at the end corporation-driven), all are forks that follow big brother (in all senses), i think would be great if open source community joins to improve the browser development (in terms of code management, compatibility, customization, performance) etc

My only hope, at least until find replacers or XUL support long time is **WaterFox**, seems better than **Pale Moon** (this seems obsolete and outdated like an old Firefox ESR build, small team, and lack of resources, difficult to re merge patches from Mozilla code etc on modified source code base etc)

## About History expiration (key though) 

When I see, Chromium and Chrome force the limitation about remember history (90 days or three months old) I have backups but that makes me angry even today (without proper advice or notice), some see browser history as a "diary of web browsing" and it is useful for agile bookmarking etc (wihout the compulsive star syndrome of push bookmark button million times) that was a key moment, i realize that i want to preserve my data and control expirations, and prevent "SHIT" and "mess" with my things by "smart app" that though for me and decides for me.

Next key moment is when I realize sync services like Chrome Sync or Firefox Sync even Pinboard(interesting) or Xmarks (creepy) make me dependant of third party services, non zero-knowledge, non privacy-friendly and even bad performance, because if you have bookmarks, urls or history ith about 10k order (n*10k) all seems to work bad

But even **bookmarking on current modern browsers is bad and old**, lack of features (and I think it is a core one).

## Sync & unification database(1)

Eventually I **feel forced to self hosted customized web apps**, and my **own server**, but integration with browser is a need for me (visited links mark, bookmarked links markx etc....) and sync across devices, mobile etc, so internal sync is a need (but I prefer my own hosted like **NextCloud**, **Owncloud** solutions or others than a **Xmarks** or **EverSync**, **Firefox Sync** **Chrome Sync*  or external service like **Pinboard** as API solution.

# Observation (WIP state)

This document is an expression of some chaos, ideas and thoughs, but chaos tends to relation and order, so check out in a few weeks and see the light (RAW state will become "state of art" ;)

PD: Initially this is a "mess" as diffuse graph of chaotic thoughs, but eventually will have many sense

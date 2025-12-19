
<!-- vim: set foldmethod=marker fmr=###,--- :-->

*Updated 19 December 2025 · Toulouse*

![Pwika: SVG-based websites built in Adobe Illustrator][logo]

*We're still cleaning up and organizing our repos — if you need help or want to contribute, contact us at hey@pwika.co with an m at the end.*

[logo]: http://files.pwika.com/github/github-banner.png "Pwika: SVG-based websites built in Adobe Illustrator"

**Pwika** is a radical new way to build websites, using the power of **Adobe Illustrator** to generate precision SVG pages.

With Pwika, building a website is **incredibly fast**, and you can create amazing content that would be impossible with other tools.

**"I really, really, really, really, really, really, really, really LOVE THIS. Thank you for making this!"**  
*—A Space Cowboi*

You'll love **Pwika** too:

- if you know Illustrator, you're already an expert
- build websites in 80-90% less time
- the techniques of professional design work natively, in the page
- no debugging or verification necessary
- compelling animation with no programming

Pwika sites are **real websites**:

- Google-indexable
- accessible
- selectable text
- linked images

**"The workflow behind this is super innovative — from your SVG program directly to the web… for a new idea, damn!"**  
*—Geena T.*

---
### The structure of Pwika

There are basically three elements to Pwika:
1. the Illustrator panel that saves SVG files
2. the server application that displays the SVG files as a website
3. a sync application that uploads the SVG files to the server (macOS only)

---
### 1. The Illustrator Panel

[illustrator-panel repository](https://github.com/pwikapanel/illustrator-panel)

This repo contains everything you need to build Pwika from scratch.

---
### The Server Application

In order of use:

1. [server-config](https://github.com/pwikapanel/server-config/settings): to configure a new Debian server  
   [server-update](https://github.com/pwikapanel/server-update/settings): to update a Pwika server to a newer version
2. [sites](https://github.com/pwikapanel/sites/settings): default sites for a new installation
3. [cloud](https://github.com/pwikapanel/cloud/settings): the Pwika server application, including Pwika Cloud
4. [animation](https://github.com/pwikapanel/animation/settings): the javascript animation component of Pwika Cloud
5. [site-admin](https://github.com/pwikapanel/site-admin/settings): to install/delete/modify Pwika sites

---
### The Sync Application

Pwika Sync is a macOS-only application that acts as a hub for your Pwika project.

[sync](https://github.com/pwikapanel/sync/settings)

---
### Extras

- [Illustrator Templates](https://github.com/pwikapanel/templates-cool-extras/settings)
- [Illustrator Scripts](https://github.com/pwikapanel/scripts-presets/settings)

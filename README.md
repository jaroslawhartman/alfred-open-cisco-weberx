# alfred-open-cisco-webex

A MacOS Alfred workflow to open a predefined Webex session.

Pre-requisites:

* [Alfred](https://www.alfredapp.com/) - free
* [Alfred Power Pack](https://www.alfredapp.com/powerpack/buy/) - commericial, but I strongly recommend
* [Webex Workflow](https://github.com/jaroslawhartman/alfred-open-cisco-webex/releases) - download

## Introduction

It's pretty basic, but helps me to speed up a very common activity (which I always tend to do on very last second when a my conference call is about to start)...

So when I urgently need to open Webex conference, instead of searching through my browser bookmarks, just press Option-Space and type _webex_:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-01.png)

Then press Enter to get the list of your web conferences, for example:

![Alfred workflow](https://jaroslawhartman.github.io/alfred-open-cisco-webex/Cisco-Alfred-02.png)

Hit cursor down or up to select bridge you want to open and just press enter.

## Installation

After downloading the workflow, just doubleclick the file and it will get imported to your Alfred.

## Configuration

### Adding a new WebEx Conference

* Copy (Command-C) the WebEx link
  * i.e. `https://webex-conferencing.webex.com/meet/jhartman`
* Press Option-Space and type _webexadd_
* Follow instructions

### Removing a WebEx Conference

* Press Option-Space and type _webexremove_
* Select the conference you'd like removed and press Enter while holding Option

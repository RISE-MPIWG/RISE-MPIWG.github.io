---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: RISE & SHINE: Tool Developers Workshop
---

## Who are we?
The [RISE project team](https://www.mpiwg-berlin.mpg.de/research/projects/rise-and-shine-research-infrastructure-study-eurasia) at the Max Planck Institute for the History of Science (MPIWG) consists of:
* [Shih-Pei Chen](mailto:schen@mpiwg-berlin.mpg.de), project leader
* [Pascal Belouin](mailto:pbelouin@mpiwg-berlin.mpg.de), IT architect
* [Sean Wang](mailto:swang@mpiwg-berlin.mpg.de), project manager
* Brent Ho, former project co-leader

## What are RISE & SHINE?
Textual resources still overwhelmingly exist in digital silos, which makes their interoperability in digital research tools challenging. RISE and SHINE are our technical solution to fill this gap between resources and tools. We defined an API (**SHINE**) and designed its related infrastructure (**RISE** and software toolkits) for resource discovery and exchange.

This virtual workshop, initially planned as an in-person [tutorial](https://dh2020.adho.org/wp-content/uploads/2020/07/403_RISEandSHINEIntroductiontoanAPIbasedeinfrastructureforinteroperabletextualresourcesandresearchtools.html) at the DH2020 conference, will introduce how tool developers can take advantage of SHINE as an interoperable standard for textual data exchange in order to (1) produce a seamless UX for tool users to load texts for analysis, and (2) expand the quantity of texts automatically available for analysis.

MPIWG's [event page](https://www.mpiwg-berlin.mpg.de/event/rise-shine-tool-developers-workshop) provides additional information specific to tool developers, while the [RISE homepage](https://rise.mpiwg-berlin.mpg.de/) includes additional information for the general audience.

## Programme
This workshop will take place on Wednesday, 23 September 2020, at 14:00 CET over Zoom. *Pre-registration is required.*

During the workshop, we will cover the following topics:

### Introduction
We will briefly introduce the history of the RISE project, including how different stakeholders in the digital humanities ecosystem could use it for their benefits.

### Technical design
We will introduce the general technical design of RISE and SHINE, focusing specifically on the components relevant to tool developers. In particular, we will cover several different ways in which tool developers could implement [SHINE](https://rise.mpiwg-berlin.mpg.de/pages/doc_for_developers#tabs) within their own tools to ingest either texts provided by RISE-linked resource providers, or as a way to de-couple the tools and their associated texts.

During this portion, we will also have three developers to share their experience of implementing SHINE or SHINE-compatible software toolkits within their own tools. They are:
* Brent Ho, chief developer of [MARKUS](https://dh.chinese-empires.eu/markus/beta/) and RISE's former project co-leader
* [Joey Hung](http://joeyhung.info/), technical lead of the [Chinese Buddhist Electronic Text Association](https://www.cbeta.org/)
* [Rainer Simon](https://rsimon.github.io/), technical lead of [Recogito](https://recogito.pelagios.org/)

### Interactive Q&A and technical consultation
We will try to replicate the in-person tutorial format as much as possible over Zoom to answer questions and discuss technical implementations.

## Resources
To demonstrate the benefits of working with RISE & SHINE and to encourage third-party development of SHINE-compatible technical solutions, we have made a suite of open-source software toolkits that can be adopted and adapted. They are available on the RISE project's [Github page](https://github.com/RISE-MPIWG).

Specifically for tool developers, 

### [React SHINE Module](https://github.com/RISE-MPIWG/react-shine-api) ###
This is a React.js component that allows users to browse the [SHINE API](https://rise.mpiwg-berlin.mpg.de/collections). It allows selection of files, and passes the selected files through to your app. This component is currently used on Pelagios' [Recogito Platform](https://recogito.pelagios.org/).


### [RISE API JS Library](https://github.com/RISE-MPIWG/rise_js_client) ###
This library is designed to allow developers to interact easily with APIs compatible with SHINE, a restful API protocol that allows clients to browse, filter and access a large number of open and licence-protected structured text resources from a wide variety of providers. Please visit [https://rise.mpiwg-berlin.mpg.de](https://rise.mpiwg-berlin.mpg.de) for more information about SHINE and the RISE project. For a more detailed documentation of this project, please visit [https://rise.mpiwg-berlin.mpg.de/jslib](https://rise.mpiwg-berlin.mpg.de/jslib).

### [RISE Python Script](https://github.com/RISE-MPIWG/hylg)
This Python script allows one to pull text from RISE, and can be easily modified for your needs.

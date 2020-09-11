---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: Workshop
title: RISE & SHINE: Tool Developers Workshop
---

# Who are we?
The [RISE project team](https://www.mpiwg-berlin.mpg.de/research/projects/rise-and-shine-research-infrastructure-study-eurasia) at the Max Planck Institute for the History of Science (MPIWG) consists of:
* [Shih-Pei Chen](mailto:schen@mpiwg-berlin.mpg.de), project leader
* [Pascal Belouin](mailto:pbelouin@mpiwg-berlin.mpg.de), IT architect
* [Sean Wang](mailto:swang@mpiwg-berlin.mpg.de), project manager
* Brent Ho, former project co-leader

# What are RISE & SHINE?
Textual resources still overwhelmingly exist in digital silos, which makes their interoperability in digital research tools challenging. RISE and SHINE are our technical solution to fill this gap between resources and tools. We defined an API (**SHINE**) and designed its related infrastructure (**RISE** and software toolkits) for resource discovery and exchange.

This virtual workshop, initially planned as an in-person [tutorial](https://dh2020.adho.org/wp-content/uploads/2020/07/403_RISEandSHINEIntroductiontoanAPIbasedeinfrastructureforinteroperabletextualresourcesandresearchtools.html) at the DH2020 conference, will introduce how tool developers can take advantage of SHINE as an interoperable standard for textual data exchange in order to (1) produce a seamless UX for tool users to load texts for analysis, and (2) expand the quantity of texts automatically available for analysis.

MPIWG's [event page](https://www.mpiwg-berlin.mpg.de/event/rise-shine-tool-developers-workshop) provides additional information specific to tool developers, while the [RISE homepage](https://rise.mpiwg-berlin.mpg.de/) includes additional information for the general audience.

## Programme
The Workshop will take place according to the following timetable:

### Introduction to RISE and SHINE, as well as overview of future developments (10mn)
Presentation of RISE and SHINE and of its various components.
### Short presentation of the RISE & SHINE Resource Provider Reference Implementation (5mn)
The tutor will introduce how RISE can be used by owners of textual resources to make their resources available through RISE & SHINE.
### RISE and SHINE for Research Tool Developers(30mn)
In this session, the tutor will show how research tools developers can consume resources from the RISE infrastructure of from Resource Providers that make their resources available in a SHINE-compatible format, either by building their own client, by using the RISE javascript library or React.js module, or using the SHINE client python script.
#### Wrap-up and individual consultations(10mn)


## Resources
To demonstrate the benefits of working with RISE and to encourage third-party development of SHINE -compatible technical solutions, a suite of open-source toolkits is available for others to adopt and adapt for their own purposes. They can be found on the [RISE Project's Github page](https://github.com/RISE-MPIWG).

### [RISE Resource Provider Application](https://github.com/RISE-MPIWG/rise_rp) ###
This application allows you to maintain collections, resources, sections and content units and make them available through a SHINE-compatible api. It relies on docker for development as well as for deployment.

### [React SHINE Module](https://github.com/RISE-MPIWG/react-shine-api) ###
This is a React.js component that allows users to browse the [SHINE API](https://rise.mpiwg-berlin.mpg.de/collections). It allows selection of files, and passes the selected files through to your app. This component is currently used on Pelagios' [Recogito Platform](https://recogito.pelagios.org/).

### [Docusky Widget](https://github.com/RISE-MPIWG/docusky_widget) ###
This Vue.js widget allows the [Docusky](https://docusky.org.tw/DocuSky/ds-01.home.html) platform to pull resources from RISE.

### [RISE API JS Library](https://github.com/RISE-MPIWG/rise_js_client) ###
This library is designed to allow developers to interact easily with APIs compatible with SHINE, a restful API protocol that allows clients to browse, filter and access a large number of open and licence-protected structured text resources from a wide variety of providers. Please visit [https://rise.mpiwg-berlin.mpg.de](https://rise.mpiwg-berlin.mpg.de) for more information about SHINE and the RISE project. For a more detailed documentation of this project, please visit [https://rise.mpiwg-berlin.mpg.de/jslib](https://rise.mpiwg-berlin.mpg.de/jslib).

### [RISE Python Script](https://github.com/RISE-MPIWG/hylg)
This Python script allows one to pull text from RISE, and can be easily modified for your needs.

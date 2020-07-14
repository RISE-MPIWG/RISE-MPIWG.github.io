---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
---

## Welcome to the RISE DH2020 Workshop Page

This four-hour tutorial will first provide a general introduction to the RISE project and to the SHINE API. 

Following the introduction, we will have hands-on tutorials on two aspects of the RISE project:

- **RISE for Resource Providers:** all want to make their resources more visible, but implementing APIs may be difficult for institutions without dedicated IT staff for DH research. Individual scholars also may have personally curated collections to share. In both cases, resource owners might want to set certain access restrictions for collaborations or copyright reasons. RISE-RP is a software package that provides an easy resource sharing solution; it makes your resources SHINE-compatible and discoverable through RISE without coding. We will work on how to store and disseminate your resources by deploying your very own instance of RISE-RP.

- **RISE for Research Tool Developers:** For most research tools, users have to manually prepare texts into a specified format and then upload them for analysis. What if this is not feasible, due to licensing restrictions or technical barriers? RISE-JS-Client is a software package for research tool developers. Once implemented, users can now search for and select RISE-linked resources to be analyzed, right within the research tool’s native UI. This allows research tool developers to tap into a large network of textual resources and make the research workflow more seamless for their user bases. We will present RISE-JS-Client, one reference implementation with the tool Recogito,  and work on how to integrate this package into individual software solutions.

## Agenda
The Workshop will take place according to the following timetable:

### Introduction to RISE and SHINE, as well as overview of future developments
The tutor will do a short presentation of RISE and SHINE and of its various components.
### RISE and SHINE for Resource Providers
During this session, the tutor will introduce how RISE can be used by owners of textual resources to make their resources available through RISE & SHINE.
### Short break
### RISE and SHINE for Research Tool Developers
In this session, the tutor will show how research tools developers can consume resources from the RISE infrastructure of from Resource Providers that make their resources available in a SHINE-compatible format, either by building their own client or by using the RISE javascript library or React.js module.
#### Wrap-up and individual consultations

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


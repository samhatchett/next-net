# NEXT-NET
A Deliberative Project for the Advancement of Water Systems Simulation

Before you initiate a pull request, please read this document. Proposals and other ideas should be thoroughly discussed in Issues first.

## Project Purpose and Scope
The purpose of this project is to collaboratively plot a course for development of a hydraulic solution engine worthy of carying on the legacy of EPANET. This project's scope is limited to design and development of a hydraulic and water quality solution engine, extended-period simulation capabilities, and I/O extensions to provide backwards compatibility with EPANET files and assets. The development of extended features, GUIs, and derivative tools is meant to be enabled by the work done here, but is out of scope for this project.

## Project Status / Getting Involved
We are in the early stages of needs-assessment and a survey of design considerations. The best place to get involved is in this repo's issues. If you have concrete design suggestions, make them there, discuss, and open a PR to `master` with your contribution to the design documents.

## Contribution Model
This project is in design-phase, which means that implementation details are less important than an accurate assessment of needs and of interface requirements. The typical interaction model for this design phase will hopefully look something like:

- Suggestion, Discussion, Resolution: make proposals related to library use and needs, and debate them in Issues.
- Design description language: Make a PR to the SRS document to illustrate the resolution that was reached.
- Implementation and/or interface discussion: API design, object heirarchy, use of patterns, etc. should be discussed/debated in Issues.
- Design revision: PR to the UML and/or supporting documents

## Design Tools

### UML / Sequence diagrams
Use the wonderful [Gravizo](http://www.gravizo.com) diagram generator. Be sure to read and understand the considerations for playing nice with github [here](https://github.com/TLmaK0/gravizo)

### Software Requirements Specification (SRS)
Use Markdown-formatted content. The SRS in this repo borrows from the [IEEE 830](http://standards.ieee.org/findstds/standard/830-1998.html) Recommended Practice.

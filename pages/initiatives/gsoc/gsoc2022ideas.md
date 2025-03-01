---
layout: full-width
title: GSoC 2022 Ideas
tags: gsoc
permalink: /initiatives/gsoc/gsoc2022ideas
---

# {{page.title}}

<!-- Template: Use a format like below to add your project:
### [Project Name]

##### [Explanation of Ideas]

![Preferred for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Possible for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Not recommended for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-not%20recommended-red)

![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)
![Possible for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-possible-yellow)
![Not recommended for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-not%20recommended-red)

##### [Expected Results]

##### [Getting Started]

##### [Mentors]
-->

Tips to get you started in no particular order:
- Read the
  [Student Guidelines](gsoc2022).
- Check our
  [github organization](https://github.com/OWASP).
- Contact one of the project mentors below.

## List of Project Ideas

### [OWASP Juice Shop](https://owasp-juice.shop)

OWASP Juice Shop is probably the most modern and sophisticated insecure
web application! It can be used in security trainings, awareness demos,
CTFs and as a guinea pig for security tools! Juice Shop encompasses
vulnerabilities from the entire OWASP Top Ten along with many other
security flaws found in real-world applications!

To receive early feedback please:
- put your proposal on Google Docs and submit it to the OWASP
  Organization on Google's GSoC page in "Draft Shared" mode.
- Please pick "juice shop" as Proposal Tag to make them easier to find
  for us. Thank you!

##### Explanation of Ideas

###### Score Board UI/UX

![Possible for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

Juice Shop's existing Score Board has been rewritten from scratch once
when the project moved from AngularJS/Bootstrap to Angular/Material.
Since then, new features, filters and information has been added to it
over the years. It has grown to a point where it can be confusing for
beginners. It also became pretty slow to render over time.

After a big facelift project for all the other UI screens, the Score
Board now is the one screen left to require some special attention. As
it is the heart and soul of the Juice Shop, any redesign or usability
improvements must be thoroughly tested and strive for the best possible
user experience.

###### Your own idea

You have an awesome idea to improve OWASP Juice Shop that is not on this
list? Great, please submit it!

##### Expected Results

* A new feature or improvement of an existing one that makes OWASP Juice
  Shop even better
* Your code follows our existing styleguides and passes all existing
  quality gates regarding code smells, test coverage etc.
* Code that you write comes with automated tests that fit into
  [our available test suites](https://pwning.owasp-juice.shop/part3/contribution.html#testing).

##### Getting started

* Make sure your JavaScript/TypeScript is sufficient to work on the
  Juice Shop codebase. Check our
  [Codebase 101](https://pwning.owasp-juice.shop/part3/codebase.html)
  here. Students with some experience with (or willingness to learn)
  Angular and NodeJS/Express are usually prefered.
* Read our
  [Contribution Guidelines](https://pwning.owasp-juice.shop/part3/contribution.html)
  very carefully. Best make some small contributions before GSoC, so we
  can see how you work and help you dive into the code even better.
* Get in touch with
  [Bjoern Kimminich](mailto:bjoern.kimminich@owasp.org) to discuss any
  of the listed or your own idea for GSoC!

##### Mentors

* [Bjoern Kimminich](mailto:bjoern.kimminich@owasp.org) - OWASP Juice
  Shop Project Leader
* Jannik Hollenbach - OWASP Juice Shop Core Team
* Timo Pagel - OWASP Juice Shop Core Team

### [OWASP ZAP](https://zaproxy.org/)

ZAP is the world’s most widely used web scanner. Previous GSoC contributors have added key features and are all listed in the [ZAP Student Hall of Fame](https://www.zaproxy.org/student-hall-of-fame/).

To get started with ZAP contributions see the [ZAP Contributing Guide](https://www.zaproxy.org/docs/contribute/). We expect GSoC contributors who apply to work on ZAP to have had at least one code PR merged into one of the ZAP repos.

##### Import Postman API Definitions

![Possible for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

Import Postman API definitions into ZAP as per [#6960](https://github.com/zaproxy/zaproxy/issues/6960)

##### Import PCAP/PCAPNG Files

![Preferred for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)

Import PCAP/PCAPNG Files into ZAP as per [#4812](https://github.com/zaproxy/zaproxy/issues/4812)

##### Modern Web App Framework Handling: Angular / VueJS / React

![Possible for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

Enhance ZAP to handle one modern framework better - either Angular, VueJS or React. This project should allow ZAP to extract more information from one of the top JavaScript frameworks and potentisally tune attacks to target known issues with that framework.

##### Your Own Idea

![Preferred for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

We are always delighted to hear from contributors who have their own ideas for projects. You are encouraged to discuss these with the ZAP project leaders.

##### Mentors

All ZAP projects will be mentored by the ZAP Project Leaders:

* [Simon Bennetts](mailto:psiinon@gmail.com)
* Rick Mitchell
* thc202

### [OWASP Maryam](https://github.com/saeeddhqan/Maryam)

OWASP Maryam is a modular open-source framework based on OSINT and data gathering. It is designed to provide a robust environment to harvest data from open sources and search engines quickly and thoroughly.

##### Explanation of Ideas

###### Iris

![Possible for "Medium" GSoC 2022 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Preferred for "Large" GSoC 2022 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

Iris currently has been added to Maryam as some basic Natural Language Processing Operations. We want to improve it.
It has a simple document clustering module, a simple meta search engine, and sentiment analysis. What we want to do add
new clustering methods that use neural networks(CNN, RNN, LSTM, ...) in order to create clusters, a topic modeling module to extract
topics from documents, and a model that recognizes the most relevant documents by the given query.

##### Getting Started

* Besides Python, make sure to be familiar with word vectors, neural networks, document retrieval, and NLP models.
* Please read our [wiki page](https://github.com/saeeddhqan/Maryam/wiki), especially the Development Guide. previous PRs would be very helpful.

##### Mentors

* [Saeed Dehqan](mailto:saeed.dehghan@owasp.org) - OWASP Maryam Project Leader
----

----

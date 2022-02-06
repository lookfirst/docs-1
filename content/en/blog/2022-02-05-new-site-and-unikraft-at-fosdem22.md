+++
title = "Kicking off 2022 with a new site and release at FOSDEM!"
date = "2022-02-04T00:00:00+01:00"
author = "Alexander Jung"
tags = ["announcement"]
+++

As the new year begins, we're excited to show off many of the things the
community has been working over the last two months.  It's become a tradition
now that Unikraft celebrates a new release at [FOSDEM'22](https://fosdem.org/2022/), and we've come a long way since
our initial release at FOSDEM'18.

### New release v0.7 (Mimas)

Unikraft has released [v0.7 (Mimas)](/releases) -- only 2 months after the last!
This is an important milestone for the project as we start to speed up the
reviewing, testing, merging and releasing of components of the Unikraft
ecosystem.  We have come a long way from using patchwork, and have introduced
functionality on top of Github to help with [the project's rigorous review
process](/docs/contributing/review-process/) -- there are a lot of moving parts
which are becoming automated (see the talk on the CI/CD system by below).

Apart from bug fixes, improvements and version updates, Unikraft Release v0.7
Mimas adds core features to support its development and deployment, including:

* [`lib/ukrust`](https://github.com/unikraft/unikraft/tree/staging/lib/ukrust): Internal Rust support, allowing the development of internal libraries in Rust
* [The documentation site](https://unikraft.org) has been revamped with
  extensive information on Unikraft architecture, usage, internals and
  development model.
* Multiple ARM features, such as [SMCCC
  support](https://github.com/unikraft/unikraft/pull/297), [ns16550
  driver](https://github.com/unikraft/unikraft/pull/233), [GICv3](https://github.com/unikraft/unikraft/pull/234) have been
  added.
* Application README files have been updated with detailed instructions on
  configuring, building and running Unikraft applications.

For more details on this release, please check out the [release
page](https://unikraft.org/release).

#### Unikaft VSCode Extension

A Visual Studio Code extension allowing developers to get the full benefits of
the IDE when working on Unikraft source code.

![](https://raw.githubusercontent.com/unikraft/ide-vscode/prototype/media/helloworld.gif)

The Unikraft VSCode Extension extension facilitates the development of Unikraft
applications and libraries (both external and internal).  A big thank you to
[Adina Smeu](https://github.com/adinasm) who was the primary contributor to this
project.

To get started using it, please visit the related repository at
https://github.com/unikraft/ide-vscode


### Unikraft at FOSDEM'22

And of course, we have four talks this year at FOSDEM all about unikernels,
including:

* [Debugging and Monitoring in Unikraft: Everything beyond printf()](https://fosdem.org/2022/schedule/event/skuenzer/)

  by Simon Kuenzer & Marc Rittinghaus (NEC Laboratories Europe & KIT)

* [Rethinking the OS for Isolation Flexibility with FlexOS](https://fosdem.org/2022/schedule/event/tee_flexos/)

  by Hugo Lefeuvre & Jan Tobias Muehlberg (The University of Manchester & imec-DistriNet Researchc Group, KU Leuven)

* [Massive Unikernel Matrices with Unikraft, Concourse and More!](https://fosdem.org/2022/schedule/event/massive_unikernel_matrices_with_unikraft_concourse_and_more/)

  by Alexander Jung (Unikraft UG (haftungsbeschränkt))

* [Unikraft Performance Monitoring with Prometheus](https://fosdem.org/2022/schedule/event/unikraft/)

  by Cezar Crăciunoiu (University Politehnica of Bucharest)

You can view previous talks at FOSDEM [here](/community/talks).

### Acknowledgements

A big thank you to the contributors to this release as mentioned above as well
as those those who helped populate the documentation site: [Răzvan
Vîrtan](https://github.com/razvanvirtan), [Stefan
Jumarea](https://github.com/StefanJum), [Laurentiu Barbulescu](#), [Cezar
Craciunoiu](https://github.com/craciunoiuc), [Fredrik Bakken](https://github.com/FredrikBakken), [Dragos
Iulian Argint](https://github.com/dragosargint), [Gabriel
Mocanu](https://github.com/gabrielmocanu), [Felipe Huici](https://github.com/felipehuici) and [Răzvan
Deaconescu](https://github.com/razvand).  Some of the new content of this documentation site has been
gathered from [Unikraft's Summer of Code (2021)](https://usoc21.unikraft.org).
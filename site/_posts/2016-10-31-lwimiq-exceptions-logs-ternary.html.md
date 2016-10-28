---
title: Last week in ManageIQ, Euwe stabilization
author: bronaghs
date: 2016-10-31
comments: true
published: true
tags: LWIMIQ
---

[Bronagh](https://github.com/bronaghs) here bringing you this weeks edition of Last Week in Manage IQ!

## Featured

A milestone was met this week when we entered into the stabilization phase of the upcoming Euwe release. At this point we will concentrate on fixing bugs. If you would like to help out then take your pick from our [open issues].

Sprint 48 ended on Monday 24th. Don't worry if you could not make the Sprint review meeting this week, it was [recorded](https://www.youtube.com/watch?v=wD6dqm9hSRM)

It was a knock out week in ManageIQ with a whopping 478 [commits] across the 164 [PRs merged].


## Improved

[Šimon](https://github.com/isimluk) is keeping it simple [UX: Simplify Chargeback rates editor](https://github.com/ManageIQ/manageiq/pull/12156)

[Beni](https://github.com/cben) undertook a major rewrite of auto-tagging of kubernetes labels
and fixed a bunch of bugs while he was at it: [Rewrite of auto-tagging, fixing multiple bugs](https://github.com/ManageIQ/manageiq/pull/11806)

Tired of having to input your RabbitMQ credentials on the rails console? Now you don't have to, thanks to [Miha](https://github.com/miha-plesko), checkout his work here: [Add GUI with inputs for VMware vCloud event monitoring](https://github.com/ManageIQ/manageiq/pull/11362)

## Fixed

[Šimon](https://github.com/isimluk) made a PR to fix the [Add a new chargeback rate screen](https://github.com/ManageIQ/manageiq/pull/12130) and 
[Nick](https://github.com/carbonin) made a PR to [Raise an error if a region is not configured for central admin](https://github.com/ManageIQ/manageiq/pull/12264) 


## New

This week we saw the introduction of [A new network provider page for Nuage](https://github.com/ManageIQ/manageiq/pull/10425) by [Samuel](https://github.com/samuel-nuage)

Mac support was added to the [linux_block_device gem](https://github.com/ManageIQ/linux_block_device), thanks to [Jason](https://github.com/fryguy).

## Deleted

Deleting duplicate code is always a good thing.
[Eric](https://github.com/epwinchell) knocked it out of the park this week by deleting 93 files! [Remove old timeline JS from public](https://github.com/ManageIQ/manageiq/pull/12135)

Robin deleted 391 lines by [Removing Ziya flash charts from code](https://github.com/ManageIQ/manageiq/pull/12122) thanks [Robin!](https://github.com/PanSpagetka)

Last but not least, [Adam](https://github.com/agrare) cleaned up the VMware provider by removing the [unused pause operation](https://github.com/ManageIQ/manageiq/pull/12255)


## Wrapping up
Thanks for joining us for another edition of LWIMIQ. Happy Halloween!

[open issues]: https://github.com/ManageIQ/manageiq/issues
[contributors]: https://github.com/ManageIQ/manageiq/graphs/contributors
[PRs merged]: https://github.com/ManageIQ/manageiq/pulls?page=1&q=is%3Apr+is%3Amerged+base%3Amaster+merged%3A%222016-10-24+..+2016-10-28%22+sort%3Acreated-desc&utf8=%E2%9C%93
[commits]: https://github.com/manageiq/manageiq/compare/master@%7B2016-10-24%7D...@%7B2016-10-28%7D

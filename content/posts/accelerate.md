---
title: "Accelerate: The best book I read in 2020"
date: 2020-10-27T22:33:49Z
toc: false
images:
tags: 
  - books
  - delivery-pipelines
  - continuous-delivery
---

The book I wish to introduce to you today is titled [Accelerate][1] :fast_forward:, from authors *Nicole Forsgren, Jez Humble & Gene Kim* . This post isn't a review &mdash; it is a short summary of my opinions and insights gained upon reading this book. I'd highly recommend it for anyone who is *writing any kind of software*(I absolutely mean it :smile:).

How often do we get started with writing code caring very little about deployment in the beginning &mdash; to realise that we should have thought about it from the start(even if that's for rapid prototyping).

We were embarking on a journey of [Greenfield Software Development][2] at work, and that's when I crossed paths with this book. It made perfect sense, and I was glad to get introduced to these **_measures_** of Software development.

* Lead time
* MTTR(Mean time to restore)
* Deployment Frequency
* Change Fail Percentage

These at first seem like *common sense* or *"well, that's obvious"*, isn't it? Indeed, they are but are often difficult to measure owing to the complexity of delivery pipelines.


So, if you were asking *what is this book all about*? The book is organized into three sections(which are pretty self-explanatory, I suppose):

* What we found
* The Research
* Transformation

The authors back what they have proposed from research conducted on various software development teams and organizations. I shall not dive into details here, but would encourage you to take a look. The biggest eye-opener for me personally, was to learn how to approach *software development and delivery* in a way that it can be quantified. This has helped me appreciate the limitations of [monoliths][3], and further emphasized the need for writing [*decoupled software*][4]. Monoliths, aren't *entirely bad*(it depends) &mdash; they could be fine as long as they are "*manageable*" and can be measured as described above.


The sections in the book talk about empowering individuals on one end of the spectrum and zooming out to organizational productivity on the other side. Simply put, each organization's performance can be attributed to every employee's productivity. From a perspective of a person writing software it can be quantified as the *ease* of releasing a change(software). How quickly can a feature requested be prototyped, iterated and deployed to the end-user. The converse so to speak &mdash; when release management isn't "scary"(be it the process or the time it takes) and if engineers can release software in an organized, repeatable and measurable manner, there isn't any barrier for enhancing productivity. 

Delivery pipelines that can be measured against the above attributes can help define the productivity of Software engineering teams. Some organizations measure productivity as a by-product of their deployment frequency, the only caveat here is to differentiate between genuine feature releases vs the percentage of remedial release. Remedial releases(change fail percentage) aren't necessarily *bad*, in-fact high performing engineering teams aren't afraid of releasing software frequently, as the time it takes to fix a bug(MTTR), would be tiny.


The book highlights many such concepts around Continuous Delivery that are simple to understand and relate to. It also sheds light onto best practices that are noteworthy. Overall this book has helped me refresh the way I think about deployment and software delivery, and I hope you would find it useful too!

Happy reading :coffee:

[1]: https://www.oreilly.com/library/view/accelerate/9781457191435/
[2]: https://en.wikipedia.org/wiki/Greenfield_project
[3]: https://en.wikipedia.org/wiki/Monolithic_application
[4]: https://en.wikipedia.org/wiki/Loose_coupling#Methods_for_decreasing_coupling
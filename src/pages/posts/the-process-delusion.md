---
title: The Process Delusion
excerpt: >-
  Speed wins in software development. It sounds wrong but it’s true. When people hear this they just can’t see why. They confuse speed with rushing or a reduction in quality. As a result of this fallacy they optimize for perceived quality. Adding process ensues.
date: '2017-07-13'
thumb_img_path: images/process-01.jpeg
thumb_img_alt: Jeff Bezos process quote
content_img_path: 
content_img_alt: 
seo:
  title: The Process Delusion
  description: >-
    The Process Delusion
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: The Process Delusion
      keyName: property
    - name: 'og:description'
      value: >-
        The Process Delusion
      keyName: property
    - name: 'og:image'
      value: images/process-01.jpeg
      keyName: property
      relativeUrl: true
template: post
---

Speed wins in software development. It sounds wrong but it’s true. When people hear this they just can’t see why. They confuse speed with rushing or a reduction in quality. As a result of this fallacy they optimize for perceived quality. Adding process ensues. It’s usually reactionary; a deployment goes out and causes an outage, a post-mortem is held and the action is to add a sign off process by a Director of Engineering. Over time these process can easily surmount to a productivity slump.

Jeff Bezos summarises the problem with this cultural mentality in [his 2017 annual letter](https://www.sec.gov/Archives/edgar/data/1018724/000119312517120198/d373368dex991.htm):

> "A common example is process as proxy. Good process serves you so you can serve customers. But if you’re not watchful, the process can become the thing. This can happen very easily in large organizations. The process becomes the proxy for the result you want. You stop looking at outcomes and just make sure you’re doing the process right. Gulp. It’s not that rare to hear a junior leader defend a bad outcome with something like, “Well, we followed the process.” A more experienced leader will use it as an opportunity to investigate and improve the process. The process is not the thing. It’s always worth asking, do we own the process or does the process own us? In a Day 2 company, you might find it’s the second."

This type of mentality produces stale engineering organizations. Over time you’re so locked in that you lose agility, autonomy, ownership and you’ve built The Titanic. Ironically companies that find themselves in this situation believe that “Agile” development methodologies can actually help them out in this situation. More process ensues.

So process is bad then right? Of course not. Question all requests to add process, whether externally pressured or within the teams. Automate as much as possible. Often the driver for process is actually visibility. Visibility can be automated. Most importantly understand your processes and document them. Associate timings against each process and dedicate time in your teams sprint (work day) to kill or automate constraints. A good way to do this is to produce a Value Stream Map for your team.

A bit of a contrived example but take a deployment process for example.

![Value Stream Map](/images/process-02.png)

In this Value Stream Map I’m only mapping out the times for each process but typically we would put timings on the transitions too to indicate how long the wait is between processes. In doing so we can identify bottlenecks/constraints and look at ways to automate or remove these steps. If a request comes in to add a new process, add it to your value stream map and assess the impact of doing so.

Don’t let process own you. Prioritize autonomy and ownership but don’t lose sight of the benefits of standardization.

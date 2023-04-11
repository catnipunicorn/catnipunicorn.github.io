---
layout: page
title: Copy & translations tooling & infrastructure
---

# Product cases for copy & translations tooling & infrastructure

- **Merging a specialised application into a generic one**

Once upon a time, a company had an internal tool to run A/B experiments. It was used by everyine at the IT department, but every experiment had to be implemented in the codebase. Can’t code? Wait for someone to help you.

Eventually someone developed a stand alone tool that allowed — with certain restrictions — to run a/b tests on pieces of copy (think *Buy now* vs *Add to cart* as a call to action on a product page) without touching the code. Let’s call it The Copy Tool. Empowering writers to leverage their craft knowledge proved to be a huge success for the business. Writers wanted less restrictions and more freedom. 
While working on implementing new features and dealing with dependencies with other internal tools, my team have realised that there is no point in having a separate application. After some talks with various stakeholders, we decided to merge The Copy Tool into the company wide tool for A/B experiments.

It took us a couple of months, with some preparatory work done over a year before the final merge.

As a result, the company has one less internal tool to maintain, happier (and more productive) writers who can use the same application as everyone else, and better words across the products. Oh, and the team owning The Copy Tool had to change its focus — it did kill its own baby after all.

- **Roadmap for copy infrastructure**
 
Imagine you build an infrastructure for all the texts you serve to your customers based on your current needs — in the year of 2005. The company grows, grows, GROWS, and you find yourself in the year of 2015 with a very complicated system built upon that same infra from 2005. It works, which is great. It requires a lot of workarounds, for writers, translators, designers and developers alike, which is not so great. It is beyond its capacity to scale.

What do you do?

You set up on a bold adventure of redoing everything, from a monolith to a micro service, from product specific to product agnostic, from multiple sources of truth to one… You set up a plan to retire legacy attributes. You talk a lot with very different people, you explain your vision and get their buy-in. You create a road map, from the most painful and most fundamental issues to full feature parity. And you start working on it.

This is exactly what I have done as a product manager. The roadmap included all the needs, and was very simple and clear. All stakeholders understood why certain things were prioritised above others. The team knew what they were doing, and whom they were doing it for. It aligned with the bigger company goals.

The project had to be put on pause; but in 2021 it’s on again — without me as a product manager and a driver, but with all my research and documentation. I wouldn’t be surprised if they are using a modified version of my roadmap.

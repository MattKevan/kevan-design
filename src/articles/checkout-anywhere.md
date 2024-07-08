---
description: Creating a new buying experience
date: 2019-06-24
image: https://res.cloudinary.com/dhcgic4ld/image/upload/c_scale,h_800,w_800/v1705278854/slc1/441.png
tags:
  - Article
layout: wide-post
cover: pi-banner.jpg
title: Checkout anywhere

---

<div class="prose-lg max-w-4xl m-auto px-4">

## About

With long-standing, successful and complex digital products, deciding whether to prioritise fixing problems or building new features can be a challenge. Often the decision comes down to whether it's better to fix  what's there already or to risk starting again and building from scratch.

This case study looks at this challenge for a major online retailer and how I developed solutions using a lean product and UX approach.

Project details
Roles
UX designer
UI designer

</div>

<div class="section bg-gray-100 prose-lg px-4 py-20">
<div class="max-w-6xl my-4 m-auto">

  <h2 class="mt-0">User problems</h2>
  <p>I used quantative analytics data to investigate how customers were using the basket and checkout, identifying areas where people were having problems and dropping out of the flow. From this, I conducted a series of qualitative user interviews to dig further into the issues. The feedback I received fell into three main groups:
  <div class="  grid grid-cols-1 lg:grid-cols-3 gap-8">


<div class="bg-pink-200 p-4 rounded-lg">
<h3 class="mt-0">Work-arounds</h3>

While the checkout had a decent conversion rate, we could see from analytics data that there was a significant drop-out at basket page. Users would add a product to their basket, go back to the catalogue to look for more products, add them to their basket, and so on. 

Research found that these users were using the basket as a comparison tool or to save products for later as this functionality wasn't available in the product catalogue.

</div>



<div class="bg-pink-200 p-4 rounded-lg">

<h3 class="mt-0">Delivery surprises</h3>

We found there was a big customer drop-out between the checkout delivery and payment pages. Users would enter their delivery details and then either exit the checkout entirely or go back to the product catalogue and look for a different product. 

Research found that users were entering the checkout as that was the only place where they could see the delivery times and cost. If the cost was too high or the delivery was inconvenient, they'd either try a different product or abandon the purchase entirely.
</div>
<div class="bg-pink-200 p-4 rounded-lg">

<h3 class="mt-0">The 'Ryanair' effect</h3>

After adding a product to the basket, the user is asked to select add-on services, such as unwrapping, rubbish disposal, installation and recycling. 

Users felt that while these services were worthwhile as they, along with the delivery fee, could add significantly to the price – an unwelcome surprise as this was not made clear before reaching the basket. One participant compared it to Ryanair, adding extra charges in the checkout and not being up-front about the real, higher price.
</div>

</div>

<h2>Product & technical problems</h2>
<div class="grid grid-cols-2 lg:grid-cols-4 gap-6">


<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Not scalable</h4>
  <p class="mb-0">Difficult to add more territories, issues multiplied as business expands.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Complex</h4>
  <p class="mb-0">Hard to understand full codebase and impact of changes. Lots of time spent on maintainence and repairs.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Can’t support new journeys</h4>
  <p class="mb-0">Difficult to add new user journeys that span multiple teams due to mis-aligned priorities & targets.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Hard to optimise</h4>
  <p class="mb-0">We can’t easily see how customers are interacting with the checkout and any problems they may have.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">No separation of concerns</h4>
  <p class="mb-0">Teams can’t take responsibility for their own areas or release independently.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Maintenance-heavy</h4>
  <p class="mb-0">Developers spend a lot of time doing things they shouldn’t have to, e.g. updating copy and adding services.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Slow pace</h4>
  <p class="mb-0">It takes a long time to do anything due to code complexity and duplication.</p>
</div>
<div class="bg-pink-200 p-4 rounded-lg">
  <h4 class="mt-0">Can’t improve UX</h4>
  <p class="mb-0">Fragile & inflexible tech means we can’t run tests or experiment with new flows and experiences.</p>
</div>
</div>

</div>
</div>
## Technical problems

The basket and checkout codebase was over 20 years old, and highly complex. Making a change involved a significant about of effort and risk – the code was so complicated and had been worked on by so many people that no-one fully understood how it worked. Changing something in one area would cause things to break in other places and, as everything was so tightly linked, it was hard for more than one team to work  on it at the same time.

Worse, there were separate applications for the mobile and desktop versions of the same site, and these  were replicated across at least six partner and subsidiary sites. Something as simple as a text change could mean touching over ten separate applications, with all of the development and testing overhead involved.

</div>



Responsibility for the checkout was split across five product squads, each with their own roadmap and priorities. The amount of strategic and ongoing work to do and the difficulty of working on the platform meant that each squad's backlog was measured in years.

While the idea behind the split was to enable squads to focus deeply on their areas, it actually meant that making changes to the end-to-end flow was almost impossible. As soon as a task involved another squad it would drop into the black hole of their backlog, never to be seen again. 


## UX review

## Opportunity mapping

## Hypotheses mapping and prioritisation

## Product vision

## LEAN approach

## Minimal useful product


## Solution

It was clear that something needed to change as the teams had reached a sort of stalemate. The platform was too complex and fragile to work on at any pace, but it wasn’t possible to properly get a handle on the technical issues as they were bigger than any one team. 

The business had been discussing for quite some time whether it was better to focus on salvaging the existing platform, or starting from scratch and building something new. These both had significant pros and cons\

Salvage
Pros:
* The existing platform works.
* Less risky to fix an existing platform than building something new

Cons:
* No guarantee the existing platform is fixable


## Outcomes
After some poor post-Covid financial results and significant turnover in the teams, the chief executive decided to launch a new company-wide initiative. All existing work was put on hold or cancelled to make room for it, including this project.

## Learning
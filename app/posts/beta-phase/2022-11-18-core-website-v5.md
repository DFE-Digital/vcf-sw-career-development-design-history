---
title: Iterating the core website v5
description: How we created version 5 of the core website
date: 2022-11-18
screenshots:
  items:
    - text: Core website sitemap v1
      src: site-map-v1.png
    - text: Development programme taxonomy v1
      src: taxonomy-v1.png
    - text: Homepage v5
      src: prototype-homepage-v5.png
related:
  items:
    - text: Designing the core website v1 (alpha)
      href: /alpha-phase/core-website-v1/
    - text: Iterating the core website v2 (alpha)
      href: /alpha-phase/core-website-v2/
    - text: Iterating the core website v3 (alpha)
      href: /alpha-phase/core-website-v3/
    - text: Iterating the core website v4 (beta)
      href: /beta-phase/core-website-v4/
---

{% from "gallery/macro.njk" import appGallery with context %}

<strong class="govuk-tag govuk-tag--turquoise">Core website</strong>&nbsp;<strong class="govuk-tag govuk-tag--purple">Career progression</strong>&nbsp;<strong class="govuk-tag govuk-tag--blue">Development programmes</strong>

## When
Sprint: Sprints 3 and 4
When: 24 October to 18 November 2022

## Overview / user needs
We iterated the core website. This iteration was based on the following:

### User needs identified during beta round 1 research sessions

#### Home / sub-level navigation pages
- The career stage titles were not always understood or recognised
- A stage between newly qualified and experienced social worker is missing - the ‘social worker’
- Career stage groupings were seen as distinctly different (Team Managers and Heads of service)
- Practice Leaders and middle manager terms were not recognised
- The sub-level navigation pages suffered similar issues:
  - Some found the titles and descriptions contradicting
  - Some felt they sit between two programmes

#### Content pages
- Users were unable to decide whether the development programme was a fit with their current commitments
- The 'What you’ll get' section was not convincing enough to guarantee sign-up

See the <a href="https://docs.google.com/presentation/d/1DTwWYCDogFHeTuYVMmxEsMPkJcTsq7GZUMouz_VO-4A/edit?usp=sharing" target="_blank">Beta Round 1 UR Findings report (opens in new tab)</a> for more detail.

### Business needs identified following feedback and show and tell sessions
- Individual development strands (Pathway 1, 2, 3 and 4 and Upon aspiring directors and new directors) should not be presented as separate programmes.
- Provide a route for users to see all development programmes and their strands
- Support the user journey of users looking for development programmes by title

## Design thinking

### Providing two alternate user journeys to reach the development programmes

#### The career stage journey
This is still the primary way for users to find the career programmes. Users have told us throughout research that they like to identify the relevant development programme in this way. This route also supports the post Minimum Viable Product offerings the business have identified, including guides and roles by career stage.

#### By all programmes
At this stage, this is a secondary route. Further research will provide insight into how important this route will be. As such we added simple links on the homepage and sub-level navigation pages.

{{ appGallery({
  items: [{
    text: "prototype homepage all programmes example",
    caption: "The homepage all programmes link"
  }, {
    text: "prototype sub level all programmes example",
    caption: "The sub-level all programmes link"
  }]
}) }}

### Showing programmes as a whole
To meet the business requirement of showing programmes as a complete programme rather than just their strands, we looked at 3 areas of presentation:

1. **The all programmes page**
A obvious step on this page was to ensure the strands were grouped by the overarching programme name. We took the decision not to allow navigation down to each programme level, for instance there is no landing page for the Social Work Leadership Pathways programme at this stage.<br>
<a href="prototype-all-programmes-v1.png" target="_blank">![All programmes page](prototype-all-programmes-v1.png "All programmes page")</a>

2. **The sub-level navigation pages**
We decided not to split the cards by the overarching programme as felt this might be confusing to users. We will monitor and review this after each round of research.

3. **The content pages**
The aside navigation area already contained the programme strands for the career stage group the user visited from. We grouped these by the overarching programme name.<br>
<a href="aside-examples.png" target="_blank">![Aside navigation examples](aside-examples.png "Aside navigation examples")</a>


<!-- Jim. Added these in. Add/change as you see fit. Feel free to integrate into above if it makes sense etc. -->

### Changing descriptions and what we did re: career step titles
 Add something about career stage groups titles having to be the way they are as per the business and using the descriptions to explain them in user centred terms

### Writing Pathways 3 and 4 content

### Sub-level content???

## What happened next?
These changes will be tested in round 3 research sessions.




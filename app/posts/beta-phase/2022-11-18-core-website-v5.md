---
title: Iterating the core website v5
description: How we created version 5 of the core website.
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
    - text: Iterating the core website v6 (beta)
      href: /beta-phase/core-website-v6/
    - text: Iterating the core website v7 (beta)
      href: /beta-phase/core-website-v7/
    - text: Iterating the core website v8 (beta)
      href: /beta-phase/core-website-v8/
---

{% from "gallery/macro.njk" import appGallery with context %}

<strong class="govuk-tag govuk-tag--turquoise">Core website</strong>&nbsp;<strong class="govuk-tag govuk-tag--purple">Career progression</strong>&nbsp;<strong class="govuk-tag govuk-tag--blue">Development programmes</strong>

## When
Sprint: Sprints 3 and 4
When: 24 October to 18 November 2022

## Overview / user needs
We iterated the core website based on the following:

### Issues identified during beta round 1 research

#### Homepage and sub-level navigation pages
- The career stage titles were not always understood or recognised
- A stage between newly qualified and experienced social worker is missing: the ‘social worker’
- Career stage groupings were seen as distinctly different (team managers and heads of service)
- 'Practice leader' and 'middle manager' were not recognised
- On sub-level navigation pages, some users felt
  - the titles and descriptions were contradictory
  - they sit between 2 programmes

#### Programme pages
- Users could not decide if the programme fitted with their current commitments
- The 'What you’ll get' section was not convincing enough to guarantee sign-up

See the <a href="https://docs.google.com/presentation/d/1DTwWYCDogFHeTuYVMmxEsMPkJcTsq7GZUMouz_VO-4A/edit?usp=sharing" target="_blank">beta round 1 user research findings report (opens in new tab)</a> for more detail.

### Business needs identified following feedback and show and tell sessions
- Individual development strands (Pathway 1, 2, 3 and 4 and Upon: aspiring directors and Upon: new directors) should not be presented as separate programmes
- Provide a route for users to see all development programmes and their strands
- Support the user journey of users looking for development programmes by title

## Design thinking

### Providing alternate user journeys to reach the development programmes

#### The career stage journey
This is still the primary way for users to find programmes.

Users have told us throughout research that they like to identify the relevant development programme in this way.

This route also supports the post minimum viable product offerings the business have identified, including guides and roles by career stage.

#### View all programmes
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

### Showing all programmes
To meet the business requirement of showing programmes as a complete programme rather than just their strands, we looked at 3 areas of presentation:

1. **The all programmes page**

A obvious step on this page was to ensure the strands were grouped by the overarching programme name.

We took the decision not to allow navigation down to each programme level, for instance there is no landing page for the Social Work Leadership Pathways programme at this stage.<br>
<a href="prototype-all-programmes-v1.png" target="_blank">![All programmes page](prototype-all-programmes-v1.png "All programmes page")</a>

2. **The sub-level navigation pages**

We decided not to split the cards by the overarching programme as felt this might be confusing to users. We will monitor and review this after each round of research.

3. **The programme pages**

The aside navigation area already contained the programme strands for the career stage group the user visited from. We grouped these by the overarching programme name.<br>
<a href="aside-examples.png" target="_blank">![Aside navigation examples](aside-examples.png "Aside navigation examples")</a>

### Homepage iteration
We changed the descriptions in each career stage card to include alternative job titles to the career stage in the heading.

We based this on user feedback that some job titles were not familiar, so by listing alternatives users may better recognise which stage applied to them.

The job titles are not exhaustive and may change based on further research and policy feedback.<br>
<a href="homepage.png" target="_blank">![Homepage](homepage.png "Homepage")</a>

### Writing Pathways 3 and 4 content
We designed the pages for Pathway 3: heads of service and Pathway 4: practice leaders.

Both pages use the Frontline website as source material.

They follow the same format as the Pathways 1 and 2 pages, except for where we used user feedback from earlier research rounds to try and improve the content, including:

- showing the time commitment in hours in the key facts
- changing 'Website' to 'Delivered by' in the key facts
- updating the 'How it's delivered' section to split in-person and online modules and show how long the take
- changing 'How to apply' to 'Next steps' and editing the link text in that section

We'll observe how these changes are received by users in Round 3 of user research.<br>
<a href="pathway-3.png" target="_blank">![Pathway 3](pathway-3.png "Pathway 3")</a>
<a href="pathway-4.png" target="_blank">![Pathway 4](pathway-4.png "Pathway 4")</a>

### Sub-level navigation content
We added real content to the sub-level navigation page for senior managers and practice leaders to replace the dummy text previously there.

We included the names of the bodies delivering the programmes as some users were surprised to see programmes were delivered by third parties on the main content pages. We hope this will make it clearer the roles DfE (funder) and third parties (provider) play.

The page also includes a link to the 'all programmes' page.<br>
<a href="sub-level-nav-senior-managers-leaders.png" target="_blank">![Senior managers and practice leaders sub-level navigation page](sub-level-nav-senior-managers-leaders.png "Senior managers and practice leaders sub-level navigation page")</a>

## Next steps
We'll test these changes in round 3 of user research.

We also aim to design:

- a 'practitioners' section
- a page for ASYE or Upon

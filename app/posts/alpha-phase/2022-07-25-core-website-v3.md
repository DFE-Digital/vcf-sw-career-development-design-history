---
title: Iterating the core website v3
description: How we created version 3 of the core website
date: 2022-07-25
screenshots:
  items:
    - text: Core website structure with career pathway
      src: core-website-structure-v3.png
    - text: The updated roles page with context links
      src: prototype-blogs-case-studies.png
    - text: New role information page
      src: prototype-role-social-worker-v2.png
related:
  items:
    - text: Designing the core website v1 (alpha)
      href: /alpha-phase/core-website-v1/
    - text: Iterating the core website v2 (alpha)
      href: /alpha-phase/core-website-v2/
    - text: Iterating the core website v4 (beta)
      href: /beta-phase/core-website-v4/
---

{% from "gallery/macro.njk" import appGallery with context %}

<strong class="govuk-tag govuk-tag--turquoise">Core website</strong>&nbsp;<strong class="govuk-tag govuk-tag--purple">Career progression</strong>&nbsp;<strong class="govuk-tag govuk-tag--blue">Development programmes</strong>

## When
Sprint: Sprint 6 and 7
When: 19 - 23 July 2022 / 25 - 30 July 2022

## Overview / user needs
We iterated the core website. At this point, users had not seen the homepage so we kept the content the same - except the Upon title, which was changed on the request of the business. We need to integrate the career progression concept into the website and that was the main driver for this version.

## Design thinking

### Integrating the career pathway
Integrating the pathway was not as simple as adding a link to the homepage. It needed to be fully integrated to cover all possible user journeys. The final structure is shown here:

<a href="core-website-structure-v3.png" target="_blank">![Core website structure with career pathways](core-website-structure-v3.png "Core website structure with career pathways")</a>

#### The user journeys
Users would be able to navigate the website in a variety of ways:

- Via the DfE development programmes > related levels on the career pathway
- Via the career pathway concept > pathway level > related DfE development programmes
- Via the career pathway concept > pathway level > related job roles
- Job roles > pathway level
- Job roles > related DfE development programmes

A new section was added to the homepage: Career progression. This contained two cards with routes to the career pathway and a supporting page hinting at future routes into role information and cast studies/day in the life content.

We added related links to all content pages where a relationship existed. This allowed for a continuous journey around the website.

Lastly, the development programmes pages remained the same as v2. We had no iterated content at this stage, with the focus on producing content for the Pathways programme which was still placeholder text.

## What happened next?

The prototype was tested during the round 3 research sessions. The focus was on comprehension of the following:

- Homepage content
- Career pathway

See the <a href="https://docs.google.com/presentation/d/11MnqvxkWeXfDxY2RkGzq6dtJ_T--K1YTAgiP6yfRmR8/edit?usp=sharing" target="_blank">DSWDC Alpha Round 3 UR Findings report (opens in new tab)</a> for more detail.

#### Iteration between UR days
After research session 3, we made some minor updates to the text. It was clear that placeholder text was tripping up users. Specifically around the last section on the homepage:

Users interpreted that copy as follows:

- 'Social work in DfE' and 'DFE role in social work' referred to social workers working in DfE (schools)
- 'Roadmap' meaning a roadmap for career progression (rather than the DfE roadmap of future deliverables)

We made the following changes:

- Renamed section to 'DfE's role in social work'
- Changed roadmap

{{ appGallery({
  items: [{
    text: "prototype homepage v1",
    caption: "The original homepage v1."
  }, {
    text: "prototype homepage v3b",
    caption: "The iterated homepage based on role level"
  }]
}) }}

> In addition to these changes, we also changed the career pathway copy to reference 'levels' rather than 'roles' as role was again confusing users. Several users had mentioned level as a more descriptful term.

## What needs to happen now?
There are a number of design changes that are required:

See the [design debt report](/design-debt) for a full list.

### Homepage
There are different ways users might want to navigate to learning & development opportunities:

- based on subject area (to find what they’re most interested in)
- based on role/years in practice (to ensure the right level for them)
- to ensure eligibility (to not “waste time reading it”)

(See the <a href="https://docs.google.com/presentation/d/1hPaTh6F0GGfeD3W2p-TMRmWQfTwd_ZPgMixFZrHXpPg/edit?usp=sharing" target="_blank">DSWDC Alpha Round 2 UR Findings report (opens in new tab)</a> for more detail.)

Based on these findings, the development programmes section need to be labelled differently and probably redesigned. The term 'Assessment'  needs to change - they think assessment as in conducting assessments themselves and did not associate this with the DfE assessment service (formally NAAS).

### Pathway page
This entire concept needs proper content and retested. It was clear that placeholder text hindered the effectiveness of the research. Alternate ways to present.

### Pathway level page
This entire concept needs proper content and retested. The job titles and job activities need to be revisited and based on user needs identified in round 3 research.

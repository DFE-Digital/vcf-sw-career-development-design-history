---
title: Iterating the core website v6
description: How we created version 6 of the core website.
date: 2022-12-08
screenshots:
  items:
    - text: Updated homepage
      src: prototype-homepage-v6.png
    - text: New practitioner information page
      src: prototype-practitioner-page-v1.png
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
    - text: Iterating the core website v5 (beta)
      href: /beta-phase/core-website-v5/
    - text: Iterating the core website v7 (beta)
      href: /beta-phase/core-website-v7/
    - text: Iterating the core website v8 (beta)
      href: /beta-phase/core-website-v8/
---

## When
Sprint: Sprint 5
When: 21 November to 2 December 2022

## Overview / user needs
We iterated the core website based on the following:

### Issues identified during beta research rounds 2 and 3

- Sign-up links were overlooked
- Social workers highlighted a career stage gap between ASYE and practice supervisors
- Users confused as to the role Frontline play
- Some content not understood or misinterpreted
- Side contextual navigation on programme pages confused some and unused by others
- Career stage titles and descriptions not always understood

See the <a href="https://docs.google.com/presentation/d/1hPaTh6F0GGfeD3W2p-TMRmWQfTwd_ZPgMixFZrHXpPg/edit?usp=share_link" target="_blank">beta round 2 user research findings report (opens in new tab)</a> and <a href="https://docs.google.com/presentation/d/11MnqvxkWeXfDxY2RkGzq6dtJ_T--K1YTAgiP6yfRmR8/edit?usp=share_link" target="_blank">beta round 3 user research findings report (opens in new tab)</a> for more detail.

### New and updated content

- ASYE programme page
- Upon programme pages
- Side ('aside component') simplification

## Design thinking

### Sign-up link
Users did not see the final sign-up link on the programme content pages. This may have been partly due to them not expecting to be required to visit the Frontline website to sign up. We decided to try the following:
1. Make it clearer that Frontline were the provider and that the user would need to visit their website to find out more and sign up.
2. Explore alternative components to make the call to action link clearer (if option 1 fails to improve the experience).

We looked a 2 possible alternatives to the existing call to action link:
- **The gov button component button**
We decided against this as the button component is generally used to carry out an action, for example applying for something.
- **The action link component**
The <a href="https://components.publishing.service.gov.uk/component-guide/action_link" target="_blank">action link component</a> provides a nice compromise as it's more interesting and clearer than a standard hyperlink but does not imply the start of an action journey. It's also used in several DfE services as detailed in our <a href="https://vcf-sw-career-dev-prototype.herokuapp.com/basic-templates/dfe-components/dfe-action-link" target="_blank">design history</a>.<br>
![Action link component](action-link.png "Action link component")

### Addressing the 'practitioner' career stage gap
We had regular user feedback that there was a gap between the newly qualified social worker and practice leader career stages.

DfE does not currently fund any programmes aimed at the practitioner career stage, but we agreed with the business that we should introduce content relevant to this cohort to ensure all career stages are covered.

The business suggested we included information about continuing professional development (CPD) and the need to record it to stay registered with Social Work England.

A policy colleague drafted a page outlining CPD requirements for social workers. Once it was signed off by other policy people, we refined the content to meet GDS standards and make it consistent with the content on the rest of the service.

### Making the role of Frontline clearer
Users found it confusing to see the word Frontline on the Pathways programme pages as it was often the first time they'd seen the Frontline brand. The solution was to introduce the partners earlier in the journey. It is now explained on the sub-level navigation pages.

### Programme content page iterations
Various content iterations were made to improve users' understanding, including:
- updating the 'How it's delivered' section to show how the programmes are split into online and in-person modules and how long they take
- displaying the number of Pathways programmes and who they're relevant for on sub-level navigation pages

> New text example: It's delivered by the Frontline charity and includes 4 separate pathways, each aimed at a different level of social work leadership.

### Programme page side navigation simplification
During research sessions we noticed that users rarely used the side navigation. The purpose of the side navigation was generally not understood by users and the complexity of presenting the information to meet business requirements made the area confusing.

For now, we have decided to remove all links to other programmes and provide a link to the relevant DfE post-qualifying standards page on GOV.UK.<br>
<a href="aside-simplified-example.png" target="_blank">![Aside simplified example](aside-simplified-example.png "Aside simplified example")</a>

## What we did next

### Usability testing in research round 5

We tested the new and iterated content in research round 5. The main focus was on:

- **creating an alternative career stage taxonomy**
The terms we use to describe the career stages and descriptions are a mixture of DfE and Frontline language. This language is not always familiar to our users. Whilst they can often navigate to the programme relevant to them, we feel we need to test and alternative language. **We created an alternative prototype based on these new terms**.

- the **practitioner information page**
The new practitioner information page was also tested in round 5.

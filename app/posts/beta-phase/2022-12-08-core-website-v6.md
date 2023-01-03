---
title: Iterating the core website v6
description: How we created version 6 of the core website
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
---

## When
Sprint: Sprint 5
When: 21 November to 2 December 2022

## Overview / user needs
We iterated the core website based on the following:

### User needs identified during beta research rounds 2 and 3

- Sign-up links get overlooked
- Social workers highlight a career stage gap between ASYE and Practice supervisors
- Users confused as to the role 'Frontline' play
- Understanding of content not understood or misinterpreted
- Side contextual navigation on programme pages confused some and unused by others
- Career stage titles and descriptions not always understood

See the <a href="https://docs.google.com/presentation/d/1hPaTh6F0GGfeD3W2p-TMRmWQfTwd_ZPgMixFZrHXpPg/edit?usp=share_link" target="_blank">beta round 2 user research findings report (opens in new tab)</a> and <a href="https://docs.google.com/presentation/d/11MnqvxkWeXfDxY2RkGzq6dtJ_T--K1YTAgiP6yfRmR8/edit?usp=share_link" target="_blank">beta round 3 user research findings report (opens in new tab)</a> for more detail.

### New and updated content

- ASYE programme page
- Upon programme page tweaks
- Side ('aside component') simplification

## Design thinking

### Sign-up link
Users failed to see the final sign-up link on the programme content pages. This may have been partly due to them not expecting to be required to visit the 'Frontline' website to sign-up. We decided to try the following:
1. Make it clearer that Frontline were the provider and that the user would need to visit their website to find out more information and sign-up.
2. Explore alternative components to make the call to action link clearer (if option 1 fails to improve the experience)

We looked a 2 possible alternatives to the existing call to action link:
- **The gov button component button**
We disregarded this as an option as the button component is generally used to carry out an action. On our service this would be directed the user to get more information and not starting an action such as applying for instance.
- **The action link component**
The <a href="https://components.publishing.service.gov.uk/component-guide/action_link" target="_blank">action link component</a> provides a nice compromise where it is more interesting and clearer than a standard hyperlink but does not imply the start of an action journey. This is also used in several DfE services as detailed in our <a href="https://vcf-sw-career-dev-prototype.herokuapp.com/basic-templates/dfe-components/dfe-action-link" target="_blank">design history</a>.<br>
![Action link component](action-link.png "Action link component")

### Addressing the 'social worker' career stage gap
Xane and Jim explored having a page for practitioners ** JIM to complete **

### Making the role of Frontline clearer
Users found it confusing to see the word Frontline on the pathway content pages as this was usually the first time they would see the Frontline brand. The solution was to introduce the partners earlier in the journey. It is now explained on the sub-level navigation pages.

### Programme content page iterations
Various content iterations were made to improve users' understanding. These included:
- Changes to the 'how it's delivered' section
- Clarification around the number of pathways on the sub-level navigation page. Previously said there were 4 pathways but not all 4 pathways are displayed on the sub-level navigation page.

> New text example: It's delivered by the Frontline charity and includes 4 separate pathways, each aimed at a different level of social work leadership.

### Programme page side navigation simplification
During research sessions we observed users rarely used the side navigation. The purpose of the side navigation was generally not understood by users and the complexity of presenting the information to meet business requirements made the area confusing.

For now, we have decided to remove all links to other programmes and provide a link to the relevant DfE post-qualifying standards page on gov.uk.<br>
<a href="aside-simplified-example.png" target="_blank">![Aside simplified example](aside-simplified-example.png "Aside simplified example")</a>

## What happened next?

### Usability testing in research round 5

We tested the new and iterated content in research round 5. The main focus was on:

- **Creating an alternative career stage taxonomy**
The terms we use to describe the career stages and descriptions are a mixture of DfE and Frontline language. This language is not always familiar to our users. Whilst they can often navigate to the programme relevant to them, we feel we need to test and alternative language. **We created an alternative prototype based on these new terms**.

- **Practitioner information page**
The new practitioner information page as also tested in round 5.

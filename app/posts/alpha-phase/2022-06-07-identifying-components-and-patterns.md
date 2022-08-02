---
title: Identifying DfE components and patterns
description: How we went about identifying design patterns and components
date: 2022-06-07
screenshots:
  items:
    - text: Various card components
      src: prototype-card-patterns.png
    - text: Sub-level navigation concept
      src: prototype-sub-level.png
---

## When
Sprint: Sprint Alpha Planning
When: 24 May 2022 - 7 June 2022

## Overview
As detailed in the [setting up for design post](/alpha-phase/setting-up-for-design/), we needed to create several components not included in the <a href="https://design-system.service.gov.uk/" target="_blank">gov.uk prototyping kit (opens in new tab)</a>. These included:

- Cards to aid in navigation to content pages
- Sub-level navigation to support grouping of content pages at lower levels
- Content pages to support large volumes of content
- Homepage header
- DfE branded header [^1]

A review of other DfE services identified that there was little consistency of approach in DfE. Most DfE services on the .education domain use the gov.uk header and GDS Transport font. We also identified 5 different card components in use across these DfE services:

- <a href="https://professional-development-for-teachers-leaders.education.gov.uk" target="_blank">https://professional-development-for-teachers-leaders.education.gov.uk/</a>
- <a href="https://esfahelp.education.gov.uk/hc/en-gb" target="_blank">https://esfahelp.education.gov.uk/hc/en-gb</a>
- <a href="https://support.tlevels.gov.uk/hc/en-gb" target="_blank">https://support.tlevels.gov.uk/hc/en-gb</a>
- <a href="https://help-for-early-years-providers.education.gov.uk/" target="_blank">https://help-for-early-years-providers.education.gov.uk/</a>
- <a href="https://explore-education-statistics.service.gov.uk/" target="_blank">https://explore-education-statistics.service.gov.uk/</a>

### Component audit

Examples of all the services and components audit can be found in these two documents:

  - <a href="/documents/design-board-1.pdf" target="_blank">DfE service examples PDF (opens in new tab)</a>
  - <a href="/documents/design-board-2.pdf" target="_blank">DfE component examples PDF (opens in new tab)</a>

## Design thinking
At this stage, the core website is very simple. We opted for a flat site structure, using cards on the homepage to guide users into the development programmes. Users could navigate back using a gov.uk back link and across different programmes using contextual links in the aside area. A sub-level navigation component was designed. This was **not** updated to match the final card component used elsewhere.

There was an unofficial brief to make the website rich and interactive. We decided against using cards with images - using images would a) require sourcing of imagery and b) felt unnecessary given the simplicity of the service.

The homepage required a title banner to explain the purpose of the service. We identified a common component used on several DfE services:

![Homepage title banner](prototype-homepage-header-example.png "Homepage title banner")

[^1]: Guidance on creating a DfE branded header is now available via the awesome <a href="https://design.education.gov.uk/" target="_blank">Design in DfE (opens in new tab)</a> resource. For more information, contact Andy Jones as of 1 August 2022.

## What happened next?
We continued to create components and templates throughout this sprint to aid in rapid prototyping later on.

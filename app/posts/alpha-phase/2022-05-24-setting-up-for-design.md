---
title: Setting up for design
description: The approach for getting ready for design.
date: 2022-05-24
screenshots:
  items:
    - text: Possible templates identified
      src: prototype-landing-page-templates.png
    - text: Card patterns from around DfE
      src: prototype-card-patterns.png
---

## When
Sprint: Sprint Alpha Planning
When: 24 May 2022 - 7 June 2022

## Overview
The first step was to setup DfE environments. These accounts were requested as follows:

Github - via the form pinned to the DfE Slack channel #digital-tools-support.
Heroku - via Stuart Charlesworth and Paul Cripwell.

## Where we started

We agreed, as a team, to use .gov.uk design patterns. The interaction designer (Jonathan Porton) had a meeting with several lead IxDs in DfE (Andy Jones and Anne Chan). Following this meeting the following was confirmed:

> "Anything on education.gov.uk must not use the GOV.UK Logotype and crown, replace both with Department for Education and use a generic font family like Arial, Sans-serif."

## Design thinking

Following initial conversations, we agreed to base the designs on the gov.uk design system. There were several reasons for taking that approach:

- This was not going to become a permanent resource, so a gov campaign website approach was not appropriate.
- The path of least resistance - by using standard gov patterns we felt it would be easier to get approval and sign-off from DfE stakeholders.
- Quick to get going. Rather than create something bespoke, the components already existed so rapid development was possible.
- We didn't want to set expectations. If we designed something away from the gov.uk patterns, such as 'Get into teaching' we would set stakeholder expectations around branding etc.

We decided to start design directly in the <a href="https://design-system.service.gov.uk/" target="_blank">gov.uk prototyping kit (opens in new tab)</a>. Due to the simplicity of the requirement, it was easier to create the pages here vs. Figma where we might have to design bespoke components.

We knew there was a business requirement to create a basic website based around the DfE development programmes. This meant we would, at a minimum, need a homepage, content pages and possible sub-level navigation pages. Additionally, the user was going to need to navigate from the homepage to content (guidance) pages. Therefore it was decided to use navigation via card components (screenshot and link below).

Lastly, we had little information on how social workers consume content. We knew they were time poor and often moving between cases, so it was felt the service should work for all devices. This meant, any new components should also work on mobile and tablet.

## Design tasks completed

The following design tasks where completed:

- Creation of DfE repo and Heroku app:
  - <a href="https://github.com/DFE-Digital/vcf-sw-career-development-prototype" target="_blank">Github repository (opens in new tab)</a>
  - <a href="https://vcf-sw-career-dev-prototype.herokuapp.com/" target="_blank">Heroku app (opens in new tab)</a>
- Capture of DfE service examples in Lucid Board:
  - <a href="/documents/design-board-1.pdf" target="_blank">DfE service examples PDF (opens in new tab)</a>
  - <a href="/documents/design-board-2.pdf" target="_blank">DfE component examples PDF (opens in new tab)</a>
- Design of basic templates (and import of personal ones)
- Creation of <a href="https://vcf-sw-career-dev-prototype.herokuapp.com/basic-templates/content-card-examples" target="_blank">initial card components</a>


## What happened next?

With the environment and basic templates setup, we begun looking at various concepts based on the discovery reports and internal workshops (such as ideation and crazy 8 sessions).

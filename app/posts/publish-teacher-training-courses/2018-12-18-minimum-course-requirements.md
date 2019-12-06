---
title: New course wizard – Minimum course requirements
description: Choose the minimum course requirements from the new course wizard.
tags: publish-teacher-training-courses
---
Following on from the [investigation into UCAS specific course requirements](/publish-teacher-training/specific-requirements), a design that comes towards the end of the new course wizard.

This design aims to:

* move more providers to the most flexible default (eg option 3)
* make it clear what that choice means

Things not yet considered in this design:

* communicating legal minimums (eg Primary requires a C in Science)
* applying defaults based on legal minimums
* what happens when you hit ‘change’

[Legal requirements are documented on GOV.UK](https://www.gov.uk/government/publications/initial-teacher-training-criteria/initial-teacher-training-itt-criteria-and-supporting-advice#c11-gcse-standard-equivalent):

> Providers should look for further evidence of a breadth of achievement in English where applicants have achieved a GCSE grade 4 or above in English literature only.

{% from "figure/macro.njk" import appFigure %}
{{ appFigure({
  image: {
    path: page.filePathStem | replace("/posts", "/images"),
    file: "minimum-course-requirements.png"
  },
  caption: "Minimum course requirements"
}) }}
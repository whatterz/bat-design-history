---
title: First designs for a minimum viable service
description: A minimum viable service that could allow the providers to access and manage their ITT applications.
date: 2019-02-19
related:
  items:
  - text: Confluence documentation
    href: https://dfedigital.atlassian.net/wiki/spaces/BaT/pages/279314433/Designs
  - text: Prototype
    href: https://bat-manage-teacher-training-applications.herokuapp.com/provider/v01/index
  - text: Original manage applications roadmap
    href: https://docs.google.com/spreadsheets/d/1n4HVUfgKdZXySAFh3KXdCqZ-Ru71DVt7RAxOvl_NO3Y
---
A minimum viable service that could allow the providers to access and manage their ITT applications.

Only admins have access to the system/applications. The providers manage the workflow outside the system.

The applciations themselves are tagged to various statuses that the admins can use to track the progress on any application.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [
    { text: "Dashboard" },
    { text: "New applications" },
    { text: "New application" },
    { text: "Change application status" },
    { text: "Interview offered" }
  ]
}) }}

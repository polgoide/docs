---
title: Creating stakeholders
layout: home
---
Stakeholders are anyone with shares, options or that has been part of a transaction in the company. Employees as stakeholders and can be identified and group as such


To create a stakeholder, use the following end-point: https://www.capboard.io/api/docs#/stakeholders/post_api_stakeholders
- id: company id
- type: person | entity. For employees, always use person.
- custom_identifier: used for employee IDs.
- country: if not set, it will be the company's country by default.
The rest of fields are optional but highly recommended as they can be later used to generate documents.

Check the output: https://www.capboard.io/api/docs#model-Stakeholder
---
title: Creating stakeholders
layout: home
nav_order: 3
---
Each person or institution that holds shares of a company is considered to be a "Stakeholder". Founders, investors, advisors with equity, employees with stock or equity... are Stakeholders.


To create a stakeholder, use the following [endpoint](https://www.capboard.io/api/docs/endpoints#/stakeholders/post_api_stakeholders)
- `id`: company id
- `type`: "person" or "entity". For employees, always use person.
- `custom_identifier`: When integrating capboard with third party providers like HR tools, this field can be used to set the employee id on said platform.
- `country`: if not set, it will be the company's country by default.
The rest of fields are optional but highly recommended as they can be later used to generate documents.
---
title: Creating stakeholders
layout: home
---
Each person or institution that holds shares of our company is a Stakeholder on Capboard. Founders, investors, advisors with equity, employees with stock or equity... are Stakeholders.


To create a stakeholder, use the following end-point: https://www.capboard.io/api/docs#/stakeholders/post_api_stakeholders
- id: company id
- type: "person" or "entity". For employees, always use person.
- custom_identifier: used for employee IDs.
- country: if not set, it will be the company's country by default.
The rest of fields are optional but highly recommended as they can be later used to generate documents.

Check the output: https://www.capboard.io/api/docs#model-Stakeholder
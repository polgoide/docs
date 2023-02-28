---
title: Exercising equity
layout: home
nav_order: 5
---

There are 2 ways to exercise grants:
- Opening an exercising window: A time window where employees can choose if they want to exercise and how many is set.
- Directly: Collaborators can set the exercised amount

## Opening an exercising window

1. First you will have to setup the [exercising details](https://www.capboard.io/api/docs/endpoints#/companies/post_api_companies__id__setup_exercising) which consists on setting which collaborators will be able to approve or deny exercising requests, as well as indicating the payment details that will be shown to employees once their exercising is approved.

2. Now an [exercising window](https://www.capboard.io/api/docs/endpoints#/grants/post_api_grants_exercising_periods) can be opened.

3. Once an exercising window is active, [exercising requests](https://www.capboard.io/api/docs/endpoints#/grants/post_api_grants_exercising) can be made.

4. Those requests can then be approved or denied using the [following endpoint](https://www.capboard.io/api/docs/endpoints#/grants/post_api_grants_requests__id__status) with `approved` param. When a request is approved, the employee will receive an email with the payments details he must pay to in order to get them exercised. 

5. The previous endpoint can also be used to exercise or deny the the request (in case the employee didn't pay). Just use the boolean param `exercised`.
 If they are exercised, the shares will be issued and the employee will be able to see them on My Equity section/portfolio endpoint.


## Directly

1. If you want to handle the whole process outside or import old exercises, you can use the [direct method](https://www.capboard.io/api/docs/endpoints#/grants/post_api_grants_exercising).


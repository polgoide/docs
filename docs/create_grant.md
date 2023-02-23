---
title: Creating equity grants
layout: home
---
ESOPs on Capboard have 3 parts:

- Pool: the amount of shares reserved and approved for the ESOP. Pool size can be increased or decreased, while it's also possible to have more than one. Each Pool can have one or several Plans. 
- Plan: ESOP clauses are set at a Plan level: vesting, cliff, good and bad leaver, exercising windows, etc. Plan-level presets can be overwritten at a grant level.
- Grant: Stock options, Warrants or Phantom shares are assigned to Stakeholders through Grants. Each Grant is linked to a Plan and inherits all clauses by default, but they can be overwritten. Each Stakeholder can have one or more grants, from one or more Plans.

How to create a Pool
Creating a Pool is the first step to launch an ESOP on Capboard. The ESOP should already be approved by your Board before you can create it.

To create a Pool, go to Equity Plans > Pools and fill the form:

- Pool name: ESOP or similar
- Amount allocated for grants: how many shares has the company approved to be granted through the ESOP. It's usually 10-15% of the cap table.
- Date: date which the Pool was approved.
- Underlying share class: the share class to which the ESOP will be issued, usually Common.

How to create a Plan
Once the Pool has been created, is time to create the Plan.

- Plan name: name of the ESOP. Employees receiving grants from a Plan will be able to see the name.
- From pool: pick the Pool to be used to issue shares for this Plan.
- Date: the day when the ESOP was approved, usually the same as the Pool creation date.
- Grant type: type of ESOP, pick between Stock options or Phantom shares. It's very important to choose the right one as it has implications for the cap table. If in doubt, review your legal documents or ask your lawyer. 
- Price: set up strike and purchase price.
- Vesting: pick among the options to set up the vesting schedule, cliff, etc.
- Definitions: the details of good leaver, bad leaver and liquidation event. Stock holders will be able to see it.


How to create a Grant
Once we have a Pool and a Plan, we can start granting options to Stakeholders. Endpoint: https://www.capboard.io/api/docs#/grants/post_api_grants
- Select the Stakeholder to grant options to. You can create if it doesn't exist yet.
- Pick the Plan to apply the rules from.
-  Granted shares: the amount of shares to be granted. If there are not enough available, the Pool size can be increased from Transactions > Pool Increase.
- The rest of details (Price, Vesting, Definitions) are inherited from the Plan, but you can customize it at a Grant level.
Upon clicking on "Save", the Grant will be creating and the Stakeholder will be able to see it under "My Equity".
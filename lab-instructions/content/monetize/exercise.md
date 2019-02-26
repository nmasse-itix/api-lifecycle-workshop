---
title: "Exercise"
weight: 1
---

## Help ACME drive revenue from its Brewery API!

ACME Customers are using the Brewery API to discover the Beer Catalog and the inventory. With an ever growing demand, ACME wants to drive new revenue from the usage of its API. Help them setup API Monetization in 3scale!

- Open your **3scale Admin Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_admin_portal_url >}}/login
```

- Go to **Beer Catalog API (PROD, v1.0)** (top dropdown list)
- Click **Applications**, **Application Plans**
- Edit the **silver** plan to add a fixed price (1$ per call) for the **Get beer having name** method
- Click **Update Application Plan**
- Edit the **gold** plan to add a variable price for the **Get beer having name** method: 1$ for 1 to 100 calls, then 0.5$ up to 1000 calls, free afterwards.
- Click **Update Application Plan**

---
title: "Exercise"
weight: 1
---

## Manage the ACME Brewery API!

Since the beginning of this workshop, ACME has released two versions of its API. Let's manage them!

- Open your **3scale Admin Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_admin_portal_url >}}/p/login
```

- Review the existing services and explain **how APIs are versioned**
- If ACME needs to release a maintenance version "1.1" of its API, **how would it materialize in the 3scale Admin Portal**?
- Create two application plans for the **Beer Catalog API (PROD, v1.0)**: `silver` and `gold`.
- Add rate limits to the `silver` application plan
- Create a new test application consuming the `silver` application plan
- Ensure the rate limits are applied
- Pretend there is a security issue and suspend the application

To complete your understanding, explain **how you would declare the v1.0 as deprecated** and **how you would help the consumer move from the deprecated v1.1 to v2.0**.
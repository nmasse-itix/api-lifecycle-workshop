---
title: "Exercise: Check"
weight: 3
---

## Check that the first implementation of the ACME Brewery API is deployed!

In the previous exercise, you automated the Continuous Integration and Continuous Deployment (CI/CD) of the ACME Brewery API. In this exercise, you will try to use the ACME Brewery API as one of the ACME customers would do.

- Open your **3scale Developer Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_developer_portal_url >}}/login
```

- Login with the default test account (login = `john`, password = `123456`)
- Go to **Applications** and grab the API Key of the "Beer Catalog API (**PROD**, v1.0)"
- Go to **Documentation** > **Beer Catalog API (PROD, v1.0)**
- Unfold **/beer**
- Click the red exclamation mark on the right side
- Paste the API Key and click **Authorize**
- Click the **Try it out!** button

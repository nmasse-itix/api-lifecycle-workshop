---
title: "Exercise"
weight: 1
---

## Help ACME manage the growing demand on their Brewery API!

- Open your **3scale Developer Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_developer_portal_url >}}
```

- Make sure you are logged in
- Click **Applications**
- Click on your application (the one that uses the **Beer Catalog API (PROD, v1.0)** service)
- Next to the plan name, click **Review/Change**
- Select the **gold** plan
- Click **Request Plan change**

*The administrators has been notified of your request. Since we do not have access to the administrator's mailbox, we will complete the rest of the process by hand.*

- Open your **3scale Admin Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_admin_portal_url >}}/login
```

- Go to **Beer Catalog API (PROD, v1.0)** (top dropdown list)
- Go to **Applications** > **Listing**
- Click on your application
- In the **Change Plan** box, select **gold** and click **Change Plan**

To complete your understanding, from the **3scale Developer Portal** pretend you have special needs and request a special treatment (such as higher limits). From the **3scale Admin Portal** fulfill this request.

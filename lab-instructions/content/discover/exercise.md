---
title: "Exercise"
weight: 1
---

## Help ACME customers to discover the Brewery API!

Since the beginning of this workshop, ACME has released two versions of its API. It's now time to promote their discovery and usage by ACME customers!

We will first start by defining the developer on-boarding workflow.

- Open your **3scale Admin Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_admin_portal_url >}}/login
```

- Go to **Beer Catalog API (PROD, v1.0)** (top dropdown list)
- Go to **Applications** > **Application Plans**
- In the **Default Plan** drop down list, select `silver`
- Below, in the list of all service plans, click **Publish** for each application plan (`silver` and `gold`)
- Go to **Integration** > **Settings**
- In the **Default Service Plan** section, in the **Default Plan** drop down list, select `Default`
- Go to **Audience** (top dropdown list) > **Developer Portal** > **Content**
- Review the **Homepage**. This will be the first page your developers will see.

You can continue by testing this on-boarding workflow as a normal developer would do.

- Open your **3scale Developer Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_developer_portal_url >}}
```

- Click the **Logout** button on the top right corner if you are already logged in
- Click **Documentation**, pretend you want to subscribe to the **Beer Catalog API (PROD, v1.0)** service
- Click **Sign-in**
- At the bottom of the sign-in form, click **Sign-up**
- Fill in the form with your corporate or personal details
- Click **Sign-up**
- Check your mailbox and click on the activation link
- Login with your chosen credentials
- Go to **Applications**

*A client application for the "Beer Catalog API (PROD, v1.0)" service should have been created.*

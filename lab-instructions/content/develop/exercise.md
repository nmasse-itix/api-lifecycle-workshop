---
title: "Exercise"
weight: 1
---

## Help ACME customers to better develop apps based on the Brewery API!

ACME customers can now discover the Brewery API, on-board and quickly get access to the API. They will start developing client applications based on this API and we want to make sure we provide enough resources for developers to get the most out of the Brewery API.

In this exercise, we will create a new Page in the Developer Portal, describing how to use an API secured by OpenID Connect.

- Open your **3scale Admin Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_admin_portal_url >}}
```

- Go to **Audience** (top dropdown list) > **Developer Portal** > **Content**
- Click **New Page** in the top right corner
- Set the **Title** to `Best Practices`
- Set the **Path** to `/docs/best-practices`
- Leave the **Layout** to `Main Layout`
- Unfold the **Advanced Options** and set the **Handler** to `Markdown`
- In the content pane, write something similar to:

```md
# Best Practices

## How to use OpenID Connect

To use OpenID Connect, you will have to first get a token from the Authorization Server and then use it to query our API. 

Bla bla bla. To be continued...
```

- Click **Create Page**
- Click **Publish**

- In the left pane, click the **Documentation** page
- In the content pane, just below `<h1>API Catalog</h1>` add this line:

```md
  <p><a href="/docs/best-practices">Best Practices</a></p>
```

- Click **Save**, then **Publish**

- Open your **3scale Developer Portal** by copying this URL in your web browser and changing the `userXY` by your actual username.

```raw
{{< param 3scale_developer_portal_url >}}
```

- Click on **Documentation**
- Click on **Best practices**

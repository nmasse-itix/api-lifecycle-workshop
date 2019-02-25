---
title: "Exercise: Build and deploy"
weight: 1
---

## Build and deploy the first implementation of the ACME Brewery API!

The ACME did a good job in implementing the ACME Brewery API. You can review the source code [from the GIT repository]({{< param github_repository_url >}}/tree/master/{{< param api_backend >}}).

Let's deploy this first version in our DEV environment!

- Open the [OpenShift Web Console]({{< param openshift_console_url >}}/console/catalog), click `SSO` and login with your username.
- Find the **Red Hat OpenJDK 8** in the catalog and click on it
- Click **Next >**
- In **Add to project**, select `Beer Catalog (DEV)`
- Choose the version 1.2
- In **Application Name**, type `beer-catalog-impl``
- In **Git Repository**, type `{{< param github_repository_url >}}`
- Click **view advanced options**
- In **Context Dir**, type `/{{< param api_backend >}}`
- At the bottom of the page, click **Create**

To complete your understanding, explain **the different steps OpenShift went through to deploy the API implementation**.

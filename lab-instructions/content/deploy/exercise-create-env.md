---
title: "Exercise: Create two environments"
weight: 1
---

## Create two environments: TEST and PROD!

The ACME Brewery API is implemented and conform to our specification. We can now envision a deployment in all the ACME environments.

Let's start by provisioning a TEST environment:

- Open the [OpenShift Web Console]({{< param openshift_console_url >}}/console/catalog)
- In the top-left dropdown box, select the `Beer Catalog (TEST)` project
- In the top-right corner, select **Add to project**, then **Select from project**.
- Select the `Beer Catalog environment` template and click **Next**
- On the **Information** screen, just click **Next**
- On the **Configuration** screen, fill-in the environment name: `test` (all lower case!)
- **Do not change the other fields**
- Click **Create**

Continue with the PROD environment:

- In the top-left dropdown box, select the `Beer Catalog (PROD)` project
- In the top-right corner, select **Add to project**, then **Select from project**.
- Select the `Beer Catalog environment` template and click **Next**
- On the **Information** screen, just click **Next**
- On the **Configuration** screen, fill-in the environment name: `prod` (all lower case!)
- **Do not change the other fields**
- Click **Create**

---
title: "Exercise: CI/CD"
weight: 2
---

## Deploy the first implementation of the ACME Brewery API in TEST and PROD!

The ACME Brewery API is implemented and conform to our specification. We can now envision a deployment in all the ACME environments. Unfortunately ACME has a lot of environments and deploying manually in each and every environment would be error prone and time consuming. It is time to think about automation and Continuous Deployment!

- Open the [OpenShift Web Console]({{< param openshift_console_url >}}/console/catalog)
- In the top-left dropdown box, select the `Beer Catalog (BUILD)` project
- In the top-right corner, select **Add to project**, then **Select from project**.
- Select the `Beer Catalog pipeline` template and click **Next**
- On the **Information** screen, just click **Next**
- On the **Configuration** screen, fill-in your username
- **Do not change the other fields**
- Click **Create**

Your CI/CD pipeline is now in place, congratulations!

- Go to **Builds** > **Pipelines**
- Click on your pipeline (the one that ends with your username)
- Click **Start Pipeline**

Wait for your pipeline to finish!

To complete your understanding, explain **what you need to do if a new version of the API implementation is released** and **what you need to do if the API Contract is updated**!

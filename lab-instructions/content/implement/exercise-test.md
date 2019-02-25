---
title: "Exercise: Test"
weight: 2
---

## Test the first implementation of the ACME Brewery API!

The ACME did a good job in implementing the ACME Brewery API and you deployed it successfully in the previous exercise.

It is now time to run the integration tests we defined in the **Test** step to make sure our first implementation is conform to our specification.

- Open the [OpenShift Web Console]({{< param openshift_console_url >}}/console/catalog)
- Make sure you are in the `Beer Catalog (DEV)` project (the dropdown box in the top left corner)
- Copy the public URL of your implementation
- Go to [Microcks]({{< param microcks_url >}}/#/services), click the **Details** button of the `Beer Catalog 1.0` service
- Click **New Test**
- In the **Test Endpoint**, paste the public URL of your implementation and **append `/api` to the end of the URL**
- In the **Runner** dropdown box, choose `POSTMAN`
- Click **Launch Test !**
- Wait for the test to complete
- **Is your implementation conform ?**
- Click on **Full results**
- Expand each method to discover the requests and responses exchanged during the test

To complete your understanding, explain **how a repository of test attempts can help post-mortem analysis**.

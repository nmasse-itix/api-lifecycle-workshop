---
title: "Exercise"
weight: 1
---

## Review the security of the ACME Brewery API!

ACME released a first version of its Brewery API secured with API Keys. However, since high security is a stake, we need to update the security scheme to OpenID Connect.

- Open the [APICurio Studio]({{< param apicurio_studio_url >}}/apis/import)
- Login with your account
- Copy [this URL](beer-catalog-2.0.yaml) and import it in APIcurio
- Review the existing design and try to determine what changed with the previous API Contract
- Open the [OpenShift Web Console]({{< param openshift_console_url >}}/console/catalog)
- Go to **Builds** > **Pipelines**
- Click on your pipeline (the one that ends with your username)
- Click **Actions** > **Edit**
- Change line number 8 from:

```yaml
      openapi_file: "api-contracts/beer-catalog-1.0.yaml",
```

to:

```yaml
      openapi_file: "api-contracts/beer-catalog-2.0.yaml",
```

- Click **Save**
- Click **Start Pipeline**

Wait for your pipeline to finish!

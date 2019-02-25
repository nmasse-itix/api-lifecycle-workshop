+++
title = "Manage"
weight = 9
chapter = true
pre = "<b>9. </b>"
+++

### Chapter 9

# Manage

In the **Manage** phase, after the APIs are deployed and secured, they need to be managed. This activity encompasses versioning, deprecation, and retirement. As a best practice, versioning should follow the semantic versioning scheme. This means when it is deployed, any new minor version of an API replaces the previous version. All consumers that were using the previous version are then using the latest version. When a breaking change occurs, a major version is released and deployed side by side with the previous one. Consumers can migrate from the previous version to the current one. They migrate at their own pace by adapting their code to the new version.

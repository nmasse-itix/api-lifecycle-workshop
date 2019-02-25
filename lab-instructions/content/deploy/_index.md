+++
title = "Deploy"
weight = 7
chapter = true
pre = "<b>7. </b>"
+++

### Chapter 7

# Deploy

In the **Deploy** phase, you will make sure you have a Continuous Integration/Continuous Deployment (CI/CD) pipeline that automates the delivery of your APIs to the production environment. The CI/CD pipeline reuses the tests you defined earlier to ensure the APIs to be deployed do not violate your specifications. Those integration tests are automated and run automatically as part of the pipeline.

The automated integration tests should also ensure the backward compatibility of your APIs. If a 1.2 version of an API is released, it must be backward compatible with any release of the 1.x branch (1.0, 1.1, and so on).

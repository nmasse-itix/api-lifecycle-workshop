---
title: "The workshop environment"
weight: 3
---

During this workshop, you will go through the different stages composing the API Full Lifecycle.

The workshop setup is as shown in schema below. We'll use:

* A multi-tenant `INFRA` environment to host the components used during building and deploying. Namely Apicurio, Microcks, Jenkins and Ansible Tower.
* One `DEV` environment per attendee where you will deploy your API implementation (based on Spring Boot but this is also subject to variants).
* One `TEST` environment where API implementation will be deployed once tested alongside with an API Gateway. In `TEST` environment, we primarily focus on testing/validating the API Gateway policies and configuration as well as feeding API Management system with API declaration,
* One `PROD` environment where API implementation and API Gateway configuration are promoted after having tested. On the API Management backend side, API definition should also appear as deployed onto a Production environment.

![Workshop Setup](workshop-setup.png)

---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

boolean securityEnabledOnly = True;

graphClient.servicePrincipals("{id}")
	.getMemberGroups(securityEnabledOnly)
	.buildRequest()
	.post();

```
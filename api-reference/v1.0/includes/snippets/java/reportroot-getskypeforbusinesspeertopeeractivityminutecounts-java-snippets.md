---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

Report report = graphClient.reports()
	.getSkypeForBusinessPeerToPeerActivityMinuteCounts('D7')
	.buildRequest()
	.get();

```
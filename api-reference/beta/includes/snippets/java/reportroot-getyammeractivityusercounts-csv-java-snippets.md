---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IYammerActivitySummaryCollectionPage getYammerActivityUserCounts = graphClient.reports()
	.getYammerActivityUserCounts('D7')
	.buildRequest()
	.get();

```
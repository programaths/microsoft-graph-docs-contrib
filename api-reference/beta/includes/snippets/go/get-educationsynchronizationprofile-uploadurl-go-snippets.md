---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-beta-sdk-go"
	  //other-imports
)

graphClient := msgraphsdk.NewGraphServiceClientWithCredentials(cred, scopes)



uploadUrl(), err := graphClient.Education().SynchronizationProfiles().ByEducationSynchronizationProfileId("educationSynchronizationProfile-id").UploadUrl().Get(context.Background(), nil)


```
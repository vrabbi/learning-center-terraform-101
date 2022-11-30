# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=vrabbi&repo=learning-center-terraform-101",
  "consoleVendor" : "kubernetes",
  "difficulty" : "beginner",
  "dockerMemory" : 768,
  "dockerStorage" : 5,
  "duration" : "45m",
  "enableConsole" : true,
  "enableDocker" : true,
  "enableEditor" : true,
  "enableRegistry" : true,
  "enableTerminal" : true,
  "exercises" : [ "providers", "resources", "data sources", "modules", "backends" ],
  "maxSessions" : 15,
  "memoryResources" : "1Gi",
  "namespaceBudget" : "small",
  "projectName" : "terraform-101",
  "registryMemory" : 768,
  "registryStorage" : 5,
  "terminalLayout" : "split/2",
  "workshopDescription" : "intro to terraform",
  "workshopFilesUrl" : "github.com/vrabbi/learning-center-terraform-101",
  "workshopTitle" : "Terraform 101 Course"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [resources/workshop.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml matched [resources/workshop.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [resources/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":15,"bsGitBranch":"main","consoleVendor":"kubernetes","enableDocker":true,"enableTerminal":true,"duration":"45m","dockerMemory":768,"exercises":["providers","resources","data sources","modules","backends"],"workshopDescription":"intro to terraform","workshopFilesUrl":"github.com/vrabbi/learning-center-terraform-101","artifactId":"terraform-101","registryStorage":5,"terminalLayout":"split/2","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Terraform 101 Course","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-terraform-101","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"terraform-101"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input14002520333631478716, --data-values-file, /tmp/accelerator-options18137838768922089823.json, --output-files, /tmp/ytt-output16951403913160683122]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [resources/training-portal.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml matched [resources/training-portal.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [resources/training-portal.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":15,"bsGitBranch":"main","consoleVendor":"kubernetes","enableDocker":true,"enableTerminal":true,"duration":"45m","dockerMemory":768,"exercises":["providers","resources","data sources","modules","backends"],"workshopDescription":"intro to terraform","workshopFilesUrl":"github.com/vrabbi/learning-center-terraform-101","artifactId":"terraform-101","registryStorage":5,"terminalLayout":"split/2","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Terraform 101 Course","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-terraform-101","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"terraform-101"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input4801028625070628224, --data-values-file, /tmp/accelerator-options17244098777868190168.json, --output-files, /tmp/ytt-output6114242345042283551]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/workshop.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/workshop.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml matched [workshop/workshop.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":15,"bsGitBranch":"main","consoleVendor":"kubernetes","enableDocker":true,"enableTerminal":true,"duration":"45m","dockerMemory":768,"exercises":["providers","resources","data sources","modules","backends"],"workshopDescription":"intro to terraform","workshopFilesUrl":"github.com/vrabbi/learning-center-terraform-101","artifactId":"terraform-101","registryStorage":5,"terminalLayout":"split/2","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Terraform 101 Course","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-terraform-101","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"terraform-101"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input16934651591867551724, --data-values-file, /tmp/accelerator-options9029800654900909990.json, --output-files, /tmp/ytt-output15847978367421853207]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/modules.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml matched [workshop/modules.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/modules.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"maxSessions":15,"bsGitBranch":"main","consoleVendor":"kubernetes","enableDocker":true,"enableTerminal":true,"duration":"45m","dockerMemory":768,"exercises":["providers","resources","data sources","modules","backends"],"workshopDescription":"intro to terraform","workshopFilesUrl":"github.com/vrabbi/learning-center-terraform-101","artifactId":"terraform-101","registryStorage":5,"terminalLayout":"split/2","enableConsole":true,"artifactVersion":"0.0.1-beta","registryMemory":768,"workshopTitle":"Terraform 101 Course","bsGitRepository":"github.com?owner=vrabbi&repo=learning-center-terraform-101","namespaceBudget":"small","memoryResources":"1Gi","difficulty":"beginner","enableEditor":true,"enableRegistry":true,"dockerStorage":5,"projectName":"terraform-101"}
┃ ┃ ┃ ┃ ┗ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input6681400224741275616, --data-values-file, /tmp/accelerator-options14634590077067356230.json, --output-files, /tmp/ytt-output17735809130218135873]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 0) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 0) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/0.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md matched [workshop/content/exercises/0.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/0.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># providers]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/0.md' matched 'workshop/content/exercises/0.md' with groups {g0=workshop/content/exercises/0.md} and was rewritten to 'workshop/content/exercises/providers.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 1) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 1) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/1.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md matched [workshop/content/exercises/1.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/1.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># resources]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/1.md' matched 'workshop/content/exercises/1.md' with groups {g0=workshop/content/exercises/1.md} and was rewritten to 'workshop/content/exercises/resources.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 2) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[6].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 2) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/2.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md matched [workshop/content/exercises/2.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/2.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># data sources]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/2.md' matched 'workshop/content/exercises/2.md' with groups {g0=workshop/content/exercises/2.md} and was rewritten to 'workshop/content/exercises/data-sources.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 3) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[7].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 3) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[7].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/3.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md matched [workshop/content/exercises/3.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/3.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[7].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># modules]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[7].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/3.md' matched 'workshop/content/exercises/3.md' with groups {g0=workshop/content/exercises/3.md} and was rewritten to 'workshop/content/exercises/modules.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[8] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 4) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[8].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 4) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[8].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/exercises/4.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md matched [workshop/content/exercises/4.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/exercises/4.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[8].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [replace me-># backends]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[8].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'workshop/content/exercises/4.md' matched 'workshop/content/exercises/4.md' with groups {g0=workshop/content/exercises/4.md} and was rewritten to 'workshop/content/exercises/backends.md'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[9] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 5) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[10] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 6) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[11] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 7) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[12] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 8) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[13] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#exercises.size() > 9) evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[14] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[14].include (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh]
┃ ┃ ┃ ┃ ┃ Debug resources/training-portal.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug resources/workshop.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/0.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/1.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/2.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/3.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/4.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/5.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/6.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/7.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/8.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/exercises/9.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content/setup-environment.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-overview.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/content/workshop-summary.md matched [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> included
┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/exercises/01-sample-step.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/setup-environment.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-overview.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/content.bak/workshop-summary.md didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/modules.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┃ ┃ Debug workshop/setup.d/setup-resources.sh didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┃ ┃ ┗ ┗ Debug workshop/workshop.yaml didn't match [workshop/content/setup-environment.md, workshop/content/workshop-overview.md, workshop/content/workshop-summary.md, workshop/setupd.d/etup-resources.sh] -> excluded
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```

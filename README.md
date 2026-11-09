# task-source-trigger-prod-1

Test fixture for ACR Tasks source-trigger (commit webhook) CI, run from the acr-ci repo (suite `task-source-trigger`). Shared by the regions mapped to this repo in the suite's `testSpecific.json`.

Each CI run creates a branch `ci/<buildId>-<region>`, creates an ACR task with a commit trigger on that branch, then commits a change to `trigger.txt` and checks the triggered run.

Do not delete this repo, edit `main`, or add GitHub Actions workflows. Owner: ACR Tasks team.

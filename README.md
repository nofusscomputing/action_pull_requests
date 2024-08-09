# No Fuss Computing - GH Action / Workflow for Pull Request Checks

To use this workflow add the following file to path `.github/workflows/pull-requests.yaml`

``` yaml

---

name: Pull Requests


on:
  pull_request: {}


jobs:

  pull-requests:
    name: Pull Request
    uses: nofusscomputing/action_pull_requests/.github/workflows/pull-requests.yaml@development

```

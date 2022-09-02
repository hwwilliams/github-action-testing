# Github Workflow Failure Dispatch

This repo contains a workflow which sends a dispatch request to a secondary workflow when workflow jobs have failed. This secondary workflow creates a GitHub issue with context about the failed workflow.

This process currently requires a secondary workflow to be triggered because you cannot retrieve workflow logs from a currently running workflow.

The issues are created in a separate repo at https://github.com/hwwilliams/github-workflow-failure-issue-creation

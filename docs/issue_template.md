# Goal

Create a simple issue template to gather user input for IssueOps workflows

# Setup

Create dedicated labels using GitHub CLI:

```bash
gh label create repo-request
✓ Label "repo-request" created in albyrubin/AHP-GitHubActions

gh label create issue-ops
✓ Label "issue-ops" created in albyrubin/AHP-GitHubActions
```

List existing labels:

```bash
gh label list

NAME              DESCRIPTION                                 COLOR
...
repo-request                                                  #5319E7
issue-ops                                                     #B60205
```

You can also provide a description or an explicit color string:

```bash
gh label create repo-request \
-c=#D541D0 \
-d="Request a new repository"
```

# AHP-GitHubActions

An honest path to mastering... GitHub Actions

## Chapter 5

[Create an issue template](docs/issue_template.md)

Create a new project and retrieve the project ID from the project URL. The ID will appear in the following format:

```
 https://github.com/users/{owner}/projects/{id}
```

Create a GitHub App with the right permissions.

[Generate a user access token for a GitHub App](https://docs.github.com/en/apps/creating-github-apps/authenticating-with-a-github-app/generating-a-user-access-token-for-a-github-app#generating-a-user-access-token-when-a-user-installs-your-app)

It's not possible to use an installation token to create user-owned repos.

To create repositories under a user account (not an organization) with a GitHub App, the GitHub App must authenticate on behalf of the user (not as an installation). This requires enabling OAuth user-to-server tokens for your GitHub App.

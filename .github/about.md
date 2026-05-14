<div align="center"><h1>About GitHub Special Repository and Files</h1></div>

- `<ORG>/<ORG>`  , `<ORG>/.github` , `<ORG>/<ORG>.github.io`
- `<USER>/<USER>`, `<USER>/.github`, `<USER>/<USER>.github.io`
- Priority `<REPO>/.github/` > `<REPO>/` > `<REPO>/docs/` > fallback to `<ORG>/.github` repo

- <https://docs.github.com/articles/creating-a-template-repository>
- <https://docs.github.com/articles/creating-a-repository-from-a-template>

- <https://docs.github.com/articles/about-issue-and-pull-request-templates>
- <https://docs.github.com/articles/helping-people-contribute-to-your-project>
- <https://docs.github.com/articles/setting-guidelines-for-repository-contributors>

- <https://docs.github.com/articles/about-codeowners>
- <https://docs.github.com/en/code-security/dependabot/dependabot-security-updates>

## Repo Healthy Files

```text
<REPO>/CNAME
<REPO>/LICENSE
<REPO>/README.md
<REPO>/docs/CHANGELOG.md

.github/CODEOWNERS
.github/CONTRIBUTING.md

.github/SECURITY.md
.github/dependabot.yml

.github/ISSUE_TEMPLATE/*.{md,yml}
.github/ISSUE_TEMPLATE/1-bug-report.md
.github/ISSUE_TEMPLATE/2-enhancement.md
.github/ISSUE-TEMPLATE.md

.github/PULL-REQUEST-TEMPLATE.md
.github/PULL_REQUEST_TEMPLATE/*.{md,yml}
.github/PULL_REQUEST_TEMPLATE/pull-request.md

.github/workflows/*.yml
.github/actions/*/{action.yml,*}

.github/SUPPORT.md
.github/FUNDING.yml
.github/GOVERNANCE.md
.github/MAINTAINERS.md
.github/CONTRIBUTORS.md
.github/CODE-OF-CONDUCT.md
```

# apache-skillset

A Claude Code plugin with skills that help contributors work on
[Apache Cloudberry (Incubating)](https://cloudberry.apache.org/) and understand
general Apache Software Foundation (ASF) processes.

> **Unofficial.** This is a community skill set. It is not endorsed by, affiliated with,
> or sponsored by the Apache Software Foundation. Apache, Apache Cloudberry, and the
> Apache feather logo are trademarks of the Apache Software Foundation. This repo
> does not reproduce ASF or project logos.

## Skills

| Skill | What it does |
|---|---|
| `cloudberry-mailing-list` | Search `dev@` and draft [DISCUSS]/[PROPOSAL]/[VOTE] emails |
| `cloudberry-pr-checklist` | Prepare and review a pull request against the repo's merge gates |
| `cloudberry-bug-report` | File or triage a bug report |
| `cloudberry-discuss` | Route ideas, proposals and questions to GitHub Discussions |
| `cloudberry-ai-disclosure` | AI-assistance disclosure rules for contributions |
| `cloudberry-license-check` | License/RAT checks and file headers |
| `cloudberry-committer-onboarding` | Committer and PPMC nomination, ICLA, apache.org email |
| `cloudberry-release-runbook` | Source release checklist and large-PR merge workaround |
| `asf-pmc-duties` | Generic ASF PMC/PPMC responsibilities reference |
| `extract-url-text` | Extract readable text from a URL (standard library only) |

Shared facts (mailing lists, website pages) live in
`references/cloudberry-facts.md`. They are a snapshot: always check the live
official sources before acting on them.

## Install

```text
/plugin marketplace add xinzweb/apache-skillset
/plugin install apache-skillset@apache-skillset
```

## Notes

- Skills draft and check; they never send email, cast votes, or merge for you.
- Content describes public processes and links to the official sources.

## License

Apache-2.0, see [LICENSE](LICENSE).

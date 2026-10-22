# Security notes - release drill
1. Dependency audit: record current Dependabot alert findings for this repo.
2. CI: the smoke check is expected to fail; recovery is re-running the failed jobs.
3. Merge policy: squash merges only, commit title prefixed with "drill:".
4. Reporting: quote findings verbatim, including empty results.

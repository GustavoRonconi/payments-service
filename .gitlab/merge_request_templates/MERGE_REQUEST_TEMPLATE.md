#### What
Please provide a short description of the purpose of this merge request.

#### Why
Explain why the proposed change is necessary.

`Story`: https://jira-olist.atlassian.net/browse/XXX-###

`Task`: https://jira-olist.atlassian.net/browse/XXX-###

---

#### Reminders
- Tests have been added and are passing ([`make lint`][Makefile]`&&`[`make test`][Makefile]). (If you've fixed a bug or added a new feature)
- The [`coding guidelines`] have been followed.
- All env vars which are being used have been added to:
  - [`local.env`]
  - [`.gitlab-ci.yml`]
  - Secret Manager (You can add them, even when the PR has not been merged yet)
- Dependencies are up to date.
- Review your own code before submitting the merge request.
- Confirm [CI build] is successfull before opening the merge request.


[CI build]: https://gitlab.olist.io/finance/csv-split-service/-/pipelines
[Makefile]: https://gitlab.olist.io/finance/csv-split-service/blob/master/Makefile
[`coding guidelines`]: https://jira-olist.atlassian.net/wiki/spaces/OP/pages/52461580/0008+-+Diretrizes+de+Estilo+de+C+digo+Python
[`local.env`]: https://gitlab.olist.io/finance/csv-split-service/blob/master/local.env

# [nickswope.dev]

## SCM & CI/CD Setup
There are two repositories for this project: the [GitLab source repository][gitlab-repo] and the [GitHub mirror][github-repo]. The GitHub mirror is used for the [Code Climate dashboard][cc-dashboard] integration.

All commits to the GitLab `master` branch will trigger an automatic deployment pipeline. Nick is the only one who can commit to `master`. All others must [open a MR][new-mr] in GitLab, which will then be reviewed, approved, and deployed.


[nickswope.dev]: https://nickswope.dev

[gitlab-repo]: https://gitlab.com/nickswope/nickswope.dev
[github-repo]: https://github.com/nickswope/nickswope.dev
[cc-dashboard]: https://codeclimate.com/github/nickswope/nickswope.dev
[new-mr]: https://gitlab.com/nickswope/nickswope.dev/merge_requests/new

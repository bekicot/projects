---
collaborating_projects:
  - gsoc-prep-tasks
desc: "List open tasks from various issue tracker. Can be filtered to only show
  newcomer friendly tasks."
difficulty: medium
initiatives:
  - GSoC
issues:
  - https://github.com/coala/projects/issues/480
  - https://github.com/coala/coala/issues/3615
  - https://github.com/coala/coala/issues/4080
markdown: git_task_list.md
mentors:
  - sims1253
  - yukiisbored
  - yashovardhanagrawal
name: "Git Task List"
requirements:
  - "The applicant should have at least one patch merged to any of the coala repositories."
  - "Familiarity with Git, GitHub API Gerrit API, Phabricator API, and GitLab API"
  - "Familiarity with EmberJS, Javascript, and GitHub Pages"
status: in_progress
tags:
  - community
  - web
---
The basic idea is an extended version of [GSOC Task List](http://summerofcode.github.io/gsoc-prep-tasks).

In [this project](), tasks means open issues and unmerged pull request coming
from GSOC open source projects.

[GSOC prep task](http://summerofcode.github.io/gsoc-prep-tasks) is an issue
finding tools that is (currently) integrated only with GitHub. It helps filter
out the GitHub issues and only show the issues that are newcomer friendly and
coming from limited GSoC organization. It limits the organization because
different organization use different kind of issue tracking such as Phabricator
and GitLab. While this tools currently only support Github.

**Git Task List** is conceptually the same as [GSOC prep task](http://summerofcode.github.io/gsoc-prep-tasks). Git Task List target a broader task type which include pull
request review as the task. The goal of this project is to help developer to
keep contributing to open source project by providing a sets of tasks that has
been filtered using predefined keywords.

In coala, this project will help sharing the tasks of reviewing a pull request
on a project. It will help fix the problem where developer spend too much time
finding PR that haven’t been reviewed. This projects aims to getting more
developer doing reviews works and sharing reviews workload, by providing an easy
way to find issues that has not been reviewed. It also help project’s maintainer
/ developer do review more efficient.

This will also help engage the developer to keep contributing to a project where
they can’t find any issue that they can fix or keep the newcomer issue for new
comer as learning path and developer with more experience can contribute by
reviewing newcomer’s work PR.

The goal of this projects is a static-site javascript web page where the user
can find Pull Request that haven’t been reviewed. User can select projects in
Open Source hosting services like GitHub or GitLab. They also have the ability
to select prefered programming language, tags, owner of the pull requests, and
other metadata that is provided by the web services (GitHub/GitLab).

Because the concept of this project, is the same as [GSOC prep task](http://summerofcode.github.io/gsoc-prep-tasks), [it](http://github.com/GSOC prep task/gsoc-prep-tasks) can be
used as the starting point of this project.

#### Milestone

##### Phase 1
- Add support to all GSOC organizations that are using GitHub as an issue
  tracker.
- Add pull request support.
  - Search unreviewed PR.
  - Search unreviewed PR on a specific project.
  - Special page to search pull request for review.
- Allow a user to add their token to increase the search limits.

##### Phase 2
- Add GitLab support.
  - Search by Projects.
  - Search open issues.
  - Search issue by tag.
  - Search merge request.
- Add Phabricator support.

##### Phase 3
- Polish UI and UX.

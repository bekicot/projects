---
collaborating_projects:
  - gsoc-prep-tasks
desc: "List pull request/merge request (in GitLab) that have no reviewer yet. Provide an easy way for newcomer / developer to do contribution to a project by giving review to other people pull requests."
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
The basic idea is an extended version of [GSOC Task List](http://summerofcode.github.io/gsoc-prep-tasks)
which was initialy intended for GSOC Applicants who don't have or only have a
litle experience in open-source. Hence, [that](http://github.com/summerofcode/gsoc-prep-tasks)
project will be the starting point of this project.

This project will help sharing the tasks of reviewing a pull request on a
project. It will help fix the problem where developer spend too much time
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

#### Milestone

##### Phase 1
- Add GitLab support
  - Search Projects
  - Search open issues
  - Search issue by tag
- Add complete list of GSOC organizations that is using GitHub or GitLab
  - Find GitLab / GitHub repository pages
  - Add simplified ui to list/search projects

##### Phase 2
- PR review list / queue
- Create a new search page for PR
- Search unreviewed PR
- Search unreviewed PR on a specific projects

##### Phase 3
- Add Gerrit support
- Add Phabricator support
- Polish UI and UX.

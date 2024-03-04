# Solid Team Contributing Guide

[The Solid Team](team.md) is headed by Sir Tim Berners-Lee and provides an organisational umbrella to facilitate a
strong open source community in support of Solid. This repository contains work of the Solid Team to meet the needs of
the [Solid Project](https://solidproject.org/).

The Solid Team is a group of volunteers tasked with representing the Solid Project in an official capacity. It engages
in activities that foster the spread and adoption of the Solid protocol.

## Code of Conduct

The Solid Team follows
the [Solid Community Code of Conduct](https://github.com/solid/process/blob/main/code-of-conduct.md).

## How to join the team

Anyone can become a member of the Solid Team. Check out the [team.md](team.md) for more information about how to join
the team.

## How the team works

Solid Team consists of volunteers, lead by Sir Tim Berners-Lee. The group operates mostly as
a [do-ocracy](https://communitywiki.org/wiki/DoOcracy), where tasks are assigned by members taking on responsibility
themselves. Members are required to adhere to [teams' decisions](#decisions).

### Tasks

The Solid Team engages in a number of [tasks](tasks). Tasks may be added or removed from the team's scope by majority
vote at a Solid Team meeting. 

### Task Force Membership 

Team members may be added or removed from this task force by a
majority vote at a Solid Team meeting. There must be a lead for this task. While other members may assist in the task,
it is the responsibility of the leader to follow up on the task and report updates to the team.

### Meetings

The Solid Team holds meetings at <https://meet.jit.si/solid-team> on every second Wednesday of the month at 15:00 UTC —
subscribe to [vCalendar](https://raw.githubusercontent.com/solid/team/main/meetings/calendar.ics). Meetings are
transcribed and [published](meetings). Additional team meetings may be created, in which case Solid Team members will be
notified via calendar invitation and in the Solid Team chat.

### Issues

[Issues](https://docs.github.com/en/github/managing-your-work-on-github/about-issues)
are used to track tasks that contributors can help with. Issues are mostly grouped
into [task forces](README.md#ongoing-task-forces), so you should join one of them if you want to collaborate with
others.

### Pull requests

A [pull
request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
is a way to suggest changes in our repository.

### Decisions

The team's decision process is inspired by
the [chapter on decisions in W3C Process Document](https://www.w3.org/Consortium/Process/#decisions).

The team attempts to resolve issues through dialog. Individuals who disagree strongly with a decision should register
any formal objections with the leader.

Any substantive issues that can't be resolved through reaching consensus through technical discussions and compromise
must go through a vote, and the results must be public. Decisions may be made during [meetings](./meetings)
(face-to-face or distributed) as well as through persistent text-based discussions.

Each member has one vote. The leader has a double vote if there's a tie. A decision requires the majority (i.e. at least
50%) of the votes amongst the attendees, and at least 50% of all members must attend a decision for it to be valid. (
E.g. if there are 12 members overall, at least 6 must attend a meeting for it to be possible to make decisions in that
meeting. Of these, at least 4 of the votes are required for a decision.)

The leader can require decisions to need a supermajority, which means that a minimum of 50% of eligible voters must vote
for a decision to be made. (E.g. if there are 12 members overall, at least 6 of their votes are required for a decision
to be made.)

Individuals might abstain. Abstention is either an explicit expression of no opinion or silence by an individual in the
set.

### Communication

The opinions of team members may carry particular weight, whether they are expressed within our community or elsewhere.
As a team member:

* It is assumed you are speaking as an individual unless you state otherwise.
* If you want to express the opinion of your organisation or a group you are affiliated with, make it clear before you
  state their view.
* Do not use phrases like "on behalf of the team" or "the team thinks that" unless the group has asked you to do so.
* When communicating team decisions, provide references to what was decided and what was not decided.

### Transparency

Team members represent the overall Solid efforts, and so should strive to make their efforts transparent. This is mostly
done by communicating substantial efforts and changes through [issues](#issues) and [pull requests](#pull-requests). In
cases where full transparency is counterproductive (e.g. ongoing efforts include tools where public access is not
possible or costly), efforts should be made to mitigate these constraints as efficient as possible.

## Make changes

### Make changes locally

1. Install Git
2. Fork the repository.
3. Create a working branch and start with your changes!

## Commit your update

Commit the changes once you are happy with them. See [Atom's contributing
guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages)
to know how to use emoji for commit messages.

Once your changes are ready, don't forget to [self-review](#self-review) to
speed up the review process:zap:.

### Self-review

You are strongly encouraged to review your own PR first.

* [ ] Compare your PR's source changes to staging to confirm that the
  output matches the source and that everything is rendering as expected. The
  W3C service to [creating diff between HTML pages](https://services.w3.org/htmldiff)
  can also be used.
* [ ] Review the content for technical accuracy.
* [ ] Review the content to use [inclusive
  language](https://github.com/github/docs/blob/main/contributing/content-style-guide.md#inclusive-language).
  Celebrate people/names from under represented ethnic/cultural backgrounds in
  examples, e.g., [unique forenames in
  Earth](https://forebears.io/earth/forenames), [example person
  names](https://developers.google.com/style/examples#example-person-names).

## Creating a pull request

When you're finished with the changes to documents that are maintained in this
repository, create a PR.

* Include atomic commits, small PRs: "one concern, one PR".
* In the PR comment, provide as much context and evidence to help reviewers
  evaluate the PR. Identify, classify, describes the changes as per W3C
  Process [Correction
  Classes](https://www.w3.org/Consortium/Process/#correction-classes).
* Don't forget to [link PR to
  issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
  if you are solving one.
* We can ask for changes to be made before a PR can be merged, either using
  [suggested
  changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request)
  or PR comments. You can apply suggested changes directly through the UI. You
  can make any other changes in your fork, then commit them to your branch.
* As you update your PR and apply changes, mark each conversation as
  [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
* If you run into any merge issues, review this [git
  tutorial](https://lab.github.com/githubtraining/managing-merge-conflicts) to
  help you resolve merge conflicts and other issues.
* You can attribute a commit to more than one author by adding one or more
  `Co-authored-by: NAME <NAME@EXAMPLE.COM>` per line to commit's message
  (after two empty lines). See [github
  tutorial](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors).
* To help maintain a clean Git history, consider using [squash
  merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/about-merge-methods-on-github#squashing-your-merge-commits)
  for PRs, especially when incorporating reviews and code additions.

### Your PR is merged!

Congratulations :tada: The Solid Team and the community thanks you :sparkles: 
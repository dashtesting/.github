## Dash Testing Organization
> Organization for testing features, used by Dash Incubator

The main purpose of this organization right now is to test features in preparation for Dash Incubator's migration from Trello to GitHub.

### Migration Notes

#### General

- Some preliminary testing was done in the [test-repo of our main repo](https://github.com/dashincubator/test-repo).
  - I might transfer that repo to this org.
- Migration scripts:
  - Current: https://github.com/dashtesting/trello-github-etl.
  - Previous: https://github.com/cloudwheels/dashincubator-data-migration.
- Transferring issues:
  - you can transfer an issue to another repo in the same repo.
  - you can transfer a repo to another org.
  - you can not transfer an issue directly to a repo in a different org.
  - if you transfer an issue that is tracking other issues, the tracked issues don't move.
- Projects (beta):
  - A project can include issues from multiple repos within an org
  - A project can not include issues from different orgs. 

#### Ideas for Next Migration

- Discuss with AJ
  - pros and cons of having a repo for each bounty
  - what is the plan to add issues to projects (beta)
  - should we do comments yet
- Revise script to:
  - exclude (filter out) archieved and completed bounties/cards
  - add labels to issues
  - push issues to a new repo
- Notes on making new repo for each bounty (Trello card):
  - Tasks would be the only issues (manage issues with projects instead of nested/tracking issues in one repo).
  - we could make tracking issues for lists (spec, prod, etc) but not sure we care to do that (what value is tracking tasks by that type adding?).


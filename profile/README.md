## Dash Testing Organization
> Organization for testing features, used by Dash Incubator

The main purpose of this organization right now is to test features in preparation for Dash Incubator's migration from Trello to GitHub.

### Migration Notes

#### General

- Some preliminary testing was done in the [test-repo of our main repo](https://github.com/dashincubator/test-repo).
- As part of testing, I might try transferring that repo to this org (I wonder if there will be a name conflict with two "test-repo"s
- Current migration script: https://github.com/dashtesting/trello-github-etl
- Previous migration script: https://github.com/cloudwheels/dashincubator-data-migration
- It looks like you can transfer an issue to another repo in the same repo, and you can transfer a repo to another org, but you can't transfer an issue directly from one repo to another repo in a different org.
- A project can track issues in multiple repos with an org, but can't track repos across different orgs. 

#### Ideas for Next Migration

- Exclude archieved and completed bounties/cards
- Possibly create a new repo for each bounty
  - Tasks would then be the only issues (instead of nested/tracking issues in one repo)
  - Could make tracking issues for lists (concept, spec, prod, QA) but not sure we care to do that (not much value in tracking tasks by that type.
- Give task issues GitHub "labels" 
- Add labels to issues
  - Add some more detailed ideas here.

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

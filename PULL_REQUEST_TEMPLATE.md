## Problem Statement
_To create a PR template with standard format for providing the problem statement, solution and checklist_

## Solution
_Created a stand format for providing the problem statement, solution, references and checklist_

#### Open Questions/Comments and Pre-Merge TODOs
- How will we record checklist responses in case of multiple assignees and reviewers?
- For now we assume that there will be same checklist for both assginees and reviewers.
- TODO: Verify in RS component.

#### References
- [How to Pull Request](https://github.com/flexyford/pull-request) Github Repo with Learning focused Pull Request Template.

#### Developer Checklist
- [ ] I have verified sonar violations on local box to ensure PR builder does not fails.
- [ ] I have written Junit test cases to cover atleast 60% of new code.
- [ ] I have requested review from an SME if my code impacts other functionality/component.
- [ ] I have followed the commit convention: <<defect/userstory>>:<<comment>>.
- [ ] I have added the reviewers and assignee for merging the PR.
- [ ] I have added the relevant documentation in Wiki and updated in UserStory.

#### Assignee/Reviewer Checklist
- [ ] I have reviewed whether all the functional requirements are met as per acceptance criteria.
- [ ] I have reviewed the Coding standards.
- [ ] I have reviewed whether the code is stable and does cause any regression.
- [ ] I have reviewed whether the SME has approved the PR in case it affects other component.
- [ ] I have reviewed the relevant documentation if any.

## Problem Statement
_To create a PR template with standard format for providing the problem statement, solution and checklist_

## Solution
_Created a standard format for providing the problem statement, solution, references and checklist_

#### Open Questions/Comments and Pre-Merge TODOs
- How will we record checklist responses in case of multiple assignees and reviewers?
- For now we assume that there will be same checklist for both assignees and reviewers.
- TODO: Verify in RS component.

#### References
- [How to Pull Request](https://github.com/flexyford/pull-request) Github Repo with Learning focused Pull Request Template.

#### Developer Checklist
- [ ] I have verified sonar violations on local box to ensure PR builder does not fails, if applicable.
- [ ] I have verified all flows related to the problem statement on local box.
- [ ] I have verified whether there are no exceptions/errors/excessive logging during local box verification.
- [ ] I have written Junit test cases to cover atleast 60% of new code, if applicable.
- [ ] I have requested review from an SME if my code impacts other functionality/component.
    - [ ] Is SME approval mandatory?
- [ ] I have added the required reviewers and assignee for merging the PR.
- [ ] I have added the task for relevant documentation (if any) in Rally.
- [ ] I have added a placeholder step in the release checklist (if required).

#### Assignee/Reviewer Checklist
- [ ] I have reviewed whether the specified problem statement is solved with this PR.
- [ ] I have reviewed the coding standards and design.
- [ ] I have reviewed whether the SME has approved the PR (if required) in case it affects any other component.
- [ ] I have reviewed the task for relevant documentation (if any).
- [ ] I have reviewed the placeholder step for release checklist step (if required).

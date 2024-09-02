# Events (Workflow Triggers)

## Repository related
- **push** : Pushing a commit
- **pull_request** : Pull Request action (opened, closed)
- **create** : A branch or a tag was created
- **fork** : A repository was forked
- **issues** : An issue was opened, deleted
- **issue_comment** : Issue or pull request comment action
- **watch** : Repository was starred
- **discussion** : Discussion was created or deleted ...
  
then there are many more!

Apart from above there are some other workflows:
- **workflow_dispatch** : Manually trigger a workflow
- **repository_dispatch** : REST API triggers workflow
- **schedule** : Workflow is scheduled
- **workflow_call** : Can be called by other workflows
# Release-Notes

Release Notes displayed on Serto Docs
When there is a New Release on any product 

- Create a new branch from `branch: main` 
- Copy changes in `drafts-notes` folder to `notes` folder 
- Manually edit the notes for better reading (remove Github links etc) 
- Create a PR to `branch: production`
- A minor release tag will be created to store history of Release Notes so its easy to revert notes as needed
- Rebase `branch: main` as needed

## When there is a release on all products
Add the label `release:major`to the PR so a major version is created

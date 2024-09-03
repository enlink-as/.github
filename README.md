# Enlink guidelines
This will contain some general guidelines we are to use for software development. 

## Git workflow

All repositories should have two branches - one for production ('main') and one for development/testing ('development').
- Main repo represents _production ready code_. Releases to production are made from this branch. Merge into this branch when code is tested/reviewed.
- The development branch is where ongoing development is happening. Here we can test features before these are merged into main.

When a developer is working on a specific feature this is to be done in a feature branch - this shall be created from the 'development' branch.
The branch should be named as **feature/\<feature-name>**. When the feature is implemented, create a PR to merge into _development_.




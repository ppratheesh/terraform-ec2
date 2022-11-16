# GitHub Actions workflow for automate releases


This workflow is used for Automatically creating [SemVer](https://semver.org/) compliant releases based on
PR labels. 

The PR should be tagged with a "*semver-compliant*" label (*patch*, *minor* or *major*),
then this workflow will create a tag and a GitHub release when it is merged main branch.

Also the workflow will consider the most recent SemVer tag as base tag for the increment of release version





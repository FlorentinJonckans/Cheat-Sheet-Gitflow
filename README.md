# Cheat-Sheet-Gitflow

`git flow init`:
Initialize empty Git repository and create a feature, realease, hotfix, support and version branch.

`git flow feature start featureName`:
Start the development of a new feature.

`git flow feature publish featureName`:
Publish a feature to the remote server.

`git flow feature finish featureName`:
Finish the development of the feature.

`git flow feature pull origin featureName`:
Get a feature published by another user.

`git flow feature track featureName`:
Track a feature on origin.

`git flow release start releaseName`:
Create a release branch created from the 'develop' branch.

`git flow release publish releaseName`:
Publish the release branch after creating it to allow release commits by other developers.

`git flow release finish releaseName`:
Finish the release which means, merges the release branch back into 'master', Tags the release with its name, Back-merges the release into 'develop' and Removes the release branch.

`git flow hotfix start versionName`:
Create a hotfix branch.

`git flow hotfix finish versionName`:
Finish a hotfix branch which means, the hotfix branch merge back into develop and master.

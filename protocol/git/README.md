# Git Protocol

Guidelines for Git version control.

## Common Courtesy

* Understand how Git works. Knowing is half the battle. And time spent reversing poor decisions is not fun for anyone.
	* [Git from the Bottom Up](https://jwiegley.github.io/git-from-the-bottom-up/)
	* [Pro Git](https://git-scm.com/book/en/v2)
* Write good commit messages. This is not just what changed but why did you make the change?
* Try to use lowercase letters and avoid using numbers for repository names.
* Use .gitignore files to prevent accidental commits.
* Do not commit anything that will be regenerated.
* Do not commit anything specific to your development environment.
* Do not commit large binaries.

## Common Sense
* Do not `reset --hard` without committing first.
* Rebase frequently to incorporate upstream changes.
* Delete old local branches.

## Workflow

We use the [Git-flow](http://nvie.com/posts/a-successful-git-branching-model/) branching model. Full details and descriptions can be found on the official page. 

In summary:

Two main protected branches in every project:

* `master` - Reflects the current _production ready_ state of the project.
* `develop` - Reflects the latest features ready for the next release. 

Additionally, there are three other branch types:

* Feature branches - Used to develop _any_ new features for upcoming releases.
* Release branches - Used to support preparation for release. These branch from `develop` for testing prior to release.
* Hotfix branches - Unplanned release fixes. These will branch off of `master` to perform the fix and merged back into `master` and `develop`.

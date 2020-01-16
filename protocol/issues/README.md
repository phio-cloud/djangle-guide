# Issue Management

Guidelines for input and handling of bugs and feature requests. Issues are currently reported and progressed through Jira.

## User Stories

Feature requests can many times be too specific by describing specifics rather than the larger desired goal. In order to get to the heart of what is desired by a feature request, it is many times useful to convert them into _User Stories_. A _User Story_ is the desired outcome written from the perspective of the user of the product. If you don't know _who_ wants the feature, _why_ it would be used, or for _what_ goal then the feature is likely not worth pursuing.

The most simple story is written with the following template: `As a <user>, I want to <action> so that I can <goal>.`

* The user tells you who wants the feature such as a salesperson or a provisioner.
* The action tells you what they need to be able to do, the penultimate goal.
* The goal tells you why they want to perform the action, the ultimate goal.

It is surprisingly common for a feature request for an action to not be what is truly desired once the ultimate goal has been understood.

Lastly, a good story will have criteria that need to be met in order to be resolved. Ideally, these can be converted into tests to confirm that the story has been adequately handled.

### Best Practices

* Try to avoid user classifications of "User" or "Developer". 
* Add acceptance criteria or a condition of satisfaction.

## Bug Reporting

When a bug is reported it is ok to simply report the bug. However, while the bug is fresh it is important to put in as much information that is available.

### Best Practices

* Provide a minimal reproducible example.
* Describe any fixes that have already been attempted.
* Include information about the environment - OS, Browser, etc.

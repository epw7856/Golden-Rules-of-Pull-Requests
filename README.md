# The Golden Rules of Pull Request Workflow

**As a Pull Request Author...**

* Ensure that code changes are self-contained and relevant. Do not address several unrelated bugs or features within the same Pull Request.
* Write meaningful commit messages, titles, and descriptions.
* Include the Jira bug, story, or task number in the Pull Request title and add a hyperlink in the description.
* Include links to design documents or additional relevant documentation in the Pull Request description.
* If applicable, use a multi-part label to indicate a series of related Pull Requests.
* Limit the rate at which Pull Request are opened based on the team's ability to complete reviews.
* Ensure that automated builds and unit tests (CI) pass prior to opening the Pull Request.
* Request reviews from teammates only when the Pull Request is finalized. Do not make additional commits unless they are intended to address comments.


**As a Pull Request Reviewer...**

* Perform reviews as soon as possible. Prioritizing review tasks maintains team velocity and keeps the project's development codebase up to date.
* Approve the Pull Request if and only if the state of the codebase is improved by the associated changes.
* Request the creation of a new Jira ticket or successive Pull Request over a rejection whenever possible.
* Provide suggestions for improvements instead of a rejection.
* Be cognizant of the work in progress (WIP) limit of the team. Prioritize the review of open Pull Requests before creating new ones.

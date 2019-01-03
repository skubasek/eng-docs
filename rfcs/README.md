# Why RFCs?

Most changes, including bug fixes and documentation improvements can be implemented and reviewed 
via the normal pull request workflow.

Some changes though are "substantial", and these should be put through a bit of a design process 
and produce a consensus among the developer and the core (primary/secondary) team.

## When you need to follow this process
You need to follow this process if you intend to make "substantial" changes 
(to any project that has primary/secondary owners). What constitutes a "substantial" change? Up to 
 discretion of the core team, and also your own judgement. In general, any substantial design/architecture
 changes or refactoring should include one.
 
## What the process is
In short, to get a major feature added, you must first get the RFC merged into the RFC repo as a 
markdown file. At that point the RFC is 'active' and may be implemented.

* Copy 0000-rfc-template.md to 000x-my-feature.md (where 'my-feature' is descriptive)
* Fill in the RFC.
* Submit a pull request. The pull request is the time to get review of the design.
* Integrate feedback. 
* Somebody on the core team approves the PR or works with the author to have the proposal
amended. Once approved, author(s) may implement it.


## Too formal?
The process is intended to be as lightweight as possible, with the intention of helping to maintain
good project design/architecture cohesion, and at the same time, providing reasoning for the bigger
changes. 

# Directus RFCs

**The "RFC" (request for comments) process is intended to provide a consistent and controlled process for new features to enter the framework.** Many changes, including bug fixes and documentation improvements, can be implemented and reviewed via the normal GitHub pull request workflow. However, _substantial_ changes to Directus should follow the RFC process, as they may require additional research, planning, design, and community feedback before starting work on a PR.

What constitutes a "substantial" change is evolving based on community norms, but may include the following:

- A new feature that creates new API surface area
- Changing the semantics or behavior of an existing API
- The removal of features that are already shipped as part of the release channel
- The introduction of new features that warrant a review from the core team or community feedback

In the end, the goal of this process is to ensure the stability and maintainability of the Directus platform, especially through the lens of our 80/20 rule. If you submit a pull request to implement a new feature without going through the RFC process, it may be closed with a polite request to submit an RFC first.

[Pending RFC List](https://github.com/directus/rfcs/pulls)

## Process

1. Fork this repository.
2. Work on your proposal in a Markdown file based on this repo's `0000-template.md` file.
   - Use a descriptive name for your proposal, eg: `rfcs/0000-my-feature.md` (don't assign a number yet).
   - Put care into the details. RFCs that do not present convincing motivation, demonstrate understanding of the impact of the design, or are disingenuous about the drawbacks or alternatives tend to be poorly received.
3. Submit a pull request, referencing any relevant GitHub Discussion in the thread.
   - Creating and referencing a GitHub Discussion on the `directus/directus` repository is an excellent way to gather community feedback and awareness. This helps in building a consensus that helps build RFC momentum.
   - You will also want to integrate additional feedback into your proposal based on any comments.
4. Eventually, the core team will decide whether the RFC is a candidate for inclusion in Directus.
   - **Modifications:** An RFC can be modified based upon feedback from the core team and community.
   - **Rejected:** An RFC may be rejected after public discussion has settled and comments have been made summarizing the rationale for rejection. A member of the core team should then close the RFC's associated pull request.
   - **Accepted:** An RFC may be accepted at the close of its final comment period. A core team member will merge the RFC's associated pull request, at which point the RFC will become 'active'.

## Active RFCs

Once an RFC becomes active, authors may implement it and submit the feature as a pull request to the Directus repository. An RFC being 'active' does not necessarily mean the feature will be merged; it does mean that the core team has agreed to it in principle and are open to merging it. Furthermore, the fact that a given RFC has been accepted and is 'active' implies nothing about what priority is assigned to its implementation, nor whether anybody is currently working on it.

## Implementing an RFC

The author of an RFC is not obligated to implement it. Of course, the RFC author (like any other developer) is welcome to post an implementation for review after the RFC has been accepted. An active RFC should have the link to the implementation PR listed if there is one. Feedback to the actual implementation should be conducted in the implementation PR instead of the original RFC PR.

## Reviewing RFCs

Members of the core team will attempt to review open RFC pull requests on a regular basis.

_[Inspired by the Vuejs RFC process.](https://github.com/vuejs/rfcs)_

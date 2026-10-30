![Banner](banner.png)

# Contributing-Template

A ready-to-copy contributing guide (`CONTRIBUTING.md`), generated with https://generator.contributing.md, for use as the contributing file of another project.

## How to use it

Copy `CONTRIBUTING.md` into your project, then fill in the template slots before publishing it. The guide covers a code of conduct, asking questions, reporting bugs, suggesting enhancements, first code contributions, documentation, commit-message styleguides, and joining the project team, with a table of contents linking to each section.

## Placeholders fixed in this pass

- The code-of-conduct section linked to `blob/master/CODE_OF_CONDUCT.md`, a file this repo does not contain, and two contact spots contained an empty `<>` address. The code-of-conduct reference now states plainly that no such file is included here and one must be added before adopting the guide, and both empty addresses now read "the project maintainer" instead of inventing an address.
- Three documentation links pointed nowhere (`[Documentation]()` and `[documentation]()` with an empty target). They now link to `README.md` in this repo; an adopting project should point them at its own documentation.

## Slots still to fill when you adopt it

Four `TODO` comment blocks are left intentionally blank in the template: first code contribution setup, improving the documentation, commit-message styleguide details, and joining the project team. Those are fill-in points for the adopting project, not oversights, and they are left as TODOs rather than filled with invented project details. The table of contents anchors were checked against the headings and all resolve to sections that exist in the file.

One more inherited quirk to check when adopting: the question, bug, and enhancement sections link to root-relative `/issues` and `/issues/new` paths, as the generator wrote them. On GitHub those resolve against the github.com root (the signed-in reader's own issue pages), not against the adopting repository, so replace them with the project's own issue URLs. They are documented here rather than rewritten, because the right target is the adopting project's address, which this template cannot know. A doubled word left in the code-of-conduct sentence by an earlier placeholder fix ("governed by the the project code of conduct") was also corrected in the deep pass.

Files: `CONTRIBUTING.md`, `LICENSE`, `logo.png`, `banner.png`.

# Green Mile RFCs

Many changes, including bug fixes and documentation improvements can be 
implemented and reviewed via the normal GitHub pull request workflow.

Some changes though are "substantial", and we ask that these be put 
through a bit of a design process and produce a consensus among the 
Bullstack team.

The "RFC" (request for comments) process is intended to provide a 
consistent and controlled path for new features to enter the project.

## When to follow this process

You should consider using this process if you intend to make "substantial"
changes to Green Mile or its documentation. Some examples that would benefit
from an RFC are:

  - A new feature that creates new API surface area, and would
     require a feature flag if introduced.
  - The removal of features that already shipped as part of the release
     channel.
  - The introduction of new idiomatic usage or conventions, even if they
     do not include code changes to Green Mile itself.

Some changes do not require an RFC:

  - Rephrasing, reorganizing or refactoring
  - Addition or removal of warnings
  - Additions that strictly improve objective, numerical quality
  criteria (speedup, better browser support)

## Inspiration

- [Rust RFC Process](https://github.com/rust-lang/rfcs/)
- [React RFC Process](https://github.com/reactjs/rfcs/)

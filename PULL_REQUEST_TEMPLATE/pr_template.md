# Checklist for Pull Requests

- [ ] I have ensured my code follows the [style guidelines](https://github.com/jasp-stats/jasp-desktop/blob/stable/Docs/development/r-style-guide.md).
<!---
-->
- [ ] I have added a linked issue #(issue number) in the pull request 
<!---
Example: 'Fixes #1234', or 'Fixes jasp-stats/INTERNAL-jasp#1234'.
See the documentation at https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword
-->
- [ ] I have added changes to `NEWS.md` under the appropriate heading
<!---
  - 'Major changes' - if the pull request changed the default functionality of an analysis changes or adds a large new feature.
    - Examples of major changes: 
      - Addition of GORICA to jaspANOVA (large feature). 
      - Addition of GLM to jaspRegression (new analysis).
  - 'Minor changes' - if the pull request changed the default functionality of an analysis changes or adds a large new feature.
    - Examples of minor changes:
      - Adding a dropdown with new options to specify histogram bins jaspDescriptives.
      - Adding a new plot to jaspRegression.
  - 'Bugfixes'
    - Example
      - The variance check in the ANOVA was too strict.
-->
- [ ] I have added unit tests or an explanation why no tests are needed.
<!---
Example: 'this bug is only reproducible in Jasp because it has to do with the state.'
-->

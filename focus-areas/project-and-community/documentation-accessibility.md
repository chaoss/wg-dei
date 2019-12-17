# Project Places: Documentation Accessibility

Question: What is the accessibility of documentation?

## Description

Accessibility of documentation has the same issues as other online publishing accessibility but it is critical due to the role documentation plays in open source projects. Documentation is codified knowledge across various dimensions of an open source project.

Documentation can be on the processes and practices of the community, thus empowering participants to contribute with certainty for how and why things are happening. It may also be on the artifacts produced by the community and as such empower participants to know where to contribute and what kind of contributions further the goals of the community.

## Objectives

- **Accessibility Screen Reader** — Documentation is accessible according to x standard for screen readers (which tool to use?)
- **Awareness** — Documentation is easy to find & discoverable
- **Clarity** — Documentation is easy to follow and structured intuitively
- **Non-Technical Accessibility** — Documentation limits use of unnecessary technical jargon
- **Inclusion** — Documentation does not include non-inclusive language (this could be ‘brogrammer’ language or exclusionary/derogatory language.
- **Inclusion** — The documentation uses global language
- **Accessibility** — There is an easy way to update documentation
- **Neurodivergent** — Making documentation accessible to various cognitive approaches [(3)](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf)

## Implementation

- A person goes through the documentation and checks off the criteria listed below.
- Gather feedback from new community members using below survey questions.
- Include a quick survey
  - See “Quick bottom-page survey” in Data Collection Strategies

### Data Collection Strategies

- Is the documentation screen-reader friendly?
  - Use a tool that evaluates screen-reader friendliness [(4)](https://soap.stanford.edu/tips/screen-reader-testing)[(6)](https://www.w3.org/WAI/ER/tools/).
- Interview with newcomers to find out how documentation helped (a) understand the contribution process and/or (b) help complete the task
- Survey project members
  - Matrix item: When you need to locate information about this project’s processes, policies, or guidelines, which of the following describes your experience? [(5)](https://communitysurvey.limequery.org/454363)
    - Matrix rows can be: Mailing list communication; IRC communication; Performing code reviews; Process of getting code accepted; Code of conduct; Onboarding newcomers; Licensing, trademark; Add new committers/PMC members; Project releases; Voting process
    - Matrix columns can be: Always easy to find; Easy to find; A little difficult to find; Quite difficult to find
  - Multiple choice: Did you face any challenges related to the accessibility of documentation when you started to participate in the project (e.g., language barriers, discoverability of documentation, structure of documentation, etc)? [(5)](https://communitysurvey.limequery.org/454363)
    - Answer options: No challenges; A Few challenges; Several challenges; Many challenges
    - Open-ended follow-up question if answer is not “no challenges”: Describe an example for when you experienced the challenge, how it affected you, and how, if at all, you overcame the challenge.
  - Open-ended question: What suggestions do you have for improving the ASF policies, processes, or guidelines available to new contributors? [(5)](https://communitysurvey.limequery.org/454363)
- Readability/Scannability Documentation uses:
  - Headings
  - Blocks of text/code
  - Bullets v paragraphs
  - Anchors
- Searchability
  - How easily can this documentation be found by the user?
- Quick micro-survey for users within documentation (bottom-page):
  - T/F question: Was this documentation page accessible to you?

## Resources

1. The Core Infrastructure Initiative [Best Practices Badge](https://bestpractices.coreinfrastructure.org/en) has criteria pertaining to documentation:
   - [`documentation_basics`](https://github.com/coreinfrastructure/best-practices-badge/blob/master/doc/criteria.md#documentation_basics)
   - [`documentation_interface`](https://github.com/coreinfrastructure/best-practices-badge/blob/master/doc/criteria.md#documentation_interface)
2. [W3C Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
3. [Breaking Down Barriers to Kubernetes Contribution for Neurodivergent Individuals](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf)
4. [Stanford: Screen Reader Testing](https://soap.stanford.edu/tips/screen-reader-testing)
5. [Apache: 2020 ASF Community Survey](https://communitysurvey.limequery.org/454363)
6. [W3C Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/)

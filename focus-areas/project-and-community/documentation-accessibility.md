# Documentation Accessibility

**Question:** How does the documentation accommodate different users?

## Overview
The **Documentation Accessibility** metric evaluates how well project documentation meets the needs of diverse users, including those with visual impairments, cognitive differences, or sensory processing needs. This metric specifically focuses on features that enhance accessibility, such as screen-reader compatibility, alternative text for images, and clear structuring for easier navigation. Tracking this metric helps ensure that documentation is inclusive, making the project more welcoming and usable for a wide audience, and improving community health by supporting contributors with diverse abilities. Objectives help measure whether your documentation is accessible to a broad audience without disproportionately creating or perpetuating artificial debts on certain segments of its intended audiences. These include: 

- Screen Reader Accessibility: Documentation is accessible according to a standard for screen readers.
- Learning Flexibility** — Documentation is accessible to people with various cognitive approaches, sensory differences, and neurodiversity. [(1)](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf).
- Blind or Visually Impaired Support: Documentation is accessible for people who primarily read text. Charts and images are examples of non-accessible types of documentation.

## Want to Know More?

<span markdown="1"><details>
<summary>Click to read more about this metric.</summary>

### Data Collection Strategies

* Use a tool that evaluates screen-reader friendliness. [(5)](https://www.w3.org/WAI/ER/tools/) [(6)](https://a11yproject.com/#Quick-tests) to determine if the documentation is screen-reader friendly?
* Interview newcomers to figure out how documentation helped with, (a) understanding the contribution process, and/or, (b) helping to complete tasks in a project.
Sample interview questions:
  * What is your experience with using the documentation to understand the contribution process?
  * What is your experience with consulting the documentation when you have a question about doing work on the project?
  * Were you comfortable with the technical terms present in the documentation?
* **Survey** project members
  * Matrix item: When you need to locate information about this project’s processes, policies, or guidelines, which of the following describes your experience? [(2)](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
    * Matrix rows can be:
      * Mailing list communication
      * Chat communication
      * Performing code reviews
      * Process of getting code accepted
      * Code of conduct
      * Onboarding newcomers
      * Licensing
      * Trademark
      * Add new Committers/Maintainers
      * Project releases
      * Voting process
      * Installation procedures
      * Feature development
      * API integration
      * Test suites
      * Architecture overview
      * User guide

    * Matrix columns can be:
      * Always easy to find
        * Easy to find
        * Difficult to find
        * Very difficult to find
  * Multiple choice: Did you face any challenges related to the accessibility of documentation when you started to participate in the project (e.g., language barriers, discoverability of documentation, the structure of documentation)? [(2)](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
    * Answer options:
      * No challenges
      * A Few challenges
      * Several challenges
      * Many challenges
    * Open-ended follow-up question if the answer is not “No challenges”: Describe an example of when you experienced the challenge, how the challenge affected you, and how, if at all, you overcame the challenge.
  * Open-ended question: What suggestions do you have for improving the project’s policies, processes, or guidelines available to new contributors? [(2)](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
* Look for organizing constructs regarding readability and scannability such as:
  * Headings
  * Text and Code Blocks
  * Bullets or Paragraphs
  * Anchors
* Evaluate searchability by considering:
  * How easily can this documentation be found by a user?
  * How easily can a user find what they require within the documentation?
  * Is the document easy to navigate with a keyboard?
* Provide a quick micro-survey with only one question to readers of the documentation (i.e., bottom-page or popup when leaving documentation page):
  * Yes/No question: Was this documentation page accessible to you?
  * Likert Scale [1-x]: How accessible was this documentation to you?
  * Short Answer: How do you feel about the accessibility of the documentation?
* Walkthrough with intended users of the documentation. Observe how they interact and use the documentation and where they get stuck. This can be a video conference session where the user of the documentation shares their screen.
* Ask users of documentation to write a [friction log](https://devrel.net/developer-experience/an-introduction-to-friction-logging) and describe what issues they had with documentation. This gives concrete use cases for documentation editors to understand how to improve the documentation for the specific user.
* Consider if different versions of documentation are available for different audiences? For example, a light-weight version and a very detailed version

### Filters
- User needs (e.g., visual impairment, cognitive diversity)
- Language version of the documentation
- Documentation type (e.g., quick-start guide, API reference)

### Visualizations
- None specified

</details></span><br>

## References
1. [Breaking Down Barriers to Kubernetes Contribution for Neurodivergent Individuals](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf)
2. [Apache Software Foundation Community Survey 2020](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
3. [GNOME Accessibility Team](https://wiki.gnome.org/Accessibility)
4. [W3C Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
5. [W3C Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/)
6. [Some quick tests to evaluate web accessibility](https://a11yproject.com/#Quick-tests)
7. [Knowability - a group that specializes in Accessibility](https://knowbility.github.io/knowbility-website/services/document-accessibility/)
8. [Thoughts on Accessibility metrics](https://www.boia.org/blog/3-times-accessibility-and-disability-stats-matter-and-3-times-they-dont)
9. [Paypal’s list of Guidelines for Accessibility](http://paypal.github.io/a11y/)
10. [Universal Design](http://shop.oreilly.com/product/9780596518745.do)

## Contributors
- None Specified

## Additional Information
To edit this metric, please [submit a Change Request here](https://github.com/chaoss/wg-dei/blob/main/focus-areas/project-and-community/documentation-accessibility.md).  
To reference this metric in software or publications, please use this stable URL: [https://chaoss.community/?p=3535](https://chaoss.community/?p=3535)

<!-- # For groupings in the knowledge base
Context tags: documentation, accessibility, inclusion
Keyword tags: screen reader, usability, onboarding, friction log, readability, navigation, alternative text
-->

# Documentation Accessibility

Question: How does the documentation accommodate different users?

### This metric is a release candidate. To comment on this metric please see [Issue #321](https://github.com/chaoss/wg-diversity-inclusion/issues/321). Following a comment period, this metric will be included in the next regular release.  

## Description

Documentation accessibility is critical due to the role documentation plays in open source projects. Users of documentation have different abilities, requiring the documentation to be offered in different formats to be equally empowering for these different users. The goal is to foster understanding for the widest audience of contributors to a project.


## Objectives

These objectives help measure whether your documentation is accessible to a broad audience without disproportionately creating or perpetuating artificial debts on certain segments of its intended audiences.

* **Accessibility Screen Reader** — Documentation is accessible according to a standard for screen readers.
* **Learning Flexibility** — Documentation is accessible to people with various cognitive approaches, sensory differences, and neurodiversity [(1)](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf).
* **Blind or Visually Impaired** — Documentation is accessible for people who primarily read text. Charts and images are examples of non-accessible types of documentation.


## Implementation

**Note:** Be attentive to the target audiences for documentation. Due to the broad spectrum of projects and people who may contribute, documentation should address the different requirements of all its audiences.


### Data Collection Strategies

* Use a **tool** that evaluates screen-reader friendliness [(5)](https://www.w3.org/WAI/ER/tools/) [(6)](https://a11yproject.com/#Quick-tests) to determine if the documentation is screen-reader friendly?
* **Interview** newcomers to figure out how documentation helped with, (a) understanding the contribution process, and/or, (b) helping to complete tasks in a project.\
Sample interview questions:
  * What is your experience with using the documentation to understand the contribution process?
  * What is your experience with consulting the documentation when you have a question about doing work in the project?
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
    * Matrix columns can be:
      * Always easy to find
        * Easy to find
        * Difficult to find
        * Very difficult to find
  * Multiple choice: Did you face any challenges related to the accessibility of documentation when you started to participate in the project (e.g., language barriers, discoverability of documentation, structure of documentation)? [(2)](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
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
* **Walkthrough** with intended users of the documentation. Observe how they interact and use the documentation and where they get stuck. This can be a video conference session where the user of the documentation shares their screen.
* Ask users of documentation to write a **friction log** and describe what issues they had with documentation. This gives concrete use cases for documentation editors to understand how to improve the documentation for the specific user.
* Consider if **different versions of documentation** are available for different audiences? For example, a light-weight version and a very detailed version.


## Resources

1. [Breaking Down Barriers to Kubernetes Contribution for Neurodivergent Individuals](https://static.sched.com/hosted_files/kcsna2019/05/Breaking%20Down%20Barriers%20to%20Kubernetes%20Contribution%20for%20Neurodivergent%20Individuals%20%282%29.pdf)
2. [Apache Software Foundation Community Survey 2020](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=158869274)
3. [GNOME Accessibility Team](https://wiki.gnome.org/Accessibility)
4. [W3C Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/)
5. [W3C Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/)
6. [Some quick tests to evaluate web accessibility](https://a11yproject.com/#Quick-tests)
7. [Knowability - a group that specializes in Accessibility](https://knowbility.org/services/document-accessibility/)
8. [Thoughts on Accessibility metrics](https://www.boia.org/blog/3-times-accessibility-and-disability-stats-matter-and-3-times-they-dont)
9. [Paypal’s list of Guidelines for Accessibility](http://paypal.github.io/a11y/)
10. [Universal Design](http://shop.oreilly.com/product/9780596518745.do)

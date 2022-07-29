# Psychological Safety

Question: To what extent do community members feel safe within a community, including adding contributions, influencing change, bringing their authentic selves, and generally participating in the project?

## Description

A key component that is integral to the goal of community inclusion, is psychological safety. Psychological safety can be defined in several different stages, according to the [Center for Creative Leadership](https://www.ccl.org/articles/leading-effectively-articles/what-is-psychological-safety-at-work/):



* Stage 1 – Inclusion Safety: Inclusion safety satisfies the basic human need to connect and belong. In this stage, you feel safe to be yourself and are accepted for who you are, including your unique attributes and defining characteristics.
* Stage 2 – Learner Safety: Learner safety satisfies the need to learn and grow. In this stage, you feel safe to exchange in the learning process, by asking questions, giving and receiving feedback, experimenting, and making mistakes.
* Stage 3 – Contributor Safety: Contributor safety satisfies the need to make a difference. You feel safe using your skills and abilities to make a meaningful contribution.
* Stage 4 – Challenger Safety: Challenger safety satisfies the need to make things better. You feel safe to speak up and challenge the status quo when you think there’s an opportunity to change or improve.

In communities with a strong level of psychological safety, contributors are more likely to be empowered to propose changes and take on leadership and/or decision-making roles. Psychological safety in communities impacts diversity, equity, and inclusion, and is signaled by indicators such as:



* Diversity: Contributors from under-represented groups are more likely to be active participants and encourage others to be so as well
* Equity: The distribution of decision-making and leadership roles is evenly distributed to include traditionally marginalized groups
* Inclusion: Those from marginalized or underrepresented backgrounds feel welcome and as if they can bring their authentic selves to the project in a safe environment
* Attraction: Creating a safe environment increases the likelihood of attracting new contributors
* Retention: Contributors are more likely to remain connected to the project if they feel safe in doing so

There will be a positive effect on contributor diversity, sense of inclusion and belonging, and ultimately contributor retention if:



* community members feel safe participating in the community through code contributions, comments, discussions, and other forms of participation
* there is a level of trust that policies have been put in place to mitigate harassment and intolerance
* there is a mechanism in place to effectively address problems if they occur
* contributors have no serious privacy concerns related to the project
* there is a high degree of transparency between project leadership and the community
* any potential vectors for abuse in the code itself have been prioritized as problematic by project leadership

## Objectives

This metric is designed to:



* Enable project maintainers to understand the level of psychological safety around project policies, such as code of conduct, and code of conduct enforcement
* Allow community members to voice concerns about psychological safety
* Identify potential areas for improving psychological safety within the community

## Implementation
*The usage and dissemination of health metrics may lead to privacy violations. Organizations may be exposed to risks. These risks may flow from compliance with the GDPR in the EU, with state law in the US, or with other law. There may also be contractual risks flowing from terms of service for data providers such as GitHub and GitLab. The usage of metrics must be examined for risk and potential data ethics problems. Please see [CHAOSS Data Ethics document](https://github.com/chaoss/community/blob/main/data-use-statement.md) for additional guidance.*


### Data Collection Strategies

The following is an example of one way to assess the level of psychological safety of open source project contributors and maintainers through a useful set of questions that can be asked regarding the well-being of community members.

_**Candidate**_ questions include:

1. Have you ever observed any of the following in the context of an open source project?
Answer options: Yes/No. If yes [select all that apply]: 
- (1) Lack of response to contributions or questions
- (2) Rejection of contributions without explanation
- (3) Dismissive responses to contributions or questions
- (4) Documentation that is incomplete or difficult to understand
- (5) Conflict or interpersonal tension between contributors
- (6) Language or other content that made you feel unwelcome (e.g. profanity, racist jokes, sexual imagery, etc.)

2. Have you ever **witnessed** any of the following behaviors directed at another person in the context of an open source project? (not including something directed at you) 
Answer options: Yes/No. If yes [select all that apply]:  
- (1) Hostility or rudeness
- (2) Name-calling
- (3) Threats of violence
- (4) Impersonation
- (5) Harassment over a sustained period
- (6) Harassment across multiple platforms
- (7) Stalking
- (8) Unsolicited sexual advances or comments
- (9) Stereotyping based on perceived demographic characteristics
- (10) Malicious publication of personal information (doxxing)
- (11) Other (please describe)
 
3. Have you ever **experienced** any of the following behaviors directed at you in the context of an open source project? 
Answer options: Yes/No. If yes [select all that apply]: 
- (1) Hostility or rudeness 
- (2) Name-calling 
- (3) Threats of violence
- (4) Impersonation
- (5) Harassment over a sustained period
- (6) Harassment across multiple platforms
- (7) Stalking
- (8) Unsolicited sexual advances or comments
- (9) Stereotyping based on perceived demographic characteristics
- (10) Malicious publication of personal information (doxxing)
- (11) Other (please describe)
 
3a. If yes to the above, when thinking of the last time you **experienced** harassment, how did you respond? Choose all that apply.
- (1) Asked the user(s) to stop the harassing behavior
- (2) Solicited support from other community members
- (3) Blocked the user(s) harassing me
- (4) Reported the incident to project maintainers
- (5) Reported the incident to the hosting service or ISP
- (6) Consulted legal counsel/ an attorney
- (7) Contacted law enforcement
- (8) Other (please describe)
- (9) I did not react / ignored the incident

3b. On a scale of 1-5, how effective were your responses? (Use Likert scale with the following options):
- 1: Not at all effective
- 2: A little effective
- 3: Somewhat effective
- 4: Mostly effective
- 5: Completely effective
 
4. As a result of experiencing or witnessing harassment, which, if any, of the following have you done?
- (1) Stopped contributing to a project
- (2) Started contributing under a pseudonym
- (3) Worked, asked questions, or collaborated in private channels more often
- (4) Changed or deleted a username
- (5) Removed or changed content on my public online presence
- (6) Suggested the creation or modification of a Code of Conduct
- (7) Engaged in public discussion with community members about the issue
- (8) Engaged in private discussion with community members about the issue
- (9) Made changes in my life offline (e.g. stopped attending meetups or conferences, etc.)
- (10) Other (please describe)
- (11) None of the above

Additional survey questions may include:

- Do you feel any private details shared with other project contributors or leadership will be kept in the strictest confidence?
- Do you feel as if project leadership values the safety of its participants?
- Do you feel as if project leadership values transparency in its communications and interactions?
- Do you feel as if project leadership is open to critical feedback regarding trust and safety issues?
- Does project leadership acknowledge potential areas in the code that could be used for abuse?
- Did project leadership prioritize these issues as areas to be fixed?
- Did the community push back on fixing these issues?

### Filters



* Demographic segments
* Role of the contributor (code, community management, advocacy, documentation, etc.)
* Length of time in the community

## References



* [Psychological Safety, Trust, and Learning in Organizations: A Group-level Lens](https://www.researchgate.net/publication/268328210_Psychological_Safety_Trust_and_Learning_in_Organizations_A_Group-level_Lens)
* [Adding Community and Safety Checks to New Features (GitHub Blog)](https://github.blog/2017-01-31-community-and-safety-feature-reviews/)
* [Open Source Survey 2017](https://opensourcesurvey.org/2017/)
* [What is Psychological Safety at Work](https://www.ccl.org/articles/leading-effectively-articles/what-is-psychological-safety-at-work/)

## Contributors



* Elizabeth Barron
* Matt Germonprez
* Kevin Lumbard
* Lauren Phipps
* Dawn Foster
* Matt Cantu
* Lucas Gonze
* Justin W. Flory
* Emily Brown
* Amy Marrich
* Trisha Rajaram
* Ruth Ikegah
* Emily Brown
* Sean Goggins
* Georg Link

***This metric was last reviewed on July 20, 2022 as part of the metrics revision process.***

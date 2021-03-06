# Chat Platform Inclusivity

Question: How do you review Chat Platform inclusivity for your community?

## Description

Open Source communities need places for contributors to interact and engage with each other.
Much of this communication is likely to be project-related, but there may also be spaces for general social connection with other contributors.
This metric describes synchronous communication in Chat Platforms, which includes platforms for public shared chat rooms, real-time conversations, and video conferences.

Chat Platforms are essential to a functioning open source community.
Chat Platforms support a healthy project by enabling cross-team collaboration in different skill areas, helping peer collaborators find and interact with each other faster, increasing project transparency which allows team members to notice potential problems before they occur, and saving time by cutting across organizational hierarchies.
Persistent Chat Platforms also become a reference for newcomers to familiarize themselves with project history, practice, and culture.

Chat Platforms should be chosen, moderated, and managed transparently, using inclusive language in order to accelerate innovative problem-solving and sustain contributor participation.


## Objectives

* Support decision-makers when choosing a Chat Platform.
* Provide ideas that contributors and potential contributors may use to evaluate the specific context of any given project.
* Identify characteristics of the Chat Platforms, such as those identified under filters, that suggest greater inclusivity.


## Implementation

### Filters

How do these filters measure inclusivity?
Think of it like an office space.
How many teams (Chat Platforms) are there?
How active are they?
For example, very active chats can be difficult to follow and that difficulty will vary from person to person.

* General:
  * Number of active Chat Platforms / rooms / groups
  * Number of messages per day, week, month
  * Number of active participants per day, week, month
  * Number of passive participants (i.e. reading but not participating)
  * Number of external participants (i.e. people who are not associated with a leading company working on an Open Source Project, such as Red Hat with the Fedora Project)
* Identities:
  * Number of (independent) volunteers
  * Number of corporate volunteers (people being paid by another entity to to volunteer work)
  * Number of workers (employees or contractors)
* Platforms without persistent connections (i.e., IRC):
  * Number of daily connections to room
  * Number of repeat logins

### Visualizations

* Most active hours in community-specific Chat Platforms
* Number of active new chat members vs. older chat members
* Word clouds (for public Chat Platforms, e.g., public Mattermost rooms)
* “On-topic” vs. “off-topic” conversation
  * How often certain keywords or phrases show up, etc.

### Tools Providing the Metric

[GrimoireLab Perceval][1] currently supports data collection from various Chat Platforms.

### Data Collection Strategies

* **Trace data from Chat Platforms**:
  * See supported platforms for data collection [in Perceval][1].
* **Open Source status of Chat Platform**:
  * See the [CHAOSS blog post on open source platform status][2].
  * Does the chat platform offer Open Source client applications?
  * Does the chat platform offer Open Source server implementations?
  * Does the chat platform offer an Open API for integrating with data collection or bridging?
* **Features for low-bandwidth connections**:
  * Does it require a persistent Internet connection to use (e.g., IRC)?
  * Does the Chat Platform function with minimal bandwidth?
* **Features for community management and moderation**:
  * Does the Chat Platform offer robust moderation tools for moderators?
  * Does the Chat Platform have bot functionality or does it require fully manual intervention for moderation?
* **Features for internationalization**:
  * Is the Chat Platform available in multiple countries, or are there geographic limitations?
  * Does the Chat Platform provide tools for translation?
* **Features for access**:
  * Does the Chat Platform support tools for accessibility (e.g., friendly for screen readers)?
  * Is the Chat Platform easy to use for newcomers?
  * Is the Chat Platform available for a variety of devices?
* **Features for privacy**:
  * Does the Chat Platform require personal information to be verified or submitted for users to sign up?


## References

1. [Love or hate chat? 4 best practices for remote teams][3] — _Opensource.com_
1. [Open source status of chat platforms][2] — _Chaoss.community_
1. **Moderation advice** (can inform choice of platform):
	1. [Moderation guidelines for inclusive community][4] — _rhea.dev_
	1. [Participation & Moderation Guidelines][5] — _drupaldiversity.com_


[1]: https://github.com/chaoss/grimoirelab-perceval#usage
[2]: https://chaoss.community/blog-post/2020/12/15/di-metrics-definition/
[3]: https://opensource.com/article/20/4/chat-tools-best-practices
[4]: https://web.archive.org/web/20200522175549/https:///articles/2017-04/Moderation-guidelines
[5]: https://www.drupaldiversity.com/docs/participation-moderation-guidelines

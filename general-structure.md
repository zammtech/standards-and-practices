# In which is described the general structure of the LearnProgramming Mentoring Community

## Levels of Participation

The LearnProgramming Mentoring Community (LPMC) is structured in the following
way:

1. Learners

    These are programmers with little experience in contributing to OSS projects,
    though they may have prior experience programming. The primary goal of the LPMC
    for these individuals is to give a 'safe' place to contribute, without fear of
    out-of-hand rejection or any sort of ridicule.

    The primary interaction a learner has with the LPMC is through fork/pull
    requests. By the nature of the LPMC, the commit bit is only given out sparingly;
    since we want to encourage code review and learning-through-iteration.

2. Associates

    These are former learners who have acheieved some degree of expertise on certain
    projects, and have demonstrated a consistent ability to contribute good code.
    Associates are, essentially, "graduated" Learners. They are thus introduced to
    new responsibilities and opportunities. In particular, for the projects they
    have demonstrated the most contributions too, they may be given the commit bit,
    and given the opportunity to review and accept/reject pull requests. Mentors are
    still responsible for doing the final merge for new associates, but over time
    the associate is given full pull-request administration duties.

3. Mentors

    These are associates who have demonstrated through continued service to the LPMC
    that they have learned excellent FOSS development and contribution skills. They
    are intimately familiar with many, if not all, of the projects, and have shown
    themselves to be highly valued members of the LPMC. As with Associate status,
    these individuals are granted, for their efforts, more responsibility. They are
    given full access to merge any pull requests on any project.

4. Project Leaders

    These are mentors who demonstrate considerably deep knowledge about a given
    project. They are responsible for guiding the future of a project with their
    fellow Project Leaders. In particular, they are the ones who act as
    "Maintainers" in the traditional sense of the word. They may decide amongst
    themselves in the context of each project how best to guide it's development.
    Though it is the opinion of this document that they should favor a small, odd
    number of Project Leaders per project, and use a simple-majority voting system.

5. Chief Mentors

    The Chief Mentors are a group of five individuals who have demonstrated
    dedication and skill within the community. They are elected from the group of
    mentors by all members of the community who are associates and up, and serve for
    life. These five people are responsible for the 'back-end' administrative tasks
    dealing with the Github organization, website administration, and similar.
    Otherwise, they are exactly Mentors. Over time, the number of Chief Mentors may
    increase to any odd number. This is to facilitate avoidance of ties in any votes
    they may need to take.

## Filling multiple positions

An individual may serve in multiple roles. Generally, if you are a Mentor, it
is better to take the role of Learner in a project with which you are not
familiar. Similarly, a Project Leader may be Project Leader of more than one
(especially related) project. 

## Regarding Votes

In general, when a vote for some change is called for, it is a vote of all LPMC
members _except_ Learners. The reasoning is thus. While any opinion from any
Learner is valued and should be heard, it is the case that they are coming to
this project with necessarily less contribution, and perhaps less knowledge,
then any other member. To that end, it is more appropriate to allow those who
have demonstrated contribution to be the decision makers, than it is to allow
every learner to vote. On top of that, it is much more difficult to manage
ensuring the veracity of every one of the (hopefully) many learner's identities,
so this allows some degree of assurance that people vote only once.

# Actions of the Chief Mentors

Any action deemed 'controversial' by the Chief Mentors should be put to a vote.
Over time, a list of known 'controversial' actions should be formed. An example
may be the foreclosure of a dead project, the renaming of a repo, etc.
Essentially, any 'breaking change' on the level of administrative tasks
(crucially, _not_ breaking changes in the feature of any project), should be put
to a simple majority vote of the Chief Mentors.

# Regarding Breaking Changes

Non-backwards compatible changes should be at the discretion of the project
leaders. Often, when the breaking change is controversial, this document
encourages the Project Leaders to put the decision to a vote of all contributors
to the project. 

# Regarding Versioning

Unless there is a compelling reason to do otherwise, all LPMC projects should
use the [SemVer](#) standard of versioning. 

# Regarding Design

Design and future direction, features, etc. are to be managed by the Project
Leaders in a way they see fit. All community members are encouraged to
contribute to future feature ideas using the issue-tracker for the project, or
other facility the Project Leader may have in place.

# Regarding 'Design by Committee'

In general, most decisions of a project are made by its Project Leaders, and
voting on features should only happen rarely, and ideally not make it past the
Project Leaders. This document provides for community voting as a last resort,
but such things are discouraged, as continued use is essentially
design-by-committee, which is a recipe for disaster.

# Regarding this document

Though it is written in a formal tone, this document should be taken informally
in most respects except for regarding the ranking structure in "Levels of
Participation" above. The only truly important thing this document does do and
should be regarded is set up an ideal structure which we can all aim to
implement. This document can and should be changed through pull requests, which
should only be approved by the Chief Mentors after discussion and a vote. 

# Regarding the Standards-And-Practices repo

In general, this repo is administrated directly by the Chief Mentors, though as
with all repos, everyone is encouraged to make pull requests regarding policy
changes to it, or -- if they feel they cannot write the policy change
appropriately -- to file an issue with a description of their suggestion which
may then be crafted into a properly worded pull request. As with all LPMC repos,
Pull Request rejection should always be paired with explanation as to why it was
rejected, and -- if applicable -- what could be done to improve it for potential
later acceptance.

# WSR - Weekly Status report

This document contains the weekly status report and indivisual contributions log for all weeks.

1. [Week 1](#week-1)
2. [Week 2](#week-2)
3. [Week 3](#week-3)


## WEEK-1
The first week - The project was introduced. This week, we want to
1. Research the domains of Testing and Architecture design
2. Explore tools in the domain
3. Propose extensions

Since the goals this week are exploratory, we are not assigning time deadlines.

## WEEK-2

### Previous Week's Goals:
Our main goal last week was to find existing research in both domains, explore tools, and propose 2 tools for extension.

### Accomplishments
We sucessfully completed last week's tasks,

Overleaf link to [Proposed tools and research overview](https://www.overleaf.com/13226372zyhdhrkqyqmm#/50905821/)

Link to : [Evaluated tools](https://github.com/saketrule/SElab_SemVI/blob/master/proposed_tools.md)
### Next Week's Goals

Quantized, the key points are

1. [Saket]                  Try ARCADE programs
2. [Varnika, Akash]    Evaluate scope for tool improvement in Paprika
3. [Varnika, Akash]    Research alternate tools to Paprika

### Discussions/Issues

We have to look at alternate possibilities instead of Paprika.
Proper extensions to ARCADE can be decided after hands on experience with the tool


## Week-3

Briefly, the key plan decided last week included:
1. Running ARCADE. 
2. Finding how to change Paprika/ looking for alternatives.

Below is a log of activities performed for each user, along with the time spent for each activity

| Developer | Task log | Time spent |
|:----------|:---------|:-----------|
| Saket | Eclipse installed | 30 |
| Saket | Experienced difficulty to configure for ARCADE | 60 |
| Saket | Tried ACDC Smell detecter on httpd project | 15 |
| Saket | Went through most of the documentation | 2 |
| Saket | Went through paper [Uncovering Architectural Design Decisions](https://arxiv.org/pdf/1704.04798.pdf) | 30 |
| Saket | Went through paper [An Empirical Study of Architectural Change in Open-Source Software Systems](http://shahbazian.me/papers/msr.pdf) | 45 |
| Varnika | Tried running Paprika | 60 |
| Varnika | Went through source code to evaluate how anti-patterns and code-smells are implemented | 45 |
| Varnika | Had some trouble navigating the source code, maybe needs a class diagram! :) | 45 |
| Akash | Looked at alternatives to Paprika | 60 |
| Akash | Went through source code of Paprika with Varnika, to see implementation details | 45 |

#### Agenda list
for the next meeting is:
1. Decide on how to proceed with the second (Testing tool)
2. Discuss extensions for the ARCADE tool


### Goals for next week
We will decide the goals for next week after a team meeting




























## Week-4

Overall, the progress this week:

1. We have been unsuccessfully trying to run Paprika.
2. We are in contact with the principal developer, Geoffrey Hecht and have been working with him to resolve the bug. We think bug resolution itself might be a contribution.
3. We are considering replacing Paprika if it still fails. These conditions are unforeseeable.

### What we did this week:

| Developer | Task log | Time spent(hours) |
|:----------|:---------|:-----------|
| Vernika | Working on getting Paprika to work | 3 |
| Akash | Working on getting Paprika to work | 2 |
| Akash | Tried to find alternate tools to replace Paprika | 2 |
| Saket | Tried resolving bugs in Paprika | 3 |
| Varnika | Ran SmellyCat | 2 |


Here is our proposed plan for next week:


| Task | Developer | Time |
|:-------|:----------|:----------|
|Last attempt at resolving Paprika bug | Saket | 1 day |
| Find an alternate to Paprika | Varnika, Akash | 1 day |
| Report/ Team meeting with the following scenarios | | Thursday |
| | | |
| `(If successful)` | | |
| Get working extension of Paprika | Saket, Varnika, Akash | Tuesday |
| Try arcade on Android | Saket | Tuesday |
| | | |
| `(If unsuccessful)` | | |
| Replace project, discuss extensions | | Tuesday |
| Try arcade on Android | Saket | Tuesday |

---------------------------


## Week-5

We successfully executed our plan from week 4. The progress is summarized as below:

1. We switched from Paprika to Smelly-cat, a tool to identify code metrics and smells in android code.
2. We analyzed the source code of smelly-cat, sucessfully ran it.
3. Refactored result template to separate css, javascript, modularize code
4. Changed API interface of smelly-cat to include a `-v` option, for comparing different versions.
5. Developed and integrated a new package to source-code, which outputs html file for version comparison.
6. We plan to extend this to integrate it with a git system, allow for data cashing.

Developer-wise summary of what we did:

| Developer | Task log | Time spent(hours) |
|:----------|:---------|:-----------|
| Varnika, Akash | Proposed paprika tool, possible extensions on analysis | 3 |
| Varnika, Akash | Documented code structure, to properly extend the tool | 1 |
| Saket, Varnika, Akash | Modified output template file | 2 |
| Saket, Varnika, Akash | Added the `-v` option, code to compare multiple versions | 2 |
| Saket, Varnika, Akash | Developed package for modified output template | 2 |
| Saket, Varnika, Akash | Added javascript logic, changing the html template file | 3 |

Plans for next week:
1. We'll integrate the project with a `-g git ` option for version control.




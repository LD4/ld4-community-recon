# LD4 Community Working Group on Reconciliation

## About

[Linked Data for Libraries, Linked Data for Production, and Linked Data for Libraries Labs](https://ld4l.org/) are a series of grant-funded projects working broadly on implementing Linked Data in library workflows across functional areas and domains. The umbrella effort is referred to as 'LD4'.

LD4 Community groups are a way to work with interested community members on a work area or topic that intersects with Linked Data and library work needs. They are open to participation from anyone and aim for the highest level of transparency in efforts, work, & outputs to help support a growing community of Linked Data implementers in libraries and other GLAM, cultural heritage, and memory institutions.

### Conveners:

- Arwen Hutt / ahutt@ucsd.edu ; @arwenhutt
- Christina Harlow / cmharlow@stanford.edu ; @cmh2166

### Scope

This LD4 Community group is an effort to:
- generate a shared understanding of what reconciliation work entails, including use cases and user stories;
- build collaboration for existing or emerging reconciliation tool development;
- and outline pragmatic solutions including matching algorithms, workflows, tools, and functional requirements for Cultural Heritage/GLAM+ resource metadata reconciliation.

NB: **Metadata** here is used in an expansive way to cover not only traditional bibliographic metadata, but also descriptions for emerging resource types & metadata domains (rights, administrative, structural, etc.) as applicable to the group’s efforts.

NB: **Reconciliation** here is meant broadly and includes:
- Reconciliation (in specific sense): entity/URI to entity/URI
- Entity resolution: string to entity/URI (what most people are thinking about, it appears)
- Lexicalization: entity/URI to string (i.e. getting a label)

The above is generated from [LD4 Community Meeting Feedback](https://wiki.duraspace.org/pages/viewpage.action?pageId=83232681), which included the following points:
- “There were so many cool presentations and conversations today around reconciliation tools, I would love to see conversations around that continue”
- “I have a lot of work queued up around reconciliation. lets work together? most is queued up in GH”
- “We’ve been trying to compare reconciliation tools and would like to expand this with this group’s input”
- Largest gap in tooling from the Tools breakout: Reconciliation listed

### Participants

The group is open to anyone who wants to contribute. [Get in touch the conveners](#conveners) if you're uncertain where to start or how to jump in.

+ Valentine Charles / valentine.charles@europeana.edu ; [@vcharles89](https://github.com/vcharles89)
+ Arcadia Falcone / arcadia@stanford.edu ; [@arcadiafalcone](https://github.com/arcadiafalcone)
+ Theodore Gerontakos / tgis@uw.edu ; ([@gerontakos](https://github.com/gerontakos))
* Joshua Greben / jgreben@stanford.edu  ; [@jgreben](https://github.com/jgreben)
+ Julie Hardesty / jlhardes@iu.edu ; ([@jlhardes](https://github.com/jlhardes))
+ Kirk Hess / khes@loc.gov ; [@kirkhess](https://github.com/kirkhess)
+ Timothy Hill / timothy.hill@europeana.eu ; ([@thill-asp](https://github.com/thill-asp))
+ Ryan Johnson / rejohnson@ucsd.edu ; ([@remerjohnson](https://github.com/remerjohnson))
+ Suzanne Pilsk / PilskS@si.edu ; [@pilsks](https://github.com/pilsks)
+ Gregory Reser / greser@ucsd.edu ;
+ Chrissy Rissmeyer / crissmeyer@ucsb.edu ; ([@chrissyrissmeyer](https://github.com/chrissyrissmeyer))
+ Darcy Rueda / dlrueda@stanford.edu ; [@dlrueda](https://github.com/dlrueda)
+ Shlomo Sanders / Shlomo.Sanders@exlibrisgroup.com ; [@shlomosanders](https://github.com/shlomosanders)
+ Adam Soroka / ajs6f@apache.org ; ([@ajs6f](https://github.com/ajs6f))
+ Osma Suominen / osma.suominen@helsinki.fi ; [@osma](https://github.com/osma)
+ Nate Trail / ntra@loc.gov ; [@ntra00](https://github.com/ntra00)

## Working Areas

### Proposed Outputs

- List of existing reconciliation tools & a comparison of them
- Identify common reconciliation use cases
- Develop flexible (modular perhaps?) abstract workflow models for use cases
- Create functional requirements for shared workflow components
- Set of leveled (i.e. simplest to complex) reconciliation and matching algorithms for common reconciliation cases & data types (i.e. going from label look-ups based off various string matching algorithms to contextual data matching based off of string and other data type matching algorithms for multiple fields attached to a resource)
- Work on light-weight tools for certain needs listed above to make proof of concepts or support intermediate work & review
- (Meta) Model for LD4 / Other blackbox LODLAM efforts in community engagement & work

### General Timeframe

**For group outputs:** Focus on smaller deliverables with shorter timeframes (< 3 months), as well as parallel work to cover a few different areas of work at the same time. We will start planning these at the kick-off meeting.

**For larger group planning:** Plan on an assessment at 1 year (or earlier if things seem to not be working). The 1 year mark is a time to rotate conveners, choose new meeting times, refresh the goals, disband, morph, etc.

## Workspace & Communication Channels

### Primary Workspace (Notes, Outputs):

- This GitHub repository https://github.com/ld4p/ld4-community-recon/ (Christina @cmh2166, cmharlow@stanford.edu can give you write access to the repository). Please follow this [GitHub Repository's Collaboration guidelines](CONTRIBUTING.md).

### Communication:

- [Regular, short (30 minute) Zoom Video calls (bi-weekly, depending on work) for updates on work](https://github.com/LD4P/ld4-community-recon/wiki/Meetings.md) (links to the Meetings page with call information)
- Github Issues on this repository for work-specific discussions or questions: https://github.com/ld4p/ld4-community-recon/issues
- Github Projects on this repository for project management: https://github.com/LD4P/ld4-community-recon/projects
- Github Wiki on this repository for meeting notes & other documentation: https://github.com/LD4P/ld4-community-recon/wiki
- SUL-DLSS LD4All-Community Slack Channel for informal discussion. We will move to a unified & open LD4 Slack when it is available (Christina @cmh2166, cmharlow@stanford.edu can add you to the Slack channel)
- [Email list](https://groups.google.com/forum/#!forum/ld4-reconciliation) for full-list meeting reminders and general updates. Use this repository as the primary place for communication and collaboration.

## Expectations of Participants

In order to create an inclusive, safe, and open work environment, we ask that all participants follow a [set of rules designed by the the Recurse Center, previously the Hacker School](recurse.com/manual#sub-sec-social-rules). In their own words, *'the goal [of the Recurse Center Social Rules] isn't to burden everyone with a bunch of annoying rules, or to give us a stick to bludgeon people with for "being bad." Rather, these rules are designed to help all of us build a pleasant, productive, and fearless community.'*

As such, these four rules are a lightweight set of explicit social norms to curtail specific kinds of behavior found to be destructive to a supportive, productive, and fun learning/working environment. The four rules are listed here; you can read more about them at http://recurse.com/manual#sub-sec-social-rules.

1. "No feigning surprise." You shouldn't act surprised when someone says they don't know something. There is no benefit to feigning surprise, and regardless of intent, it makes someone feel bad, or worse, about admitting that they don't know something.
2. "No well-actually's." This is when someone says something almost, but not entirely correct, and another person responds with "well, actually," and gives a correction. That's not to say we don't care about truth or precision, but there are better ways to communicate this.
3. "No back-seat driving." If you overhear other people working through a problem, don't just intermittently toss advice in without engaging.
4. "No subtle -isms". This last rule bans racism, sexism, homophobia, transphobia, and other kinds of bias. Subtle -isms are small things that make others feel uncomfortable, and might be familiar as they're under the term "microagressions."

Tip of the hat here also to [Mark Matienzo](http://matienzo.org/), who wrote the additional text explaining each of these rules in the context of a collaborative environment. We've paraphrased Matienzo's comments here.

## Questions or Comments?

Use [Github Issues on this repository](https://github.com/ld4p/ld4-community-recon/issues) or [get in touch with one of the conveners](#conveners).

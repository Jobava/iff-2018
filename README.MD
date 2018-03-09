Workshop plan

### WHAT?

What is localization.

More than translation, adapting language to a local context.


### WHY?

Why localize?

* Context, making something adaptable, participation.
* Reaching other communities and reachability of software and advocacy reasons.
* Preservation of minority language.
* People taking ownership and preservation of language.
* Assumption that English prevails wrong even for technical environments.
* Adapting tools to local context.
* Extra testing and feedback from users.
* Increasing usability of tools, allowing people to have ownership over tools, feedback and insight.
* Localizing technical tools and technical documentation for technical tools.


### TOOLS and UIs

Tools and why have them / make them. 


Tool, example URL, number of people that work and worked with them (from this workshop)

* Pootle: https://translations.documentfoundation.org/ro/  1
* Pontoon: https://pontoon.mozilla.org/ro/    2
* Transifex: https://www.transifex.com/voxelands/voxelands/translate/#ro/voxelandspot/117642715?translated=no everyone
* Crowdin: https://crowdin.com/translate/wire-cs/1184/en-ro  3
* Weblate: https://hosted.weblate.org/projects/debian-installer/   everyone
* Zanata (Fedora and RedHat): https://fedora.zanata.org   1
* Damned Lies (Gnome): https://l10n.gnome.org/   1
* Babelzilla (Mozilla addons, defunct)   2
* programmer-oriented tools: github, gitlab   4
* no tools: git/e-mail  5
* launchpad: ubuntu-related 2
* Offline tools: Poedit, CAT tools, SDL

Favorite tool: Pontoon

Least favorite tool: Transifex

Why people dislike some tools:
* lack of ownership of translation and of data (like cloud-based solutions)
* lack of granularity of permissions
* having to sign up to a website and the security implications of that


### FEATURES

Features we want from a translation UI:
* list of strings view (most basic requirement)
* translation memory: Transifex may not work across projects, also Amagama (now abandoned)
  * missing feature: contextual TM
* terminology
* automated translation (people noted Google Translate as better than Microsoft's Bing Translate)
  * a workshop participant noted that there are free software solutions for automated translation, such as TMServer
* related strings in other languages
  * a member noted a French tool -- Traduction
* related strings in other projects
* checks (consistency & formatting & custom)
* ability to report bad source string to developer
* ability to ask questions about the source string
  * does anyone get notified when questions arrive? (yes in weblate)


Missing features from tooling today:

* good search and replace, regex search
* timelines (string contribution history of a certain user) useful for reviewers
  * Pontoon has useless timelines
  * Pootle has timelines, but not useful for large reviews


The talk was cut short as we ran out of time.

What we didn't talk about, but was on the agenda:

* Tools don't offer UIs specific to a Reviewer's role, such as:
  * personalized reviews
  * formal review with standard quality checks (MQM)

* Tools need better UIs for project managers and maintainers:
  * granular permissions
  * who just started to contribute
  * what changed recently
  * who added what recently
  * which people modified this string

* Tools have limited or no support for notifications in the UI:
  * deadlines
  * when new users arrive
  * when new strings are added

For Pontoon specifically, there is a Firefox Extention: Pontoon Tools that adds a limited set of notifications.

* Discuss tooling support for offline work and what more we need from them, like data export
* Discuss about what would it take to move some people off offline and into tool UIs

### COMPARE

We didn't get to cover also the following:

* Feature matrix of existing tools

* What we need to make the review process faster, better, higher quality, with better feedback

* Quality assurance, checks, formal feedback (MQM)

* Terminology control and terminology hierarchies

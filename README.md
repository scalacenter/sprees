# Open Source Spree

The focus of Scala Sprees is to help newcomers and veterans alike participate
in open source! Come meet contributors of well-known open source Scala projects and
learn how you can make your own contribution.

We have TWO sprees planned for June 2023 in Seattle and San Francisco!

**Your challenge?** Get one pull request merged into one of the projects, and
get this awesome t-shirt:
![](https://pbs.twimg.com/media/CtnCrtvWAAAO0nE.jpg:small)

## Madrid, Spain. Monday, 15th of September 2023

|                    |                                                                                                 |
|--------------------|-------------------------------------------------------------------------------------------------|
| Time               | Friday, 15th of September 2023, 13:30-17:00                                                           |
| Location           | Universidad Rey Juan Carlos – Sede Madrid-Argüelles, C. de Quintana, 21, 28008 Madrid, Spain) |
| Event Registration | <https://airtable.com/shrwSI11zJHmh7CkZ>                                    |
| Bring              | laptop + power cord                                                                             |

### Projects

If you are a **maintainer** of an OSS project and would like to mentor someone during the Spree on your project, please fill in the [form](https://airtable.com/shrwSI11zJHmh7CkZ), indicating that you would like to be a mentor.

| Project                                                                              |Description | Contact                                                              |
|--------------------------------------------------------------------------------------|------------|----------------------------------------------------------------------|
| [docs.scala-lang.org](https://github.com/scala/docs.scala-lang) | scala 3 additions, new material, restructuring, translations | [@bishabosha](https://github.com/bishabosha) |
| [The Scala Toolkit](https://github.com/scala/toolkit) | Tookit introduces libraries for everyday tasks in Scala! We are in round 2 of selecting candidates | [@bishabosha](https://github.com/bishabosha) |
| [Doric](https://github.com/hablapps/doric)| Type safe Spark columns | [@alfonsorr](https://github.com/alfonsorr) |
| [Scala's Advent of Code](https://github.com/scalacenter/scala-advent-of-code)| contribute solutions and explanations for 2022, 2021 and earlier | [@bishabosha](https://github.com/bishabosha) |
| [Scala 3 Compiler](https://github.com/lampepfl/dotty) | linting, semanticdb, parsing, error messages, new features, etc. | [@smarter](https://github.com/smarter), [@bishabosha](https://github.com/bishabosha), [@dwijnand](https://github.com/dwijnand) |
| [TASTy Query](https://github.com/scalacenter/tasty-query) | static analysis of your classpath and the definitions within | [@bishabosha](https://github.com/bishabosha) |

<!--
| Jamie Thompson | Guillaume Martres | Anatolii Kmetiuk |
|-|-|-|
| <img src="https://scala.epfl.ch/resources/img/jamiethompson.png"> | <img src="https://scala.epfl.ch/resources/img/guillaume-martres.jpg"> | <img src="https://scala.epfl.ch/resources/img/toli.png"> |

| Seth Tisue | Szymon Rodziewicz | Tomasz Godzik |
|-|-|-|
| <img src="https://i.imgur.com/ubdDky1.jpg" height="150" width="150"> | <img src="https://avatars.githubusercontent.com/u/4761866" height="150" width="150"> | <img src="https://avatars.githubusercontent.com/u/3807253" height="150" width="150"> | -->

## Duration, pace steps

At the beginning, maintainers gather together in front of all the contributors
to briefly explain their projects and tickets in one minute. The idea is to give
a good high-level explanation to motivate participants without going into too
much detail. A link to this page is provided.

When they are done, participants approach the projects they are most
interested in and speak with the maintainers. Maintainers can listen
to the participants' experience and provide guidance on what tickets
would suit them.

Then, the fun begins! Participants start hacking on their projects and
maintainers review PRs as they come, assisting participants when they ask for
help. We encourage maintainers to merge as many PRs on the spot if possible,
for two reasons:

1. Participants get a small token of appreciation from the Scala Center.
2. It increases the motivation of the participants.

If a participant gets their first PR merged, they are invited to continue solving
issues until they are happy with their work!

At the middle of the spree, the Scala Center and sponsors of the event provide
maintainers and participants alike with some refreshment (drinks, sandwiches,
pizza, etc).

Participants can leave the event at any time they want. When the time approaches
the end, everyone starts to wrap up: participants finish their PRs while
maintainers finish their review, and organizers of the spree give away Scala
t-shirts. We finish by thanking your hard work for open-source.

## For Maintainers

### How to propose a project

A Scala Center spree is the perfect event to gauge interest in your open-source
projects. You not only have the opportunity to get new contributors involved in
your project, but you can make friends and co-maintainers that help you
make a difference in the open-source world.

There is only one requirement to submit a project -- you need to be present for
the duration of the Scala Center spree. Your physical presence is important to
assist and motivate contributors.

If you are a maintainer of an open-source Scala project, fill in the registration
[form](https://airtable.com/shrwSI11zJHmh7CkZ) and we will get in touch with you.

### What you need to do

Create a PR with the following information:

- Project information.
- Your contact details.
- A link to a "spree" or "hackathon" label with curated tickets for the
  participants. See
  [this project](https://github.com/sbt/zinc/issues?utf8=✓&q=label:hackathon%20is:issue)
  for inspiration.

It's important that the curated tickets are entry-level, typical issues that you
would solve in 15-20 minutes of your time as an experienced maintainer. In our
experience, newcomers will take 1 to 2 hours to address them, assuming they are
unfamiliar with the codebase and this is their first contribution.

### How to be an effective maintainer

Maintainers can make a difference by tweaking some knobs:

- Provide a `CONTRIBUTING` guide. Contributing guides explain to newcomers the
  usual workflow to get started and what's expected from them. Good guides:
  [scala/scala](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md),
  [sbt/zinc](https://github.com/sbt/zinc/blob/1.x/CONTRIBUTING.md),
  [scalameta/scalameta](https://github.com/scalameta/scalameta/blob/master/CONTRIBUTING.md),
  [scalacenter/scalafix](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md).
- Provide a motivating `README` with clear instructions. Make sure docs are up
  to date.
- Link to documentation when possible, or show contributors how to search for
  docs. You can label as `docs` any issue or PR with relevant discussions to get
  acquainted with implementation details and design decisions.
- [Be nice to newcomers](http://brson.github.io/2017/04/05/minimally-nice-maintainer),
  they will always remember it!

### How to write good tickets

Curating tickets is not easy. If you want to optimize for the highest number of
contributors, we recommend you to:

- Give hints on potential solutions. Say which solutions are not on the table,
  if any.
- Describe the purpose of the ticket and its context. Having a clear idea of why
  your ticket is relevant will motivate participants.
- Add links to source code sparingly. Show the entry-points for the requested
  functionality / fix, give a basic explanation of the code structure.
- Be concise and detail specifics of your project or its implementation.
  Providing this kind of domain knowledge to participants will help them finish
  off their tickets sooner, and move to the next one!

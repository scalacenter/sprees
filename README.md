# Open Source Spree

The focus of Scala Sprees is to introduce newcomers and veterans alike to open
source! Come meet contributors of well-known open source Scala projects and
learn how you can make your own contribution.

**Your challenge?** Get one pull request merged into one of the projects, and
get this awesome t-shirt:
![](https://pbs.twimg.com/media/CtnCrtvWAAAO0nE.jpg:small)

[![Join the chat at https://gitter.im/scalacenter/sprees](https://badges.gitter.im/scalacenter/sprees.svg)](https://gitter.im/scalacenter/sprees?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Lausanne, Switzerland. June 11th 2019

|                    |                                                              |
| ------------------ | ------------------------------------------------------------ |
| Time               | June 11th, 09:00 - 16:00                               |
| Location           | EPFL building BC, 4th Floor, room no. 410, Lausanne, Switzerland |
| Event Registration | Free [here](https://www.meetup.com/Scala-Romandie/events/261590615/) |
| Food               | Free! See detailed schedule. |
| Bring              | Laptop + Power Cord                                          |

### Detailed Schedule

|            |         |
| ---------- | ------- |
| Welcome Breakfast | 08:00 - 09:00 |
| Start Time | 09:00 |
| Coffee and fruits break | 11:00 |
| Lunch     | 12:30 |
| End Time | 16:00 |

### Projects (**Maintainers: Please add your project here!**)

Here is a list of projects that you could contribute to during the spree:

| Project                                                   | Contact          |
| --------------------------------------------------------- | ---------------- |
| [Coursier] — Library and CLI tool to manage dependencies  | @alexarchambault |
| [Almond] (aka jupyter-scala) — Scala kernel for Jupyter   | @alexarchambault |
| [Bloop] — Scala build server for fast developer workflows | @jvican          |
| [Scala.js] — scalac backend that produces JavaScript      | @sjrd            |
| [scalac] — The Scala compiler and standard library        | @sjrd            |
| [scalajs-bundler] — Integration with npm and webpack      | @julienrf        |
| [endpoints] — Consistent HTTP client, server and docs     | @julienrf        |
| [akka] - Toolkit to build concurrent and distributed apps | @jrudolph        |
| [akka-http] - Streaming HTTP server + client on Akka      | @jrudolph        |
| [Metals] - Language Server for Scala                      | @olafurpg        |
| Add your project here!                                    |                  |

[almond]: https://github.com/almond-sh/almond/labels/low%20hanging%20fruit
[coursier]: https://github.com/coursier/coursier/issues?q=is%3Aopen+is%3Aissue+label%3Aspree
[scala.js]: https://github.com/scala-js/scala-js
[scalac]: https://github.com/scala/bug/labels/good%20first%20issue
[bloop]: https://github.com/scalacenter/bloop/labels/good%20first%20issue
[intellij scala]: https://github.com/jetbrains/intellij-scala
[scalajs-bundler]:
  https://github.com/scalacenter/scalajs-bundler/labels/low%20hanging%20fruit
[cats]: https://github.com/typelevel/cats/issues
[cats-collections]: https://github.com/typelevel/cats-collections
[cats-mtl]: https://github.com/typelevel/cats-mtl
[scaladex]: https://github.com/scalacenter/scaladex/labels/Scala%20Spree
[graalvm]: https://github.com/oracle/graal
[dotty]:
  https://github.com/lampepfl/dotty/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22
[@smarter]: https://github.com/smarter
[akka]: https://github.com/akka/akka
[akka-http]: https://github.com/akka/akka-http
[metals]: https://github.com/scalameta/metals

Who will be leading the Scala Open Source Spree?

- Darja Jovanovic, @darjutak (Scala Center)
- Sébastien Doeraene, @sjrd (Scala Center)

Want to add your project to the list? Jump to the next section!

## Duration, pace steps

At the beginning, maintainers gather together in front of all the contributors
to briefly explain their projects and tickets in one minute. The idea is to give
a good high-level explanation to motivate participants without going into too
much detail. A link to this page is provided.

When they are done, participants approach the projects they are most interested
in and get it contact with the maintainers. At this point, maintainers usually
listen to the participants' experience and provide personal guidance on tickets
that would suit them.

Then, the fun begins! Participants start hacking on their projects and
maintainers review PRs as they come, assisting participants when they ask for
help. We encourage maintainers to merge as many PRs as possible in the place,
for two reasons:

1.  Participants get a small token of appreciation from the Scala Center.
2.  It increases the motivation of the participants.

If participants get the first PR merged, they are invited to continue solving
issues until they are happy with their work!

At the middle of the spree, the Scala Center and sponsors of the event provide
maintainers and participants alike with some refreshment (drinks, sandwiches,
pizza, etc).

Participants can leave the event at any time they want. When the time approaches
the end, everyone starts to wrap up: participants finish their PRs while
maintainers finish their review, and organizers of the spree give away Scala
t-shirts. We finish by thanking your hard work for open-source.

## For Maintainers:

### How to propose a project

A Scala Center spree is the perfect event to gauge interest in your open-source
projects. You not only have the opportunity to get new contributors involved in
your project, but you can win friends and lifetime maintainers that help you
make a difference in the open-source world.

There is only one requirement to submit a project -- you need to be present for
the duration of the Scala Center spree. Your physical presence is important to
assist and motivate contributors.

If you are a maintainer of an open-source Scala project, make a PR to add your
project to the list!

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

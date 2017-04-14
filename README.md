# [Scala Days Chicago](http://event.scaladays.org/scaladays-chicago-2017)

The Scala Center is organizing an *Open Source Spree* at Scala Days, on Tuesday, April 18.

The focus of Scala Sprees is to introduce newcomers to open source! Come learn how to 
contribute to open source Scala projects. Meet other contributors on well-known open 
source Scala projects.

You don't have to be new to open source to attend -- anyone who wants help making a
contribution to one of the represented Scala projects is welcome.

The event is free. Conference registration is not required.

**Your challenge?** Get one pull request merged into one of the projects,
and get this awesome t-shirt:
![](https://pbs.twimg.com/media/CtnCrtvWAAAO0nE.jpg:small)

[![Join the chat at https://gitter.im/scalacenter/hackathons](https://badges.gitter.im/scalacenter/hackathons.svg)](https://gitter.im/scalacenter/hackathons?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Where and when?

Swissôtel Chicago<br />
323 E Upper Wacker Dr.<br />
Chicago, IL 60601<br />
Look for room “Zurich C” (basement floor) - that’s where we will be<br />

We will start at 10am and go until 4pm (free food will be provided).

## Projects

Here is a list of projects that you could contribute to during the spree:

| Project                                           | Contact                           |
| -------                                           | -------                           |
| [scastie][scastie]                                | [@MasseGuillaume][MasseGuillaume] |
| [scaladex][scaladex]                              | [@MasseGuillaume][MasseGuillaume] |
| [scala-lang.org][scala-lang]                      | [@SethTisue][SethTisue]           |
| [docs.scala-lang.org][docs.scala-lang]            | [@SethTisue][SethTisue]           |
| [scala][scala]<br>(spec, api docs, lib, compiler) | [@SethTisue][SethTisue]           |
| [cbt][cbt] - simple, fast scala builds            | [@cvogt][cvogt]                   |
| add your project here!                            |                                   |

Who will be leading the Scala Open Source Spree?
- Guillaume Massé, [@MasseGuillaume][MasseGuillaume] (Scala Center)
- Seth Tisue, [@SethTisue][SethTisue] (Lightbend)
- Jon Pretty, [@propensive][propensive] (Propensive)

Want to add your project to the list? Please send us a PR :) For your project to be represented at 
the Scala Open Source Spree, you must (1) be present for the duration of the Scala Open Source Spree 
to assist new contributors, and (2) you must curate a handful of entry-level tickets (~4-5) ahead 
of the event.

[MasseGuillaume]: https://github.com/MasseGuillaume
[SethTisue]: https://github.com/SethTisue
[propensive]: https://github.com/propensive
[cvogt]: https://github.com/cvogt

[docs.scala-lang]: https://github.com/scala/scala.github.com/issues
[scala]: https://github.com/scala/bug/issues
[scala-lang]: https://github.com/scala/scala-lang/issues
[scaladex]: https://github.com/scalacenter/scaladex/labels/hackathon
[scastie]: https://github.com/scalacenter/scastie/labels/hackathon
[cbt]: https://github.com/cvogt/cbt

## How to propose a project

A Scala Center spree is the perfect event to gauge interest in your open-source
projects. You not only have the opportunity to get new contributors involved in
your project, but you can win friends and lifetime maintainers that help you
make a difference in the open-source world.

There is only one requirement to submit a project -- you need to be present for
the duration of the Scala Center spree to assist contributors.  Your physical
presence is important to help and motivate them!

If you are a maintainer of an open-source Scala project, open a PR to add your
project to the list!

### What you need to do

Add a PR with the following information:
  
* Project information.
* Your contact details.
* A link to a "spree" or "hackathon" label with curated tickets for the
  participants. See [this project](https://github.com/sbt/zinc/labels/hackathon) for inspiration.

It's important that the tickets you curate are entry-level, typical issues that
would take you 15-20 minutes of your time as an experienced maintainer. In our
experience, newcomers will take 1 to 2 hours to solve them, depending on their
level of familiarity with the codebase and their experience.

#### How to be an effective maintainer

Maintainers can make a difference by tweaking some knobs:
  
* Provide a `CONTRIBUTING` guide. Contributing guides explain to newcomers the
    usual workflow to get started and what's expected from them. Good guides:
    [scala/scala](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.m://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md),
    [sbt/zinc](https://github.com/sbt/zinc/blob/1.0/CONTRIBUTING.md), [scalameta/scalameta](https://github.com/scalameta/scalameta/blob/master/CONTRIBUTING.m://github.com/scalameta/scalameta/blob/master/CONTRIBUTING.md),
		[scalacenter/scalafix](https://github.com/scala/scala/blob/2.12.x/CONTRIBUTING.md).
* Provide a motivating `README` with clear instructions. Make sure docs are up to date.
* Link to documentation when possible, or show contributors how to search for docs.
* [Be nice to newcomers](http://brson.github.io/2017/04/05/minimally-nice-maintainer), they will always remember it!

#### How to write good tickets

Curating tickets is not easy. If you want to optimize for the highest number of
contributors, we recommend you to:
  
* Give hints on potential solutions. Say which solutions are not on the table,
    if any.
* Describe the purpose of the ticket and its context. Having a clear idea of why
    your ticket is relevant will motivate participants.
* Add links to source code sparingly. Show the entry-points for the requested
    functionality / fix, give a basic explanation of the code structure.
* Be concise and detail specifics to your project or its implementation that are
    relevant for the ticket.

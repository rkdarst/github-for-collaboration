# Why git / Github?

## What are git / Github?

* **git:** a version control system.  It tracks changes.
  * There are many different programs that use the same format.
  * git dominates the world now.
  * It's a great skill for CVs and stuff.
  * All open-source.
* **GitHub: One website for hosting and sharing git repositories**
  * Also dominates the world (but many competitors)
  * Provides a lot of nice stuff for free
  * Proprietary (not open-source)
* **Github Pages:** makes websites available on the web.


## Why not Github?
* Github is proprietary and not open-source
* Controlled by just one company (Microsoft)
* It's very popular, and this dominance is not good for the world.


## Why git / Github ?  Comparison to our list

This assumes using
* git
* GitHub
* A standard text-to-website generator
* Automatically building and deploying via Github Pages, just like
  [this site](https://rkdarst.github.io/github-for-collaboration/).

```{list-table}
:header-rows: 1
:name: test

* - Feature request
  - Git equivalent
* - View current version
  - Public on Github Pages.

    Also raw original of current version
    visible on github.com
* - History available
  - Full history on github.com via web browser.

    With other tools, you can do much more detailed inspections.
* - Permanent identifiers for each version
  - Git provides this via the "version hash", like
  `2d77d996bfe06048ba44d6914e423702d4b79a7e` (or short form,
  `2d77d9`).

    This will never change.

    This used to be searchable on Github but I can't make it work
	anymore.
* - Others can contribute changes
  - This is the "killer feature" of Github.  It works for non-code,
    too.

* - Contribute without advanced permission
  - Anyone can make a **fork** which is a separate linked copy, make
	their change, and propose it back to you.

    There is no possibility of change until it is approved.

* - Other versions possible
  - Yes: the forks can make their own versions avalible for others.

* - You can easily see and merge differences
  - Yes: this is a killer feature of git.  Demo later.

* - All open-source
  - git: yes.  Github: no
* - Via web browser
  - Basic edits and modifications, yes.  Old presentation: [github-without-command-line](https://coderefinery.github.io/github-without-command-line/)

    Setting it up and advanced fixing could be done also but better to
	be done with a computer.
* - Zenodo archiving
  - Yes: can be made [automatic archival for each release](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
* - Easy enough for anyone with basic training
  - **???**

    This is the big question.  Historically, "no" - and that's why it's
    not more common.
```


## So how close are git and Github?

* Based on the above, quite close.
* One person who knows it has to set it up.
* Then many people can edit from the web browser.
* **But is it usable enough?**


```{admonition} Any experiences?

* Any comments of the above?
```

## Rest of this talk

* Use this talk itself as an example.
* Walk through doing some practical thing on a Github-hosted site.
* See what the audience asks.
* Discuss what else is needed.

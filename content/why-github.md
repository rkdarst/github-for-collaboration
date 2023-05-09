# Why git / Github?

## What are git / Github?

You *don't* need to know how each of these work individually.  But
here's our overall map:

* **git:** a version control system.  It tracks changes.
  * There are many different programs that use the same format.
  * git dominates the world now.
  * It's a great skill for CVs and stuff.
  * All open-source.
* **GitHub: One website for hosting and sharing git repositories**
  * Also dominates the world (but many competitors)
  * Provides a lot of nice stuff for free
  * Proprietary (not open-source)
* **Markdown:** a simpler way to write basic markup like **bold**,
  **italics**, and [links](https://scicomp.aalto.fi/)
  * [View a bigger example on GitHub](https://github.com/rkdarst/github-for-collaboration/blob/main/content/why-github.md?plain=1#L1)
* **Sphinx (and many other tools):** convert source markdown (and
  others) into a web site.
* **Github Pages:** makes websites available on the web.


## Why not Github?
* Github is proprietary and not open-source
* Controlled by just one company (Microsoft): vendor lock-in, it's
  going to be bad for us some day.
* It's very popular, and this dominance is not good for the world
* Some promotion of this idea: <https://giveupgithub.org/>

Alternatives exist: GitLab is the most popular one (gitlab.org and
also organizations can self-host, some universities do:
<https://version.aalto.fi>)

## Why git / Github ?  Comparison to our list

Using best practices of git + GitHub + myst-markdown + Sphinx + GitHub
pages, we can get:

```{list-table}
:header-rows: 1

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
   `70a98a7f3dbace9e8518723f5e6bfb252440a263` (or short form,
   `70a98a7`).

    This will never change.

    This is actually searchable on Github: [link](https://github.com/search?q=70a98a7f3dbace9e8518723f5e6bfb252440a263&type=commits)
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

    **This is the big question.  Historically, "no" - and that's why it's
    not more common.**
```


## So how close are git and Github?

* Based on the above, we are quite close.
* As long as one person knows how to set it up and provide help.
* Then many people can edit from the web browser.
* **But is it usable enough?  Can anyone manage to use this?**


```{admonition} Any experiences?

* Any comments of the above?
```

## Rest of this talk

* Use this talk itself as an example: it is hosted on GitHub
* Walk through doing some practical edits.
* See what else the audience asks if we can do.
* Discuss how to improve things in the future.
* (do those things)
* (start using this somewhere?)

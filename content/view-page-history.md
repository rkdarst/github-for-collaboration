# View history of a single page

## Background

Git stores *all* history of all past edits, and this is very useful.
You can:

* See when something was last updated
* See who last updated each part
* See what the update is (precisely - the *diff*)
* See a message about why it was done.

You need to find where it is on Github.  Many websites hosted there
have an "Edit on Github", but sometimes you have to search for the file.


## How to

Go to the example page: <https://scicomp.aalto.fi/data/>.

Find the right file in Github:

* Click the `Edit on GitHub` button
* Or find the repository and navigate to the file you want.

![Edit on Github in the sidebar](img/edit-on-github.png)

Then try examining it:

* Find `History`. [example](https://github.com/rkdarst/github-for-collaboration/commits/main/content/how-to-edit.md)
* Try clicking `Blame` (left side, down a bit).  This is not a good
  term, but shows exactly when each part was changed. [example](https://github.com/AaltoSciComp/scicomp-docs/blame/master/triton/tut/array.rst)
* Click `Code` or `<>` to see the raw source.  This is what it looks like
  "under the hood".  [example](https://github.com/rkdarst/github-for-collaboration/blob/main/content/how-to-edit.md?plain=1)


Most of these buttons found at the top of pageshere:
![Screenshot of Github with the buttons](img/code-viewing.png)


## What we got

We can really see in depth who has contributed to this - useful if we
want to know who to talk to about things or knowing if something is
intentional.

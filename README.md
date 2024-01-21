# Simple template for a CSL personal website

Huge thanks to [Mark Buckler](http://www.markbuckler.com/) for sharing
his website with me - this template was directly lifted from his site.

You can see a Github repo for Mark's website [here](https://github.com/mbuckler/personal-website)

Many thanks to [Skand Hurkat](https://people.ece.cornell.edu/skand/) for his
[rework of the Hugo Academic Theme](https://github.com/skandhurkat/hugo-theme-cornellcsl)

## Getting Started ##

After cloning, use [Git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
to clone Skand's CSL Academic Theme. Run the following inside the cloned directory:

    git submodule init
    git submodule update

## Basic Guide ##

The layout of the homepage is configured in **config.toml**.
All content is inside the **content** directory. Using Talks as an example:

* **content/home/about.md** contains the frontpage bio
* **content/home/talk.md** contains layouts for the publications panel
* **content/talk/my_talk.md** contains content for a talk

So to add a new talk, create a new .md in the content/talk/ directory.

```hugo server``` will build and test the website.

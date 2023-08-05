---
marp: true
---

# MUSA GitHub Workshop
_Set up your portfolio site on GitHub Pages_

---

## Goals

The **outcome** of this workshop is that you will leave here with a portfolio site hosted on GitHub Pages that you know how to add entries to so that as you complete projects in the MUSA program you can add them to your portfolio.

However, the **purpose** of this workshop is to introduce you to the concept of version control, and to give you a basic understanding of how to use git and GitHub.

---

## Outline

0.  What is a version control system? Why should we use one?
1.  What is git? What is GitHub?
2.  Getting started with git and GitHub
    - Signing up for an account
    - Installing a git client
3.  Creating a portfolio

---

## What is a version control system?

The purpose of a version control system is to make your coding life easier and more organized:

- A *version control system* (**VCS** -- also called a *source code manager* or **SCM**) is a tool that helps you manage changes to a set of files over time.
- It allows you to track changes to files, quickly compare different versions of files, and to revert to previous versions or sync new changes into those files.

**Version control is time-travel enabling a super-power 🦸🏾‍♀️!**

---

## Direct benefits of version control

- **Tracking changes:** A VCS monitors the changes you make to your code. Instead of saving new versions of your files like "script_final," "script_final_revised," and so on (which we've all done 😒), a VCS keeps a detailed record of each change, and allows you to add annotations to your changes like "added an introduction," "changed the main function's name," and so forth.
- **Collaboration:** If you're working with colleagues on the same code or sharing your code with others, a VCS helps everyone stay on the same page. It ensures that everyone can work on the code at the same time without messing things up. It's akin to working with others in the same Google Doc, rather than emailing around different versions of a Word document.

---

## ... and a few indirect benefits of version control

- **Backup:** It's like a safety net. If you accidentally delete something important or your code becomes a big mess, you can go back to a previous version.

- **Experimentation:** Want to try a new idea without destroying your current work? A VCS lets you create a new "branch" to experiment without affecting the main code.

- **Documentation:** It's a log of your coding journey. You can see why you made certain changes, which can be really helpful when you revisit your code later.

---

## Why git, and why GitHub?

There are other VC systems -- `svn`, `hg`, even some niche ones (like Piper, which Google uses internally). Is `git` the best VCS? That's debatable, and a matter of opinion.

But it's definitely the most popular by far.

<!--
The first version of git was released in 2005.

In 2009, most of the projects that I was working on were tracked in Subversion. One was tracked in Mercurial and one in CVS.

By 2014, all of the projects that I was working on were tracked in Git.

-->

---

## Why is `git` the most popular VCS?

When git debuted it had several things going for it:
* **It was invented by Linus Torvalds**, the inventor of Linux. There's not much stronger star power you could have for a tool that developers use.
* **Merging became magic ✨**. `git` was -- and is -- really smart about merging code changes from different collaborators together.
  
  <!-- In time, many of you will come to have complex feelings toward merging code -- among those feelings will be anxiety, anger, perhaps fear. However, you have to understand that it used to be so much worse. -->
  
  `git` handles most merge situations seamlessly. ... But so do other tools that were invented around the same time (like `hg` or `bzr`). So the questions remains: why `git`?

I think the thing that pushed `git` over the top was...

---

## GitHub

Launched in 2008.

- It created tools for the social aspects of collaboration (managing code change permissions, requesting code merges), ensuring strong network effects, while relying on git for the technical aspects (merging).
- It stayed ahead of its competition (like BitBucket) by adding features that developers wanted (like GitHub Pages, which we'll use today), and by more effective corporate strategy, gaining favor among both open source and startup communities.

Remember this about all the technologies you learn here:
- Try to understand the ideas behind the tech you use as well as the tech itself.

---

### Sample GitHub version history
![Sample GitHub version history -- bg right contain](figures/sample-github-version-history.png)

---

# Let's get started!

---

To use GitHub [well] you need two components:
- An account on the GitHub website
- A `git` client installed on your computer

<!-- You can use GitHub without a local git client, just by making changes directly on the GitHub website, and for some changes this is a reasonable thing to do. However, very often, it is not. -->

---

Common actions:
- Fork a repository
- Clone a repository
- Create a branch
- Make and stage changes
- Commit changes
- Push changes
- Submit a pull request
- Merge a pull request
- Checkout a branch
# OSDC 2023.03 Azrieli

* [site](https://osdc.code-maven.com/osdc-2023-03-azrieli/)

* Start day: 2023.03.09
* Meetings: Every Thursday 12:15-14:45

## TOC

* [Session 1: Welcome, Version Control, Journal, Slack](#session-1-welcome-version-control-journal-slack)
* [Assignment 1](#assignment-1)
* [Session 2: Finding projects, git workflows, ci, yaml](#session-2-finding-projects-git-workflows-ci-yaml)
* [Assignment 2](#assignment-2)
* [Assignment 3](#assignment-3)
* [Next](#next)

## Videos

* [Playlist](https://www.youtube.com/playlist?list=PLm2NBp4tb5F0L6SmPx17K5bQM3Ha62DHp)

## Session 1: Welcome, Version Control, Journal, Slack

* Welcome

* About the course:
    * Goal: Become familiar with tools and processes used for software development both in the industry and in the academic institutions through contribution to open source projects.
    * List of tools we learn, they are all used in both academy and corporation, they could be used better in both places.
    * Overview of the [course](https://osdc.code-maven.com/)
        * Slack
        * git
        * GitHub
            * Issues
            * Pull Request
            * Pages
            * Actions
        * (GitLab)
        * Markdown (journal, issues, etc.)
        * Docker
        * Testing
        * Static analysis
    * End results:
        * Blog posts (journal entries)
        * Personal web site
        * Issues (tickets) opened on various projects
        * Pull-Requests sent to various projects
        * Development of a personal open source project

* About myself:
    * Self employed
    * Training
    * Introducing testing, CI etc. to teams in corporations.

* Assignments:
    * Will be in some public GitHub or GitLab repositories.
    * At the end of each assignment you'll write a report - a blog post / journal entry.
    * You will add the link of your blog post to your personal JSON file and send a Pull-Request with the change. (We'll learn these soon)
    * Video timstamping: Every week two people have to "timestamp" the videos. You can pick a video you'd like to do. If noone volunteers to do one of the videos I'll pick from the names so by the end of the semester everyone will do approximately the same number of videos.
    * First few assignments will be to my projects. This allows for quick feedback and integration.
    * Then to each others projects. This still allows for quick feedback.
    * Then we'll find you open source projects maintained by other people. For these I might be able to give feedback, but I cannot integrate them.
* Grades:
    * Grades are based on the work done during the course.
    * There is no end-project or exam at the end.
    * Each week you'll get a grade of 0-100 and we'll have an average of them at the end of the semester.

* How and why to blog/journal?
    * [DEV.to](https://dev.to/)
    * Use [Markdown](https://en.wikipedia.org/wiki/Markdown).
    * Use visual editor of DEV (Switch at Customization / Writing)
    * Create series.
    * Add `#osdc` tag
    * The importance of linking and link anchors.

* Why use version control?
* What is [JSON](https://www.json.org/).
* Pull request to add JSON, show drawing.
* Use the cm-demo account to add enty to participant.

* About GitHub Actions: they are programs triggered by some action. In this case by a pull request.

* [Video 1-1](https://youtu.be/uiJjhFW6TH4): (Yael Levy)
    * 00:00 About the course
    * 04:28 Overview of the course
    * 18:46 About Gabor Szabo
    * 20:15 Assighnments
    * 23:05 Video timestamping
    * 31:20 Grades
    * 35:20 Blog posting
    * 35:49 Dev.to
    * 36:15 Post editor
    * 39:18 Published
    * 39:39 Description
    * 40:10 Tags
    * 48:28 Text in markdown

* [Video 1-2](https://youtu.be/-euAGPpymjQ): (Eliyahou Levy)
    * 00:00 Forem issues to solve bug
    * 06:50 Inbound links
    * 08:44 Version control
    * 11:22 Json
    * 14:36 Add json participant by pull request
    * 16:30 Fork
    * 25:35 Create pull request
    * 27:40 Workflow
    * 28:40 Approve pull request
    * 30:00 Error handling
    * 36:30 Sqush and merge pull request
    * 37:43 Actions
    * 39:02 Exercise definition-send pull request
    * 42:50 Add comment

## Assignment 1

* Create GitHub repository if you don't have one yet.
* Add an image or an avatar to your GitHub account.
* Add your JSON to our repository to the `participants/' folder.
* List interesting projects in the JSON file.
* Follow this git repository. Follow a number of other GitHub repositories that you find interesting or that you use.
* Write a blog post about this on [DEV.to](https://dev.to/)
* Include the link of the article in the JSON file.

* Dead-line: 2023.03.14 midnight.


## Session 2: Finding projects, git workflows, ci, yaml

2023.03.16 12:15-14:30

* Go over all the PRs people opened and the Issue I opened on our GitHub repository.
    * Fix issue in PR instead of opening new one (show it)
    * Mentioning commits in issues and issues in commits.
* Blogging: linking, more details!

* Ask to get the Video timestamping earlier.

* Show how to follow projects on GitHub to get notifications.

* The structure of a Github URL : https://github.com/(username|organization)

* How to find a git repo of a project?
    * [Perl MetaCPAN](https://metacpan.org/)
    * [Python PyPI](https://pypi.org/)
    * [3rd party package registries](https://code-maven.com/package-registry)
    * Google search?

* What are [yaml](https://yaml.org/) files See the [repo](https://github.com/OSDC-Code-Maven/open-source-by-organizations/) and the [site](https://osdc.code-maven.com/)

* [Video 2-1](https://youtu.be/Ydbkk1ZKDLk): (Freddy Adiv)
   * 00:00 Recap of last session
   * 07:25 Dev.to - navigation using tags
   * 15:57 Opening issues in git
   * 19:00 Issues and pull requests
   * 30:55 Sample for real project interaction for Forem
   * 42:10 Git project concepts, Forking and comminting

* [Video 2-2](https://youtu.be/WuKd66rLTKw): (Freddy Adiv)
   * 00:00 Locking files - pros and cons
   * 02:50 Following a project and notifications in Git
   * 05:35 Ranking mechanizm of projects
   * 06:10 Sturcture of Git URLs, projects/ organizations/ repos
   * 15:01 3rd party packages registry
   * 17:45 Open source by orgznizations
   * 21:35 YAML file format
   * 31:15 Adding a new organization using YAML
   * 50:22 Assignments for next week

## Assignment 2

* Add (more) projects you are interested in.
* Follow our project
* Follow my projects
* Follow each other's projects.

* Convert 5 more organizations to yaml files.
* Find more organizations. (more github organizations belonging to governments, universities, or corporations that are not even in the md files yet. I realize that converting the md files to yaml files should be probably the priority for this project so it might be better to do a few more of that.)
* Write a blog post (tag with #osdc, notes, links, etc.)
* Send a PR to add your blog post to your JSON file.

* Dead-line: 2023.03.21 midnight.

## Session 3 2023.03.23 13:30-14:30

* Create Github pages.
* Markdown.

* Introduce git client.
    * Setup local git configure, clone, add, commit, etc.

* Download and install the git client from [git-scm](https://git-scm.com/)
* In Windows, start the git-bash application

* On Github create the USERNAME.github.io repository (with your USERNAME)


```
git clone git@github.com:cm-demo/cm-demo.github.io.git
cd cm-demo.github.io
```

```
mkdir docs
    Create the file docs/index.md
git add .
git commit -m "first file"
```


Configure the git client (if it is not configured yet)

```
git config --global --add user.name "Foo Bar"
git config --global --add user.email foo@bar.com

cat ~/.gitconfig
```

Create private/public key pair. put the public key in your github account.

```
ssh-keygen
```

```
git commit --amend --reset-author -m "first commit"
```

```
git log
```


```
git status
git add docs/index.md
git commit -m "add more content"
git push
```

* [Video 1](https://youtu.be/s4N0CGTP-GA): Ran Moshe


## Assignment 3

* Create a web site using GitHub pages, with cv, image, projects. Link to the course site, link to your blog. Use this to show a lot more interesting information about yourself to both your future employer, but also to friends and family. Check out what others in the [other course](https://osdc.code-maven.com/instances) did for inspiration.
* Write a blog post about what you did, link it to the course web site, to your own new web site, to the pull-requests you made.
* Update your JSON file with the new blog post and also add an entry of `"githu_page": true` to your JSON file if it is not there yet.


* Dead-line: 2023.03.28 midnight.

## Next:

## Session 4 2023.03.30 13:30-14:30

* Comments:
    * Send the deletition and addition in the same pull-request. Even better, in the same commit
    * There were conflicts as the same person changed subsequent lines in separate changes.
* Explain why linking and the anchors are important.
* git-scm configure the default editor


* Video 1: Ran Moshe

## Session 5 2023.04.13 12:15-14:30

* Video 1: Ran Moshe
* Video 2: Ran Moshe

## Session 6 2023.04.20 12:15-14:30

* Video 1:
* Video 2:

## Session 7 2023.04.27 12:15-14:30

* Video 1:
* Video 2:

## Session 8 2023.05.04 12:15-14:30

* Video 1:
* Video 2:

## Session 9 2023.05.11 12:15-14:30

* Video 1:
* Video 2:

## Session 10 2023.06.01 12:15-14:30

* Video 1:
* Video 2:

## Session 11 2023.06.08 12:15-14:30

* Video 1:
* Video 2:

## Session 12 2023.06.15 12:15-14:30

* Video 1:
* Video 2:

## Session 13 2023.06.22 12:15-14:30

* Video 1:
* Video 2:


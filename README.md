# OSDC 2023.03 Azrieli

* [site](https://osdc.code-maven.com/osdc-2023-03-azrieli/)

* Start day: 2023.03.09
* Meetings: Every Thursday 12:15-14:45

## TOC

* [Session 1: Welcome, Version Control, Journal, Slack](#session-1-welcome-version-control-journal-slack)
* [Assignment 1](#assignment-1)
* [Session 2: Finding projects, git workflows, ci, yaml](#session-2-finding-projects-git-workflows-ci-yaml)
* [Assignment 2](#assignment-2)
* [Session 3: Github Pages; Markdown](#session-3-github-pages-markdown)
* [Assignment 3](#assignment-3)
* [Session 4: PyDigger, updating meta data of a Python project](#session-4-pydigger-updating-meta-data-of-a-python-project)
* [Assignment 4](#assignment-4)
* [Session 5](#session-5)
* [Assignment 5](#assignment-5)
* [Session 6: Docker](#session-6-docker)
* [Assignment 6](#assignment-6)
* [Session 7: Docker, part 2](#session-7-docker-part-2)
* [Session 8: git-scm on Windows, GitHub contribution workflow](#session-8-git-scm-on-windows-github-contribution-workflow)
* [Session 9: GitHub Actions](#session-9-github-actions)

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
    * Video timestamping: Every week two people have to "timestamp" the videos. You can pick a video you'd like to do. If no-one volunteers to do one of the videos I'll pick from the names so by the end of the semester everyone will do approximately the same number of videos.
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
* Use the cm-demo account to add entry to participant.

* About GitHub Actions: they are programs triggered by some action. In this case by a pull request.

* [Video 1-1](https://youtu.be/uiJjhFW6TH4): (Yael Levy)
    * 00:00 About the course
    * 04:28 Overview of the course
    * 18:46 About Gabor Szabo
    * 20:15 Assignments
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
    * 36:30 Squash and merge pull request
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
   * 42:10 Git project concepts, Forking and committing

* [Video 2-2](https://youtu.be/WuKd66rLTKw): (Freddy Adiv)
   * 00:00 Locking files - pros and cons
   * 02:50 Following a project and notifications in Git
   * 05:35 Ranking mechanism of projects
   * 06:10 Structure of Git URLs, projects/ organizations/ repos
   * 15:01 3rd party packages registry
   * 17:45 Open source by organizations
   * 21:35 YAML file format
   * 31:15 Adding a new organization using YAML
   * 50:22 Assignments

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

## Session 3: Github Pages; Markdown

Date: 2023.03.23 13:30-14:30

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

* [Video 3-1](https://youtu.be/s4N0CGTP-GA): Ran Moshe
   * 00:00 Windows - Oracle VM VirtualeBox
   * 07:40 Back to local linux PC
   * 07:50 Create repository for Github pages site (on Github)
   * 09:11 Clone for create repository locally (on PC)
   * 13:00 Download and install the git client from git-scm
   * 15:05 In Windows, git-bash application
   * 17:24 Setup local git configure (add, commit, config, etc.)
   * 29:35 Create private/public key pair
   * 35:10 Push changes (git push)
   * 39:45 Config github.io repository (on Github-settings)
   * 42:38 Creating the Github page using Markdown
   * 44:30 Push more changes (git status, add, commit, log. etc.)
   * 47:50 The Github page after changes
   * 48:45 Adding images to our Github page (add another file)
   * 52:00 Push images and more changes (git status, add, commit, etc.)
   * 54:23 Jekyll (from Markdown to Github)
   * 55:30 Assignments

## Assignment 3

* Create a web site using GitHub pages, with cv, image, projects. Link to the course site, link to your blog. Use this to show a lot more interesting information about yourself to both your future employer, but also to friends and family. Check out what others in the [other course](https://osdc.code-maven.com/instances) did for inspiration.
* Write a blog post about what you did, link it to the course web site, to your own new web site, to the pull-requests you made.
* Update your JSON file with the new blog post and also add an entry of `"github_page": true` to your JSON file if it is not there yet.


* Dead-line: 2023.03.28 midnight.


## Session 4: PyDigger, updating meta data of a Python project

Date: 2023.03.30 13:30-14:30

* We looked at the [PyDigger](https://pydigger.com/) web site and the [Stats](https://pydigger.com/stats) page from where we had links to
* projects [have link to VCS but no license field](https://pydigger.com/search/has-vcs-no-license)
* projects [have link to VCS but no author field](https://pydigger.com/search/has-vcs-no-author)
* projects [have link to VCS but no summary](https://pydigger.com/search/has-vcs-no-summary)
* projects where PyDigger [did not find VCS](https://pydigger.com/search/no-vcs)

* We looked at pypi page of [numpy](https://pypi.org/project/numpy/)
* We sent [this Pull-Request](https://github.com/vangheem/mr.flagly/pull/1)

* We found that the [mrflagly](https://pydigger.com/pypi/mrflagly) project was missing the author field from the meta-data.
* We went to its GitHub repository, found that it was using pyproject.toml and found the name and email of the author.
* [pyproject.toml file specification](https://python-poetry.org/docs/pyproject/)

* We also looked at [pglib](https://pydigger.com/pypi/pglib) and saw that it is hosted on GitLab.

* The [licenses page](https://pydigger.com/licenses) on PyDigger was [fixed](https://github.com/szabgab/pydigger.com/commit/bfc242d95e9ae3c968b35b6f0910ad7c8c7ad6af) a few hours before the lecture.
* OSI approved [Open Source licenses](https://opensource.org/licenses/).

* I mentioned the recommended books listed at the bottom of the OSDC main page. Especially I mentioned the one I am reading now [Uncurled by Daniel Stenberg, author of curl](https://un.curl.dev/).

* [Video 4-1](https://youtu.be/xIP13AK4usI): Ran Moshe
   * 00:00 PyDigger and pypi.org (Introduction)
   * 03:00 last updates of pypi (show in CLI- use grep & ack to get the relevant url) 
   * 04:45 PyDigger-Statistics
   * 06:30 No VCS (PyDigger-Statistics)
   * 07:50 CI (PyDigger-Statistics)
   * 09:30 Has VCS (PyDigger-Statistics)
   * 11:05 Has VCS license (PyDigger-Statistics)
   * 12:35 Has VCS author (PyDigger-Statistics)
   * 13:30 mrflalgy (example-Has VCS but no author)
   * 14:40 pyproject.toml author field
   * 20:00 Explain about pyproject.toml file & sending PR (mrflalgy- example)
   * 32:20 types-pytz (example-Has VCS but no author)
   * 34:50 pglib (example-Has VCS but no author (GitLab & setup.cfg file))
   * 37:00 Has VCS summary (PyDigger-Statistics)
   * 41:00 Adyen (example-Has VCS but no license)
   * 41:56 Details Licenses page (PyDigger-Statistics)
   * 45:10 Recommended books listed
   * 46:10 open source initiative
   * 51:00 searchkit (example-no VCS)
   * 55:15 Assignments



## Assignment 4

Find 5 (was 10) projects via [PyDigger](https://pydigger.com/) that have no author, not license, or no VCS. Add the missing information and send a pull-request. In the Pull-Request mention that you found the package missing this information via [PyDigger](https://pydigger.com/), that you are sending it as part of the [OSDC](https://osdc.code-maven.com/), and mention me as well: @szabgab

* Dead-line: 2023.03.28 midnight.


## Session 5

Date: 2023.04.13 12:15-14:30

* We need Better projects (e.g. projects you use at your work) we discussed what are GitHub organizations and what are repositories.

* How to update a PR that was not accepted yet.
    * We created a [new PR](https://github.com/OSDC-Code-Maven/osdc-2023-03-azrieli/pulls) via the Web interface of GitHub that failed the CI and the owner also commented on it.
    * Then we found the fork and the branch in the fork and updated the file.
    * It automatically updated the PR and started the CI again.

* We discussed [this PR](https://github.com/iterative/dvc-data/pull/340) that needs a fix.

* We discussed (in theory) how to handle a case when we plan to create a change for an open source project that might take us a month.
    * How to avoid breakage caused by changes created on the main project that conflict with the change we make.
    * The answer is that we cannot totally avoid those conflicts, but we can reduce their impact by communication and by frequently aligning our work with that of the main branch.
    * I mentioned `rebase`. We will see it in action later.
* We briefly discussed if people get paid for their open source work.

* [Video 5-1](https://youtu.be/Im5vaQ6CJqo): Ran Moshe
   * 00:00 Meetups
   * 03:20 Meetup - Code Mavens
   * 04:45 Meetup - PyWeb-IL
   * 06:50 Find a better open source projects
   * 09:00 Find a better open source projects - metacpan
   * 15:40 Find a better open source projects - perl5-dbi
   * 17:05 Find a better open source projects - forem
   * 18:50 Find a better open source projects - psf/requests
   * 20:55 requirements.txt file
   * 28:20 dependabot.yml file
   * 34:00 constraints.txt file
   * 36:40 Find better open source projects - pyflakes
   * 39:55 How to update a PR that was not accepted yet
   * 44:20 How to update a PR that was not accepted yet - create a new PR

* [Video 5-2](https://youtu.be/gzbDrmieM7k): Ran Moshe
   * 00:00 How to update a PR that was not accepted yet - CI failed and the owner commented
   * 03:00 How to update a PR that was not accepted yet - find fork and branch to update PR
   * 05:50 How to update a PR that was not accepted yet - automatically updated the PR & started the CI again.
   * 11:55 Explain for failed git push
   * 17:00 How to avoid breakage caused by changes created on the main project by us - in organizations
   * 22:05 How to avoid breakage caused by changes created on the main project by us - in open source project
   * 34:20 rebase
   * 43:00 Assignments
   * 44:00 Assignments - projects in szabgab, OSDC-Code-Maven, Kantoniko and GitHub Topic
   * 51:40 Do people get paid for their open source work
   * 57:00 Previous and future assignments explained

## Assignment 5

* Fix the PRs that are problematic. (Where the CI failed or where the owner asked for an update)
* Add better projects to your JSON (that are not ours)
* Send more pull-requests, preferably not just for the `author` filed to make it more interesting and more challenging to you too.
* Ideas for PR besides the one we discussed in the previous session:
    * Makes sure the README (or CONTRIBUTION) file in a project has clear instructions how to set up the local development environment and how to run the tests locally. (pick a project that has no, or very few stars)
    * If you can find any open source project with something you feel you can already fix, feel free to do that.
    * Check out my projects in [szabgab](https://github.com/szabgab/) or [OSDC-Code-Maven](https://github.com/OSDC-Code-Maven/) or [Kantoniko](https://github.com/kantoniko/) Feel free to send a PR for them, or even just to discuss open issues.
* In those new PRs, include a better explanation of why this change is useful. If you are not sure what to write, ask on our Slack.

* Dead-line: 2023.04.30


## Session 6: Docker

* Date: 2023.04.20 12:15-14:30

* Languages the students mentioned: Python, Java, JavaScript, C#, Also https://openui5.org/ was mentioned.

* Docker images:
    * [Node JavaScript](https://hub.docker.com/_/node)
    * [Python](https://hub.docker.com/_/python)
    * [R-Base](https://hub.docker.com/_/r-base)
    * [Java OpenJDK](https://hub.docker.com/_/openjdk)
    * [Mono C#](https://hub.docker.com/_/mono)
    * [Mono C#](https://hub.docker.com/r/esolang/csharp)
    * [PHP](https://hub.docker.com/_/php)

* We went over the slides of [Learning Linux in a Docker container](https://code-maven.com/slides/linux-docker/) up before the slide about CentOS.
* Then we saw a few examples of [Open source project in Docker](https://code-maven.com/slides/docker/open-source)

* [Source of all the slides](https://github.com/szabgab/slides)

* [Video 6-1](https://youtu.be/0GAyyX1UaqQ): Doron Chapnitsky
   * 00:00 Coding language we use at work
   * 03:00 Introduction to Docker
   * 15:00 Linux distributions and structure
   * 18:00 Docker installation
   * 21:00 Docker image
   * 29:00 docker run command
   * 32:00 docker ps & docker rm commands
   * 38:00 root in Docker
   * 44:00 Common linux commands
   * 59:00 apt-get & nano & htop commands

* [Video 6-2](https://youtu.be/4_A2K6oLV0s): Doron Chapnitsky
   * 00:00 Python Flask container and running tests
   * 21:30 Coding languages containers
   * 28:00 More about Flask
   * 31:00 Assignments
   * 40:00 bridgeql repository example



## Assignment 6

* Setup the local development environment of 5 open source projects - in your preferred programming language.
    * They could taken from the ones where you already sent a PR with some other change that was already accepted.
* Describe the steps and send a PR to add them to the slides: [Source of the Open Source examples](https://github.com/szabgab/slides/blob/main/docker/opensource.md)
* Send PR to the project itself adding the same information to its README file.
    * Think about the point of view of the developer of the project. Make the title and the explanation in the PR clear as why s/he would want to accept this.
* Write a blog post describing your experience and what you learned.

* Dead-line: 2023.05.02


## Session 7: Docker, part 2

Date: 2023.04.27 12:15-14:30

* Write blog posts that have actual text that a random person can read, not just a bunch of links.
* Explain what you learned from the lecture, from the assignments, and from the way the project owners responded to your PRs.
* Include links to the issues you opened, the pull-requests you sent.
* Follow-up on the issues and pull-requests if the owner asks for an updates. We already learned *how* to update a PR.
* Use Markdown to add titles to the links so they won't be just URLs pasted.
* See for example [TD](https://dev.to/tdaw)  (OSD700)
* [blog posts](https://osdc.code-maven.com/blogs)

* [GitHub + DEV Hackathon](https://dev.to/devteam/announcing-the-github-dev-2023-hackathon-4ocn)

* [tomlkit](https://github.com/sdispater/tomlkit)

* [Video 7-1](https://youtu.be/CPpneLuU4aA): Freddy
   * 00:00 Docker with CentOS
   * 22:13 Installing CentOS packages
   * 30:35 Bash Configuration
   * 31:16 Adding and changing users
   * 40:40 Which command
   * 49:40 Grep command
   * 01:01:10 Find
   * 01:02:15 Manual pages
   * 01:03:30 Pipelines

* [Video 7-2](https://youtu.be/TrnTCjYKWIs): Freddy
   * 00:00 Pipelines continued
   * 15:38 Creating container for Python's tomlkit
   * 28:10 Running tests
   * 41:30 Creating image from container


## Assignment 7

TBD.

## Session 8: git-scm on Windows, GitHub contribution workflow

Date: 2023.05.04 12:15-14:30

* git-scm configure the default editor
* Windows install (again), process of clone/fork/pull
* [workflows](https://code-maven.com/slides/git/collection-of-git-workflows)

* git-scm
* ~/.gitconfig      global config
* .git/config       config for each repository

* ssh-keygen
* ls -l ~/.ssh/
* cat ~/.ssh/id_ras.pub

```
git init
git add
git commit
```

* Create repo in GitHub and follow the instructions there to push out the repository

```
git clone
git checkout -b branch-name
git add
git commit
git push


git checkout main
git pull origin main
git checkout branch-name
git rebase main
git push --force
```

A few notes for he lecture yesterday:

For each thing you change create a separate branch from the default branch (usually "master" or "main").
So for example yesterday Ran Moshe found out that the generate command in the [README](https://github.com/OSDC-Code-Maven/open-source-by-organizations) does not work.
First of all Ran, you should have opened the two issues right away

1. with the error message for this command `python generate.py github/bioinform.yaml github/calgaryml.yaml` failing
2. that the python generate.py` is failing that you already opened since then: https://github.com/OSDC-Code-Maven/open-source-by-organizations/issues/79

Then when fixing you create a branch and sent a [PR to fix the first issue](https://github.com/OSDC-Code-Maven/open-source-by-organizations/pull/80) and I have accepted it.
Already before I accepted it you could go back to the "main" branch and create a new branch for some other changes you might want to make.

Now that I've already accepted the PR, you can update your main branch from my main branch (as I showed yesterday) and then
1. start your new branch from there.
1. if you already have a branch that you started from main you can rebase that branch to "main" and be up to date (as we saw yesterday)


* [Video 8-1](https://youtu.be/aheLynn8QI8): Yael
* 00:00 Topics we will talk about
* 04:35 git client installation(git-scm)
* 12:20 bash window basic commands
* 15:54 create new file
* 17:35 find command
* 20:00 edit file with vim
* 21:04 create project
* 21:45 readme file
* 23:29 git init
* 24:25 git add
* 25:00 identification user config
* 28:58 commit Author
* 32:26 configuration commands
* 35:00 git commit add README
* 36:54 github create new repository
* 38:46 git remote add
* 44:16 git branch main
* 45:16 public key
* 50:00 push
* 53:00 repository permissions
* 54:30 git push -u
* [Video 8-2](https://youtu.be/Opa8_QL3GV0): Eliyahou
* 00:00 delete repository
* 03:20 git clone
* 08:05 create new branch
* 09:50 create new file
* 10:58 git add
* 12:00 git log
* 13:25 create fork
* 15:15 git push
* 19:00 merge
* 20:34 send PR
* 22:30 fix PR
* 25:32 update readme file
* 28:56 rebase / merge
* 36:34 reset
* 37:28 push rejected
* 39:31 force push
* 43:42 merge
* 46:10 delete last commit
* 47:37 rebase benefits
* 51:30 Assignment

## Assignment 8

* Take one of the following projects, set up the local development environment, work on one of the issues, send a PR
    * https://osdc.code-maven.com/
    * https://osdc.code-maven.com/open-source-by-organizations/
    * https://kantoniko.com/
    * https://pydigger.com/
    * https://cpan-digger.perlmaven.com/
    * https://ruby-digger.code-maven.com/

## Session 9: GitHub Actions

Date: 2023.05.11 12:15-14:30

* [slides: Continuous Integration for GitHub projects](https://code-maven.com/slides/github-ci/)
* [Collection of official GitHub Actions](https://github.com/actions)

* [GitHub Action to generate the site of the course](https://github.com/osdc-code-maven/osdc-site-generator)
* [GitHub Actions examples](https://code-maven.com/github-actions)
* [GitHub action for Perl library to access Postgres](https://github.com/bucardo/dbdpg/pull/115/files)
* [Pydigger has GitHub but no CI](https://pydigger.com/search/has-github-no-ci)
* [capturecli, simple python project with CI](https://github.com/szabgab/capturecli)
* [Video: GitHub Actions to generate complex static web](https://workshops.code-maven.com/github-actions-to-generate-complex-static-web-sites)
* [Video: GitHub REST AP and GraphQL API](https://workshops.code-maven.com/github-rest-api-and-graphql-api)

* [Video 9-1](https://youtu.be/7ulEqu7Rr8I): Doron Chapnitsky
  * 00:00 Introduction to CI
  * 07:00 Introduction to Github Actions
  * 14:00 Simple workflow example and implementation
  * 35:00 Ubuntu, macOS and Windows examples
  * 38:30 Triggering jobs
  * 44:00 Github environment variables
  * 48:00 Github actions repositories
  * 55:00 Github matrix strategy

* [Video 9-2](https://youtu.be/PtnGFykK8jc): Doron Chapnitsky
  * 00:00 Github matrix strategy recap
  * 03:20 How to use Github environment variables and conditions
  * 17:00 Github Actions collection
  * 18:20 Linux commands with Github Actions
  * 22:30 Github actions artifact
  * 27:00 Github actions services and DB
  * 49:50 Home assignment - create CI for a repository

## Assignment 9

Find a project that has some tests but does not have any type of continuous integration. Set up GitHub Action to run the tests.
Before you send the PR to the project owner show the results to @szabgab.

## Session 10: Dockerfile; Playground; GitHub Actions for Java, Open Source

Date: 2023.06.01 12:15-14:30

* [OSDC Site generator](https://github.com/OSDC-Code-Maven/osdc-site-generator)
* Earlier we saw how to run a docker container, install things and then build a Docker image
* Today we'll see how to build a Docker image using Dockerfile https://code-maven.com/slides/docker/docker-empty-ubuntu
* [Creating a file on a mounted volume in Docker as the external user (and not as root)](https://code-maven.com/creating-file-in-docker-as-the-external-user)
* [Dockerfile of OSDC Site Generator](https://github.com/OSDC-Code-Maven/osdc-site-generator/blob/v1/Dockerfile)
* Then how the [CPAN Digger](https://cpan-digger.perlmaven.com/) project uses a Docker image
* Then we'll see the [Playground](https://github.com/szabgab/playground) docker image
* GitHub Action for Java Projects
    * [Explore projects](https://github.com/explore)
    * [Java](https://github.com/topics/java?l=java)
    * We looked at this [guava](https://github.com/google/guava)
    * [styfle/cancel-workflow-action](https://github.com/styfle/cancel-workflow-action)
    * [setup-java action](https://github.com/actions/setup-java)


* Briefly: why companies and people write open source and Quality of open source code: Test coverage on [CPAN Digger](https://cpan-digger.perlmaven.com/recent).

* [Video 10-1](https://youtu.be/GdXP0uSRK4Y): Zohar Asulin
   * 00:00 convert Markdown to html
   * 04:26 GITHUB ACTION
   * 08:55 Dockerfile
   * 10:24 build a Docker image using Dockerfile
   * 21:29 CMD  echo HELLO WORLD
   * 29:19 ubuntu htop
   * 36:29 docker copy file to img
   * 45:20 copy file from stopped container
   * 47:52 Docker curl
   * 49:33 add ENTRYPOINT to Dockerfile
   * 51:44 ENTRYPOINT vs. CMD

* [Video 10-2](https://youtu.be/pgWTk2jejM4): Zohar Asulin
   * 00:00 Docker and variable environment
   * 00:40 Docker with crontab
   * 12:06 Creating a file on a mounted volume in Docker as the external user
   * 16:04 Dockerfile of OSDC Site Generator
   * 25:28 CPAN Digger
   * 26:53 Playground docker image
   * 41:50 GitHub Action for Java Projects
   * 58:17  motivation of projects open source code
   * 01:06:05 CPAN Digger test average


## Session 11: Testing with PyTest

* Date: 2023.06.08 12:15-14:30

* [Testing Demo](https://code-maven.com/slides/python/testing-demo)
* [Testing Python with pytest](https://code-maven.com/slides/python/pytest)


* [Video 11-1](https://youtu.be/X3LMTayDRUM): Zohar Asulin
   *  00:00 testing with pytest
   * 05:27 test methods
   * 06:37 testing demo tools in python
   * 08:13 AUT-application under test
   * 10:30 Regression test
   * 13:07 doctest
   * 26:14 unittest
   * 30:50 pytest
   * 45:46 and unittest pytest run  doctest
   * 46:25 test coverage
   * 54:13 pytest setup
   * 55:37 examples test


* [Video 11-2](https://youtu.be/vB172bgPoxc): Zohar Asulin
   * 00:00 pytest expected exception
   * 06:37 pytest change text
   * 07:37 pytest missing exception
   * 08:14 exception raised
   * 10:20 exercise-test exceptions
   * 10:57 multiple failures
   * 12:30 selective running of test functions
   * 13:24 stop on first failure
   * 15:55 expect a test to fail
   * 23:15 –rx
   * 24:17 skip test
   * 27:37 –rs skip test
   * 28:15 show extra test –r
   * 28:30 verbose mode
   * 28:39 quiet mode
   * 28:49 STDOUT STDERR
   * 31:30 using classes
   * 32:06 module Home assignment - create test for open source project
   * 34:32 Travis CI
   * 35:06 pytest.mark.parametrize
   * 43:13 testing flask
   * 44:15 Anagram in CMD
   * 48:44 examples function test
   * 50:35 Fixtures
   * 1:00:12 Home assignment


## Assignment 11

Find an open source project, generate a test coverage report for it, write some tests for a part of the code
that did not have tests. Send it as a Pull-Request.
It can be a project you already contributed to or any other project. It can be in Python or any other language.

## Session 12: Which project to work on; Docker compose

* Date: 2023.06.15 12:15-14:30

* [Which project to contribute to?](https://code-maven.com/slides/osdc/)
* [Docker commands](https://code-maven.com/slides/docker/)
* [docker-compose](https://code-maven.com/slides/docker/docker-compose)
* [PyDigger](https://pydigger.com/) is using it.

* [Linode](https://www.linode.com/)
* [Digital Ocean](https://www.digitalocean.com/)


* [Video 12-1](https://youtu.be/jmdGLyhQFTI): Yael Levi
    * 00:00 Input order bug
    * 06:10 Which project to contribute
    * 12:12 Git log to watch commits on the project
    * 13:08 gitk, gitg
    * 15:02 tig
    * 17:17 A well-known projects
    * 24:25 Django
    * 35:49 search recent updates
    * 37:31 A project missing something
    * 37:50 cpan digger
    * 41:54 Desktop app, API, dependencies
    * 43:07 awesome list
    * 47:11 Type of project
    * 51:00 Web application
    * 51:42 databases
    * 01:01:00 in the OSDC
    * 01:01:02 Points for improvement
* [Video 12-2](https://youtu.be/OgYzZI1O1LQ): Eliyahou Levi
   * 00:30 Bot to telegram
   * 03:00 Docker commands
   * 05:40 Docker tag, update & publish
   * 08:39 Docker Compose
   * 11:08 docker-compose.yml
   * 13:02 swarm mode warnning
   * 15:29 Docker exec
   * 16:42 2 services example
   * 17:40 docker-compose up
   * 18:52 example with 2 docker files
   * 19:13 redis - key value db
   * 23:36 docker compose stop
   * 25:04 docker rm redis
   * 27:00 Docker Solr
   * 27:41 MongoDB
   * 29:01 Postgres
   * 29:30 Compose for Perl
   * 30:40 pydigger docker-compose.yml
   * 35:57 update pydigger
   * 37:43 docker-compose.yml example
   * 40:00 docker compose override.yml
   * 48:50 Linode
   * 52:17 Exercise

### Assignment 12

* Start writing a project and pusing it out to a repository on GitHub. The programming language used is not important and the project can be any "toy" project, but it needs to show the various things we learned. It has to have at least one test and there has to be Github Actions configured to run it.

## Next:

Videos so far:
    Yael Levi        18C
    Eliyahou Levi    18C
    Freddy Adiv      2277
    Ran Moshe        3455
    Doron Chapnitsky 6699
    Zohar Asulin     AABB

## Session 13

* Date: 2023.06.22 12:15-14:30

* Q&A Session
* https://dev.to/szabgab/the-most-interesting-open-source-web-applications-356
* https://distributed.blog/
* https://code-maven.com/live-web-site-with-editable-open-source-code

* [Maakaf](https://maakaf.code-maven.com/) Discord!
* Review lots of open source projects

* Video 13-1:
* Video 13-2:


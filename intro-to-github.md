*Sources:*

-   *Version Control with Git 3rd Ed, PK Ponuthorai & J Loeliger*

-   \_<https://docs.github.com/en_>

  

### Getting Started [(/get-started/)](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github)

GitHub is a developer platform that allows you to create, store, manage,
and share your code.

<ins>
**To start using GitHub, you first need to create an account on the
platform.**
</ins>

Your GitHub.com personal account is your identity on the platform, and
it represents you as an individual. Having an active account allows you
to collaborate on code stored on the platform. It also enables you to
organize and control access to the code or repositories you store on
GitHub.

  

#### Create a repository [(/repositories/)](https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories)

1.  Click the **New** button on the upper left of the page. This will
    bring you to the “Create new repository page”. Provide a new
    repository name.

2.  Also on this page, you have the option to provide a description for
    the repository, followed by an option to make this repository either
    public or private. A public repository is discoverable and
    accessible to anyone who is on GitHub.com. A private repository will
    require the owner of the project to invite collaborators, making it
    less discoverable.

3.  Finally, you have the option to initialize the repository with a
    README.md file. Click **Create Repository**.

------------------------------------------------------------------------

<span style="color:red"> **PRACTICE:**</span>

Create a repository called “Introduction_to_GitHub” with the description
“The place to start if you’ve never used GitHub before”. Make this new
repo public and initiate with a README.

------------------------------------------------------------------------

#### Add a file [(/repositories/working-with-files/)](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)

You can quickly add a file to the repository without cloning the repo
via the **Add file** button. You can choose to upload files from your
personal machine or create a new file via the GitHub.com user interface
(UI).

------------------------------------------------------------------------

<span style="color:red"> **PRACTICE:**</span>

Cut-and-paste the following into a text editor, such as TextEdit on Mac,
and save to your personal machine’s Desktop with the title
“github-basics”. Then upload the file to your Introduction_to_GitHub
repository. To commit the changes, provide a brief commit message such
as “My first commit.” and a longer description of your choice. Finally,
hit the green **Commit changes**.

INTRODUCTORY TOPICS:

1.  Creating repositories
2.  Adding files
3.  Issues
4.  Forking
5.  Branches
6.  Pull Requests
7.  GitHub Actions (GHA)
8.  Templates

------------------------------------------------------------------------

### Issues [(/issues/)](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)

Use GitHub Issues to to plan, discuss, and track your work. Issues are
available in all GitHub repositories and are often used for reporting
bugs and requesting features. You can use Issues to collaborate on ideas
or tasks, give or receive feedback, and communicate with others.

**Quickly create issues from a repository:**
[(/creating-an-issue/)](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue)

1.  On GitHub.com, navigate to the main page of the repository.

2.  Under your repository name, click **Issues**.

3.  Click the green **New issue**.

4.  In the **Title** field, type a title for your issue.

5.  In the comment body field, type a description of your issue.

6.  If you’re a project maintainer, you can assign the issue to someone,
    add it to a project, associate it with a milestone, or apply a
    label.

7.  When you’re finished, click **Submit new issue**.

  

------------------------------------------------------------------------

<span style="color:red"> **PRACTICE:**</span>

Create a new issue with the title “Convert github-basics from .rtf to
.md”. In the description include “Replace github-basics.rtf with a
Markdown file so that it is easier to read.”. Submit this new issue.

------------------------------------------------------------------------

 

### Forking [(/fork-a-repository/)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)

A fork is a new repository that shares code and visibility settings with
the original “upstream” repository. Forks are often used to iterate on
ideas or changes before they are proposed back to the upstream
repository, such as in open source projects or when a user does not have
write access to the upstream repository.

You can use forks to propose changes related to fixing a bug. Rather
than logging an issue for a bug you have found, you can: (1) Fork the
repository, (2) Make the fix, (3) Submit a pull request to the project
owner.

**Forking a repository:**

1.  On GitHub.com, navigate to the repository.

2.  In the top-right corner of the page, click **Fork**.

3.  Under “Owner”, select the dropdown menu and click an owner of the
    forked repository.

4.  By default, forks are named the same as their upstream repositories.
    Optionally, to further distinguish your fork, in the “Repository
    name” field, type a name.

5.  Optionally, in the “Description” field, type a description of your
    fork.

6.  Optionally, select **Copy the DEFAULT branch only**. For many
    forking scenarios, such as contributing to open-source projects, you
    only need to copy the default branch. If you do not select this
    option, all branches will be copied into the new fork.

7.  Click **Create fork**.

  

------------------------------------------------------------------------

**PRACTICE:**

On GitHub.com, navigate to
<https://github.com/cshelley/Introduction_to_GitHub>. This repository
contains all of the notes you are currently reading, so forking this is
the easiest way to keep a copy of these instructions.

------------------------------------------------------------------------

  

### Branching [(/about-branches/)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)

Branches allow you to develop features, fix bugs, or safely experiment
with new ideas in a contained area of your repository.

Each repository has one default branch, called the *main branch*, that
reflects the most up-to-date, fully functioning project code. A *branch*
allows the user to launch a separate line of development within a
software project. Therefore, you can use a branch to isolate development
work without affecting the main branch or other branches in the
repository. Each repository has one default branch, and can have
multiple other branches. You can merge a branch into another branch
using a pull request.

You always create a branch from an existing branch. Typically, you might
create a new branch from the default branch of your repository. You can
then work on this new branch in isolation from changes that other people
are making to the repository. A branch you create to build a feature is
commonly referred to as a *feature branch* or *topic branch*.

**Creating and deleting branches within your repository**
[(/creating-and-deleting-branches/)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)

1.  On GitHub.com, navigate to the main page of the repository.

2.  From the file tree view on the left, select the branch dropdown
    menu, then click **View all branches.** You can also find the branch
    dropdown menu at the top of the integrated file editor.

3.  Click the green **New branch** button on the right.

4.  Under “Branch name”, type a name for the branch.

5.  Under “Branch source”, choose a source for your branch. Select the
    branch dropdown menu and click a branch.

------------------------------------------------------------------------

<span style="color:red"> **PRACTICE:**</span>

Create a new branch of Introduction_to_GitHub called
“best_practices_for_pull_requests”.

------------------------------------------------------------------------

**Viewing branches in your repository**
[(/view_branches/)](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/viewing-branches-in-your-repository)

1.  On GitHub.com, navigate to the main page of the repository.

2.  From the file tree view on the left, select the branch dropdown
    menu, then click **View all branches**.

3.  Use the navigation at the top of the page to view specific lists of
    branches.

4.  Optionally, use the search field on the top right.

  

### Pull Requests [(/about-pull-requests/)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

Pull requests let you tell others about changes you’ve pushed to a
branch in a repository on GitHub. Once a pull request is opened, you can
discuss and review the potential changes with collaborators and add
follow-up commits before your changes are merged into the base branch.

A pull request is a proposal to merge a set of changes from one branch
into another. In a pull request, collaborators can review and discuss
the proposed set of changes before they integrate the changes into the
main codebase. Pull requests display the differences, or diffs, between
the content in the source branch and the content in the target branch.

After initializing a pull request, you’ll see a review page that shows a
high-level overview of the changes between your branch (the *compare
branch*) and the repository’s base branch. You can add a summary of the
proposed changes, review the changes made by commits, add labels,
milestones, assignees, and @mention individual contributions or teams.

Create a pull request to propose and collaborate on changes to a
repository. These changes are proposed in a *branch*, which ensures that
the default branch only contains finished and approved work. If you want
to create a new branch for your pull request and do not have write
permissions to the repository, you can fork the repository first.

  

**Creating Pull Requests:**
[(/creating-a-pull-request/)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

1.  On GitHub.com, navigate to the main page of the repository.

2.  In the “Branch” menu, choose the branch that contains your commits.

3.  Above the list of files, in the yellow banner, click the green
    **Compare & pull request** to create a pull request for the
    associated branch.

4.  Use the *base* branch drowdown menu to select the branch you’d like
    to merge your changes into, then use the *compare* branch drop-down
    menu to choose the topic branch you made your changes in.

5.  Type a title and description of your pull request.

6.  To create a pull request that is ready for review, click **Create
    Pull Request**. To create a draft pull request, use the drop-down
    and select **Create Draft Pull Request**, then click **Draft Pull
    Request**.

7.  After you create a pull request, you can ask a specific person to
    review your proposed changes. After your pull request has been
    reviewed, it can be merged into the repository.

  

------------------------------------------------------------------------

**PRACTICE:**

1.  Create a new issue titled “Add instructions on how to create pull
    requests within issues”.

2.  Create a .md file on your local machine with the title
    `linking-a-pull-request-to-an-issue.md`. This file should contain
    the following information:

### About Linked Issues and pull requests

Source:
<https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue>

You can link an issue to a pull request manually or using a supported
keyword in the pull request description. When you link a pull request to
the issue the pull request addresses, collaborators can see that someone
is working on the issue. The pull request will also reflect the issue
number, which will help keep track of pull requests. When you merge a
linked pull request into the default branch of a repository, it’s linked
issue is automatically closed.

To link the pull request to an issue, navigate to the issue you wish to
address. On the right-hand panel, click on “Create a branch” for this
issue or link a pull request.

You can now navigate to this new branch, which will begin with an
assigned Issue #. Upload your file addressing the issue and Commit
changes.

1.  Follow your own instructions as outlined in
    `linking-a-pull-request-to-an-issue.md` to address and close your
    issue with a pull request.

2.  Confirm that your issue is now closed.

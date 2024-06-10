# GitHub Workflow
>
> BATYA GUR ARIYE

## GitHub's issues and PR features

### ISSUES

item that can be created in a repository to plan, discuss and etc.
Issues are simple to create and to suit a variety of scenarios.
You can use issues to give or receive feedback, collaborate on ideas or tasks,
and efficiently communicate with others.
Issues let you track your work on GitHub.
When you mention an issue in another issue or pull request,
you can link an issue to a pull request. When the pull request merges,
the linked issue automatically closes.
Use keywords that you can see in the attached table.
Issues can be created in a variety of ways,
so you can choose the most convenient method for your workflow.
For example, you can create an issue from a repository, an item in a task list,
a note in a project, a comment in an issue or pull request.

#### Creating an issue

**A.**  Under your repository name, click  Issues.

 ![picture1](assets/1.png)

**B.**  Click New issue.

 ![picture2](assets/2.png)

**C.** In the "Title" field, type a title for your issue.

 ![picture3](assets/3.png)

**D.** In the comment body field, type a description of your issue.

 ![picture4](assets/4.png)

**E.** When you're finished, click Submit new issue.
  
 ![picture5](assets/5.png)

### PULL REQUESTS

A pull request allows you to show others the changes
you made in the branch that is in your repository,
after opening pull requests,
you can discuss and review the changes,
add follow-up commits before merging into the main branch.

A pull request is a proposal to merge a
set of changes from one branch into another.
Pull requests display the differences between the content in the source branch
and the content in the target branch.

After initializing a pull request,
Can  see a review page that shows high-level overview of
the changes between your branch
(the compare branch)
and the repository's base branch.

Once the task is complete, can merge the pull request.
If you're working in a shared repository model,
create a pull request and you,
or someone else, will merge your changes from your
feature branch into the base branch you specify
in your pull request.

can link a pull request or branch to an issue to
show that a fix is in progress and to
automatically close the issue when the pull request or branch is merged.

***Who can use this feature?***

Anyone with read access to a repository can create a pull request.
You can specify which branch you'd like to merge your
changes into when you create your pull request.
Pull requests can only be opened between two branches that are different.

#### Creating a pull request

**A.** Under your repository name, click  Pull requests.

 ![picture1](assets/6.png)

**B.**  Click New Pull requests.

 ![picture2](assets/7.png)

**C.** Compare changes - 
Compare changes across branches, commits, tags, and more below.

 ![picture3](assets/8.png)

**D.** Click Create Pull requests.

 ![picture4](assets/9.png)

**E.** Fill in the details and look at the issues.
  
**F.** Now you can add comments and upload files to merge the request back into the main branch.

![picture5](assets/10.png)
![picture5](assets/11.png)  
![picture5](assets/12.png)  

***Differences between commits on compare and pull request pages***

The compare and pull request pages use
different methods to calculate the diff for changed files:
Compare pages show the diff between
the tip of the head ref and the current
common ancestor (that is, the merge base)
of the head and base ref.
Pull request pages show the diff between
the tip of the head ref and the common ancestor
of the head and base ref at the time when the pull request was created.
Consequently,
the merge base used for the comparison might be different.
##### Attached a pull request with problems

can link a pull request or branch to an issue to show that a fix is in progress and to automatically close the issue when the pull request or branch is merged.
Using by a supported keyword:

* close
* closes
* closed
* fix
* fixes
* fixed
* resolve
* resolves
* resolved

| linked issue                    | Syntax                              | Exemple                                                     |
|---------------------------------|-------------------------------------|-------------------------------------------------------------|
| Issue in the same repository    |KEYWORD #ISSUE-NUMBER                | Closes #10                                                  |
| Issue in a different repository |KEYWORD OWNER/REPOSITORY#ISSUE-NUMBER|Use full syntax for each issue                               |
|Multiple issues                  |Use full syntax for each issue       |Resolves #10, resolves #123, resolves octo-org/octo-repo#100 |

You can manually link up to ten issues to each pull request.
The issue can be in a different repository than the linked pull request or branch.
Your last selected repository will be remembered.

* click the pull request that you'd like to link to an issue.
* In the right sidebar, click Development

![picture5](assets/13.png)

* Click the issue you want to link to the pull request.

![picture5](assets/14.png)

## GitHub's projects

A project is an adaptable spreadsheet, task-board,
and road map that integrates with
issues and pull requests on GitHub to help plan and track work effectively.
You can create and customize multiple
views by filtering, sorting,
grouping issues and pull requests,
visualize work with configurable charts,
and add custom fields to track metadata specific to a team.

Your projects are built from the issues and pull requests you add,
creating direct references between your project and your work.
Information is synced automatically to
your project as you make changes,
updating your views and charts.
This integration works both ways,
so that when you change information about a pull request or issue in your project,
the pull request or issue reflects that information.

You can use task lists to build hierarchies of issues,
dividing your issues into smaller subtasks,
and creating new relationships between your issues.

You can view your project as a high-density
table layout, as a Kanban board,
or a timeline-style roadmap.

---

*you can add the following metadata as custom fields:*

* *A date field to track target ship dates.*
* *A number field to track the complexity of a task.*
* *A single select field to track whether a task is Low,*
* *Medium, or High priority.*
* *A text field to add a quick note.*
* *An iteration field to plan work week-by-week,*
*including support for breaks*

### Creating a Project

**A.** In the upper-right corner of GitHub, select your profile photo, then click  Your Projects.

 ![picture1](assets/15.png)

**B.**  click New project.

![picture2](assets/16.png)

**C.**  Select which type of projects or template you ant to use.

* To create a blank project, click Table, Roadmap, or Board.

 ![picture3](assets/17.png)

* To create a project from a template, click the template you want to use.

 ![picture3](assets/18.png)

**D.** click Create project.

 ![picture4](assets/19.png)

**E.** Don't forget to save when finished.

## GitHub's discussions

GitHub Discussions is a collaborative communication form for the community
around an open source or internal project.
Discussions are for conversations that
need to be transparent and accessible but do
not need to be tracked on a project and are not related to code,
unlike GitHub Issues.
Discussions enable fluid, open conversation in a public forum.

Discussions give a space for more collaborative conversations by connecting
and giving a more centralized area to connect and find inform.
Organization owners
can enable GitHub Discussions for their organization.

When you enable organization discussions, you will choose a repository in the
organization to be the source repository for your organization discussions.
You can use an existing repository or create a repository specifically to
hold your organization discussions.
Discussions will appear both on the discussions page for the organization and
on the discussion page for the source repository.

### Creating a discussion

**A.**  A   Under your repository name, click  Settings .(Only the administrator can create a discussion).

 ![picture1](assets/20.png)

**B.** Scroll down to the "Features" section and click Set up discussions.

 ![picture2](assets/21.png)

**C.** Fill in the necessary details title and body of the discussion.

 ![picture3](assets/22.png)

**D.** You can change the discussion category.
 ![picture4](assets/23.png)

**E.** Click Start discussion.

   <!-- ![picture4](.\Pictures\24.png) -->

**F.** Now, you can add a comment, or close the discussion.

![picture5](assets/24.png)

## GitHub's milestones and labels

### label

You can manage your work on GitHub by creating labels to categorize issues,
pull requests, and discussions.
You can apply labels in the repository the label was created in.
Once a label exists, you can use the label on any issue,
pull request,
or discussion within that repository.

#### Creating a label

Anyone with writeaccess to a repository can create a label.

**A.**  Under your repository name, click Issues or Pull requests..

 ![picture1](assets/25.png)

**B.** Above the list, of issues or pull requests, click Labels.

 ![picture2](assets/26.png)

**C.** To the right of the search field, click New label.

 ![picture3](assets/27.png)

**D.**   - Under "Label name", type a name for your label.
        -Under "Description", type a description to help others understand and use your label.
          - Optionally, to customize the color of your label, edit the hexadecimal number,
          or, for another random selection, click refresh .

 ![picture4](assets/28.png)

**E.** Click  create label or cancel.

![picture4](assets/29.png)

### milestones

you can associate it with issues and pull requests.
To better manage your project, From the milestone page, you can see:

* A user-provided description of the milestone,
which can include information like a project overview,
relevant teams, and projected due dates
* The milestone's due date
* The milestone's completion percentage
* The number of open and closed issues and
pull requests associated with the milestone
* A list of the open and closed issues and pull requests associated with the milestone
Additionally, you can edit the milestone from the milestone
page and create new issues that are, by default,
associated with the milestone.

#### Creating a milestones

**A.** Under your repository name, click Issues or Pull requests..

 ![picture1](assets/30.png)

**B.**  Above the list, of issues or pull requests, click milestones.

 ![picture2](assets/31.png)

**C.** create a new milestone, click New Milestone.

 ![picture3](assets/32.png)

**D.** and fill in the fields.

 ![picture4](assets/33.png)

**E.** To edit a milestone, next to the milestone you want to edit, click Edit.

![picture4](assets/34.png)

**F.** To delete a milestone, next to the milestone you want to edit, click Delete.

![picture4](assets/35.png)

title: My Coding Journey Starts Here “Hello World!”
intro: 'Embark on your coding journey with this hands-on exercise to explore GitHub''s pull request workflow.'

versions:
  fpt: '*'
  ghes: '*'
  ghec: '*'

type: quick_start

topics:
  - Pull requests
  - Fundamentals
redirect_from:
  - /get-started/quickstart/hello-world
---

## Introduction

Welcome to your coding adventure! In this tutorial, we'll dive into the basics of coding “Hello World” and collaboration using GitHub's pull request workflow. Whether you're a prac developer or just starting out, this guide will walk you through the essentials of repositories, branches, commits, and pull requests, setting you on the path to becoming a coding pro. 

In this quickstart guide, you will:

- Create and use a repository.
- Start and manage a new branch.
- Make changes to a file and push them to {% data variables.product.product_name %} as commits.
- Open and merge a pull request.

### Prerequisites

- You must have a {% data variables.product.prodname_dotcom %} account. {% ifversion fpt or ghec %}For more information, see "[AUTOTITLE](/get-started/start-your-journey/creating-an-account-on-github)."{% endif %}  
- You don't need to know how to code, use the command line, or install Git (the version control software that {% data variables.product.product_name %} is built on).


## Step 1: Let's Build our Project starting off with creating our first repo 

To kick things off, we're going to create a project repository. Think of it as your digital workspace where you'll bring your coding ideas to life. But don't worry, you won't be alone in this journey – GitHub makes collaboration a breeze! README files are written in Markdown, which is an easy-to-read, easy-to-write language for formatting plain text. We'll learn more about Markdown in the next tutorial, "[AUTOTITLE](/get-started/start-your-journey/setting-up-your-profile)."
 {% data variables.product.product_name %} lets you add a README file at the same time you create your new repository. {% data variables.product.product_name %} also offers other common options such as a license file, but you do not have to select any of them now. 
Follow these simple steps to create your project repository:

{% data reusables.repositories.create_new %}
1. Name your repository something catchy and meaningful. How about "My Coding Adventure"?
{% data reusables.repositories.add-description %} You can leave a short description to tell others what your project is all about.
{% data reusables.repositories.select-public-or-private %}
{% data reusables.repositories.add-readme %}
{% data reusables.repositories.click-create %}

## Step 2: Let Your Ideas Branch Out by creating a branch

Branching out is where the real fun begins! It's like exploring different paths on your coding journey. With branches, you can experiment, make changes, and test new ideas without affecting your main project.

By default, your repository has one branch named `main` that is considered to be the definitive branch. You can create additional branches off of `main` in your repository.


Branching is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to `main`.


When you create a branch off the `main` branch, you're making a copy, or snapshot, of `main` as it was at that point in time. If someone else made changes to the `main` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The `main` branch
- A new branch called `feature`
- The journey that `feature` takes before it's merged into `main`

![Diagram of the two branches. The "feature" branch diverges from the "main" branch, goes through stages for "Commit changes," "Submit pull request," and "Discuss proposed changes," and is then merged back into main.](/assets/images/help/repository/branching.png)


### Creating a branch

1. Click the **Code** tab of your `hello-world` repository.
1. Above the file list, click the dropdown menu that says **main**.

{% ifversion global-nav-update %}

   ![Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.](/assets/images/help/branches/branch-selection-dropdown-global-nav-update.png)

{% else %}

   ![Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.](/assets/images/help/branches/branch-selection-dropdown.png)

{% endif %}

1. Type a branch name, `readme-edits`, into the text box.
1. Click **Create branch: readme-edits from main**.

   ![Screenshot of the branch dropdown for a repository. "Create branch: readme-edits from 'main'" is outlined in dark orange.](/assets/images/help/repository/new-branch.png)

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next you'll add changes to the new `readme-edits` branch.


## Step 3: Making and committing changes

Now that you've set up your project and branched out, it's time to get coding! Let your creativity flow as you make changes to your project files. Every change you make will be saved as a commit, documenting your progress along the way.  

When you created a new branch in the previous step, {% data variables.product.product_name %} brought you to the code page for your new `readme-edits` branch, which is a copy of `main`.

You can make and save changes to the files in your repository. On {% data variables.product.product_name %}, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

Here's how to make and save your changes:

 ![Screenshot of a diff for the README.md file. 3 red lines list the text that's being removed, and 3 green lines list the text being added.](/assets/images/help/repository/diffs.png)

1. Click on a file in your repository to open it.
1. Make your edits right in the GitHub interface.
1. Write a brief description of your changes in the commit message box.
1. Hit **Commit changes** to save your work.

## Step 4: Open a pull request

Coding is more fun when you do it together! With pull requests, you can share your work with others, gather feedback, and collaborate on making your project even better.

Let's open a pull request to share your changes:

1. Go to the **Pull requests** tab of your repository.
1. Click **New pull request**.
1. Choose the branch you created earlier as the "compare" branch.
1. Review your changes and click **Create pull request**.
1. Give your pull request a title and description, then hit **Create pull request** again.

### Step 5: Time to Merge 

Once your pull request is open, you can collaborate with others, discuss your changes, and refine your project together. When you're ready, it's time to merge your changes into the main project!


1. Click **Merge pull request**.
1. Confirm the merge and celebrate your first collaboration success!
1. Don't forget to **Delete branch** to keep your project organized.

## Conclusion

Congratulations! You've taken your first steps into the exciting world of coding and collaboration using GitHub's pull request workflow. With these fundamental skills under your belt, you're ready to tackle even bigger coding adventures ahead.

## Next Steps

- Explore your GitHub profile and see your coding journey come to life on your contribution graph.
- Ready for more challenges? Check out the [{% data variables.product.prodname_learning %}](https://skills.github.com/) courses to expand your coding skills.
- Continue your journey by personalizing your GitHub profile and mastering Markdown in the next tutorial.

## Further Reading

- "[AUTOTITLE](/get-started/using-github/github-flow)"

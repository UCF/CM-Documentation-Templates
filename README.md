# CM-Documentation-Templates

A set of project documentation templates for use in new projects by UCF CM.


## How to use these files

In this project, each set of available templates is split out into unique branches.  Templates are grouped by project type; e.g. `plugin-wiki`, `theme-wiki`.

Know what you're looking for?  See below:

### How-Tos
- [Create a new wiki](#creating-a-new-wiki)
- [Create a new theme or plugin](#creating-a-new-theme-or-plugin)

### Wiki Files
- [WordPress Theme wiki template](https://github.com/UCF/CM-Documentation-Templates/tree/theme-wiki)
- [WordPress Plugin wiki template](https://github.com/UCF/CM-Documentation-Templates/tree/plugin-wiki)

-----

## Creating a new wiki

Whenever you're starting a new project hosted on Github, you should set up a new project wiki to host documentation and usage information.  A project wiki is a series of markdown files (and, optionally, images) that live in their own separate repo.  For more information on Github wikis, [check out their documentation here](https://help.github.com/articles/about-github-wikis/).

**Note: these instructions are intended for brand new, unedited wikis.**  We recommend making changes to existing wikis manually to avoid accidentally overwriting data.

### Instructions:

1. From your project repo in Github, click on the "Wiki" tab.

    <img src="https://help.github.com/assets/images/help/wiki/wiki_menu_link.png">

    If you haven't created any pages for this wiki yet (you see a welcome message with a "Create the first page" button), create a new "Home" page and save it (don't worry about the contents of this new file; they'll get overwritten).  Else, proceed to the next step.

2. Create a new directory on your machine where you'd like the wiki files to live on your machine.

3. `cd` into the new wiki directory on your machine.

4. Pull down the relevant template files for your project.

    **For plugin wikis:**

    `git clone --depth=1 -b plugin-wiki git@github.com:UCF/CM-Documentation-Templates.git .; rm -rf .git`

    **For theme wikis:**

    `git clone --depth=1 -b theme-wiki git@github.com:UCF/CM-Documentation-Templates.git .; rm -rf .git`

5. Initialize a new git repository, and force push it up to the wiki repo on Github (where "MY-PROJECT" refers to the project name you used on Github):

    ```
    git init
    git add --all
    git commit -m "Initial commit"
    git remote add origin git@github.com:UCF/MY-PROJECT.wiki.git
    git push -u origin master --force
    ```

6. Replace `{{My-Project}}` and `{{My Project}}` placeholders throughout the template files.

    `{{My-Project}}` corresponds to the the **slug of your project on Github**, e.g. `Main-Site-Theme`.

    `{{My Project}}` should be replaced with the **human-friendly name** of your project, e.g. `Main Site Theme`.

    You can perform a couple of project-wide find+replace commands in your IDE/editor to do this quickly.

From this point, you can [edit your project's wiki files directly in Github](https://help.github.com/articles/adding-wiki-pages-via-the-online-interface/), or [continue editing the wiki repo locally](https://help.github.com/articles/adding-and-editing-wiki-pages-locally/) (note that you _must_ work locally to commit and push images up to the wiki).  See [Github's wiki documentation](https://help.github.com/articles/about-github-wikis/#further-reading) for more information.

**Remember to fill in the remaining placeholder information for your project wiki** in the provided template files! (You can do a project-wide search for `{{` to locate all of these placeholders.)

-----

## Creating a new theme or plugin

Looking for WordPress theme and plugin project templates?  Since Github launched its project template feature, these have been moved out of this repo into their own separate template repos:

- [WordPress Theme template](https://github.com/UCF/CM-WP-Theme-Template)
- [WordPress Child Theme template](https://github.com/UCF/CM-WP-Child-Theme-Template)
- [WordPress Plugin template](https://github.com/UCF/CM-WP-Plugin-Template)

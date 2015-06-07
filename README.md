Documentation
====
# Building Social Repositories and Extending their Applications 
## Getting Started with Pedagogy Toolkit Templates

Read more about the templates branch in the [Pedagogy Toolkit documentation](http://pedagogy-toolkit.org/documentation/documentation.html#teach-in-the-cloudspan-classarrowh2span).

#Getting started with GitHub

Sign-up for a GitHub account at https://github.com/join 

As soon as you have created an account, be sure to verify your e-mail. You will receive an automated e-mail from GitHub (do this straight away).

In the following steps, we will deal with basic branching and forking. Read more about these and other aspects of Git and Github at https://help.github.com/ and https://git-scm.com/ .

#Setting up your website

##Forking Pedagogy Toolkit

Naviagte to the Pedagogy Toolkit repository and view the "templates" branch at https://github.com/axchristie/toolkit/tree/templates .

Now we will copy the Pedagogy Toolkit source code to your account. Click "fork" to copy the repository.

![](http://acrl.ala.org/techconnect/wp-content/uploads/2013/05/github-fork-btn.png)

##Configuring your repository

You are now viewing your copy of the Pedagogy Toolkit code, which you can repurpose for your own projects. Let's set up your repository.

First, we need to replace the "gh-pages" branch with the "templates" branch. You may preserve the original gh-pages branch as another branch if you would like to revisit it. In the following steps, we'll simply delete it.

Go to "Settings" and change the Default branch to "templates."

Return to the repository and click "2 branches." Then delete the gh-pages branch by clicking the red trash can.

Return to the repository once more and click "branch: templates." Type "gh-pages" to create a new branch based on the templates branch.

Now return to settings and switch the default branch back to gh-pages.

**We will now edit and configure your website. Make sure you are working on the gh-pages branch (you may delete the old "templates" branch if you wish).

##Getting started with editing

You may either work directly on the GitHub website or download the GitHub client if you prefer to work locally. If you're not sure where to start, I suggest working online first and downloading the client at the end of today's workshop.

The GitHub client is available for download at https://mac.github.com/  and https://windows.github.com/ https://mac.github.com/  .
 
##Website URL

The current name of your website is "toolkit." If you would like to change the name of your site,  you may do so by changing the repository name in "Settings."

Now click on "_config.yml." Once the file is open in your browser, click the pen logo to edit the file.

![](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png)

We will now set the site baseurl to match the repository name you have chosen. Replace "template" with the name of your repository (if you have chosen to mantain the "toolkit" name, then replace "template" with "toolkit"). Be sure not to delete the slash.

Click "commit changes" to save your update. Congratulations on your first commit!

Your website is not viewable online at yourusername.github.io/yourrepository name (i.e., axchristie.github.io/ENGL135 ). It may take a few minutes for changes you have made to appear online.

##The basic layout of the repository

Congratulations! You now have a socially editable repository that corresponds to an active website. Updates made to this repository will automatically update the website, allowing you to easily design and share web content with students, colleagues, and so on. You may socially author your repository with other users on GitHub.
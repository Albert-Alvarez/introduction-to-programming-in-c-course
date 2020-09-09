First of all, welcome {{ user.login }} to the {{ course.title }} course! In this course, we're going to see how to create programs in [C language](https://en.wikipedia.org/wiki/C_(programming_language)).

During the course, we'll suppose that we don't know how to operate with Git and GitHub. This course **isn't intended to learn Git or GitHub**. I'm going to give you all the instructions to operate with Git and GitHub so that you can follow the course without knowing them. If you want to learn Git or GitHub, you can find more resources on [GitHub Lab](https://lab.github.com/).

# Prerequisites

## Installing Git

Obviously, if you're here is because you've already created an account in GitHub. So, we're going to skip this step. Let's install Git in our computer in order to syncronize our local (computer) and remote (GitHub) repositories. To do this, the first is to download and install Git. You can find it [here](https://git-scm.com/). During the installation, you only have to click <kbd>Next</kbd>, <kbd>Next</kbd>, <kbd>Next</kbd>..., until the installation finishes. Let the default installation options.

## Configuring Git

Once installed, right-click on you Desktop and click on <kbd>Git Bash Here</kbd> to open bash terminal with you Desktop as the current directory. Then, we hace to configure the name and email that Git will use to commit our changes. Run the next commands in the terminal:

```bash
$ git config --global user.name "John Doe"
```
where you have to replace "John Doe" by your full name.

```bash
$ git config --global user.email johndoe@example.com
```
where you have to replace "johndoe@example.com" by your email (it doesn't have to be the same email as your GitHub account).

## Cloning the remote repository on GitHub

Run in the terminal the next command:

```bash
$ git clone {{ repoUrl }}
```
A login windows will appear asking to log in GitHub. Use your GitHub user/email and password to log in.

Once logged, a new folder, named "{{ course.slug }}", will be created in your Desktop with the local repository. Access to the folder running the command:

```bash
$ cd {{ course.slug }}
```

Close the terminal. In the future, if you accidentally close the terminal, or want to take a pause, you can directly open the bash terminal right-clicking the folder "{{ course.slug }}" in your Desktop and clicking on <kbd>Git Bash Here</kbd>.

# Compilation and execution: how is done?

<!-- http://embedyoutube.org/ -->
[![](URL_IMAGE)](URL_VIDEO "Compilation and execution")

# Installing GCC

Let's install our compiler. There are several compilers. We're going to use the GCC compiler. You can download MinGW, from [here](http://www.mingw.org/), to get the GCC compiler. Use the <kbd>Next</kbd>, <kbd>Next</kbd>, <kbd>Next</kbd>..., installation technique until finished. Once installed, a new window will open. Select the package "mingw32-base-bin", and, in the menu bar, select <kbd>Installation > Apply Changes</kbd>.

![00_mingw](https://user-images.githubusercontent.com/34403794/92594349-ee9b4b80-f2a2-11ea-9f13-717529552a41.png)

Then <kbd>Apply</kbd>. Once finished, close the application.

## Testing that GCC is correctly installed



<!-- Haremos dos issues/steps de esto -->
# Creating a "Hello, World!" program

# Running the program

      _____   _____  _____ _   _        _  _ ___  _____ 
     |  __ \ / ____|/ ____| \ | |      | || |__ \| ____|
     | |  | | (___ | |  __|  \| |______| || |_ ) | |__  
     | |  | |\___ \| | |_ | . ` |______|__   _/ /|___ \ 
     | |__| |____) | |__| | |\  |         | |/ /_ ___) |
     |_____/|_____/ \_____|_| \_|         |_|____|____/

# Welcome to DSGN-425

This is an example of a GitHub repository, and it is yours to break. Make your own copy, open it in a Codespace, change something, and put the change through a pull request. Nothing you do in your copy can affect anyone else, so this is the place to get the moves wrong before they count.

You will do the same moves in the class `roster` repo, where they do count.

This README tells you which buttons to press. What a branch and a pull request actually are, and why every software team works this way, is in [Git and GitHub](https://entr451.com/git-and-github/). Read that one at some point; it outlives this repo and this course.

## 1. Make your own copy

Click the green **Use this template** button at the top of this page, then **Create a new repository**. Owner: your own account (not the class org). Name: `hello-world`. Leave the visibility on **Private**. Click **Create repository**.

Check the name at the top left of the page. It should read `your-username/hello-world`. If it still says `dsgn425-fall2026/hello-world`, you are looking at the template, not your copy; go back and click **Use this template**.

You now have a repo of your own with these files in it. That is what a template is for: a starting point you copy, not a place you edit.

## 2. Open it in a Codespace

On your new repo's page, click the green **Code** button, then the **Codespaces** tab, then **Create codespace on main**.

A Codespace is a full development environment (a computer, an operating system, an editor, and the tools) that GitHub sets up for you in the cloud. It looks like VS Code because it is VS Code. The first open takes a minute or two while it builds; after that it is fast.

## 3. Make a branch

Before you change anything, look at the bottom-left corner of the editor. It says `main`. Click it, choose **Create new branch...**, give it a name that says what you are about to do (`my-first-edit` is fine), and press Enter.

It is your repo and nobody would stop you from editing `main` directly. Make the branch anyway. In the class repo `main` is locked, and on any team you work with it will be too. The branch is the habit; this is where you build it. ([What a branch is actually for](https://entr451.com/git-and-github/#branches).)

## 4. Change something

Open `README.md` (this file) from the Explorer on the left, and add a line at the bottom under **About me**. Or add a whole new file. Save with Ctrl-S (Cmd-S on a Mac).

## 5. Commit and publish

Click the Source Control icon in the left bar. Your change is listed. Click the **+** next to it to stage it. In the message box, write what you did in plain words (`adds a line about me`, not `update` and not `tried again`). Click **Commit**, then **Publish Branch**.

Your change is now on GitHub, on your branch. `main` has not changed yet.

## 6. Open a pull request and merge it

Go to your repo's page on github.com. A yellow banner offers **Compare & pull request**; click it. Title, one sentence, **Create pull request**.

This is the request to change `main`. In the class repo someone else reviews it. Here, you are the whole team: read your own change on the **Files changed** tab, then click **Merge pull request**, **Confirm merge**, and **Delete branch**. Look at `main`; your change is there, and the commit history shows how it got there.

A pull request is more than the button, and reviewing one is a real skill you will use whether or not you ever write the code. Both are explained in [Git and GitHub](https://entr451.com/git-and-github/).

## The code folder

`code/` has three tiny Ruby programs for the command-line part of the first class. In the Codespace terminal (View > Terminal):

    ruby code/hello.rb

prints a greeting.

    ruby code/infinite-tacos.rb

never stops on its own. Press Ctrl-C to stop it. `code/data.rb` is a worksheet for later.

## When you are done

Stop the Codespace. Code > Codespaces > the three dots next to it > **Stop codespace**. It stops itself after thirty minutes idle, but stopping it yourself is the habit.

## About me
lmfao
# Git Scavenger Hunt

Welcome to the official *Git For Noobs!* scavenger hunt. This README file contains all the instructions you need to get started!

## 1. Prerequisites

**Each participant will need:**

- A GitHub account
- Git

## 1.1 Create a GitHub Account

On GitHub, click **Sign Up** at the top of the page. You may use any email you want, just remember you will have to use the same one when you configure Git in [step 1.2](#11-install-git).

## 1.2 Install Git

**Each participant needs to complete these steps:**

1. Check if Git is already installed by opening a terminal and entering:

```
git --version
```

2. If the command fails, install Git from here: https://git-scm.com/install/windows. **For Linux and macOS users:** Make sure you use the terminal commands from the other tabs.

3. Once installed, You will need to enter these commands into your terminal (Make sure to change the name and email):

```
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL"
```

4. You may also enter these **recommended** commands to make things work just a bit smoother:

```
git config --global init.defaultBranch main
git config --global core.editor "nano -w"
```

**Extra steps for Linux and macOS users:**

5. It's recommended you use `gh` for authentication with HTTPS (for simplicity). Follow the install steps here: https://cli.github.com/

6. Enter:

```
gh auth login
```

7. Here are the recommended settings to choose from the setup dialog:

```
? What account do you want to log into? GitHub.com
? What is your preferred protocol for Git operations on this host? HTTPS
? Authenticate Git with your GitHub credentials? Yes
? How would you like to authenticate GitHub CLI? Login with a web browser
```

8. Copy the one-time code and paste it into your web browser. You will have to log into your GitHub account, first.

## 1.3 Fork the Repository

**Only one participant needs to complete these steps:**

1. Scroll to the top of the page and hit the **Fork** button.

![alt text](screenshots/image.png)

2. On the next page, make sure to **uncheck** the "Copy to the `main` branch only" checkbox, and hit **Create Fork**.

![alt text](screenshots/image-1.png)

You now have a personal copy of this repository on your GitHut account. It's time to add your group members!

3. From your fork, find the **Settings** tab.

![alt text](screenshots/image-2.png)

4. Find **Collaborators** in the sidebar.

![alt text](screenshots/image-3.png)

5. Click **Add People**.

![alt text](screenshots/image-4.png)

6. Search for your group members and add them. **Your group members will need to accept the invites from their email inboxes!**

![alt text](screenshots/image-5.png)

## 1.4 Clone the Forked Repository

**Each participant will need to complete these steps:**

1. Copy the URL from the **Code** dropdown.

![alt text](screenshots/image-6.png)

2. Now clone the repo using the URL you copied:

```
git clone https://your-fork.git
```

If you tried to clone the repository and it asks you for a password, **you may need to install [Git Credential Manager](https://github.com/git-ecosystem/git-credential-manager/tree/main)** to proceed. But this should only happen if you're on Linux or macOS.

## 2. The Scavenger Hunt

Okay, with setup out of the way you can finally start scavenger hunting! 🎉

Your team has been assigned the task of maintaining a long forgotten project which used to run your company's super high-tech computer network.

But the maintainers have gone missing and it's up to you to get it back to its former working glory!

Lucky for you, you've been sent some helpful instructions on how to get started:

> Dear new maintainers,
> 
> This project is riddled with bugs and unnecessary branches. There's a to-do list in the main code file and instructions on how to organize your team in CONTRIBUTING.md. You may find those useful.
> 
> Thanks and good luck,
> [Inked out name]
> 
> PS. You may need to install Python

...Well, that was sort of helpful. Anyways, good luck!

## 3. Running

(To-do)
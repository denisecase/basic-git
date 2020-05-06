# Basic Git

> Just the basics.

## Recommendation

- Create a **projects** root folder on your local computer to hold all repositories (repos).
- This 'projects' folder is NOT under source control.
- All of its SUBFOLDERS are individually under source control.

---

## Process Options

- A: Start on your local machine & push up to cloud
- B: Start in the cloud & clone to local machine

---

## Option A: Start on your local machine

### A.1: Start local project

Create a new subfolder under your projects root folder. Use your local IDE to create your app in this subfolder. Use all lower kebob case for the folder name (e.g. my-app).

Include:

- .gitignore
- README.md

### A.2: Create cloud repo

- Create a cloud repo with same name as the local repo, e.g. my-app.
- Get the HTTPS URL (see the suggested commands)

### A.3: Initialize, add & commit, then push

When ready to move the project under source control (use the URL from your new cloud repo below):

```Bash
git init
git remote add origin https://github.com/denisecase/basic-git.git

git add --all
git commit -m "first commit"

git push origin master
```

---

## Option B: Start in the cloud

### B.1: Create cloud repo

- Create a cloud repo - use all lower kebob case for the folder name (e.g. my-app).

### B.2: Clone project

Click the 'Clone or download' button to get the HTTPS URL of the project repo. 

Open Git Bash in your root projects folder (described above). Use the following to duplicate the repo as a subfolder.

```Bash
git clone https://github.com/denisecase/basic-git.git
```

---

## Basic Git Commands

- [git init](https://git-scm.com/docs/git-init)
- [git remote](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes) add origin
- [git add](https://git-scm.com/docs/git-add) --all
- [git commit](https://git-scm.com/docs/git-commit) -m "message"
- [git push](https://git-scm.com/docs/git-push) origin master
- [git clone](https://git-scm.com/docs/git-clone)

## Learn More

- [Everyday Git commands you will use as a Developer](https://medium.com/@paulrohan/everday-git-commands-you-will-use-as-a-developer-e84b4a327036)

---

## Repository

- <https://github.com/denisecase/basic-git>
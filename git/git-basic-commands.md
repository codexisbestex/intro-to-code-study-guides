# Git

## Git info

1. What is git?

- Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows. Git is an open sourced distributed version control system.
-

## Elements of git

1. What is a repository?
   - A repo is a folder inside a project that keeps track of your project history/updates.
2. What is a commit?
   - A snapshot of the repo at a specific moment
3. What is a branch?
   - Branches are a way to add new features that don't interfere or affect the main project
4. What is merging?
   - Putting forked branch histories together; this is where you merge commits by selecting the parts of each branch's latest commit to apply to the merge branches next commit.
     - `main & fix/headerStyling`
5. What is a remote?

- A server that contains a copy of the git repo typically at an online address.

6. What is `HEAD`?
   - The pointer to the current commit you are viewing

## Common git commands

- `git status`
- `git init`
- `git remote`
- `git branch`
- `git add .`
- `git commit`
- `git push origin`/ `git push -u origin`

### Setup and config

#### `git config`

What can `git config` be used to do?

- Set up basic information in the repo

##### Using `git config`:

1. Set your user name as it will appear on commits you make

```shell
git config --global user.name "Angelique Rivera"
```

- Global is a flag that allows you to set universal values for git

2. Set your user email as it will appear on commits you make

```shell
git config --global user.email "angeliqueriveramorales@gmail.com"
```

### Getting and creating projects

#### `git init`

What can `git init` be used to do?

- Initiates an empty git repo

##### Using `git init`:

1. Create a project called `my-awesome-repo`

```shell
git init my-awesome-repo
```

#### `git clone`

What can `git clone` be used to do?

- Clone an established repo
- Creates remote tracking branches for each branch in the cloned repo
- Creates and checks out an initial branch that is forked from the cloned repo's currently active branch

##### Using `git clone`:

1. Clone a project from a local repo on your device: `<home dir>/programming/local-repo`

```shell
git clone <home dir>/programming/local-repo
```

2. Clone a project from a remote repo: `https://github.com/chrismejia/intro-to-code-study-guides.git`

```shell
git clone https://github.com/chrismejia/intro-to-code-study-guides.git
```

### Basic snapshotting

What is 'snapshotting' in the context of git?

- Staging and committing new content in your repo

#### `git add`

What can `git add` be used to do?

- Staging any new changes
- Updates the index using the current content found in the working tree aka what's different between the last commit snapshot and the current state of the files to prepare for a commit

##### Using `git add`:

1. Add the new file, `new-code.js`, to the staging area.

```shell
git add new-code.js
```

2. Add the new file, `new-code.js`, and the modified file, `changed-code.js`, to the staging area.

```shell
git add new-code.js changed-code.js
```

3. Add all new and modified files to the staging area.

```shell
<command here>
```

#### `git commit`

1. What can `git commit` be used to do?

##### Using `git commit`:

1. Commit the staged with, `new-code.js`, to the staging area.

```shell
<command here>
```

2. Add the new file, `new-code.js`, and the modified file, `changed-code.js`, to the staging area.

```shell
<command here>
```

3. Add all new and modified files to the staging area.

```shell
<command here>
```

#### `git restore`

What can be `git restore` be used for?

##### Using `git restore`

1. You've accidently staged the file, `unfinishedFunc.js`, before it was ready to be committed; unstage it.

```shell
<command here>
```

2. You've realized you don't want to keep the changes you've made to `changedFunc.js`; return the repo back to the state it was in before you added that file.

#### `git status`

What does `git status` do?

When can you use `git status` in the snapshotting process?

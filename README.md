# Sprint-based Technical Onboarding

This is an opinionated definition of Sprints to pick up the fundamentals of version control with GitHub and Visual Studio Code.

## Sprints

### Sprint 1: Version control and Github

- [ ] Do: [Hello World!](https://guides.github.com/activities/hello-world/)
- [ ] Read: [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)

### Sprint 2: Collaborating and communicating around code

- [ ] Read: [Communicating with Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)
- [ ] Read: [Forking projects](https://guides.github.com/activities/forking/)
- [ ] Do: Fork this repository, add tick marks for tasks within this document that you'd completed (You can just use the edit function in GitHub to do this).

> Hint: The syntax for a checkbox with a tick mark is ``` - [x] ```

### Sprint 3: Getting familiar with VS Code as an IDE

- [ ] Do: [Download and install VS Code](https://code.visualstudio.com/download)
- [ ] Do: [Clone the **fork (your fork)** of this repository locally using VS Code](https://code.visualstudio.com/docs/editor/versioncontrol#_cloning-a-repository)

### Sprint 4 Be aware of the Integrated Terminal

- [ ] Read: [Learn how to bring up the Integrated Terminal in VS Code](https://code.visualstudio.com/docs/editor/integrated-terminal)
- [ ] Do: Bring up the Integrated Terminal in your VS Code. In the Bash command line, do:
```
$ git remote add upstream https://github.com/vitoc/gitstarted.git
```
- [ ] Do: From the command line, check for updates from upstream:
```
$ git pull upstream master
```
> Always pull from upstream first whenever you start working on an issue with a new branch.

### Sprint 5 Edit locally and push to remote 

- [ ] Do: Continuing from the previous sprint, make a local edit in VS Code by adding the
  keyboard shortcut to open the Integrated Terminal here:

```
REPLACE WITH KEYBOARD SHORTCUT
```

- [ ] Do: [Commit and push this back to your forked repository.](https://code.visualstudio.com/docs/editor/versioncontrol#_commit)

## Optional and additional resources
* [GitHub Learning Lab](https://lab.github.com/)
* [GitHub Training & Guides](https://www.youtube.com/githubguides)

## Next steps for DevOps

* [GitHub Actions](https://lab.github.com/githubtraining/github-actions:-hello-world)
* [Continuous Delivery to Azure](https://lab.github.com/githubtraining/github-actions:-continuous-delivery-with-azure)
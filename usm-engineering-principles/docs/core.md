# Core Principles

Anything that is "core" to our beliefs or you don't know where else to put goes in here. We can always move things around later.

## Be nice to future you

Whenever you make a change, take a moment to imagine how it will impact you or your team 6 months or a year down the line. Some questions you might want to ask yourself are:

* Am I going to remember this?
* Will it make things harder to change?

### Useful documentation

Our repositories should be self-documented. All the information needed to get up and going should be right there. If you have a script that makes your life easier, spend the extra 15 minutes to document it and push it in a PR.

Git messages, PR descriptions & comments, code comments also count as documentation. 

### Intention revealing names

Use intention revealing names for your class, variables, and function names. This may seem less important while you’re deep in the context but 6 months later you will thank yourself. Your team will too.

### Refactoring

Make sure you’re set up to allow for frequent refactoring. Have confidence that automated tests will keep the quality up. Make changes in small increments and avoid major merges with conflicts. Get frequent, early feedback by running tests as part of the CI/CD pipeline and on PRs.

## Single Responsibility

Consider the single responsibility principle even sometimes at the expense of DRY (don’t repeat yourself). We should not avoid code duplication at the expense of code maintainability.

## Simplicity

> Simplicity--the art of maximizing the amount
> of work not done--is essential.

Simplicity is a core [principle of agile principles](https://agilemanifesto.org/principles.html). Simple code is easy to maintain. When in doubt, choose simple over complicated.

## Use accepted by community tools and libraries

We prefer to use tools and libraries that are widespread over the community for your language, framework, etc.
Community accepted tools, libraries are usually well documented, tested, and receive updates/fixes more frequently. 
Also, you can get help from the community easier and faster when a tool is commonly used in the community.
Any developer who will work with your project in the future might need to learn new tools and it's a way easier with good documentation and reach the community.

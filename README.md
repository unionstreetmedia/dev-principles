# Union Street Media Engineering Principles

## Culture

- [be nice to future you](docs/be-nice-to-future-you.md)
- choose [simple over complicated](docs/simple-over-complicated.md)
- approach [building software as a craft](http://manifesto.softwarecraftsmanship.org/)
- [value agile over scrum/kanban/other framework](docs/agile.md)

## Building Software

- working software is the primary measure of progress
- use tools and libraries that are well supported in the community
- prioritize code maintainability over code duplication
- set yourself up for [frequent refactoring](https://martinfowler.com/bliki/OpportunisticRefactoring.html)
- use [intention revealing names](docs/descriptive-names.md)
- write self documenting code
- don't leave [broken windows](https://blog.codinghorror.com/the-broken-window-theory/) unrepaired

## Code Reviews
Pending code reviews represent blocked threads of execution. To prevent getting blocked for more
time than is necessary, follow these basic principles (inspired by
[Glen Stanford](https://medium.com/@9len/on-code-review-16ea85f7c585)):

### Reviewers

- make code reviews your top priority
- be thorough each and every time

### Submitters

- make your pull requests a pleasure to read
  - write good titles and descriptions
  - keep review requests as small as possible
- dot your i's and j's:
  - carefully review the diff
  - make sure you wrote code you like
  - run automated tests prior to submission

## Quality

- prioritize quality over speed | [the only way to go fast is to go well](http://butunclebob.com/ArticleS.UncleBob.VehementMediocrity)
- [test, automate, test, automate](docs/automate-tests.md)
- tend your [test garden](docs/automate-tests.md#tend-your-test-garden)

## Continuous Delivery

We strive to [deliver continuously](https://continuousdelivery.com/) into production in order to get new functionality into the hands of users safely and quickly.

- [if it hurts, do it more often](https://medium.com/continuousdelivery/if-it-hurts-do-it-more-often-f5a00cc12ffa)
- [use automated code formatters](docs/format-code-automatically.md)

## Inspired from:

- https://github.com/daftlabs/creed
- http://engineering-principles.onejl.uk/

# Quality Principles

Anything that has to do with code and software quality goes here

## Test, automate, test, automate

Design and code with testing in mind. Starting with the unit test, write it as soon as you write the code (or even sooner of you're a TDD purist). Thinking about testing as we write the code forces us to write better code, both testable and correct. Automated tests are great because they can be run over and over again at little to no cost. They will help us move faster in the long run and allow our systems to evolve with confidence that we're not breaking existing functionality. 

It is expected for a team to go a little bit slower while ensuring quality is built into the code. When looking at the bigger picture and the ability to *move fast longer term*, having good automated tests is the only way. Uncle Bob calls this [VehementMediocrity](http://butunclebob.com/ArticleS.UncleBob.VehementMediocrity).

Production code should be tested in an automated fashion. Automated tests should be easy to run in a development environment and enable us to find issues before we commit any code. Automated tests should be run as part of the continuous integration pipeline and flag issues as soon as a PR is created. 

## No broken windows

Broken windows are those things we know are bad but we do them anyway. Sometimes it's because we want to move fast, sometimes we've inherited them and we just follow past conventions. Software systems degrade through broken windows at an exponential rate. A broken window makes it ok for others to be broken. And other broken windows appear all over the place. How many times have you thought 'I could spend more time to do it right but it's done wrong all over this file, why should I change it?'. 

No broken windows means we hold ourselves accountable to make changes and either repair existing broken windows by paying back some technical debt or stop creating new ones. 

These two articles tell the story of broken windows much better:

- <https://pragprog.com/the-pragmatic-programmer/extracts/software-entropy>
- <https://blog.codinghorror.com/the-broken-window-theory/>
# Test, automate, test, automate

Design and code with testing in mind. Starting with the unit test, write it as soon as you write the code (or even sooner of you're a TDD purist). Thinking about testing as we write the code forces us to write better code, both testable and correct. Automated tests are great because they can be run over and over again at little to no cost. They will help us move faster in the long run and allow our systems to evolve with confidence that we're not breaking existing functionality.

It is expected for a team to go a little bit slower while ensuring quality is built into the code. When looking at the bigger picture and the ability to *move fast longer term*, having good automated tests is the only way. Uncle Bob calls this [VehementMediocrity](http://butunclebob.com/ArticleS.UncleBob.VehementMediocrity).

Production code should be tested in an automated fashion. Automated tests should be easy to run in a development environment and enable us to find issues before we commit any code. Automated tests should be run as part of the continuous integration pipeline and flag issues as soon as a PR is created.

## Tend your Test Garden

A test suite is like a garden. When you're first getting started, there is a lot of ground to cover
and a lot of work to do. In time and with good care, we reap the rewards of a properly tended test
suite.

### Gardens

We start with the most necessary parts: clearing an area, tilling and prepping the soil, and
planting the seeds are the building blocks of a prosperous garden. It is a lot of work to start a
garden, but there is promise and hope of a bountiful harvest.

At first, plants take a while get going. Weeds start taking over since your seeds have not had time
to establish. It's hard to see progress and it's a little overwhelming. It seems like the effort
might not be worth the reward.

As time goes on, it becomes easier and easier to care for your garden. It only requires some light
weeding and watering. The garden is part of your routine.

Before you know it, you have a fully fledged garden and you're harvesting the fruits of your labor.
You start making plans for next year. Expand the area, plant new things, and trying seed starts
in early Spring. Who knows what you and your garden can achieve?

### Test Suites

We start with the most necessary parts: choosing and setting up the test runner, ensuring tests run
automatically, and writing the tests are the building blocks of a reliable test suite. It is a lot
of work to start a test suite, but there is promise and hope of ensured quality.

At first, tests may be flaky or don't run correctly and need to be fixed. There are a lot of tests
to write and patterns haven't had time to establish themselves. It's hard to see progress and a
little overwhelming. It seems like the effort might not be worth the reward.

As time goes on, it becomes easier and easier to care for your test suite. It only requires some
light fixes and new tests that come with features. The test suite is part of your routine.

Before you know it, the test coverage chart is looking solid and you're running the tests
constantly to check your work. You start feeling confident about your tests catching bugs and
preventing problems. The more tests you write, the more you want to write tests. You can
confidently refactor large areas of the code knowing your tests will catch important issues. Who
knows what you and your test suite can achieve?

[< back](../README.md)

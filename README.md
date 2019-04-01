# Codecademy Open Source Practices

Codecademy open source guidelines and recommendations!
Do we open source things?
What do we open source?
Let's find out!
🙌

## Preliminary preparation

### What not to open source

Generally, anything related to our mission-critical or business-exclusive IP _(intellectual property)_.
That includes, but is not limited to:

* Internal code evaluation services
* Content authoring toolsets
* Payments handling
* Super secret projects the world isn't ready for yet

Note that _"old, sloppy code"_ is not on that list of exclusions.
We understand nothing is perfect and code rots over time.

### What to open source

Ideally, most everything else!
We'd like to err on the side of openness.
Sections of code that can be made generic should, when reasonably possible, be opened so the community can benefit from them as well.

### First steps

Before creating a new open source repository or releasing an existing one:

1. Ask your EM to approve the idea of open sourcing your component(s)
2. Ask your department head to approve the idea of open sourcing your component(s)
3. Code review files in the code for insensitive language or sensitive items _(e.g. AWS secrets)_
4. Ask your EM for a similar code review
5. Run a tool to check for sensitive items in Git history

## Project paperwork

Oh boy, you're ready to create a repository on GitHub! It should contain at least the following:

* `.circleci/config.yml` and PR builds set up with CircleCI
* `LICENSE.md`, preferably with the MIT license
* `README.md` containing at least:
    * Title, GitHub badges for relevant tooling, and a concise explanation of the project
    * Clear documentation for the following, each either in the README.md or a linked docs file:
        * Basic and advanced usage instructions 
        * Development requirements and instructions
    * Link to the [Contributor Covenant](https://www.contributor-covenant.org) as the code of conduct

Also see:

* [./template](./template) as our recommended starting repository files
* [console-fail-test](/) as an example

## Popular promotions

Fun things you can do to spread the brand! We recommend going through at least some of these to get more eyes on the project. It helps your personal brand and ours!

* Solicit teammates to star the GitHub repository
* Tweet it out and tag the [Codecademy](https://twitter.com/Codecademy)‏ account
* Publish a Medium article

## Contribution Guidelines

Please note that this project is released with a [Contributor Covenant](https://www.contributor-covenant.org).
By participating in this project you agree to abide by its terms.
See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

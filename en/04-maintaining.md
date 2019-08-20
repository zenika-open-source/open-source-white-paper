# Chapter 4: Maintaining

In a [previous article](https://oss.zenika.com/white-paper/getting-started), we helped you submitting your first contribution. You now want to launch your own open source project but you don't know what to do before letting everyone view your code ? No worries, in this article we will give you all pre-requisites you need to launch your project, methods to facilitate contributions and tools to help you maintain your project in the long term.

## Pre-requisites before launching your project

If you want your project to have contributions you need to write a minimum of documentation. There are four files that are essential:

- README
- License
- Contributing guide
- Code of conduct

We will describe each one and provide you guides to help you writing them.

### README

The first is well known and you probably already have one but let's talk a bit about README.md. 

Mike McQuaid theorized about [the open source contributor funnel](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/) and how to get contributors on your open source projects. You need to provide informations for every type of visitors (*users*, *contributors*) in your README.

> Your project description and first paragraph of your README should be a simple summary of your project which hits all the important keywords that people search for.
> -- [<cite>Andrey Petrov</cite>](https://medium.com/code-zen/how-to-maintain-a-successful-open-source-project-aaa2a5437d3a)

First of all, nobody is in your head. You should explain the **goal** of your project. It doesn't have to be an essay a single sentence is good enough like in [Conference Hall README](https://github.com/bpetetot/conference-hall).

> **Conference Hall** is an opened SaaS platform to manage call for papers and speakers submissions for your conferences and meetups. Speaker writes a talk once and can submit it to every events of the platform.

This section is the first thing a new comer read on your project, you need to catch his attention.

Another important part to document in your README is how to install and use your project. It is essential for *users* so they can easily test it. Gatsby does a good job explaining how to have a website [running in 5 minutes](https://github.com/gatsbyjs/gatsby#-get-up-and-running-in-5-minutes) with their cli. 

Last but not least you should provide instructions for future contributors. A simple section that link your contributing guide is most of the time enough.

A simple [template](https://www.makeareadme.com/#template-1) is available on makeareadme.com. It contains all the sections we talked about. You can find more informations about how to write a good README on this website. You can also use tools to generate your README like [readme-md-generator](https://github.com/kefranabg/readme-md-generator). It fill your README with informations extracted from git configuration or your `package.json` file if your project is made with JavaScript. You can find [README generators](https://github.com/search?utf8=%E2%9C%93&q=generate+readme&type=Repositories) for other languages on GitHub.

### License

The LICENSE file is what make open source possible. It protects *users* and *contributors* by giving them rights to use, copy, modify and contribute to your project. This file is mandatory you should consider not contributing to projects that don't provide a license.

[OSI](https://opensource.org/) is an organism that promote open source software and communities for over 20 years. They have an process to review licenses. The OSI-approved licenses are the most popular licenses like [MIT](https://opensource.org/licenses/MIT) or [Apache 2.0](https://opensource.org/licenses/Apache-2.0). We can find a [good comparision](https://choosealicense.com/licenses/) between licenses on [choosealicense.com](https://choosealicense.com/).

We will talk more about this important and complicated subject in a further article. If you want to get informed about its publication don't hesitate to follow our twitter [@ZenikaOSS](https://twitter.com/ZenikaOSS)!

### Contributing guide

> A CONTRIBUTING.md file, in your open source repository or site, provides potential project contributors with a short guide to how they can help with your project or study group. It is convention to capitalize the word "contributing" as the file title, and to save it as a resource in markdown (hence the extension .md).
> -- [<cite>Mozilla Science Lab</cite>](https://mozillascience.github.io/working-open-workshop/contributing/)

Earlier we talked about **The open source contributor funnel** in our README we provided documentation to help *users* installing and using your project, you will now focus on *contributors*. The contributing guide is made to give instructions to everybody that want to participate on your projects.

Most of the time contributions are made by users because they encounters a problem using your project. It's nice to a have information on how to report a bug or suggest a new feature.

If you want code contributors you need to give all details about how to set up development environment and how to submit their contributions. [Mocha's contributing guide](https://github.com/mochajs/mocha/blob/master/.github/CONTRIBUTING.md#shoe-contributing-code-step-by-step) is a good example of step by step instructions to get your contribution merged. 

The contributing guide is also the good place to describe coding styles. You can enforce good practices like testing or conventions like in [Immutadot's contributing guide](https://github.com/zenika-open-source/immutadot/blob/master/.github/CONTRIBUTING.md#tests-and-code-style-policeman).

If your project is on GitHub this file will be [automatically linked](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors) when a contributor open an issue or create apull request.

## Usage 

semver / changelog
Documentation

## Facilitate contributions

Templates
Fun site to generate templates or use Github https://www.talater.com/open-source-templates/#/
Issue triaging
Get confidence in contributions automate tests
Communication

## Automate everything

Bots and Hygie

## Open source doesn't mean free

open collective


# Preparing your project being open sourced

In a [previous article](https://oss.zenika.com/white-paper/getting-started), we showed you how to make your first contribution. You now want to launch your own open source project but you don't know what to do before letting everyone view your code? No worries, in this article we will give you all pre-requisites you need to launch your project.

## Pre-requisites

If you want your project to have contributions you need to write a minimum of documentation. There are four files that are essential:

- Readme
- License
- Contributing guide
- Code of conduct

We will describe each one and provide you guides to help you writing them.

## README

The first is well known and you probably already have one but let's talk a bit about README.md. 

Mike McQuaid theorized about [the open source contributor funnel](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/) and how to get contributors on your open source projects. You need to provide information for every type of visitors (*users*, *contributors*, *maintainers*) in your readme.

> Your project description and first paragraph of your readme should be a simple summary of your project which hits all the important keywords that people search for.
> -- [<cite>Andrey Petrov</cite>](https://medium.com/code-zen/how-to-maintain-a-successful-open-source-project-aaa2a5437d3a)

First of all, nobody is in your head. You should explain the **goal** of your project. It doesn't have to be an essay a single sentence is good enough like in [Conference Hall readme](https://github.com/bpetetot/conference-hall).

> **Conference Hall** is an opened SaaS platform to manage call for papers and speakers submissions for your conferences and meetups. Speaker writes a talk once and can submit it to every events of the platform.

This section is the first thing a new comer read on your project, you need to catch his attention.

Another important part to document in your readme is how to install and use your project. It is essential for *users* so they can easily test it. Gatsby does a good job explaining how to have a website [running in 5 minutes](https://github.com/gatsbyjs/gatsby#-get-up-and-running-in-5-minutes) with their cli. 

Last but not least you should provide instructions for future contributors. A section that link your contributing guide is most of the time enough.

A [template](https://www.makeareadme.com/#template-1) is available on makeareadme.com. It contains all the sections we talked about. You can find more information about how to write a good readme on this website. You can also use tools to generate your readme like [readme-md-generator](https://github.com/kefranabg/readme-md-generator). It fills it with information extracted from git configuration or your `package.json` file if your project is made with JavaScript. You can find [readme generators](https://github.com/search?utf8=%E2%9C%93&q=generate+readme&type=Repositories) for other languages on GitHub.

## License

The LICENSE file is what make open source possible. It protects *users* and *contributors* by giving them rights to use, copy, modify and contribute to your project. This file is mandatory you should consider not contributing to projects that don't provide a license.

[OSI](https://opensource.org/) is an organism that promote open source software and communities for over 20 years. They have an process to review licenses. The OSI-approved licenses are the most popular licenses like [MIT](https://opensource.org/licenses/MIT) or [Apache 2.0](https://opensource.org/licenses/Apache-2.0). We can find a [good comparision](https://choosealicense.com/licenses/) between licenses on [choosealicense.com](https://choosealicense.com/).

We will talk more about this important and complicated subject in a further article. If you want to get informed about its publication don't hesitate to follow our twitter [@ZenikaOSS](https://twitter.com/ZenikaOSS)!

## Contributing guide

> A CONTRIBUTING.md file, in your open source repository or site, provides potential project contributors with a short guide to how they can help with your project or study group. It is convention to capitalize the word "contributing" as the file title, and to save it as a resource in markdown (hence the extension .md).
> -- [<cite>Mozilla Science Lab</cite>](https://mozillascience.github.io/working-open-workshop/contributing/)

Earlier we talked about **The open source contributor funnel** in our readme we provided documentation to help *users* installing and using your project, you will now focus on *contributors*. The contributing guide is made to give instructions to everybody that want to participate on your project.

Most of the time contributions are made by users because they encounter a problem using your project. It's nice to a have information on how to report a bug or suggest a new feature.

If you want code contributors you need to give all details about how to set up project's development environment and how to submit a contribution. [Mocha's contributing guide](https://github.com/mochajs/mocha/blob/master/.github/CONTRIBUTING.md#shoe-contributing-code-step-by-step) is a good example of step by step instructions to get your contribution merged. 

The contributing guide is also the good place to describe coding styles. You can enforce good practices such as testing or conventions like in [Immutadot's contributing guide](https://github.com/zenika-open-source/immutadot/blob/master/.github/CONTRIBUTING.md#tests-and-code-style-policeman).

If your project is on GitHub this file will be [automatically linked](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors) when a contributor open an issue or create a pull request.

## Code of conduct

> Having a CODE_OF_CONDUCT.md in your public repository lets potential *contributors* know in advance how they can expect to be treated by the community and *maintainers*.
> -- [<cite>Michael Jolley</cite>](https://dev.to/michaeljolley/using-a-contributing-codeofconduct-to-assist-others-in-contributing-to-public-repositories-1l90)

The code of conduct of your project is a document that protects every participants. It helps creating a welcoming community. 

A good addition to your code of conduct is an explanation about how you plan to enforce it. It's important to show that you take it seriously so everybody knows what action will be taken in case of a code of conduct violation.

You should also clarify the way to report a violation like an email.

The most famous code of conduct is [Contributor Covenant](https://www.contributor-covenant.org). It is used by thousands of open source projects. If your project is on GitHub you can directly add Contributor Covenant or [Citizen Code of Conduct](http://citizencodeofconduct.org/) through your repository interface. You should go to `Insights > Community > Code of conduct` by clicking on the Add button and choosing a code of conduct it will create a commit for you.

Your project is now ready to be open sourced. You can start promoting it and getting your first contributions!

If you want further news about our projects or future articles don't forget to follow our twitter [@ZenikaOSS](https://twitter.com/ZenikaOSS)!

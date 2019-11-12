# Preparing your project being open sourced

In a [previous article](https://oss.zenika.com/white-paper/getting-started), we helped you submit your first contribution. Now you want to launch your own open source project but you don't know what to do before letting everyone view your code? No worries, in this article we will give you all the pre-requisites you need to launch your project.

## Pre-requisites

If you want your project to have contributions you need to write at least some documentation. There are four essential files:

- Readme
- License
- Contributing guide
- Code of conduct

We will describe each one and provide you some guidance to help you write them.

## README

The first one is well known and you probably already have one, but let's talk a bit about README.md.

Mike McQuaid theorized about [the open source contributor funnel](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/) and how to get contributors on your open source projects. You need to provide information for every type of visitors (_users_, _contributors_, _maintainers_) in your readme.

Your project description and first paragraph of your readme should be a simple summary of your project which hits all the important keywords that people search for. -- [Andrey Petrov](https://medium.com/code-zen/how-to-maintain-a-successful-open-source-project-aaa2a5437d3a)

First of all, nobody is in your head. You should explain the goal of your project. It doesn't have to be an essay though, a single sentence is good enough like in [Conference Hall’s readme](https://github.com/bpetetot/conference-hall):

> Conference Hall is an opened SaaS platform to manage call for papers and speaker's submissions for your conferences and meetups. As a speaker you write a talk once and submit it to every event you want, within the platform.

This section is the first thing a newcomer will read on your project, hence you need to catch their attention.

Another important part to include in your readme is how to install and use your project. It is essential for _users_ to be able to easily test it. Gatsby does a good job explaining how to have a website [running in 5 minutes](https://github.com/gatsbyjs/gatsby#-get-up-and-running-in-5-minutes) with its CLI.

Last but not least, you should provide instructions for future contributors. Most of the time, a section that links to your contributing guide is enough.

For starters, a [template](https://www.makeareadme.com/#template-1) can be found on makeareadme.com. It contains all the sections we've talked about. There, you can find more information about how to write a good readme.  
Furthermore you can use tools to generate your readme, like [readme-md-generator](https://github.com/kefranabg/readme-md-generator). It fills your file with information extracted from your Git configuration (or specifically from the `package.json` file if your project is made with JavaScript). You can find other [readme generators](https://github.com/search?utf8=%E2%9C%93&q=generate+readme&type=Repositories) for various languages on GitHub.

## License

The LICENSE file is what makes open source possible. It protects both _users_ and _contributors_ by giving them rights to use, copy, modify and contribute to your project. This file is mandatory, hence you should consider not contributing to projects that don't provide a license.

[OSI](https://opensource.org/) is an organism that has been promoting open source software and communities for over 20 years. They have a process to review licenses. The OSI-approved licenses are the most popular ones like [MIT](https://opensource.org/licenses/MIT) or [Apache 2.0](https://opensource.org/licenses/Apache-2.0). You can find a [good comparison](https://choosealicense.com/licenses/) between licenses on [choosealicense.com](https://choosealicense.com/).

## Contributing guide

A CONTRIBUTING.md file, in your open source repository or site, provides potential project contributors with a short guide to how they can help with your project or study group. By convention you should capitalize the word "contributing" as the file title, and save it as a resource in Markdown (hence the extension .md). -- [Mozilla Science Lab](https://mozillascience.github.io/working-open-workshop/contributing/)

Earlier we talked about "The open source contributor funnel" in our readme. We provided documentation to help _users_ installing and using your project. Now we will focus on _contributors_. The contributing guide is designed to give instructions to anyone that wants to participate to your project.

Most of the time contributions are made by users that encounter an issue using your project. It's nice to have instructions on how to report a bug or suggest a new feature.

If you want code contributors you need to provide all the details on how to set up the project's development environment and how to submit a contribution. [Mocha's contributing guide](https://github.com/mochajs/mocha/blob/master/.github/CONTRIBUTING.md#shoe-contributing-code-step-by-step) is a good example of step by step instructions to get your contribution merged.

The contributing guide is also the right place to describe coding styles. You can enforce good practices such as testing or conventions like in the [Immutadot's contributing guide](https://github.com/zenika-open-source/immutadot/blob/master/.github/CONTRIBUTING.md#tests-and-code-style-policeman).

If your project is on GitHub, this file will be [automatically linked](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors) when a contributor opens an issue or creates a pull request.

## Code of conduct

Having a CODE_OF_CONDUCT.md in your public repository lets potential _contributors_ know in advance how they can expect to be treated by the community and _maintainers_. -- [Michael Jolley](https://dev.to/michaeljolley/using-a-contributing-codeofconduct-to-assist-others-in-contributing-to-public-repositories-1l90)

The code of conduct of your project is a document that protects every participant. It helps creating a welcoming community.

A good addition to your code of conduct is an explanation about how you plan to enforce it. It's important to show that you take it seriously so everybody knows what action will be taken in case of a violation.

You should also clarify the way to report a violation, such as through an email.

The most famous code of conduct is [Contributor Covenant](https://www.contributor-covenant.org/). It is used by thousands of open source projects. If your project is on GitHub you can directly add Contributor Covenant or [Citizen Code of Conduct](http://citizencodeofconduct.org/) through your repository interface. You need to go to `Insights > Community > Code of conduct`, then by clicking on the Add button and choosing a code of conduct, it will create a commit for you.

Your project is now ready to be open sourced. You can start promoting it and getting your first contributions!

If you want further news about our projects or future articles, consider following us on Twitter [@ZenikaOSS](https://twitter.com/ZenikaOSS)!

# Contributing to Gogs

> This guidelines sheet is forked from [CONTRIBUTING.md](https://github.com/drone/drone/blob/master/CONTRIBUTING.md).

Gogs is not perfect and it has bugs, or incomplete features for rare cases. You're welcome to tell us or contribute some code. This document describles details about how can you contribute to Gogs project.

## Contribution guidelines

Depends on the situation, you will:

- Find bug, create an issue
- Need more functionality, make a feature request
- Want to contribute code, open a pull request
- Run into issue, need help

### Bug Report

If you find or consider something is a bug, please create a issue on [GitHub](https://github.com/gogits/gogs/issues). To reduce unnecessary time wasting of interacting and waiting with team members, please use following form as template in the first place:

```
- **Bug Description**: 
- **Gogs Version**:
- **Git Version**:
- **System Type**:
- **Error Log**:
- **Other information**:
```

Please take a moment to check that an issue on [GitHub](https://github.com/gogits/gogs/issues) doesn't already exist documenting your bug report or improvement proposal. If it does, it never hurts to add a quick "+1" or "I have this problem too". This will help prioritize the most common problems and requests.

#### Bug Report Example

- **Bug Description**: Crash when create repository with license|
- **Gogs Version**: `v0.4.9.0901`
- **Git Version**: `1.9.0`
- **System Type**: `Ubuntu 12.04`
- **Error Log**:

```
2014/09/01 07:21:49 [E] nil pointer
```

- **Other information**: Use SQLite3 as database

### Feature Request

There is no standard form of making a feature request, just try to describle the feature as clear as possible because team members may not have experience with the functionality you're talking about.

### Pull Request

Pull requests are always welcome, but note that **ALL PULL REQUESTS MUST SEND TO `DEV` BRANCH**.

We are always thrilled to receive pull requests, and do our best to process them as fast as possible. Not sure if that typo is worth a pull request? Do it! We will appreciate it.

If your pull request is not accepted on the first try, don't be discouraged! If there's a problem with the implementation, hopefully you received feedback on what to improve.

We're trying very hard to keep Gogs lean and focused. We don't want it to do everything for everybody. This means that we might decide against incorporating a new feature.

### Ask For Help

Before open any new issue, please check your problem on [Troubleshooting](http://gogs.io/docs/intro/troubleshooting.md) and [FAQs](http://gogs.io/docs/intro/faqs.html) pages.

## Things To Notice

Please take a moment to check that an issue on [GitHub](https://github.com/gogits/gogs/issues) or card on [Trello](https://trello.com/b/uxAoeLUl/gogs-go-git-service) doesn't already exist documenting your bug report or improvement proposal. If it does, it never hurts to add a quick "+1" or "I have this problem too". This will help prioritize the most common problems and requests.

### Discuss your design on the mailing list

We recommend discussing your plans [on the mailing list](https://groups.google.com/forum/#!forum/gogits) before starting to code - especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give feedback on your design, and maybe point out if someone else is working on the same thing.

We may close your pull request if not first discussed on the mailing list. We aren't doing this to be jerks. We are doing this to prevent people from spending large amounts of time on changes that may need to be designed or architected in a specific way, or may not align with the vision of the project.
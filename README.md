# Contributions and credit policy for open source projects

## Introduction

A contributions and credit policy is a written policy laying out what contributions to an open source project are welcome, how they will be handled, and how credit will be distributed. This project explains how to design a policy for an open source project, as well as how a policy can save maintainers time and effort.

### Problem: people have different expectations for contributions

Open source software projects receive a wide variety of contributions from many different people and organizations. Each person has their own assumptions and expectations for how a project should respond to a contribution: how or if it is reviewed, whether it is merged, how credit is assigned, whether it will be changed or rewritten, etc.

When there is a mismatch between the expected response and the actual response, both the maintainers and the contributors suffer. This is an especially important problem for open source software because credit is often a major motivation for contributing.

Some concrete examples:

1. [Someone debugs a serious Linux kernel memory error](https://ariel-miculas.github.io/How-I-got-robbed-of-my-first-kernel-contribution/), writes a fix, and sends the change to the maintainer. The maintainer writes a very similar fix and checks it in under his own name, giving the original author credit only for reporting the bug.
2. Someone sends in a contribution, but project maintainers are too overworked to review the contribution. Some time later, another person fixes the same problem without ever seeing the first contribution. The first person accuses them of plagiarism when it was actually a case of two people independently coming up with similar contributions.
3. Someone who has personal connections with the maintainers of an open source project scans the outstanding contributions that have not yet been reviewed. [They rewrite someone else's contribution without crediting them](https://news.ycombinator.com/item?id=37677321) and request review from the maintainers, who review and approve their contribution.
4. A standards body works together to develop and review drafts of standards. People who write early drafts discover that [later drafts use their work without crediting it](https://www.ietf.org/blog/report-experience-of-women-participating-in-the-ietf/).
5. Someone writes a bot that uses AI to scan source code and submit automatically generated contributions, nearly all of which are garbage that waste the reviewers' time. When their contributions are rejected, they criticize the project maintainers.

One thing is clear: people have wildly different expectations for how contributions should be handled.

### Our solution: a written policy

Our proposed solution to this problem is for each project to write down and publish a formal contributions and credit policy. The policy describes what contributions are welcome, how they will be handled, and what kind of credit and acknowledgement contributors can expect.

A policy can reduce maintainer workload in the following ways:

* Maintainers and contributors have more similar expectations for review, merging, and credit
* Maintainers are more likely to get the kind of contributions they want
* Maintainers can refer to the policy when making difficult decisions
* Maintainers can avoid or end arguments by pointing at the policy

## Policy creation guide

For help creating a contributions and credit policy, see the [policy creation guide](policy_guide.md).

## Projects with policies

See the [list of projects with contributions and credit policies](policies.md).

## Related talks and articles

* [Linux Weekly News article by Valerie Aurora](https://lwn.net/Articles/971817/)
* [Talk by Maria Matějka about the policy release at RIPE 88](https://ripe88.ripe.net/archives/video/1371/)
* [Talk by Valerie Aurora proposing a policy at RIPE 87](https://ripe87.ripe.net/archives/video/1218/)

## Contributing

We welcome contributions to this project. Please see our [contributions and credit policy](CONTRIBUTING.md) for more information on how to contribute.

## Credits and license

This contributions and credit policy was created by [Valerie Aurora](https://valerieaurora.org/), Maria Matějka ([project BIRD](https://bird.network.cz/), [CZ.NIC](https://www.nic.cz/)), and other members of the [RIPE Open Source Working Group](https://www.ripe.net/participate/ripe/wg/active-wg/os). See the [CREDITS.md](CREDITS.md) file for a full list of contributors.

This project is licensed Creative Commons Zero ([CC0-1.0](LICENSE)).

We request but do not require that derivative works give credit to the contributors to this project. Example:

> This policy was constructed using the [contributions and credits policy guide](https://github.com/contribution-credit/policy) created by members of the RIPE Open Source Working Group. For a full list of contributors, see https://github.com/contribution-credit/policy/blob/main/CREDITS.md

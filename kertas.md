[](https://info.tea.xyz/tea-white-paper/)

![](https://www.gitbook.com/cdn-cgi/image/width=256,dpr=2,height=40,fit=contain,format=auto/https%3A%2F%2F2873717268-files.gitbook.io%2F~%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnquaL4SJ8uar13sCFHzm%252Flogo%252FRVz1Ooeh2CBG3q18O0oV%252Ffavicon%2520256x256.png%3Falt%3Dmedia%26token%3D12828983-c9e7-4144-8ec6-1c258ed36c6a)

![](https://www.gitbook.com/cdn-cgi/image/width=256,dpr=2,height=30,fit=contain,format=auto/https%3A%2F%2F2873717268-files.gitbook.io%2F~%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnquaL4SJ8uar13sCFHzm%252Flogo%252FRVz1Ooeh2CBG3q18O0oV%252Ffavicon%2520256x256.png%3Falt%3Dmedia%26token%3D12828983-c9e7-4144-8ec6-1c258ed36c6a)

Mencari

⌃K

[](https://info.tea.xyz/tea-white-paper/)

Baca aku

[](https://info.tea.xyz/tea-white-paper/white-paper)

kertas putih

Didukung Oleh GitBook

Comment on page

# white-paper

Version 2.1.0

## 

A Decentralized Protocol for Open-Source Developers to Capture the Value
They Create

  - Max Howell
  - Thomas Borrel
  - Timothy Lewis
  - Troy Wong

## 

Abstract

A system in which open-source developers could receive rewards
commensurate with their contributions would enhance the sustainability
and integrity of the software supply chain. A decentralized protocol
secured by reputation and incentives could accomplish this by
facilitating value accrual back to the developers that maintain
open-source codebases as a public utility, thus promoting future
innovation and growth within the open-source ecosystem. Package
maintainers will register their projects with a registry powered by a
Byzantine fault-tolerant blockchain. The tea Protocol’s unique “Proof of
Contribution” algorithm will determine each project’s contribution and
impact to the system’s utility and health. Registered projects will
receive rewards from the tea Protocol commensurate with their
contribution, be secured through staking, benefit from a reputation
system that spans projects and contributors, and have the option to
allow communities to govern their regions of the open-source ecosystem,
independent of external agendas. The tea Protocol will incentivize the
maintenance of open-source by allowing network participants who
registered their projects and comply with the rules of the network to
receive rewards and contribute to their reputation and their projects’.
If security or development issues are found, developers can make claims
supported by evidence against the package, and slashing may occur.
Members of the open-source community can review packages for quality
issues, and the protocol can respond to these reviews by enacting
proportional slashing events.

## 

Disclaimer

The information set out in this white paper is of a preliminary nature.
Consequently, neither the authors nor any of their respective affiliates
assume any responsibility that the information set out herein is final
or correct and each of the foregoing disclaims, to the fullest extent
permitted by applicable law, any and all liability whether arising in
tort, contract or otherwise in respect of this white paper. Neither this
white paper nor anything contained herein shall form the basis of or be
relied on in connection with or act as an inducement to enter into any
contract or commitment whatsoever.

Nothing in this white paper constitutes an offer to sell or a
solicitation to purchase any tokens discussed herein. In any event, were
this white paper to be deemed to be such an offer or solicitation, no
such offer or solicitation is intended or conveyed by this white paper
in any jurisdiction where it is unlawful to do so, where such an offer
or solicitation would require a license or registration, or where such
an offer or solicitation is subject to restrictions. In particular, any
tokens discussed herein have not been, and, as of the date of issuance
of this white paper, are not intended to be, registered under the
securities or similar laws of any jurisdiction, whether or not such
jurisdiction considers such tokens to be a security or similar
instrument and may not be offered or sold in any jurisdiction where to
do so would constitute a violation of the relevant laws of such
jurisdiction. Do not purchase any tokens unless you’re prepared to lose
the entire purchase price. It is a high-risk purchase and you are
unlikely to be protected if something goes wrong.

## 

License

This paper is available under the [Creative Commons
Attribution-ShareAlike 4.0 International
license](https://creativecommons.org/licenses/by-sa/4.0/).

## 

Introduction

The modern-day Internet is predominantly composed of open-source
projects and has been since its inception. Open-source projects are
developed and maintained via collaboration amongst global developer
communities, and their codebases are made available for anyone to
utilize as a public good. In the past 80 years (it is [generally
believed](https://archive.org/details/historyofmodernc00ceru) that the
first example of free and open-source software was released in 1953),
open-source software has evolved from the product of niche technology
hobbyists to the infrastructure upon which all innovation has been
built. Despite the importance of open-source software, the developers
that create and maintain the codebase as a public utility receive no
fungible rewards for their immense contribution as innovators and
maintainers.

Enterprise software, which has grown into a multi-billion dollar
industry, is built on the foundation laid by open-source. Yet there is
almost no value accrual back to the individuals who thanklessly maintain
its very underpinnings. And while fortunes have been made from it,
open-source software is mainly created and maintained as a public
utility with no viable means for developers to capture the value they
create.

We believe that the potential of the modern-day internet has been
stunted by relying on a small percentage of the world’s engineers to
maintain open-source software purely out of altruism. Open-source is a
labor of love often hindered by a lack of meaningful incentives for core
maintainers. Open source developers must choose between a day job that
provides living wages or maintaining the very foundation of enterprise
software. A lack of incentives results in genuinely worthwhile projects
never reaching their potential while others suffer from security issues
due to a lack of upkeep throughout the software’s lifecycle. To unlock
the full potential of open-source, we require a universal method for
assessing the “fair value” of open-source projects, enabling open-source
developers to capture the value they create by facilitating capital
inflows to the open-source community, all without altering the core
principles of how open-source is developed and used.

Enterprises often wrap business models around open-source, generating
revenue directly from the work of the benevolent developers while also
relying on them to fix bugs as issues occur. Open-source codebases offer
plug-and-play core functionality for enterprises; however, software
vulnerabilities can pose an immense risk for applications built on top
of open-source. A great example is a recent incident involving a
critical security vulnerability in Log4j, a package from the [Apache
Software Foundation](https://www.apache.org/) that found its way across
many commercial software and services employed by enterprises and
governments. In November 2021, a security researcher working for
[Alibaba Group Holding Ltd.](https://www.alibabagroup.com/) reported
vulnerability
[CVE-2021-44228](https://nvd.nist.gov/vuln/detail/CVE-2021-44228), which
received the highest possible base score from the Apache Software
Foundation. Amit Yoran, Chief Executive of
[Tenable](https://www.tenable.com/) and founding director of the United
States Computer Emergency Readiness Team (US-CERT), described this
vulnerability as “[the single biggest, most critical vulnerability of
the last
decade](https://www.reuters.com/article/usa-cyber-vulnerability-idCNL1N2SY2PA)”.
Panic ensued and the few volunteers who maintained this package came
publicly under fire for the failure. After addressing the outrage with a
humble plea for fairness, systems got patched. Enterprises and
governments eventually realized that Log4j, a package used by a broad
range of critical systems for two decades, was maintained by a few
unpaid volunteers, the same unsung heroes who sprang into action despite
[abuse from the
industry](https://twitter.com/yazicivo/status/1469349956880408583) and
worked tirelessly to address the vulnerability.

Sadly, Log4j is far from the only example. core-js is downloaded 30
million times per week as the base of every Node.js application, yet it
is also barely funded, potentially forcing it’s primary maintainer to
[walk away from the project or even change the license to closed
source](https://www.thestack.technology/core-js-maintainer-denis-pusharev-license-broke-angry/).
Recently several bitcoin core developers resigned, citing, among other
reasons, a lack of financial compensation for their decision.

![](https://2873717268-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnquaL4SJ8uar13sCFHzm%2Fuploads%2F74Kvn7zgrBPPYKqEuyuw%2Fxkcd-dependency.png?alt=media&token=2fd6186f-6e7a-456f-a594-0da433f3977b)

Figure 1 - Dependency - Source: <https://xkcd.com/2347/>​

There have been multiple attempts at providing incentive structures,
typically involving sponsorship and bounty systems. Sponsorship makes it
possible for consumers of open-source to donate to the projects they
favor. However, picture open-source as a tower of bricks where lower
layers are long forgotten, but still maintained by dedicated engineers
and relied upon by even more developers. Only projects at the top of the
tower are typically known and receive sponsorship. This biased selection
leads to essential bricks that hold up the tower attracting no
donations, while favorites receive more than they need. Bounties allow
consumers of projects to propose payment for developers to build
specific features, thus only rewarding projects for doing things that
may not be in their best interest. And again, only rewarding favorites.

At tea, we’ve seen too many open-source projects suffering from these
failed attempts at supporting the open-source community and have made it
our mission to enhance the sustainability and integrity of the software
supply chain by allowing open-source developers to capture the value
they create.

In this paper, we propose tea — a decentralized system for

1.  1\.
    computing and assigning a “[Proof of
    Contribution](https://info.tea.xyz/tea-white-paper/white-paper#proof-of-contribution)”
    to every open-source project relative to the entire ecosystem,
2.  2\.
    ensuring open-source software projects are well maintained,
3.  3\.
    empowering open-source developers with equitable rewards
    proportionate to their ecosystem-wide contributions, achieved
    through the implementation of the tea incentive algorithm across
    every entry in the tea registry, and
4.  4\.
    incentivizing network participants to follow responsible disclosure
    practices for vulnerabilities and bugs.

## 

Components

A software developer building an application needs four things: a
browser, a terminal, an editor, and a package manager. Of these four,
the package manager is what controls the tooling and frameworks a
developer needs to construct their product. This layer is where we see
the potential to change how open-source is secured and rewarded.

### 

The Package Manager

The package manager knows what open-source software a package or
application depends upon to function, from the top of the tower to its
base. Each project, along with every packaged version, meticulously
documents all essential components and their corresponding versions.

It knows that the top of the tower carefully selects its dependencies,
and that careful selection continues down. The package manager is
uniquely placed in the developer tool stack to enable automated and
precise value distribution based on actual real-world contribution.

We propose an immutable decentralized registry designed to distribute
value based on the tea Protocol’s unique “Proof of Contribution”, an
algorithm that determines each project’s contribution and impact to the
system’s utility and health. Value can enter the graph at apex
points—such as essential libraries—and be distributed to the
dependencies of those packages and their dependencies recursively since
the registry knows the entire open-source graph.

Additionally, we believe that the information provided by the protocol’s
Proof of Contribution must be available for developers to assess whether
they can trust a project and its author. This information may be based
on reputation, community kudos, data retrieved from decentralized
identity ("[DID](https://www.w3.org/TR/did-core/)") systems, other
package managers, or incentive mechanisms that potentially rely on
network participants putting value at risk.

We predict that tea’s combination of tools, information, and rewards
will justly incentivize developers, helping secure the software supply
chain, stimulating the growth of open-source software, and fostering
innovation.

### 

The Decentralized Registry

Every package manager has its own package registry duplicating the same
metadata repeatedly. In some cases, this registry may include
[information that differs from the project’s
manifest](https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-attacks/),
thus allowing bad actors to potentially inject nefarious code
unbeknownst to the user. It’s time there was a single, comprehensive,
and definitive registry designed and governed by the communities that
depend on it. This decentralized, immutable registry could provide
security, stability and prevent malevolent intent.

The Internet runs on tens of thousands of vital open-source components.
It’s remarkable that thus far, incidents caused by the removal of
essential open-source infrastructure have been minimal. The most famous
was the [removal of an NPM left-pad
dependency](https://www.theregister.com/2016/03/23/npm_left_pad_chaos/)
in 2016, which cascaded into continuous integration and continuous
deployment systems, leaving developers high and dry for days. This event
demonstrated that the Internet itself is based on fragile systems of
development. Other examples involved active or intentional participation
from the package maintainers sabotaging their popular packages (See
[colors.js and
faker.js](https://fossa.com/blog/npm-packages-colors-faker-corrupted/),
as well as
[node-ipc](https://www.lunasec.io/docs/blog/node-ipc-protestware/)), or
bad actors looking to profit by pretending to help maintain packages and
corrupting them to steal, for example, Bitcoin private keys (See
[event-stream](https://github.com/dominictarr/event-stream/issues/116)),
or malicious packages with intentional misspelling errors, also known as
“[typosquatting](https://en.wikipedia.org/wiki/Typosquatting)”, in the
hope of tricking users into installing them, for example [crossenv vs.
cross-env NPM
packages](https://blog.npmjs.org/post/163723642530/crossenv-malware-on-the-npm-registry.html).

Software integrity needs to be guaranteed as the industry progresses
towards a future where digital assets are part of the software. We
cannot continue to leave ourselves vulnerable to malicious actors
modifying the software.

Most tools that we call package managers cannot guarantee that these
packages built into the apps and dApps are the unaltered open-source
code published by their original authors. [Microsoft’s GitHub has found
that 17% of vulnerabilities in software were planted for malicious
purposes](https://www.zdnet.com/article/open-source-software-how-many-bugs-are-hidden-there-on-purpose/),
with some remaining undetected for extended periods (See
[Webmin 1.890](https://threatpost.com/backdoor-found-in-utility-for-linux/147581/)).

A global decentralized registry augmented by a reputation system and
supported by incentives designed to expose bad actors and reward good
ones may provide the guarantees developer communities have been looking
for to secure the software supply chain.

### 

The Storage System

Open-source projects deliver a broad range of functionality, some of
which may be restricted or unwanted. Encryption is an excellent example
of that. A critical use case for encryption is the support of
individuals’ privacy across the globe. Encryption, however, can also be
used for nefarious purposes (see [Phantom
Secure](https://www.fbi.gov/news/stories/phantom-secure-takedown-031618),
dismantled by law enforcement agencies in March 2018) or may be
compromised to support law enforcement activities (See [Operation
Ironside (AFP), Operation Greenlight (Europol), and Operation Trojan
Shield
(FBI)](https://www.europol.europa.eu/media-press/newsroom/news/800-criminals-arrested-in-biggest-ever-law-enforcement-operation-against-encrypted-communication)
where the FBI operated an “encrypted” communication platform, AN0M, and
convinced criminals to use their “encrypted” phones for secure
communication).

Encryption’s broad applications have made it a perfect use case for
open-source software and a great example that any solution that stores
packages must be tamper-proof and censorship-resistant. tea is a
decentralized protocol that does not intend to filter or sanction
packages based on their functionality. While the tea governance may
elect to remove proven malicious packages (see the [governance
section](https://info.tea.xyz/tea-white-paper/white-paper#governance)
for more information), it is critical for the tea system to connect with
multiple storage systems, including decentralized ones that demonstrate
that a package is unaltered and correctly replicated. Package
maintainers may choose the storage system best suited for their need to
store and distribute their packages securely.

## 

Protocol Overview

Designing a protocol to reward open-source contributions presents
formidable challenges. Open-source software, being universally
accessible, is susceptible to misattribution, appropriation, and
malicious tampering. However, the open-source community has consistently
demonstrated its willingness to highlight good actors and expose bad
actors. Historically, the energy spent reviewing and commenting on other
developers’ contributions has been strictly voluntary, despite how
time-consuming and crucial reporting and defending findings may be.

We intend to create a decentralized protocol secured by reputation and
incentives that enhances the sustainability and integrity of the
software supply chain by allowing open-source developers to capture the
value they create in a trustless manner. We believe adequate rewards for
open-source contributions cannot succeed without both a reputation
system and the ability for members of the community to communicate their
findings and support (or dissent) for a project or the work of a
developer. Additionally, we must provide developers with tools to access
and contribute to this reputation system. Tools that include simple
visual and programmable access to the version and reputation of all
dependencies within their projects.

Transparency into the TEA tokens staked by community members to support
each project enhances each project's reputation, much like the number of
tokens a package maintainer stakes on their own work signals their
commitment to it. These combined data points will help inform a
reputation system for all community members and facilitate choice. As
the [event-stream package
hack](https://medium.com/intrinsic-blog/compromised-npm-package-event-stream-d47d08605502)
was not conducted through the package itself, but via one of its
dependencies, visibility across all layers of dependencies will be vital
to building this trustless system. However, considerations such as
computation and transaction (“gas”) costs will need to take priority as
the system is designed and built.

Our goal is to reward both Web 2.0 and web3 developers. The intricacies
and specifics of each stack make it so that tracking installations of
packages could easily fall victim to one or more bad actors. That
includes “buying” installations to artificially inflate numbers. An even
worse scenario would be introducing fundamental changes to the nature of
open-source software by creating unnecessary friction with license keys
or other deployment tracking mechanisms. To provide the broadest
coverage, we believe that rewards must not rely on a simplistic notion
of tracking installations, but rather on incentive mechanisms that
encourage the submission of quality packages and the reporting of
nefarious or high-risk packages. Lastly, many packages rely on common
dependencies. For example,
[lodash](https://www.npmjs.com/package/lodash) has 176,308 open-source
dependents while [chalk](https://www.npmjs.com/package/chalk) has
100,247 dependents or [log4js](https://www.npmjs.com/package/log4js/)
has 3,809 dependents. As more packages are created using the same
dependencies, how do we ensure that rewards are distributed fairly and
equitably? How do we ensure that the most utilized dependencies are
rewarded without starving new or emerging packages and developers? How
do we ensure that the incentive system does not end up steering
developers away from niche languages to centralize them where incentives
are better? But also, as developers, how do we identify packages with
the most dependents to build alternatives - leaner, more efficient,
better-coded versions of these packages?

At tea, we believe that the lack of visibility and incentives has
impeded the evolution of open-source software. Supported by the right
incentives and rewards, more developers will be in a position to build,
improve and augment open-source software for the betterment of the
world.

### 

Proof of Contribution

In this white paper, we propose “Proof of Contribution”, a novel
consensus mechanism designed to quantify the impact of all projects
across all open-source systems.

Proof of Contribution assigns a dynamic score, referred to as a
project’s teaRank, based on each open-source project’s orientation
within, and utilization from the broader open-source ecosystem over
time.

We believe that this approach benefits foundational software far removed
from the application layer (which tends to be the most visible layer to
the public and attracts most of the interest) and extends the reward
mechanism to ensure that all components of a project—from the top of the
tree, all the way to its base—are rewarded for their contribution.

To calculate each project’s score, teaRank builds upon the foundation
laid by [Google's PageRank](https://en.wikipedia.org/wiki/PageRank)
algorithm. Google’s PageRank is the search product’s defining component
and is built on the graph-like structure of web pages. PageRank, at its
core, is a probability distribution algorithm that assigns scores to
nodes in a graph, representing the likelihood that anything randomly
navigating the graph will arrive at a particular node. This algorithm is
particularly effective in a graph-like data structure, such as the
internet, because it quantifies the impact of each node (or web page)
based on the quantity and quality of edges (links) to it. This algorithm
was modified over time to better discern the web’s topology and identify
fraudulent links between web pages, allowing various attacks to be
mitigated.

Because the graph structure of the internet and the tea Protocol’s
decentralized registry share remarkable similarities, PageRank initially
appeared to be a promising approach for analysis. However, upon further
experimentation, it became apparent that PageRank's anti-spam strategies
were less effective when applied to open-source.

The key distinction lies in open-source software metadata. Unlike web
pages, most open-source package metadata, such as lines of code and
commit messages, are user-generated and susceptible to spoofing. Package
managers are vulnerable to spam campaigns, wherein malicious actors
flood the registry with packages containing phishing links or other
harmful content. Package manager registries may also inaccurately
reflect the dependencies of specific projects. This issue, known as
“[manifest
confusion](https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-attacks/)”
may allow bad actors to inject nefarious code or artificially inflate
the impact of third-party dependencies, often for nefarious purposes.

The arduous task of identifying and addressing these spam packages
typically falls to security firms or altruistic individuals, neither of
which offers a scalable solution to combat spam attacks in open-source.

Proof of Contribution is an algorithm specifically designed to address
the identification and isolation of spam packages and ensure only
impactful projects receive a fair reward. The details of the Proof of
Contribution algorithm will be the subject of a dedicated technical
paper.

### 

Network Participants

In this white paper, we distinguish participants through their
contributions. Some may contribute code or verify contributed code.
Others may support developers and their reputation.

#### 

Package Maintainers

tea assumes that package creators maintain their work. In this white
paper, we’ll refer to them as “package maintainers”.

Package maintainers must make sure their software continues to deliver
increasing value as the industry evolves. They are pillars of
open-source communities who need to be empowered and rewarded for their
ongoing contributions. However, a package maintainer may decide to
discontinue their maintenance efforts or realize they cannot operate at
a pace that matches the project’s users’ expectations. To ensure
continuity, they must have the ability to transfer control of their
project to another developer or group of developers, thereby appointing
them as maintainers and granting them ownership and control over
existing and future rewards associated with the project.

Similarly, a developer may decide to take on the role of package
maintainer by forking the existing project and registering a new one
which they will maintain moving forward, thus becoming package
maintainers. Once registered, projects whose teaRank exceeds a
governance defined threshold start receiving rewards from the tea
Protocol through the protocol's Proof of Contribution algorithm, in
parallel with the legacy forked project. As the open-source community
shifts away from the legacy project in favor of its newer iteration, the
Proof of Contribution algorithm will gradually decrease the rewards
allocated to the legacy project while boosting those assigned to the new
forked project.

It is essential to provide developer communities with the right tools to
determine which projects are being maintained and their past and present
maintainers’ reputation and quality of work. We’ve too often seen
open-source work being tampered with and the efforts of many ruined by
bad actors. Although the work of these bad actors is largely discovered
and remediated, it is often not until significant damage has been
incurred through financial or data loss. Take for example the
[event-stream npm
package](https://medium.com/intrinsic-blog/compromised-npm-package-event-stream-d47d08605502)
that was downloaded over 1.5 million times per week and relied upon by
over 1,500 packages when a hacker managed to penetrate the open-source
project, gain the trust of its original author, and modify event-stream
to depend on a malicious package that would exfiltrate bitcoin wallet
credentials to a third-party server. Although tools may help detect some
of these attacks, they cannot always be relied upon, which creates an
entire community dependent upon each other’s diligence and willingness
to share their findings.

We propose introducing incentives via the TEA token described in the
"[TEA
token](https://info.tea.xyz/tea-white-paper/white-paper#tea-token)"
section, to encourage open-source communities to report their findings
constructively, so package maintainers can address them before they are
exploited.

#### 

Package Users and tea community members

“Package users” are software developers focused on solving a specific
problem. They often look in the open-source community for the tools they
need to experiment quickly and iterate at little to no cost, directly
benefiting from the work of package maintainers.

With more than 10 million packages accessible across the top 30 package
managers, the absence of universal value attribution to open-source
projects can transform the selection of secure and efficient packages
for development into a high-risk and daunting endeavor. With no
discernible means to attribute and measure value, how do package users
efficiently select secure packages for their development?

We believe that the tea Protocol’s Proof of Contribution algorithm
combined with other incentives can provide package users with the
information they need to select the foundation of their own project
quickly and thoughtfully.

#### 

Project Supporters

In Web 2.0 and web3, a subset of package users, often called “sponsors”,
has chosen to support package maintainers through donations or other
forms of remuneration; however, this has rarely been the case.

These “project supporters” are organizations or open-source project
users who use open-source software to build their commercial products,
philanthropists looking to support the ecosystem, or entrepreneurs
looking to fund teams to develop components of a larger system.

tea proposes to extend the communities of open-source project supporters
to the entire tea community, whether organizations, developers, users,
or tech enthusiasts. tea’s goal is to implement decentralized incentive
mechanisms through unique use cases of the TEA token for any member of
the tea community to contribute to the perpetual sustainability and
continuous growth of open-source. Project supporters are free to decide
which projects or package maintainers they want to support based on
their work, beliefs, or any criteria and metric that would influence
their decision. Additionally, project supporters are free to decide how
they want to support these projects.

Sponsorship can be an effective system to support open-source
development; however, these sponsorships do not typically extend to all
dependencies. This limitation benefits favorites and gets in the way of
innovation and software building. To strive as the foundation of
software development, open-source must empower all developers, whether
beginners or experts, across all layers in the tower.

To bolster the sustainability and integrity of the software supply chain
and enable open-source developers to capture the value they create, tea
aims to establish mechanisms where support benefits all aspects of a
project. Support from backers will cascade through a project's
dependencies, from the top to the base of the tree. This implicitly
places trust in the package maintainer's ability to make informed
choices about their stack, thus enhancing their reputation.

![](https://2873717268-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnquaL4SJ8uar13sCFHzm%2Fuploads%2FEtkQIUM6tqk3CzPuXlZn%2Ffigure-2.png?alt=media&token=4871dc9a-03ec-42a0-bb29-5fc02f986d49)

Figure 2 - Rewards distribution across dependencies

#### 

tea Tasters

As new projects or new versions of existing projects are released, the
validity of the work needs to be provably demonstrated. This information
is critical for package users to decide if they can trust the package
and its maintainers. Within the tea Protocol, this function is provided
by the “tea tasters”.

tea tasters, typically, are experienced software developers willing to
dedicate some of their time to check the claims associated with a
package (functionality, security, [semantic
versioning](https://semver.org/), license accuracy, etc.) and stake both
their reputation and TEA tokens to demonstrate the outcome of their
research and support their reviews. In the tea Protocol, “staking your
tea” is the process of locking TEA tokens to support your reviews,
potentially earning rewards or facing penalties based on the consensus
about the quality of your reviews. tea tasters also have the option to
report bugs or vulnerabilities to package managers confidentially. Valid
reports result in rewards from the project's treasury, while invalid
reports lead to the forfeiture of the tea taster's stake. Lastly, if
package maintainers ignore these reported issues, it triggers penalties,
or “slashing”, for the project's treasury.

Like project supporters, tea tasters can influence a project and package
maintainer’s reputation; however, their impact is more significant given
their role in validating a project’s security, functionality, and
quality. tea tasters will also need to build their reputation to support
their claims. The quality of their work and the TEA tokens they put at
risk as they stake their reviews combined with other external data
sources will build each tea taster’s reputation, bringing more value to
their work. See the "[Package & Package Maintainer
Reputation](https://info.tea.xyz/tea-white-paper/white-paper#package-and-package-maintainer-reputation)"
section for more details on the mechanisms used to influence a project
and package maintainer’s reputation.

### 

Project Registration and Proof of Contribution Rewards

The registration of a project release requires multiple transactions to
occur atomically. Specifically:

  - The package maintainer must register the project with the
    decentralized registry,
  - The tea Protocol must instantiate a project treasury owned,
    controlled, and configured by the package maintainers according to
    the rules defined by the package maintainers, and
  - The tea Protocol must register the treasury’s unique name with the
    Ethereum Naming Service, or ENS, thus simplifying all user
    interactions with the treasury.

Failure of any one of the operations will result in the protocol
reverting to its previous state.

Upon successful registration of a project with a teaRank surpassing a
governance-defined threshold, the tea Protocol initiates the
distribution of Proof of Contribution rewards to the project's treasury.
We suggest distributing these rewards following a predetermined curve
from a predefined pool of tokens controlled by the tea Protocol and
allocated from the TEA tokens total supply.

Package maintainers are required to bolster their project's reputation
and trustworthiness by consistently staking a portion of the Proof of
Contribution rewards received by the project's treasury. For each token
staked, network participants will receive a non-transferrable “staked
TEA”, or stTEA, at a 1:1 ratio, to participate in the governance of the
tea Protocol. In line with the protocol's rules, these staked rewards,
and their corresponding stTEA, may be subject to reduction (“slashing”)
or redistribution if package maintainers fail to address bugs or
vulnerabilities.

Lastly, failure to maintain the minimum staked treasury ratio defined in
the governance rules will result in the suspension of Proof of
Contribution reward distribution to the project. Instead, these rewards
will be redistributed among compliant projects.

### 

Package & Package Maintainer Reputation

A reputation system that relies solely on the author’s economic
contribution does not provide sufficient user protection and can be
subject to Sybil attacks, where a single individual creates multiple
representations of themselves to leave a large volume of positive
reviews on their work, tricking users into believing their work was
reviewed and approved of by many.

Several methodologies are available to prevent Sybil attacks, some of
which are described by Nitish Balachandran and Sugata Sanyal in “[A
Review of Techniques to Mitigate Sybil
Attacks](https://arxiv.org/abs/1207.2617/)”. As tea is a decentralized
protocol, using a trust certification system that relies on a
centralized certificate issuance authority would be contrary to its
core. We propose to focus on decentralized approaches to Sybil attack
mitigation and, more specifically, on methodologies that rely on a large
group of network participants incentivized to assess and publicly
represent the reputation of each package and its maintainer.

Similar to the production of blocks on a proof-of-stake blockchain,
where non-producing nodes can validate the work of others and, when
necessary, highlight a violation of the rules of the network, leading to
a penalization of the bad actor through slashing (destruction of a
portion of their stake), we propose a system whereby third-parties, such
as tea tasters, would be able to review packages produced by package
maintainers and be incentivized to behave in the best interest of the
open-source software community and its users, as well as recognize good
behavior and penalize bad behavior. This system must be both
Sybil-resistant and prevent large token holders from materially
influencing the protocol or the reputation of specific packages. We
believe this approach to be more aligned with open-source, providing a
more fertile substrate to foster adoption and trust, and ultimately
facilitate the growth of tea.

Additionally, as the reputation of any member of the tea community
reaches key milestones, they may be granted access to elevated parts of
the protocol.

### 

Package Review by Third Parties

The review of packages by third parties is an essential component of
reputation building and the security of the software supply chain.
However, third-party reviews come with their own set of unique threats
including the aforementioned Sybil attacks.

Blockchain technology, and more explicitly staking, offers a unique
opportunity for tea to tackle this challenge. Although wallet addresses
may be available in infinite quantities, this is not the case with TEA
tokens, whose total supply is expected to be 10 billion. Additionally,
each action performed by developers, such as submitting, verifying, or
staking packages, will contribute to their reputation, thus creating a
unique profile each developer can use to both contribute to the tea
community and participate in tea’s governance.

By requiring third-party reviewers to stake TEA tokens and incur the
risk of losing a portion of their stake should they turn out to behave
against the interest of the network or be a bad actor, third parties can
provide additional credence to a package and receive a reward, in the
form of TEA tokens.

We also propose extending the reputation system to the third parties who
perform the independent verification of packages—the tea tasters. The
completion of a positive review will require two operations to occur
atomically:

  - The submission of the code review, signed by the tea taster and
    publicly accessible to all members of the community, along with
  - The act of staking the package, to substantiate their review.

The completion of a negative review that includes one or more critical
vulnerabilities will require the tea tasters to first contact the
package maintainer using a messaging protocol to notify them of the
vulnerability and allow them to address the issue in a timely fashion.
Upon expiry of the governance-defined period allocated to the package
maintainer to address their vulnerability or as the corrected package
becomes available, the same messaging protocol will be used to notify
users and testers of this package (including dependents) that a
vulnerability has been identified, and hopefully addressed, so they know
to update their application or dependencies. To disincentivize wasting
developers’ time, communication between the tea tasters and package
maintainers will require the tea tasters to stake TEA tokens.

Upon completing both operations, the tea tasters will receive an NFT as
evidence of their work on the specific package and package version. The
accumulation of NFTs combined with the staking ratio of each of the
packages reviewed and information extracted from external systems will
inform a tea taster’s reputation. As their reputation reaches key
milestones, tea tasters may earn access to elevated parts of the
protocol or accelerated rewards from the protocol, as decided by the tea
governance.

### 

Outdated or Corrupt Packages

tea’s mission is to enhance the sustainability and integrity of the
software supply chain by allowing open-source developers to capture the
value they create; however, rewards must be commensurate with the
efforts deployed by package maintainers and tea tasters.
Under-maintained, outdated, or corrupted packages are clear indications
of package maintainers not living up to the community’s expectations or
not delivering on the trust and support impressed upon them through the
staking of packages. Another manifestation of outdated packages may be
the continued use of a legacy language or legacy version of
multi-version languages. Packages remaining outdated or corrupt for too
long indicate that tea tasters need to review package maintainers’ work
regularly and consistently.

tea tasters play a pivotal role in open-source communities, as their
reviews and associated claims can influence package users, either
guiding them towards or away from specific packages. To ensure that
reviews can be trusted on an ongoing basis, we propose a mechanism
whereby reviews posted by tea tasters must be associated with staked TEA
tokens. Outdated or corrupted packages may see a portion of their
treasury slashed, while another portion is sent to the tea taster who
first recognized the lack of maintenance of any package.

As packages gain in popularity and usage, with more applications and
potentially mission-critical systems depending on them, we must
incentivize developers to discreetly report flaws to the package
maintainer and encourage package maintainers to address such flaws
before they can be exploited. Consequently, we propose that any negative
review which outlines a flaw such as a zero-day vulnerability or the use
of an outdated dependency and remains open beyond a grace period defined
by governance should be considered a failure on the part of the package
maintainer and be subject to the same penalties with the first tea
taster to report the flaw receiving a portion of the slashed tokens.

The same can be said for package supporters who staked their reputation
and TEA tokens on the work of delinquent package maintainers and
received rewards for it. As they failed to identify the lack of
maintenance or elected to continue to support the package regardless, we
propose that all slashing activities extend to the supporters of the
package.

Distribution to all tea tasters could be based on the age of their
review and the number of TEA tokens they staked for their review.

## 

TEA Token

TEA is a cryptographic token which serves as the access key to certain
parts and designated features of the tea Protocol.

Holders of TEA token have the ability to:

  - Register their packages;
  - Support packages by staking TEA tokens to specific packages;
  - Contribute to the security of the software supply chain by
    challenging packages and conducting reviews to report bugs and/or
    vulnerabilities.

As discussed, the tea Protocol unlocks the open-source economy and
creates value for builders, maintainers, and end-users of enterprise
software. Ultimately, the value captured by the tea Protocol accrues
back to token holders as the community scales, creating a feedback loop
that further incentivizes participation.

### 

Rewarding Open-Source Developers

We expect tea’s Proof of Contribution and staking mechanisms to foster
the growth of open-source by empowering its participants with the
resources they need to pursue their passion unencumbered.

As outlined in "[Project Registration and Proof of Contribution
Rewards](https://info.tea.xyz/tea-white-paper/white-paper#project-registration-and-proof-of-contribution-rewards)",
projects registered with the tea Protocol and with a teaRank that
surpasses a governance-defined threshold will receive Proof of
Contribution rewards in the form of TEA tokens from the tea Protocol.
This distribution will persist as long as the package complies with the
rules of the protocol. Specifically, the package will have to maintain a
teaRank above the governance defined threshold and package maintainers
will have to contribute to their project’s reputation and
trustworthiness by continuously staking a portion of the Proof of
Contribution rewards received by the project’s treasury. Failure to
comply with these rules will result in the suspension of the
distribution of Proof of Contribution rewards and the redistribution of
future rewards among compliant projects.

Dependencies can significantly affect the reliability and security of a
package, and the absence of registration for a package's dependencies
should be seen as a potential risk. Package maintainers, being both
validators and users of these dependencies, are in a prime position to
connect with the maintainers of those dependencies. They can encourage
them to register their projects with tea, thus making them subject to
oversight by tea tasters and eligible for associated rewards. To
encourage this community-wide engagement aimed at enhancing the
reputation system, we recommend that any package with dependencies that
are not registered with the tea Protocol see a fraction of its Proof of
Contribution rewards burnt. This burn would be proportional to the
number and contribution, quantified in teaRank, of each unregistered
dependency, and continue as long as these dependencies remain
unregistered.

Numerous cases have demonstrated that strong incentives can entice
malicious actors to compromise open-source software. Most of the
Internet’s critical infrastructure is running on open-source, and the
race to find exploits and other vulnerabilities is on. At tea, we
believe that package maintainers are not the ones that should be blamed
(although they often are).

The tea Protocol's incentives address this issue by ensuring a fair and
equitable distribution of incentives. A package like lodash with over
176k dependents is a pillar of open-source development, and its
maintainers deserve to be rewarded proportionally. However, a reward
system built solely on the number of dependents would prevent innovators
from disrupting these monopolies unless they are sufficiently funded by
third parties or have already accumulated enough resources to self-fund.
This approach would likely lead to a shrinking number of contributors,
resulting in the polar opposite of what tea is about.

To address this limitation and empower every TEA token holder with the
ability to support package maintainers, we also recommend that a
governance-defined fraction of all staking rewards received by all
network participants be directed towards the treasury of the staked
package, along with its dependencies.

### 

Staking to Secure the Software Supply Chain

Staking can be an effective methodology to support a decentralized
reputation system. However, to facilitate the security of the software
supply chain, the tea incentive distribution system must carefully
consider the staking ratio of each package and adjust each package’s
incentive accordingly.

To reduce the risk of a small number of packages used as dependencies
across many applications collecting most staking rewards, we recommend
the implementation of an optimum staking ratio, similar to the approach
described in the [research produced by the web3
Foundation](https://research.web3.foundation/Polkadot/overview/token-economics).

When a package exceeds the governance-defined optimum staking ratio, the
total amount of staking rewards allocated to the package will remain
fixed, regardless of the number of TEA tokens staked to the package.
This measure, designed to de-incentivize package supporters and tea
tasters from further staking highly staked packages, will result in a
linear decrease of the staking rewards received by each package
supporter.

A curve-based approach, such as the one described in the web3
Foundation’s research would slow down the reduction of the staking
rewards pool allocated to the package, thus continuing to take away from
lesser staked packages and introducing negative externalities by
granting more influence on large token holders over the distribution of
the staking rewards pool.

The recommended linear design should allow lesser staked packages to
become more attractive to both package supporters and tea tasters. It
may also incentivize experienced developers to build alternatives to
highly-staked packages, creating an opportunity for the tea community to
balance supporting existing software and promoting innovation. In its
initial design, the staking ratio will be calculated using the
circulating supply. The tea community may alter this design to improve
the system’s scalability further.

Just as good actors need to be rewarded; bad actors need to be
identified and penalized. Open-source software provides many
opportunities for bad actors to create pain points and reputational
risks for an entire community of developers. From the misappropriation
of work to the alteration and redistribution of software packages, or
the injection of nefarious code, the war between good and bad actors
goes on, often with well-funded bad actors who see the contamination of
open-source packages as an opportunity to benefit financially. The
downside has been relatively minimal, with packages potentially banned
from digital shelves or subjected to a poor reputation.

To directly address malicious actors and intensify the repercussions for
actions contrary to the open-source, we recommend implementing the
slashing mechanism detailed in the “[Package Review by Third
Parties](https://info.tea.xyz/tea-white-paper/white-paper#package-review-by-third-parties)”
and “[Outdated or Corrupt
Packages](https://info.tea.xyz/tea-white-paper/white-paper#outdated-or-corrupt-packages)”
sections.

As tea tasters evaluate and analyze the code in newly submitted
packages, we suggest tea tasters receive the tools and incentives to
pinpoint and highlight nefarious code so

  - package users can be made aware of the risks, and
  - package maintainers and package supporters are penalized for
    submitting or supporting nefarious code.

To that extent, for all evidenced negative reviews performed per the
network rules and which have been addressed by the package maintainer
within the governance defined period, the package maintainer should not
incur any penalty contrary to the package supporters or the tea tasters
who provided a positive review of the package in question.

For negative reviews performed per the network rules and that the
package maintainer has not addressed within the governance-defined
period, a fraction of the TEA tokens staked by the project’s treasury,
the package supporters, and previous tea tasters will be slashed and
sent to the tea taster who identified the bug or vulnerability. Another
fraction will be locked into an insurance pool controlled by the tea
governance. The tea governance will establish policies and rules in
close collaboration with the community to distribute the pool’s contents
to those affected by vulnerabilities. The protocol will distribute a
third fraction of the slashed TEA tokens across all tea tasters who
contributed to the negative review.

Staking and slashing are vital components of the tea Protocol's
incentive and penalty system. Package maintainers are required to stake
a portion of their project's treasury, ensuring they have a substantial
stake at risk in case they neglect to address bugs or vulnerabilities.
Package users, supporters, and tea tasters can also stake TEA tokens to
contribute to a package or package maintainer's reputation and actively
participate in the protocol to uphold the software supply chain's
sustainability and integrity.

Governance is closely tied to this active engagement. For each TEA token
staked, participants receive non-transferrable "staked TEA" (stTEA) at a
1:1 ratio, enabling them to participate in the governance of the tea
Protocol. Staked rewards and their corresponding stTEA tokens may face
reduction (slashing) or redistribution if the protocol rules are not
followed, reinforcing accountability within the ecosystem.

### 

TEA Token Supply Distribution

A majority of the TEA tokens created by the protocol are used as
incentives to encourage package maintainers, users, and supporters to
perform activities that provide value to the decentralized network. The
distribution of TEA tokens to various stakeholders within the protocol
is dictated by a “distribution schedule.”

Network incentives will be distributed directly by the tea Protocol, in
the form of TEA tokens, to four groups of stakeholders:

  - Package Maintainers;
  - Package Users (which include all members of the tea community);
  - Project Supporters; and,
  - tea Tasters.

TEA tokens will also be utilized to support packages and secure the
software supply chain through staking, including the right to challenge
a package by conducting a review and reporting bugs or vulnerabilities,
reward the open-source developers of registered projects, and
participate in the governance of the tea Protocol.

It’s recommended that a 10 billion maximum token supply be distributed
across all members of the tea community as described below:

![](https://2873717268-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnquaL4SJ8uar13sCFHzm%2Fuploads%2FmZtQomvVHgqHYJpFp0Xg%2FToken%20Allocation-Updated.svg?alt=media&token=3e3c881e-768a-4fa1-a354-a6efd1201855)

Figure 3 - Token distribution of maximum supply

Roughly 51.4% of the maximum token supply should be allocated to
“Ecosystem & Governance”, which includes incentives for open-source
projects to onboard and maintain their codebase as well as rewards for
contributing to decentralized votes and consensus via the tea DAO.
Tokens allocated to “Ecosystem & Governance” should be distributed as
Proof of Contribution rewards, staking rewards, and other types of
developer-centric incentives.

Roughly 18.6% of the maximum token supply should be allocated to the
“Protocol Development” to ensure the sustainability and continued
evolution of the tea Protocol. Roughly 12.7% should be earmarked for
“Early Supporters & Advisors”. Roughly 11.0% should be earmarked for a
Private sale, 3.0% for a public sale, while the remaining 3.2% should be
allocated to support marketplace liquidity once a token generation event
occurs.

Detailed Tokenomics, including a comprehensive Token Distribution and
Emissions schedule will be the subject of a dedicated paper.

## 

Governance

Governance is critical to the development, sustainability, and adoption
of any distributed system.

We propose that the tea Protocol incorporates governance mechanisms that
enable active contributors who have staked TEA tokens to propose and
vote on non-financial critical parameter changes. The voting process
would be weighted by stTEA token ownership and individual reputation.

Protocol parameters could include the priority to support specific
package managers or introduce new protocol features or functions, as
well as the impact of external factors on user and package reputation.
This functionality will ensure that critical parameters can evolve and
be optimized over time by active members of the tea community. We
anticipate governance will launch with a simple structure and
progressively expand as the tea system matures, facilitating adoption
and ensuring progressive decentralization.

Some system parameters may not be subject to governance or support high
frequency changes to reduce the attack surface represented by
governance. A progressive transition of parameters to open,
decentralized governance will ensure the stability and predictability of
the system.

## 

Third-Party Extensibility

As we build the initial tools to ignite the long-overdue support of the
open-source communities, we believe part of our mission is to ensure
that third parties can extend the overall toolset. In addition to
providing the infrastructure for developers to build extensions to the
protocol, including new ways to innovate and further the support of
open-source developers, our plans include the potential for other
package managers to contribute to the protocol.

The dreams and efforts of open-source developers have built the
innovation that supports our everyday life. We look forward to
discovering the new uses and extensions for the tea Protocol proposed by
the tea community.

## 

Future Work and Potential Community Efforts

As the tea system matures, we foresee the community deciding and
contributing to alterations and extensions of the tea system through
governance. Below are some ideas that we believe may inspire some,
however we do not guarantee any future performance.

### 

tea Wholesalers

Open-source software communities are vibrant and constantly looking to
innovate and deliver value. This dedication and altruism lead to the
constant building of new software and packages, each one pulling
dependencies. As a result, we anticipate the dependencies map to evolve
constantly, leading to frequent changes to the staking ratio and
rewards. In the future, the tea community may propose the development of
a system designed to dynamically monitor the staking ratio for each
project and rebalance how project supporters stake their TEA tokens
based on their own criteria.

### 

Royalties on Package Transfer

We recognize that package maintainers may decide to transfer their
rewards stream to one or more developers. The governance of such
transfer must remain the decision of the package maintainer and their
partners, with no interference from tea. Tools will need to be provided
for such transfer to be total or partial (perhaps through only a portion
of the rewards being redirected to one or more developers, while the
remaining rewards continue to flow to the original package maintainer)
and for the staking rewards to flow through a single account controlled
by a single network participant, multiple network participants, or
automatically distributed across multiple accounts using static or
dynamic ratios.

### 

Rewards Distribution Across Multiple Maintainers

Pemeliharaan suatu paket dapat mengandalkan pekerjaan satu tim
pengembang lagi. Sebelum imbalan mulai mengalir, tim harus
mempertimbangkan untuk mengotomatiskan distribusi nilai di antara mereka
sendiri. Bagaimana pendistribusian terjadi harus diputuskan oleh
pengelola sendiri, karena merekalah yang mempunyai posisi terbaik untuk
mengevaluasi siapa yang berkontribusi dan bagaimana mereka harus diberi
imbalan.

Untuk mencapai hal tersebut, setiap tim (atau tim) dapat membentuk
organisasi otonom terdesentralisasi (
[DAO](https://ethereum.org/en/dao/) ) mereka sendiri dan mengotomatisasi
distribusi atau menerapkan sistem yang lebih kompleks untuk menentukan
distribusi nilai yang memadai berdasarkan faktor eksternal seperti
pemungutan suara dari semua anggota DAO, atau distribusi berbasis waktu
berdasarkan kontribusi berkelanjutan, keberhasilan penyelesaian bounty,
dll.

### 

Menangani Paket “Garpu”

Kami percaya bahwa fork sangat penting dan kurang dimanfaatkan. Fork
dapat menjadi alat yang efektif untuk mengembangkan paket yang bersaing
dalam hal fungsionalitas, kinerja, keamanan, dan bahkan perhatian.
Meskipun bermanfaat, fork harus mengakui upaya awal. Melalui upaya di
masa depan atau kontribusi potensial, komunitas teh dapat meningkatkan
sistem yang mengharuskan fork diumumkan, bahkan mungkin terdeteksi
ketika sebuah proyek didaftarkan. Garpu yang tidak diumumkan yang
diungkapkan oleh pencicip teh dapat mengakibatkan sebagian dari
perbendaharaan garpu tersebut dipotong, dipindahkan ke pengelola paket
asli, atau dikirim ke pencicip teh yang mengungkapkan garpu tersebut.

### 

Runtime vs. Ketergantungan Build

teh mungkin tidak membedakan dependensi build dari dependensi runtime
saat mendistribusikan hadiah Bukti Kontribusi saat peluncuran. Namun,
jika komunitas teh sangat ingin membuat perbedaan tersebut, komunitas
teh dapat mengusulkan peningkatan pada algoritma distribusi imbalan
untuk memperhitungkan pentingnya setiap ketergantungan dan kontribusinya
terhadap nilai individual dari paket yang bergantung padanya. Proposal
ini akan dipilih dan dilaksanakan berdasarkan keputusan masyarakat.

### 

Hadiah berdasarkan penggunaan

Karena semakin banyak aplikasi yang dibangun menggunakan proyek yang
didaftarkan pada teh, komunitas dapat meningkatkan algoritme penghargaan
sehingga alokasi dapat dipengaruhi oleh kumpulan data eksternal yang
telah dibuktikan seperti penggunaan. Pembaruan pada mekanisme hadiah ini
memungkinkan alokasi hadiah token TEA yang lebih tinggi untuk mengalir
ke paket dengan penggunaan tertinggi sambil tetap menghormati batasan
rasio staking yang dijelaskan di bagian token TEA. Pengelola paket dapat
menggunakan pendekatan serupa untuk mendistribusikan imbalan di seluruh
dependensinya berdasarkan logika transparan pilihan mereka. Perlu
diperhatikan bahwa semua informasi yang digunakan untuk mempengaruhi
distribusi imbalan di seluruh paket dan ketergantungan dalam sistem teh
harus dapat diandalkan.

## 

Ucapan Terima Kasih

Buku putih ini tidak akan ada tanpa dukungan dan dedikasi dari banyak
pecinta teh. Para penulis ingin mengucapkan terima kasih kepada Jacob
Heider, Jadid Khan, Josh Kruger, dan Shane Molidor atas kontribusi
mereka terhadap tokennomics, Sanchit Ram atas kontribusinya pada
algoritma teaRank, dan banyak individu yang menyumbangkan waktunya untuk
memberikan masukan mengenai konten. dokumen ini.

## 

Daftar Istilah

Ketentuan

Definisi

Daun

Denominasi terkecil dari token TEA. Satu daun setara dengan seperlima
triliun (10^−18) teh.

Nekat

Tindakan memberikan sanksi kepada pemangku kepentingan sebagai respons
terhadap perilaku yang bertentangan dengan aturan protokol.

Mempertaruhkan

Tindakan mengunci token TEA untuk mendukung klaim Anda dan menerima
hadiah (atau penalti) berdasarkan konsensus mengenai validitas klaim
Anda.

stTEA

Token “stake TEA” atau “stTEA” yang tidak dapat ditransfer diterima oleh
peserta jaringan untuk setiap token yang dipertaruhkan dengan rasio 1:1.
stTEA dapat dimanfaatkan untuk berpartisipasi dalam tata kelola Protokol
teh

peringkat teh

Skor dampak dinamis ditetapkan untuk setiap proyek berdasarkan algoritma
“Bukti Kontribusi” protokol.

## 

Referensi

1.  1\.
    ​https://creativecommons.org/licenses/by-sa/4.0/[](https://creativecommons.org/licenses/by-sa/4.0/)
2.  2\.
    ​https://archive.org/details/historyofmodernc00ceru[](https://archive.org/details/historyofmodernc00ceru)
3.  3\.
    ​https://nvd.nist.gov/vuln/detail/CVE-2021-44228[](https://nvd.nist.gov/vuln/detail/CVE-2021-44228)
4.  4\.
    ​https://www.reuters.com/article/usa-cyber-vulnerability-idCNL1N2SY2PA[](https://www.reuters.com/article/usa-cyber-vulnerability-idCNL1N2SY2PA)
5.  5\.
    ​https://twitter.com/yazicivo/status/1469349956880408583[](https://twitter.com/yazicivo/status/1469349956880408583)
6.  6\.
    ​https://www.thestack.technology/core-js-maintainer-denis-pusharev-license-broke-angry/[](https://www.thestack.technology/core-js-maintainer-denis-pusharev-license-broke-angry/)
7.  7\.
    https://www.w3.org/TR/did-core/[](https://www.w3.org/TR/did-core/)
8.  8\.
    ​https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-actions/[](https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-attacks/)
9.  9\.
    ​https://www.theregister.com/2016/03/23/npm\_left\_pad\_chaos/[](https://www.theregister.com/2016/03/23/npm_left_pad_chaos/)
10. 10\.
    ​https://fossa.com/blog/npm-packages-colors-faker-corrupted/[](https://fossa.com/blog/npm-packages-colors-faker-corrupted/)
11. 11\.
    ​https://www.lunasec.io/docs/blog/node-ipc-protestware/[](https://www.lunasec.io/docs/blog/node-ipc-protestware/)
12. 12\.
    https://github.com/dominictarr/event-stream/issues/116[](https://github.com/dominictarr/event-stream/issues/116)
13. 13\.
    ​https://blog.npmjs.org/post/163723642530/crossenv-malware-on-thenpm-registry.html[](https://blog.npmjs.org/post/163723642530/crossenv-malware-on-the-npm-registry.html)
14. 14\.
    ​https://www.zdnet.com/article/open-source-software-how-many-bug-are-hidden-there-on-tujuan/[](https://www.zdnet.com/article/open-source-software-how-many-bugs-are-hidden-there-on-purpose/)
15. 15\.
    https://threatpost.com/backdoor-found-in-utility-for-linux/147581/[](https://threatpost.com/backdoor-found-in-utility-for-linux/147581/)
16. 16\.
    ​https://www.fbi.gov/news/stories/phantom-secure-takedown-031618[](https://www.fbi.gov/news/stories/phantom-secure-takedown-031618)
17. 17\.
    ​https://www.europol.europa.eu/media-press/newsroom/news/800-criminalsarrested-in-biggest-ever-law-enforcement-operation-against-encryptedcommunication[](https://www.europol.europa.eu/media-press/newsroom/news/800-criminals-arrested-in-biggest-ever-law-enforcement-operation-against-encrypted-communication)
18. 18\.
    ​https://medium.com/intrinsic-blog/compromised-npm-package-event-stream-d47d08605502[](https://medium.com/intrinsic-blog/compromised-npm-package-event-stream-d47d08605502)
19. 19\.
    ​https://www.npmjs.com/package/lodash[](https://www.npmjs.com/package/lodash)
20. 20\.
    https://www.npmjs.com/package/chalk[](https://www.npmjs.com/package/chalk)
21. 21\.
    https://www.npmjs.com/package/log4js/[](https://www.npmjs.com/package/log4js/)
22. 22\.
    ​https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-actions/[](https://www.bleepingcomputer.com/news/security/npm-ecosystem-at-risk-from-manifest-confusion-attacks/)
23. 23\.
    ​https://medium.com/intrinsic-blog/compromised-npm-package-eventstream-d47d08605502[](https://medium.com/intrinsic-blog/compromised-npm-package-event-stream-d47d08605502)
24. 24\.
    ​https://semver.org/[](https://semver.org/)
25. 25\.
    ​https://arxiv.org/abs/1207.2617[](https://arxiv.org/abs/1207.2617)
26. 26\.
    ​https://research.web3.foundation/Polkadot/overview/token-economics[](https://research.web3.foundation/Polkadot/overview/token-economics)

[](https://info.tea.xyz/tea-white-paper/)

Sebelumnya

Baca aku

Terakhir diubah 1 bulan yang lalu

Di halaman ini

Protokol Terdesentralisasi bagi Pengembang Sumber Terbuka untuk
Menangkap Nilai yang Mereka Ciptakan

Abstrak

Penafian

Lisensi

Perkenalan

Komponen

Manajer Paket

Registri Terdesentralisasi

Sistem Penyimpanan

Ikhtisar Protokol

Bukti Kontribusi

Peserta Jaringan

Pendaftaran Proyek dan Bukti Imbalan Kontribusi

Reputasi Pemelihara Paket & Paket

Peninjauan Paket oleh Pihak Ketiga

Paket Kedaluwarsa atau Rusak

Token TEH

Menghargai Pengembang Sumber Terbuka

Staking untuk Mengamankan Rantai Pasokan Perangkat Lunak

Distribusi Pasokan Token TEH

Tata Kelola

Ekstensibilitas Pihak Ketiga

Pekerjaan Masa Depan dan Potensi Upaya Masyarakat

Pedagang grosir teh

Royalti atas Transfer Paket

Distribusi Hadiah ke Beberapa Pengelola

Menangani Paket “Garpu”

Runtime vs. Ketergantungan Build

Hadiah berdasarkan penggunaan

Ucapan Terima Kasih

Daftar Istilah

Referensi

Untuk mengambil item yang dapat diseret, tekan bilah spasi. Saat
menyeret, gunakan tombol panah untuk memindahkan item. Tekan spasi lagi
untuk menjatuhkan item ke posisi barunya, atau tekan escape untuk
membatalkan.

[](https://info.tea.xyz/tea-white-paper/)

Baca aku

[](https://info.tea.xyz/tea-white-paper/white-paper)

kertas putih

Didukung Oleh GitBook

![](https://fonts.gstatic.com/s/i/productlogos/translate/v14/24px.svg)

Teks asli

Beri rating terjemahan ini

Masukan Anda akan digunakan untuk membantu meningkatkan kualitas Google
Terjemahan

\------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-44c9c59e-300d-4786-bc4b-700a798b5d03@mhtml.blink @charset
"utf-8"; html, body { overflow-x: clip; } body.theme-overlay { position:
fixed; width: 0px; inset: 0px; background-color:
var(--theme-overlay-background); z-index: 10000; } .gitbook-splashscreen
{ position: fixed; inset: 0px; display: flex; width: 100%; height: 100%;
z-index: 10000; } .slate-spacer { height: 0px; color: transparent;
outline: none; position: absolute; }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-94990de6-6f2c-437c-a8e0-63054addb49e@mhtml.blink @charset
"utf-8"; :root { --custom-theme-color-primary-xxlight: \#f6fef6;
--custom-theme-color-primary-xlight: \#d0f9d0;
--custom-theme-color-primary-light: \#89f089;
--custom-theme-color-primary-base: \#56EA57;
--custom-theme-color-primary-dark: \#3cc13c;
--custom-theme-color-primary-xdark: \#2c912c;
--custom-theme-color-primary-xxdark: \#284f27; }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-bd85a6c9-4490-4dd3-a287-94dd3eaa0c55@mhtml.blink @charset
"utf-8"; @font-face { font-family: gitbook-content-font; font-style:
normal; font-weight: 700; font-display: swap; src: local("Inter Bold"),
local("Inter-Bold"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Bold.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Bold.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: italic; font-weight: 700; font-display: swap; src:
local("Inter BoldItalic"), local("Inter-BoldItalic"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-BoldItalic.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-BoldItalic.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: normal; font-weight: 800; font-display: swap; src:
local("Inter ExtraBold"), local("Inter-ExtraBold"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-ExtraBold.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-ExtraBold.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: italic; font-weight: 800; font-display: swap; src:
local("Inter ExtraBoldItalic"), local("Inter-ExtraBoldItalic"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-ExtraBoldItalic.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-ExtraBoldItalic.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: normal; font-weight: 500; font-display: swap; src:
local("Inter Medium"), local("Inter-Medium"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Medium.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Medium.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: italic; font-weight: 500; font-display: swap; src:
local("Inter MediumItalic"), local("Inter-MediumItalic"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-MediumItalic.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-MediumItalic.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: normal; font-weight: 400; font-display: swap; src:
local("Inter Regular"), local("Inter-Regular"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Regular.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Regular.woff?v=3.21")
format("woff"); } @font-face { font-family: gitbook-content-font;
font-style: italic; font-weight: 400; font-display: swap; src:
local("Inter Italic"), local("Inter-Italic"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Italic.woff2?v=3.21")
format("woff2"),
url("https://app.gitbook.com/public/fonts/Inter/Inter-Italic.woff?v=3.21")
format("woff"); }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-241e1b56-afb8-48e4-8577-cb257bd539a0@mhtml.blink @charset
"utf-8"; \[stylesheet-group="0"\] { } body { margin: 0px; } html {
text-size-adjust: 100%; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); }
input::-webkit-search-cancel-button, input::-webkit-search-decoration,
input::-webkit-search-results-button,
input::-webkit-search-results-decoration { display: none; }
\[stylesheet-group="1"\] { } .css-11aywtz { appearance: none;
background-color: rgba(0, 0, 0, 0); border-radius: 0px; border: 0px
solid black; box-sizing: border-box; font: 14px -apple-system,
BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
margin: 0px; padding: 0px; resize: none; } .css-175oi2r { align-items:
stretch; background-color: rgba(0, 0, 0, 0); border: 0px solid black;
box-sizing: border-box; display: flex; flex-basis: auto; flex-direction:
column; flex-shrink: 0; list-style: none; margin: 0px; min-height: 0px;
min-width: 0px; padding: 0px; position: relative; text-decoration: none;
z-index: 0; } .css-1qaijid { background-color: rgba(0, 0, 0, 0); border:
0px solid black; box-sizing: border-box; color: inherit; display:
inline; font: inherit; list-style: none; margin: 0px; padding: 0px;
text-align: inherit; text-decoration: none; white-space: inherit;
overflow-wrap: break-word; } .css-1rynq56 { background-color: rgba(0, 0,
0, 0); border: 0px solid black; box-sizing: border-box; color: rgb(0, 0,
0); display: inline; font: 14px -apple-system, BlinkMacSystemFont,
"Segoe UI", Roboto, Helvetica, Arial, sans-serif; list-style: none;
margin: 0px; padding: 0px; text-align: inherit; text-decoration: none;
white-space: pre-wrap; overflow-wrap: break-word; } .css-9pa8cd { inset:
0px; height: 100%; opacity: 0; position: absolute; width: 100%; z-index:
-1; } \[stylesheet-group="2"\] { } .r-1064s9p { margin: 4px; }
.r-117ykcp { border-bottom-color: var(--sp-color-border-base);
border-left-color: var(--sp-color-border-base); border-right-color:
var(--sp-color-border-base); border-top-color:
var(--sp-color-border-base); } .r-11mg6pl { border-color: rgb(255, 255,
255); } .r-13awgt0 { flex: 1 1 0%; } .r-13fxbef { border-color: rgb(211,
61, 61); } .r-1471scf { display: inline; } .r-156hn8l { border-color:
rgb(211, 220, 228); } .r-17gur6a { border-radius: 0px; } .r-18c69zk {
border-radius: 100px; } .r-190qawg { border-color: rgb(227, 232, 237); }
.r-19dn8jc { border-color: rgb(104, 60, 17); } .r-1awa8pu {
border-color: rgb(101, 119, 134); } .r-1c57tb8 { border-radius: 34px; }
.r-1d4xg89 { border-color: rgb(170, 184, 194); } .r-1dqxon3 { overflow:
auto; } .r-1edjr5w { padding: 80px; } .r-1fdo3w0 { margin: 16px; }
.r-1fuqb1j { border-radius: 24px; } .r-1j16mh1 { border-radius: 100%; }
.r-1jkafct { border-radius: 2px; } .r-1jti08r { border-color: rgb(86,
234, 87); } .r-1jyn79y { border-color: rgb(0, 150, 136); } .r-1p0fg95 {
border-color: rgb(245, 247, 249); } .r-1phboty { border-style: solid; }
.r-1rwzld0 { border-color: rgb(11, 79, 47); } .r-1udh08x { overflow:
hidden; } .r-1ufqoot { border-color: rgb(20, 23, 28); } .r-1w1o3af {
border-color: rgb(251, 232, 240); } .r-1wgstfn { border-style: none; }
.r-1x0lp8v { border-color: rgb(220, 238, 244); } .r-1xc7w19 {
border-color: rgb(0, 0, 0); } .r-1xfd6ze { border-radius: 8px; }
.r-1xutcf9 { padding: 40px; } .r-1yadl64 { border-width: 0px; }
.r-42olwf { border-color: rgba(0, 0, 0, 0); } .r-4a18lf { border-color:
rgb(255, 0, 0); } .r-4qtqp9 { display: inline-block; } .r-60ke3l {
border-color: rgb(0, 128, 0); } .r-6578ry { margin: 40px; } .r-6koalj {
display: flex; } .r-6ncur5 { border-radius: 18px; } .r-6t2glc {
border-radius: 40px; } .r-9x6qib { border-color: rgb(204, 214, 221); }
.r-ancj0c { border-color: rgb(218, 212, 255); } .r-by8dw1 { margin:
24px; } .r-bztko3 { overflow: visible; } .r-cdmcib { border-radius: 3px;
} .r-cpet4d { border-radius: 999px; } .r-crgep1 { margin: 0px; }
.r-d045u9 { border-width: 2px; } .r-d23pfw { padding: 24px; } .r-dta0w2
{ flex: 2 1 0%; } .r-edyy15 { padding: 8px; } .r-eg6o18 { border-style:
dashed; } .r-egco7n { border-color: rgb(253, 195, 137); } .r-fx7oqy {
border-color: rgb(0, 0, 255); } .r-hvic4v { display: none; } .r-hwh8t1 {
margin: 8px; } .r-jqra5g { border-color: rgb(55, 65, 81); } .r-jxo161 {
border-color: rgb(255, 204, 203); } .r-kdyh1x { border-radius: 6px; }
.r-krxsd3 { display: -webkit-box; } .r-m2nopt { border-color: rgb(43,
46, 57); } .r-m7id7e { flex: unset; } .r-m9k8lk { border-color: rgb(223,
255, 240); } .r-nsbfu8 { padding: 16px; } .r-p4pd8u { border-color:
rgb(36, 42, 49); } .r-qwd59z { border-radius: 1px; } .r-rs99b7 {
border-width: 1px; } .r-t60dpp { padding: 0px; } .r-texgdz { margin:
80px; } .r-tuq35u { padding: 4px; } .r-tyhe3k { border-radius: 64px; }
.r-xoduu5 { display: inline-flex; } .r-xyw6el { padding: 12px; }
.r-ywje51 { margin: auto; } .r-z2wwpe { border-radius: 4px; } .r-zhp00w
{ padding: 2px; } \[stylesheet-group="2.1"\] { } .r-10x3wzx {
padding-bottom: 40px; padding-top: 40px; } .r-11yq8vr { margin-left:
40px; margin-right: 40px; } .r-1e081e0 { padding-left: 12px;
padding-right: 12px; } .r-1guathk { padding-left: 24px; padding-right:
24px; } .r-1h4fu65 { padding-bottom: 24px; padding-top: 24px; }
.r-1hy1u7s { margin-left: 24px; margin-right: 24px; } .r-1isdzm1 {
padding-left: 80px; padding-right: 80px; } .r-1jgb5lz { margin-left:
auto; margin-right: auto; } .r-1p02zvt { padding-left: 48px;
padding-right: 48px; } .r-1p4rafz { padding-left: 2px; padding-right:
2px; } .r-1p6iasa { margin-bottom: 4px; margin-top: 4px; } .r-1pn2ns4 {
padding-left: 8px; padding-right: 8px; } .r-1r5su4o { margin-bottom:
16px; margin-top: 16px; } .r-1unineu { margin-bottom: 40px; margin-top:
40px; } .r-1w3m5we { padding-bottom: 80px; padding-top: 80px; }
.r-1ybube5 { margin-left: 8px; margin-right: 8px; } .r-1ydw1k6 {
margin-left: 16px; margin-right: 16px; } .r-1yzf0co { padding-bottom:
16px; padding-top: 16px; } .r-4amgru { margin-left: 4px; margin-right:
4px; } .r-5njf8e { padding-bottom: 8px; padding-top: 8px; } .r-5wp0in {
padding-left: 40px; padding-right: 40px; } .r-c8eef1 { margin-bottom:
8px; margin-top: 8px; } .r-g4w12b { padding-left: 94px; padding-right:
94px; } .r-g8va3u { margin-left: 80px; margin-right: 80px; } .r-mk0yit {
padding-left: 0px; padding-right: 0px; } .r-mvpalk { margin-left: 0px;
margin-right: 0px; } .r-oyd9sg { padding-bottom: 4px; padding-top: 4px;
} .r-pw2am6 { margin-bottom: 24px; margin-top: 24px; } .r-r0h9e2 {
margin-bottom: 0px; margin-top: 0px; } .r-r26ds4 { margin-bottom: 80px;
margin-top: 80px; } .r-rjfia { padding-bottom: 0px; padding-top: 0px; }
.r-s1qlax { padding-left: 4px; padding-right: 4px; } .r-ymttw5 {
padding-left: 16px; padding-right: 16px; } \[stylesheet-group="2.2"\] {
} .r-100vyta { margin-top: 7px; } .r-1029d6i { top: -24px; } .r-105ug2t
{ pointer-events: auto \!important; } .r-109y4c4 { height: 1px; }
.r-10kz8ia { color: rgb(228, 79, 137); } .r-10ptun7 { height: 16px; }
.r-10pyoum { color: rgb(5, 5, 5); } .r-10x49cs { font-size: 10px; }
.r-10xqauy { padding-top: env(safe-area-inset-top); } .r-111w7nw {
box-shadow: rgba(0, 0, 0, 0.69) 0px 1px 2px; } .r-113qch9 { cursor:
auto; } .r-116b19x { padding-left: 40px; } .r-119vxgs {
border-top-style: dashed; } .r-11c0sde { margin-top: 24px; } .r-11f42r {
height: 314px; } .r-11g3r6m { padding-right: 24px; } .r-11j9u27 {
visibility: hidden; } .r-11mo1y0 { margin-bottom: 7px; } .r-11mpjr4 {
background-color: rgb(223, 223, 223); } .r-11udlyb { background-color:
rgb(0, 150, 136); } .r-11vxtcu { background-color: rgb(211, 220, 228); }
.r-11wrixw { margin-left: 0px; } .r-11xdecz { max-width: 233px; }
.r-11yh6sk { overflow-x: hidden; } .r-11ys0m { break-before: auto; }
.r-123mryc { color: rgb(185, 94, 4); } .r-127358a { animation-name:
r-9p3sdl; } .r-127gp16 { max-width: 150px; } .r-12dqhl9 { height:
calc(100vh - 80px); } .r-12mrs02 { object-fit: contain; } .r-12vffkv \>
\* { pointer-events: auto; } .r-12vffkv { pointer-events: none
\!important; } .r-12ym1je { width: 18px; } .r-12zb1j4 { margin-right:
7px; } .r-135wba7 { line-height: 24px; } .r-13gfk22 { animation-delay:
250ms; } .r-13hce6t { margin-left: 4px; } .r-13i40vn { box-shadow:
rgba(0, 0, 0, 0.02) 0px 12px 13px; } .r-13l2t4g { border-right-width:
1px; } .r-13ll0g2 { color: rgb(10, 48, 105); } .r-13lvk87 { margin-left:
110px; } .r-13qz1uu { width: 100%; } .r-13tjlyg { transition-duration:
0.1s; } .r-13yce4e { border-top-width: 0px; } .r-142tt33 {
text-decoration-line: line-through; } .r-144uupt { left: 2px; }
.r-146iojx { max-width: 300px; } .r-1472mwg { height: 24px; } .r-14bkmb3
{ bottom: -3px; } .r-14eup4l { top: 3px; } .r-14gqq1x { margin-top: 4px;
} .r-14lw9ot { background-color: rgb(255, 255, 255); } .r-14sbq61 {
background-color: rgb(33, 150, 243); } .r-14utu6a { line-height: 8px; }
.r-14vq63g { background-color: rgb(3, 58, 22); } .r-14yzgew {
line-height: 18px; } .r-150rngu { } .r-157h22z { background-color:
rgb(45, 50, 58); } .r-15g7tld { margin-bottom: 80px; } .r-15m1z73 {
margin-left: 40px; } .r-15m68ww { color: rgb(137, 198, 218); }
.r-15o5oer { bottom: auto; } .r-15ysp7h { min-height: 32px; } .r-15zivkp
{ margin-bottom: 4px; } .r-16dba41 { font-weight: 400; } .r-16et402 {
color: var(--sp-color-text-light); } .r-16l9doz { height: auto; }
.r-16y2uox { flex-grow: 1; } .r-173mn98 { align-self: flex-end; }
.r-1777fci { justify-content: center; } .r-17bb2tj { animation-duration:
0.75s; } .r-17f5ght { border-bottom-color: rgb(86, 234, 87); }
.r-17giqoz { box-shadow: rgba(0, 0, 0, 0.52) 0px 0px 7px; } .r-17grq5a {
margin-right: -8px; } .r-17leim2 { background-repeat: repeat; }
.r-17mnkfo { background-color:
var(--sp-color-button-upgrade-bg-default); } .r-17rnw9f { line-height:
30px; } .r-17s6mgv { justify-content: flex-end; } .r-17tb59b { opacity:
0.7; } .r-17tloay { opacity: 0.6; } .r-17wrw06 { color: rgb(180, 26,
26); } .r-184en5c { z-index: 1; } .r-18ayb63 { border-right-color:
rgb(227, 232, 237); } .r-18kxxzh { flex-grow: 0; } .r-18nhz7w { top:
-3px; } .r-18p6if4 { border-right-width: 2px; } .r-18u37iz {
flex-direction: row; } .r-18y5qoh { color: rgb(165, 214, 255); }
.r-190thrv { color: rgb(145, 75, 5); } .r-19554kt { width: 90px; }
.r-19akecc { color: rgb(175, 245, 180); } .r-19byhck { flex-basis: 32%;
} .r-19lq7b1 { top: 16px; } .r-19r33im { letter-spacing: 1.2px; }
.r-19tq15n { margin-top: 80px; } .r-19wmn03 { width: 20px; } .r-19z077z
{ touch-action: none; } .r-1a3cspq { background-color: rgb(40, 49, 67);
} .r-1abnn5w { animation-play-state: paused; } .r-1acpoxo { width: 36px;
} .r-1adewhw { padding-bottom: 76px; } .r-1aerykh { border-top-color:
rgb(211, 220, 228); } .r-1ais5m6 { transform: rotate(90deg); }
.r-1aockid { width: 40px; } .r-1armvtb { font-size: 8px; } .r-1asdvj5 {
color: rgb(44, 145, 44); } .r-1awozwy { align-items: center; }
.r-1axcl7z { border: 1px solid rgb(211, 220, 228); } .r-1ay1djp {
animation-duration: 1s; } .r-1b00too { background-color: rgb(236, 239,
241); } .r-1b096ap { border-bottom-color: rgb(36, 42, 49); } .r-1b1g84l
{ bottom: -8px; } .r-1b389cn { color: rgb(60, 193, 60); } .r-1b43r93 {
font-size: 14px; } .r-1bcbbo8 { color: rgb(17, 99, 41); } .r-1bnj018 {
color: rgb(92, 105, 117); } .r-1c681wc { color: rgb(77, 222, 152); }
.r-1c6unfx { forced-color-adjust: none; } .r-1ce3o0f { max-height: 80vh;
} .r-1ceczpf { min-height: 24px; } .r-1clhhh9 { transition-property:
all; } .r-1cmwbt1 { gap: 8px; } .r-1d09ksm { align-items: baseline; }
.r-1d2f490 { left: 0px; } .r-1d4mawv { margin-right: 4px; } .r-1d5kdc7 {
flex-direction: column-reverse; } .r-1d7fvdj { justify-content:
space-evenly; } .r-1d9grui { border-bottom-color: rgb(211, 220, 228); }
.r-1ddef8g { text-decoration-line: underline; } .r-1dernwh { height:
70%; } .r-1dlgt49 { max-height: 30px; } .r-1dmvmgl { background-color:
rgb(36, 42, 49); } .r-1dn12g7 { line-height: 48px; } .r-1dpl46z {
border-bottom-right-radius: 4px; } .r-1dqbpge { cursor: text; }
.r-1dumtqg { background-color: rgb(253, 195, 137); } .r-1efo1hp {
border-bottom-color: rgb(43, 46, 57); } .r-1ei5mc7 { cursor: inherit; }
.r-1eic64l { color: rgb(198, 44, 104); } .r-1enofrn { font-size: 12px; }
.r-1euycsn { flex-direction: row-reverse; } .r-1ewcgjf { box-shadow:
rgba(0, 0, 0, 0.5) 0px 1px 3px; } .r-1f2v84d { color: rgb(204, 207,
212); } .r-1f529hi { line-height: 14px; } .r-1f77ubx { padding-bottom:
var(--sp-spacing-300); } .r-1fd96xs { padding-left: 50px; } .r-1fe0xdi {
left: 0%; } .r-1ff274t { text-align: right; } .r-1fi01yr {
background-color: rgb(55, 65, 81); } .r-1fiaf3z { opacity: 0.05; }
.r-1fo40xd { top: 80px; } .r-1fq43b1 { flex-basis: 100%; } .r-1g7fiml {
height: 30px; } .r-1g80fh1 { margin-right: 80px; } .r-1gigy5k {
border-bottom-color: rgb(45, 50, 58); } .r-1glc72y {
border-bottom-color: rgb(245, 247, 249); } .r-1glkqn6 { width: 80px; }
.r-1h0z5md { justify-content: flex-start; } .r-1h2t8mc { width: 0px; }
.r-1h815vi { right: 92%; } .r-1h8ys4a { padding-top: 4px; } .r-1habvwh {
align-items: flex-start; } .r-1hjwoze { height: 18px; } .r-1hlnpa {
height: 3px; } .r-1hpgsb4 { } .r-1hqdnve { box-shadow: rgba(0, 0, 0,
0.08) 0px 0px 4px inset; } .r-1hrvmjx { border-top-color: rgb(55, 65,
81); } .r-1hvjb8t { padding-right: 4px; } .r-1hy97zq { padding-top:
80px; } .r-1i6wzkk { transition-property: opacity; } .r-1i7sdiz {
box-shadow: rgba(0, 0, 0, 0.05) 0px 4px 10px; } .r-1i93rbr { right: 0%;
} .r-1iadl42 { background-color: var(--sp-color-bg-standout-base); }
.r-1ielgck { animation-duration: 300ms; } .r-1ifxtd0 { margin-bottom:
16px; } .r-1iln25a { overflow-wrap: normal; } .r-1ioqa4e {
border-top-right-radius: 7px; } .r-1ipicw7 { width: 300px; } .r-1j7aebl
{ width: 880px; } .r-1janqcz { width: 16px; } .r-1jg9483 { width: 8px; }
.r-1jj8364 { margin-left: auto; } .r-1jkjb { margin-left: 8px; }
.r-1jnzvcq { padding-bottom: 80px; } .r-1jocfgc { width: 290px; }
.r-1jpmnxg { overflow-wrap: anywhere; } .r-1jxfwug { border-top-width:
2px; } .r-1k25im9 { height: 26px; } .r-1kb76zh { margin-right: 8px; }
.r-1kf75xu { color: rgb(12, 105, 61); } .r-1kfrs79 { font-weight: 600; }
.r-1kihuf0 { align-self: center; } .r-1kjq87h { width: 376px; }
.r-1knl56f { animation-name: r-1hunrpy; } .r-1kvn7zp { max-height:
150px; } .r-1l0m7dr { background-image: radial-gradient(rgba(0, 0, 0,
0.1), rgb(255, 255, 255)); } .r-1l7z4oj { padding-bottom: 16px; }
.r-1l94q7l { box-shadow: rgba(0, 0, 0, 0.3) 0px 0px 1px inset; }
.r-1ld3bg { top: -4px; } .r-1ldzwu0 { animation-timing-function: linear;
} .r-1ljd8xs { border-left-width: 1px; } .r-1lky6n1 { background-color:
rgb(227, 232, 237); } .r-1lnfjr6 { background-clip: text; } .r-1lnt56z {
color: rgb(211, 220, 228); } .r-1loqt21 { cursor: pointer; } .r-1m04atk
{ padding-left: 8px; } .r-1m4drjs { top: -6px; } .r-1maqer6 { max-width:
860px; } .r-1mdbw0j { padding-bottom: 0px; } .r-1mdsxwj { color:
rgb(237, 159, 81); } .r-1mgmw1x { background-image:
linear-gradient(90deg, rgb(95, 69, 255), rgb(68, 47, 200)); } .r-1mhb1uw
{ width: 42px; } .r-1mhtwjo { left: -3px; } .r-1mlwlqe { flex-basis:
auto; } .r-1mnahxq { margin-top: 0px; } .r-1moh23t { bottom: 16px; }
.r-1mrlafo { background-position: 0px center; } .r-1ms9ukt { bottom:
-5px; } .r-1mtwht8 { color: rgb(210, 168, 255); } .r-1muvv40 {
animation-iteration-count: infinite; } .r-1n20pny { width: 140px; }
.r-1n6k3lk { color: rgb(36, 42, 49); } .r-1na1l7e {
animation-play-state: running; } .r-1nf4jbm { color: rgb(59, 69, 78); }
.r-1niwhzg { background-color: rgba(0, 0, 0, 0); } .r-1nj16ve { left:
-10px; } .r-1nlw0im { bottom: 8px; } .r-1nnq5pb { background-color:
var(--sp-color-bg-base); } .r-1ny4l3l { outline-style: none; }
.r-1o2nx2a { font-weight: 360; } .r-1ocf4r9 { scroll-snap-type: y
mandatory; } .r-1odw9d6 { background-color: rgb(20, 23, 28); }
.r-1oec5bt { opacity: 0.2; } .r-1oep0n4 { left: -12px; } .r-1ois7e2 {
color: rgb(55, 65, 81); } .r-1or9b2r { height: 10px; } .r-1osy6ei {
color: rgb(255, 220, 215); } .r-1oszu61 { align-items: stretch; }
.r-1otgn73 { touch-action: manipulation; } .r-1ow6zhx { margin-left:
16px; } .r-1p0dtai { bottom: 0px; } .r-1p5i0ed { bottom: -24px; }
.r-1p69tiw { border-top-color: rgb(43, 46, 57); } .r-1pa6394 { color:
var(--sp-color-text-muted); } .r-1peese0 { margin-bottom: 24px; }
.r-1ph75f1 { height: 80px; } .r-1pi2tsx { height: 100%; } .r-1pl7oy7 {
min-height: 48px; } .r-1ptriwd { right: 2px; } .r-1pyaxff {
padding-right: 8px; } .r-1q142lx { flex-shrink: 0; } .r-1q6rxnj {
padding-right: 110px; } .r-1q77oe7 { background-color: rgb(171, 183,
202); } .r-1q9ho9q { color: rgb(48, 127, 152); } .r-1q9jyb7 { filter:
blur(16px) contrast(110%) hue-rotate(10deg) brightness(1.2)
saturate(1.2); } .r-1qc3rpd { transform: scaleY(-1); } .r-1qd0xha {
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
Helvetica, Arial, sans-serif; } .r-1qdbj55 { animation-name: r-ndfo3d; }
.r-1qefu2b { right: -3px; } .r-1qhn6m8 { padding-left: 16px; }
.r-1qipmxq { color: var(--sp-color-button-upgrade-text); } .r-1quu1zo {
} .r-1r0uwd5 { color: rgb(255, 166, 87); } .r-1r3mtb5 {
border-bottom-color: rgb(20, 23, 28); } .r-1r74h94 { left: 8px; }
.r-1r8g8re { height: 36px; } .r-1rasi3h { color: rgb(136, 153, 168); }
.r-1rbj2e8 { outline-color: rgb(245, 247, 249); } .r-1rdth4h {
border-left-color: rgb(55, 65, 81); } .r-1rho1gz { box-shadow: rgba(0,
0, 0, 0.12) 0px 12px 13px; } .r-1rkdych { max-width: 1040px; }
.r-1rla0r3 { background-image: linear-gradient(90deg, rgb(211, 61, 61),
rgb(180, 26, 26)); } .r-1rnoaur { overflow-y: auto; } .r-1ro0kt6 {
flex-basis: 0%; } .r-1ro7rbe { right: 100%; } .r-1rq5dk0 {
border-right-color: rgb(86, 234, 87); } .r-1rttkqs { width: 400px; }
.r-1s3egr7 { z-index: 100; } .r-1s8p94s { max-width: 832px; } .r-1sncvnh
{ transform: translateZ(0px); } .r-1sxrcry { background-size: auto; }
.r-1t2qqvi { flex-basis: 50%; } .r-1t7uo4s { object-fit: cover; }
.r-1t8m4kl { text-shadow: rgb(36, 42, 49) 0px 0px 3px; } .r-1tazni7 {
cursor: not-allowed; } .r-1ts5s6y { aspect-ratio: 1.77778 / 1; }
.r-1ttybm1 { border-top-color: rgb(45, 50, 58); } .r-1tymxbh {
box-shadow: rgba(36, 42, 49, 0.6) 5px 0px 7px; } .r-1u9v6se { color:
rgb(39, 85, 100); } .r-1ua3vzd { background-color: rgb(223, 255, 240); }
.r-1ub1aon { transform: translateY(100%); } .r-1udbk01 { text-overflow:
ellipsis; } .r-1ufdtu9 { background-image: linear-gradient(270deg,
rgb(227, 232, 237) 10%, rgb(245, 247, 249), rgb(227, 232, 237) 90%); }
.r-1ufr4wv { z-index: 9; } .r-1ui5ee8 { font-size: 32px; } .r-1ul06mb {
margin-left: 32px; } .r-1ulgld5 { color: rgb(255, 123, 114); }
.r-1um4q9x { transition: opacity 800ms ease 0s; } .r-1uql0sn { top:
-1.2em; } .r-1ur9v65 { padding-top: 40px; } .r-1ut4w64 { margin-bottom:
-1px; } .r-1uwte3a { padding-bottom: 40px; } .r-1uypc71 {
animation-timing-function: ease-in; } .r-1v2oles { top: 50%; }
.r-1v7sw2p { background-size: 50% 80px; } .r-1vamr63 { max-width: 720px;
} .r-1vckr1u { background-color: rgb(245, 247, 249); } .r-1vex5ub {
color: rgb(68, 47, 200); } .r-1vutw0s { background-color: rgb(103, 6,
12); } .r-1vzi8xi { vertical-align: middle; } .r-1w2pmg { height: 0px; }
.r-1w6e6rj { flex-wrap: wrap; } .r-1wbh5a2 { flex-shrink: 1; } .r-1wezhl
{ margin-left: 80px; } .r-1wfhzrg { height: 120px; } .r-1wghi3f { top:
-8px; } .r-1wtj0ep { justify-content: space-between; } .r-1wv73ep {
align-self: baseline; } .r-1ww30s9 { max-width: 30px; } .r-1wyyakw {
z-index: -1; } .r-1wzrnnt { margin-top: 16px; } .r-1x35g6 { font-size:
24px; } .r-1xbve24 { height: 6px; } .r-1xcajam { position: fixed; }
.r-1xnzce8 { user-select: text; } .r-1xoqk23 { background-color: rgb(68,
47, 200); } .r-1xsj5db { background-color:
var(--sp-color-sidesheet-list-item-bg-hover); } .r-1y0r55a {
background-image: radial-gradient(rgba(255, 255, 255, 0.1), rgb(20, 23,
28)); } .r-1y14msn { border-bottom-color: rgb(55, 65, 81); } .r-1y9xkqr
{ left: 8%; } .r-1yb8zos { background-color: rgb(162, 169, 185); }
.r-1ybp48z { background-image: linear-gradient(90deg, rgb(204, 49, 49),
rgb(180, 26, 26)); } .r-1ye8kvj { max-width: 600px; } .r-1ygmrgt {
padding-top: 24px; } .r-1yv4afn { border-top-color: rgb(227, 232, 237);
} .r-1yvhtrz { width: 32px; } .r-1yxedwg { top: 8px; } .r-1yyzdbt {
border-left-color: rgb(227, 232, 237); } .r-257lmc { width: 1180px; }
.r-2atnlg { background-color: rgb(78, 170, 200); } .r-2awvau {
min-width: max-content; } .r-2eszeu::-webkit-scrollbar { display: none;
} .r-2eszeu { } .r-2fm7cc { color: rgb(139, 148, 158); } .r-2fw26j {
outline-offset: 0px; } .r-2jelyo { background-color: rgb(24, 28, 31); }
.r-2jxp4q { background-color: rgb(34, 39, 46); } .r-2kxcpj { inset: 0px;
} .r-2llsf { min-height: 100%; } .r-2o02ov { margin-top: 40px; }
.r-2tavb8 { background-color: rgba(0, 0, 0, 0.6); } .r-2yi16 {
min-height: 36px; } .r-2zpn8w { break-inside: avoid; } .r-30o5oe {
appearance: none; } .r-30qeir { bottom: -4px; } .r-36ujnk { font-style:
italic; } .r-37p410 { color: var(--sp-color-text-base); } .r-37tt59 {
line-height: 32px; } .r-3da1kt { height: 8px; } .r-3dgjpp {
border-top-color: rgb(36, 42, 49); } .r-3hw5f6 { color: rgb(149, 56, 0);
} .r-3kxdz0 { outline-color: rgb(40, 106, 127); } .r-3mc0re { right:
8px; } .r-3mtglp { row-gap: 16px; } .r-3o833n { background-color:
rgb(251, 232, 240); } .r-3pxcvb { border-bottom-color: rgb(255, 255,
255); } .r-3s2u2q { white-space: nowrap; } .r-417010 { z-index: 0; }
.r-432wen { width: 3px; } .r-44c749 { border-bottom-left-radius: 7px; }
.r-47i0zk { background-image: radial-gradient(rgba(0, 0, 0, 0.1),
rgb(20, 23, 28)); } .r-493a2x { width: 680px; } .r-4dj0k7 { box-shadow:
rgba(0, 0, 0, 0.12) 0px 1px 2px; } .r-4gszlv { background-size: cover; }
.r-4v7adb { height: 5px; } .r-5cpxsl { stroke-width: 3; } .r-5is6sd {
max-width: 460px; } .r-5k5nmx { color: rgb(86, 234, 87); } .r-5kkj8d {
border-top-width: 1px; } .r-5ks0hp { right: 3.5px; } .r-5kx3fr {
break-inside: avoid; } .r-5oul0u { margin-bottom: 8px; } .r-5soawk {
width: 10px; } .r-5vf7qs { width: 188px; } .r-5xr8s6 { outline-width:
2px; } .r-60emj1 { background-color: rgb(255, 204, 203); } .r-61z16t {
margin-right: 0px; } .r-633pao { pointer-events: none \!important; }
.r-6dt33c { opacity: 1; } .r-6k4xqk { margin-top: -40px; } .r-6t5ypu {
border-bottom-left-radius: 4px; } .r-6taxm2::-webkit-input-placeholder {
color: var(--placeholderTextColor); opacity: 1; } .r-6taxm2::placeholder
{ color: var(--placeholderTextColor); opacity: 1; } .r-6uxfom {
margin-left: 24px; } .r-6wscbn { max-width: 252px; } .r-73dpzl {
border-top-color: rgb(245, 247, 249); } .r-7b7h2f { left: 100%; }
.r-7cikom { font-size: inherit; } .r-7l9xyp { background-color:
rgba(255, 255, 255, 0.2); } .r-7q8q6z { cursor: default; } .r-7xmw5f {
width: fit-content; } .r-81rbui { animation-name: r-1ak6360; } .r-855088
{ border-left-color: rgba(0, 0, 0, 0); } .r-88pszg { margin-right: 16px;
} .r-8akbws { -webkit-box-orient: vertical; } .r-8d26hk { margin-bottom:
40px; } .r-8hc5te { width: 6px; } .r-8jwyv6 { transition: opacity 0.2s
ease-in-out 0s; } .r-8upyzv { width: 260px; } .r-8v5hsd { color:
rgb(126, 231, 135); } .r-9030i9 { box-shadow: rgba(0, 0, 0, 0.99) 0px
4px 10px; } .r-9111t9 { padding-right: 410px; } .r-92ng3h { width: 1px;
} .r-934yyj { padding-left: 34px; } .r-95jzfe { padding-top: 16px; }
.r-97e31f { padding-bottom: env(safe-area-inset-bottom); } .r-97prym {
flex-basis: 16px; } .r-99m41f { color: rgb(110, 119, 129); } .r-9aemit {
padding-right: 0px; } .r-9ji8r7 { transform: translateY(0%); } .r-9jpwak
{ min-width: auto; } .r-a2tzq0 { justify-content: space-around; }
.r-a5pmau { margin-right: 2px; } .r-a9hzal { height: 660px; } .r-adacv {
min-height: 64px; } .r-adyw6z { font-size: 20px; } .r-agyig6 {
background-color: var(--sp-color-button-upgrade-bg-hover); } .r-ah5dr5
\> \* { pointer-events: none; } .r-ah5dr5 { pointer-events: auto
\!important; } .r-ak0haq { color: rgb(121, 192, 255); } .r-aqxs90 {
transition: opacity 500ms ease-in 0s, z-index 1000ms ease-in 0s; }
.r-b4cb4 { max-height: 440px; } .r-b88u0q { font-weight: 700; }
.r-bcqeeo { min-width: 0px; } .r-bgnin { min-width: 150px; } .r-bnwqim {
position: relative; } .r-bsjocg { } .r-buy8e9 { overflow-y: hidden; }
.r-bv2aro { padding-left: env(safe-area-inset-left); } .r-bxaprw {
border-top-left-radius: 7px; } .r-c68hjy { color: rgb(161, 161, 161); }
.r-cdhzog { padding-right: 80px; } .r-cpa5s6 { scroll-snap-align: start;
} .r-cqilzk { height: 400px; } .r-d822y2 { color: rgb(5, 80, 174); }
.r-deolkf { box-sizing: border-box; } .r-dflpy8 { height: 1.2em; }
.r-dkge59 { background-color: rgb(170, 184, 194); } .r-dnmrzs {
max-width: 100%; } .r-dse9kg { outline-style: auto; } .r-dvzd6p { right:
-1px; } .r-dvzwsg { border-left-color: rgb(211, 220, 228); } .r-dwliz8 {
border-left-width: 2px; } .r-e1k2in { right: 16px; } .r-e9uq0i {
animation-duration: 1200ms; } .r-ea455c { border: none; } .r-eafdt9 {
transition-duration: 0.15s; } .r-ecifi { max-width: 970px; } .r-ehq7j7 {
background-size: contain; } .r-epq5cr { height: 2px; } .r-eqz5dr {
flex-direction: column; } .r-eu3ka { height: 40px; } .r-fdjqy7 {
text-align: left; } .r-fl3jdt { background-color: rgb(246, 254, 246); }
.r-flmpir { border-bottom-color: rgb(40, 49, 67); } .r-fnigne {
border-right-width: 0px; } .r-fpub7 { color: rgba(0, 0, 0, 0); }
.r-fvlm2j { color: rgb(40, 106, 127); } .r-g3mlsw { animation-name:
r-t2lo5v; } .r-gg6oyi { font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; } .r-ggadg3 { left: -2px; } .r-givd4m { left: -5px; }
.r-gl891g { min-width: 420px; } .r-gpkeig { border-right-color:
var(--sp-color-border-base); } .r-gtdqiz { position: sticky; } .r-gu0qjt
{ padding-left: 32px; } .r-gxnn5r { border-left-width: 0px; } .r-gxopl6
{ left: 316px; } .r-gy4na3 { padding-left: 0px; } .r-gys0vz { color:
rgb(0, 136, 71); } .r-h2mvr { min-width: 8px; } .r-h2q2x { transform:
scaleX(-1); } .r-h3s6tt { height: 48px; } .r-h7ga17 { background-color:
rgb(43, 46, 57); } .r-h7gdob { color: currentcolor; } .r-ha54is { }
.r-hauab { transition: width 50ms ease-in-out 0s; } .r-hbpseb {
line-height: 22px; } .r-hd655f { color: rgb(162, 169, 185); } .r-homxoj
{ color: inherit; } .r-hq6u89 { left: 92%; } .r-htfu76 { margin-left:
-8px; } .r-hxflta { padding-right: env(safe-area-inset-right); }
.r-i023vh { padding-right: 16px; } .r-i7h7g2 { backdrop-filter:
blur(5px); } .r-i8xx8x { color: rgb(207, 34, 46); } .r-ia06lx {
background-color: rgb(115, 92, 255); } .r-ibjss6 { background-color:
rgb(136, 153, 168); } .r-icoktb { opacity: 0.5; } .r-ifefl9 {
min-height: 0px; } .r-ihd41t { border: 1px solid rgb(55, 65, 81); }
.r-iphfwy { padding-bottom: 4px; } .r-ipm5af { top: 0px; } .r-iqs06e {
background-image: radial-gradient(rgba(255, 255, 255, 0.1), rgb(255,
255, 255)); } .r-ir6n1k { border-top-right-radius: 6px; } .r-ixzivm { }
.r-iyfy8q { width: auto; } .r-j300sb { animation-name: r-1rx4pb; }
.r-jfrpv2 { color: rgb(130, 80, 223); } .r-jn0m22 { top: 54px; }
.r-jn5ml { right: -5px; } .r-jvuzdy { top: -5px; } .r-jwli3a { color:
rgb(255, 255, 255); } .r-jxjwwx { left: 24px; } .r-k200y { align-self:
flex-start; } .r-k923pl { background-color: rgb(218, 212, 255); }
.r-kbz91p { border-top-color: rgb(86, 234, 87); } .r-kcufgn { cursor:
ew-resize; } .r-key0ze { height: 240px; } .r-kicko2 {
border-top-left-radius: 4px; } .r-kls4rr { padding-right: 40px; }
.r-knv0ih { margin-top: 8px; } .r-kquydp { right: -4px; } .r-ky29hr {
bottom: 2px; } .r-l0gwng { width: 200px; } .r-l13dpy { z-index: 200; }
.r-l27s25 { background-color: rgb(204, 207, 212); } .r-l9hqf4 {
box-shadow: rgba(0, 0, 0, 0.69) 0px 1px 1px; } .r-labphf { height:
fit-content; } .r-lchren { margin-right: auto; } .r-ld67tl { left:
-72px; } .r-lk1fr1 { } .r-lltvgl { overflow-x: auto; } .r-lqms97 {
margin-left: -1px; } .r-lrsllp { width: 24px; } .r-lrvibr { user-select:
none; } .r-lv5dtd { padding-left: 110px; } .r-lx1l9k { background-image:
radial-gradient(rgba(255, 255, 255, 0.1), rgb(255, 255, 255)); }
.r-m0vln2 { border-left-color: rgb(43, 46, 57); } .r-m2pi6t {
padding-left: 4px; } .r-m5arl1 { width: 2px; } .r-m5n4jz {
background-color: rgb(220, 238, 244); } .r-mabqd8 { height: 32px; }
.r-majxgm { font-weight: 500; } .r-mbgqwd { margin-right: 24px; }
.r-mfh4gg { scroll-snap-type: x mandatory; } .r-mhe3cw { z-index: 10; }
.r-ms8t9i { border-left-width: 3px; } .r-na6qhi { } .r-ng8e2f { cursor:
grab; } .r-njhh6i { color: rgb(78, 170, 200); } .r-nkouq2 { box-shadow:
rgba(36, 42, 49, 0.6) -5px 0px 7px; } .r-notknq {
border-top-right-radius: 4px; } .r-nvplwv { animation-timing-function:
ease-out; } .r-nvvorq { top: 3.5px; } .r-nwxazl { line-height: 40px; }
.r-nzcix3 { border-bottom-color: rgb(227, 232, 237); } .r-o8yidv {
border-top-left-radius: 6px; } .r-o9xkwf { top: 2px; } .r-obd0qt {
align-items: flex-end; } .r-onxxid { background-color: rgba(27, 30, 33,
0.77); } .r-op3p1c { width: 520px; } .r-orgf3d { opacity: 0; } .r-ou6ah9
{ border-top-left-radius: 0px; } .r-oucylx { border-bottom-color:
rgba(0, 0, 0, 0); } .r-oz83uh { box-shadow: rgba(0, 0, 0, 0.12) 0px 1px
1px; } .r-p1pxzi { margin-bottom: 0px; } .r-pex7a0 { color: rgb(130, 7,
30); } .r-pi8zqv { box-shadow: rgba(0, 0, 0, 0.04) 0px 0px 7px; }
.r-pm9dpa { max-height: 100%; } .r-puj83k { padding-left: 24px; }
.r-py1axk { border-bottom-right-radius: 7px; } .r-q4m81j { text-align:
center; } .r-qklmqi { border-bottom-width: 1px; } .r-qn3fzs {
padding-bottom: 24px; } .r-r1s0sa { background-color: rgb(255, 235,
233); } .r-r9hte5 { backdrop-filter: blur(10px); } .r-redadu {
margin-left: var(--sp-spacing-200); } .r-rs94m5 { background-image:
url("data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiIHN0YW5kYWxvbmU9Im5vIj8+CjxzdmcKICAgeG1sbnM6ZGM9Imh0dHA6Ly9wdXJsLm9yZy9kYy9lbGVtZW50cy8xLjEvIgogICB4bWxuczpjYz0iaHR0cDovL2NyZWF0aXZlY29tbW9ucy5vcmcvbnMjIgogICB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiCiAgIHhtbG5zOnN2Zz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiAgIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIKICAgdmVyc2lvbj0iMS4xIgogICB2aWV3Qm94PSIwIDAgMSAxIgogICBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJ4TWluWU1pbiBtZWV0Ij4KICA8cGF0aAogICAgIGQ9Ik0gMC4wNDAzODA1OSwwLjYyNjc3NjcgMC4xNDY0NDY2MSwwLjUyMDcxMDY4IDAuNDI5Mjg5MzIsMC44MDM1NTMzOSAwLjMyMzIyMzMsMC45MDk2MTk0MSB6IE0gMC4yMTcxNTcyOSwwLjgwMzU1MzM5IDAuODUzNTUzMzksMC4xNjcxNTcyOSAwLjk1OTYxOTQxLDAuMjczMjIzMyAwLjMyMzIyMzMsMC45MDk2MTk0MSB6IgogICAgIGlkPSJyZWN0Mzc4MCIKICAgICBzdHlsZT0iZmlsbDojZmZmZmZmO2ZpbGwtb3BhY2l0eToxO3N0cm9rZTpub25lIiAvPgo8L3N2Zz4K");
} .r-rweumo { color: rgb(208, 249, 208); } .r-rwqe4o { width: 48px; }
.r-s09aw7 { background-image: linear-gradient(to left, rgb(115, 92,
255), rgb(109, 28, 169), rgb(96, 104, 191), rgb(0, 136, 71), rgb(255,
209, 57), rgb(185, 94, 4), rgb(211, 61, 61)); } .r-s0e3za {
padding-left: 80px; } .r-s8bhmr { min-width: 56px; } .r-sfbmgh {
z-index: 9999; } .r-sga3zk { height: 64px; } .r-sgscqh { width: 250px; }
.r-t12b5v { border-top-right-radius: 0px; } .r-t1hnsm { transition:
transform 150ms ease 0s; } .r-t9hbny { background-color: rgb(211, 61,
61); } .r-tceitz { left: 16px; } .r-td7lzs { background-color:
var(--sp-color-bg-standout-side); } .r-tfaxyh { background-color:
rgb(86, 234, 87); } .r-tni569 { background-color: rgb(11, 79, 47); }
.r-tskmnb { padding-top: 8px; } .r-tsynxw { text-transform: uppercase; }
.r-u529wo { transform: translateY(-2px); } .r-u6sd8q {
background-repeat: no-repeat; } .r-u8s1d { position: absolute; }
.r-u92y06 { background-color: rgb(255, 165, 0); } .r-u9bbvc { }
.r-u9z937 { bottom: 80px; } .r-ubezar { font-size: 16px; } .r-ud0q2t {
letter-spacing: 1px; } .r-udcg8d { color: rgb(20, 23, 28); } .r-ufs8t {
} .r-uibjmv { font-family: gitbook-code-font, Menlo, monospace; }
.r-upfvwg { box-shadow: rgba(255, 255, 255, 0.3) 0px 0px 1px; }
.r-uweo6c { bottom: 136px; } .r-ux9zog { background-color: rgb(51, 61,
85); } .r-v2u3o6 { right: 4px; } .r-vq47rg { color: rgb(211, 61, 61); }
.r-vvn4in { background-position: center center; } .r-w0va4e {
margin-right: 40px; } .r-w9n8ly { transition-delay: 200ms; } .r-wc24c3 {
z-index: 20; } .r-wech8c { max-width: 1280px; } .r-wgabs5 {
border-bottom-width: 2px; } .r-wk8lta { padding-top: 0px; } .r-ws9h79 {
left: 4px; } .r-wwqw7s { left: -1px; } .r-wy61xf { height: 72px; }
.r-x1dlf0 { max-width: 200px; } .r-x3cy2q { background-size: 100% 100%;
} .r-xb2eav { font-size: 40px; } .r-xd6kpl { padding-bottom: 8px; }
.r-xifl00 { left: -4px; } .r-xky0vn { background-color: rgb(104, 60,
17); } .r-xnn892 { background-color: rgb(218, 251, 225); } .r-xx3c9p {
animation-name: r-imtty0; } .r-xzortm { margin-right: -16px; } .r-y18gqp
{ color: rgb(137, 240, 137); } .r-y3rmyz { width: 120px; } .r-y60x34 {
outline-color: rgb(60, 193, 60); } .r-ye2ihm { background-image: none; }
.r-yh6aho { background-image: linear-gradient(270deg, rgb(43, 46, 57)
10%, rgb(34, 39, 46), rgb(43, 46, 57) 90%); } .r-ymefdi { padding-top:
var(--sp-spacing-300); } .r-yrgyi6 { white-space: pre; } .r-ywxogp {
color: rgb(115, 92, 255); } .r-z2g584 { width: 76px; } .r-z3s97b {
border-right-color: rgb(43, 46, 57); } .r-z80fyv { height: 20px; }
.r-z9jf92 { color: rgb(234, 242, 247); } .r-zchlnj { right: 0px; }
.r-zh076v { height: 100vh; } .r-zits6j { right: 8%; } .r-zo7nv5 {
column-gap: 16px; } .r-ztyd71 { background-color: rgba(0, 0, 0, 0.2); }
.r-zv9js0 { border-left-color: rgb(86, 234, 87); } @-webkit-keyframes
r-1ak6360 { 0% { background-position-x: 0%; } 100% {
background-position-x: 100%; } } @-webkit-keyframes r-1hunrpy { 0% {
transform: translateY(100%); } 100% { transform: translateY(0%); } }
@-webkit-keyframes r-1rx4pb { 0% { transform: translateX(-100%); } 100%
{ transform: translateX(400%); } } @-webkit-keyframes r-9p3sdl { 0% {
transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
@-webkit-keyframes r-imtty0 { 0% { opacity: 0; } 100% { opacity: 1; } }
@-webkit-keyframes r-ndfo3d { 0% { transform: translateY(0%); } 100% {
transform: translateY(100%); } } @-webkit-keyframes r-t2lo5v { 0% {
opacity: 1; } 100% { opacity: 0; } } @keyframes r-1ak6360 { 0% {
background-position-x: 0%; } 100% { background-position-x: 100%; } }
@keyframes r-1hunrpy { 0% { transform: translateY(100%); } 100% {
transform: translateY(0%); } } @keyframes r-1rx4pb { 0% { transform:
translateX(-100%); } 100% { transform: translateX(400%); } } @keyframes
r-9p3sdl { 0% { transform: rotate(0deg); } 100% { transform:
rotate(360deg); } } @keyframes r-imtty0 { 0% { opacity: 0; } 100% {
opacity: 1; } } @keyframes r-ndfo3d { 0% { transform: translateY(0%); }
100% { transform: translateY(100%); } } @keyframes r-t2lo5v { 0% {
opacity: 1; } 100% { opacity: 0; } } .r-12vffkv \> \* { pointer-events:
auto; } .r-ah5dr5 \> \* { pointer-events: none; }
\[stylesheet-group="10"\] { } \[data-rnwrdesktop-166pt5r\] { width:
max(220px, ((((100vw - max(300px, ((100vw - 970px) / 2) - 0px)) - 750px)
- 110px) - 300px) - 0px); } \[data-rnwrdesktop-18u37iz\] {
flex-direction: row; }
\[data-rnwrdesktop-1hy97zq-1q6rxnj-lv5dtd-9111t9\] { padding-left:
110px; padding-right: 410px; padding-top: 80px; }
\[data-rnwrdesktop-1ph75f1\] { height: 80px; }
\[data-rnwrdesktop-1uwte3a\] { padding-bottom: 40px; }
\[data-rnwrdesktop-eu3ka\] { height: 40px; } \[data-rnwrdesktop-fnigne\]
{ border-right-width: 0px; }
\[data-rnwrdesktop-gg6oyi-1x35g6-37tt59-b88u0q\] { font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; font-size: 24px; font-weight: 700;
line-height: 32px; } \[data-rnwrdesktop-gg6oyi-adyw6z-135wba7-b88u0q\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 20px; font-weight:
700; line-height: 24px; }
\[data-rnwrdesktop-gg6oyi-ubezar-135wba7-1kfrs79\] { font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 600;
line-height: 24px; } \[data-rnwrdesktop-gg6oyi-xb2eav-1dn12g7-b88u0q\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 40px; font-weight:
700; line-height: 48px; } \[data-rnwrdesktop-h3s6tt\] { height: 48px; }
\[data-rnwrdesktop-hidden\] { display: none; }
\[data-rnwrdesktop-iyfy8q-1qhn6m8-11g3r6m-1h0z5md\] { justify-content:
flex-start; padding-left: 16px; padding-right: 24px; width: auto; }
\[data-rnwrdesktop-visible\] { display: flex; }
\[data-rnwrdesktop-1moh23t-e1k2in\] { bottom: 16px; right: 16px; }
\[stylesheet-group="11"\] { } @media (max-width: 1024px) and (max-width:
9999999.49485052px) { \[data-rnwr1024-eqz5dr\] { flex-direction: column;
} } @media (max-width: 1024px) and (max-width: 9999999.49485052px) {
\[data-rnwr1024-1ifxtd0\] { margin-bottom: 16px; } } @media (max-width:
1280px) and (max-width: 9999999.49505648px) { \[data-rnwr1280-hidden\] {
display: none; } } @media (max-width: 1280px) and (max-width:
9999999.49505648px) { \[data-rnwr1280-1777fci\] { justify-content:
center; } } @media (max-width: 1430px) and (max-width:
9999999.49525148px) { \[data-rnwr1430-visible\] { display: flex; } }
@media (max-width: 1490px) and (max-width: 9999999.49525748px) {
\[data-rnwr1490-1777fci\] { justify-content: center; } } @media
(max-width: 1430px) and (max-width: 9999999.49525148px) {
\[data-rnwr1430-visible\] { display: flex; } } @media (max-width:
1280px) and (max-width: 9999999.49505648px) { \[data-rnwr1280-1777fci\]
{ justify-content: center; } } @media (max-width: 1490px) and
(max-width: 9999999.49525748px) { \[data-rnwr1490-1777fci\] {
justify-content: center; } } @media (max-width: 1024px) and (max-width:
9999999.49485052px) { \[data-rnwr1024-eqz5dr\] { flex-direction: column;
} } @media (max-width: 1024px) and (max-width: 9999999.49485052px) {
\[data-rnwr1024-1ifxtd0\] { margin-bottom: 16px; } } @media (max-width:
1280px) and (max-width: 9999999.49505648px) { \[data-rnwr1280-hidden\] {
display: none; } } \[stylesheet-group="12"\] { } @media (max-width:
700px) and (max-width: 9999999.55484845px) { \[data-rnwr700-eqz5dr\] {
flex-direction: column; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-ubezar-135wba7-1kfrs79\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 16px; font-weight:
600; line-height: 24px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-ubezar-135wba7-1o2nx2a\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 16px; font-weight:
360; line-height: 24px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-1ui5ee8-nwxazl-b88u0q\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 32px; font-weight:
700; line-height: 40px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-adyw6z-135wba7-b88u0q\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 20px; font-weight:
700; line-height: 24px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-hidden\] { display: none; } }
@media (max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-iyfy8q-eu3ka\] { height: 40px; width: auto; } } @media
(max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-iyfy8q-gy4na3-i023vh-1wbh5a2-1h0z5md-\] { flex-shrink: 1;
justify-content: flex-start; padding-left: 0px; padding-right: 16px;
width: auto; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-sga3zk\] { height: 64px; } } @media
(max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-visible\] { display: flex; } } @media (max-width: 700px)
and (max-width: 9999999.55484846px) { \[data-rnwr700-1g7fiml\] { height:
30px; } } @media (max-width: 700px) and (max-width: 9999999.55484846px)
{ \[data-rnwr700-1w6e6rj-1777fci\] { flex-wrap: wrap; justify-content:
center; } } @media (max-width: 700px) and (max-width:
9999999.55484846px) { \[data-rnwr700-13l2t4g\] { border-right-width:
1px; } } @media (max-width: 700px) and (max-width: 9999999.55484846px) {
\[data-rnwr700-95jzfe-1qhn6m8-i023vh\] { padding-left: 16px;
padding-right: 16px; padding-top: 16px; } } @media (max-width: 970px)
and (max-width: 9999999.57554845px) { \[data-rnwr970-eqz5dr\] {
flex-direction: column; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-sga3zk\] { height: 64px; } } @media
(max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-visible\] { display: flex; } } @media (max-width: 700px)
and (max-width: 9999999.55484845px) {
\[data-rnwr700-iyfy8q-gy4na3-i023vh-1wbh5a2-1h0z5md-\] { flex-shrink: 1;
justify-content: flex-start; padding-left: 0px; padding-right: 16px;
width: auto; } } @media (max-width: 700px) and (max-width:
9999999.55484846px) { \[data-rnwr700-1g7fiml\] { height: 30px; } }
@media (max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-hidden\] { display: none; } } @media (max-width: 700px)
and (max-width: 9999999.55484845px) { \[data-rnwr700-eqz5dr\] {
flex-direction: column; } } @media (max-width: 700px) and (max-width:
9999999.55484846px) { \[data-rnwr700-13l2t4g\] { border-right-width:
1px; } } @media (max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-iyfy8q-eu3ka\] { height: 40px; width: auto; } } @media
(max-width: 700px) and (max-width: 9999999.55484845px) {
\[data-rnwr700-gg6oyi-1ui5ee8-nwxazl-b88u0q\] { font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; font-size: 32px; font-weight: 700;
line-height: 40px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-adyw6z-135wba7-b88u0q\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 20px; font-weight:
700; line-height: 24px; } } @media (max-width: 700px) and (max-width:
9999999.55484846px) { \[data-rnwr700-1w6e6rj-1777fci\] { flex-wrap:
wrap; justify-content: center; } } @media (max-width: 700px) and
(max-width: 9999999.55484845px) {
\[data-rnwr700-gg6oyi-ubezar-135wba7-1kfrs79\] { font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 600;
line-height: 24px; } } @media (max-width: 700px) and (max-width:
9999999.55484845px) { \[data-rnwr700-gg6oyi-ubezar-135wba7-1o2nx2a\] {
font-family: gitbook-content-font, -apple-system, BlinkMacSystemFont,
"Segoe UI", Helvetica, Arial, sans-serif; font-size: 16px; font-weight:
360; line-height: 24px; } } @media (max-width: 970px) and (max-width:
9999999.57554845px) { \[data-rnwr970-eqz5dr\] { flex-direction: column;
} } @media (max-width: 700px) and (max-width: 9999999.55484846px) {
\[data-rnwr700-1moh23t-e1k2in-tceitz\] { bottom: 16px; left: 16px;
right: 16px; } } \[stylesheet-group="13"\] { } @media (max-width: 700px)
and (max-width: 9999999.55484846px) { \[data-rnwr700-1777fci\] {
justify-content: center; } } @media (max-width: 700px) and (max-width:
9999999.55484846px) { \[data-rnwr700-1777fci\] { justify-content:
center; } } \[stylesheet-group="20"\] { } \[data-rnwi-1pa6394-\] {
color: var(--sp-color-text-muted); } \[data-rnwi-handle="link"\]
\[data-rnwilink--y18gqp-\] { color: rgb(137, 240, 137); }
body:not(.dragging) \[data-rnwi--1jti08r--focus\]:focus { border-color:
rgb(86, 234, 87); } body:not(.dragging)
\[data-rnwi--njhh6i-hover-focus\]:hover, body:not(.dragging)
\[data-rnwi--njhh6i-hover-focus\]:focus { color: rgb(78, 170, 200); }
body:not(.dragging) \[data-rnwi--y18gqp-hover-focus\]:hover,
body:not(.dragging) \[data-rnwi--y18gqp-hover-focus\]:focus { color:
rgb(137, 240, 137); } body:not(.dragging)
\[data-rnwi-157h22z-hover\]:hover { background-color: rgb(45, 50, 58); }
body:not(.dragging) \[data-rnwi-1iadl42-hover-focus\]:hover,
body:not(.dragging) \[data-rnwi-1iadl42-hover-focus\]:focus {
background-color: var(--sp-color-bg-standout-base); }
body:not(.dragging)
\[data-rnwi-5xr8s6-dse9kg-1rbj2e8-2fw26j-focus-visible\]:focus-visible {
outline: rgb(245, 247, 249) auto 2px; outline-offset: 0px; }
body:not(.dragging) \[data-rnwi-handle="BaseCard"\]:hover
\[data-rnwibasecard--y18gqp-hover-focus\], body:not(.dragging)
\[data-rnwi-handle="BaseCard"\]:focus
\[data-rnwibasecard--y18gqp-hover-focus\] { color: rgb(137, 240, 137); }
body:not(.dragging) \[data-rnwi-handle="BaseCard"\]:hover
\[data-rnwibasecard--y18gqp-hover\] { color: rgb(137, 240, 137); }
body:not(.dragging) \[data-rnwi-handle="button"\]:hover
\[data-rnwibutton--5k5nmx-hover-focus\], body:not(.dragging)
\[data-rnwi-handle="button"\]:focus
\[data-rnwibutton--5k5nmx-hover-focus\] { color: rgb(86, 234, 87); }
body:not(.dragging) \[data-rnwi-handle="button"\]:hover
\[data-rnwibutton-37p410-hover-focus\], body:not(.dragging)
\[data-rnwi-handle="button"\]:focus
\[data-rnwibutton-37p410-hover-focus\] { color:
var(--sp-color-text-base); } body:not(.dragging)
\[data-rnwi-handle="link"\]:hover
\[data-rnwilink--1b389cn-1ddef8g-hover\] { color: rgb(60, 193, 60);
text-decoration-line: underline; } body:not(.dragging)
\[data-rnwi-handle="nearest"\]:hover
\[data-rnwinearest--njhh6i-hover-focus\], body:not(.dragging)
\[data-rnwi-handle="nearest"\]:focus
\[data-rnwinearest--njhh6i-hover-focus\] { color: rgb(78, 170, 200); }
body:not(.dragging) \[data-rnwi-handle="nearest"\]:hover
\[data-rnwinearest--y18gqp-hover\] { color: rgb(137, 240, 137); }
body:not(.dragging) \[data-rnwi-handle="nearest"\]:hover
\[data-rnwinearest-37p410-hover-focus\], body:not(.dragging)
\[data-rnwi-handle="nearest"\]:focus
\[data-rnwinearest-37p410-hover-focus\] { color:
var(--sp-color-text-base); } body:not(.dragging)
\[data-rnwi-m2nopt-hover-focus\]:hover, body:not(.dragging)
\[data-rnwi-m2nopt-hover-focus\]:focus { border-color: rgb(43, 46, 57);
} body:not(.dragging)
\[data-rnwi-u529wo-aq1qub-c1zw6o-1k4bu33-1cut0bx-na6qhi--hover\]:hover {
box-shadow: rgba(0, 0, 0, 0.12) 0px 12px 13px; transform:
translateY(-2px); }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-b0ce88ee-00d4-432e-aa77-56ae35c9d99a@mhtml.blink @charset
"utf-8"; html, body { -webkit-font-smoothing: antialiased;
text-rendering: optimizelegibility; width: 100%; min-height: 100vh;
user-select: none; outline: none; position: relative; } @supports
(-webkit-touch-callout: none) { html, body, .gitbook-root { min-height:
-webkit-fill-available; } } .gitbook-root { display: flex; min-height:
100vh; }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-39584592-ae9a-463d-90ce-46ba1b1a352b@mhtml.blink @charset
"utf-8"; .iframely-responsive { top: 0px; left: 0px; width: 100%;
height: 0px; position: relative; padding-bottom: 56.25%; box-sizing:
border-box; } .iframely-responsive \> \* { top: 0px; left: 0px; width:
100%; height: 100%; position: absolute; border: 0px; box-sizing:
border-box; }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
https://app.gitbook.com/public/app/public-ID23QPJH.css?v=10.9.545-61e5a4ac58d3c51841a883524c519b974d97db1f-7449304366
@charset "utf-8"; \*, ::before, ::after { box-sizing: border-box; }
:focus, :hover { outline: none; } body, h1, h2, h3, h4, p, figure,
blockquote, dl, dd { margin: 0px; } a:not(\[class\]) {
text-decoration-skip-ink: auto; } :root, .theme-color-light {
--sp-color-black: \#000000; --sp-color-white: \#ffffff;
--sp-color-transparent: transparent; --sp-color-primary-100: \#F3FAFB;
--sp-color-primary-200: \#DCEEF4; --sp-color-primary-300: \#89C6DA;
--sp-color-primary-400: \#4EAAC8; --sp-color-primary-500: \#307F98;
--sp-color-primary-600: \#286A7F; --sp-color-primary-700: \#275564;
--sp-color-primary-800: \#11262D; --sp-color-dark-mode-100: \#7A808B;
--sp-color-dark-mode-200: \#58616E; --sp-color-dark-mode-300: \#374151;
--sp-color-dark-mode-400: \#2D323A; --sp-color-dark-mode-500: \#2B2E39;
--sp-color-dark-mode-600: \#22272E; --sp-color-dark-mode-700: \#14171C;
--sp-color-dark-mode-800: \#0a0c0e; --sp-color-action-bg-danger-default:
\#d33d3d; --sp-color-action-bg-danger-hover: \#cc3131;
--sp-color-action-bg-danger-focus: \#d33d3d;
--sp-color-action-bg-merge-default: \#735cff;
--sp-color-action-bg-merge-hover: \#5f45ff;
--sp-color-action-bg-merge-focus: \#735cff;
--sp-color-action-bg-primary-default: \#307F98;
--sp-color-action-bg-primary-hover: \#286A7F;
--sp-color-action-bg-primary-focus: \#307F98;
--sp-color-action-bg-secondary-default: \#ffffff;
--sp-color-action-bg-secondary-hover: \#f7f7f7;
--sp-color-action-bg-secondary-focus: \#f7f7f7;
--sp-color-action-bg-upgrade-default: \#E44F89;
--sp-color-action-bg-upgrade-hover: \#DB3B79;
--sp-color-action-bg-upgrade-focus: \#E44F89;
--sp-color-action-bg-blank-default: transparent;
--sp-color-action-bg-nested-hover: \#eaebee;
--sp-color-action-border-default: transparent;
--sp-color-action-border-secondary-inactive: \#f7f7f7;
--sp-color-attention-upgrade: \#E44F89; --sp-color-icon-ask-gitbook:
\#4EAAC8; --sp-color-icon-menu-default: \#a4a7b0;
--sp-color-icon-menu-hover: \#656973; --sp-color-icon-menu-active:
\#4EAAC8; --sp-color-icon-menu-disabled: \#c4c6cc;
--sp-color-icon-danger-default: \#d33d3d; --sp-color-icon-info-default:
\#89C6DA; --sp-color-icon-diff-added: \#008847;
--sp-color-icon-diff-deleted: \#d33d3d; --sp-color-icon-diff-modified:
\#4EAAC8; --sp-color-icon-upgrade: \#E44F89;
--sp-color-text-interactive: \#307F98; --sp-color-text-light: \#a4a7b0;
--sp-color-text-muted: \#656973; --sp-color-text-base: \#262930;
--sp-color-text-inverted: \#dedfe3; --sp-color-text-primary: \#ffffff;
--sp-color-text-secondary: \#52555e; --sp-color-text-info: \#286A7F;
--sp-color-text-danger: \#d33d3d; --sp-color-text-merge: \#735cff;
--sp-color-text-upgrade: \#E44F89; --sp-color-text-success: \#008847;
--sp-color-text-alpha: \#B4641A; --sp-color-text-menu-default: \#656973;
--sp-color-text-menu-hover: \#262930; --sp-color-text-menu-active:
\#307F98; --sp-color-text-menu-disabled: \#c4c6cc;
--sp-color-text-menu-dark-default: \#eaebee;
--sp-color-text-menu-dark-hover: \#ffffff;
--sp-color-text-menu-dark-active: \#F3FAFB;
--sp-color-text-menu-dark-disabled: \#c4c6cc;
--sp-color-text-input-placeholder: \#a4a7b0;
--sp-color-text-stepper-light-default: \#a4a7b0;
--sp-color-text-stepper-light-active: \#4EAAC8;
--sp-color-text-stepper-light-error: \#d33d3d;
--sp-color-text-stepper-dark-default: \#a4a7b0;
--sp-color-text-stepper-dark-active: \#4EAAC8;
--sp-color-text-stepper-dark-error: \#d33d3d;
--sp-color-text-sign-in-terms: \#a4a7b0;
--sp-color-text-sign-in-subtitle: \#656973; --sp-color-bg-base:
\#ffffff; --sp-color-bg-side: \#f7f7f7; --sp-color-bg-card: \#ffffff;
--sp-color-bg-muted: \#f7f7f7; --sp-color-bg-inactive: \#f7f7f7;
--sp-color-bg-standout-base: \#f7f7f7; --sp-color-bg-standout-on-base:
\#eaebee; --sp-color-bg-standout-side: \#eaebee;
--sp-color-bg-standout-on-side: \#dedfe3; --sp-color-bg-primary:
\#4EAAC8; --sp-color-bg-secondary: \#f7f7f7; --sp-color-bg-info:
\#DCEEF4; --sp-color-bg-danger: \#ffe4e3; --sp-color-bg-merge: \#f2f0ff;
--sp-color-bg-upgrade: \#FFF6FA; --sp-color-bg-success: \#dffff0;
--sp-color-bg-alpha: \#FFDCBC; --sp-color-bg-suggestion-default:
\#f7f7f7; --sp-color-bg-suggestion-hover: \#eaebee;
--sp-color-bg-menu-default: \#ffffff; --sp-color-bg-menu-hover:
\#f7f7f7; --sp-color-bg-menu-active: \#F3FAFB;
--sp-color-bg-menu-dark-default: \#2a3142;
--sp-color-bg-menu-dark-hover: \#353d53; --sp-color-bg-menu-dark-active:
\#5f677b; --sp-color-bg-keyboard-shortcut-default: \#ffffff;
--sp-color-bg-keyboard-shortcut-inverted: \#262930;
--sp-color-join-organizations-card-default: \#ffffff;
--sp-color-join-organizations-card-hover: \#f7f7f7;
--sp-color-join-organizations-card-focus: \#eaebee;
--sp-color-border-base: \#eaebee; --sp-color-border-light: \#f7f7f7;
--sp-color-border-standout: \#eaebee; --sp-color-border-table: \#dedfe3;
--sp-color-border-card: \#f7f7f7; --sp-color-border-menu-default:
\#f7f7f7; --sp-color-border-menu-dark: \#353d53;
--sp-color-border-keyboard-shortcut-default: \#eaebee;
--sp-color-border-keyboard-shortcut-inverted: \#52555e;
--sp-color-button-upgrade-bg-default: \#E44F89;
--sp-color-button-upgrade-bg-hover: \#DB3B79;
--sp-color-button-upgrade-bg-focus: \#E44F89;
--sp-color-button-upgrade-text: \#ffffff;
--sp-color-button-muted-bg-default: rgba(0, 0, 0, 0);
--sp-color-button-muted-bg-hover: \#eaebee;
--sp-color-button-muted-bg-focus: \#eaebee;
--sp-color-button-inline-text-default: \#262930;
--sp-color-button-inline-text-hover: \#52555e;
--sp-color-button-inline-text-focus: \#656973;
--sp-color-button-pill-bg-active: \#F3FAFB; --sp-color-button-pill-text:
\#52555e; --sp-color-button-pill-border: \#89C6DA;
--sp-color-search-group-border-light: \#eaebee;
--sp-color-search-group-border-dark: \#262930;
--sp-color-search-group-heading: \#656973; --sp-color-search-ai-cta-bg:
\#F3FAFB; --sp-color-search-ai-cta-text-default: \#52555e;
--sp-color-search-ai-cta-text-highlight: \#262930;
--sp-color-search-ai-cta-border: \#4EAAC8;
--sp-color-search-ai-cta-action-button: \#4EAAC8;
--sp-color-search-ai-cta-icon: \#4EAAC8;
--sp-color-search-result-item-regular-bg-light: \#f7f7f7;
--sp-color-search-result-item-regular-bg-dark: \#262930;
--sp-color-search-icons-sparkle-search-color-light: \#4EAAC8;
--sp-color-search-icons-sparkle-search-color-dark: \#89C6DA;
--sp-color-sidesheet-header-border: \#eaebee;
--sp-color-sidesheet-avatar-badge-border: \#ffffff;
--sp-color-sidesheet-avatar-bg: \#2a3142;
--sp-color-sidesheet-list-item-bg-hover: \#f7f7f7;
--sp-color-comments-comment-bg-active: \#F3FAFB;
--sp-color-comments-comment-bg-resolved: \#f7f7f7;
--sp-color-segmented-control-bg: \#f7f7f7;
--sp-color-segmented-control-active-segment-bg: \#ffffff;
--sp-color-segmented-control-active-segment-border: rgba(0, 0, 0, 0);
--sp-color-segmented-control-text-hover: \#262930;
--sp-color-segmented-control-text-disabled: \#a4a7b0;
--sp-theme-color-primary-100: var(--custom-theme-color-primary-xxlight,
\#F3FAFB); --sp-theme-color-primary-200:
var(--custom-theme-color-primary-xlight, \#DCEEF4);
--sp-theme-color-primary-300: var(--custom-theme-color-primary-light,
\#89C6DA); --sp-theme-color-primary-400:
var(--custom-theme-color-primary-base, \#4EAAC8);
--sp-theme-color-primary-500: var(--custom-theme-color-primary-dark,
\#307F98); --sp-theme-color-primary-600:
var(--custom-theme-color-primary-xdark, \#286A7F);
--sp-theme-color-primary-700: var(--custom-theme-color-primary-xxdark,
\#275564); --sp-theme-radius-medium: 4px; --sp-theme-radius-large: 6px;
--sp-theme-radius-xlarge: 8px; --sp-insights-meters-searches: \#4EAAC8;
--sp-insights-meters-hits: \#b2a5ff; --sp-focus-ring: 0px 0px 0px 1px
var(--sp-color-white), 0px 0px 0px 3px var(--sp-color-primary-300);
--sp-duration-immediate: 0; --sp-duration-short-1: 50ms;
--sp-duration-short-2: 0.1s; --sp-duration-short-3: 0.15s;
--sp-duration-short-4: 0.2s; --sp-duration-short-5: 0.25s;
--sp-duration-medium-1: 0.3s; --sp-duration-medium-2: 0.35s;
--sp-duration-medium-3: 0.4s; --sp-duration-medium-4: 0.5s;
--sp-duration-medium-5: 0.6s; --sp-duration-long-1: 0.7s;
--sp-duration-long-2: 0.8s; --sp-duration-long-3: 0.9s;
--sp-duration-seconds-1: 1s; --sp-duration-seconds-2: 2s;
--sp-duration-seconds-3: 3s; --sp-duration-seconds-4: 4s;
--sp-duration-seconds-5: 5s; --sp-radius-0: 0; --sp-radius-100: 1px;
--sp-radius-200: 3px; --sp-radius-300: 4px; --sp-radius-400: 6px;
--sp-radius-500: 8px; --sp-radius-pill: 999px; --sp-radius-circle: 100%;
--sp-radius-badge: 50%; --sp-shadow-base: 0px 1px 2px 0px rgba(0, 0, 0,
0.15), 0px -1px 1px 0px rgba(0, 0, 0, 0.05); --sp-shadow-elevated: 0px
8px 14px 3px rgba(31, 41, 51, 0.08), 0px 2px 2px 0px rgba(0, 0, 0,
0.07); --sp-shadow-sidebar-main: 0px -22px 24px rgba(51, 61, 85, 1);
--sp-shadow-organization-creation-logo-first-layer: 0px 1.66667px
3.33333px rgba(0, 0, 0, 0.15);
--sp-shadow-organization-creation-logo-second-layer: 0px -1.66667px
1.66667px rgba(0, 0, 0, 0.05); --sp-shadow-segmented-control: 0px 1px
2px 0px rgba(0, 0, 0, 0.15); --sp-size-100: 12px; --sp-size-125: 14px;
--sp-size-150: 16px; --sp-size-200: 18px; --sp-size-250: 20px;
--sp-size-300: 24px; --sp-size-350: 28px; --sp-size-400: 32px;
--sp-size-425: 36px; --sp-size-450: 40px; --sp-size-500: 48px;
--sp-size-600: 64px; --sp-size-700: 80px; --sp-size-icon-100: 12px;
--sp-size-icon-200: 14px; --sp-size-icon-300: 16px; --sp-size-icon-400:
18px; --sp-size-icon-500: 20px; --sp-size-icon-600: 24px;
--sp-size-icon-700: 28px; --sp-size-icon-800: 30px; --sp-size-icon-900:
32px; --sp-size-icon-925: 48px; --sp-size-icon-950: 64px;
--sp-size-button-100: 20px; --sp-size-button-200: 24px;
--sp-size-button-300: 32px; --sp-size-button-400: 40px;
--sp-size-button-500: 48px; --sp-spacing-0: 0px; --sp-spacing-50: 2px;
--sp-spacing-100: 4px; --sp-spacing-150: 6px; --sp-spacing-200: 8px;
--sp-spacing-250: 10px; --sp-spacing-300: 12px; --sp-spacing-400: 16px;
--sp-spacing-450: 18px; --sp-spacing-500: 20px; --sp-spacing-600: 24px;
--sp-spacing-650: 32px; --sp-spacing-700: 40px; --sp-spacing-750: 50px;
--sp-spacing-800: 60px; --sp-spacing-900: 80px;
--sp-typography-page-title-font: 700 2.5rem/1.2 gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-page-title-font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-page-title-font-size:
2.5rem; --sp-typography-page-title-font-weight: 700;
--sp-typography-page-title-line-height: 1.2;
--sp-typography-page-title-letter-spacing: -0.03em;
--sp-typography-page-subtitle-font: 500 1.25rem/1.4
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-page-subtitle-font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-page-subtitle-font-size:
1.25rem; --sp-typography-page-subtitle-font-weight: 500;
--sp-typography-page-subtitle-line-height: 1.4;
--sp-typography-page-subtitle-letter-spacing: -0.02em;
--sp-typography-content-heading-large-font: 500 2rem/1.25
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-content-heading-large-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-content-heading-large-font-size: 2rem;
--sp-typography-content-heading-large-font-weight: 500;
--sp-typography-content-heading-large-line-height: 1.25;
--sp-typography-content-heading-large-letter-spacing: -0.02em;
--sp-typography-content-heading-medium-font: 500 1.5rem/1.33333
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-content-heading-medium-font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-content-heading-medium-font-size: 1.5rem;
--sp-typography-content-heading-medium-font-weight: 500;
--sp-typography-content-heading-medium-line-height: 1.33333;
--sp-typography-content-heading-medium-letter-spacing: -0.01em;
--sp-typography-content-heading-small-font: 500 1.25rem/1.4
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-content-heading-small-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-content-heading-small-font-size: 1.25rem;
--sp-typography-content-heading-small-font-weight: 500;
--sp-typography-content-heading-small-line-height: 1.4;
--sp-typography-content-heading-small-letter-spacing: 0;
--sp-typography-content-paragraph-font: 400 1rem/1.5
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-content-paragraph-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-content-paragraph-font-size: 1rem;
--sp-typography-content-paragraph-font-weight: 400;
--sp-typography-content-paragraph-line-height: 1.5;
--sp-typography-content-paragraph-letter-spacing: 0;
--sp-typography-content-mono-font: 400 1rem/1.5 gitbook-code-font,
Menlo, monospace; --sp-typography-content-mono-font-family:
gitbook-code-font, Menlo, monospace;
--sp-typography-content-mono-font-size: 1rem;
--sp-typography-content-mono-font-weight: 400;
--sp-typography-content-mono-line-height: 1.5;
--sp-typography-content-mono-letter-spacing: 0;
--sp-typography-ui-heading-large-font: 500 1.5rem/1.5
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-ui-heading-large-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-heading-large-font-size: 1.5rem;
--sp-typography-ui-heading-large-font-weight: 500;
--sp-typography-ui-heading-large-line-height: 1.5;
--sp-typography-ui-heading-large-letter-spacing: -0.01em;
--sp-typography-ui-heading-medium-font: 500 1rem/1.375
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif;
--sp-typography-ui-heading-medium-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-heading-medium-font-size: 1rem;
--sp-typography-ui-heading-medium-font-weight: 500;
--sp-typography-ui-heading-medium-line-height: 1.375;
--sp-typography-ui-heading-medium-letter-spacing: 0;
--sp-typography-ui-base-font: 400 0.875rem/1.42857 gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-base-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-base-font-size: 0.875rem;
--sp-typography-ui-base-font-weight: 400;
--sp-typography-ui-base-line-height: 1.42857;
--sp-typography-ui-base-letter-spacing: 0;
--sp-typography-ui-standout-font: 500 0.875rem/1.42857
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-standout-font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-standout-font-size:
0.875rem; --sp-typography-ui-standout-font-weight: 500;
--sp-typography-ui-standout-line-height: 1.42857;
--sp-typography-ui-standout-letter-spacing: 0;
--sp-typography-ui-action-font: 400 0.875rem/1.42857
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-action-font-family:
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-action-font-size:
0.875rem; --sp-typography-ui-action-font-weight: 400;
--sp-typography-ui-action-line-height: 1.42857;
--sp-typography-ui-action-letter-spacing: 0;
--sp-typography-ui-small-font: 500 0.75rem/1.33333 gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-small-font-family: gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-small-font-size: 0.75rem;
--sp-typography-ui-small-font-weight: 500;
--sp-typography-ui-small-line-height: 1.33333;
--sp-typography-ui-small-letter-spacing: 0.01em;
--sp-typography-ui-emphasize-font-weight: 700;
--sp-typography-stepper-label-font-small: 500 0.875rem/1.33333
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-stepper-label-font-medium:
500 1rem/1.33333 gitbook-content-font, -apple-system,
BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif; }
.theme-color-dark { --sp-color-action-bg-danger-default: \#ff918f;
--sp-color-action-bg-danger-hover: \#ffcccb;
--sp-color-action-bg-danger-focus: \#ffcccb;
--sp-color-action-bg-merge-default: \#b2a5ff;
--sp-color-action-bg-merge-hover: \#dad4ff;
--sp-color-action-bg-merge-focus: \#dad4ff;
--sp-color-action-bg-primary-default: \#89C6DA;
--sp-color-action-bg-primary-hover: \#DCEEF4;
--sp-color-action-bg-primary-focus: \#DCEEF4;
--sp-color-action-bg-secondary-default: \#22272E;
--sp-color-action-bg-secondary-hover: \#2B2E39;
--sp-color-action-bg-secondary-focus: \#22272E;
--sp-color-action-bg-upgrade-default: \#EF96B8;
--sp-color-action-bg-upgrade-hover: \#FBE8F0;
--sp-color-action-bg-upgrade-focus: \#FBE8F0;
--sp-color-action-bg-nested-hover: \#2D323A;
--sp-color-action-border-secondary-inactive: \#2D323A;
--sp-color-icon-ask-gitbook: \#89C6DA; --sp-color-icon-upgrade:
\#FBE8F0; --sp-color-text-muted: \#dedfe3; --sp-color-text-base:
\#ffffff; --sp-color-text-inverted: \#52555e; --sp-color-text-secondary:
\#ffffff; --sp-color-text-info: \#11262D; --sp-color-text-danger:
\#ffe4e3; --sp-color-text-merge: \#f2f0ff; --sp-color-text-upgrade:
\#FBE8F0; --sp-color-text-success: \#91eabf; --sp-color-text-alpha:
\#5B330D; --sp-color-text-sign-in-subtitle: \#ffffff;
--sp-color-bg-base: \#14171C; --sp-color-bg-side: \#22272E;
--sp-color-bg-card: \#262930; --sp-color-bg-muted: \#0a0c0e;
--sp-color-bg-inactive: \#22272E; --sp-color-bg-standout-base: \#2B2E39;
--sp-color-bg-standout-on-base: \#374151; --sp-color-bg-standout-side:
\#2B2E39; --sp-color-bg-standout-on-side: \#374151;
--sp-color-bg-primary: \#275564; --sp-color-bg-secondary: \#262930;
--sp-color-bg-info: \#89C6DA; --sp-color-bg-danger: \#9a1616;
--sp-color-bg-merge: \#5846ce; --sp-color-bg-upgrade: \#6F0F34;
--sp-color-bg-success: \#0c693d; --sp-color-bg-alpha: \#FFDCBC;
--sp-color-bg-suggestion-default: \#262930;
--sp-color-bg-suggestion-hover: \#52555e;
--sp-color-bg-keyboard-shortcut-default: \#262930;
--sp-color-bg-keyboard-shortcut-inverted: \#ffffff;
--sp-color-join-organizations-card-default: \#22272E;
--sp-color-join-organizations-card-hover: \#2B2E39;
--sp-color-join-organizations-card-focus: \#2D323A;
--sp-color-border-base: \#2D323A; --sp-color-border-light: \#7A808B;
--sp-color-border-standout: \#52555e; --sp-color-border-table: \#262930;
--sp-color-border-card: \#262930;
--sp-color-border-keyboard-shortcut-default: \#52555e;
--sp-color-border-keyboard-shortcut-inverted: \#eaebee;
--sp-color-button-upgrade-bg-default: \#DB3B79;
--sp-color-button-upgrade-bg-hover: \#C62C68;
--sp-color-button-upgrade-bg-focus: \#DB3B79;
--sp-color-button-muted-bg-hover: \#262930;
--sp-color-button-muted-bg-focus: \#262930;
--sp-color-button-inline-text-default: \#ffffff;
--sp-color-button-inline-text-hover: \#f7f7f7;
--sp-color-button-inline-text-focus: \#eaebee;
--sp-color-button-pill-bg-active: \#22272E; --sp-color-button-pill-text:
\#dedfe3; --sp-color-search-group-heading: \#a4a7b0;
--sp-color-search-ai-cta-bg: \#2a3142; --sp-color-search-ai-cta-border:
\#89C6DA; --sp-color-search-ai-cta-action-button: \#89C6DA;
--sp-color-search-ai-cta-icon: \#89C6DA;
--sp-color-sidesheet-header-border: \#374151;
--sp-color-sidesheet-avatar-badge-border: \#22272E;
--sp-color-sidesheet-avatar-bg: \#262930;
--sp-color-sidesheet-list-item-bg-hover: \#22272E;
--sp-color-comments-comment-bg-active: \#22272E;
--sp-color-comments-comment-bg-resolved: \#14171C;
--sp-color-segmented-control-bg: \#2D323A;
--sp-color-segmented-control-active-segment-bg: \#22272E;
--sp-color-segmented-control-active-segment-border: \#374151;
--sp-color-segmented-control-text-hover: \#f7f7f7;
--sp-color-segmented-control-text-disabled: \#52555e; --sp-focus-ring: 0
0 0 1px var(--sp-color-dark-mode-500), 0px 0px 0px 3px
var(--sp-color-primary-300); --sp-shadow-base: 0px 1px 2px 0px rgba(0,
0, 0, 0.62); --sp-shadow-elevated: 0px 8px 14px 3px rgba(16, 17, 17,
0.32), 0px 2px 2px 0px rgba(0, 0, 0, 0.37); --sp-shadow-sidebar-main:
0px -22px 24px rgba(24, 28, 31, 1); } @media (prefers-color-scheme:
dark) { :root { --sp-color-action-bg-danger-default: \#ff918f;
--sp-color-action-bg-danger-hover: \#ffcccb;
--sp-color-action-bg-danger-focus: \#ffcccb;
--sp-color-action-bg-merge-default: \#b2a5ff;
--sp-color-action-bg-merge-hover: \#dad4ff;
--sp-color-action-bg-merge-focus: \#dad4ff;
--sp-color-action-bg-primary-default: \#89C6DA;
--sp-color-action-bg-primary-hover: \#DCEEF4;
--sp-color-action-bg-primary-focus: \#DCEEF4;
--sp-color-action-bg-secondary-default: \#22272E;
--sp-color-action-bg-secondary-hover: \#2B2E39;
--sp-color-action-bg-secondary-focus: \#22272E;
--sp-color-action-bg-upgrade-default: \#EF96B8;
--sp-color-action-bg-upgrade-hover: \#FBE8F0;
--sp-color-action-bg-upgrade-focus: \#FBE8F0;
--sp-color-action-bg-nested-hover: \#2D323A;
--sp-color-action-border-secondary-inactive: \#2D323A;
--sp-color-icon-ask-gitbook: \#89C6DA; --sp-color-icon-upgrade:
\#FBE8F0; --sp-color-text-muted: \#dedfe3; --sp-color-text-base:
\#ffffff; --sp-color-text-inverted: \#52555e; --sp-color-text-secondary:
\#ffffff; --sp-color-text-info: \#11262D; --sp-color-text-danger:
\#ffe4e3; --sp-color-text-merge: \#f2f0ff; --sp-color-text-upgrade:
\#FBE8F0; --sp-color-text-success: \#91eabf; --sp-color-text-alpha:
\#5B330D; --sp-color-text-sign-in-subtitle: \#ffffff;
--sp-color-bg-base: \#14171C; --sp-color-bg-side: \#22272E;
--sp-color-bg-card: \#262930; --sp-color-bg-muted: \#0a0c0e;
--sp-color-bg-inactive: \#22272E; --sp-color-bg-standout-base: \#2B2E39;
--sp-color-bg-standout-on-base: \#374151; --sp-color-bg-standout-side:
\#2B2E39; --sp-color-bg-standout-on-side: \#374151;
--sp-color-bg-primary: \#275564; --sp-color-bg-secondary: \#262930;
--sp-color-bg-info: \#89C6DA; --sp-color-bg-danger: \#9a1616;
--sp-color-bg-merge: \#5846ce; --sp-color-bg-upgrade: \#6F0F34;
--sp-color-bg-success: \#0c693d; --sp-color-bg-alpha: \#FFDCBC;
--sp-color-bg-suggestion-default: \#262930;
--sp-color-bg-suggestion-hover: \#52555e;
--sp-color-bg-keyboard-shortcut-default: \#262930;
--sp-color-bg-keyboard-shortcut-inverted: \#ffffff;
--sp-color-join-organizations-card-default: \#22272E;
--sp-color-join-organizations-card-hover: \#2B2E39;
--sp-color-join-organizations-card-focus: \#2D323A;
--sp-color-border-base: \#2D323A; --sp-color-border-light: \#7A808B;
--sp-color-border-standout: \#52555e; --sp-color-border-table: \#262930;
--sp-color-border-card: \#262930;
--sp-color-border-keyboard-shortcut-default: \#52555e;
--sp-color-border-keyboard-shortcut-inverted: \#eaebee;
--sp-color-button-upgrade-bg-default: \#DB3B79;
--sp-color-button-upgrade-bg-hover: \#C62C68;
--sp-color-button-upgrade-bg-focus: \#DB3B79;
--sp-color-button-muted-bg-hover: \#262930;
--sp-color-button-muted-bg-focus: \#262930;
--sp-color-button-inline-text-default: \#ffffff;
--sp-color-button-inline-text-hover: \#f7f7f7;
--sp-color-button-inline-text-focus: \#eaebee;
--sp-color-button-pill-bg-active: \#22272E; --sp-color-button-pill-text:
\#dedfe3; --sp-color-search-group-heading: \#a4a7b0;
--sp-color-search-ai-cta-bg: \#2a3142; --sp-color-search-ai-cta-border:
\#89C6DA; --sp-color-search-ai-cta-action-button: \#89C6DA;
--sp-color-search-ai-cta-icon: \#89C6DA;
--sp-color-sidesheet-header-border: \#374151;
--sp-color-sidesheet-avatar-badge-border: \#22272E;
--sp-color-sidesheet-avatar-bg: \#262930;
--sp-color-sidesheet-list-item-bg-hover: \#22272E;
--sp-color-comments-comment-bg-active: \#22272E;
--sp-color-comments-comment-bg-resolved: \#14171C;
--sp-color-segmented-control-bg: \#2D323A;
--sp-color-segmented-control-active-segment-bg: \#22272E;
--sp-color-segmented-control-active-segment-border: \#374151;
--sp-color-segmented-control-text-hover: \#f7f7f7;
--sp-color-segmented-control-text-disabled: \#52555e; --sp-focus-ring: 0
0 0 1px var(--sp-color-dark-mode-500), 0px 0px 0px 3px
var(--sp-color-primary-300); --sp-shadow-base: 0px 1px 2px 0px rgba(0,
0, 0, 0.62); --sp-shadow-elevated: 0px 8px 14px 3px rgba(16, 17, 17,
0.32), 0px 2px 2px 0px rgba(0, 0, 0, 0.37); --sp-shadow-sidebar-main:
0px -22px 24px rgba(24, 28, 31, 1); } } .theme-radius-straight {
--sp-theme-radius-medium: 0; --sp-theme-radius-large: 1px;
--sp-theme-radius-xlarge: 3px; } .theme-font-variable {
--sp-typography-content-paragraph-font-weight: 360;
--sp-typography-ui-base-font: 360 0.875rem/1.42857 gitbook-content-font,
-apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial,
sans-serif; --sp-typography-ui-base-font-weight: 360;
--sp-typography-ui-action-font: 440 0.875rem/1.42857
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-action-font-weight:
440; --sp-typography-ui-small-font: 440 0.75rem/1.33333
gitbook-content-font, -apple-system, BlinkMacSystemFont, "Segoe UI",
Helvetica, Arial, sans-serif; --sp-typography-ui-small-font-weight: 440;
} :root { --color-primary-xxxlight: var(--color-teal-xxxlight);
--color-primary-xxlight: var(--color-teal-xxlight);
--color-primary-xlight: var(--color-teal-xlight); --color-primary-light:
var(--color-teal-light); --color-primary-base: var(--color-teal-base);
--color-primary-dark: var(--color-teal-dark); --color-primary-xdark:
var(--color-teal-xdark); --color-primary-xxdark:
var(--color-teal-xxdark); --color-teal-xxxlight: \#f3fafb;
--color-teal-xxlight: \#dceef4; --color-teal-xlight: \#89c6da;
--color-teal-light: \#4eaac8; --color-teal-base: \#307f98;
--color-teal-dark: \#286a7f; --color-teal-xdark: \#275564;
--color-teal-xxdark: \#11262d; --color-violet-xlight: \#dad4ff;
--color-violet-light: \#b2a5ff; --color-violet-base: \#735cff;
--color-violet-dark: \#5f45ff; --color-violet-xdark: \#442fc8;
--color-scarlet-xlight: \#ffcccb; --color-scarlet-light: \#ff918f;
--color-scarlet-base: \#d33d3d; --color-scarlet-dark: \#cc3131;
--color-scarlet-xdark: \#b41a1a; --color-fuchsia-xlight: \#fbe8f0;
--color-fuchsia-light: \#ef96b8; --color-fuchsia-base: \#e44f89;
--color-fuchsia-dark: \#db3b79; --color-fuchsia-xdark: \#c62c68;
--color-orange-xlight: \#fdc389; --color-orange-light: \#ed9f51;
--color-orange-base: \#b95e04; --color-orange-dark: \#914b05;
--color-orange-xdark: \#683c11; --color-green-xxlight: \#dffff0;
--color-green-xlight: \#91eabf; --color-green-light: \#4dde98;
--color-green-base: \#008847; --color-green-dark: \#0c693d;
--color-green-xdark: \#0b4f2f; --color-white: \#ffffff; --color-black:
\#242a31; --color-backdrop-bg: rgba(27, 30, 33, 0.77);
--color-backdrop-bg-light: rgba(0, 0, 0, 0.05);
--color-backdrop-bg-transparent: rgba(0, 0, 0, 0);
--color-backdrop-dark-bg: rgba(0, 0, 0, 0.6);
--color-backdrop-dark-bg-light: rgba(0, 0, 0, 0.1);
--color-backdrop-dark-bg-transparent: rgba(0, 0, 0, 0);
--color-light-mode-sidebar-base: \#333d55;
--color-light-mode-sidebar-dark: \#283143;
--color-dark-mode-grey-scale-xxlight: \#374151;
--color-dark-mode-grey-scale-xlight: \#2d323a;
--color-dark-mode-grey-scale-light: \#2b2e39;
--color-dark-mode-grey-scale-base: \#22272e;
--color-dark-mode-grey-scale-dark: \#181c1f;
--color-dark-mode-grey-scale-xdark: \#14171c;
--color-light-mode-grey-scale-xxlight: \#f5f7f9;
--color-light-mode-grey-scale-xlight: \#eceff1;
--color-light-mode-grey-scale-light: \#e3e8ed;
--color-light-mode-grey-scale-base: \#d3dce4;
--color-light-mode-grey-scale-dark: \#cccfd4;
--color-light-mode-grey-scale-xdark: \#454545;
--color-light-mode-text-xlight: \#8899a8; --color-light-mode-text-light:
\#5c6975; --color-light-mode-text-base: \#3b454e;
--color-light-mode-text-dark: \#050505; --color-dark-mode-text-xdark:
\#a2a9b9; --color-dark-mode-text-dark: \#cccfd4;
--color-dark-mode-text-base: \#eaf2f7; --color-dark-mode-text-light:
\#ffffff; --z-index-promote: 99; --z-index-overlay: 100;
--z-index-sidesheet: 100; --z-index-popover: 100; --z-index-modal: 100;
--z-index-toast: 200; --z-index-dragged-item: 300;
--font-weight-regular: 400; --font-weight-medium: 500;
--font-weight-semibold: 600; --font-weight-bold: 700;
--theme-color-primary-xxlight: var(
--custom-theme-color-primary-xxlight, var(--color-primary-xxlight) );
--theme-color-primary-xlight: var( --custom-theme-color-primary-xlight,
var(--color-primary-xlight) ); --theme-color-primary-light: var(
--custom-theme-color-primary-light, var(--color-primary-light) );
--theme-color-primary-base: var(--custom-theme-color-primary-base,
var(--color-primary-base)); --theme-color-primary-dark:
var(--custom-theme-color-primary-dark, var(--color-primary-dark));
--theme-color-primary-xdark: var( --custom-theme-color-primary-xdark,
var(--color-primary-xdark) ); --theme-color-primary-xxdark: var(
--custom-theme-color-primary-xxdark, var(--color-primary-xxdark) ); }
:root { --focusring-color: var(--theme-color-primary-dark);
--focusring-offset-color: var(--theme-color-primary-base); }
.theme-color-dark { --focusring-color:
var(--color-light-mode-grey-scale-xxlight); --focusring-offset-color:
var(--color-white); } :root { --color-primary-main:
var(--theme-color-primary-base); --color-primary-mid:
var(--theme-color-primary-xlight); --color-primary-muted:
var(--theme-color-primary-xxlight); --color-primary-hover:
var(--theme-color-primary-dark); --color-primary-standout:
var(--theme-color-primary-xdark); --color-primary-text-inside:
var(--color-white); --color-secondary-main: var(--color-white);
--color-secondary-muted: var(--color-light-mode-grey-scale-xlight);
--color-secondary-hover: var(--color-light-mode-grey-scale-xlight);
--color-secondary-standout: var(--color-light-mode-grey-scale-light);
--color-secondary-text-inside: var(--color-light-mode-grey-scale-xdark);
--color-standout-main: var(--theme-color-primary-base);
--color-standout-standout: var(--theme-color-primary-dark);
--color-standout-text-inside: var(--color-white);
--color-backdrop-transparent: var(--color-backdrop-bg-transparent);
--color-backdrop-background: var(--color-backdrop-bg);
--color-backdrop-background-light: var(--color-backdrop-bg-light);
--color-info-main: var(--color-primary-base); --color-info-muted:
var(--color-primary-xxlight); --color-info-hover:
var(--color-primary-dark); --color-info-standout:
var(--color-primary-xdark); --color-info-text-inside:
var(--color-white); --color-success-main: var(--color-green-base);
--color-success-muted: var(--color-green-xxlight);
--color-success-standout: var(--color-green-dark);
--color-success-text-inside: var(--color-white); --color-warning-main:
var(--color-orange-base); --color-warning-muted:
var(--color-orange-xlight); --color-warning-standout:
var(--color-orange-dark); --color-warning-text-inside:
var(--color-white); --color-danger-main: var(--color-scarlet-base);
--color-danger-muted: var(--color-scarlet-xlight); --color-danger-hover:
var(--color-scarlet-dark); --color-danger-standout:
var(--color-scarlet-xdark); --color-danger-text-inside:
var(--color-white); --color-merge-main: var(--color-violet-base);
--color-merge-muted: var(--color-violet-xlight); --color-merge-hover:
var(--color-violet-dark); --color-merge-standout:
var(--color-violet-xdark); --color-merge-text-inside:
var(--color-white); --color-upgrade-main: var(--color-fuchsia-base);
--color-upgrade-muted: var(--color-fuchsia-xlight);
--color-upgrade-hover: var(--color-fuchsia-dark);
--color-upgrade-standout: var(--color-fuchsia-xdark);
--color-upgrade-text-inside: var(--color-white); --color-item-hover:
var(--color-light-mode-grey-scale-xxlight); } .theme-color-dark {
--color-primary-main: var(--theme-color-primary-base);
--color-primary-mid: var(--theme-color-primary-xdark);
--color-primary-muted: var(--color-black); --color-primary-hover:
var(--theme-color-primary-base); --color-primary-standout:
var(--theme-color-primary-dark); --color-primary-text-inside:
var(--theme-color-primary-xxdark); --color-secondary-main:
var(--color-dark-mode-grey-scale-xlight); --color-secondary-muted:
var(--color-dark-mode-grey-scale-dark); --color-secondary-hover:
var(--color-dark-mode-grey-scale-xxlight); --color-secondary-standout:
var(--color-dark-mode-grey-scale-xxlight);
--color-secondary-text-inside: var(--color-white);
--color-standout-main: var(--color-white); --color-standout-standout:
var(--color-light-mode-grey-scale-xxlight);
--color-standout-text-inside: var(--theme-color-primary-base);
--color-backdrop-background: var(--color-backdrop-dark-bg);
--color-backdrop-background-light: var(--color-backdrop-dark-bg-light);
--color-info-main: var(--color-primary-light); --color-info-hover:
var(--color-primary-light); --color-success-muted:
var(--color-green-xdark); --color-success-standout:
var(--color-green-light); --color-warning-muted:
var(--color-orange-xdark); --color-warning-standout:
var(--color-orange-light); --color-danger-main:
var(--color-scarlet-light); --color-danger-hover:
var(--color-scarlet-base); --color-item-hover:
var(--color-dark-mode-grey-scale-light); } :root {
--color-background-main: var(--color-white); --color-background-mid:
var(--color-light-mode-grey-scale-xxlight); --color-background-muted:
var(--color-light-mode-grey-scale-xxlight); --color-background-standout:
var(--color-light-mode-grey-scale-xlight); --color-background-inverted:
var(--color-dark-mode-grey-scale-dark); } .theme-color-dark {
--color-background-main: var(--color-dark-mode-grey-scale-dark);
--color-background-mid: var(--color-dark-mode-grey-scale-xdark);
--color-background-muted: var(--color-dark-mode-grey-scale-base);
--color-background-standout: var(--color-dark-mode-grey-scale-light);
--color-background-inverted: var(--color-white); } :root {
--color-text-main: var(--color-light-mode-text-base); --color-text-mid:
var(--color-light-mode-text-light); --color-text-muted:
var(--color-light-mode-text-xlight); --color-text-primary:
var(--theme-color-primary-base); --color-text-primary-muted:
var(--theme-color-primary-xxlight); --color-text-primary-mid:
var(--theme-color-primary-xlight); --color-text-primary-standout:
var(--theme-color-primary-xdark); --color-text-primary-text-inside:
var(--color-white); --color-text-standout-main:
var(--theme-color-primary-base); --color-text-inverted:
var(--color-dark-mode-text-base); --color-text-standout:
var(--color-light-mode-text-dark); } .theme-color-dark {
--color-text-main: var(--color-dark-mode-text-base); --color-text-mid:
var(--color-dark-mode-text-dark); --color-text-muted:
var(--color-dark-mode-text-xdark); --color-text-primary:
var(--theme-color-primary-light); --color-text-primary-muted: var(
--color-black ); --color-text-primary-mid:
var(--theme-color-primary-xdark); --color-text-primary-standout:
var(--theme-color-primary-dark); --color-text-primary-text-inside:
var(--theme-color-primary-xxdark); --color-text-standout-main:
var(--color-white); --color-text-inverted:
var(--color-light-mode-text-base); --color-text-standout:
var(--color-dark-mode-text-light); } :root { --shadow-pop: 0 4px 10px 0
rgba(0, 0, 0, 0.05); } .theme-color-dark { --shadow-pop: 0 4px 10px 0
rgba(0, 0, 0, 0.99); } :root { --color-gradient-primary-hover:
var(--theme-color-primary-dark), var(--theme-color-primary-xdark);
--color-gradient-secondary-hover:
var(--color-light-mode-grey-scale-xlight),
var(--color-light-mode-grey-scale-light); --color-gradient-merge-hover:
var(--color-merge-hover), var(--color-merge-standout);
--color-gradient-danger-hover: var(--color-scarlet-dark),
var(--color-scarlet-xdark); } .theme-color-dark {
--color-gradient-primary-hover: var(--theme-color-primary-base),
var(--theme-color-primary-dark); --color-gradient-secondary-hover:
var(--color-dark-mode-grey-scale-xxlight),
var(--color-dark-mode-grey-scale-xxlight);
--color-gradient-danger-hover: var(--color-scarlet-base),
var(--color-scarlet-xdark); } :root {
--public-content-desktop-header-height: 80px;
--public-content-mobile-header-height: 64px;
--public-content-container-max-width: 1900px; --block-wrapper-max-width:
750px; --page-wrapper-max-width: 1200px; --app-max-width: 1440px;
--content-max-width: 980px; --content-min-horizontal-spacing:
var(--sp-spacing-800); --sidebar-expanded-width: 260px;
--signin-flows-content-width: 420px; --sidebar-header-height: 113px;
--sidebar-header-compact-height: 210px; --app-header-height:
calc(var(--sp-size-600) + 1px); --app-toolbar-height:
calc(var(--sp-size-400) + calc(var(--sp-spacing-200) \* 2) + 1px);
--toc-desktop-width: 300px; --toc-hover-area-width: 48px; }
body.dragging \[data-hide-on-drag\] { transition: opacity
var(--sp-duration-short-4); opacity: 0; } :root {
--theme-overlay-background: var(--color-background-main); }
.theme-color-dark { --theme-overlay-background:
var(--color-background-main); } .theme-font-variable \[data-nudge-icon\]
{ margin-top: -0.1rem; } .view\_manYY { display: flex; min-width: 0px; }
.base\_qcuoW, .uiBase\_eGiAK { font: var(--sp-typography-ui-base-font);
letter-spacing: var(--sp-typography-ui-base-letter-spacing); }
.uiHeadingLarge\_TNEyV { font:
var(--sp-typography-ui-heading-large-font); letter-spacing:
var(--sp-typography-ui-heading-large-letter-spacing); }
.uiHeadingMedium\_KefKX { font:
var(--sp-typography-ui-heading-medium-font); letter-spacing:
var(--sp-typography-ui-heading-medium-letter-spacing); }
.uiAction\_bZmXH { font: var(--sp-typography-ui-action-font);
letter-spacing: var(--sp-typography-ui-action-letter-spacing); }
.uiSmall\_BjkNA { font: var(--sp-typography-ui-small-font);
letter-spacing: var(--sp-typography-ui-small-letter-spacing); }
.uiStandout\_fNFZw { font: var(--sp-typography-ui-standout-font);
letter-spacing: var(--sp-typography-ui-standout-letter-spacing); }
.uiEmphasize\_WjK8R { font-weight:
var(--sp-typography-ui-emphasize-font-weight); } .selectable\_gP-v9 {
user-select: text; } .contentHeadingLarge\_E6maj { font:
var(--sp-typography-content-heading-large-font); letter-spacing:
var(--sp-typography-content-heading-large-letter-spacing); }
.contentHeadingMedium\_QTXTi { font:
var(--sp-typography-content-heading-medium-font); letter-spacing:
var(--sp-typography-content-heading-medium-letter-spacing); }
.contentHeadingSmall\_PZccC { font:
var(--sp-typography-content-heading-small-font); letter-spacing:
var(--sp-typography-content-heading-small-letter-spacing); }
.contentParagraph\_-qmPj { font:
var(--sp-typography-content-paragraph-font); letter-spacing:
var(--sp-typography-content-paragraph-letter-spacing); }
.contentMono\_rIZdi { font: var(--sp-typography-content-mono-font);
letter-spacing: var(--sp-typography-content-mono-letter-spacing); }
.pageMainTitle\_4t6Ok { font: var(--sp-typography-page-title-font);
letter-spacing: var(--sp-typography-page-title-letter-spacing); }
.pageMainSubtitle\_dLQTm { font:
var(--sp-typography-page-subtitle-font); letter-spacing:
var(--sp-typography-page-subtitle-letter-spacing); } .colorBase\_DJAFR {
color: var(--sp-color-text-base); } .colorMuted\_Nk-dv { color:
var(--sp-color-text-muted); } .colorLight\_I6WtJ { color:
var(--sp-color-text-light); } .link\_-0Vkt\[href\] { text-decoration:
none; color: var(--sp-color-text-interactive); }
.link\_-0Vkt\[href\]:hover, .link\_-0Vkt\[href\]:focus-visible,
.link\_-0Vkt\[href\]:active { text-decoration: underline; } .main\_kxvok
{ background-color: var(--color-background-main); } .mid\_9V4uj {
background-color: var(--color-background-mid); } .muted\_1--Ni {
background-color: var(--sp-color-bg-muted); } .standout\_lsZhY {
background-color: var(--color-background-standout); } .inverted\_u6Zdl {
background-color: var(--color-background-inverted); }
.primaryMain\_g-6J9 { background-color: var(--color-primary-main); }
.primaryMid\_A-hRf { background-color: var(--color-primary-mid); }
.primaryMuted\_DzY9h { background-color: var(--color-primary-muted); }
.primaryHover\_ihg5M:hover { background-color:
var(--color-primary-hover); } .primaryStandout\_1qKhr {
background-color: var(--color-primary-standout); }
.primaryTextInside\_28ROR { background-color:
var(--color-primary-text-inside); } .secondaryMain\_9ufzC {
background-color: var(--color-secondary-main); } .secondaryMuted\_fq-FH
{ background-color: var(--color-secondary-muted); }
.secondaryHover\_rH-Vb:hover { background-color:
var(--color-secondary-hover); } .secondaryStandout\_6mNUa {
background-color: var(--color-secondary-standout); }
.secondaryTextInside\_WRI3S { background-color:
var(--color-secondary-text-inside); } .standoutMain\_2Ccp1 {
background-color: var(--color-standout-main); } .standoutStandout\_4F1t1
{ background-color: var(--color-standout-standout); }
.standoutTextInside\_FadK7 { background-color:
var(--color-standout-text-inside); } .itemHover\_71JI0:hover {
background-color: var(--color-item-hover); } .backdropTransparent\_V93XY
{ background-color: var(--color-backdrop-transparent); }
.backdropBackground\_f7JvU { background-color:
var(--color-backdrop-background); } .backdropBackgroundLight\_zKkF- {
background-color: var(--color-backdrop-background-light); }
.infoMain\_WLOJj { background-color: var(--color-info-main); }
.infoMuted\_URkIL { background-color: var(--color-info-muted); }
.infoHover\_SdLQi:hover { background-color: var(--color-info-hover); }
.infoStandout\_-wKqA { background-color: var(--color-info-standout); }
.infoTextInside\_vz1-a { background-color:
var(--color-info-text-inside); } .successMain\_oeknr { background-color:
var(--color-success-main); } .successMuted\_mdUO3 { background-color:
var(--color-success-muted); } .successStandout\_6QJrP {
background-color: var(--color-success-standout); }
.successTextInside\_QkhHt { background-color:
var(--color-success-text-inside); } .warningMain\_smS-6 {
background-color: var(--color-warning-main); } .warningMuted\_k3aPL {
background-color: var(--color-warning-muted); } .warningStandout\_IVsgc
{ background-color: var(--color-warning-standout); }
.warningTextInside\_9wDmF { background-color:
var(--color-warning-text-inside); } .dangerMain\_Bp0PI {
background-color: var(--color-danger-main); } .dangerMuted\_QeqgX {
background-color: var(--color-danger-muted); } .dangerHover\_2uhbI:hover
{ background-color: var(--color-danger-hover); } .dangerStandout\_NC9TF
{ background-color: var(--color-danger-standout); }
.dangerTextInside\_EgNZK { background-color:
var(--color-danger-text-inside); } .mergeMain\_DZLsS { background-color:
var(--color-merge-main); } .mergeMuted\_0WTMX { background-color:
var(--color-merge-muted); } .mergeHover\_WMNM4:hover { background-color:
var(--color-merge-hover); } .mergeStandout\_iguwY { background-color:
var(--color-merge-standout); } .mergeTextInside\_8hnUv {
background-color: var(--color-merge-text-inside); } .upgradeMain\_OU4ch
{ background-color: var(--color-upgrade-main); } .upgradeMuted\_zOxra {
background-color: var(--color-upgrade-muted); }
.upgradeHover\_AKcIL:hover { background-color:
var(--color-upgrade-hover); } .upgradeStandout\_gj0v6 {
background-color: var(--color-upgrade-standout); }
.upgradeTextInside\_-DzzI { background-color:
var(--color-upgrade-text-inside); } .transparent\_fqMTx {
background-color: transparent; } .weightRegular\_y-Mey { font-weight:
var(--font-weight-regular); } .weightMedium\_ZX-0r { font-weight:
var(--font-weight-medium); } .weightSemibold\_jepPC { font-weight:
var(--font-weight-semibold); } .weightBold\_0byV- { font-weight:
var(--font-weight-bold); } .italic\_Oujte { font-style: italic; }
.underline\_R6S7u { text-decoration: underline; } .strikethrough\_uKiLm
{ text-decoration: line-through; } .uppercase\_nKiGD { text-transform:
uppercase; } .capitalize\_6c66v { text-transform: capitalize; }
.capitalizeFirstLetter\_q2gtW::first-letter { text-transform:
capitalize; } .alignCenter\_RgXft { text-align: center; }
.alignRight\_6C9Wo { text-align: right; } .selectable\_GH2GF { cursor:
text; user-select: text; } .notSelectable\_XCDZC { user-select: none; }
.overflowHidden\_YOfcf { overflow: hidden; } .wrap\_Bf9cm { white-space:
pre-wrap; overflow-wrap: break-word; } .noWrap\_LVWYr { white-space:
nowrap; } .background\_sthSo { background-color:
var(--color-light-mode-sidebar-base); } .theme-color-dark
.background\_sthSo { background-color:
var(--color-dark-mode-grey-scale-dark); }
.theme-color-light.theme-contrast-low .background\_sthSo {
background-color: var(--color-white); } .activeItem\_1MGCd {
background-color: var(--color-light-mode-sidebar-dark); }
.theme-color-dark .activeItem\_1MGCd { background-color:
var(--color-black); } .theme-color-light.theme-contrast-low
.activeItem\_1MGCd { background-color:
var(--color-light-mode-grey-scale-xlight); } .hoverItem\_7-Wd1 {
background-color: rgba(0, 0, 0, 0.1); } .theme-color-dark
.hoverItem\_7-Wd1 { background-color: rgba(0, 0, 0, 0.2); }
.theme-color-light.theme-contrast-low .hoverItem\_7-Wd1 {
background-color: var(--color-light-mode-grey-scale-xxlight); }
.itemBorder\_5278A { border-color: var(--color-light-mode-sidebar-dark);
} .theme-color-dark .itemBorder\_5278A { border-color:
var(--color-dark-mode-grey-scale-xlight); }
.theme-color-light.theme-contrast-low .itemBorder\_5278A { border-color:
var(--color-light-mode-grey-scale-light); } .itemText\_RwWFz { color:
var(--color-dark-mode-text-dark); } .theme-color-dark .itemText\_RwWFz {
color: var(--color-dark-mode-text-dark); }
.theme-color-light.theme-contrast-low .itemText\_RwWFz { color:
var(--color-light-mode-text-light); } .mutedItemText\_I9bjw { color:
var(--color-dark-mode-text-xdark); } .theme-color-dark
.mutedItemText\_I9bjw { color: var(--color-dark-mode-text-xdark); }
.theme-color-light.theme-contrast-low .mutedItemText\_I9bjw { color:
var(--color-light-mode-text-xlight); } .activeItemText\_TeY14 { color:
var(--color-white); } .theme-color-dark .activeItemText\_TeY14 { color:
var(--color-white); } .theme-color-light.theme-contrast-low
.activeItemText\_TeY14 { color: var(--color-black); }
.inputBorder\_oGEtJ { border-color:
var(--color-light-mode-sidebar-dark); } .theme-color-dark
.inputBorder\_oGEtJ { border-color:
var(--color-dark-mode-grey-scale-light); }
.theme-color-light.theme-contrast-low .inputBorder\_oGEtJ {
border-color: var(--color-light-mode-grey-scale-base); }
.standoutText\_tJhEs { color: var(--color-white); } .theme-color-dark
.standoutText\_tJhEs { color: var(--color-white); }
.theme-color-light.theme-contrast-low .standoutText\_tJhEs { color:
var(--color-black); } .main\_ZqJpq, .mainHover\_0hFY8:hover { color:
var(--color-text-main); } .mid\_Vbes2, .midHover\_-TN8i:hover { color:
var(--color-text-mid); } .muted\_Ahh3m, .mutedHover\_8ivdf:hover {
color: var(--color-text-muted); } .standout\_gVGv2,
.standoutHover\_oo1I3:hover { color: var(--color-text-standout); }
.inverted\_1UcNv, .invertedHover\_UyWNb:hover { color:
var(--color-text-inverted); } .primary\_dKCeI,
.primaryHover\_szgyT:hover { color: var(--color-text-primary); }
.primaryMuted\_OC3m2, .primaryMutedHover\_gPwB1:hover { color:
var(--color-text-primary-muted); } .primaryMid\_kgYUZ,
.primaryMidHover\_Xl-cU:hover { color: var(--color-text-primary-mid); }
.primaryStandout\_HwfAX { color: var(--color-text-primary-standout); }
.primaryTextInside\_l5ZwJ { color:
var(--color-text-primary-text-inside); } .secondaryMain\_4R-se { color:
var(--color-secondary-main); } .secondaryMuted\_wzWgW { color:
var(--color-secondary-muted); } .secondaryHover\_IMGbU:hover { color:
var(--color-secondary-hover); } .secondaryStandout\_7vWQ8 { color:
var(--color-secondary-standout); } .secondaryTextInside\_pLNMR { color:
var(--color-secondary-text-inside); } .standoutMain\_ac2pt { color:
var(--color-text-standout-main); } .standoutStandout\_cjJuU { color:
var(--color-standout-standout); } .standoutTextInside\_2-iKN { color:
var(--color-standout-text-inside); } .itemHover\_-ylH4:hover { color:
var(--color-item-hover); } .backdropTransparent\_Moc6- { color:
var(--color-backdrop-transparent); } .backdropBackground\_YFiDa { color:
var(--color-backdrop-background); } .backdropBackgroundLight\_q6NNp {
color: var(--color-backdrop-background-light); } .infoMain\_7psg4 {
color: var(--color-info-main); } .infoMuted\_EZrrH { color:
var(--color-info-muted); } .infoHover\_S69L4:hover { color:
var(--color-info-hover); } .infoStandout\_y-svw { color:
var(--color-info-standout); } .infoTextInside\_nOnT6 { color:
var(--color-info-text-inside); } .successMain\_kWZo- { color:
var(--color-success-main); } .successMuted\_oEcOM { color:
var(--color-success-muted); } .successStandout\_qoM0B { color:
var(--color-success-standout); } .successTextInside\_0gkOV { color:
var(--color-success-text-inside); } .warningMain\_5zFys { color:
var(--color-warning-main); } .warningMuted\_GMMTa { color:
var(--color-warning-muted); } .warningStandout\_vmBPZ { color:
var(--color-warning-standout); } .warningTextInside\_Hwxtq { color:
var(--color-warning-text-inside); } .dangerMain\_w69YD { color:
var(--color-danger-main); } .dangerMuted\_CXRAl { color:
var(--color-danger-muted); } .dangerHover\_h5ZhC:hover { color:
var(--color-danger-hover); } .dangerStandout\_aOay6 { color:
var(--color-danger-standout); } .dangerTextInside\_57sqJ { color:
var(--color-danger-text-inside); } .mergeMain\_VKoJU { color:
var(--color-merge-main); } .mergeMuted\_NuhTj { color:
var(--color-merge-muted); } .mergeHover\_4-mA-:hover { color:
var(--color-merge-hover); } .mergeStandout\_Jmh7g { color:
var(--color-merge-standout); } .mergeTextInside\_UYqCH { color:
var(--color-merge-text-inside); } .upgradeMain\_OuYBG { color:
var(--color-upgrade-main); } .upgradeMuted\_tD8ko { color:
var(--color-upgrade-muted); } .upgradeHover\_3NNnj:hover { color:
var(--color-upgrade-hover); } .upgradeStandout\_aI0FK { color:
var(--color-upgrade-standout); } .upgradeTextInside\_xDBuA { color:
var(--color-upgrade-text-inside); } .verticalAlignMiddle\_PBEii {
vertical-align: middle; } .badge\_VWtFo { align-items: center;
justify-content: center; border-radius: 999px; border-width: 1px; width:
fit-content; text-align: center; vertical-align: middle; gap:
var(--sp-spacing-200); } .numberLabel\_JVVfk { font-variant-numeric:
tabular-nums; } .icon\_G-mdX { width: var(--sp-size-icon-200); height:
var(--sp-size-icon-200); } .badge\_VWtFo.xsmall\_n11tZ { min-width:
var(--sp-size-250); height: var(--sp-size-250); }
.badge\_VWtFo.small\_nhoKY { min-width: var(--sp-size-300); height:
var(--sp-size-300); } .badge\_VWtFo.medium\_cUPFJ { min-width:
var(--sp-size-350); height: var(--sp-size-350); } .xsmall\_n11tZ {
padding-inline: var(--sp-spacing-150); } .small\_nhoKY { padding-inline:
var(--sp-spacing-200); } .medium\_cUPFJ { padding-inline:
var(--sp-spacing-250); } .iconOnly\_Z0bU7 { padding-inline: 0px; }
.primary\_VQM1J { color: var(--sp-color-text-primary); background-color:
var(--sp-color-bg-primary); } .secondary\_kROfE { color:
var(--sp-color-text-secondary); background-color:
var(--sp-color-bg-secondary); } .info\_TqxOr, .beta\_20seX { color:
var(--sp-color-text-info); background-color: var(--sp-color-bg-info); }
.danger\_--LKA { color: var(--sp-color-text-danger); background-color:
var(--sp-color-bg-danger); } .merge\_uRfaJ { color:
var(--sp-color-text-merge); background-color: var(--sp-color-bg-merge);
} .upgrade\_q4XQ0 { color: var(--sp-color-text-upgrade);
background-color: var(--sp-color-bg-upgrade); } .done\_kPYVL { color:
var(--sp-color-text-success); background-color:
var(--sp-color-bg-success); } .alpha\_Kn2s6 { color:
var(--sp-color-text-alpha); background-color: var(--sp-color-bg-alpha);
} .toolbar\_xobeF { gap: var(--sp-spacing-200); flex-direction: row; }
.toolbarVertical\_6JXew { flex-direction: column; } .card\_1mmNB {
position: relative; background: var(--sp-color-bg-card); border: 1px
solid var(--sp-color-border-card); border-radius: var(--sp-radius-500);
box-shadow: var(--sp-shadow-base); padding: var(--sp-spacing-600);
flex-direction: column; gap: var(--sp-spacing-600); transition:
box-shadow var(--sp-duration-short-4) ease-in; } .card\_1mmNB:hover,
.card\_1mmNB:focus-within { box-shadow: var(--sp-shadow-elevated); }
.image\_-ky4t { overflow: hidden; border-radius: var(--sp-radius-500); }
.shortcut\_8i--D { border-radius: var(--sp-radius-200);
background-color: var(--sp-color-bg-keyboard-shortcut-default);
min-width: var(--sp-size-250); height: var(--sp-size-250);
text-transform: uppercase; color: var(--sp-color-text-base); display:
flex; align-items: center; justify-content: center; padding:
var(--sp-spacing-0) var(--sp-spacing-100); border: 1px solid
var(--sp-color-border-keyboard-shortcut-default); } .inverted\_RF8TI {
background-color: var(--sp-color-bg-keyboard-shortcut-inverted); color:
var(--sp-color-text-inverted); border: 1px solid
var(--sp-color-border-keyboard-shortcut-inverted); } .gap\_PR1GX { gap:
var(--sp-spacing-100); } .menuitem\_4EEri { --color-menuitem-icon:
var(--sp-color-icon-menu-default); --color-menuitem-icon-hover:
var(--sp-color-icon-menu-hover); --color-menuitem-icon-active:
var(--sp-color-icon-menu-active); --color-menuitem-text:
var(--sp-color-text-menu-default); --color-menuitem-text-hover:
var(--sp-color-text-menu-hover); --color-menuitem-text-active:
var(--sp-color-text-menu-active); --color-menuitem-text-disabled:
var(--sp-color-text-menu-disabled); --color-menuitem-surface:
var(--sp-color-bg-menu-default); --color-menuitem-surface-hover:
var(--sp-color-bg-menu-hover); --color-menuitem-surface-active:
var(--sp-color-bg-menu-active); } .theme-color-dark .menuitem\_4EEri {
--color-menuitem-text: var(--sp-color-text-menu-dark-default);
--color-menuitem-text-hover: var(--sp-color-text-menu-dark-hover);
--color-menuitem-text-active: var(--sp-color-text-menu-dark-active);
--color-menuitem-text-disabled: var(--sp-color-text-menu-dark-disabled);
--color-menuitem-surface: var(--sp-color-bg-menu-dark-default);
--color-menuitem-surface-hover: var(--sp-color-bg-menu-dark-hover);
--color-menuitem-surface-active: var(--sp-color-bg-menu-dark-active); }
.menuitem\_4EEri { background-color: var(--color-menuitem-surface);
justify-content: flex-start; } .label\_kEhEF { color:
var(--color-menuitem-text); margin: 0px auto 0px 0px; }
.leadingIcon\_JrIhQ { color: var(--color-menuitem-icon-active); }
.trailingIcon\_vT1Vh { color: var(--color-menuitem-icon); }
.menuitem\_4EEri:focus-visible { outline-color:
var(--color-menuitem-text); } .menuitem\_4EEri:hover { background-color:
var(--color-menuitem-surface-hover); } .menuitem\_4EEri:hover
.label\_kEhEF { color: var(--color-menuitem-text-hover); }
.menuitem\_4EEri:hover .trailingIcon\_vT1Vh { color:
var(--color-menuitem-icon-hover); } :is(.active\_wdOfq,
.active\_wdOfq:hover), :is(.active\_wdOfq, .active\_wdOfq:hover)
:is(.label\_kEhEF, .leadingIcon\_JrIhQ, .trailingIcon\_vT1Vh) {
background-color: var(--color-menuitem-surface-active); color:
var(--color-menuitem-text-active); } :is(.disabled\_00v1N,
.disabled\_00v1N:hover), :is(.disabled\_00v1N, .disabled\_00v1N:hover)
:is(.label\_kEhEF, .leadingIcon\_JrIhQ, .trailingIcon\_vT1Vh) { color:
var(--color-menuitem-text-disabled); } .header\_zK-Aj { align-items:
center; gap: var(--sp-spacing-700); } .textColumn\_zZUK4 {
flex-direction: column; flex: 1 1 0%; gap: var(--sp-spacing-600); }
.headingWithBadge\_gB50v { align-items: center; gap:
var(--sp-spacing-200); } .description\_7Qp6k { max-width: 647px; }
.ctas\_okOZX { gap: var(--sp-spacing-400); } .imageWrapper\_l2pTF {
flex-direction: column; flex: 1 1 0%; }
.imageWrapper\_l2pTF.responsiveWrapper\_zXLkQ { display: none; } @media
screen and (min-width: 1025px) {
.imageWrapper\_l2pTF.responsiveWrapper\_zXLkQ { display: flex; } }
.indicator\_eWNyc { width: var(--loading-indicator-size); height:
var(--loading-indicator-size); color: var(--color-primary-mid); }
.panel\_1cs-N { align-items: center; display: flex; flex-direction: row;
justify-content: center; flex: 1 1 0%; min-width: 220px; min-height:
var(--loading-panel-height); padding: var(--loading-panel-padding); }
.icon\_tOUal { width: var(--loading-indicator-size); height:
var(--loading-indicator-size); animation: 1s linear 0s infinite normal
none running LoadingIndicator\_siDKO; } .paused\_BTNiD .icon\_tOUal {
animation-play-state: paused; } .xsmall\_utN-1 {
--loading-indicator-size: var(--sp-size-icon-300);
--loading-panel-height: 0; --loading-panel-padding: 0; } .small\_yM-2T {
--loading-indicator-size: var(--sp-size-icon-400);
--loading-panel-height: 160px; --loading-panel-padding:
var(--sp-spacing-400) var(--sp-spacing-200); } .medium\_hPjBC {
--loading-indicator-size: var(--sp-size-icon-400);
--loading-panel-height: 180px; --loading-panel-padding:
var(--sp-spacing-600) var(--sp-spacing-400); } .large\_cd7CN {
--loading-indicator-size: var(--sp-size-icon-500);
--loading-panel-height: 180px; --loading-panel-padding:
var(--sp-spacing-600) var(--sp-spacing-400); } .xlarge\_E9uA- {
--loading-indicator-size: var(--sp-size-icon-600);
--loading-panel-height: 260px; --loading-panel-padding:
var(--sp-spacing-700) var(--sp-spacing-400); } @keyframes
LoadingIndicator\_siDKO { 0% { transform: rotate(0deg); } 100% {
transform: rotate(360deg); } } .segmentedControl\_rqDuf { background:
var(--sp-color-segmented-control-bg); border-radius:
var(--sp-radius-300); width: fit-content; padding: 3px; gap:
var(--sp-spacing-100); } .segmentedControl\_rqDuf button { padding:
var(--sp-spacing-100) var(--sp-spacing-300); background: none; cursor:
pointer; border: 1px solid transparent; transition: background 200ms
ease-in 0s, border 200ms ease-in 0s; text-transform: capitalize;
position: relative; } .label\_5-gOH { z-index: 2; transition: color
200ms ease-in 0s, transform 200ms ease-in 0s; } .icon\_VJAHb { width:
var(--sp-size-icon-200); height: var(--sp-size-icon-200); }
.disabled\_fAx43 .label\_5-gOH { color:
var(--sp-color-segmented-control-text-disabled); }
.segmentedControl\_rqDuf:not(.disabled\_fAx43) button:hover
.label\_5-gOH { color: var(--sp-color-segmented-control-text-hover); }
.segmentedControl\_rqDuf button:focus { outline: none; } .active\_ghKjr
{ position: absolute; inset: 0px; z-index: 1; border-radius:
var(--sp-radius-300); content: ""; box-shadow:
var(--sp-shadow-segmented-control); background-color:
var(--sp-color-segmented-control-active-segment-bg); border: 1px solid
var(--sp-color-segmented-control-active-segment-border); }
.segmentedControl\_rqDuf.disabled\_fAx43 .active\_ghKjr { cursor: unset;
border: 0px solid transparent; background: var(--sp-color-white); }
.button\_nHYaP { align-items: center; appearance: none; cursor: pointer;
flex: 0 0 auto; flex-direction: row; justify-content: center; outline:
none; user-select: none; text-decoration-line: none; border: 1px solid
var(--sp-color-action-border-default); border-radius:
var(--sp-radius-300); height: var(--button-size); gap:
var(--sp-spacing-200); padding: 0 var(--sp-spacing-300); color:
var(--sp-color-bg-base); transition-duration:
var(--sp-duration-short-4), var(--sp-duration-short-4),
var(--sp-duration-short-4); transition-property: background-color,
border, opacity; } .button\_nHYaP:active { opacity: 0.2; }
.button\_nHYaP:focus { box-shadow: var(--sp-focus-ring); outline:
transparent solid 2px; } .button\_nHYaP:not(:focus-visible) {
box-shadow: none; outline: 0px; } .button\_nHYaP:focus-visible {
box-shadow: var(--sp-focus-ring); outline: transparent solid 2px; }
.primary\_t4-q8 { background-color:
var(--sp-color-action-bg-primary-default); } .primary\_t4-q8:hover {
background-color: var(--sp-color-action-bg-primary-hover); }
.merge\_ctRU6 { background-color:
var(--sp-color-action-bg-merge-default); } .merge\_ctRU6:hover {
background-color: var(--sp-color-action-bg-merge-hover); }
.danger\_r-6u1 { background-color:
var(--sp-color-action-bg-danger-default); } .danger\_r-6u1:hover {
background-color: var(--sp-color-action-bg-danger-hover); }
.upgrade\_hluc0 { background-color:
var(--sp-color-action-bg-upgrade-default); } .upgrade\_hluc0:hover {
background-color: var(--sp-color-action-bg-upgrade-hover); }
.secondary\_N24Yh { background-color:
var(--sp-color-action-bg-secondary-default); border: 1px solid
var(--sp-color-border-base); } .secondary\_N24Yh, .blank\_CprgO,
.nested\_4SkDt { color: var(--sp-color-text-muted); }
.secondary\_N24Yh:hover, .blank\_CprgO:hover, .nested\_4SkDt:hover {
color: var(--sp-color-text-base); } .blank\_CprgO, .nested\_4SkDt {
background-color: transparent; } .secondary\_N24Yh:hover,
.blank\_CprgO:hover { background-color:
var(--sp-color-action-bg-secondary-hover); } .nested\_4SkDt:hover {
background-color: var(--sp-color-action-bg-nested-hover); } .link\_UFR54
{ background-color: transparent; color:
var(--sp-color-button-inline-text-default); padding: unset; display:
inline; text-decoration-line: underline; } .link\_UFR54:hover { color:
var(--sp-color-button-inline-text-hover); } .link\_UFR54:focus { color:
var(--sp-color-button-inline-text-focus); } .pill\_CjxsT {
--shadow-border-300: 0px 0px 0px 3px; --teal-400-transparent-25:
hsl(195deg 53% 55% / 25%); width: fit-content; padding:
var(--sp-spacing-100) var(--sp-spacing-250); border-radius:
var(--sp-radius-pill); color: var(--sp-color-button-pill-text);
background-color: var(--sp-color-bg-secondary); border: 1px solid
transparent; height: auto; text-align: left; align-self: center; }
.pill\_CjxsT:active, .pill\_CjxsT:hover, .pill\_CjxsT:focus-visible {
background-color: var(--sp-color-button-pill-bg-active); border: 1px
solid var(--sp-color-button-pill-border); box-shadow:
var(--shadow-border-300) var(--teal-400-transparent-25); } .small\_vXHK5
{ --button-size: var(--sp-size-button-200); --icon-size:
var(--sp-size-icon-100); } .medium\_CpI3p { --button-size:
var(--sp-size-button-300); --icon-size: var(--sp-size-icon-300); }
.large\_Lqq9j { --button-size: var(--sp-size-button-400); --icon-size:
var(--sp-size-icon-300); } .disabled\_vwRFY, .disabled\_vwRFY:hover,
.disabled\_vwRFY:active .disabled\_vwRFY.active\_h-7Mf {
transition-duration: var(--sp-duration-immediate); opacity: 1;
background-color: var(--sp-color-bg-inactive); background-image: none;
color: var(--sp-color-text-light); cursor: not-allowed; box-shadow:
none; outline: none; } .blank\_CprgO.disabled\_vwRFY,
.nested\_4SkDt.disabled\_vwRFY, .blank\_CprgO.disabled\_vwRFY:hover,
.nested\_4SkDt.disabled\_vwRFY:hover,
.blank\_CprgO.disabled\_vwRFY:active,
.nested\_4SkDt.disabled\_vwRFY:active,
.blank\_CprgO.disabled\_vwRFY.active\_h-7Mf,
.nested\_4SkDt.disabled\_vwRFY.active\_h-7Mf { background-color:
transparent; } .secondary\_N24Yh.disabled\_vwRFY,
.secondary\_N24Yh.disabled\_vwRFY:hover,
.secondary\_N24Yh.disabled\_vwRFY:active,
.secondary\_N24Yh.disabled\_vwRFY.active\_h-7Mf { background-color:
var(--sp-color-action-bg-secondary-default); border: 1px solid
var(--sp-color-action-border-secondary-inactive); }
.pill\_CjxsT.disabled\_vwRFY, .pill\_CjxsT.disabled\_vwRFY:hover,
.pill\_CjxsT.disabled\_vwRFY:active,
.pill\_CjxsT.disabled\_vwRFY.active\_h-7Mf,
.pill\_CjxsT.disabled\_vwRFY:active { transition-duration:
var(--sp-duration-immediate); opacity: 1; background-color:
var(--sp-color-bg-inactive); background-image: none; border-color:
var(--sp-color-action-border-default); color:
var(--sp-color-text-light); cursor: not-allowed; box-shadow: none;
outline: none; } .rounded\_-bdo9 { border-radius:
var(--sp-radius-circle); } .iconOnly\_t2JNX { width: var(--button-size);
height: var(--button-size); padding: 0px; } .icon\_sNfFo { width:
var(--icon-size); height: var(--icon-size); } body.dragging
.hideOnDrag\_zX3VC { transition: opacity var(--sp-duration-short-4);
opacity: 0; } .dropBefore\_MwWdn::before, .dropAfter\_5MuRf::after {
position: absolute; content: ""; background-color:
var(--theme-color-primary-base); animation: var(--sp-duration-short-4)
cubic-bezier(0.65, 0.05, 0.36, 1) dropPop\_ZUQVo; scale: 1; opacity: 1;
} .dropVertical\_-4-Ev::before, .dropVertical\_-4-Ev::after { height:
100%; width: 2px; } .dropHorizontal\_445te::before,
.dropHorizontal\_445te::after { height: 3px; width: 100%; }
.dropVertical\_-4-Ev::before { left: calc(-1 \* var(--sp-spacing-200));
} .dropVertical\_-4-Ev::after { right: calc(-1 \*
var(--sp-spacing-200)); } .dropHorizontal\_445te::before { top: 0px; }
.dropHorizontal\_445te::after { bottom: 0px; } @keyframes dropPop\_ZUQVo
{ 0% { scale: 0.95; opacity: 0; } 50% { opacity: 1; } 100% { scale: 1;
opacity: 1; } } .grabber\_p72PX { cursor: grab; } .grabberIcon\_ebrbU {
color: var(--color-text-muted); } .grabberIcon\_ebrbU:hover { color:
var(--color-primary-base); } .container\_UPXwU { border: none; padding:
0px; position: relative; width: 58px; height: 32px; border-radius: 25px;
cursor: pointer; transition: background-color 0.25s ease-in-out 0s; }
.container\_UPXwU:focus-visible { outline: 2px solid
var(--focusring-color); outline-offset: 1px; }
.darkestParentBackground\_8TVPV { background-color: rgba(255, 255, 255,
0.2); } .darkParentBackground\_ziFwB { background-color: rgba(59, 69,
78, 0.5); } .semiDarkParentBackground\_wgu6B { background-color:
rgba(59, 69, 78, 0.3); } .mediumParentBackground\_BIBSL {
background-color: rgba(59, 69, 78, 0.25); }
.semiLightParentBackground\_Yx9Vw { background-color: rgba(255, 255,
255, 0.55); } .lightParentBackground\_INb4a { background-color:
rgba(255, 255, 255, 0.6); } .lightestParentBackground\_FL4je {
background-color: rgba(59, 69, 78, 0.1); } .toggle\_siihR { border:
none; position: absolute; width: var(--sp-size-icon-600); height:
var(--sp-size-icon-600); border-radius: 50%; transition: left 0.4s
ease-in-out 0s; } .toggleLightMode\_-FLG4 { left: 0px; }
.toggleDarkMode\_uS4t3 { left: calc(100% - var(--sp-size-icon-600) -
var(--sp-spacing-200)); } .toggleSwitch\_NtUzX { box-shadow: rgba(0, 0,
0, 0.1) 0px 1px 2px; } .toggleButton\_ePBfn { color:
var(--color-text-primary); } .toggleIcon\_-vIfn { width: 100%; height:
100%; color: var(--color-text-primary); } .alert\_q3k8d { color:
var(--color-text-main); border-color: transparent; border-radius:
var(--sp-theme-radius-xlarge); background-color:
var(--color-background-muted); } .details\_KGSjO { color:
var(--color-text-mid); } .mainBg\_Wb45V { border: 1px solid
var(--sp-color-border-base); background-color:
var(--color-background-main); } .iconColor\_RR8-I,
.mainBg\_Wb45V.info\_Ulw7q .title\_lR6tH, .info\_Ulw7q .iconColor\_RR8-I
{ color: var(--color-text-primary); } .softInfo\_pPq1w {
background-color: var(--color-primary-xxlight); color:
var(--color-light-mode-text-base); } .softInfo\_pPq1w .details\_KGSjO {
color: var(--color-light-mode-text-light); }
.mainBg\_Wb45V.softInfo\_pPq1w .title\_lR6tH, .softInfo\_pPq1w
.iconColor\_RR8-I { color: var(--color-primary-main); }
.mainBg\_Wb45V.success\_u5BQT .title\_lR6tH, .success\_u5BQT
.iconColor\_RR8-I { color: var(--color-success-main); }
.mainBg\_Wb45V.warning\_zxFFZ .title\_lR6tH, .warning\_zxFFZ
.iconColor\_RR8-I { color: var(--color-warning-main); }
.mainBg\_Wb45V.danger\_VigyZ .title\_lR6tH, .danger\_VigyZ
.iconColor\_RR8-I { color: var(--color-danger-main); }
.mainBg\_Wb45V.merge\_e72vD .title\_lR6tH, .merge\_e72vD
.iconColor\_RR8-I { color: var(--color-merge-main); } .upgrade\_9UtYW {
background-color: var(--sp-color-bg-upgrade); color:
var(--sp-color-text-upgrade); } .upgrade\_9UtYW .details\_KGSjO { color:
var(--sp-color-text-upgrade); } .mainBg\_Wb45V.upgrade\_9UtYW
.title\_lR6tH, .upgrade\_9UtYW .iconColor\_RR8-I { color:
var(--sp-color-icon-upgrade); } .sideSheetBackdrop\_YXb4R { position:
fixed; inset: 0px; backdrop-filter: blur(2px); background-color:
var(--color-backdrop-bg); display: flex; align-items: flex-start;
justify-content: center; z-index: var(--z-index-popover); }
.sideSheetView\_7f5UW { position: absolute; cursor: default; right: 0px;
top: 0px; bottom: 0px; } .blankslate\_SmOSx { flex: 1 1 0%;
flex-direction: row; align-items: center; justify-content: center; }
.alertBlankSlate\_LR5yW { max-width: 400px; } .content\_xiays {
max-width: 500px; flex-direction: column; align-items: center;
justify-content: center; gap: var(--sp-spacing-400); text-align: center;
padding: 0 var(--sp-spacing-600) var(--sp-spacing-600)
var(--sp-spacing-600); } .bordered\_3dmLt { border: 1px solid
var(--sp-color-border-base); } .pressable\_nUrxI { cursor: pointer; }
.withFocusRing\_9WvnS:focus-visible { box-shadow: var(--focusring-color)
0px 0px 0px 1px, var(--focusring-offset-color) 0px 0px 0px 3px, rgba(0,
0, 0, 0) 0px 0px 0px 0px; } .buttonGroup\_-Se5P { --separator-color:
var(--color-background-muted); } .buttonGroup\_-Se5P \>
.buttonGroupItem\_gipgW { position: relative; z-index: 0; }
.buttonGroup\_-Se5P \> .buttonGroupItem\_gipgW:focus-visible { z-index:
1; } .buttonGroup\_-Se5P \> .buttonGroupItem\_gipgW +
.buttonGroupItem\_gipgW { border-left-width: 0px; } .buttonGroup\_-Se5P
\> .buttonGroupItem\_gipgW +
.buttonGroupItem\_gipgW:not(:last-of-type):not(:only-child) {
border-radius: 0px; border-right: 1px solid var(--separator-color); }
.buttonGroup\_-Se5P \>
.buttonGroupItem\_gipgW:first-of-type:not(:only-child) {
border-top-right-radius: 0px; border-bottom-right-radius: 0px;
border-right: 1px solid var(--separator-color); } .buttonGroup\_-Se5P \>
.buttonGroupItem\_gipgW:last-of-type:not(:only-child) {
border-top-left-radius: 0px; border-bottom-left-radius: 0px; }
.buttonGroupItem\_gipgW.primary\_uS3uI { --separator-color:
var(--color-primary-hover); } .buttonGroupItem\_gipgW.merge\_vcRHb {
--separator-color: var(--color-merge-hover); }
.buttonGroupItem\_gipgW.danger\_Rnkqs { --separator-color:
var(--color-danger-hover); } .buttonGroupItem\_gipgW.disabled\_exUb1 {
--separator-color: var(--sp-color-border-base); } .tooltip\_juN0X {
color: var(--color-text-inverted); } .badge\_Zr1xM { border-radius:
var(--sp-theme-radius-medium); height: var(--sp-size-300); background:
var(--color-background-standout); } .icon\_BNB9n { height:
var(--sp-size-icon-400); width: var(--sp-size-icon-400); }
.topBanner\_hUJpL { padding: var(--sp-spacing-600); background-color:
var(--sp-color-bg-side); align-items: center; justify-content:
space-between; } .topBannerTitle\_iQvDX { max-width: 90%; }
.topBannerCloseButton\_1d0O4 { align-self: center; } .background\_Cxsqe
{ background-color: var(--sp-color-bg-base); } .gradientImage\_g0N1P {
position: absolute; top: 50%; left: 50%; transform: translate(-50%,
-50%); width: 100%; height: 100%; object-fit: cover; background:
var(--sp-color-bg-base); z-index: -1; } .wrapper\_rU1eX { width:
var(--signin-flows-content-width); } @media (max-width: 425px) {
.wrapper\_rU1eX { width: 90vw; } } .screenLeftButton\_78aBB { position:
absolute; top: var(--sp-spacing-600); left: var(--sp-spacing-600); }
.children\_c-fln { margin-top: var(--sp-spacing-600); } .subtitle\_3rYzg
{ text-align: center; color: var(--sp-color-text-sign-in-subtitle); }
.screenClose\_fCUXs { position: absolute; top: var(--sp-spacing-600);
right: var(--sp-spacing-600); } @media (max-width: 700px) {
.screenLeftButton\_78aBB { top: var(--sp-spacing-200); left:
var(--sp-spacing-200); } .screenClose\_fCUXs { top:
var(--sp-spacing-200); right: var(--sp-spacing-200); } } :root {
--color-menuitem-text: var(--sp-color-text-menu-default);
--color-menuitem-text-hover: var(--sp-color-text-menu-hover);
--color-menuitem-text-active: var(--sp-color-text-menu-active);
--color-menuitem-surface: var(--sp-color-bg-menu-default);
--color-menuitem-surface-hover: var(--sp-color-bg-menu-hover);
--color-menuitem-surface-active: var(--sp-color-bg-menu-active); }
.theme-color-dark { --color-menuitem-text:
var(--sp-color-text-menu-dark-default); --color-menuitem-text-hover:
var(--sp-color-text-menu-dark-hover); --color-menuitem-text-active:
var(--sp-color-text-menu-dark-active); --color-menuitem-surface:
var(--sp-color-bg-menu-dark-default); --color-menuitem-surface-hover:
var(--sp-color-bg-menu-dark-hover); --color-menuitem-surface-active:
var(--sp-color-bg-menu-dark-active); } .button\_3OpqX { --button-size:
var(--sp-size-button-300); --button-padding: var(--sp-spacing-0);
--button-background: none; align-items: center; appearance: none;
border: 1px solid transparent; border-radius: 4px; color: currentcolor;
cursor: pointer; flex: 0 0 auto; flex-direction: row; gap:
var(--sp-spacing-200); height: var(--button-size); justify-content:
center; outline: none; transition-property: rotate, opacity;
transition-duration: var(--sp-duration-short-2);
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1); padding:
var(--button-padding); background-image: var(--button-background);
user-select: none; } .button\_3OpqX:active { opacity: 0.2;
transition-duration: var(--sp-duration-short-4); } .button\_3OpqX:hover,
.button\_3OpqX:focus-visible { --button-background:
linear-gradient(90deg, var(--button-background-hover)); }
.button\_3OpqX:focus { outline: 2px solid var(--focusring-color);
outline-offset: 1px; } .button\_3OpqX:focus:not(:focus-visible) {
outline: none; } .button\_3OpqX:focus-visible { outline: 2px solid
var(--focusring-color); outline-offset: 1px; } .iconButton\_zzwo7 {
width: var(--button-size); padding: var(--sp-spacing-0); display: flex;
justify-content: center; align-items: center; }
.iconButtonWith2Icons\_N4QG3 { width: calc(var(--button-size) +
var(--icon-size)); padding: var(--sp-spacing-0); } .rounded\_D9hjc {
border-radius: 100%; } .icon\_P3uif { width: var(--icon-size); height:
var(--icon-size); } .xsmall\_ZP889 { --button-size:
var(--sp-size-button-100); --button-padding: 0 var(--sp-spacing-200);
--icon-size: var(--sp-size-icon-300); } .small\_BQ6sr { --button-size:
var(--sp-size-button-200); --button-padding: 0 var(--sp-spacing-200);
--icon-size: var(--sp-size-icon-300); } .medium\_Tbhdr { --button-size:
var(--sp-size-button-300); --button-padding: 0 var(--sp-spacing-300);
--icon-size: var(--sp-size-icon-300); } .large\_Jwmle { --button-size:
var(--sp-size-425); --button-padding: 0 var(--sp-spacing-400);
--icon-size: var(--sp-size-icon-400); } .xlarge\_PwJbx { --button-size:
var(--sp-size-button-500); --button-padding: 0 var(--sp-spacing-400);
--icon-size: var(--sp-size-icon-400); } .default\_fAsWH {
background-color: transparent; color: var(--color-text-mid); }
.default\_fAsWH.active\_gcfxH { color: var(--color-text-primary); }
.default\_fAsWH:hover { color: var(--color-text-primary); }
.default\_fAsWH:focus-visible { outline-color: var(--color-text-main); }
.primary\_c8kAw { background-color: var(--theme-color-primary-base);
color: var(--color-white); } .primary\_c8kAw:hover {
--button-background-hover: var(--color-gradient-primary-hover); }
.primary\_c8kAw:focus-visible { outline-color:
var(--theme-color-primary-base); } .secondary\_AFynQ { background-color:
var(--sp-color-bg-base); color: var(--sp-color-text-muted); border: 1px
solid var(--sp-color-border-base); } .secondary\_AFynQ.active\_gcfxH {
color: var(--sp-color-text-base); } .secondary\_AFynQ:hover {
background-color: var(--sp-color-bg-standout-base); }
.secondary\_AFynQ:focus-visible { outline-color: var(--color-text-main);
} .danger\_VNqSR { background-color: var(--color-scarlet-base); color:
var(--color-white); } .danger\_VNqSR:hover { background-color:
var(--color-scarlet-base); --button-background-hover:
var(--color-gradient-danger-hover); } .danger\_VNqSR:focus-visible {
outline-color: var(--color-scarlet-base); } .muted\_09to- {
border-color: transparent; color: var(--sp-color-text-muted);
background-color: var(--sp-color-bg-base); } .muted\_09to-.active\_gcfxH
{ background-color: var(--color-primary-muted); color:
var(--color-text-primary); } .muted\_09to-:hover { background-color:
var(--sp-color-bg-muted); color: var(--sp-color-text-muted); }
.muted\_09to-:focus-visible { outline-color: var(--sp-color-text-muted);
} .merge\_hWOHE { background-color: var(--color-merge-main); color:
var(--color-merge-text-inside); } .merge\_hWOHE:hover {
background-color: var(--color-merge-standout);
--button-background-hover: var(--color-gradient-merge-hover); }
.merge\_hWOHE:focus-visible { outline-color: var(--color-merge-main); }
.disabled\_jIs9y, .disabled\_jIs9y:hover, .disabled\_jIs9y:active,
.button\_3OpqX.disabled\_jIs9y:active, .disabled\_jIs9y:focus,
.disabled\_jIs9y:focus-visible { opacity: 1; background-color:
var(--color-background-muted); background-image: none; color:
var(--color-text-muted); cursor: not-allowed; box-shadow: none; outline:
none; } .menuitem\_MOc8H { background-color:
var(--color-menuitem-surface); color: var(--color-menuitem-text); }
.menuitem\_MOc8H:hover { background-color:
var(--color-menuitem-surface-hover); color:
var(--color-menuitem-text-hover); } .menuitem\_MOc8H:focus-visible {
outline-color: var(--color-menuitem-text); }
.menuitem\_MOc8H.active\_gcfxH { background-color:
var(--color-menuitem-surface-active); color:
var(--color-menuitem-text-active); } .menuitem\_MOc8H.disabled\_jIs9y,
.menuitem\_MOc8H.disabled\_jIs9y:hover,
.menuitem\_MOc8H.disabled\_jIs9y:active,
.menuitem\_MOc8H.button\_3OpqX.disabled\_jIs9y:active,
.menuitem\_MOc8H.disabled\_jIs9y:focus,
.menuitem\_MOc8H.disabled\_jIs9y:focus-visible { background-color:
var(--color-menuitem-surface); opacity: 0.5; } .toolbar\_hJES6 {
--color-toolbar-surface: var(--sp-color-bg-menu-default); }
.theme-color-dark .toolbar\_hJES6 { --color-toolbar-surface:
var(--sp-color-bg-menu-dark-default); } .toolbar\_hJES6 {
background-color: var(--color-toolbar-surface); box-shadow:
var(--sp-shadow-elevated); padding: var(--sp-spacing-100); }
.toolbar\_hJES6, .toolbar\_hJES6 \> .toolbarGroup\_mD69e { gap:
var(--sp-spacing-100); } .toolbar\_hJES6 \> .toolbarGroup\_mD69e +
.toolbarGroup\_mD69e { padding-left: var(--sp-spacing-100); border-left:
1px solid var(--sp-color-border-base); } :root {
--color-pulsing-primary-inner-0: \#346ddbb5;
--color-pulsing-primary-inner-99: \#91b1f046;
--color-pulsing-primary-outer-0: \#91b1f01f;
--color-pulsing-primary-outer-99: \#ecf3ff00;
--color-pulsing-scarlet-inner-0: \#d33d3db5;
--color-pulsing-scarlet-inner-99: \#ff918f46;
--color-pulsing-scarlet-outer-0: \#ff918f26;
--color-pulsing-scarlet-outer-99: \#ffcccb00; }
.verticalBadgeLine\_5USzO { height: 16px; width: 2px; z-index: -2; }
.horizontalBadgeLine\_hwvoz { position: absolute; top: 10px; height:
2px; background-size: 12px 16px; background-repeat: repeat-x; }
.lineBeforeBadge\_t-h6P { left: -2px; right: calc(50% + 11px); }
.lineAfterBadge\_8Fw-x { left: calc(50% + 11px); right: 0px; }
.horizontalDashedLine\_43Sm4 { background-image: linear-gradient( to
right, transparent 4px, var(--color-background-standout) 4px,
var(--color-background-standout) 4px ); } .verticalDashedLine\_ikjgM {
background-image: repeating-linear-gradient( to bottom, transparent,
transparent 3px, var(--color-background-standout) 3px,
var(--color-background-standout) 8px ); } .solidBlueLine\_4TDi- {
background-image: linear-gradient(var(--color-info-main) 1px,
var(--color-info-main) 1px); } .pulse\_EL6eD { border-radius: 50%; }
.pulse\_EL6eD::after { box-shadow: 0 0 0 3px
var(--color-pulsing-primary-inner-99), 0 0 0 6px
var(--color-pulsing-primary-outer-0); opacity: 1; content: "";
border-radius: 50%; position: absolute; z-index: -1; top: 1px; left:
1px; width: 20px; height: 20px; animation: 2000ms ease-in-out 0s
infinite normal none running pulsingAnimation\_5imGn; } .pulseRed\_35S8S
{ border-radius: 50%; } .pulseRed\_35S8S::after { box-shadow: 0 0 0 3px
var(--color-pulsing-scarlet-inner-99), 0 0 0 6px
var(--color-pulsing-scarlet-outer-0); } @keyframes
pulsingAnimation\_5imGn { 0% { opacity: 1; transform: scale(0.8); } 80%
{ opacity: 1; transform: scale(1.08); } 100% { opacity: 0; transform:
scale(1.08); } } .header\_F9H2h { height: var(--app-header-height); }
.headerWithTabs\_gzlHf { height: calc(var(--app-header-height) +
var(--app-toolbar-height)); } .headerBorder\_pdhTr { border-bottom: 1px
solid var(--color-background-standout); } .heading\_zpkSw { flex: 1 1
0%; } .scrollable\_xQRHB { overflow-y: auto; } :root {
--sidepanel-width: 350px; } .containerWithOpenedSidePanel\_4Aw1U { }
.sidePanel\_8ugtc { border-left: 1px solid var(--sp-color-border-base);
width: var(--sidepanel-width); } .sidePanelPhaseMount\_-i4Bt {
margin-right: 0px; animation-duration: var(--sp-duration-short-4);
animation-name: slideSidePanelIn\_ZmxYm; } .sidePanelPhaseUnmount\_DYB3O
{ margin-right: calc(0px - var(--sidepanel-width)); animation-duration:
var(--sp-duration-short-4); animation-name: slideSidePanelOut\_zQfY7; }
.sidePanelSection\_Kksk- { border-bottom: 1px solid
var(--color-background-standout); } @media (max-width: 700px) {
.containerWithOpenedSidePanel\_4Aw1U { display: none; }
.sidePanel\_8ugtc { margin: 0px; width: auto; position: absolute; inset:
0px; } } @keyframes slideSidePanelIn\_ZmxYm { 0% { margin-right:
calc(0px - var(--sidepanel-width)); } 100% { margin-right: 0px; } }
@keyframes slideSidePanelOut\_zQfY7 { 0% { margin-right: 0px; } 100% {
margin-right: calc(0px - var(--sidepanel-width)); } } .buttonTabs\_ihLP4
{ display: flex; flex-direction: row; align-items: center; }
.buttonTabsItem\_9vRT7 { transition: background-color ease
var(--sp-duration-short-2); align-items: center; }
.buttonTabsItemActive\_PnjM4 { background-color:
var(--color-background-standout); } .buttonTabsItemIcon\_wUvLo { color:
var(--color-text-muted); transition: color ease
var(--sp-duration-short-2); } .buttonTabsItemText\_Oa-uN { color:
var(--color-text-mid); transition: color ease
var(--sp-duration-short-2); } .buttonTabsItem\_9vRT7:hover
.buttonTabsItemText\_Oa-uN, .buttonTabsItemActive\_PnjM4
.buttonTabsItemText\_Oa-uN, .buttonTabsItem\_9vRT7:hover
.buttonTabsItemIcon\_wUvLo, .buttonTabsItemActive\_PnjM4
.buttonTabsItemIcon\_wUvLo { color: var(--color-text-main); }
.buttonTabsSizeMedium\_Cra41 { height: var(--sp-size-button-300);
padding: var(--sp-spacing-100) var(--sp-spacing-100); border-radius:
var(--sp-theme-radius-medium); } .buttonTabsSizeMedium\_Cra41
.buttonTabsItem\_9vRT7 { padding: 0px var(--sp-spacing-200);
border-radius: var(--sp-theme-radius-medium); }
.buttonTabsSizeMedium\_Cra41 .buttonTabsItemIcon\_wUvLo +
.buttonTabsItemText\_Oa-uN { margin-left: var(--sp-spacing-200); }
.buttonTabsItem\_9vRT7.buttonTabsItemDisabled\_XW4rD { cursor: default;
} .buttonTabsItem\_9vRT7.buttonTabsItemDisabled\_XW4rD
.buttonTabsItemText\_Oa-uN { color: var(--color-text-muted); }
.backdrop\_11Iq- { pointer-events: none; } .absoluteFill\_IKtIQ {
position: absolute; inset: 0px; } .popover\_8oy7U { z-index:
var(--z-index-popover); position: fixed; pointer-events: auto; }
.card\_qVFG8 { position: relative; box-shadow: var(--shadow-pop); }
.card\_qVFG8.chromeless\_mWYpC, .card\_qVFG8.tooltip\_AZt4J {
box-shadow: none; } .card\_qVFG8 { background-color:
var(--color-background-main); } .card\_qVFG8.tooltip\_AZt4J {
background-color: var(--color-background-inverted); }
.card\_qVFG8.chromeless\_mWYpC { background-color: transparent; }
.tooltip\_AZt4J { min-width: var(--sp-size-300); min-height:
var(--sp-size-300); max-width: 500px; max-height: 340px; }
.default\_SJvM7 { min-width: var(--sp-size-300); min-height:
var(--sp-size-300); max-width: 200px; max-height: 340px; } .large\_TW0Wd
{ min-width: 340px; min-height: var(--sp-size-300); max-width: 340px;
max-height: 320px; } .xlarge\_KVbe9 { min-width: 500px; min-height:
var(--sp-size-300); max-width: 500px; max-height: 1000px; } .wide\_TmhZ9
{ min-width: var(--sp-size-300); min-height: var(--sp-size-300);
max-width: 1000px; max-height: 1000px; } .menu\_YxBet { min-width:
var(--sp-size-300); min-height: var(--sp-size-300); max-width: 500px;
max-height: 1000px; } .default\_SJvM7 .content\_liNQV, .large\_TW0Wd
.content\_liNQV { overflow: hidden; } .xlarge\_KVbe9 .content\_liNQV {
border-radius: var(--sp-radius-400); } .tabsBorderBottom\_Tp1fX {
border-bottom: 1px solid var(--sp-color-border-base); } .backdrop\_M-DLi
{ position: fixed; inset: 0px; backdrop-filter: blur(2px);
background-color: var(--color-backdrop-bg); display: flex; align-items:
flex-start; justify-content: center; z-index: var(--z-index-popover); }
.searchModal\_Vcy-I { width: 785px; background-color:
var(--color-background-main); box-shadow: var(--shadow-pop); overflow:
hidden; flex-direction: column; max-height: calc(min(640px, 100% - (2 \*
var(--sp-spacing-900)))); margin-top: var(--sp-spacing-900);
margin-right: var(--sp-spacing-600); margin-left: var(--sp-spacing-600);
} @media (max-width: 1024px) { .searchModal\_Vcy-I { width: 75vw;
max-width: 785px; } } @media (max-width: 768px) { .searchModal\_Vcy-I {
position: absolute; margin: 0px auto; top: var(--sp-spacing-600); left:
var(--sp-spacing-400); right: var(--sp-spacing-400); max-height:
min(100vh, 440px); width: auto; max-width: 95vw; } }
.searchModalHeader\_XHNRd { padding-right: var(--sp-spacing-600);
padding-left: var(--sp-spacing-600); flex-direction: row; align-items:
center; } .searchModalHeaderIcon\_Q-OxP { color:
var(--sp-color-primary-400); } .theme-color-dark
.searchModalHeaderIcon\_Q-OxP { color: var(--sp-color-primary-300); }
.searchInput\_TEvvq { border: none; padding-right:
var(--sp-spacing-400); padding-left: var(--sp-spacing-400); padding-top:
var(--sp-spacing-400); padding-bottom: var(--sp-spacing-400);
background-color: var(--color-background-main); }
.searchInput\_TEvvq::placeholder { color: var(--color-text-muted); }
.searchModalBody\_kS0BP { flex: 1 1 0%; overflow-y: auto;
flex-direction: column; } .activityItemDate\_2ZKLX { position: relative;
padding: var(--sp-spacing-400) var(--sp-spacing-400)
var(--sp-spacing-200) var(--sp-spacing-400); } .gradientSvg\_5PSv4 {
position: absolute; inset: 0px; width: 100%; height: 100%; }
.scalingEllipse770x231\_2rzxx { transform-origin: 770px 231px;
animation: 20s linear 0s infinite alternate none running
scale770x231\_22iOt; } @keyframes scale770x231\_22iOt { 0% { transform:
rotate(22.8929deg); } 100% { transform: rotate(60deg); } }
.rotatingEllipse705x383\_0el6u { transform-origin: 705px 383px;
animation: 30s linear 0s infinite alternate none running
rotate705x383\_JsoTC; } @keyframes rotate705x383\_JsoTC { 0% {
transform: rotate(0deg) scale(1); } 100% { transform: rotate(360deg)
scale(1.1); } } .scalingEllipse682x415\_S-Zhq { transform-origin: 682px
415px; animation: 30s linear 0s infinite alternate none running
scale682x415\_BBh9j; } @keyframes scale682x415\_BBh9j { 0% { transform:
scale(0.9) rotate(-14.4727deg); } 100% { transform: scale(1)
rotate(-14.4727deg); } } .innerLeftEdge\_C-DSM { animation: 8s linear 0s
infinite alternate none running fillInnerLeftEdge\_GK3kV; } @keyframes
fillInnerLeftEdge\_GK3kV { 0% { stop-color: rgb(136, 172, 185); } 100% {
stop-color: rgb(176, 199, 237); } } .faintLeftMiddle\_iDsDW { animation:
8s linear 0s infinite alternate none running fillFaintLeftMiddle\_NPtBK;
} @keyframes fillFaintLeftMiddle\_NPtBK { 0% { stop-color: rgb(30, 161,
205); } 100% { stop-color: rgb(247, 108, 142); } } .farLeftEdge\_GYGH5 {
animation: 8s linear 0s infinite alternate none running
fillFarLeftEdge\_9QOPy; } @keyframes fillFarLeftEdge\_9QOPy { 0% {
stop-color: rgb(253, 203, 153); } 100% { stop-color: rgb(253, 165, 153);
} } .dropArea\_dSnnA { position: relative; width: 100%; }
.dropAreaHovered\_C-mWH { position: absolute; inset: 0px; border: 2px
solid var(--color-primary-main); border-radius: 5px; pointer-events:
none; } :root { --transition-active-search-item: background-color 200ms
ease-in, border-color 200ms ease, box-shadow 200ms ease; }
.searchResultItem\_p8cXr { padding: var(--sp-spacing-300)
var(--sp-spacing-400); position: relative; align-items: center; gap:
var(--sp-spacing-200); } .searchResultItemNested\_c68te { padding-left:
var(--sp-spacing-600); } .searchResultItemIconWrapper\_9nhf7 {
align-self: flex-start; margin-top: 1px; } .searchResultIcon\_Mak8U {
width: var(--sp-size-icon-300); height: var(--sp-size-icon-300); color:
var(--color-text-mid); } .searchResultTitle\_oejjj { color:
var(--sp-color-text-base); } .searchResultBody\_C6kw1 {
-webkit-box-orient: vertical; -webkit-line-clamp: 3; overflow: hidden;
display: -webkit-box \!important; } .searchResultWithoutTitle\_bAqon {
padding-left: var(--sp-spacing-650); padding-top: var(--sp-spacing-400);
} .searchResultAction\_4Kmeo { padding-right: var(--sp-spacing-400);
padding-left: var(--sp-spacing-100); margin-top: var(--sp-spacing-300);
position: absolute; top: 0px; right: 0px; background-color:
var(--sp-color-search-result-item-regular-bg-light); } .theme-color-dark
.searchResultAction\_4Kmeo { background-color:
var(--sp-color-search-result-item-regular-bg-dark); }
.searchResultItemStandout\_nxC87 .searchResultAction\_4Kmeo {
background-color: unset; margin-top: var(--sp-spacing-300); }
.searchResultActionIcon\_dkZSk { width: var(--sp-size-icon-300); height:
var(--sp-size-icon-300); margin-top: var(--sp-spacing-100);
margin-right: var(--sp-spacing-200); color: var(--color-text-primary); }
.searchResultActionText\_2EDdS { color: var(--color-text-primary); }
.searchResultItemActive\_Ih3Vm { background-color:
var(--sp-color-search-result-item-regular-bg-light); } .theme-color-dark
.searchResultItemActive\_Ih3Vm { background-color:
var(--sp-color-search-result-item-regular-bg-dark); }
.searchResultItemActive\_Ih3Vm .searchResultIcon\_Mak8U { color:
var(--color-text-main); } .searchResultItemActive\_Ih3Vm
.searchResultTitle\_oejjj { color: var(--color-text-main); }
.searchResultItemActive\_Ih3Vm .searchResultItemStandout\_nxC87
.searchResultAction\_4Kmeo, .searchResultItemActive\_Ih3Vm
.searchResultItemStandout\_nxC87 { background-color:
var(--sp-color-search-ai-cta-bg); }
.searchResultItemActive\_Ih3Vm.searchResultItemStandout\_nxC87
.searchResultIcon\_Mak8U { color: var(--color-text-primary); }
.searchResultItemStandout\_nxC87 { border: 1px solid transparent;
background: var(--sp-color-search-ai-cta-bg); padding:
var(--sp-spacing-300) var(--sp-spacing-400); margin-bottom:
var(--sp-spacing-200); } .theme-color-dark
.searchResultItemStandout\_nxC87 { background:
var(--sp-color-search-ai-cta-bg); }
.searchResultItemStandout\_nxC87.searchResultItemActive\_Ih3Vm { border:
1px solid var(--sp-color-search-ai-cta-border); box-shadow: rgba(145,
176, 240, 0.25) 0px 0px 0px 3px; transition:
var(--transition-active-search-item); } .searchResultItemDisabled\_TTaLk
.searchResultActionText\_2EDdS, .searchResultItemDisabled\_TTaLk
.searchResultActionIcon\_dkZSk, .searchResultItemDisabled\_TTaLk
.searchResultTitle\_oejjj, .searchResultItemDisabled\_TTaLk
.searchResultIcon\_Mak8U { color: var(--color-text-muted); }
.suggestedQueryOrPrompt\_3qSXL { display: flex; padding:
var(--sp-spacing-100) var(--sp-spacing-250); justify-content: center;
gap: var(--sp-spacing-200); background-color:
var(--sp-color-bg-secondary); cursor: pointer; width: fit-content;
margin: var(--sp-spacing-200) 0; border: 1px solid transparent;
transition: var(--transition-active-search-item); }
.suggestedQueryOrPromptActive\_13Zwu { background:
var(--sp-color-button-pill-bg-active); border: 1px solid
var(--sp-color-button-pill-border); box-shadow: rgba(145, 176, 240,
0.25) 0px 0px 0px 3px; } .promptText\_iqPtZ { color:
var(--sp-color-button-pill-text); text-align: center; } .icon\_r3tWb {
width: 15px; height: 15px; flex-shrink: 0; color:
var(--sp-color-search-icons-sparkle-search-color-light); }
.theme-color-dark .icon\_r3tWb { color:
var(--sp-color-search-icons-sparkle-search-color-dark); }
.searchResultItemStandout\_nxC87 .searchResultActionText\_2EDdS,
.searchResultItemStandout\_nxC87 .searchResultActionIcon\_dkZSk { color:
var(--sp-color-search-ai-cta-action-button); }
.searchResultsGroup\_1WUmo { padding: var(--sp-spacing-200);
align-items: flex-end; gap: var(--sp-spacing-200); }
.searchResultsGroupIcon\_GTLB4 { width: var(--sp-spacing-400); height:
var(--sp-spacing-400); color: var(--sp-color-search-group-heading); }
.searchResultsGroupHeading\_R3qNK { color:
var(--sp-color-search-group-heading); } .paletteView\_PnMMq { inset:
0px; flex-direction: row; align-items: flex-start; justify-content:
center; width: 100%; height: 100%; z-index: var(--z-index-popover);
background-color: transparent; } .container\_IzjBN { background-color:
var(--sp-color-bg-base); box-shadow: var(--sp-shadow-base); border:
none; padding-top: ; padding-right: ; padding-left: ; padding-bottom:
var(--sp-spacing-400); flex-direction: column; align-items: stretch;
flex: 1 1 0px; } .header\_BqnpV { flex-direction: row; align-items:
center; margin-bottom: var(--sp-spacing-300); } .icon\_T1Bss {
margin-left: var(--sp-spacing-100); } .action\_c3X06 { flex-direction:
row; margin-top: var(--sp-spacing-400); padding-right:
var(--sp-spacing-300); } .main\_b4cUt { background-color:
var(--sp-color-bg-side); border-right: 1px solid
var(--sp-color-border-base); } .settings\_YAjcS { background-color:
var(--sp-color-bg-side); border-right: 1px solid
var(--sp-color-border-base); min-width: 220px; max-width: 260px; }
.table\_b-JzK { border-radius: var(--sp-radius-500); box-shadow: 0 0 0
1px var(--sp-color-border-table); border-collapse: collapse; width:
100%; } .clickableRow\_zEo8T:hover { background-color:
var(--sp-color-bg-muted); cursor: pointer; } .tr\_6fw2z { display:
table-row; } .cell\_wCymr { display: table-cell; padding:
var(--sp-spacing-400) var(--sp-spacing-200); border-bottom-width: 1px;
border-bottom-style: solid; border-bottom-color:
var(--sp-color-border-table); } .cell\_wCymr:first-child { padding-left:
var(--sp-spacing-600); } .cell\_wCymr:last-child { padding-right:
var(--sp-spacing-600); } tbody \> .tr\_6fw2z:last-child .cell\_wCymr {
border-bottom-color: transparent; } tbody \> .tr\_6fw2z:last-child
.cell\_wCymr:first-child { border-radius: 0 0 0 var(--sp-radius-500); }
tbody \> .tr\_6fw2z:last-child .cell\_wCymr:last-child { border-radius:
0 0 var(--sp-radius-500) 0; } .thead\_6BjgW { display: table-row-group;
} .thContent\_bnDGS { align-items: center; } .th\_sL6X5:first-child {
border-radius: var(--sp-radius-500) 0 0 0; } .th\_sL6X5:last-child {
border-radius: 0 var(--sp-radius-500) 0 0; } .selected\_mrBvU {
background-color: var(--sp-color-primary-100); } .theme-color-dark
.selected\_mrBvU { background-color: var(--sp-color-black); }
.th\_sL6X5.sortable\_KomSu:hover { cursor: pointer; }
.searchAndFiltersWrapper\_QRzT1 { background-color:
var(--sp-color-bg-muted); border-radius: var(--sp-radius-500); padding:
var(--sp-spacing-200); margin-bottom: var(--sp-spacing-400);
flex-direction: row; align-items: center; } .sortDirection\_zAnB6 {
flex-direction: column; padding-left: var(--sp-spacing-100); }
.sortDirection\_zAnB6 .icon\_UeWsU { width: var(--sp-size-icon-xs);
height: var(--sp-size-icon-xs); } .pagination\_RwAUR { margin-top:
var(--sp-spacing-400); } .blockWrapper\_8BIg7 { position: relative;
flex-direction: row; width: 100%; max-width:
var(--block-wrapper-max-width); } .pageWrapper\_BkhZI { position:
relative; flex-direction: column; width: 100%; max-width:
var(--page-wrapper-max-width); padding: 0 calc(var(--sp-spacing-900) +
var(--sp-spacing-400)); } @media screen and (min-width: 1025px) {
.pageWrapper\_BkhZI { padding-right: calc(var(--sp-spacing-900) +
var(--sp-spacing-400)); padding-left: calc( var(--sp-spacing-900) +
var(--sp-spacing-400) - var(--toc-hover-area-width) ); } } @media
(max-width: 700px) { .pageWrapper\_BkhZI { padding: 0
var(--sp-spacing-400); } } .container\_X2Vji { flex: 1 1 0%;
flex-direction: column; justify-content: space-between; padding-top:
var(--sp-spacing-300); padding-bottom: var(--sp-spacing-400); }
.container\_X2Vji.compact\_T96r- { align-items: center; padding-top:
var(--sp-spacing-400); } .alert\_EXE5- { margin-left:
var(--sp-spacing-300); margin-right: var(--sp-spacing-300);
margin-bottom: var(--sp-spacing-400); margin-top: 0px; } .shadow\_5r7pZ
{ box-shadow: 0px -22px 24px var(--sp-color-bg-side); max-width:
var(--sidebar-expanded-width); overflow-x: hidden; z-index: 10; }
.background\_8ngQa { background-color: var(--sp-color-bg-base); }
.full\_UmwQp { width: 100%; } .vwFull\_sedTo { width: 100vw; }
.minFitContent\_2iAe1 { min-width: fit-content; } .maxFull\_8pKCn {
max-width: 100%; } @keyframes popInFrames\_QH4ut { 0% { opacity: 0;
transform: scale(0.9); } 100% { opacity: 1; transform: scale(1); } }
@keyframes popOutFrames\_JPhI- { 0% { opacity: 1; transform: scale(1); }
100% { opacity: 0; transform: scale(0.9); } } @keyframes scaleIn\_mE5J-
{ 0% { transform: scale(0.9); } 100% { transform: scale(1); } }
@keyframes slideInRightFrames\_AgLzp { 0% { transform: translateX(100%);
} 100% { transform: translateX(0px); } } @keyframes
slideOutRightFrames\_Fn9Nl { 0% { transform: translateX(0px); } 100% {
transform: translateX(100%); } } @keyframes slideAndScaleToAppear\_-I6Yc
{ 0% { opacity: 0; transform: translateY(10px) scale(0.95); } 100% {
opacity: 1; transform: translateY(0px) scale(1); } } @keyframes
slideEnter\_EKdSu { 0% { transform: var(--transform); } } @keyframes
slideExit\_e8Xau { 100% { transform: var(--transform); } } @keyframes
fadeEnter\_XgSzY { 0% { opacity: 0; } 100% { opacity: 1; } } @keyframes
fadeExit\_OiUzs { 0% { opacity: 1; } 100% { opacity: 0; } }
.popIn\_dU96k { animation-name: popInFrames\_QH4ut; animation-duration:
var(--sp-duration-short-4); } .popOut\_6-r2c { animation-name:
popOutFrames\_JPhI-; animation-duration: var(--sp-duration-short-4); }
.scaleInBackground\_jJRTJ { animation-name: scaleIn\_mE5J-;
animation-duration: var(--sp-duration-seconds-4); transform-origin:
center center; } .fadeIn\_R1YXo { animation-name: fadeEnter\_XgSzY;
animation-duration: var(--sp-duration-short-2); } .fadeOut\_ZRXwk {
animation-name: fadeExit\_OiUzs; animation-duration:
var(--sp-duration-short-2); } .slideAndScale\_Alex- { animation-name:
slideAndScaleToAppear\_-I6Yc; animation-duration:
var(--sp-duration-long-2); } .slideInRight\_RJYC7 { animation-name:
slideInRightFrames\_AgLzp; animation-duration:
var(--sp-duration-short-4); } .slideOutRight\_SJgAQ { animation-name:
slideOutRightFrames\_Fn9Nl; animation-duration:
var(--sp-duration-short-4); } .fade\_-Cw7M { animation-delay:
var(--delay, 0); animation-duration: var(--duration);
animation-fill-mode: both; } .fade\_-Cw7M.enter\_7BS6A { animation-name:
fadeEnter\_XgSzY; } .fade\_-Cw7M.exit\_B-iyU { animation-name:
fadeExit\_OiUzs; } .slide\_MY4Yb { animation-delay: var(--delay, 0);
animation-duration: var(--duration); animation-fill-mode: both; }
.slide\_MY4Yb.enter\_7BS6A { animation-name: slideEnter\_EKdSu; }
.slide\_MY4Yb.exit\_B-iyU { animation-name: slideExit\_e8Xau; }
.fade\_-Cw7M.slide\_MY4Yb { animation-delay: var(--delay, 0),
var(--delay, 0); animation-duration: var(--duration), var(--duration);
animation-fill-mode: both, both; }
.fade\_-Cw7M.slide\_MY4Yb.enter\_7BS6A { animation-name:
slideEnter\_EKdSu, fadeEnter\_XgSzY; }
.fade\_-Cw7M.slide\_MY4Yb.exit\_B-iyU { animation-name:
slideExit\_e8Xau, fadeExit\_OiUzs; } .enter\_7BS6A { --duration:
var(--sp-duration-short-4); } .exit\_B-iyU { --duration:
var(--sp-duration-short-2); } .distance-s\_Qtpc7 { --distance: 5px; }
.distance-m\_u5hRA { --distance: 10%; } .distance-l\_69IQb { --distance:
100%; } .left\_QXXHA, .top\_eKYz9 { --direction: -1; } .right\_lcku6,
.bottom\_Y-I-A { --direction: 1; } .left\_QXXHA, .right\_lcku6 {
--transform-origin: translateX(0); --transform:
translateX(calc(var(--direction) \* var(--distance))); } .bottom\_Y-I-A,
.top\_eKYz9 { --transform-origin: translateY(0); --transform:
translateY(calc(var(--direction) \* var(--distance))); }
.delay-xs\_voqE- { --delay: var(--sp-duration-short-2); }
.delay-s\_W2tT8 { --delay: var(--sp-duration-short-3); } .delay-m\_jCTo0
{ --delay: var(--sp-duration-short-4); } .delay-l\_-M4OH { --delay:
var(--sp-duration-short-5); } .delay-xl\_5snf9 { --delay:
var(--sp-duration-medium-2); } .duration-xs\_GH4wP { --duration:
var(--sp-duration-short-2); } .duration-s\_iOqVv { --duration:
var(--sp-duration-short-4); } .duration-m\_hb4se { --duration:
var(--sp-duration-medium-3); } .duration-l\_S8iBG { --duration:
var(--sp-duration-long-2); } .duration-xl\_nmWBJ { --duration:
var(--sp-duration-seconds-4); } .debug\_zIQwv { border: 1px solid red; }
.none\_ZA5mK { border: 0px; } .transparent\_gSDBz { border: 1px solid
transparent; } .block\_dQisI { border: 2px dashed
var(--sp-color-border-base); } .dashed\_08ZR5 { border: 1px dashed
var(--sp-color-border-base); } .dotted\_zHY-H { border: 1px dotted
var(--sp-color-border-base); } .double\_eQKA7 { border: 1px double
var(--sp-color-border-base); } .hidden\_flCGr { border: 1px hidden
var(--sp-color-border-base); } .inset\_4CbY- { border: 1px inset
var(--sp-color-border-base); } .groove\_Bsa3w { border: 1px groove
var(--sp-color-border-base); } .none\_ZA5mK { border: 1px none
var(--sp-color-border-base); } .outset\_BSDk7 { border: 1px outset
var(--sp-color-border-base); } .ridge\_LScnO { border: 1px ridge
var(--sp-color-border-base); } .solid\_yJHQz { border: 1px solid
var(--sp-color-border-base); } .widthBase\_f5LI0 { border-width: 1px; }
.widthMedium\_4PAG2 { border-width: 2px; } .widthLarge\_haEb3 {
border-width: 4px; } .colorBase\_cV3li { border-color:
var(--sp-color-border-base); } .radius0\_uAs0T { border-radius:
var(--sp-radius-0); } .radius100\_vadq- { border-radius:
var(--sp-radius-100); } .radius200\_mDC2o { border-radius:
var(--sp-radius-200); } .radius300\_p9SAu { border-radius:
var(--sp-radius-300); } .radius400\_l2UJI { border-radius:
var(--sp-radius-400); } .radius500\_GpM8y { border-radius:
var(--sp-radius-500); } .radiusPill\_CQ2Fp { border-radius:
var(--sp-radius-pill); } .radiusCircle\_y-4nz { border-radius:
var(--sp-radius-circle); } .radiusThemeMedium\_8-j6y { border-radius:
var(--sp-theme-radius-medium); } .radiusThemeLarge\_6Rm3a {
border-radius: var(--sp-theme-radius-large); } .radiusThemeXlarge\_BubY9
{ border-radius: var(--sp-theme-radius-xlarge); } .default\_WyuPL {
cursor: default; } .grab\_I-pJs { cursor: grab; } .grabbing\_MnFhS {
cursor: grabbing; } .notAllowed\_KXHOI { cursor: not-allowed; }
.pointer\_A00Ap { cursor: pointer; } .text\_476SB { cursor: text; }
.flex\_UQ2Vi { display: flex; } .inlineFlex\_ovaxL { display:
inline-flex; } .grid\_2braI { display: grid; } .block\_MOLwy { display:
block; } .inlineBlock\_hWqe0 { display: inline-block; } .inline\_oScT6 {
display: inline; } .table\_T-miO { display: table; } .inlineTable\_bzZuk
{ display: inline-table; } .tableCaption\_p7U1I { display:
table-caption; } .none\_QhsJi { display: none; } .opacity100\_vlg8p {
opacity: 1; } .opacity90\_fIQkG { opacity: 0.9; } .opacity80\_xUEzb {
opacity: 0.8; } .opacity70\_nn1sN { opacity: 0.7; } .opacity60\_v0XvW {
opacity: 0.6; } .opacity50\_lHpyp { opacity: 0.5; } .opacity40\_ab31W {
opacity: 0.4; } .opacity30\_kux-b { opacity: 0.3; } .opacity20\_7B82- {
opacity: 0.2; } .opacity10\_x9Gg1 { opacity: 0.1; } .opacity0\_n4lDR {
opacity: 0; } .flex\_l2cvU { display: flex; } .inline\_qnnmb { display:
inline-flex; } .column\_Pzect { flex-direction: column; } .row\_apb2Z {
flex-direction: row; } .alignItemsCenter\_Si4Gd { align-items: center; }
.alignItemsStart\_EDPjS { align-items: flex-start; }
.alignItemsEnd\_RFywp { align-items: flex-end; }
.alignItemsStretch\_jNBGv { align-items: stretch; }
.alignItemsInitial\_Esfsk { align-items: initial; }
.alignSelfCenter\_M-f7p { align-self: center; }
.alignSelfBaseline\_G7-y7 { align-self: baseline; } .alignSelfEnd\_IwWNi
{ align-self: flex-end; } .justifyCenter\_LjhMA { justify-content:
center; } .justifyStart\_r4IXv { justify-content: flex-start; }
.justifyEnd\_cQQhY { justify-content: flex-end; }
.justifySpaceBetween\_WG1-N { justify-content: space-between; }
.justifySpaceAround\_6b2zN { justify-content: space-around; }
.flex1\_qv0N2 { flex: 1 1 0%; } .flex2\_07Rme { flex: 2 1 0%; }
.flex0Auto\_enRHI { flex: 0 0 auto; } .unset\_f8L1m { flex: unset; }
.shrink0\_RawU5 { flex-shrink: 0; } .shrink1\_lgb4L { flex-shrink: 1; }
.shrink2\_6Hy1V { flex-shrink: 2; } .grow1\_g3-rV { flex-grow: 1; }
.wrap\_zWAll { flex-wrap: wrap; } .nowrap\_HfCr0 { flex-wrap: nowrap; }
.wrapReverse\_eYQdR { flex-wrap: wrap-reverse; } .basisAuto\_ZtlK3 {
flex-basis: auto; } .basis50\_ahu85 { flex-basis: 50%; } .gap100\_6X7no
{ gap: var(--sp-spacing-100); } .gap50\_Pt-Xo { gap:
var(--sp-spacing-50); } .gap200\_KaqoO { gap: var(--sp-spacing-200); }
.gap250\_yl8h6 { gap: var(--sp-spacing-250); } .gap300\_QofqA { gap:
var(--sp-spacing-300); } .gap400\_7Fbq5 { gap: var(--sp-spacing-400); }
.gap450\_5XA9M { gap: var(--sp-spacing-450); } .gap500\_-bbyz { gap:
var(--sp-spacing-500); } .gap600\_DtZK- { gap: var(--sp-spacing-600); }
.gap650\_Rh3ZR { gap: var(--sp-spacing-650); } .gap700\_Fim0p { gap:
var(--sp-spacing-700); } .gap800\_XbHM5 { gap: var(--sp-spacing-800); }
.gap900\_ZAcyz { gap: var(--sp-spacing-900); } .rowGap50\_gjLjr {
row-gap: var(--sp-spacing-50); } .rowGap100\_1Og9l { row-gap:
var(--sp-spacing-100); } .rowGap200\_Qyv31 { row-gap:
var(--sp-spacing-200); } .rowGap250\_i-ydY { row-gap:
var(--sp-spacing-250); } .rowGap300\_fhWWo { row-gap:
var(--sp-spacing-300); } .rowGap400\_ZW76K { row-gap:
var(--sp-spacing-400); } .rowGap500\_wgvVR { row-gap:
var(--sp-spacing-500); } .rowGap600\_JxJOY { row-gap:
var(--sp-spacing-600); } .rowGap650\_C-ojq { row-gap:
var(--sp-spacing-650); } .rowGap700\_sDC4x { row-gap:
var(--sp-spacing-700); } .rowGap800\_KWF2S { row-gap:
var(--sp-spacing-800); } .rowGap900\_qdoqO { row-gap:
var(--sp-spacing-900); } .columnGap50\_EO-NN { column-gap:
var(--sp-spacing-50); } .columnGap100\_WpE2b { column-gap:
var(--sp-spacing-100); } .columnGap200\_7-bJD { column-gap:
var(--sp-spacing-200); } .columnGap250\_O0lpi { column-gap:
var(--sp-spacing-250); } .columnGap300\_SkRjq { column-gap:
var(--sp-spacing-300); } .columnGap400\_iZH-2 { column-gap:
var(--sp-spacing-400); } .columnGap500\_gOjAw { column-gap:
var(--sp-spacing-500); } .columnGap600\_mw4Cs { column-gap:
var(--sp-spacing-600); } .columnGap650\_8Ovwt { column-gap:
var(--sp-spacing-650); } .columnGap700\_Z8t-g { column-gap:
var(--sp-spacing-700); } .columnGap800\_wPXib { column-gap:
var(--sp-spacing-800); } .columnGap900\_LyNBm { column-gap:
var(--sp-spacing-900); } .none\_uZkPa { height: 0px; } .min0\_EC4xn {
min-height: 0px; } .auto\_6IaAq { height: auto; } .full\_cEaBc { height:
100%; } .maxFull\_FdXcP { max-height: 100%; } .minFull\_a5Vk4 {
min-height: 100%; } .vhFull\_I7l5r { height: 100vh; } .fitContent\_7qWKQ
{ height: fit-content; } .minFitContent\_loah- { min-height:
fit-content; } .showTargetOnHover\_FeZFI { opacity: 0; transition:
opacity 0.2s var(--sp-duration-short-2); }
.showAncestorOnHover\_jokyb:hover .showTargetOnHover\_FeZFI { opacity:
1; } .auto\_OLfRt { margin: auto; } .all0\_heREj { margin:
var(--sp-spacing-0); } .all50\_yOevW { margin: var(--sp-spacing-50); }
.all100\_v-7-M { margin: var(--sp-spacing-100); } .all200\_AsWWH {
margin: var(--sp-spacing-200); } .all300\_U7Z1y { margin:
var(--sp-spacing-300); } .all400\_W9PCz { margin: var(--sp-spacing-400);
} .all500\_r-55l { margin: var(--sp-spacing-500); } .all600\_p5XnH {
margin: var(--sp-spacing-600); } .all700\_sn1ge { margin:
var(--sp-spacing-700); } .all750\_lrxpa { margin: var(--sp-spacing-750);
} .all800\_P-4Sb { margin: var(--sp-spacing-800); } .all900\_51uKq {
margin: var(--sp-spacing-900); } .horizontalAuto\_xck7M { margin-left:
auto; margin-right: auto; } .horizontal0\_ceWPC { margin-left:
var(--sp-spacing-0); margin-right: var(--sp-spacing-0); }
.horizontal50\_Bn9Ge { margin-left: var(--sp-spacing-50); margin-right:
var(--sp-spacing-50); } .horizontal100\_3q91o { margin-left:
var(--sp-spacing-100); margin-right: var(--sp-spacing-100); }
.horizontal200\_VmYud { margin-left: var(--sp-spacing-200);
margin-right: var(--sp-spacing-200); } .horizontal300\_QeLUo {
margin-left: var(--sp-spacing-300); margin-right: var(--sp-spacing-300);
} .horizontal400\_Hu-eD { margin-left: var(--sp-spacing-400);
margin-right: var(--sp-spacing-400); } .horizontal500\_19-MU {
margin-left: var(--sp-spacing-500); margin-right: var(--sp-spacing-500);
} .horizontal600\_xce26 { margin-left: var(--sp-spacing-600);
margin-right: var(--sp-spacing-600); } .horizontal700\_RMUt6 {
margin-left: var(--sp-spacing-700); margin-right: var(--sp-spacing-700);
} .horizontal700\_RMUt6 { margin-left: var(--sp-spacing-750);
margin-right: var(--sp-spacing-750); } .horizontal800\_OjgwR {
margin-left: var(--sp-spacing-800); margin-right: var(--sp-spacing-800);
} .horizontal900\_yDjtM { margin-left: var(--sp-spacing-900);
margin-right: var(--sp-spacing-900); } .verticalAuto\_hhBBY {
margin-top: auto; margin-bottom: auto; } .vertical0\_jPhI0 { margin-top:
var(--sp-spacing-0); margin-bottom: var(--sp-spacing-0); }
.vertical50\_j8fF6 { margin-top: var(--sp-spacing-50); margin-bottom:
var(--sp-spacing-50); } .vertical100\_s8aD- { margin-top:
var(--sp-spacing-100); margin-bottom: var(--sp-spacing-100); }
.vertical200\_XHx83 { margin-top: var(--sp-spacing-200); margin-bottom:
var(--sp-spacing-200); } .vertical300\_I0lbh { margin-top:
var(--sp-spacing-300); margin-bottom: var(--sp-spacing-300); }
.vertical400\_qQS0a { margin-top: var(--sp-spacing-400); margin-bottom:
var(--sp-spacing-400); } .vertical500\_uRwie { margin-top:
var(--sp-spacing-500); margin-bottom: var(--sp-spacing-500); }
.vertical600\_HiyZM { margin-top: var(--sp-spacing-600); margin-bottom:
var(--sp-spacing-600); } .vertical700\_9GNcq { margin-top:
var(--sp-spacing-700); margin-bottom: var(--sp-spacing-700); }
.vertical750\_P56E9 { margin-top: var(--sp-spacing-750); margin-bottom:
var(--sp-spacing-750); } .vertical800\_UMdWU { margin-top:
var(--sp-spacing-800); margin-bottom: var(--sp-spacing-800); }
.vertical900\_Szy4W { margin-top: var(--sp-spacing-900); margin-bottom:
var(--sp-spacing-900); } .leftAuto\_PLgvI { margin-left: auto; }
.left0\_PK-SE { margin-left: var(--sp-spacing-0); } .left50\_FQgCQ {
margin-left: var(--sp-spacing-50); } .left100\_W006s { margin-left:
var(--sp-spacing-100); } .left200\_8h1-8 { margin-left:
var(--sp-spacing-200); } .left300\_oNONJ { margin-left:
var(--sp-spacing-300); } .left400\_AmB9S { margin-left:
var(--sp-spacing-400); } .left500\_-RRhw { margin-left:
var(--sp-spacing-500); } .left600\_vgXMR { margin-left:
var(--sp-spacing-600); } .left700\_W-17x { margin-left:
var(--sp-spacing-700); } .left750\_-3sFZ { margin-left:
var(--sp-spacing-750); } .left800\_LJoNK { margin-left:
var(--sp-spacing-800); } .left900\_Ar007 { margin-left:
var(--sp-spacing-900); } .rightAuto\_-K8TC { margin-right: auto; }
.right0\_Ly2JM { margin-right: var(--sp-spacing-0); } .right50\_kTWD8 {
margin-right: var(--sp-spacing-50); } .right100\_uV8pP { margin-right:
var(--sp-spacing-100); } .right200\_TOfaN { margin-right:
var(--sp-spacing-200); } .right300\_eqkIE { margin-right:
var(--sp-spacing-300); } .right400\_RGRnu { margin-right:
var(--sp-spacing-400); } .right500\_sN-eU { margin-right:
var(--sp-spacing-500); } .right600\_55R6Z { margin-right:
var(--sp-spacing-600); } .right700\_6Eoaz { margin-right:
var(--sp-spacing-700); } .right750\_qjIUA { margin-right:
var(--sp-spacing-750); } .right800\_eRlVB { margin-right:
var(--sp-spacing-800); } .right900\_94p1B { margin-right:
var(--sp-spacing-900); } .topAuto\_9pue4 { margin-top: auto; }
.top0\_toxlo { margin-top: var(--sp-spacing-0); } .top50\_-OTuZ {
margin-top: var(--sp-spacing-50); } .top100\_XN841 { margin-top:
var(--sp-spacing-100); } .top200\_Mzy9L { margin-top:
var(--sp-spacing-200); } .top300\_avwC- { margin-top:
var(--sp-spacing-300); } .top400\_8Uwjw { margin-top:
var(--sp-spacing-400); } .top500\_setkd { margin-top:
var(--sp-spacing-500); } .top600\_q8Ng4 { margin-top:
var(--sp-spacing-600); } .top700\_sk0eO { margin-top:
var(--sp-spacing-700); } .top750\_5e-nf { margin-top:
var(--sp-spacing-750); } .top800\_8NAGh { margin-top:
var(--sp-spacing-800); } .top900\_Rwido { margin-top:
var(--sp-spacing-900); } .bottomAuto\_q0Lau { margin-bottom: auto; }
.bottom0\_0MBh5 { margin-bottom: var(--sp-spacing-0); } .bottom50\_nfgm4
{ margin-bottom: var(--sp-spacing-50); } .bottom100\_2ROul {
margin-bottom: var(--sp-spacing-100); } .bottom200\_M0-xO {
margin-bottom: var(--sp-spacing-200); } .bottom300\_qW2XO {
margin-bottom: var(--sp-spacing-300); } .bottom400\_-vdrf {
margin-bottom: var(--sp-spacing-400); } .bottom500\_CZy4K {
margin-bottom: var(--sp-spacing-500); } .bottom600\_DtxRs {
margin-bottom: var(--sp-spacing-600); } .bottom700\_uHnik {
margin-bottom: var(--sp-spacing-700); } .bottom750\_8MddL {
margin-bottom: var(--sp-spacing-750); } .bottom800\_kbXnE {
margin-bottom: var(--sp-spacing-800); } .bottom900\_xAl02 {
margin-bottom: var(--sp-spacing-900); } .hidden\_eEVdx { overflow:
hidden; } .xHidden\_2qAGf { overflow-x: hidden; } .yHidden\_28a-f {
overflow-y: hidden; } .auto\_TqVKU { overflow: auto; } .xAuto\_Pb-16 {
overflow-x: auto; } .yAuto\_00Vvf { overflow-y: auto; }
.textEllipsis\_q-vyL { text-overflow: ellipsis; } .auto\_ADnGh { }
.all0\_hmdqA { padding: var(--sp-spacing-0); } .all50\_nqnch { padding:
var(--sp-spacing-50); } .all100\_n9QCA { padding: var(--sp-spacing-100);
} .all200\_IeoS3 { padding: var(--sp-spacing-200); } .all300\_pgEob {
padding: var(--sp-spacing-300); } .all400\_M6s-z { padding:
var(--sp-spacing-400); } .all450\_uwoM8 { padding:
var(--sp-spacing-450); } .all500\_R1f6Y { padding:
var(--sp-spacing-500); } .all600\_xGE3p { padding:
var(--sp-spacing-600); } .all650\_9fEJF { padding:
var(--sp-spacing-650); } .all700\_ncXi7 { padding:
var(--sp-spacing-700); } .all800\_ox3T5 { padding:
var(--sp-spacing-800); } .all900\_tBSf9 { padding:
var(--sp-spacing-900); } .horizontalAuto\_p-BPd { } .horizontal0\_xP-uM
{ padding-left: var(--sp-spacing-0); padding-right: var(--sp-spacing-0);
} .horizontal50\_GMdSF { padding-left: var(--sp-spacing-50);
padding-right: var(--sp-spacing-50); } .horizontal100\_0WHkK {
padding-left: var(--sp-spacing-100); padding-right:
var(--sp-spacing-100); } .horizontal200\_M-XNg { padding-left:
var(--sp-spacing-200); padding-right: var(--sp-spacing-200); }
.horizontal300\_ChbpU { padding-left: var(--sp-spacing-300);
padding-right: var(--sp-spacing-300); } .horizontal400\_nJfgD {
padding-left: var(--sp-spacing-400); padding-right:
var(--sp-spacing-400); } .horizontal450\_xr8kG { padding-left:
var(--sp-spacing-450); padding-right: var(--sp-spacing-450); }
.horizontal500\_QUs7G { padding-left: var(--sp-spacing-500);
padding-right: var(--sp-spacing-500); } .horizontal600\_N1-mR {
padding-left: var(--sp-spacing-600); padding-right:
var(--sp-spacing-600); } .horizontal650\_-dfWX { padding-left:
var(--sp-spacing-650); padding-right: var(--sp-spacing-650); }
.horizontal700\_ltOel { padding-left: var(--sp-spacing-700);
padding-right: var(--sp-spacing-700); } .horizontal800\_p2SP4 {
padding-left: var(--sp-spacing-800); padding-right:
var(--sp-spacing-800); } .horizontal900\_S-sSP { padding-left:
var(--sp-spacing-900); padding-right: var(--sp-spacing-900); }
.verticalAuto\_T00qN { } .vertical0\_b-kiX { padding-top:
var(--sp-spacing-0); padding-bottom: var(--sp-spacing-0); }
.vertical50\_Jq1x6 { padding-top: var(--sp-spacing-50); padding-bottom:
var(--sp-spacing-50); } .vertical100\_I8YWM { padding-top:
var(--sp-spacing-100); padding-bottom: var(--sp-spacing-100); }
.vertical200\_ZtUoe { padding-top: var(--sp-spacing-200);
padding-bottom: var(--sp-spacing-200); } .vertical300\_12z25 {
padding-top: var(--sp-spacing-300); padding-bottom:
var(--sp-spacing-300); } .vertical400\_IGNdU { padding-top:
var(--sp-spacing-400); padding-bottom: var(--sp-spacing-400); }
.vertical450\_VTKn3 { padding-top: var(--sp-spacing-450);
padding-bottom: var(--sp-spacing-450); } .vertical500\_bx75Z {
padding-top: var(--sp-spacing-500); padding-bottom:
var(--sp-spacing-500); } .vertical600\_HOYe0 { padding-top:
var(--sp-spacing-600); padding-bottom: var(--sp-spacing-600); }
.vertical650\_m4Vle { padding-top: var(--sp-spacing-650);
padding-bottom: var(--sp-spacing-650); } .vertical700\_C1cz5 {
padding-top: var(--sp-spacing-700); padding-bottom:
var(--sp-spacing-700); } .vertical800\_ItVu3 { padding-top:
var(--sp-spacing-800); padding-bottom: var(--sp-spacing-800); }
.vertical900\_hwXRa { padding-top: var(--sp-spacing-900);
padding-bottom: var(--sp-spacing-900); } .leftAuto\_8m-Rl { }
.left0\_9dOO6 { padding-left: var(--sp-spacing-0); } .left50\_WwOEm {
padding-left: var(--sp-spacing-50); } .left100\_eCjKH { padding-left:
var(--sp-spacing-100); } .left200\_DGncv { padding-left:
var(--sp-spacing-200); } .left300\_XiCh1 { padding-left:
var(--sp-spacing-300); } .left400\_hSR-r { padding-left:
var(--sp-spacing-400); } .left450\_KA-bM { padding-left:
var(--sp-spacing-450); } .left500\_rZS9G { padding-left:
var(--sp-spacing-500); } .left600\_YCCWj { padding-left:
var(--sp-spacing-600); } .left650\_TgeDY { padding-left:
var(--sp-spacing-650); } .left700\_8dcoj { padding-left:
var(--sp-spacing-700); } .left800\_4de60 { padding-left:
var(--sp-spacing-800); } .left900\_adpPN { padding-left:
var(--sp-spacing-900); } .rightAuto\_Zk0oe { } .right0\_q954h {
padding-right: var(--sp-spacing-0); } .right50\_qCfwP { padding-right:
var(--sp-spacing-50); } .right100\_1eleB { padding-right:
var(--sp-spacing-100); } .right200\_ZpetL { padding-right:
var(--sp-spacing-200); } .right300\_cEENY { padding-right:
var(--sp-spacing-300); } .right400\_vB-w3 { padding-right:
var(--sp-spacing-400); } .right450\_zy8hD { padding-right:
var(--sp-spacing-450); } .right500\_9m8pG { padding-right:
var(--sp-spacing-500); } .right600\_9uUYF { padding-right:
var(--sp-spacing-600); } .right650\_HPlB6 { padding-right:
var(--sp-spacing-650); } .right700\_MDnT9 { padding-right:
var(--sp-spacing-700); } .right800\_oCCsr { padding-right:
var(--sp-spacing-800); } .right900\_-fmMq { padding-right:
var(--sp-spacing-900); } .topAuto\_mokOy { } .top0\_4AOU1 { padding-top:
var(--sp-spacing-0); } .top50\_pzWAK { padding-top:
var(--sp-spacing-50); } .top100\_QcUCv { padding-top:
var(--sp-spacing-100); } .top200\_FwkHm { padding-top:
var(--sp-spacing-200); } .top300\_9VDS9 { padding-top:
var(--sp-spacing-300); } .top400\_n25lP { padding-top:
var(--sp-spacing-400); } .top450\_qZbVE { padding-top:
var(--sp-spacing-450); } .top500\_GoTWI { padding-top:
var(--sp-spacing-500); } .top600\_sT-91 { padding-top:
var(--sp-spacing-600); } .top650\_ze-G9 { padding-top:
var(--sp-spacing-650); } .top700\_934HS { padding-top:
var(--sp-spacing-700); } .top800\_0PHmt { padding-top:
var(--sp-spacing-800); } .top900\_C9PF1 { padding-top:
var(--sp-spacing-900); } .bottomAuto\_onb3l { } .bottom0\_fXfxl {
padding-bottom: var(--sp-spacing-0); } .bottom50\_a8Itm {
padding-bottom: var(--sp-spacing-50); } .bottom100\_Y7CMU {
padding-bottom: var(--sp-spacing-100); } .bottom200\_HuRwz {
padding-bottom: var(--sp-spacing-200); } .bottom300\_DRVtj {
padding-bottom: var(--sp-spacing-300); } .bottom400\_6eeBF {
padding-bottom: var(--sp-spacing-400); } .bottom450\_ukwwP {
padding-bottom: var(--sp-spacing-450); } .bottom500\_9bXHF {
padding-bottom: var(--sp-spacing-500); } .bottom600\_L2psW {
padding-bottom: var(--sp-spacing-600); } .bottom650\_20zHd {
padding-bottom: var(--sp-spacing-650); } .bottom700\_LCaZO {
padding-bottom: var(--sp-spacing-700); } .bottom800\_zkX-h {
padding-bottom: var(--sp-spacing-800); } .bottom900\_0MvyQ {
padding-bottom: var(--sp-spacing-900); } .inlineAuto\_lHtw9 { }
.inline0\_bcuGT { padding-inline: var(--sp-spacing-0); }
.inline50\_PgIpI { padding-inline: var(--sp-spacing-50); }
.inline100\_gWYq0 { padding-inline: var(--sp-spacing-100); }
.inline200\_I-Arm { padding-inline: var(--sp-spacing-200); }
.inline300\_XOzyV { padding-inline: var(--sp-spacing-300); }
.inline400\_sX-5i { padding-inline: var(--sp-spacing-400); }
.inline450\_3I429 { padding-inline: var(--sp-spacing-450); }
.inline500\_3Cvkm { padding-inline: var(--sp-spacing-500); }
.inline600\_HGLHC { padding-inline: var(--sp-spacing-600); }
.inline650\_R6moi { padding-inline: var(--sp-spacing-650); }
.inline700\_2EKoQ { padding-inline: var(--sp-spacing-700); }
.inline750\_f5zLC { padding-inline: var(--sp-spacing-750); }
.inline800\_8SnL2 { padding-inline: var(--sp-spacing-800); }
.inline900\_VfWic { padding-inline: var(--sp-spacing-900); }
.static\_QhWzo { position: static; } .relative\_kNGzo { position:
relative; } .absolute\_b-of0 { position: absolute; } .fixed\_lQeix {
position: fixed; } .sticky\_vusPp { position: sticky; } .inset0\_bHjhE {
inset: 0px; } .top0\_Op2Lc { top: 0px; } .bottom0\_telwG { top: 0px; }
.left0\_H9ocw { right: 0px; } .right0\_AyUjm { right: 0px; }
.mobileOnlyInsert\_9W9Zl, .tabletOnlyInsert\_aHzf-,
.desktopOnlyInsert\_Lv9zH { display: none; } @media screen {
.screenRemove\_u4sBx { display: none; } .screenInsert\_2fPVC { display:
flex; } .screenInsertBlock\_-lQvQ { display: block; } .screenHide\_RGVMR
{ opacity: 0; } .screenShow\_s6Yea { opacity: 1; } } @media screen and
(min-width: 701px) { .notMobileRemove\_Zj-i0 { display: none; }
.notMobileInsert\_ueRCy { display: flex; } .notMobileInsertBlock\_GC8Gb
{ display: block; } .notMobileHide\_3kYWX { opacity: 0; }
.notMobileShow\_2LMZ3 { opacity: 1; } } @media screen and (max-width:
700px) { .mobileRemove\_6H9PI { display: none; } .mobileInsert\_RUwJY,
.mobileOnlyInsert\_9W9Zl { display: flex; } .mobileInsertBlock\_MLJJe {
display: block; } .mobileHide\_r1sXQ { opacity: 0; } .mobileShow\_TeFrL
{ opacity: 1; } } @media screen and (min-width: 701px) and (max-width:
1024px) { .tabletRemove\_yTFbe { display: none; } .tabletInsert\_bD59n,
.tabletOnlyInsert\_aHzf- { display: flex; } .tabletInsertBlock\_zG-Rk {
display: block; } .tabletHide\_1qAfe { opacity: 0; } .tabletShow\_eoLfU
{ opacity: 1; } } @media screen and (min-width: 1025px) {
.desktopRemove\_7LyCp { display: none; } .desktopInsert\_W1VyR,
.desktopOnlyInsert\_Lv9zH { display: flex; } .desktopInsertBlock\_nvRa4
{ display: block; } .desktopHide\_kzKHk { opacity: 0; }
.desktopShow\_pmscC { opacity: 1; } } .switcher\_NlVFC { display: flex;
flex-wrap: wrap; gap: 1rem; --threshold: 30rem; } .switcher\_NlVFC \> \*
{ flex-grow: 1; flex-basis: calc((var(--threshold) - 100%) \* 999); }
.any100\_1YkjT { width: var(--sp-size-100); height: var(--sp-size-100);
} .any125\_2YxZZ { width: var(--sp-size-125); height:
var(--sp-size-125); } .any150\_3c3T6 { width: var(--sp-size-150);
height: var(--sp-size-150); } .any250\_wHECV { width:
var(--sp-size-250); height: var(--sp-size-250); } .any300\_m-mqc {
width: var(--sp-size-300); height: var(--sp-size-300); } .any350\_obytu
{ width: var(--sp-size-350); height: var(--sp-size-350); }
.any375\_XXkgX { width: var(--sp-size-375); height: var(--sp-size-375);
} .any400\_Y-msF { width: var(--sp-size-400); height:
var(--sp-size-400); } .any450\_Jg7Ds { width: var(--sp-size-450);
height: var(--sp-size-450); } .any500\_0QIcn { width:
var(--sp-size-500); height: var(--sp-size-500); } .any600\_vRtCU {
width: var(--sp-size-600); height: var(--sp-size-600); } .any700\_yC-Zj
{ width: var(--sp-size-700); height: var(--sp-size-700); }
.icon100\_4biex { width: var(--sp-size-icon-100); height:
var(--sp-size-icon-100); } .icon200\_F3Q1y { width:
var(--sp-size-icon-200); height: var(--sp-size-icon-200); }
.icon300\_ohvou { width: var(--sp-size-icon-300); height:
var(--sp-size-icon-300); } .icon400\_NSr2Y { width:
var(--sp-size-icon-400); height: var(--sp-size-icon-400); }
.icon500\_NesPz { width: var(--sp-size-icon-500); height:
var(--sp-size-icon-500); } .icon600\_vICmc { width:
var(--sp-size-icon-600); height: var(--sp-size-icon-600); }
.icon700\_tYQbl { width: var(--sp-size-icon-700); height:
var(--sp-size-icon-700); } .icon800\_PYbjz { width:
var(--sp-size-icon-800); height: var(--sp-size-icon-800); }
.icon900\_vL3V0 { width: var(--sp-size-icon-900); height:
var(--sp-size-icon-900); } .icon925\_D7vtu { width:
var(--sp-size-icon-925); height: var(--sp-size-icon-925); }
.icon950\_NXLgc { width: var(--sp-size-icon-950); height:
var(--sp-size-icon-950); } .minIcon100\_zqLqV { min-width:
var(--sp-size-icon-100); min-height: var(--sp-size-icon-100); }
.minIcon200\_eo3r- { min-width: var(--sp-size-icon-200); min-height:
var(--sp-size-icon-200); } .minIcon300\_rBzHp { min-width:
var(--sp-size-icon-300); min-height: var(--sp-size-icon-300); }
.minIcon400\_GUHfK { min-width: var(--sp-size-icon-400); min-height:
var(--sp-size-icon-400); } .minIcon500\_jjiwH { min-width:
var(--sp-size-icon-500); min-height: var(--sp-size-icon-500); }
.minIcon600\_-w2kJ { min-width: var(--sp-size-icon-600); min-height:
var(--sp-size-icon-600); } .minIcon700\_VvxBh { min-width:
var(--sp-size-icon-700); min-height: var(--sp-size-icon-700); }
.minIcon800\_B3TAd { min-width: var(--sp-size-icon-800); min-height:
var(--sp-size-icon-800); } .minIcon900\_Vok4U { min-width:
var(--sp-size-icon-900); min-height: var(--sp-size-icon-900); }
.minIcon925\_Brjg- { min-width: var(--sp-size-icon-925); min-height:
var(--sp-size-icon-925); } .minIcon950\_KBG4w { min-width:
var(--sp-size-icon-950); min-height: var(--sp-size-icon-950); }
.normal\_SmQV- { white-space: normal; } .nowrap\_Cy8a- { white-space:
nowrap; } .pre\_S09XK { white-space: pre; } .preWrap\_lP9zf {
white-space: pre-wrap; } .preLine\_QAilh { white-space: pre-line; }
.breakSpaces\_4jyL2 { white-space: break-spaces; } .section\_nd724 {
width: 100%; padding-inline: var(--content-min-horizontal-spacing); }
.section\_nd724 \> .content\_ca2hG { width: 100%; max-width:
var(--content-max-width); margin: 0px auto; } .title\_-6NKe {
margin-bottom: var(--sp-spacing-600); } .subtitle\_bpqRl {
margin-bottom: var(--sp-spacing-450); } .emptyState\_9xkN6 { margin:
var(--sp-spacing-900) auto; } @media (max-width: 1440px) { .main\_Ro3g1
{ max-width: calc(var(--content-max-width) + (var(--sp-spacing-800) \*
2)); padding-left: var(--sp-spacing-800); padding-right:
var(--sp-spacing-800); } } .appLayoutHeaderMobile\_xDIPy {
background-color: var(--sp-color-bg-side); height: var(--sp-size-500);
border-bottom: 1px solid var(--sp-color-border-base); } .section\_NEZ49
{ padding-inline: var(--content-min-horizontal-spacing); }
.section\_NEZ49 \> .content\_--XeX { max-width:
var(--content-max-width); } .jumpInSection\_9Vpnl { background-color:
var(--sp-color-bg-base); background-image: var(--bg-image, none);
background-size: cover; background-repeat: no-repeat;
background-position: 25% 85%; } .jumpInMinHeight\_7Emu0 { min-height:
400px; } .roleCustomSection\_m6wnk { grid-template-columns: 2fr 1fr; }
@media (max-width: 1024px) { .roleCustomSection\_m6wnk {
grid-template-columns: 1fr 1fr; } } @media (max-width: 900px) {
.roleCustomSection\_m6wnk { grid-template-columns: 1fr; gap:
var(--sp-spacing-600); } } .cards\_bb1ky { list-style-type: none;
padding-inline-start: 0px; grid-template-columns: 1fr 1fr 1fr;
grid-template-rows: 1fr 1fr; } @media (max-width: 1240px) {
.cards\_bb1ky { grid-template-columns: 1fr 1fr; } } @media (max-width:
900px) { .cards\_bb1ky { grid-template-columns: 1fr; } }
.iconWrapper\_x37cD { display: flex; align-items: center;
justify-content: center; --background-color-inactive:
var(--color-background-mid); --background-color-ok:
var(--color-warning-main); --background-color-good:
var(--color-success-main); --background-color-bad:
var(--color-danger-main); --background-color:
var(--background-color-inactive); background-color:
var(--background-color); color: var(--color-text-mid); width:
var(--rating-size); height: var(--rating-size); border-radius:
var(--rating-size); } .icon\_TnMUQ { width: calc(0.75 \*
var(--rating-size)); height: calc(0.75 \* var(--rating-size)); }
.active\_CllGx.ok\_V1sO-, .interactive\_B2TwX.ok\_V1sO-:focus,
.interactive\_B2TwX.ok\_V1sO-:hover { --background-color:
var(--background-color-ok); } .active\_CllGx.good\_nqe9w,
.interactive\_B2TwX.good\_nqe9w:focus,
.interactive\_B2TwX.good\_nqe9w:hover { --background-color:
var(--background-color-good); } .active\_CllGx.bad\_pz0f3,
.interactive\_B2TwX.bad\_pz0f3:focus,
.interactive\_B2TwX.bad\_pz0f3:hover { --background-color:
var(--background-color-bad); } .active\_CllGx .icon\_TnMUQ,
.interactive\_B2TwX:focus .icon\_TnMUQ, .interactive\_B2TwX:hover
.icon\_TnMUQ { color: var(--color-text-primary-text-inside); }
.commentInput\_hJRXS { flex: 1 1 0%; flex-direction: column;
background-color: var(--color-background-main); }
.commentInputInner\_Z2RUb { flex: 1 1 0%; flex-direction: column;
padding: var(--sp-spacing-200); overflow-y: auto; }
.commentInputToolbar\_-TyX0 { padding-left: var(--sp-spacing-200);
padding-right: var(--sp-spacing-400); padding-bottom:
var(--sp-spacing-200); } .commentInputAvatar\_M7QBN { height:
var(--sp-size-425); } .mentionButton\_9ZOeP { margin-left: calc(0 -
var(--sp-spacing-200)); } .section\_HzSLn { padding-inline:
var(--content-min-horizontal-spacing); max-width:
calc(var(--content-max-width) + var(--content-min-horizontal-spacing) \*
2); } .tabsBorder\_nCe-Y { border-bottom: 1px solid
var(--sp-color-border-base); } .tableBorder\_ukTKc { border: 1px solid
var(--sp-color-border-table); } .contentScoresDataTable\_r-nsH {
max-height: 450px; } .sourceOverview\_C0KJl:hover { cursor: pointer;
background-color: var(--sp-color-bg-muted); border-radius:
var(--sp-radius-300); } .contradiction\_rhEOb { color:
var(--sp-color-icon-danger-default); } .duplicate\_xfq-3 { color:
var(--sp-color-icon-info-default); } .disabledTable\_jfEpE {
pointer-events: none; background-color: var(--sp-color-bg-inactive);
opacity: 0.75; filter: grayscale(1); } .demoTable\_RQsA-:hover { cursor:
not-allowed; } .modal\_tjvIf { width: 880px; padding:
var(--sp-spacing-600) var(--sp-spacing-650) var(--sp-spacing-650); }
.source\_HBTfG { box-shadow: var(--sp-shadow-base); } .reason\_b5GJh {
background-color: var(--sp-color-bg-muted); } @media (min-width: 1024px)
{ html:has(.withStickyHeader\_HQiM-) { scroll-padding-top:
var(--public-content-desktop-header-height); } } @media (max-width:
700px) { html:has(.withStickyHeader\_HQiM-) { scroll-padding-top:
var(--public-content-mobile-header-height); } }
.loadingDelayedText\_WVBF7 { opacity: 0; transition: opacity
var(--sp-duration-long-2) ease; } .loadingDelayedTextVisible\_y5onq {
opacity: 1; } .fullResponse\_adSl0 { gap: var(--sp-spacing-500);
padding: var(--sp-spacing-400) var(--sp-spacing-500)
var(--sp-spacing-500) var(--sp-spacing-500); user-select: text; }
.prompts\_Th3zf { align-items: center; align-content: center; gap:
var(--sp-spacing-400); align-self: stretch; flex-wrap: wrap; }
.answerWrapper\_Uizn- { max-width: 600px; } .queryHeading\_kpHvY {
color: var(--sp-color-text-base); } .theme-color-dark
.queryHeading\_kpHvY { color: var(--sp-color-text-light); }
.prompt\_F-9A- { display: flex; padding: var(--sp-spacing-100) 10px;
justify-content: center; align-items: flex-start; gap:
var(--sp-spacing-200); background-color: var(--sp-color-bg-side);
border: 1px solid var(--sp-color-bg-side); transition: background-color
0.2s ease-in 0s; } .prompt\_F-9A-:focus-visible, .prompt\_F-9A-:hover,
.prompt\_F-9A-:active { background-color:
var(--sp-color-button-pill-bg-active); border: 1px solid
var(--sp-color-button-pill-border); color:
var(--sp-color-button-pill-text); } .icon\_281MC { width: 15px; height:
15px; flex-shrink: 0; color:
var(--sp-color-search-icons-sparkle-search-color-light); }
.theme-color-dark .icon\_281MC { color:
var(--sp-color-search-icons-sparkle-search-color-dark); }
.actions\_FNzrP { display: flex; align-items: center; gap:
var(--sp-spacing-400); padding-bottom: var(--sp-spacing-400);
border-bottom: 1px solid var(--sp-color-search-group-border-light); }
.theme-color-dark .actions\_FNzrP { border-bottom: 1px solid
var(--sp-color-search-group-border-dark); } .relatedQueries\_nIpkZ {
flex-direction: column; border-top: 1px solid var(--grey-200, \#eaebee);
padding-top: var(--sp-spacing-400); } .blankSlateNoAiAnswer\_rz6wQ {
flex-direction: column; justify-content: flex-start; align-items:
flex-start; padding: var(--sp-spacing-200) var(--sp-spacing-600)
var(--sp-spacing-600) var(--sp-spacing-600); gap: var(--sp-spacing-200);
} .buttons\_Q48Sx { gap: var(--sp-spacing-300); margin-top:
var(--sp-spacing-200); } .background\_yPhnp { background-color:
var(--color-green-xxlight); } .commentHalo\_0AauK { --negative-margin:
calc(-1 \* var(--sp-spacing-200)); --fill-negative-margin: calc(100% + 2
\* var(--sp-spacing-200)); background-color: var(--color-primary-muted);
position: absolute; width: var(--fill-negative-margin); height:
var(--fill-negative-margin); pointer-events: none; padding:
var(--sp-spacing-0); margin: var(--negative-margin); opacity: 1;
z-index: -1; transition: opacity var(--sp-duration-short-4);
user-select: none; display: flex; } .container\_4EAMO { overflow-y:
auto; flex: 1 1 auto; height: 0px; } .section\_PNnaW { width: 100%;
padding-inline: var(--content-min-horizontal-spacing); } .section\_PNnaW
\> .content\_7ClDf { width: 100%; max-width: var(--content-max-width);
margin: 0px auto; flex-direction: column; gap: var(--sp-spacing-650); }
.tile\_DN0PL { border: 1px solid var(--sp-color-border-standout); }
.icon\_-jsPK { width: var(--sp-size-icon-200); height:
var(--sp-size-icon-200); } .capturedBy\_9VA12 { gap:
var(--sp-spacing-300); } .title\_xz2to { padding-block:
var(--sp-spacing-200); } tr:hover .optionsButton\_XaqAo {
background-color: var(--sp-color-bg-standout-base); } tr:hover
.optionsButton\_XaqAo:hover { background-color:
var(--sp-color-bg-standout-on-base); color: var(--sp-color-text-base); }
.sidebarHeader\_TUr1b { height: var(--sidebar-header-height);
max-height: var(--sidebar-header-height); display: flex; flex-direction:
column; justify-content: space-between; align-items: stretch; }
.sidebarHeader\_TUr1b.compact\_uFEDc { height:
var(--sidebar-header-compact-height); max-height:
var(--sidebar-header-compact-height); justify-content: center;
align-items: center; gap: var(--sp-spacing-400); } .upperHeader\_Ioy94 {
display: flex; flex-direction: row; align-items: center;
justify-content: space-between; min-width: 0px; width: 100%; }
.compact\_uFEDc .upperHeader\_Ioy94 { flex-direction: column; min-width:
0px; justify-content: center; gap: var(--sp-spacing-400); }
.upperHeaderIcons\_uYmPJ { min-width: 0px; margin-left: 8px; flex-basis:
30%; display: flex; align-items: center; justify-content: flex-end; }
.compact\_uFEDc .upperHeaderIcons\_uYmPJ { margin-left: 0px;
flex-direction: column; gap: 16px; } .organizationTitle\_6dFDd {
margin-left: var(--sp-spacing-200); overflow: hidden; text-overflow:
ellipsis; white-space: nowrap; } .sidebarToggleButton\_zIiCL {
background-color: var(--sp-color-bg-side); color:
var(--sp-color-text-base); width: 32px; height: 32px; display: flex;
align-items: center; justify-content: center; }
.sidebarToggleButton\_zIiCL:hover,
.sidebarToggleButton\_zIiCL:focus-visible,
.sidebarToggleButton\_zIiCL:active { background-color:
var(--sp-color-bg-standout-side); color: var(--sp-color-text-base);
outline: none; border: none; } .compact\_uFEDc
.sidebarToggleButton\_zIiCL { order: -1; }
.searchAskButtonWrapper\_5BCYf { justify-content: flex-start; }
.compact\_uFEDc .searchAskButtonWrapper\_5BCYf { align-items: center; }
.searchAskButtonWrapper\_5BCYf div:last-child { margin-left: auto; }
.searchAskButton\_fcsHm { background-color:
var(--sp-color-bg-standout-side); color: var(--sp-color-text-muted);
padding: var(--sp-spacing-400) var(--sp-spacing-100)
var(--sp-spacing-400) var(--sp-spacing-200); width: 100%;
justify-content: space-around; margin-top: var(--sp-spacing-200);
border: none; } .compact\_uFEDc .searchAskButton\_fcsHm {
background-color: var(--sp-color-bg-side); outline: none; color:
var(--sp-color-text-base); width: var(--sp-size-button-300); height:
var(--sp-size-button-300); display: flex; align-items: center;
justify-content: center; margin-top: 0px; padding: 0px; }
.searchAskButton\_fcsHm:hover, .searchAskButton\_fcsHm:active,
.searchAskButton\_fcsHm:focus { color: var(--sp-color-text-base);
background-color: var(--sp-color-bg-standout-on-side); } .compact\_uFEDc
.searchAskButton\_fcsHm:hover, .compact\_uFEDc
.searchAskButton\_fcsHm:active, .compact\_uFEDc
.searchAskButton\_fcsHm:focus { color: var(--sp-color-text-base);
background-color: var(--sp-color-bg-standout-side); } @media (max-width:
1024px) { .searchAskButton\_fcsHm { justify-content: flex-start; } }
.treeItemButton\_WGUu5 { background-color:
var(--sp-color-bg-standout-side); } .treeItemButton\_WGUu5:hover,
.treeItemButton\_WGUu5:active, .treeItemButton\_WGUu5:focus-visible {
background-color: var(--sp-color-bg-standout-on-side); }
.addContentButton\_5AGYJ { background-color: var(--sp-color-bg-side); }
.addContentButton\_5AGYJ:hover, .addContentButton\_5AGYJ:active,
.addContentButton\_5AGYJ:focus-visible { background-color:
var(--sp-color-bg-standout-side); } .addSnippetButton\_pCaPG {
background-color: transparent; } .addSnippetButton\_pCaPG:hover,
.addSnippetButton\_pCaPG:active, .addSnippetButton\_pCaPG:focus-visible
{ background-color: var(--sp-color-bg-standout-on-side); }
.publicContainer\_11UZS { flex-direction: row; width: 100%; max-width:
var(--public-content-container-max-width); margin: 0px auto; }
.aiSearchSpinner\_cTH2Q { animation: 1.8s cubic-bezier(0.59, 0.27, 0.33,
0.86) 0s infinite normal none running aiSearchSpinnerAnim\_75OX-; color:
var(--color-text-muted); } .aiSearchSpinnerIcon\_MOqIL { } @keyframes
aiSearchSpinnerAnim\_75OX- { 0% { transform: rotate(0deg) scale(1);
opacity: 0.4; } 50% { transform: rotate(180deg) scale(1.6); opacity: 1;
} 100% { transform: rotate(360deg) scale(1); opacity: 0.4; } }
.aiAnswerFooter\_pxFSA { border-top: 1px solid
var(--sp-color-border-base); } .sourcesHeadingButton\_YdnnI { color:
var(--sp-color-text-muted); padding: 0px; } .tableContainer\_lZe2Q {
border: 1px solid var(--sp-color-border-table); } .keywordCell\_LNimk {
--meterSize: 6px; --meterBorder: 2px; --percent-full: 0%; align-items:
center; } .meterContainer\_A3X3f { max-width: 500px; gap:
var(--meterSize); max-height: calc(var(--meterSize) \* 3); align-items:
initial; } .meter\_sAAX1 { max-height: var(--meterSize); width:
var(--percent-full); height: var(--meterSize); border-radius:
var(--meterBorder); } .meter\_sAAX1 svg { height: 100%; width: 100%;
border-radius: var(--meterBorder); } .searchesMeter\_SwJEA svg { color:
var(--sp-insights-meters-searches); } .hitsMeter\_-i37u svg { color:
var(--sp-insights-meters-hits); } .queryContainer\_nQd60 { width: 160px;
} .query\_kMTRv { max-width: 100%; overflow: hidden; white-space:
nowrap; text-overflow: ellipsis; } .opacityFadeIn\_e3HUz { opacity: 1;
transition: opacity var(--sp-duration-medium-3); }
.opacityFadeOut\_YF-cJ { opacity: 0; transition: opacity
var(--sp-duration-short-4); } @media screen and (max-width: 1370px) {
.container\_8KTw5 { display: none; } } :root { --login-narrow-max-width:
304px; } .narrowLoginContainer\_Ksh2Q { width:
var(--login-narrow-max-width); } .socialLogins\_Oui-Q { gap:
var(--sp-spacing-600); } .switchLoginSignupCTA\_kbdNQ { color:
var(--sp-color-button-inline-text-default); } .cardWrapper\_6Hr4m {
position: absolute; top: 0px; left: 0px; white-space: nowrap; }
.container\_4xc2q { display: inline-flex; } .hitArea\_oHT6S { position:
absolute; background-color: transparent; justify-content: flex-start;
user-select: none; overflow: hidden; top: 0px; height: 100%;
padding-left: var(--sp-spacing-100); } .buttonWrapper\_3J38G { position:
relative; gap: var(--sp-spacing-100); width: 100%; opacity: 0;
translate: 0px; will-change: transform, opacity; }
.hideTransition\_k0Mlc { transition: opacity var(--sp-duration-short-4)
ease-out; } .conflicts\_NH0YT { --hoz-size: 86px; --neg-hoz-size:
calc(-1 \* var(--hoz-size)); } .toolbarConnector\_rKw9X { position:
relative; } .toolbarConnector\_rKw9X::before { display: block; position:
absolute; content: ""; background-color: var(--sp-color-border-base);
height: 2px; width: var(--hoz-size); left: var(--neg-hoz-size); top:
50%; pointer-events: none; } .toolbarConnector\_rKw9X::after { display:
block; position: absolute; content: ""; background-color:
var(--sp-color-border-base); width: 2px; height: calc(12px +
var(--sp-spacing-200)); left: var(--neg-hoz-size); pointer-events: none;
} .conflictBase\_F-gkn.toolbarConnector\_rKw9X::after { bottom: calc(-1
\* var(--sp-spacing-200)); }
.conflictHead\_qDgkT.toolbarConnector\_rKw9X::after { height: calc(14px
+ var(--sp-spacing-200)); top: calc(-1 \* var(--sp-spacing-200)); }
.verticalConnector\_6gQQw { position: absolute; display: block;
translate: -50%; left: calc(50% - var(--hoz-size)); width: 100%; height:
100%; max-width: var(--block-wrapper-max-width); pointer-events: none; }
.verticalConnector\_6gQQw::before { display: block; content: ""; width:
2px; height: 100%; background-color: var(--sp-color-border-base); left:
var(--neg-hoz-size); pointer-events: none; } .conflictBadge\_rJISv {
position: absolute; left: -12px; top: -12px; }
.highlightContainer\_T2jbl { position: relative; } .highlight\_r-5El {
position: absolute; inset: 0px; opacity: 0.5; pointer-events: none; }
.highlight\_r-5El.main\_K0HuP { background-color:
var(--color-merge-muted); } .highlight\_r-5El.current\_-GeKS {
background-color: var(--color-primary-muted); } .body\_WFMnw {
max-width: 456px; } .stepButtonGroup\_l1c9k { max-width: 504px; }
.stepButton\_tVlIt { max-width: 245px; } .formPanel\_2XVsB {
background-color: var(--sp-color-bg-muted); } .cname\_W9J6h { height:
36px; } .info\_SjDpe { color: var(--sp-color-primary-500); }
.success\_LI26O { color: var(--sp-color-text-success); } .danger\_x9c-b
{ color: var(--sp-color-text-danger); } .footerBorder\_UEHGo {
border-top: 1px solid var(--color-background-standout); }
.integrationCards\_5DfZc { flex-flow: column nowrap; gap:
var(--sp-spacing-600); } @media screen and (min-width: 701px) {
.integrationCards\_5DfZc { flex-flow: row wrap; gap:
var(--sp-spacing-700); } } @supports (grid-template-columns: subgrid) {
.integrationCards\_5DfZc { display: grid; grid-template-columns: 1fr; }
@media screen and (min-width: 701px) { .integrationCards\_5DfZc {
grid-template-columns: repeat(auto-fill, minmax(230px, 1fr)); } } }
.integrationCard\_UGVJy { min-width: 230px; max-width: 330px; flex: 1 1
calc(33% - 40px); height: fit-content; box-shadow:
var(--sp-shadow-base); } .integrationCard\_UGVJy \> .content\_Q9zbp {
flex-direction: column; gap: var(--sp-spacing-600); }
.integrationCard\_UGVJy .body\_QM88U, .integrationCard\_UGVJy
.footer\_s3DxX, .integrationCard\_UGVJy .header\_APV0p { flex-direction:
column; gap: var(--sp-spacing-200); } .integrationCard\_UGVJy
.dataBody\_Mglrq { gap: var(--sp-spacing-400); } .integrationCard\_UGVJy
.image\_4-AEH { overflow: hidden; width: 100%; } .image\_4-AEH \> img {
background: linear-gradient(to bottom, transparent 8%,
var(--sp-color-bg-card) 8%) 2px 2px / 8px 8px repeat, linear-gradient(to
right, lightgrey 8%, var(--sp-color-bg-card) 8%) 2px 2px / 8px 8px
repeat; width: 100%; height: auto; } .image\_4-AEH \> svg { background:
var(--sp-color-bg-card); width: 100%; height: auto; }
.integrationCard\_UGVJy .dataItem\_-QEdK { flex-direction: row; gap:
var(--sp-spacing-200); } .integrationCard\_UGVJy .icon\_YrNzh { width:
var(--sp-size-icon-200); height: var(--sp-size-icon-200); margin-top:
-2px; color: var(--icon-color, currentcolor); } .integrationCard\_UGVJy
.titleWithSub\_-POgw { flex-direction: column; gap:
var(--sp-spacing-100); } .integrationCard\_UGVJy.pending\_cmXq2
.icon\_YrNzh { color: var(--sp-color-primary-300); }
.integrationCard\_UGVJy.success\_8Ad62 .icon\_YrNzh { background:
var(--sp-color-bg-success); color: var(--sp-color-text-success);
border-radius: var(--sp-radius-circle); outline-offset: -1px; outline:
var(--sp-spacing-100) solid var(--sp-color-bg-success); }
.integrationCard\_UGVJy.disabled\_iF-dR::before { display: none; }
@supports (grid-template-columns: subgrid) { .integrationCard\_UGVJy {
display: grid; } } .header\_APV0p { position: relative; } .badge\_cK-kZ
{ position: absolute; top: var(--sp-spacing-250); right:
var(--sp-spacing-250); } .title\_QlXWG { flex-direction: row; gap:
var(--sp-spacing-200); align-items: center; } .title\_QlXWG .icon\_YrNzh
{ width: var(--sp-size-icon-200); height: var(--sp-size-icon-200);
margin-top: -2px; color: var(--icon-color, currentcolor); } @media
screen and (min-width: 1025px) { .details\_ljTjj { min-height: calc(
var(--sp-typography-ui-small-line-height) \*
var(--sp-typography-ui-small-font-size) \* 3 ); } } .halo\_oiCij {
--negative-margin: calc(-1 \* var(--sp-spacing-200));
--fill-negative-margin: calc(100% + 2 \* var(--sp-spacing-200));
background-color: var(--color-primary-muted); position: absolute; width:
var(--fill-negative-margin); height: var(--fill-negative-margin);
pointer-events: none; padding: var(--sp-spacing-0); margin:
var(--negative-margin); opacity: 0; z-index: -1; transition: opacity
var(--sp-duration-short-4); user-select: none; display: none; }
.halo\_oiCij.ready\_81z1f { display: flex; opacity: 0; will-change:
opacity; } .halo\_oiCij.show\_byjur { opacity: 1; } .divider\_osV0o {
width: 100%; height: 1px; border: none; background-color:
var(--sp-color-border-base); padding: 0px; margin: 0px; }
.modalBackdrop\_YIGNh { position: absolute; inset: 0px;
background-color: var(--color-backdrop-background); } .modal\_L4RAz {
position: absolute; top: var(--sp-spacing-600); bottom:
var(--sp-spacing-600); right: var(--sp-spacing-600); left:
var(--sp-spacing-600); background-color: var(--color-background-main);
overflow: hidden; } .modalBody\_-1ixR { position: absolute; inset: 0px;
} .generateFooter\_fzJyh { position: absolute; bottom:
var(--sp-spacing-200); left: 280px; right: 280px; z-index: 10; }
.tooltip\_8qsEs { background-color: var(--color-background-mid);
flex-direction: row; padding: var(--sp-spacing-100); }
.brokenImage\_F5FWc { padding: var(--sp-spacing-100); background-color:
var(--color-background-muted); } .pageCoverBleedFull\_eqtqd { width:
100vw; margin-left: calc(50% - 50vw); } .tocButton\_Rr2pQ { opacity: 0;
transition: opacity var(--sp-duration-short-4) ease-out; position:
sticky; top: var(--sp-spacing-200); } .tocHoverArea\_ZNa-w { display:
none; height: 100%; width: var(--toc-hover-area-width); padding-top:
var(--sp-spacing-200); justify-content: center; }
.tocHoverArea\_ZNa-w:hover .tocButton\_Rr2pQ { opacity: 1; } @media
screen and (min-width: 1025px) { .tocHoverArea\_ZNa-w { display: flex; }
} .notificationsButton\_TGSVx { background-color:
var(--sp-color-bg-side); color: var(--sp-color-text-base); display:
flex; align-items: center; justify-content: center; }
.notificationsButton\_TGSVx:hover, .notificationsButton\_TGSVx:focus,
.notificationsButton\_TGSVx:active { background-color:
var(--sp-color-bg-standout-side); color: var(--sp-color-text-base);
outline: none; border: none; } .popover\_41P2r { max-height: 300px;
position: relative; white-space: pre-wrap; overflow-wrap: break-word; }
.toolbar\_EEKEO { position: absolute; top: var(--sp-spacing-400); right:
var(--sp-spacing-400); } .annotatedText\_DZvL5 { text-decoration:
underline dotted var(--color-text-muted) 2px; user-select: none; }
.annotatedText\_DZvL5:hover, .active\_mnp9Q { border-radius:
var(--sp-theme-radius-medium); padding: 0 var(--sp-spacing-100);
background-color: rgba(35, 131, 226, 0.14); margin: 0 calc(-1 \*
var(--sp-spacing-100)); z-index: -1; cursor: pointer; } .quote\_5I59h {
color: var(--color-text-mid); padding-left: var(--sp-spacing-400);
border-left: var(--sp-spacing-100) solid var(--sp-color-border-base); }
.hint\_rnF2j { background-color: var(--color-background-muted);
padding-right: var(--sp-spacing-600); border-left: var(--sp-spacing-100)
solid var(--hint-color); border-radius: var(--sp-radius-300); }
.iconWrapper\_NJPs7 { width: calc(var(--sp-spacing-700) +
var(--sp-spacing-200)); color: var(--hint-color); z-index:
var(--z-index-promote); align-self: start; } .icon\_abDxV { --icon-size:
var(--sp-size-icon-500); width: var(--icon-size); height:
var(--icon-size); } .info\_-xeCE { --hint-color:
var(--color-primary-base); } .warning\_5BM-F { --hint-color:
var(--color-orange-base); } .danger\_UUfHb { --hint-color:
var(--color-scarlet-base); } .success\_3o6RV { --hint-color:
var(--color-green-base); } .placeholder\_YMCFu { position: absolute;
width: 100%; pointer-events: none; } .instructions\_1Qp3O { display:
inline-block; white-space: nowrap; overflow: hidden; text-overflow:
ellipsis; margin-right: var(--sp-spacing-200); } .shortcuts\_WxjGT {
pointer-events: all; flex-wrap: wrap; } .progressContainer\_Sj3CE {
width: 30px; height: 30px; z-index: -1; left: -3px; top: -3px; }
.indicatorContainer\_5ILWs { width: 9px; height: 9px; left: 15px; }
.indicatorDot\_xDC17 { width: 6px; height: 6px; } .footer\_SvIjE {
border-top: 1px solid var(--sp-color-border-base); } .header\_x3-rd {
border-bottom: 1px solid var(--sp-color-border-base); }
.modalFooterButtonsWrapper\_80kwB { width: 100%; max-width: 250px;
justify-content: center; align-self: center; } .definitionWrapper\_0vx5U
{ position: relative; } .grabberWrapper\_WLh-V { position: absolute;
left: calc(-1 \* var(--sp-spacing-600)); opacity: 0; transition: opacity
var(--sp-duration-short-4) ease; } .definitionWrapper\_0vx5U:hover
.grabberWrapper\_WLh-V { opacity: 1; } .targetCard\_YoeqR { position:
relative; } .controlButtons\_l18tz { width: 100%; position: absolute;
top: var(--sp-spacing-200); padding: 0 var(--sp-spacing-200); opacity:
0; transition: opacity 0.2s ease-in-out 0s; } .targetCard\_YoeqR:hover
.controlButtons\_l18tz { opacity: 1; } .searchButton\_X3i3J {
background-color: var(--sp-color-bg-standout-side); color:
var(--sp-color-text-muted); padding: var(--sp-spacing-400)
var(--sp-spacing-100) var(--sp-spacing-400) var(--sp-spacing-200);
width: 100%; border: none; } .searchButton\_X3i3J:hover,
.searchButton\_X3i3J:active, .searchButton\_X3i3J:focus { color:
var(--sp-color-text-light); } .popover\_eLmJg { width: 400px; }
.container\_JxrHs { padding-top: calc(var(--sp-spacing-600) +
var(--sp-spacing-200)); } .pageHeaderContainer\_f8iPF { padding-top:
calc(var(--sp-spacing-600) + var(--sp-spacing-200)); }
.pageControls\_65PGe { position: absolute; top: 0px; }
.hiddenIcon\_MYEiw { color: var(--color-text-muted); }
.revealOnHover\_QTUA- { opacity: 0; transition: opacity
var(--sp-duration-short-4) ease; } .pageHeaderContainer\_f8iPF:hover
.revealOnHover\_QTUA- { opacity: 1; } .exitHint\_xASL- { position:
absolute; bottom: 0px; right: 0px; display: inline-flex; padding:
var(--sp-spacing-100); gap: 0px; white-space: pre-wrap; animation:
var(--sp-duration-short-4) show\_HIlHf forwards; } @keyframes
show\_HIlHf { 0% { opacity: 0; } } .header\_hoasR { border-bottom: 1px
solid var(--sp-color-border-base); } .orgCard\_o9I-u { background-color:
var(--sp-color-join-organizations-card-default); flex-direction: row;
justify-content: space-between; } .organizationIcon\_jht0- { filter:
drop-shadow(var(--sp-shadow-organization-creation-logo-first-layer))
drop-shadow(var(--sp-shadow-organization-creation-logo-second-layer)); }
.scrollableOrganizations\_L0vv- { max-height: 380px; }
.tocDesktopWrapper\_WWBt8 { background-color: var(--sp-color-bg-base);
border-right: 1px solid var(--sp-color-border-base); }
.tocDesktop\_oqOIi { width: var(--toc-desktop-width); }
.tocMenuItem\_k5u8k { text-decoration: none; user-select: none;
touch-action: manipulation; color: var(--sp-color-text-muted);
border-radius: var(--sp-radius-300) 0 0 var(--sp-radius-300); }
.tocMotionWrapper\_AUhf4 { display: none; } @media screen and
(min-width: 1025px) { .tocMotionWrapper\_AUhf4 { display: flex; } }
.tocItemChildren\_TvU-m .tocMenuItem\_k5u8k { margin-left:
var(--sp-spacing-100); } .newPageMenuItem\_LsRng .tocMenuItem\_k5u8k {
color: var(--sp-color-text-light); border-radius: var(--sp-radius-300);
} button.tocMenuItem\_k5u8k { appearance: none; border: none;
background: transparent; cursor: pointer; }
button:disabled.tocMenuItem\_k5u8k { cursor: not-allowed; }
.tocMenuItem\_k5u8k\[aria-current\], .tocMenuItem\_k5u8k\[href\]:hover,
.tocMenuItem\_k5u8k\[href\]:focus-visible, .newPageMenuItem\_LsRng
.tocMenuItem\_k5u8k:hover, .newPageMenuItem\_LsRng
.tocMenuItem\_k5u8k:focus-visible { background-color:
var(--sp-color-bg-standout-base); color: var(--sp-color-text-base); }
.tocGroup\_Uier2 { margin-bottom: var(--sp-spacing-650); } \* +
.tocGroup\_Uier2 { margin-top: var(--sp-spacing-650); } .tocGroup\_Uier2
+ .tocGroup\_Uier2 { margin-top: var(--sp-spacing-0); }
.tocItemChildren\_TvU-m { gap: var(--sp-spacing-200); position:
relative; margin-top: var(--sp-spacing-200); }
.tocItemChildrenLine\_EQRRP { position: absolute; top: 0px; bottom: 0px;
left: 0px; width: 1px; background-color: var(--sp-color-border-light); }
.tocItemChildrenLineConflicted\_O3CXz { background-color:
var(--color-warning-muted); } .menuItemLabel\_CbI9D { display:
inline-flex; vertical-align: middle; align-items: center; }
.menuItemGroup\_dfzGS { text-transform: uppercase; }
.menuItemExpanded\_exIN7 { transition: rotate 200ms ease 0s; rotate:
0.25turn; } .newPageMenuItem\_LsRng { border: none; margin-right:
var(--sp-spacing-400); } .disclosureButton\_rELaR,
.disclosureButton\_rELaR:hover, .disclosureButton\_rELaR:active,
.disclosureButton\_rELaR:focus-visible, .menuItemButton\_v0sRA {
background-color: transparent; } .menuItemButton\_v0sRA:hover,
.menuItemButton\_v0sRA:active, .menuItemButton\_v0sRA:focus-visible {
background-color: var(--sp-color-bg-standout-on-base); }
.actionsButton\_LgBRh { transition: opacity 0.15s ease 0s; opacity: 0; }
.actionsButton\_LgBRh.active\_etKgK, .actionsButton\_LgBRh:focus-visible
{ opacity: 1; } .added\_rDRC1 { color: var(--sp-color-icon-diff-added);
} .deleted\_o0zxE { color: var(--sp-color-icon-diff-deleted); }
.modified\_Zd7Ia { color: var(--sp-color-icon-diff-modified); }
.dot\_Q4qwk { width: 7px; height: 7px; background-color:
var(--sp-color-attention-upgrade); } .disabled\_n8ush {
background-color: var(--sp-color-bg-muted); } .fileItemSeperator\_CkhaN
{ border-bottom: 1px solid var(--color-background-standout); }
.fileTypeInfoIcon\_D47ls { width: var(--sp-size-icon-300); height:
var(--sp-size-icon-300); color: var(--color-info-main); }
.imageItem\_lflIb { border-width: 2px; border-color: transparent;
overflow: hidden; width: 142px; height: 100px; } .imageAuthor\_AbPnX {
max-width: 142px; } .imageItem\_lflIb:hover,
.imageItem\_lflIb:focus-within { outline: var(--color-primary-main)
solid 2px; } .unsplashImage\_sd2F6 { aspect-ratio: 2 / 1; object-fit:
cover; width: 142px; height: 100px; } .changeRequestStatus\_Xfm80 {
position: absolute; box-shadow: 0px 0px 0px 1px var(--sp-color-bg-base);
background: var(--sp-color-bg-base); right: 0px; bottom: 0px; translate:
20% -20%; } .wrapper\_oADFW { border-bottom: 1px solid
var(--sp-color-border-base); } .header\_rroi5 { height:
var(--sp-size-600); padding-inline: var(--sp-spacing-200); } @media
screen and (min-width: 701px) { .header\_rroi5 { padding-inline:
var(--sp-spacing-600); } .shareButton\_dpVtI { margin-left:
var(--sp-spacing-400); } } .buttonIcon\_PNHD1 { width: 16px; height:
16px; } .commentBoxBgActive\_rgpQ5 { background-color:
var(--sp-color-comments-comment-bg-active); }
.commentBoxBgResolved\_C9IWA { background-color:
var(--sp-color-comments-comment-bg-resolved); } .reviewStatusIcon\_uVtTj
{ padding: calc((var(--sp-size-button-300) - var(--sp-size-icon-400)) /
2); } .avatarBadge\_YTUIm { border: 1px solid
var(--sp-color-sidesheet-avatar-badge-border); z-index: 2; position:
absolute; right: calc(-1 \* var(--sp-spacing-100)); }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
https://www.gstatic.com/\_/translate\_http/\_/ss/k=translate\_http.tr.qhDXWpKopYk.L.W.O/am=wA/d=0/rs=AN8SPfq5gedF4FIOWZgYyMCNZA5tU966ig/m=el\_main\_css
@charset "utf-8"; .VIpgJd-ZVi9od-ORHb-OEVmcd { left: 0px; top: 0px;
height: 39px; width: 100%; z-index: 10000001; position: fixed;
border-top: none; border-right: none; border-left: none; border-image:
initial; border-bottom: 1px solid rgb(107, 144, 218); margin: 0px;
box-shadow: rgb(153, 153, 153) 0px 0px 8px 1px; }
.VIpgJd-ZVi9od-xl07Ob-OEVmcd { z-index: 10000002; border: none;
position: fixed; box-shadow: rgb(153, 153, 153) 0px 3px 8px 2px; }
.VIpgJd-ZVi9od-SmfZ-OEVmcd { z-index: 10000000; border: none; margin:
0px; } .goog-te-gadget { font-family: arial; font-size: 11px; color:
rgb(102, 102, 102); white-space: nowrap; } .goog-te-gadget img {
vertical-align: middle; border: none; } .goog-te-gadget-simple {
background-color: rgb(255, 255, 255); border-width: 1px; border-style:
solid; border-color: rgb(155, 155, 155) rgb(213, 213, 213) rgb(232, 232,
232); font-size: 10pt; display: inline-block; padding-top: 1px;
padding-bottom: 2px; cursor: pointer; } .goog-te-gadget-icon {
margin-left: 2px; margin-right: 2px; width: 19px; height: 19px; border:
none; vertical-align: middle; } .goog-te-combo { margin-left: 4px;
margin-right: 4px; vertical-align: baseline; } .goog-te-gadget
.goog-te-combo { margin: 4px 0px; } .VIpgJd-ZVi9od-l4eHX-hSRGPd,
.VIpgJd-ZVi9od-l4eHX-hSRGPd:link, .VIpgJd-ZVi9od-l4eHX-hSRGPd:visited,
.VIpgJd-ZVi9od-l4eHX-hSRGPd:hover, .VIpgJd-ZVi9od-l4eHX-hSRGPd:active {
font-size: 12px; font-weight: bold; color: rgb(68, 68, 68);
text-decoration: none; } .VIpgJd-ZVi9od-ORHb
.VIpgJd-ZVi9od-l4eHX-hSRGPd, .VIpgJd-ZVi9od-TvD9Pc-hSRGPd { display:
block; margin: 0px 10px; } .VIpgJd-ZVi9od-ORHb
.VIpgJd-ZVi9od-l4eHX-hSRGPd { padding-top: 2px; padding-left: 4px; }
.goog-te-combo, .VIpgJd-ZVi9od-ORHb \*, .VIpgJd-ZVi9od-SmfZ \*,
.VIpgJd-ZVi9od-xl07Ob \*, .VIpgJd-ZVi9od-vH1Gmf \*,
.VIpgJd-ZVi9od-l9xktf \* { font-family: arial; font-size: 10pt; }
.VIpgJd-ZVi9od-ORHb { margin: 0px; background-color: rgb(228, 239, 251);
overflow: hidden; } .VIpgJd-ZVi9od-ORHb img { border: none; }
.VIpgJd-ZVi9od-ORHb-bN97Pc { color: rgb(0, 0, 0); }
.VIpgJd-ZVi9od-ORHb-bN97Pc img { vertical-align: middle; }
.VIpgJd-ZVi9od-ORHb-Tswv1b { color: rgb(102, 102, 102); vertical-align:
top; margin-top: 0px; font-size: 7pt; } .VIpgJd-ZVi9od-ORHb-KE6vqe {
width: 8px; } .VIpgJd-ZVi9od-LgbsSe { border-color: rgb(231, 231, 231);
border-style: none solid solid none; border-width: 0px 1px 1px 0px; }
.VIpgJd-ZVi9od-LgbsSe div { border-color: rgb(204, 204, 204) rgb(153,
153, 153) rgb(153, 153, 153) rgb(204, 204, 204); border-style: solid;
border-width: 1px; height: 20px; } .VIpgJd-ZVi9od-LgbsSe button {
background: transparent; border: none; cursor: pointer; height: 20px;
overflow: hidden; margin: 0px; vertical-align: top; white-space: nowrap;
} .VIpgJd-ZVi9od-LgbsSe button:active { background: none 0px 0px repeat
scroll rgb(204, 204, 204); } .VIpgJd-ZVi9od-SmfZ { margin: 0px;
background-color: rgb(255, 255, 255); white-space: nowrap; }
.VIpgJd-ZVi9od-SmfZ-hSRGPd { text-decoration: none; font-weight: bold;
font-size: 10pt; border: 1px outset rgb(136, 136, 136); padding: 6px
10px; white-space: nowrap; position: absolute; left: 0px; top: 0px; }
.VIpgJd-ZVi9od-SmfZ-hSRGPd img { margin-left: 2px; margin-right: 2px;
width: 19px; height: 19px; border: none; vertical-align: middle; }
.VIpgJd-ZVi9od-SmfZ-hSRGPd span { text-decoration: underline;
margin-left: 2px; margin-right: 2px; vertical-align: middle; }
.goog-te-float-top .VIpgJd-ZVi9od-SmfZ-hSRGPd { padding: 2px;
border-top-width: 0px; } .goog-te-float-bottom
.VIpgJd-ZVi9od-SmfZ-hSRGPd { padding: 2px; border-bottom-width: 0px; }
.VIpgJd-ZVi9od-xl07Ob-lTBxed { text-decoration: none; color: rgb(0, 0,
204); white-space: nowrap; margin-left: 4px; margin-right: 4px; }
.VIpgJd-ZVi9od-xl07Ob-lTBxed span { text-decoration: underline; }
.VIpgJd-ZVi9od-xl07Ob-lTBxed img { margin-left: 2px; margin-right: 2px;
} .goog-te-gadget-simple .VIpgJd-ZVi9od-xl07Ob-lTBxed { color: rgb(0, 0,
0); } .goog-te-gadget-simple .VIpgJd-ZVi9od-xl07Ob-lTBxed span {
text-decoration: none; } .VIpgJd-ZVi9od-xl07Ob { background-color:
rgb(255, 255, 255); text-decoration: none; border: 2px solid rgb(195,
217, 255); overflow: hidden scroll; position: absolute; left: 0px; top:
0px; } .VIpgJd-ZVi9od-xl07Ob-ibnC6b { padding: 3px; text-decoration:
none; } .VIpgJd-ZVi9od-xl07Ob-ibnC6b, .VIpgJd-ZVi9od-xl07Ob-ibnC6b:link
{ color: rgb(0, 0, 204); background: rgb(255, 255, 255); }
.VIpgJd-ZVi9od-xl07Ob-ibnC6b:visited { color: rgb(85, 26, 139); }
.VIpgJd-ZVi9od-xl07Ob-ibnC6b:hover { background: rgb(195, 217, 255); }
.VIpgJd-ZVi9od-xl07Ob-ibnC6b:active { color: rgb(0, 0, 204); }
.VIpgJd-ZVi9od-vH1Gmf { background-color: rgb(255, 255, 255);
text-decoration: none; border: 1px solid rgb(107, 144, 218); overflow:
hidden; padding: 4px; } .VIpgJd-ZVi9od-vH1Gmf-KrhPNb { width: 16px; }
.VIpgJd-ZVi9od-vH1Gmf-hgDUwe { margin: 6px 0px; height: 1px;
background-color: rgb(170, 170, 170); overflow: hidden; }
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b div, .VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd
div { padding: 4px; } .VIpgJd-ZVi9od-vH1Gmf-ibnC6b .uDEFge { display:
none; } .VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd .uDEFge { }
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd .fmcmS { padding-left: 4px;
padding-right: 4px; } .VIpgJd-ZVi9od-vH1Gmf-ibnC6b,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd { text-decoration: none; }
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b div, .VIpgJd-ZVi9od-vH1Gmf-ibnC6b:link div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b:visited div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b:active div { color: rgb(0, 0, 204);
background: rgb(255, 255, 255); } .VIpgJd-ZVi9od-vH1Gmf-ibnC6b:hover div
{ color: rgb(255, 255, 255); background: rgb(51, 102, 204); }
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd:link div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd:visited div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd:hover div,
.VIpgJd-ZVi9od-vH1Gmf-ibnC6b-gk6SMd:active div { color: rgb(0, 0, 0);
font-weight: bold; } .VIpgJd-ZVi9od-l9xktf { background-color: rgb(255,
255, 255); overflow: hidden; padding: 8px; border: none; border-radius:
10px; } .VIpgJd-ZVi9od-l9xktf-OEVmcd { background-color: rgb(255, 255,
255); border: 1px solid rgb(107, 144, 218); box-shadow: rgb(153, 153,
153) 0px 3px 8px 2px; border-radius: 8px; } .VIpgJd-ZVi9od-l9xktf img {
border: none; } .VIpgJd-ZVi9od-l9xktf-fmcmS { margin-top: 6px; }
.VIpgJd-ZVi9od-l9xktf-VgwJlc { margin-top: 6px; white-space: nowrap; }
.VIpgJd-ZVi9od-l9xktf-VgwJlc \* { vertical-align: middle; }
.VIpgJd-ZVi9od-l9xktf-VgwJlc .DUGJie { background-image:
url("https://www\&google.com/images/zippy\_minus\_sm.gif"); }
.VIpgJd-ZVi9od-l9xktf-VgwJlc .TdyTDe { background-image:
url("https://www\&google.com/images/zippy\_plus\_sm.gif"); }
.VIpgJd-ZVi9od-l9xktf-VgwJlc span { color: rgb(0, 0, 204);
text-decoration: underline; cursor: pointer; margin: 0px 4px; }
.VIpgJd-ZVi9od-l9xktf-I9GLp { margin: 6px 0px 0px; }
.VIpgJd-ZVi9od-l9xktf-I9GLp form { margin: 0px; }
.VIpgJd-ZVi9od-l9xktf-I9GLp form textarea { margin-bottom: 4px; width:
100%; } .VIpgJd-ZVi9od-l9xktf-yePe5c { margin: 6px 0px 4px; }
.VIpgJd-ZVi9od-aZ2wEe-wOHMyf { z-index: 1000; position: fixed;
transition-delay: 0.6s; left: -1000px; top: -1000px; }
.VIpgJd-ZVi9od-aZ2wEe-wOHMyf-ti6hGc { transition-delay: 0s; left: -14px;
top: -14px; } .VIpgJd-ZVi9od-aZ2wEe-OiiCO { display: flex;
-webkit-box-align: center; align-items: center; -webkit-box-pack:
center; justify-content: center; width: 104px; height: 104px;
border-radius: 50px; background:
url("https://www.gstatic.com/images/branding/product/2x/translate\_24dp.png")
50% 50% no-repeat rgb(255, 255, 255); transition: all 0.6s ease-in-out
0s; transform: scale(0.4); opacity: 0; }
.VIpgJd-ZVi9od-aZ2wEe-OiiCO-ti6hGc { transform: scale(0.5); opacity: 1;
} .VIpgJd-ZVi9od-aZ2wEe { margin: 2px 0px 0px 2px; animation: 1.4s
linear 0s infinite normal none running spinner-rotator; }
@-webkit-keyframes spinner-rotator { 0% { transform: rotate(0deg); }
100% { transform: rotate(270deg); } } @keyframes spinner-rotator { 0% {
transform: rotate(0deg); } 100% { transform: rotate(270deg); } }
.VIpgJd-ZVi9od-aZ2wEe-Jt5cK { stroke-dasharray: 187; stroke-dashoffset:
0; stroke: rgb(66, 133, 244); transform-origin: center center;
animation: 1.4s ease-in-out 0s infinite normal none running
spinner-dash; } @-webkit-keyframes spinner-dash { 0% {
stroke-dashoffset: 187; } 50% { stroke-dashoffset: 46.75; transform:
rotate(135deg); } 100% { stroke-dashoffset: 187; transform:
rotate(450deg); } } @keyframes spinner-dash { 0% { stroke-dashoffset:
187; } 50% { stroke-dashoffset: 46.75; transform: rotate(135deg); } 100%
{ stroke-dashoffset: 187; transform: rotate(450deg); } }
.VIpgJd-yAWNEb-L7lbkb html, .VIpgJd-yAWNEb-L7lbkb body,
.VIpgJd-yAWNEb-L7lbkb div, .VIpgJd-yAWNEb-L7lbkb span,
.VIpgJd-yAWNEb-L7lbkb iframe, .VIpgJd-yAWNEb-L7lbkb h1,
.VIpgJd-yAWNEb-L7lbkb h2, .VIpgJd-yAWNEb-L7lbkb h3,
.VIpgJd-yAWNEb-L7lbkb h4, .VIpgJd-yAWNEb-L7lbkb h5,
.VIpgJd-yAWNEb-L7lbkb h6, .VIpgJd-yAWNEb-L7lbkb p, .VIpgJd-yAWNEb-L7lbkb
a, .VIpgJd-yAWNEb-L7lbkb img, .VIpgJd-yAWNEb-L7lbkb ol,
.VIpgJd-yAWNEb-L7lbkb ul, .VIpgJd-yAWNEb-L7lbkb li,
.VIpgJd-yAWNEb-L7lbkb table, .VIpgJd-yAWNEb-L7lbkb form,
.VIpgJd-yAWNEb-L7lbkb tbody, .VIpgJd-yAWNEb-L7lbkb tr,
.VIpgJd-yAWNEb-L7lbkb td { margin: 0px; padding: 0px; border: 0px;
font-style: inherit; font-variant: inherit; font-weight: inherit;
font-stretch: inherit; font-family: inherit; font-size: 100%;
vertical-align: baseline; text-align: left; line-height: normal; }
.VIpgJd-yAWNEb-L7lbkb ol, .VIpgJd-yAWNEb-L7lbkb ul { list-style: none; }
.VIpgJd-yAWNEb-L7lbkb table { border-collapse: collapse; border-spacing:
0px; } .VIpgJd-yAWNEb-L7lbkb caption, .VIpgJd-yAWNEb-L7lbkb th,
.VIpgJd-yAWNEb-L7lbkb td { text-align: left; font-weight: normal; } div
\> .VIpgJd-yAWNEb-L7lbkb { padding: 10px 14px; } .VIpgJd-yAWNEb-L7lbkb {
color: rgb(34, 34, 34); background-color: rgb(255, 255, 255); border:
1px solid rgb(238, 238, 238); box-shadow: rgba(0, 0, 0, 0.2) 0px 4px
16px; display: none; font-family: arial; font-size: 10pt; width: 420px;
padding: 12px; position: absolute; z-index: 10000; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-nVMfcd-fmcmS,
.VIpgJd-yAWNEb-yAWNEb-Vy2Aqc-pbTTYe { clear: both; font-size: 10pt;
position: relative; text-align: justify; width: 100%; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-r4nke { color: rgb(153, 153, 153);
font-family: arial, sans-serif; margin: 4px 0px; text-align: left; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-TvD9Pc-LgbsSe { display: none; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-l4eHX { float: left; margin: 0px; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-Z0Arqf-PLDbbf { display:
inline-block; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-fw42Ze-Z0Arqf-haAclf { display: none; width: 100%; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-Z0Arqf-H9tDt { margin-top: 20px; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-LK5yu { float: left; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-qwU8Me { float: right; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-cGMI2b { min-height: 15px;
position: relative; height: 1%; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-jOfkMb-Ne3sFf { background: rgb(41, 145, 13);
border-radius: 4px; box-shadow: rgb(30, 102, 9) 0px 2px 2px inset;
color: white; font-size: 9pt; font-weight: bolder; margin-top: 12px;
padding: 6px; text-shadow: rgb(30, 102, 9) 1px 1px 1px; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-Z0Arqf-hSRGPd { color: rgb(17, 85,
204); cursor: pointer; font-family: arial; font-size: 11px;
margin-right: 15px; text-decoration: none; } .VIpgJd-yAWNEb-L7lbkb \>
textarea { font-family: arial; resize: vertical; width: 100%;
margin-bottom: 10px; border-radius: 1px; border-width: 1px;
border-style: solid; border-color: silver rgb(217, 217, 217) rgb(217,
217, 217); border-image: initial; font-size: 13px; height: auto;
overflow-y: auto; padding: 1px; } .VIpgJd-yAWNEb-L7lbkb textarea:focus {
box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 2px inset; border: 1px solid
rgb(77, 144, 254); outline: none; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-Z0Arqf-IbE0S { margin-right: 10px; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp { min-height: 25px;
vertical-align: middle; padding-top: 8px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp { margin-bottom:
0px; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input { display: inline-block; min-width:
54px; border: 1px solid rgba(0, 0, 0, 0.1); text-align: center; color:
rgb(68, 68, 68); font-size: 11px; font-weight: bold; height: 27px;
outline: 0px; padding: 0px 8px; vertical-align: middle; line-height:
27px; margin: 0px 16px 0px 0px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px
2px; border-radius: 2px; transition: all 0.218s ease 0s;
background-color: rgb(245, 245, 245); background-image:
-webkit-linear-gradient(top, rgb(245, 245, 245), rgb(241, 241, 241));
user-select: none; cursor: default; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp input:hover {
border: 1px solid rgb(198, 198, 198); color: rgb(34, 34, 34);
transition: all 0s ease 0s; background-color: rgb(248, 248, 248);
background-image: -webkit-linear-gradient(top, rgb(248, 248, 248),
rgb(241, 241, 241)); } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:active { border: 1px solid rgb(198,
198, 198); color: rgb(51, 51, 51); background-color: rgb(246, 246, 246);
background-image: -webkit-linear-gradient(top, rgb(246, 246, 246),
rgb(241, 241, 241)); } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:focus .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp input.AHmuwe
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:active, .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp
input:focus:active { box-shadow: rgba(255, 255, 255, 0.5) 0px 0px 0px
1px inset; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:focus, .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp input.AHmuwe {
outline: none; border: 1px solid rgb(77, 144, 254); z-index: 4
\!important; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input.gk6SMd { background-color: rgb(238,
238, 238); background-image: -webkit-linear-gradient(top, rgb(238, 238,
238), rgb(224, 224, 224)); box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 2px
inset; border: 1px solid rgb(204, 204, 204); color: rgb(51, 51, 51); }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf { color:
white; border-color: rgb(48, 121, 237); background-color: rgb(77, 144,
254); background-image: -webkit-linear-gradient(top, rgb(77, 144, 254),
rgb(71, 135, 237)); } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:hover
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:focus,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf.AHmuwe
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:active {
border-color: rgb(48, 121, 237); background-color: rgb(53, 122, 232);
background-image: -webkit-linear-gradient(top, rgb(77, 144, 254),
rgb(53, 122, 232)); } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:hover {
box-shadow: rgb(255, 255, 255) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.1)
0px 1px 1px; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:focus, .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp input.AHmuwe,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input:active, .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-L4Nn5e-I9GLp .VIpgJd-yAWNEb-Z0Arqf-I9GLp input:hover,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:focus,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf.AHmuwe,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:active,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-L4Nn5e-I9GLp
.VIpgJd-yAWNEb-Z0Arqf-I9GLp input .VIpgJd-yAWNEb-Z0Arqf-sFeBqf:hover {
border-color: rgb(48, 121, 237); } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-mrxPge { color: rgb(153, 153, 153); font-family: arial,
sans-serif; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-W0vJo-fmcmS {
color: rgb(153, 153, 153); font-size: 11px; font-family: arial,
sans-serif; margin: 15px 0px 5px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-u0pjoe-fmcmS { color: rgb(136, 0, 0); display:
none; font-size: 9pt; } .VIpgJd-yAWNEb-VIpgJd-fmcmS-sn54Q {
background-color: rgb(201, 215, 241); box-shadow: rgb(153, 153, 170) 2px
2px 4px; box-sizing: border-box; position: relative; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-xl07Ob
.VIpgJd-yAWNEb-VIpgJd-xl07Ob { background: rgb(255, 255, 255); border:
1px solid rgb(221, 221, 221); box-shadow: rgb(153, 153, 170) 0px 2px
4px; min-width: 0px; outline: none; padding: 0px; position: absolute;
z-index: 2000; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-xl07Ob
.VIpgJd-yAWNEb-VIpgJd-j7LFlb { cursor: pointer; padding: 2px 5px 5px;
margin-right: 0px; border-style: none; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-xl07Ob .VIpgJd-yAWNEb-VIpgJd-j7LFlb:hover {
background: rgb(221, 221, 221); } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-xl07Ob .VIpgJd-yAWNEb-VIpgJd-j7LFlb h1 {
font-size: 100%; font-weight: bold; margin: 4px 0px; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-xl07Ob
.VIpgJd-yAWNEb-VIpgJd-j7LFlb strong { color: rgb(52, 90, 173); }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-VIpgJd-eKm5Fc-hFsbo { text-align:
right; position: absolute; right: 0px; left: auto; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-VIpgJd-j7LFlb-SIsrTd
.VIpgJd-yAWNEb-VIpgJd-eKm5Fc-hFsbo { text-align: left; position:
absolute; left: 0px; right: auto; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-yAWNEb-Vy2Aqc-fmcmS, .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-TVLw9c-ppHlrf-sn54Q { background-color: rgb(241, 234, 0);
border-radius: 4px; box-shadow: rgba(0, 0, 0, 0.5) 3px 3px 4px;
box-sizing: border-box; color: rgb(241, 234, 0); cursor: pointer;
margin: -2px -2px -2px -3px; padding: 2px 2px 2px 3px; position:
relative; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-TVLw9c-ppHlrf-sn54Q {
color: rgb(34, 34, 34); } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-yAWNEb-Vy2Aqc-pbTTYe { color: white; position: absolute
\!important; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-TVLw9c-ppHlrf,
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-TVLw9c-ppHlrf
.VIpgJd-yAWNEb-TVLw9c-ppHlrf-sn54Q { background-color: rgb(201, 215,
241); border-radius: 4px 4px 0px 0px; box-shadow: rgba(0, 0, 0, 0.5) 3px
3px 4px; box-sizing: border-box; cursor: pointer; margin: -2px -2px -2px
-3px; padding: 2px 2px 3px 3px; position: relative; }
.VIpgJd-yAWNEb-L7lbkb span:focus { outline: none; }
.VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-TVLw9c-DyVDA { background-color:
transparent; border: 1px solid rgb(77, 144, 254); border-radius: 0px;
margin: -2px; padding: 1px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-yAWNEb-TVLw9c-sn54Q-LzX3ef { border-left: 2px solid red;
margin-left: -2px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-yAWNEb-TVLw9c-sn54Q-YIAiIb { border-right: 2px solid red;
margin-right: -2px; } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-YPqjbf
{ padding: 2px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-YPqjbf-fmcmS { font-size: 11px; padding: 2px 2px
3px; margin: 0px; background-color: rgb(255, 255, 255); color: rgb(51,
51, 51); border-width: 1px; border-style: solid; border-color: rgb(192,
192, 192) rgb(217, 217, 217) rgb(217, 217, 217); border-image: initial;
display: inline-block; vertical-align: top; height: 21px; box-sizing:
border-box; border-radius: 1px; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-YPqjbf-fmcmS:hover { border-width: 1px;
border-style: solid; border-color: rgb(160, 160, 160) rgb(185, 185, 185)
rgb(185, 185, 185); border-image: initial; box-shadow: rgba(0, 0, 0,
0.1) 0px 1px 2px inset; } .VIpgJd-yAWNEb-L7lbkb
.VIpgJd-yAWNEb-IFdKyd-YPqjbf-fmcmS:focus { box-shadow: rgba(0, 0, 0,
0.3) 0px 1px 2px inset; outline: none; border: 1px solid rgb(77, 144,
254); } .VIpgJd-yAWNEb-L7lbkb .VIpgJd-yAWNEb-IFdKyd-YPqjbf-sFeBqf {
font-size: 11px; padding: 2px 6px 3px; margin: 0px 0px 0px 2px; height:
21px; } .VIpgJd-yAWNEb-hvhgNd { font-family: "Google Sans", Arial,
sans-serif; } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-l4eHX-i3jM8c {
position: absolute; top: 10px; left: 14px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-l4eHX-SIsrTd { position: absolute; top: 10px;
right: 14px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-k77Iif-i3jM8c, .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-k77Iif-SIsrTd { margin: 16px; padding: 0px; }
.VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-IuizWc { margin: 0px 0px 0px
36px; padding: 0px; color: rgb(116, 119, 117); font-size: 14px;
font-weight: 500; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-k77Iif-SIsrTd .VIpgJd-yAWNEb-hvhgNd-IuizWc {
text-align: right; margin: 0px 36px 0px 0px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-axAV1 { width: auto; padding: 12px 0px 0px; color:
rgb(31, 31, 31); font-size: 16px; text-align: initial; }
.VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-axAV1 .VIpgJd-yAWNEb-SIsrTd
{ text-align: right; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-N7Eqid { border-radius: 0px 0px 12px 12px; margin:
0px; background: rgb(241, 244, 249); position: relative; min-height:
50px; } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-N7Eqid
.VIpgJd-yAWNEb-SIsrTd { text-align: right; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-N7Eqid-B7I4Od { display: inline-block; width: 77%;
padding: 12px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-N7Eqid-B7I4Od .VIpgJd-yAWNEb-SIsrTd { text-align:
right; } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-UTujCb { color:
rgb(31, 31, 31); font-size: 12px; font-weight: 500; }
.VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-N7Eqid-B7I4Od
.VIpgJd-yAWNEb-SIsrTd .VIpgJd-yAWNEb-hvhgNd-UTujCb { text-align: right;
} .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-eO9mKe { color: rgb(68,
71, 70); font-size: 12px; padding-top: 4px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-N7Eqid-B7I4Od .VIpgJd-yAWNEb-SIsrTd
.VIpgJd-yAWNEb-hvhgNd-eO9mKe { text-align: right; }
.VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-xgov5 { position: absolute;
top: 10px; right: 5px; } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-xgov5 .VIpgJd-yAWNEb-SIsrTd { left: 5px; right:
auto; } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-THI6Vb { fill:
rgb(11, 87, 208); } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-bgm6sf {
margin: -4px 2px 0px 0px; padding: 2px 0px 0px; width: 48px; height:
48px; border: none; border-radius: 24px; cursor: pointer; background:
none; } .VIpgJd-yAWNEb-hvhgNd .VIpgJd-yAWNEb-hvhgNd-bgm6sf:hover {
background: rgb(232, 235, 236); } .VIpgJd-yAWNEb-hvhgNd
.VIpgJd-yAWNEb-hvhgNd-aXYTce { display: none; } sentinel { }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: image/avif Content-Transfer-Encoding: binary
Content-Location:
https://www.gitbook.com/cdn-cgi/image/width=256,dpr=2,height=40,fit=contain,format=auto/https%3A%2F%2F2873717268-files.gitbook.io%2F\~%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnquaL4SJ8uar13sCFHzm%252Flogo%252FRVz1Ooeh2CBG3q18O0oV%252Ffavicon%2520256x256.png%3Falt%3Dmedia%26token%3D12828983-c9e7-4144-8ec6-1c258ed36c6a
  ?٧�/&#1; &#6;�2�&#5;dX��JE�?�&#15;�&#7;�&#2; &#1; �
1u&#14;�U��)���&#3;J7�q��\_�&#24;(Pm����^3r����Z�A�Cn�rѾ'�������Ǿ���&#7;��S����i\\s��&#23;X&#2;�?�w͞�\_.\\\]�uZ
�&#16;�\_�����,�&#20;�&#1;J��&#29;F�\*%6&#24;L&#24;Z�䎙�QȞ+2�&#6;oM����P�&#26;\>�f�&#28;&#14;&#18;��K\>ǟ�=�&#4;&#6;o{���(8�&#29;�\*$30�W�m&#7;&#21;r��&#26;k&#8;K���2F�i��$��2�)�nD�4ghv��i&#2;��aCT&#24;�F�
��&#25;/����p�\>�&#29;&#7;¢�&#30;���&#27;��$��h۳W��
V��/&#20;&#23;f�&#5;�� �d��&#28;�&#31;�$a;$�
��̀&#19;C�zo�5�;�ӟ'T�Ve\[&#7;��%&#17;��$�&#17;B�Nߺ���.���/�/ޚS&#5;�Q�\>�\~h&#22;%R��a�����+&#11;�?�Ҁ��&#12;&#15;�0���U2꡺
�Ժ3�𓞞��3E���^&#3;�xIe&#22;\]&#2;y5㥐�CZx\_�A�;&#18;&#14;H9xx���{X��Γ�P�&#1;��&#18;�Zܝ�ָz&#28;\`�u����G�.&#21;2ہ&#27;�k4�w��W�\\&#4;&#8;�&#26;ԠNH��;\#�4���&#4;\~q&#19;&#29;��&#1;ߍ52�-�n�&#30;w�����ⷖ&#3;Z��;F\\&;̺&#1;��&#14;UĊ�\~z�1��hbԦ�s
��d&#25;���y� �\#�8��L ׻ul��h�@�g
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: image/avif Content-Transfer-Encoding: binary
Content-Location:
https://www.gitbook.com/cdn-cgi/image/width=256,dpr=2,height=30,fit=contain,format=auto/https%3A%2F%2F2873717268-files.gitbook.io%2F\~%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FnquaL4SJ8uar13sCFHzm%252Flogo%252FRVz1Ooeh2CBG3q18O0oV%252Ffavicon%2520256x256.png%3Falt%3Dmedia%26token%3D12828983-c9e7-4144-8ec6-1c258ed36c6a
  ?�{�&#4;4&#27;@2�&#3;e�/A'&#19;���?�&#16;&#8;&#8;8&#4;&
��&#7;�r��&#28;&#18;i&#29;
bm�&#6;&#12;���&#4;zn&#6;��u����L���\*U1^C�P�|\>L%娨^��&#21;a7��\!);F�f�&#23;J�x&#28;W�&#16;'��&#21;�^&#26;D��L=��$����Q\[Ҷ�.�O��Y����&#22;�M͖�(,�d�?���9K&#23;/�b�&#2;{�\]�N�
��)I�pU����W�&�&#6;l�}
�t��保��&#20;&#20;�4&#14;rm;�&#25;���(;���4&#17;&#26;�a�\]b�EA�z&#16;�\\���A&#7;&#14;&#31;:�&#24;}�
��&#27;
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: image/svg+xml Content-Transfer-Encoding: binary
Content-Location:
https://fonts.gstatic.com/s/i/productlogos/translate/v14/24px.svg

\------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/html Content-ID: Content-Transfer-Encoding: binary
Content-Location: chrome-error://chromewebdata/

# app.gitbook.com diblokir. 

**app.gitbook.com** menolak untuk terhubung.

  - 
ERR\_BLOCKED\_BY\_RESPONSE

Oke

**app.gitbook.com** menolak untuk terhubung.

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABNEAAABkBAMAAABayruYAAAAJFBMVEUAAADa2tr/////9/e6urpTU1O5ubn39/f///9ZWVlfX1/z8/O/OctmAAAACXRSTlMA//////////ZO3iNwAAALPElEQVR4AezdwY6bShMF4GP6krX9Bqgk9kiI/SzyAAir9lnlFfL6N26OWhXckDae9mClj/L7L1czMMbfbYDMOCgpKSkpwelyRmIEd6mEhTQpDabvu1C7vsf2ALM6cLlctquVtq2YDwC1jrfHEVDV8fagvln7p7XOlUKVi9SKWrncY5GQnN0DhLuZ1HZJa7WZPemU0GCc6hUMBtVue4BZHeD3v1caTn9KIyiPSimIvjw8SqtDVaQlvKrT2e91JEVUsEilOtGTNkkNUglWnFLX1oDrWSwGSOZ8V91CRczFDnBkWVEaKG0WBISZDPOTeeD2MIZK/Sz4YESUkbxdRhlkTXTrJ74d+aQ1bFRPSRvYjUuLmLOKmNjIch3/fQesGygrHW/SyO2WWzWmSyvSHjpVE1WJSWsIqwJk0agmSmsb39gnzbGKSaOXyJTGKmFSA6vvv/Nh3NQaDpyjPWaCp22mt0+ahkj+LlTzU4tu3Ujjrt4nrZoIq20qlT8brW/4k7S5sQGq73ZJO+M5aawjc5pHRmmYLxMozY/64llp8oAeeaQrMWkir5EGnSPLg8aZ6OaIrJ3n8WsX0lptPCy5ldOiYaT5xro0p9cEaa7nAENd99DOrEzIK0btxOrDSKMl0JeyCgugtr2DSWunmDR2Xy7tdF7c7MgmrfmLNDa7LWmOX9pllzbSDac0UBqrpTQOHOboeQBpIWJOjU3Oq8dItu+pNZRWLaWFBg+nnyBt6FhxIMIrVGxfFqGujcuDj/lkf6S0EeYC9E5aGDiUtAMcPUNkMZ8xl/Oj0qqJ0tomSFs2xDfkaWlOr1FpZzwrzU5qP3jn1px/qeroQUGVDyR2q/hs9X5auSI44T5nLheTJkppdnDpiNJCY1ta3wVQcB2lceBrpH3Dj29F2qdKO50vEWunl0qb6RDUcO0ojQOGYFya6++gnVlRGiubIO1CXgtq+IFPTZF2AeJvBBeT+Ffz8TlpvJnhZTleSTo+NwOB4Iq0QbvPl/btJz41Rdpanpemf5EWbmZQVheXZgei0m7Fp0v7+Ts/APteqI6savX/Y22XCa3NJVlH9qrP092DSROfv3qUOXdt/t8z0iyo3rjplgMJ0ugkemPjHCobnKK3PPiFnNOOL61Iq95cGq89rZ9aQ6l1MKNYhLqi9XKZX79if0EokqNrk9FZwtZj0EJks01pamYztFYaSz7qXmmue5U0f+0Zs0FpWqR9rbSpIqwGFWEpG0Fau1/a4Fn1r5rTskv7pV5aJeYwA4hKli4UjFXmh2LhGho8mujW1yNzlFE+R7QdpDWUNgGoOHmxQWnazP090nr/R/UV0sLfe2ryGVfcZB1Zkms+qLRKhGki0iTkC6VNglmaNKC0KTSCNAhnvf3SOnT5pW3pwlgnzWnLqwOY9ghKE2nDzuQ7laUL81KMtHlYDC9TtpNIY+xJsrTl1pmnD6I8OeNE1gAsGzZgpIGz3pa0fkvaFe7qpfX5pH18fPyj0sKX6SRipTHKiHyJtIrS0Fppk4ANwgvSpNmW5hOXdu078Cab5pP23/cZx9oZV6I0qI5RaVC9SVO+dwyd5OlCNXKHQ9QsTF5qy8nY0zRp0a2nUiPO1bY9O6O0RaO10hpsSHPb0oD80vzP3AKqutSVfD+NITS7JAnrQaWRFeulNA35ImmVzLAgbZBmGySnKdIwJEjDkH1Oe4U0+94JnWTqQlUNNARpd5napTob2QYU33qqNEbifUn+3ahbK0Ga25bm/JzGhTKep+VOTmlFWpMiDcOmtKEbtLs9aNZrz9dIY+z5fKYu1MTc5dDVTBKlliBtsfWUyNpXiG2nSpvENHiJqT1B9To/dIDjQFSa0+ugvV5d32f7G/Yi7d2lAVYaQ0zMFeAgB0jwThrglDYzSMMXSIOPZOnGpW1Tm5pK2qelIS2yeptXGOB5aZ0zNaXZAaqLSKPNIm21W6TRCakMpqY0/8QNlmNcWpfj9wheElEbydxFVBpE1qVhSS2FkOyTlrDsPmlGVxfQXPuO0swAh1gupdHm+0uT3F1EoGWXJjiANCLqezuJMYMZIEGWVhoHcvwW3uupSfYurLRtapPc0iBOTXywFtkpTZBJGvp+CCdmvJIEYwZIkKWRlu932I8vrUjL8KlWhuDwhtLSr+3zdxGDZqnxdi2LBlhSEwlF+qv6XGkQaWZyImmNHZ815HojLfETYFguoeG0+gkwx5ZWpO3Krk+14tVCzk+1ej01kVd0EYHmNf15a2NOw1FLTSBM6qtKjajgYNJ4upb3k/r+TWki7SRr0iYRlX9Kmh/su8yfPvqa8MglqiKpXeGBzXYlaQ2khntpLX9AyEuLsOFWU+XYrSdHcDxpbtAuDGT6ROV/SVollNZULdcd32oSHZ7OcevKvKc0WGmZPiX+ZRFVgaikd3lgW1JLWsOs7F6a/3yLBmvSBBAh5/2vKn/ySztyji8NVZAW1m1CaXNQpL2vNOFDWjcSEUldAxQxaSLSTg3WpBHYQ9IERdpqijQmLi09qkXaYY+eKqndeBLXAFU+RA6gTcKqd7yq40hzFlS3MRCX1uHoKdJqfG2c86AGb6Wbf1b7ejcAx4GINA68c8Jvhqd240lbw3p4hra66vSoLrZ+gAyDhqnLXZUzlB0gwXnAWWl2IH+KtPeOc/3vdCCoWxYDJEhfHVz4LTwzkJKSEmetDN1ygARvA47/7OfQud4OJKWkxFJxCQOh5pP3S0lJSUlJSYmq4sipVcdF/Y4pqcfbnwNHgXFRv2FKagWgOG74D97a+h1Tonw8ZgiLjxo6nxQteV1GzmzK8NlxYkyMz/lAydGmEEVJSe7Mc0dJrY8uPyaedO4PN5I96Zsr+yp9c6ppKwKjSIuurYAZk48wy4xJb7COO2jU3CIXKPsqcV8dMnXaEjuiO76DL9xLZV/Va9+T6oP/LSVN3yO3wMXzRLEnY9lXyUk8dOquw8R4vHNG1T3fmCa90LKv0vfV/+2dQW6jQBBFEascwyqpL9RSiZO0ejvL4QZDbmB8g/hy0zXwRUPZ0QiRDfwnJ5aesstTCdNNm7yAEEJaWXE7ztQQEnRFPM6Q04+orftuwLS64XaUacjpR5Q7KyQuRirMBt0QjzLNmSHyr7TNSVuFOJuPYRjGifsw/GFp+yCtqBHlnemH4XOcKdH9Ymm7IKIT8eYNShvB/X1p3cYY2RlNznSXKI20CgQmrk2PkWZ8U1remtrBqDddukJpRNxHvxDDaqj1w7hwn0pLKbl5lfOL0pIrzZkuX6A00sYqDwy5sBpq/edYMZWWsxWTC3VpaWsK6o12G5NgmhPD0uRlaQFmKu05Pp6FL5TW5ZxRydSMqbQ1BXXGulqbDNOcFtKqqMoM7q5FM6Eq7WGlGShNp5lmoBm0B4MQVwYzbW0STENOS1AJUTQKLsuso2ARiBRnprfKvsbCo7zdUVpeLrLiG5O6vDX22pguw5y0NIKurDIJqorSROyXvU+ljVaaUZeWXFfedMmX5kyXLlAaCXNkWpcWA0JAaV/PbWkp/09pzmjypek1SmNp0ZWmMEtpoytNfUU7zTVLY2nK0sjPlKa+NGFp5AdKc58INE4/LI0cWloUe6E0TDjxpT1YGtmLaEFEcD8NJkiA6S2xmRGlZYBmDjENOftWDtFCrEyU9WrUBFajsIqElaajTEOuVFpQZKDx3Qr7Mozwx4eYhpyXsJR2m4wsGbzeNcQ9t2QHLf7pKjD1SPM7IVka2UUruKshMMGEISyNHMe8mh6lMrhuc88RDCyN7Gba9xhvlYlaBJ/CI8fSBg0qt9pIEYvpkdrdRhpLI57dXw66Mh+/K3haAuEJMOQ88FQrsoO/etICpT2ul1QAAAAASUVORK5CYII=)
![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAACY4AAADCCAMAAADT9DSoAAAANlBMVEUAAADa2tr/////9/e5ubn39/dTU1P29vbv7+/+/v74+Pjw8PD///9ZWVlfX1/z8/P5+fn///9RgilMAAAAEnRSTlMA///////////////2////9gn80juWAAAR/UlEQVR4AezdAW+jOBPG8QcgVPv9P+xqHQPvu9nrTWWd1enNuY7D/ydpS+gwdqRq44yN0WUBAAAAAAAA06u/sVPPbZZ0/Ie5LNvIEWbRu11msCsK7duYZM4OcaWzf1+rVk13fbTpj1SctXMWZJHluSLYTmxlUBlVxJlkZz/py2a/txeV/o1qls9B3q55/TALAAAAHa16KeU340nT4+gKZq36LesYPMIsWmR2mbGuqGvZxqkrOsct+wNgOAYA2Gy6bysmEo3N/71HKhWzg+W1haTCZqdr06Blu5tSvS/GpLIhAAzHmsxMWyWsqJA980zxKinb+4zWxh4Zs46RIyoVosWqRGNcYRGOrJE2zCTjjzsD+SwysJLTFXdaRCjf+DA7P74yeTvmrdtUKCTWjr2uaZIAoHR7k5a3H+oLANZX+W4zdf4WjFmHP+IyrM616/ucQ+S1nFO3FWTn/r6Gsbi50Sb+3l+aykxk5Q5Mu9xstTshK20UL5MAMBwbzsmyXgCF22yD5OVx/EthAMBw7NSobP1Yh2qV7X4WyjF/shLMIio5Xrw2tsTrY/3XjQXiLPYMxFktLZ7v3O04azRYA/+z9stL3s0Zk/ibHkqvqUwA2Opzl9ock5B2J2Qtn50t5ky38txW6R8AhmM9xt4w/mrVnyMpB3I8MjyOKyyimqO9+r2O16sRswdZtv+HNN01KGRJK/1tmfdhbZ4Xq67AtoS11wDwcLsLAK49HEvhqvrU9O7Po2HudpVAq0Udn0bocfQ4DuRo0NOB7nXsULPrsG7s9MUZ/zouTV3Wj0lZq6Z7juyclFQe1yYh7ZxxXJvKBJvsd+XvTbKTQHxtc+u8WPXyJp3Fh8kkAAAAhmMxzu/G/WHWccF7HesWazVYswOw0l/L++zAvmP1Oy0BoLr5a8WmIsC9lasdBVgeE8sMgOHYFl4nczZ7lqRsPVez3Nle2/qxXrvhN8hh903CqmB7uGYX3x/sDOdzaLj/2BTNB8Ahf1NerNz+DgAAwHCs/Vox9hdr2Yp/tzFqYw1XrZ1C9KmYSdrKab+tOh+42XXldqxJFf8Q95VrN5lUucuzov4+gP5r3TDrwqb/E4BLur39KI57AYCVfccra7v65Lb1Y4HqU7O9wQbdocvqUezcD3PuR3HcCwCsTGEAYDf+v4+TCkn1M/Wz9d8l/7X1vvj7l+wAAMMxoMeu+vErAhW45nVB92O/JpXOxndVtr+78tTkiiu/fFlctnqvHXcBAOtYS/incq/9oNPyALic27xrmeef6goAVqFc21Vfy9Uot+ptXozVf/y76nuvWKox8Tbsmn2op23i3MW+eAAYjn11YuOsTlUAgN9ttoHt8jj+JQBgOAb+GOKrvLr0yiIWixngaZvUxd5lgf3jyQuGYw5n5RwANH1wW3LHOyNT5WUtvpBav6n2/dwcwR0BDMfy06wb8++XewRzG9aPlfWfwBUXqEpNMqczTq3j2t9dGYg7Ncnisuw/wOkuAGBX/n4A4CYAoDrWFQ5lrboiIGvVdM/Vebq6Mn6TNt+F23u8U1JU8aasqzGBftb7M38y7zA7P86y5SBvPG+p2dxNojoGADyzEsD4qI41GtP3Xze2+r8jxHPHOXKuofqY5aAcG9+hHzyzEgBWCQB4ZmVgpvLr85VXAYDhGLIOzZ9G/HbYfWYNWrFVOtdQ26F/0TMBz6x81uei5Opv6x9buVNe8to3jOSIKSXnWqpDDURaZe0YAAAA1bEOY++ee56tzv3Bao5GuQ9X1coTYfnmSt9irVj+rPUCxVnboZ/a2MjKzV0796RDZ+wO0Jb93AQ8S93p6NVqJR4AAACsHUO80neEIoqVYYEcplihVrRyHfv7g6u1qwTAPbNScXTIS94WNVCbI5r/dSXpGKjVSwKA2zz/tJ8f+efp3GFFZn/+pJbqPazP2Mb7WSYHsI783cYh3F52rvEyJlv+JrmPatQh442o1caiOcor5korPSxda2O2O1m3XrHzmP18QQBm5+gjW2yHVg+75noAYHuTljfpJgBogclKnjdpEcH1Z/5W1kArr10bszrYx9rY0nV3MuS//p3u2b+Va8mCt6EfzFefq03tp0TTp/eUe+cRskrkbZ+3vvfY5pyyTs62Z2ef7QqvDq0yHAOA2ywbHD+OfwnAeKiOdRh793C41niZLHO0zN20PmYttG/le+0d60+7ngfO3Y6zXheA1RmTu7Vq8QAAm698IpvKHsbfVHJflVr2s5yvBBg0Yli2m5cjonUr6wB/XFYfu3Kf8PHvebqrK8SrBtnieuUlb7F+bHMuo9yaDVdW/7vo1SrPrASA25setrcf6gkA1qG+2wzA1sDF16a5cjt2LLGIAFcrSXN9z31qUdW9+JcufcK5T/f1URs7/LNs9cjUOD4itbwqBdImXRpAdQwAbvbzdQFg7RhgtTHqY7YXf3muR5+Qle0nhv94yn3ykjf+2LD4vFn8HXdvdVZHAAAAWIf5bjOALHPE9zYL5u4vh3q7fH4ucMVejVia18aWyrn9S704JU36Y9LpijPt4zzOb42bKnFdAQDVMQC46YUBoDoGHFKz2tiuXYvnCosvrrcIRxvOVmL2IqPvnfyPvXvRkRMHogAKYdT//70ImH3WitHGkTXuCpQ4Z59NsD2iETE3hWGEujHXG/2m9zvwNH9HJVfVUaVjAADSsYajaJ1YOEbfjdl9fNinPWf/Rpv+BG6ZxsnGAOqTjgEASMcgaTWwSIiiRXo2tvf/VL85FYynHP/5d//TlfEsZv7TlXlPS86eqqyv9Yx5hX7123j3pPox6RgAgHRsfO5dp27suKx2Tj62T3tfi9hvMBv7yzJeaZZSMQfEFVm/tfpdJ6RjAABqx9pzb+Rj/VlXTz7WNjBGo0Xs+159Kd+sMqqrygz1Y/pVP7ZdOKp0rD4AQDqmfkySl+1Xb27ce1sM2L+R2oX0fOyNT0PO0+d4f5e9q3J+c38AascAAKRjcL98bBlokZnaLZ0VcNlA/dim39x+k+rH1t9WP7Y1JjsfP9nnuHTUS9MxAAA+Kt3btHGcjuRRd48Cqd1ym7xutN4rnsQc70/dGIDaMQAA6RjXO4rv8YAV1GLbafvy5vX258QkaE5LmGYrjvVSP9ZR8aPf/H5H6sfWod/jfnyjkuvoXGfs2lEvTccAAPi4yb2NNcd4bGYW2VjV+rHoR90YcK3ty+RmKzCqdAwAQO0YyMf2+He4dQXZnNDrrGqshfgzlsbnGv3+4+O/7du/KcjxvX6jz5sfh6gfa30e89E4CltqzXLre/1VJnZIxwAApGO9c+8CDnVjpK1ftk/vE8nV3L9fO0vr769dQfbGGq9ZzRhYmatz/f5zivbP5yNv1NAY9XnpGACAdOz1zRX3X+Nvt4JC9sjGUkXqVZOqMSLnCNtPntk/7t9vvPXw5Bh6X2OkL9cfhz5rZv3YBSsfnEfarMoPACAd60yxeubea5H7NKjh86r9CvysQPm8tMN2bnfNqNIxAABPVgJAQr1OjX4/T/0eb8yFtvPnAsdhzVsF/7K6sZF3TkrHAACkY9mzVwCA4zajSscAAKRjr1MqBgDjq0wd7W236neOVdmz0pcCxyFmAmt72+BR+NH+SZPPw17SMQAA6dga8723zr1hmfb6LULiGPkAkI4BAEjH8r0e+75KCdjS+JW/tu+XtAjtFpliDHiarbGtQL95ChyHtXNblaO9SccAAKRjnV4x/33b3HudeJjIgRrJ1f7PP/kt+jO7aDFc4dU/BgBqxwAAeJt5gjK1Y/uFLZZGiz1anPbaT59O+8W48SuxtWsMAJ6SjgEA4MlKiDqp9pOF+S36K8rO2/f/fQr7lxH209beMQB4cjoGAACwLAVaJIwQbQB4djoGAAAAAAAAYN0xAF5eYEKVM9AZq3YMAEA6BkBCMrF+/XBPOAOdsdIxAADpGAAJNTtrM3qA689AZ6x0DABAOgZAfs1OO4CAa85AZ2zJdAwAgDmmqABU0C7R6WzabgwJZ+D62JNuvWM6BgCA2jEAz8M9sY4H1I4BACAdA+DVX+UCSMcAAKRj+dULNb0S7iQd1fzvBN+d65Wj6jsh/7uTjgEAlDRXmre/prVnteACqxknHIPe1mWOSv5Ryr9H7x+x8qhxtON7zP8ZXK9cr1yv8rleqR0DAFA7RlWvafVzXHt/XOn4q+bBdcL1yvXKk5UAAMzJM92EWXx+zUh+bUD+/D7vT9VlKfXvbOURrleuV2RwvZKOAQAUNZ/v3HJmuu3+3ZlTt0agfX6Pn2PuctvHz/WK+3K9cr2SjgEAAAAAAADFzN6R3vZHe3ew27YORGH4DDHLbu77P2Q3WQ40FygCI0xpj0xJjST8H9A2qugTZ3cwZqiFnDoHAACwdwwAAODKXLfW5JoXWoocci4NAACmYwAAALDVjW3RvD7n3LOxTmghp8jZBgAAeF2guotlvoi5FG/mNDaXAwCAu7OXXcjVianG0/rmF0Vz2q2ONbm2C4mcA+djAADA325CbZkpY95/x1iT80u2pjdm9/WHAAAArsTfH0s1LW+VMY/ht40ipypjD6b88vUvCtkNAABAHWvdrXKwVW8a2zhos+J26qIAAAC8no3ND8ia5FXO7GysY8przscAAAD87RLlkqIcbNWlztcO2kyd+w3IUiYAAMAxsA9t7oWH5dj5Hr6ZqdPKvPjPCAAAdaxNvnJ82zfnmFYyXVdSfgAAoI51166Ce9WjmtzrmDrHtJpduj9lMh8DAIA6doCIuthdj+3byEwAAIA6Nr4salSrY2vxcrHtVWvysz9lKk80I2M+BgAA2pEvdp/rdfuPmVKZn/0idaIOBQAA4IPTJ0r1Ute5WI5bW6pn6+N6OZWjHJ54kXM5gyQpD83ZDgAA+GjcFa512vJ6bBYbc2xw0qu96BCWawpUms4CAADA9c+EXCOuUMW0leV+J7IORm2zOT2bzxm98vic7QAAgI9OuQg9xMxYq41K2CPMV+dY96/likck5Yo+ZtqP6cQAAADTMX+0se8Nz3+w8aRtmo+lCrM5tuf7sR/LmQcAAHWsPa5C8r45DVtUjMdaTUNdMYuvWa4Y5di3NmB5umdXmgAAALbxw1MfTS4e3ev9KVnxO4wm5VSHsj56fi+aTedIUvYJNpUz/g1I2zXnwgAAYCu/y0cb+KN4DynZ3qOvNAEAAJy6jnkMplcuhULyvlK9Fl9iunj/8nFoEZKy2btjtttRZnbOTz3tTDkAAKDQdCh3H5Q+7xb4P+wHZ2tQAAAA7Vkzi/j7KUfuLwPGORqK+BbbqrqTuU9JMqVuzexUOQAAoOA/EuqhCXm/z/IYtAEAAK+fR7mNK/bpY3Qf9o0BAMDescO4CwAAgOnYYfzJ8ysBAADQDhhYub4JjQEAAKDpXwgVKGwAAIA6pkV/iXhy+epVS0TUc7Y6JzUjBQAAwHTM9U0MLwEAAOAvb8W65YWQFN5fO8dWAAAArOlX8VgSmtX1uvDYv3elAAAAOOjitZB3Ba8TAgAAoI5paeGDI/VDz4S0qDfOiaJzjXPS9LacX9Aj504AAGA65uM2BgAAAO/HWk/vx7i7LRpZWl3JipxuPJard46lnjOlaqYCOVcAAADTseiDn3Q6to4BAAD4eEhVKdYvbZ+ctPe2NOXW+Y+pRg4AANiTPzvXohQ80BIAAGA71wZL/XHlfM6EVMW0ATkAAOD4OrY0heT1nq8Ytagu57uYaWNpk20MAACAgy5CXnw3AAAA+MpN+F4OtYqcGGZElZPGcAwAANxaG5WsUCGiaFGj214sHEvaGAAAuLU2u69+WbEg9CkihqUuVuQkbQwAANyZj3pUi683Qp2o21iXUy0qpYw2BgAAbsunTnFdVOtzXPHWtrEP/ZKt3kCWekh9CAAA4Dr8WY8KSfJ+UbxsY0Wv876J+Ts5aYzGAADA7RT769suh7YuiienX0SV08/HZHUZYzZ2DwAAUMeKQrZoqMgJySVFP2KrC9modHnIpc+/eh8CAAC4Fi+24v8Rk2WsL3bR/+e8ePwBAAC4PFOpTRSoI3P+0x+/VWpybRNaTpfTpFO9HwAAsI2rtGjCgTm/BQAAcB+mW2vy7bOfk+U0STrZzwUAAOY1ATgnAADTMfrmcracLuEs7wcAADAdAwAAuLD/AQPLUxmjjeldAAAAAElFTkSuQmCC)

\------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-2ed21bb9-1b80-4d87-9194-841f899a6fe4@mhtml.blink @charset
"utf-8"; a { color: var(--link-color); } body { --background-color:
\#fff; --error-code-color: var(--google-gray-700); --google-blue-100:
rgb(210, 227, 252); --google-blue-300: rgb(138, 180, 248);
--google-blue-600: rgb(26, 115, 232); --google-blue-700: rgb(25, 103,
210); --google-gray-100: rgb(241, 243, 244); --google-gray-300: rgb(218,
220, 224); --google-gray-500: rgb(154, 160, 166); --google-gray-50:
rgb(248, 249, 250); --google-gray-600: rgb(128, 134, 139);
--google-gray-700: rgb(95, 99, 104); --google-gray-800: rgb(60, 64, 67);
--google-gray-900: rgb(32, 33, 36); --heading-color:
var(--google-gray-900); --link-color: rgb(88, 88, 88);
--popup-container-background-color: rgba(0,0,0,0.65);
--primary-button-fill-color-active: var(--google-blue-700);
--primary-button-fill-color: var(--google-blue-600);
--primary-button-text-color: \#fff; --quiet-background-color: rgb(247,
247, 247); --secondary-button-border-color: var(--google-gray-500);
--secondary-button-fill-color: \#fff;
--secondary-button-hover-border-color: var(--google-gray-600);
--secondary-button-hover-fill-color: var(--google-gray-50);
--secondary-button-text-color: var(--google-gray-700);
--small-link-color: var(--google-gray-700); --text-color:
var(--google-gray-700); background: var(--background-color); color:
var(--text-color); overflow-wrap: break-word; } .nav-wrapper
.secondary-button { background: var(--secondary-button-fill-color);
border: 1px solid var(--secondary-button-border-color); color:
var(--secondary-button-text-color); float: none; margin: 0px; padding:
8px 16px; } .hidden { display: none; } html { text-size-adjust: 100%;
font-size: 125%; } .icon { background-repeat: no-repeat;
background-size: 100%; } @media (prefers-color-scheme: dark) { body {
--background-color: var(--google-gray-900); --error-code-color:
var(--google-gray-500); --heading-color: var(--google-gray-500);
--link-color: var(--google-blue-300);
--primary-button-fill-color-active: rgb(129, 162, 208);
--primary-button-fill-color: var(--google-blue-300);
--primary-button-text-color: var(--google-gray-900);
--quiet-background-color: var(--background-color);
--secondary-button-border-color: var(--google-gray-700);
--secondary-button-fill-color: var(--google-gray-900);
--secondary-button-hover-fill-color: rgb(48, 51, 57);
--secondary-button-text-color: var(--google-blue-300);
--small-link-color: var(--google-blue-300); --text-color:
var(--google-gray-500); } }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-599515f8-ff77-46af-8eb1-69c938be5904@mhtml.blink @charset
"utf-8"; button { border: 0px; border-radius: 4px; box-sizing:
border-box; color: var(--primary-button-text-color); cursor: pointer;
float: right; font-size: 0.875em; margin: 0px; padding: 8px 16px;
transition: box-shadow 150ms cubic-bezier(0.4, 0, 0.2, 1) 0s;
user-select: none; } \[dir="rtl"\] button { float: left; } .bad-clock
button, .captive-portal button, .https-only button, .insecure-form
button, .lookalike-url button, .main-frame-blocked button, .neterror
button, .pdf button, .ssl button, .safe-browsing-billing button {
background: var(--primary-button-fill-color); } button:active {
background: var(--primary-button-fill-color-active); outline: 0px; }
\#debugging { display: inline; overflow: auto; } .debugging-content {
line-height: 1em; margin-bottom: 0px; margin-top: 1em; }
.debugging-content-fixed-width { display: block; font-family: monospace;
font-size: 1.2em; margin-top: 0.5em; } .debugging-title { font-weight:
bold; } \#details { margin: 0px 0px 50px; } \#details
p:not(:first-of-type) { margin-top: 20px; } .secondary-button:active {
border-color: white; box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px,
rgba(60, 64, 67, 0.15) 0px 2px 6px 2px; } .secondary-button:hover {
background: var(--secondary-button-hover-fill-color); border-color:
var(--secondary-button-hover-border-color); text-decoration: none; }
.error-code { color: var(--error-code-color); font-size: 0.8em;
margin-top: 12px; text-transform: uppercase; } \#error-debugging-info {
font-size: 0.8em; } h1 { color: var(--heading-color); font-size: 1.6em;
font-weight: normal; line-height: 1.25em; margin-bottom: 16px; } h2 {
font-size: 1.2em; font-weight: normal; } .icon { height: 72px; margin:
0px 0px 40px; width: 72px; } input\[type="checkbox"\] { opacity: 0; }
input\[type="checkbox"\]:focus \~ .checkbox::after { outline:
-webkit-focus-ring-color auto 5px; } .interstitial-wrapper { box-sizing:
border-box; font-size: 1em; line-height: 1.6em; margin: 14vh auto 0px;
max-width: 600px; width: 100%; } \#main-message \> p { display: inline;
} \#extended-reporting-opt-in { font-size: 0.875em; margin-top: 32px; }
\#extended-reporting-opt-in label { display: grid;
grid-template-columns: 1.8em 1fr; position: relative; }
\#enhanced-protection-message { border-radius: 4px; font-size: 1em;
margin-top: 32px; padding: 10px 5px; } \#enhanced-protection-message
label { display: grid; grid-template-columns: 2.5em 1fr; position:
relative; } \#enhanced-protection-message div { margin: 0.5em; }
\#enhanced-protection-message .icon { height: 1.5em; vertical-align:
middle; width: 1.5em; } .nav-wrapper { margin-top: 51px; }
.nav-wrapper::after { clear: both; content: ""; display: table; width:
100%; } .small-link { color: var(--small-link-color); font-size:
0.875em; } .checkboxes { flex: 0 0 24px; } .checkbox { --padding: 0.9em;
background: transparent; display: block; height: 1em; left: -1em;
padding-inline-start: var(--padding); position: absolute; right: 0px;
top: -0.5em; width: 1em; } .checkbox::after { border: 1px solid white;
border-radius: 2px; content: ""; height: 1em; left: var(--padding);
position: absolute; top: var(--padding); width: 1em; } .checkbox::before
{ background: transparent; border-width: 0px 2px 2px; border-style:
solid; border-color: white; border-image: initial;
border-inline-end-width: 0px; content: ""; height: 0.2em; left:
calc(0.3em + var(--padding)); opacity: 0; position: absolute; top:
calc(0.3em + var(--padding)); transform: rotate(-45deg); width: 0.5em; }
input\[type="checkbox"\]:checked \~ .checkbox::before { opacity: 1; }
\#recurrent-error-message { background: rgb(237, 237, 237);
border-radius: 4px; margin-bottom: 16px; margin-top: 12px; padding: 12px
16px; } .showing-recurrent-error-message \#extended-reporting-opt-in {
margin-top: 16px; } .showing-recurrent-error-message
\#enhanced-protection-message { margin-top: 16px; } @media (max-width:
700px) { .interstitial-wrapper { padding: 0px 10%; }
\#error-debugging-info { overflow: auto; } } @media (max-width: 420px) {
button, \[dir="rtl"\] button, .small-link { float: none; font-size:
0.825em; font-weight: 500; margin: 0px; width: 100%; } button { padding:
16px 24px; } \#details { margin: 20px 0px; } \#details
p:not(:first-of-type) { margin-top: 10px; }
.secondary-button:not(.hidden) { display: block; margin-top: 20px;
text-align: center; width: 100%; } .interstitial-wrapper { padding: 0px
5%; } \#extended-reporting-opt-in { margin-top: 24px; }
\#enhanced-protection-message { margin-top: 24px; } .nav-wrapper {
margin-top: 30px; } } @media (max-width: 420px) { .nav-wrapper
.secondary-button { border: 0px; margin: 16px 0px 0px;
margin-inline-end: 0px; padding-bottom: 16px; padding-top: 16px; } }
@media (min-width: 240px) and (max-width: 420px) and (min-height:
401px), (min-width: 421px) and (min-height: 240px) and (max-height:
560px) { body .nav-wrapper { background: var(--background-color);
bottom: 0px; box-shadow: 0 -12px 24px var(--background-color); left:
0px; margin: 0px auto; max-width: 736px; padding-inline: 24px; position:
fixed; right: 0px; width: 100%; z-index: 2; } .interstitial-wrapper {
max-width: 736px; } \#details, \#main-content { padding-bottom: 40px; }
\#details { padding-top: 5.5vh; } button.small-link { color:
var(--google-blue-600); } } @media (max-width: 420px) and (orientation:
portrait), (max-height: 560px) { body { margin: 0px auto; } button,
\[dir="rtl"\] button, button.small-link, .nav-wrapper .secondary-button
{ font-family: Roboto-Regular, Helvetica; font-size: 0.933em; margin:
6px 0px; transform: translateZ(0px); } .nav-wrapper { box-sizing:
border-box; padding-bottom: 8px; width: 100%; } \#details { box-sizing:
border-box; height: auto; margin: 0px; opacity: 1; transition: opacity
250ms cubic-bezier(0.4, 0, 0.2, 1) 0s; } \#details.hidden,
\#main-content.hidden { height: 0px; opacity: 0; overflow: hidden;
padding-bottom: 0px; transition: none 0s ease 0s; } h1 { font-size:
1.5em; margin-bottom: 8px; } .icon { margin-bottom: 5.69vh; }
.interstitial-wrapper { box-sizing: border-box; margin: 7vh auto 12px;
padding: 0px 24px; position: relative; } .interstitial-wrapper p {
font-size: 0.95em; line-height: 1.61em; margin-top: 8px; }
\#main-content { margin: 0px; transition: opacity 100ms
cubic-bezier(0.4, 0, 0.2, 1) 0s; } .small-link { border: 0px; }
.suggested-left \> \#control-buttons, .suggested-right \>
\#control-buttons { float: none; margin: 0px; } } @media (min-width:
421px) and (min-height: 500px) and (max-height: 560px) {
.interstitial-wrapper { margin-top: 10vh; } } @media (min-height: 400px)
and (orientation: portrait) { .interstitial-wrapper { margin-bottom:
145px; } } @media (min-height: 299px) { .nav-wrapper { padding-bottom:
16px; } } @media (max-height: 560px) and (min-height: 240px) and
(orientation: landscape) { .extended-reporting-has-checkbox \#details {
padding-bottom: 80px; } } @media (min-height: 500px) and (max-height:
650px) and (max-width: 414px) and (orientation: portrait) {
.interstitial-wrapper { margin-top: 7vh; } } @media (min-height: 650px)
and (max-width: 414px) and (orientation: portrait) {
.interstitial-wrapper { margin-top: 10vh; } } @media (max-height: 400px)
and (orientation: portrait), (max-height: 239px) and (orientation:
landscape), (max-width: 419px) and (max-height: 399px) {
.interstitial-wrapper { display: flex; flex-direction: column;
margin-bottom: 0px; } \#details { flex: 1 1 auto; order: 0; }
\#main-content { flex: 1 1 auto; order: 0; } .nav-wrapper { flex: 0 1
auto; margin-top: 8px; order: 1; padding-inline: 0px; position:
relative; width: 100%; } button, .nav-wrapper .secondary-button {
padding: 16px 24px; } button.small-link { color: var(--google-blue-600);
} } @media (max-width: 239px) and (orientation: portrait) { .nav-wrapper
{ padding-inline: 0px; } }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/css Content-Transfer-Encoding: binary
Content-Location:
cid:css-1e20ce6a-0894-4162-9f49-ace25f0f1bad@mhtml.blink @charset
"utf-8"; html\[subframe\] \#main-frame-error { display: none; }
html:not(\[subframe\]) \#sub-frame-error { display: none; } h1 {
margin-top: 0px; overflow-wrap: break-word; } h1 span { font-weight:
500; } a { text-decoration: none; } .icon { user-select: none; display:
inline-block; } .icon-generic { content:
-webkit-image-set(url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEgAAABIAQMAAABvIyEEAAAABlBMVEUAAABTU1OoaSf/AAAAAXRSTlMAQObYZgAAAENJREFUeF7tzbEJACEQRNGBLeAasBCza2lLEGx0CxFGG9hBMDDxRy/72O9FMnIFapGylsu1fgoBdkXfUHLrQgdfrlJN1BdYBjQQm3UAAAAASUVORK5CYII=")
1x,
url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJAAAACQAQMAAADdiHD7AAAABlBMVEUAAABTU1OoaSf/AAAAAXRSTlMAQObYZgAAAFJJREFUeF7t0cENgDAMQ9FwYgxG6WjpaIzCCAxQxVggFuDiCvlLOeRdHR9yzjncHVoq3npu+wQUrUuJHylSTmBaespJyJQoObUeyxDQb3bEm5Au81c0pSCD8HYAAAAASUVORK5CYII=")
2x); } .icon-offline { content:
-webkit-image-set(url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEgAAABIAQMAAABvIyEEAAAABlBMVEUAAABTU1OoaSf/AAAAAXRSTlMAQObYZgAAAGxJREFUeF7tyMEJwkAQRuFf5ipMKxYQiJ3Z2nSwrWwBA0+DQZcdxEOueaePp9+dQZFB7GpUcURSVU66yVNFj6LFICatThZB6r/ko/pbRpUgilY0Cbw5sNmb9txGXUKyuH7eV25x39DtJXUNPQGJtWFV+BT/QAAAAABJRU5ErkJggg==")
1x,
url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJAAAACQBAMAAAAVaP+LAAAAGFBMVEUAAABTU1NNTU1TU1NPT09SUlJSUlJTU1O8B7DEAAAAB3RSTlMAoArVKvVgBuEdKgAAAJ1JREFUeF7t1TEOwyAMQNG0Q6/UE+RMXD9d/tC6womIFSL9P+MnAYOXeTIzMzMzMzMzaz8J9Ri6HoITmuHXhISE8nEh9yxDh55aCEUoTGbbQwjqHwIkRAEiIaG0+0AA9VBMaE89Rogeoww936MQrWdBr4GN/z0IAdQ6nQ/FIpRXDwHcA+JIJcQowQAlFUA0MfQpXLlVQfkzR4igS6ENjknm/wiaGhsAAAAASUVORK5CYII=")
2x); position: relative; } .icon-disabled { content:
-webkit-image-set(url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHAAAABICAMAAAAZF4G5AAAABlBMVEVMaXFTU1OXUj8tAAAAAXRSTlMAQObYZgAAASZJREFUeAHd11Fq7jAMRGGf/W/6PoWB67YMqv5DybwG/CFjRuR8JBw3+ByiRjgV9W/TJ31P0tBfC6+cj1haUFXKHmVJo5wP98WwQ0ZCbfUc6LQ6VuUBz31ikADkLMkDrfUC4rR6QGW+gF6rx7NaHWCj1Y/W6lf4L7utvgBSt3rBFSS/XBMPUILcJINHCBWYUfpWn4NBi1ZfudIc3rf6/NGEvEA+AsYTJozmXemjXeLZAov+mnkN2HfzXpMSVQDnGw++57qNJ4D1xitA2sJ+VAWMygSEaYf2mYPTjZfk2K8wmP7HLIH5Mg4/pP+PEcDzUvDMvYbs/2NWwPO5vBdMZE4EE5UTQLiBFDaUlTDPBRoJ9HdAYIkIo06og3BNXtCzy7zA1aXk5x+tJARq63eAygAAAABJRU5ErkJggg==")
1x,
url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOAAAACQAQMAAAArwfVjAAAABlBMVEVMaXFTU1OXUj8tAAAAAXRSTlMAQObYZgAAAYdJREFUeF7F1EFqwzAUBNARAmVj0FZe5QoBH6BX+dn4GlY2PYNzGx/A0CvkCIJuvIraKJKbgBvzf2g62weDGD7CYggpfFReis4J0ey9EGFIiEQQojFSlA9kSIiqd0KkFjKsewgRbStEN19mxUPTtmW9HQ/h6tyqNQ8NlSMZdzyE6qkoE0trVYGFm0n1WYeBhduzwbwBC7voS+vIxfeMjeaiLxsMMtQNwMPtuew+DjzcTHk8YMfDknEcIUOtf2lVfgVH3K4Xv5PRYAXRVMtItIJ3rfaCIVn9DsTH2NxisAVRex2Hh3hX+/mRUR08bAwPEYsI51ZxWH4Q0SpicQRXeyEaIug48FEdegARfMz/tADVsRciwTAxW308ehmC2gLraC+YCbV3QoTZexa+zegAEW5PhhgYfmbvJgcRqngGByOSXdFJcLk2JeDPEN0kxe1JhIt5FiFA+w+ItMELsUyPF2IaJ4aILqb4FbxPwhImwj6JauKgDUCYaxmYIsd4KXdMjIC9ItB5Bn4BNRwsG0XM2nwAAAAASUVORK5CYII=")
2x); width: 112px; } .hidden { display: none; } \#suggestions-list a {
color: var(--google-blue-600); } \#suggestions-list p {
margin-block-end: 0px; } \#suggestions-list ul { margin-top: 0px; }
.single-suggestion { list-style-type: none; padding-inline-start: 0px; }
\#error-information-button { content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBmaWxsPSJub25lIiBkPSJNMCAwaDI0djI0SDB6Ii8+PHBhdGggZD0iTTExIDE4aDJ2LTJoLTJ2MnptMS0xNkM2LjQ4IDIgMiA2LjQ4IDIgMTJzNC40OCAxMCAxMCAxMCAxMC00LjQ4IDEwLTEwUzE3LjUyIDIgMTIgMnptMCAxOGMtNC40MSAwLTgtMy41OS04LThzMy41OS04IDgtOCA4IDMuNTkgOCA4LTMuNTkgOC04IDh6bTAtMTRjLTIuMjEgMC00IDEuNzktNCA0aDJjMC0xLjEuOS0yIDItMnMyIC45IDIgMmMwIDItMyAxLjc1LTMgNWgyYzAtMi4yNSAzLTIuNSAzLTUgMC0yLjIxLTEuNzktNC00LTR6Ii8+PC9zdmc+");
height: 24px; vertical-align: -0.15em; width: 24px; }
.use-popup-container\#error-information-popup-container
\#error-information-popup { align-items: center; background-color:
var(--popup-container-background-color); display: flex; height: 100%;
left: 0px; position: fixed; top: 0px; width: 100%; z-index: 100; }
.use-popup-container\#error-information-popup-container
\#error-information-popup-content \> p { margin-bottom: 11px;
margin-inline-start: 20px; }
.use-popup-container\#error-information-popup-container
\#suggestions-list ul { margin-inline-start: 15px; }
.use-popup-container\#error-information-popup-container
\#error-information-popup-box { background-color:
var(--background-color); left: 5%; padding-bottom: 15px; padding-top:
15px; position: fixed; width: 90%; z-index: 101; }
.use-popup-container\#error-information-popup-container div.error-code {
margin-inline-start: 20px; }
.use-popup-container\#error-information-popup-container
\#suggestions-list p { margin-inline-start: 20px; }
:not(.use-popup-container)\#error-information-popup-container
\#error-information-popup-close { display: none; }
\#error-information-popup-close { margin-bottom: 0px; margin-inline-end:
35px; margin-top: 15px; text-align: end; } .link-button { color: rgb(66,
133, 244); display: inline-block; font-weight: bold; text-transform:
uppercase; } \#sub-frame-error-details { color: rgb(143, 143, 143); }
\[jscontent="hostName"\], \[jscontent="failedUrl"\] { overflow-wrap:
break-word; } .secondary-button { background: rgb(217, 217, 217); color:
rgb(105, 105, 105); margin-inline-end: 16px; } .snackbar { background:
rgb(50, 50, 50); border-radius: 2px; bottom: 24px; box-sizing:
border-box; color: rgb(255, 255, 255); font-size: 0.87em; left: 24px;
max-width: 568px; min-width: 288px; opacity: 0; padding: 16px 24px 12px;
position: fixed; transform: translateY(90px); will-change: opacity,
transform; z-index: 999; } .snackbar-show { animation: 250ms
cubic-bezier(0, 0, 0.2, 1) 0s 1 normal forwards running show-snackbar,
250ms cubic-bezier(0.4, 0, 1, 1) 5s 1 normal forwards running
hide-snackbar; } @-webkit-keyframes show-snackbar { 100% { opacity: 1;
transform: translateY(0px); } } @-webkit-keyframes hide-snackbar { 0% {
opacity: 1; transform: translateY(0px); } 100% { opacity: 0; transform:
translateY(90px); } } .suggestions { margin-top: 18px; }
.suggestion-header { font-weight: bold; margin-bottom: 4px; }
.suggestion-body { color: rgb(119, 119, 119); } @media (max-width:
640px), (max-height: 640px) { h1 { margin: 0px 0px 15px; } .suggestions
{ margin-top: 10px; } .suggestion-header { margin-bottom: 0px; } }
\#download-link, \#download-link-clicked { margin-bottom: 30px;
margin-top: 30px; } \#download-link-clicked { color: rgb(187, 187, 187);
} \#download-link::before, \#download-link-clicked::before { content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxLjJlbSIgaGVpZ2h0PSIxLjJlbSIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNNSAyMGgxNHYtMkg1bTE0LTloLTRWM0g5djZINWw3IDcgNy03eiIgZmlsbD0iIzQyODVGNCIvPjwvc3ZnPg==");
display: inline-block; margin-inline-end: 4px; vertical-align:
-webkit-baseline-middle; } \#download-link-clicked::before { opacity: 0;
width: 0px; } \#offline-content-list-visibility-card { border: 1px solid
white; border-radius: 8px; display: flex; font-size: 0.8em;
justify-content: space-between; line-height: 1; }
\#offline-content-list.list-hidden
\#offline-content-list-visibility-card { border-color: rgb(218, 220,
224); } \#offline-content-list-visibility-card \> div { padding: 1em; }
\#offline-content-list-title { color: var(--google-gray-700); }
\#offline-content-list-show-text, \#offline-content-list-hide-text {
color: rgb(66, 133, 244); } \#offline-content-list.list-hidden
\#offline-content-list-hide-text,
\#offline-content-list:not(.list-hidden)
\#offline-content-list-show-text { display: none; }
\#offline-content-suggestions { max-height: 27em; transition: max-height
200ms ease-in 0s, visibility 0s ease 200ms, opacity 200ms linear 200ms;
} \#offline-content-list.list-hidden \#offline-content-suggestions {
max-height: 0px; opacity: 0; transition: opacity 200ms linear 0s,
visibility 0s ease 200ms, max-height 200ms ease-out 200ms; visibility:
hidden; } \#offline-content-list { margin-inline-start: -5%; width:
110%; } @media (max-width: 420px) { \#offline-content-list {
margin-inline-start: -2.5%; width: 105%; } } @media (max-width: 420px)
and (orientation: portrait), (max-height: 560px) {
\#offline-content-list { margin-inline-start: -12px; width: calc(100% +
24px); } } .suggestion-with-image .offline-content-suggestion-thumbnail
{ flex-basis: 8.2em; flex-shrink: 0; } .suggestion-with-image
.offline-content-suggestion-thumbnail \> img { height: 100%; width:
100%; } .suggestion-with-image \#offline-content-list:not(.is-rtl)
.offline-content-suggestion-thumbnail \> img {
border-bottom-right-radius: 7px; border-top-right-radius: 7px; }
.suggestion-with-image \#offline-content-list.is-rtl
.offline-content-suggestion-thumbnail \> img {
border-bottom-left-radius: 7px; border-top-left-radius: 7px; }
.suggestion-with-icon .offline-content-suggestion-thumbnail {
align-items: center; display: flex; justify-content: center; min-height:
4.2em; min-width: 4.2em; } .suggestion-with-icon
.offline-content-suggestion-thumbnail \> div { align-items: center;
background-color: rgb(241, 243, 244); border-radius: 50%; display: flex;
height: 2.3em; justify-content: center; width: 2.3em; }
.suggestion-with-icon .offline-content-suggestion-thumbnail \> div \>
img { height: 1.45em; width: 1.45em; }
.offline-content-suggestion-favicon { height: 1em; margin-inline-end:
0.4em; width: 1.4em; } .offline-content-suggestion-favicon \> img {
height: 1.4em; width: 1.4em; } .no-favicon
.offline-content-suggestion-favicon { display: none; } .image-video {
content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTcgMTAuNVY3YTEgMSAwIDAgMC0xLTFINGExIDEgMCAwIDAtMSAxdjEwYTEgMSAwIDAgMCAxIDFoMTJhMSAxIDAgMCAwIDEtMXYtMy41bDQgNHYtMTFsLTQgNHoiIGZpbGw9IiMzQzQwNDMiLz48L3N2Zz4=");
} .image-music-note { content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTIgM3Y5LjI2Yy0uNS0uMTctMS0uMjYtMS41LS4yNkM4IDEyIDYgMTQgNiAxNi41UzggMjEgMTAuNSAyMXM0LjUtMiA0LjUtNC41VjZoNFYzaC03eiIgZmlsbD0iIzNDNDA0MyIvPjwvc3ZnPg==");
} .image-earth { content:
url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMTIgMmM1LjUyIDAgMTAgNC40OCAxMCAxMHMtNC40OCAxMC0xMCAxMFMyIDE3LjUyIDIgMTIgNi40OCAyIDEyIDJ6TTQgMTJoNC40YzMuNDA3LjAyMiA0LjkyMiAxLjczIDQuNTQzIDUuMTI3SDkuNDg4djIuNDdhOC4wMDQgOC4wMDQgMCAwIDAgMTAuNDk4LTguMDgzQzE5LjMyNyAxMi41MDQgMTguMzMyIDEzIDE3IDEzYy0yLjEzNyAwLTMuMjA2LS45MTYtMy4yMDYtMi43NWgtMy43NDhjLS4yNzQtMi43MjguNjgzLTQuMDkyIDIuODctNC4wOTIgMC0uOTc1LjMyNy0xLjU5Ny44MTEtMS45N0E4LjAwNCA4LjAwNCAwIDAgMCA0IDEyeiIgZmlsbD0iIzNDNDA0MyIvPjwvc3ZnPg==");
} .image-file { content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTMgOVYzLjVMMTguNSA5TTYgMmMtMS4xMSAwLTIgLjg5LTIgMnYxNmEyIDIgMCAwIDAgMiAyaDEyYTIgMiAwIDAgMCAyLTJWOGwtNi02SDZ6IiBmaWxsPSIjM0M0MDQzIi8+PC9zdmc+");
} .offline-content-suggestion-texts { display: flex; flex-direction:
column; justify-content: space-between; line-height: 1.3; padding:
0.9em; width: 100%; } .offline-content-suggestion-title {
-webkit-box-orient: vertical; -webkit-line-clamp: 3; color: rgb(32, 33,
36); display: -webkit-box; font-size: 1.1em; overflow: hidden;
text-overflow: ellipsis; } div.offline-content-suggestion { align-items:
stretch; border: 1px solid rgb(218, 220, 224); border-radius: 8px;
display: flex; justify-content: space-between; margin-bottom: 0.8em; }
.suggestion-with-image { flex-direction: row; height: 8.2em; max-height:
8.2em; } .suggestion-with-icon { flex-direction: row-reverse; height:
4.2em; max-height: 4.2em; } .suggestion-with-icon
.offline-content-suggestion-title { -webkit-line-clamp: 1; word-break:
break-all; } .suggestion-with-icon .offline-content-suggestion-texts {
padding-inline-start: 0px; }
.offline-content-suggestion-attribution-freshness { color: rgb(95, 99,
104); display: flex; font-size: 0.8em; line-height: 1.7em; }
.offline-content-suggestion-attribution { -webkit-box-orient: vertical;
-webkit-line-clamp: 1; display: -webkit-box; flex-shrink: 1;
margin-inline-end: 0.3em; overflow: hidden; overflow-wrap: break-word;
text-overflow: ellipsis; word-break: break-all; } .no-attribution
.offline-content-suggestion-attribution { display: none; }
.offline-content-suggestion-freshness::before { content: "-"; display:
inline-block; flex-shrink: 0; margin-inline: 0.1em; } .no-attribution
.offline-content-suggestion-freshness::before { display: none; }
.offline-content-suggestion-freshness { flex-shrink: 0; }
.suggestion-with-image .offline-content-suggestion-pin-spacer {
flex-grow: 100; flex-shrink: 1; } .suggestion-with-image
.offline-content-suggestion-pin { content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCI+PGRlZnM+PHBhdGggaWQ9ImEiIGQ9Ik0wIDBoMjR2MjRIMFYweiIvPjwvZGVmcz48Y2xpcFBhdGggaWQ9ImIiPjx1c2UgeGxpbms6aHJlZj0iI2EiIG92ZXJmbG93PSJ2aXNpYmxlIi8+PC9jbGlwUGF0aD48cGF0aCBjbGlwLXBhdGg9InVybCgjYikiIGQ9Ik0xMiAyQzYuNSAyIDIgNi41IDIgMTJzNC41IDEwIDEwIDEwIDEwLTQuNSAxMC0xMFMxNy41IDIgMTIgMnptNSAxNkg3di0yaDEwdjJ6bS02LjctNEw3IDEwLjdsMS40LTEuNCAxLjkgMS45IDUuMy01LjNMMTcgNy4zIDEwLjMgMTR6IiBmaWxsPSIjOUFBMEE2Ii8+PC9zdmc+");
flex-shrink: 0; height: 1.4em; margin-inline-start: 0.4em; width: 1.4em;
} \#offline-content-list-action { text-align: center; transition:
visibility 0s ease 200ms, opacity 200ms linear 200ms; }
\#offline-content-list.list-hidden \#offline-content-list-action {
opacity: 0; transition: opacity 200ms linear 0s, visibility 0s ease
200ms; visibility: hidden; } \#cancel-save-page-button {
background-image:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48Y2xpcFBhdGggaWQ9Im1hc2siPjxwYXRoIGQ9Ik0xMiAyQzYuNSAyIDIgNi41IDIgMTJzNC41IDEwIDEwIDEwIDEwLTQuNSAxMC0xMFMxNy41IDIgMTIgMnptNSAxNkg3di0yaDEwdjJ6bS02LjctNEw3IDEwLjdsMS40LTEuNCAxLjkgMS45IDUuMy01LjNMMTcgNy4zIDEwLjMgMTR6IiBmaWxsPSIjOUFBMEE2Ii8+PC9jbGlwUGF0aD48cGF0aCBjbGlwLXBhdGg9InVybCgjbWFzaykiIGZpbGw9IiM5QUEwQTYiIGQ9Ik0wIDBoMjR2MjRIMHoiLz48cGF0aCBjbGlwLXBhdGg9InVybCgjbWFzaykiIGZpbGw9IiMxQTczRTgiIHN0eWxlPSJhbmltYXRpb246b2ZmbGluZUFuaW1hdGlvbiA0cyBpbmZpbml0ZSIgZD0iTTAgMGgyNHYyNEgweiIvPjxzdHlsZT5Aa2V5ZnJhbWVzIG9mZmxpbmVBbmltYXRpb257MCUsMzUle2hlaWdodDowfTYwJXtoZWlnaHQ6MTAwJX05MCV7ZmlsbC1vcGFjaXR5OjF9dG97ZmlsbC1vcGFjaXR5OjB9fTwvc3R5bGU+PC9zdmc+");
background-position: right 27px center; background-repeat: no-repeat;
border: 1px solid var(--google-gray-300); border-radius: 5px; color:
var(--google-gray-700); margin-bottom: 26px; padding-bottom: 16px;
padding-inline: 16px 88px; padding-top: 16px; text-align: start; }
html\[dir="rtl"\] \#cancel-save-page-button { background-position: left
27px center; } \#save-page-for-later-button { display: flex;
justify-content: start; } \#save-page-for-later-button a::before {
content:
url("data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxLjJlbSIgaGVpZ2h0PSIxLjJlbSIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNNSAyMGgxNHYtMkg1bTE0LTloLTRWM0g5djZINWw3IDcgNy03eiIgZmlsbD0iIzQyODVGNCIvPjwvc3ZnPg==");
display: inline-block; margin-inline-end: 4px; vertical-align:
-webkit-baseline-middle; } .hidden\#save-page-for-later-button {
display: none; } html\[subframe\] body { overflow: hidden; }
\#sub-frame-error { align-items: center; flex-flow: column;
justify-content: center; background-color: rgb(221, 221, 221); display:
-webkit-flex; height: 100%; left: 0px; position: absolute; text-align:
center; top: 0px; transition: background-color 200ms ease-in-out 0s;
width: 100%; } \#sub-frame-error:hover { background-color: rgb(238, 238,
238); } \#sub-frame-error .icon-generic { margin: 0px 0px 16px; }
\#sub-frame-error-details { margin: 0px 10px; text-align: center;
visibility: hidden; } \#sub-frame-error:hover \#sub-frame-error-details
{ visibility: visible; } @media (max-width: 200px), (max-height: 95px) {
\#sub-frame-error-details { display: none; } } @media (max-height:
100px) { \#sub-frame-error .icon-generic { height: auto; margin: 0px;
padding-top: 0px; width: 25px; } } \#details-button { box-shadow: none;
min-width: 0px; } .suggested-left \> \#control-buttons, .suggested-right
\> \#details-button { float: left; } .suggested-right \>
\#control-buttons, .suggested-left \> \#details-button { float: right; }
.suggested-left .secondary-button { margin-inline: 16px 0px; }
\#details-button.singular { float: none; } \#download-button {
padding-bottom: 4px; padding-top: 4px; position: relative; }
\#download-button::before { background:
-webkit-image-set(url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAQAAABKfvVzAAAAO0lEQVQ4y2NgGArgPxIY1YChsOE/LtBAmpYG0mxpIOSDBpKUo2lpIDZxNJCkHKqlYZAla3RAHQ1DFgAARRroHyLNTwwAAAAASUVORK5CYII=")
1x,
url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAQAAAD9CzEMAAAAZElEQVRYw+3Ruw3AMAwDUY3OzZUmRRD4E9iim9wNwAdbEURHyk4AAAAATiCVK8lLyPsKeT9K3lsownnunfkPxO78hKiYHxBV8x2icr5BVM+/CMf8g3DN34Rzns6ViwHUAUQ/6wIAd5Km7l6c8AAAAABJRU5ErkJggg==")
2x) no-repeat; content: ""; display: inline-block; height: 24px;
margin-inline: -4px 4px; vertical-align: middle; width: 24px; }
\#download-button:disabled { background: rgb(180, 206, 249); color:
rgb(255, 255, 255); } \#buttons::after { clear: both; content: "";
display: block; width: 100%; } html\[dir="rtl"\] .runner-container,
html\[dir="rtl"\].offline .icon-offline { transform: scaleX(-1); }
.offline { transition: filter 1.5s cubic-bezier(0.65, 0.05, 0.36, 1) 0s,
background-color 1.5s cubic-bezier(0.65, 0.05, 0.36, 1) 0s; will-change:
filter, background-color; } .offline body { transition: background-color
1.5s cubic-bezier(0.65, 0.05, 0.36, 1) 0s; } .offline \#main-message \>
p { display: none; } .offline.inverted { background-color: rgb(255, 255,
255); filter: invert(1); } .offline.inverted body { background-color:
rgb(255, 255, 255); } .offline .interstitial-wrapper { color:
var(--text-color); font-size: 1em; line-height: 1.55; margin: 0px auto;
max-width: 600px; padding-top: 100px; position: relative; width: 100%; }
.offline .runner-container { direction: ltr; height: 150px; max-width:
600px; overflow: hidden; position: absolute; top: 35px; width: 44px; }
.offline .runner-container:focus { outline: none; } .offline
.runner-container:focus-visible { outline: 3px solid
var(--google-blue-300); } .offline .runner-canvas { height: 150px;
max-width: 600px; opacity: 1; overflow: hidden; position: absolute; top:
0px; z-index: 10; } .offline .controller { height: 100vh; left: 0px;
position: absolute; top: 0px; width: 100vw; z-index: 9; }
\#offline-resources { display: none; } \#offline-instruction {
image-rendering: pixelated; left: 0px; margin: auto; position: absolute;
right: 0px; top: 60px; width: fit-content; } .offline-runner-live-region
{ bottom: 0px; clip-path: polygon(0px 0px, 0px 0px, 0px 0px); color:
var(--background-color); display: block; font-size: xx-small; overflow:
hidden; position: absolute; text-align: center; transition: color 1.5s
cubic-bezier(0.65, 0.05, 0.36, 1) 0s; user-select: none; }
.slow-speed-option { align-items: center; background:
var(--google-gray-50); border-radius: 24px / 50%; bottom: 0px; color:
var(--error-code-color); display: inline-flex; font-size: 1em; left:
0px; line-height: 1.1em; margin: 5px auto; padding: 2px 12px 3px 20px;
position: absolute; right: 0px; width: max-content; z-index: 999; }
.slow-speed-option.hidden { display: none; } .slow-speed-option
\[type="checkbox"\] { opacity: 0; pointer-events: none; position:
absolute; } .slow-speed-option .slow-speed-toggle { cursor: pointer;
margin-inline-start: 8px; padding: 8px 4px; position: relative; }
.slow-speed-option \[type="checkbox"\]:disabled \~ .slow-speed-toggle {
cursor: default; } .slow-speed-option-label \[type="checkbox"\] {
opacity: 0; pointer-events: none; position: absolute; }
.slow-speed-option .slow-speed-toggle::before, .slow-speed-option
.slow-speed-toggle::after { content: ""; display: block; margin: 0px
3px; transition: all 100ms cubic-bezier(0.4, 0, 1, 1) 0s; }
.slow-speed-option .slow-speed-toggle::before { background: rgb(189,
193, 198); border-radius: 0.65em; height: 0.9em; width: 2em; }
.slow-speed-option .slow-speed-toggle::after { background: rgb(255, 255,
255); border-radius: 50%; box-shadow: rgba(0, 0, 0, 0.4) 0px 1px 3px
0px; height: 1.2em; position: absolute; top: 51%; transform:
translate(-20%, -50%); width: 1.1em; } .slow-speed-option
\[type="checkbox"\]:focus + .slow-speed-toggle { box-shadow: rgb(94,
158, 214) 0px 0px 8px; outline: rgb(93, 157, 213) solid 1px; }
.slow-speed-option \[type="checkbox"\]:checked +
.slow-speed-toggle::before { background: var(--google-blue-600);
opacity: 0.5; } .slow-speed-option \[type="checkbox"\]:checked +
.slow-speed-toggle::after { background: var(--google-blue-600);
transform: translate(calc(2em - 90%), -50%); } .slow-speed-option
\[type="checkbox"\]:checked:disabled + .slow-speed-toggle::before {
background: rgb(189, 193, 198); } .slow-speed-option
\[type="checkbox"\]:checked:disabled + .slow-speed-toggle::after {
background: var(--google-gray-50); } @media (max-width: 420px) {
\#download-button { padding-bottom: 12px; padding-top: 12px; }
.suggested-left \> \#control-buttons, .suggested-right \>
\#control-buttons { float: none; } .snackbar { border-radius: 0px;
bottom: 0px; left: 0px; width: 100%; } } @media (max-height: 350px) { h1
{ margin: 0px 0px 15px; } .icon-offline { margin: 0px 0px 10px; }
.interstitial-wrapper { margin-top: 5%; } .nav-wrapper { margin-top:
30px; } } @media (min-width: 420px) and (max-width: 736px) and
(min-height: 240px) and (max-height: 420px) and (orientation: landscape)
{ .interstitial-wrapper { margin-bottom: 100px; } } @media (max-width:
360px) and (max-height: 480px) { .offline .interstitial-wrapper {
padding-top: 60px; } .offline .runner-container { top: 8px; } } @media
(min-height: 240px) and (orientation: landscape) { .offline
.interstitial-wrapper { margin-bottom: 90px; } .icon-offline {
margin-bottom: 20px; } } @media (max-height: 320px) and (orientation:
landscape) { .icon-offline { margin-bottom: 0px; } .offline
.runner-container { top: 10px; } } @media (max-width: 240px) { button {
padding-inline: 12px; } .interstitial-wrapper { overflow: inherit;
padding: 0px 8px; } } @media (max-width: 120px) { button { width: auto;
} } .arcade-mode, .arcade-mode .runner-container, .arcade-mode
.runner-canvas { image-rendering: pixelated; max-width: 100%; overflow:
hidden; } .arcade-mode \#buttons, .arcade-mode \#main-content { opacity:
0; overflow: hidden; } .arcade-mode .interstitial-wrapper { height:
100vh; max-width: 100%; overflow: hidden; } .arcade-mode
.runner-container { left: 0px; margin: auto; right: 0px;
transform-origin: center top; transition: transform 250ms
cubic-bezier(0.4, 0, 1, 1) 400ms; z-index: 2; } @media
(prefers-color-scheme: dark) { .icon { filter: invert(1); } .offline
.runner-canvas { filter: invert(1); } .offline.inverted {
background-color: var(--background-color); filter: invert(0); }
.offline.inverted body { background-color: rgb(255, 255, 255); }
.offline.inverted .offline-runner-live-region { color: rgb(255, 255,
255); } \#suggestions-list a { color: var(--link-color); }
\#error-information-button { filter: invert(0.6); } .slow-speed-option {
background: var(--google-gray-800); color: var(--google-gray-100); }
.slow-speed-option .slow-speed-toggle::before, .slow-speed-option
\[type="checkbox"\]:checked:disabled + .slow-speed-toggle::before {
background: rgb(189, 193, 198); } .slow-speed-option
\[type="checkbox"\]:checked + .slow-speed-toggle::after,
.slow-speed-option \[type="checkbox"\]:checked +
.slow-speed-toggle::before { background: var(--google-blue-300); } }
------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI----
Content-Type: text/html Content-ID: Content-Transfer-Encoding: binary

\------MultipartBoundary--kprC5JlbNxFhRm0tZbF6zHFFWlsIaYTP7G7bCyKmjI------

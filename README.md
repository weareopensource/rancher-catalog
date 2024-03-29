# :globe_with_meridians: [WeAreOpenSource](https://weareopensource.me) Rancher Catalog

## :book: Presentation

This project is a rancher catalog to simplify the initialization of certain tools around our stacks. We wanted to use the official catalog or helm directly, unfortunately they are sometimes not up to date on the tools.

Quick links :

* [Mindset and what we would like to create](https://weareopensource.me/)
* [How to start a project and maintain updates from stacks](https://blog.weareopensource.me/start-a-project-and-maintain-updates/)
* [Global roadmap and  ideas about stacks](https://github.com/orgs/weareopensource/projects/3)
* [How to contribute and help us](https://blog.weareopensource.me/how-to-contribute/)

## :boom: Installation

Rancher (interface) :

* go in `Apps > Manage Catalog > Add Catalog`
* configure name namespace and add url `https://github.com/weareopensource/rancher-catalog.git`
* go in `Apps > Launch`
* Selectn configure and install

![config01](https://github.com/weareopensource/rancher-catalog/blob/master/images/config01.png?raw=true)
![config02](https://github.com/weareopensource/rancher-catalog/blob/master/images/config02.png?raw=true)

Helm (command line) :

```bash
git clone https://github.com/weareopensource/rancher-catalog.git
helm package charts/SERVICES/VERSION
helm install WORKLOAD_NAME -f CONFIG.yaml ./SERVICES-VERSION.tgz
```
## :runner: Running Your Application

### others

* release : `npm run release -- --first-release` **standard version, changelog, tag & choose version number : -- --release-as 1.1.1**
* release:auto : `GITHUB_TOKEN=XXXXX npm run release:auto` **semantic release, changelog, tag, release** *require repositoryUrl conf in package.json*

## :pencil2: [Contribute](https://blog.weareopensource.me/how-to-contribute/)

## :globe_with_meridians: [We Are Open Source, Who we are ?](https://weareopensource.me)

Today, we dreams to create Backs/Fronts, aligns on feats, in multiple languages, in order to allow anyone to compose fullstack on demand (React, Angular, VusJS, Node, Nest, Swift, Go).
Feel free to discuss, share other kind of bricks, and invite whoever you want with this mindset to come help us.

Feel free to help us ! :)

## :clipboard: Licence

[![Packagist](https://badges.weareopensource.me/packagist/l/doctrine/orm.svg?style=flat-square)](/LICENSE.md)

## :family: Main Team

## :link: Links

[![Blog](https://badges.weareopensource.me/badge/Read-our%20Blog-1abc9c.svg?style=flat-square)](https://blog.weareopensource.me) [![Slack](https://badges.weareopensource.me/badge/Chat-on%20our%20Slack-d0355b.svg?style=flat-square)](https://join.slack.com/t/weareopensource/shared_invite/zt-62p1qxna-PEQn289qx6mmHobzKW8QFw) [![Discord](https://badges.weareopensource.me/badge/Chat-on%20our%20Discord-516DB9.svg?style=flat-square)](https://discord.gg/U2a2vVm)  [![Mail](https://badges.weareopensource.me/badge/Contact-us%20by%20mail-00a8ff.svg?style=flat-square)](mailto:brisorgueilp@gmail.com?subject=Contact)

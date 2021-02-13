# About STEM Diverse TV Content Management System

Content Management System (CMS) for managing content of STEM Diverse TV backend. This repository is for frontend part for STEM Diverse TV [backend](https://github.com/anitab-org/stem-diverse-tv), so we could manage add/remove and edit content of our platform apps.

At the moment all content is comming from Youtube, however we are planning to extend that with other sources in future.

**Table of Contents**
- [About STEM Diverse TV Project](#about-stem-diverse-tv-project)
- [Technical Stack](#technical-stack)
- [Setup and run](#setup-and-run)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## About STEM Diverse TV Project

STEM Diverse TV is a project which gather and provide inspiring, motivating, informative, educational and supportive videos about diversity in STEM. This is the frontend of the project.


## Technical Stack

- React JS.

## Setup and run

To setup the project locally follow the instructions:

#### Fork

_**Note**_: *This is only needed if you want to contribute to the project.*

If you want to contribute to the project you will have to create your own copy of the project on GitHub. You can do this by clicking the Fork button that can be found on the top right corner of the [landing page](https://github.com/anitab-org/stem-diverse-tv) of the repository.

#### Clone

_**Note**_: *For this you need to install git on your machine. You can download the git tool from [here](https://git-scm.com/downloads).*

 * If you have forked the project, run the following command -

   `git clone https://github.com/YOUR_GITHUB_USER_NAME/stem-diverse-tv-cms`

   where `YOUR_GITHUB_USER_NAME` is your GitHub handle.

 * If you haven't forked the project, run the following command -

   `git clone https://github.com/anitab-org/stem-diverse-tv-cms`

 * Now after you cloned the repository, get into the stem-diverse-tv-cms directory by -

   `cd stem-diverse-tv-cms`

#### Remote

_**Note**_: *This is only needed if you want to contribute to the project.*

When a repository is cloned, it has a default remote named `origin` that points to your fork on GitHub, not the original repository it was forked from. To keep track of the original repository, you should add another remote named upstream. For this project it can be done by running the following command -

`git remote add upstream https://github.com/anitab-org/stem-diverse-tv-cms`

You can check that the previous command worked by running `git remote -v`. You should see the following output:

```
$ git remote -v
origin  https://github.com/YOUR_GITHUB_USER_NAME/stem-diverse-tv-cms (fetch)
origin  https://github.com/YOUR_GITHUB_USER_NAME/stem-diverse-tv-cms (push)
upstream        https://github.com/anitab-org/stem-diverse-tv-cms (fetch)
upstream        https://github.com/anitab-org/stem-diverse-tv-cms (push)
```

### Run app
Download the latest stable version of NodeJs [here](https://nodejs.org/en/download/) and install it. 
##### For yarn users
Install `yarn`. Run `node --version` and `yarn --version` to verify successful installation.

To get the frontend running locally:
- run `yarn` or `npm i` to install all required dependencies
- run `yarn start` or `npm start` to start the local server

## Contributing

**This project is under active development**

Please read our [Contributing Guidelines](docs/contributing_guidelines.md), [Code of Conduct](docs/code_of_conduct.md) and [Reporting Guidelines](docs/reporting_guidelines.md) thoroughly.

## Branches
- master: This contains the latest code. All the contributing PRs must be sent to this branch.
- production: Merge master into production triggers deployment of the website.

## Contact

If you have any questions or want to discuss something about this repo, feel free to reach out to our team on our Zulip channel [#STEM-Diverse-TV](https://anitab-org.zulipchat.com/#narrow/stream/216323-design/topic/STEM.20Diverse.20TV). If you are a new contributor, head over to this [project's stream](https://anitab-org.zulipchat.com/#narrow/stream/225705-STEM-diverse-tv) on Zulip to see ongoing discussions.

## License

The project is licensed under the GNU General Public License v3.0. Learn more about it in the [LICENSE](LICENSE) file.



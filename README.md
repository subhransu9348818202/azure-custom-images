# A Simple Nodejs API

[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/azure-custom-images.svg?style=svg)](https://circleci.com/gh/CIRCLECI-GWP/azure-custom-images)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

## Details

This repo is built following a tutorial published on CircleCI blog under the CircleCI Guest Writer Program.

- Blog post: ***Not yet published***
- Author's GitHub profile: [Fikayo Adepoju][author]

### About CircleCI Guest Writer Program

Join a team of freelance writers and write about your favorite technology topics for the CircleCI blog. Read more about the program [here][gwp-program].

Reviewers: [Laureen Harris][laureen], [Stanley Ndagi][stan]

[author]: https://github.com/coderonfleek

[gwp-program]: https://circle.ci/3ahQxfu
[laureen]: https://github.com/laureenh-zz
[stan]: https://github.com/NdagiStanley

---

## Running the Application

1. Run `npm install`
2. Run `node server`

### Using Docker

1. Install Docker
1. Run `docker build -t customnodeimage .`
1. Run `docker run -p 1337:1337 customnodeimage`
1. Navigate to <http://localhost:1337> and <http://localhost:1337/todos>

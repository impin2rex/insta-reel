# Instagram-Reel-Download-Using-Node
## CHANGELOG
[changelog]

## _Using Cheerio and instagram GhaphQL_

[![impin2rex](https://avatars.githubusercontent.com/u/53005904?s=60&v=4)](https://impin2rex.github.io)


This is a simple instagram reel link generator using [cheerio] and [axios] by targeting instagram public data DB GraphQL.
NodeJS-powered API.

- Put instagram reel link.
- Get reel URL.
- Magic 😎

## Features

- Get all reel's URL.

## Used

Insta-reel uses a number of open source projects to work properly:

- [Cheerio] - Fast, flexible & lean implementation of core jQuery designed specifically for the server.
- [node.js] - Run the backend.
- [axios] - The simplified HTTP request client 'request' with Promise support.
- [nodemon] - nodemon is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

You can send pull request from [git-repo-url].
 on GitHub.

## Installation

Instareel requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies and start the server.

```sh
npm i insta-reel
```

## Usage

```sh
const instareel = require("insta-reel");
const URL = "https://www.instagram.com/reel/CP4_gXYIup1/?utm_medium=copy_link"; // Instagram reel sharable link
(async() => {
    const reel = await instareel(URL);
    console.log(reel);
})();
```

## Response
```sh
https://instagram.fccu14-1.fna.fbcdn.net/v/t50.2886-16/198370938_205345488102850_8777608826093414179_n.mp4?_nc_ht=instagram.fccu14-1.fna.fbcdn.net&_nc_cat=110&_nc_ohc=usI6kP6O5f4AX8HMJEW&edm=APfKNqwBAAAA&ccb=7-4&oe=60E11234&oh=a565d58ba1091f06e3c4569b8c16ebfa&_nc_sid=74f7ba
```

## License

ISC

**Free Software, Hell Yeah!**

   [impin2rex]: <https://github.com/impin2rex>
   [git-repo-url]: <https://github.com/impin2rex/insta-reel>
   [changelog]: <https://github.com/impin2rex/insta-reel/blob/master/CHANGELOG.md>
   [cheerio]: <https://www.npmjs.com/package/cheerio>
   [axios]: <https://www.npmjs.com/package/axios>
   [node.js]: <http://nodejs.org>
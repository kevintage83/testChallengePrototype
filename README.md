# Functional Test Challenge Prototype
This project is a Node.js/Express API that returns search results of famous explorers. Most importantly, there is a functional test suite for the Node.js/Express files. A note to tech leads and senior software devs: Welcome! You're likely here because you need to see my coding chops! Express and Node.js examples (which aren't locked behind a previous client's privacy settings/guidelines or blocked by an NDA) must be created in my free time. Sharable projects are relegated to simple apps like these! I'm sure [at least some of] you can relate. :-)

In this example, we see how to send data in a request payload (body). Functional tests should test for 'res.status' to be 200 and for 'res.type' to be 'application/json'. Functional tests should test for 'res.body.name' to be 'Cristoforo' and 'res.body.surname' to be 'Colombo'. Super basic stuff. I am using Chai in this example. Chai is an assertion library, similar to Node's built-in assert. It makes testing much easier by giving you lots of assertions you can run against your code.

<p align="center">
  <img src="E54CA5D7-03DA-40BD-86E4-F96383615092.jpeg" width=50%/>
</p>

## Installation
You could clone the repo, click the download button, or just copy/paste the code into your code editor; it's only a few files. 

```bash
$ git clone https://github.com/kevintage83/testChallengePrototype
```

## Usage (Windows)
```bash
cmd /c start testChallengePrototype
```

## Usage (MacOS X)
```bash
open testChallengePrototype
```

## Usage (Linux/Unix)
```bash
xdg-open testChallengePrototype
```

## Contributing
At this time, I am not handling pull requests; this repo is primarily here to serve as a topic of dicussion among developers. Normally, if this were a repository where pull requests were welcome, I would ask that (for major changes, at least) you please open an issue first to discuss what you would like to change... but this is currently not the case.

I would also ask that you please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

Test Challenge Prototype 
============================
[![Run on Repl.it](https://repl.it/badge/github/freeCodeCamp/boilerplate-mochachai)](https://repl.it/github/freeCodeCamp/boilerplate-mochachai)

QA with mocha & chai

# ItemsAPI dashboard

This project is an angular.js dashboard for <a href="https://www.itemsapi.com" target="_blank">ItemsAPI</a>.  

Initially it was mostly for demo purposes but now it allows you to:
- create your own search api by providing json data
- search and manage your items
- integrate with heroku easily

Info from creator: this dashboard can be very powerful because it allows you to add and search / filter data instantly.
Developing and maintaining it is not my top prority anyway. I'd like to focus on core ItemsAPI https://github.com/itemsapi/itemsapi. If you like UX and frontend side and want to make it more useful feel free to make contribution! Matt


![](https://media.giphy.com/media/1iYG1Zaf12Yrk6T6/giphy.gif)


## Demo

- http://app.itemsapi.com/

## Requirement

- node.js

## Heroku installation

<a target="_blank" href="https://heroku.com/deploy?template=https://github.com/itemsapi/dashboard"><img src="https://camo.githubusercontent.com/c0824806f5221ebb7d25e559568582dd39dd1170/68747470733a2f2f7777772e6865726f6b7563646e2e636f6d2f6465706c6f792f627574746f6e2e706e67" alt="Deploy" data-canonical-src="https://www.herokucdn.com/deploy/button.png"></a>

## Installation (ubuntu 14.04)


Node.js:
```bash
$ sudo apt-get install curl
$ curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ sudo npm install npm@3.8.6 -g
```

Clone ItemsAPI Dashboard repository from github:
```bash
$ git clone https://github.com/itemsapi/dashboard.git
$ cd dashboard
```


local npm packages (in your project directory):
it will install bower packages as well
```bash
$ npm install --production
```

## Configuration and Run

```bash
$ PORT=3000 npm start
```

Open http://localhost:3000 in your browser


## Example data

- https://github.com/itemsapi/itemsapi-example-data/tree/master/items
- https://raw.githubusercontent.com/itemsapi/itemsapi-example-data/master/items/restaurants.json

## Troubleshooting

- https://github.com/itemsapi/dashboard/blob/master/TROUBLESHOOTING.md

## Contribution

This is early stage of the dashboard. There is still lot of works, improvements. If you want to help you can:

- make code review and suggest improvements
- share your ideas
- add new pull requests

## License

ItemsAPI dashboard is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.

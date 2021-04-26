# PWA-budget-tracker
PWA Budget Tracker is a performance web application (PWA) that allows users to track expenses and deposits both on and offline for on-the-go travellers.

[Deployed Heroku Application](https://github.com/jonathanstoll0603/PWA-budget-tracker)

---
    
## Description
    
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

```
AS A person who travels
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```
```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to the application's success. 

A list of technologies utilized in this application include: 

1. MongoDB / Morgan
2. indexedDB
3. Express Routing
4. Service Workers
5. Manifests
6. Caching
7. Lighthouse
8. JavaScript
9. Node


---
    
## Table of Contents
    
* [Installation](#installation)
    
* [Usage](#usage)
    
* [License](#license)
    
* [Contribution](#contribution)
    
* [Links](#links)
    
* [Questions](#questions)
    
---
    
## Installation

To install the necessary dependancies run the following command in your project folder's terminal window:
    
```
npm i
```

---
    
## Usage
    
To use this application, install the necessary dependancies then run the follow command in your project folder's terminal window:

```
npm start
```

A short video walkthrough of the application and it's functionality can be found below, as well as examples of the service-worker and webmanifest.


![video walkthrough](./public/media/PWA-budget-tracker-gif.gif)

![service-worker](./public/media/service-worker.png)

![webmanifest](./public/media/webmanifest.png)

    
## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license. Click the link for further information regarding this license. 

---

## Contributions
    
If you wish to contribute to this project, contact Jonathan Stoll via GitHub a [Jon's GitHub](https://github.com/jonathanstoll0603)

1. Ensure any install or build dependencies are removed before the end of the layer when doing a build.

2. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.

3. Increase the version numbers in any examples files and the README.md to the new version that this Pull Request would represent. 

---

## Links

A deployed version of the application via Heroku and MongoDB Atlas can be found [here](https://vast-crag-09121.herokuapp.com/).

---
    
    
## Questions
    
For any questions, please contact me via email at Jonathanstoll0603@gmail.com, or GitHub [issues page](https://github.com/jonathanstoll0603/readme-generator/issues).
    
---   

# Kalpa

This is an application for tracking plasma center donation rates. This is a frontend angular application, intended to work with an express api. 

<div align="center">
  <img src="./src/app/assets/images/readme_logo.png" alt="Kalpa" />
</div>

## Table Of Content

- [⚙️ Local Setup](#%EF%B8%8F-local-setup)
- [💾 Technologies Used](#-technologies-used)
- [🪢 Standard Workflow](#-standard-workflow)
- [🔗 Links](#-links)
- [🖥️ Contributors](#%EF%B8%8F-contributors)
 
<br> 
<br>

## ⚙️ Local Setup
---

Once the project is cloned down from github, run the following in your command line to start the development version of the project:  
```bash
cd my-first-app
git checkout dev
npm install
ng serve
```

You will need to have node installed on your machine to run a local server. Once you have run ng serve, you can navigate to a browser and enter the url http://localhost:4200 

You will also need the [express app](https://github.com/cynerge-consulting/kalpa-nodejs) running locally and get your ip whitelisted by the cynerge infrastructure team. Demo user login info can be found in the [spaces documentation](https://cynerge.teamwork.com/spaces/kalpa-team-information/page/6480-kalpa-logins).

<br />
<br />

## 💾 Technologies Used
---
- <a href="https://angular.io/docs">Angular</a>
- <a href="https://material.angular.io/">Material UI</a>
- AWS Amplify to help with AWS cognito pools which are being used for auth
- Eslint for formatting
- [Husky](https://typicode.github.io/husky/#/) for middleware processes
- [Chartjs](https://www.chartjs.org/) for our charts
- [fullCalendar](https://fullcalendar.io/) for our calendar

<br />
<br />

## 🪢 Standard Workflow
---
We use git branches associated with issue numbers. Git branches should be named numberOfIssue-small_name_of_issue. For example: 
```bash
1-create_initial_documentation
```

Please make sure that you create your feature branch off of dev and that your branch is up to date with dev before creating a pull request. 

<br />
<br />

## 🔗 Links
---
- [GitHub Repository for Angular Project]()
- [GitHub Repository for Express Project]()
- [GitHub kanban]()
- [Live dev site]()
- [Live staging site]()
- [Figma design center]()  
- [Teamwork Board]()
- [Spaces Documentation Hub]()

note: you will need permissions from Zachary for access to these resources

<br />
<br />

## 🖥️ Contributors
---
- Zach Joliff

## License
PlasmaPal is a product of Jolliff Consulting, Inc. © 2025 - All Rights Reserved

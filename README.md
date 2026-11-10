<img src="https://user-images.githubusercontent.com/59381432/93412198-ef5f4f00-f859-11ea-97d5-74424f9bb4fd.png" width=150px height=150px alt="Lono">

# Lono

[![Build Status](https://travis-ci.org/Birth-control-tech/birth-control-tech-FE.svg?branch=master)](https://travis-ci.org/Birth-control-tech/birth-control-tech-FE)

### Contributors
- Frontend
  * __Becca Steinbrecher__ (GitHub: [b-stein](https://github.com/b-stein))
  * __Alex Sodemann__ (GitHub: [asodemann18](https://github.com/asodemann18))
- Backend ([repo](https://github.com/whitneykidd/lono-be))
  - __Madeleine Halle__ (GitHub: [madhalle](https://github.com/madhalle))
  - __Whitney Kidd__ (GitHub: [whitneykidd](https://github.com/whitneykidd))

## Abstract
This is a birth control tool for women to follow the fertility awareness method (natural birth control). 

A user logged in for the first time is prompted to submit the profile form, so the app can start tracking their high risk and low risk days.  Once their profile information has been logged, a user can start tracking their daily basal body temperature along with any symptoms they might be having that day.  After filling out today's entry, a user can then view whether today is a high risk day or not.  The user can also see their historical data through a color coded calendar, or they can view reports that will display their temperature over the past week or month. 

## Learning Goals
* Build a PWA
* Utilize TypeScript and React Hooks
* Implement TravisCI
* Deploy to Heroku

## Setup
Checkout the [deployed application](https://lono-fertility.herokuapp.com/) (For mobile view, open devtools `cmd + opt + j`, then click mobile view).

--OR--

```
$ git clone [file path name]
$ cd birth-control-tech-fe
$ npm install 
$ npm start
```
## In Action
High-fidelity prototypes by Becca Steinbrecher, designed for the next phase of development.
<img width="405" height="803" alt="l1" src="https://github.com/user-attachments/assets/2ad8ada2-af4e-43d3-bb38-b537ce800abc" />
<img width="408" height="808" alt="l7" src="https://github.com/user-attachments/assets/c09c0242-2f2f-442e-98eb-cfb0584c653c" />
<img width="401" height="806" alt="l6" src="https://github.com/user-attachments/assets/e705eb43-2d53-45a4-80e6-aa68c86c21c7" />
<img width="409" height="805" alt="l5" src="https://github.com/user-attachments/assets/32adaf2f-b521-400f-83e4-4b7115b69d9c" />
<img width="398" height="813" alt="l4" src="https://github.com/user-attachments/assets/f8b15a88-e478-4bfb-aae8-6faa67feb460" />
<img width="403" height="804" alt="l3" src="https://github.com/user-attachments/assets/e9bd9d9c-7c9a-4b6b-8692-656922757912" />
<img width="401" height="806" alt="l2" src="https://github.com/user-attachments/assets/9ff56caf-a5ad-464a-a964-7b42d74b7a95" />

## Wins
- Connecting a hardware bluetooth piece to our application programmatically
- Incorporating a PWA push notification based off time to the user
- Write a frontend codebase with TypeScript
- Making a very atomic project board from the beginning, and staying on task with our due dates to finish the project on time
- Long, effective pairing hours remotely

## Future Iterations..
- Predict upcoming high or low risk days
- Finish CRUD features, namely **Updatintg** & **Deleting** entries.
- Implement a CSS framework (Tailwind, Bootstrap, etc) and a color theme
- Ensure responsive design
- Track symptoms along with these phases (helpful for athletic planning or general health awareness/planning)
- Finish bluetooth functionality: Keep thermometer connected, capture data for daily log form
- Put app on PWA store for android consumption
- Enable push notification to open right to the daily log form
- Calculate which of the 4 phases the user is on based off their tracking

## Technologies Used
- React, React Hooks
- TypeScript
- Jest
- React Testing Library
- HTML/SCSS
- npm
  - react-chartjs-2
  - react-multi-select-component
  - react-responsive-carousel
  - react-calendar
  - momentjs
  
## Systems/Practices
- git/Version Control
- [Wireframe](https://www.figma.com/file/cdMfcy3cP3iIhKzIbQfY5I/LNGP-Wireframe?node-id=0%3A1)
- TravisCI
- Heroku
- [PR Template](https://github.com/Birth-control-tech/birth-control-tech-FE/blob/master/pull_request_template.md)
- [Project Board](https://github.com/orgs/Birth-control-tech/projects/1)
- TDD

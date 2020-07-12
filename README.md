# PROJECT 4 README <!-- omit in toc -->

> The Project Planning section **should be completed** for your project pitch with instructors.
>
> To ensure correct Markdown, copy and paste the raw template code into your project repo README file. Remove ALL template instructions and replace with your project details.

- [Overview](#overview)
- [MVP](#mvp)
  - [Goals](#goals)
  - [Libraries and Dependencies](#libraries-and-dependencies)
  - [Client (Front End)](#client-front-end)
    - [Wireframes](#wireframes)
    - [Component Tree](#component-tree)
    - [Component Hierarchy](#component-hierarchy)
    - [Component Breakdown](#component-breakdown)
    - [Time Estimates](#time-estimates)
  - [Server (Back End)](#server-back-end)
    - [ERD Model](#erd-model)
- [Post-MVP](#post-mvp)
- [Code Showcase](#code-showcase)
- [Code Issues & Resolutions](#code-issues--resolutions)

<br>

## Overview

Exchange Zero is a full stack app which for users to trade and give away unwanted items with the goal of reducing waste and consumption. 


<br>

## MVP

###### Server (Back End)
- [ ] Have a RESTful JSON API.
- [ ] Build a Ruby on Rails server, exposing RESTful JSON endpoints.
- [ ] Build a database with at least 3 tables:
- [ ] There must be at least 1 association between your tables. (1:m or m:m)
- [ ] Utilize Rails to define models for interacting with the database.
- [ ] Implement working generic controller actions for Full CRUD (index, show, create, update, delete) between your non-User tables
 

###### Client (Front End)
- [ ] Have a working, interactive React app, built using npx create-react-app.
- [ ] Have at least 8 separate, rendered components in an organized and understandable React file structure.
- [ ] Utilize functional and class React components appropriately.
- [ ] Utilize state and props in your components efficiently.
- [ ] Use only React for DOM Manipulation.
- [ ] Consume data from your Ruby on Rails API, and render that data in your components.
- [ ] Utilize React Router, for client-side routing.
- [ ] Demonstrate Full CRUD actions ( index, show, create, update, and delete ) on the front end.


###### Styling
- [ ] Be styled with CSS 
- [ ] Use Flexbox 
- [ ] Implement 2 media queries for responsive design on 3 screen sizes (including desktop).

###### Linting
- [ ] Indent properly.
- [ ] tilize high-quality, semantic variable names.
- [ ] Follow camelCase, snake_case, and kebab-case convention.
- [ ] Remove unnecessary boilerplate React files and code.
- [ ] Remove all console.log()s and commented out code (functional notes and comments are okay).

###### Deployment
- [ ] Deploy the fully functional front-end via Surge or Netlify.
- [ ] Deploy the back-end via Heroku.

###### Procedural
- [ ] Initialize a git repo on Github, with a link to your hosted project.
- [ ] Have frequent commits, making a robust commit history at least every day. (75 commits minimum)
- [ ] Use effective and safe branching and merging processes.

<br>

### Goals

Have a working app with all MVP requirements.

<br>

### Libraries and Dependencies

> Use this section to list all supporting libraries and dependencies, and their role in the project. Below is an example - this needs to be replaced!

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|      React       | Front End |
|   React Router   | For routes|
| Axios| For API calls|
|     Ruby on Rails      | For Backend|

<br>

### Client (Front End)

#### Wireframes / Component Tree

https://whimsical.com/RzcHP8eKTseHtNBgqHHRE3



#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app. This should be a reflection of how you expect your directory/file tree to look like. 

``` structure

src
|__ assets/
      |__ fonts
      |__ graphics
      |__ images
      |__ mockups
|__ components/
      |__ Header.jsx
      |__ Footer.jsx
      |__ Signup.jsx
      |__ Listings.jsx
|__ services/
      |__ apiconfig.jsx
      |__ apihelper.jsx
      

```

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   n   | _The header will contain the navigation and logo._               |
| Footer  | functional |   n   |   n   | _The navigation will provide a link to each of the pages._       |
|   Signup    |   class    |   y   |   n   | _The gallery will render the posts using cards in flexbox._      |
| Listings | functional |   n   |   y   | _The cards will render the post info via props._                 |


#### Time Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Make Readme with Wireframes & ERD  |    L     |     3 hrs      |     0 hrs     |    0 hrs   |
| Ruby on Rails Models  |    L     |     3 hrs      |     0 hrs     |    0 hrs   |
| Ruby on Auth |    L     |     3 hrs      |     0 hrs     |    0 hrs|
| Ruby on Rails Controllers |    L     |     3 hrs      |    0 hrs     |    0 hrs   |
| Troubleshooting Ruby on Rails Backend |    L     |     3 hrs      |     0 hrs    |    0 hrs   |
| Create CRUD Actions |    H     |     3 hrs      |     0 hrs     |     0 hrs    |
| Create React Components|    H     |     6 hrs      |    0 hrs    |     0 hrs    |
| Style with Flexbox / make responsive |     H     |     6 hrs    |     0 hrs     |     0 hrs     |
| Services / Api Calls|    H     |     3 hrs      |     0 hrs   |     0 hrs     |
| General Troubleshooting |    H     |     10 hrs      |     0 hrs    |     0 hrs    |
| TOTAL               |          |     43 hrs      |     0 hrs    |     0 hrs   |



<br>

### Server (Back End)

#### ERD Model



https://app.diagrams.net/#G14Wgm3RFggvZ-wyzG8_NlKqJCmuboDPTb

<br>

***

## Post-MVP

- [ ] Allow messaging between users
- [ ] Implement Authorization
- [ ] Use Material UI
- [ ] Allow users to create more advanced profile
- [ ] Add blogging
- [ ] Add Resources for zero waste ideas
- [ ] Dark Mode

***

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution.




## SlowFood Challenge


This week's challenge is to build an Online Food Ordering System - a web-based application that allows customers to order their food for home delivery, or for pick up from the restaurant. Our imaginary client is a restaurant owner that needs a website where he can list his menu and allow visitors to place orders.


This is the first challenge touching upon the e-commerce domain that we will be working on during the course. **The purpose of this challenge is to simulate a real project and prepare you for the Mid Course Project, that you will be working on in week 6 of the Bootcamp.**


This challenge introduces a new set of technologies and skills you'll need as a developer. The main objective for this challenge is to practice the workflow that we want to use in our projects with a focus on:


* Agile methods for software development
* Pair Programming
* Collaboration using Git and GitHub
* Test Driven Development and Behavior Driven Design



### Learning Objectives

We set the goals high for this week. Apart from programming skills, that are of course in focus at all times, we will be working in teams during this week. Set yourself up to practice and learn more about:


* Use basic Agile practices
  - self-organizing teams
  - **iterative and incremental design**
  - the importance of planning your work
* Learn about Ruby on Rails as an API
  - understand the concept of ORM's vs SQL (ActiveRecord)
  - understand the MVC structure
  - controllers
  - routes
  - models
  - relation between models
  - concept of `params` (See: https://www.youtube.com/watch?v=y57OnWV6dRE)
* Learn more about React
  - understand how to consume an API
  - understand the different requests (POST/PUT/GET/DELETE)
  - how a react client fits into the MVC structure
* Learn more about User Authentication
* Learn about the hardships that will occur if we can't read the documentation for libraries we use in our projects (gems & packages).
* Learn more about Test- and Behavior Driven Development or Acceptance - Unit Test cycle.
* Embrace and understand the benefits of Pair Programming && collaboration using Git and GitHub


**Please note that there may be subtle errors or typos in the following materials. Please try to approach those as challenges on which to polish your debugging and problem-solving skills**


### Concept of the Week
**Incremental and Iterative Design**: The basic idea behind this method is to develop a system through repeated cycles (iterative) and in smaller portions at a time (incremental), allowing software developers to take advantage of what was learned during development of earlier parts or versions of the system.

- **Incremental** – adding new functionality in small chunks.
- **Iterative** – performing repeatedly, i.e. adding new functionality repetitively or cyclically.


## Tools

During this project, you will be using a variety of tools. You have used some of them in other challenges, but many will be new to you.


* [Ruby on Rails](https://rubyonrails.org/) as web framework
* [Rails API Boilerplate](https://github.com/CraftAcademy/slowfood_api_boilerplate) A scaffolded application with a basic setup for testing.
* [React Client Boilerplate](https://github.com/CraftAcademy/slowfood-client-boilerplate) A scaffolded app wit all testing tools configured.
* [Devise](https://github.com/plataformatec/devise) for user authentication and account management
* [PostgreSQL](http://www.postgresql.org/) as a database with ActiveRecord as ORM
* [RSpec](http://rspec.info/) for Unit & Request tests
* [Cypress](https://docs.cypress.io/guides/overview/why-cypress.html) for acceptance testing in React.
* [Pony](https://editor.ponyorm.com/) for creating end editing Entity-Relationship Diagrams (optional)
* [GitHub](https://github.com/) to store your code and make it available for the entire team
* [Pivotal Tracker](https://www.pivotaltracker.com/) as Project Management tool for tracking Features, Chores, and Bugs.


As you can see, there's plenty of tools and services for you to familiarize yourself with.


## Scope


In the first version of the application should focus on the following functionality:


* The restaurant owner needs to access a protected part of the application to set up information about his restaurant (like address, opening hours, etc) and his menus (products ordered in categories)
* A menu needs to consist of many dishes
* Each dish has/belongs to a Category. It is either a 'Starter', a 'Main course' or a 'Dessert'
* The restaurant also sells cold beverages and side orders like salads, bread, etc.
* Visitors to the site can add various products to their order
* To create an order and Check out, a customer needs to become a registered user
* Order need to calculate a total price and a pickup time (30 minutes)


**Nothing else should be considered or implemented.**

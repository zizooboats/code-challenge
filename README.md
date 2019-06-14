## Introduction
This project is designed to test the ability to tackle problems similar to applications of Zizoo.
The instructions are left ambiguous and are meant in order to give the developer freedom to design,
implement and test their own solution.

## Instructions
Your objective is to create an internal API to fetch the boat data
and create a filterable interface to show those boat details.
The dataset json is included in this repository.
Ensure that you application meets the requirements.
You can use any libraries as you like through the implementation of the project.

## General
- Front-end should be written in React.js/Vue.js
- API Language should be your own choice (We strongly prefer PHP)
- Dockerization

## API
The API should support multiple queries at the same time, and should only restrict the dataset.
All values are inclusive and should be ingested as shown below. Some of the values can be implemented
as min-max values.

*GET /boats?location=Berlin&min_length=10&nr_guest=10&cabins=4*

## Front-end
- Tables should have pagination enabled
- Details should be accessible via tables as link
- Formatting should be enabled for special variables (e.g. date)
- Styling should meet modern appliances

## Bonus
- End-to-end tests
- Unit tests
- CI implementation
- You application is deployed somewhere (Heroku, Now or any other)
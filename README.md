# Zizoo Fullstack Code Challenge

This project is designed to test the candidates ability to tackle problems similar to applications we develop at Zizoo.
The instructions are broad in order to give the developer freedom to design, implement and test their own solution.

## Instructions

The objective is to create a full stack application that fetches boat data and creates a filterable interface to show the boat details.

The `json` dataset is included in this repository.

You can use any libraries you consider necessary for the successful implementation of the project, but ensure that you application meets the requirements.

## Requirements

### Back-end
- Language can be your own choice (We use PHP);
- The API should support multiple queries at the same time, and should only restrict the dataset;
- All values are inclusive and should be ingested as shown below. Some of the values can be implemented as min-max values.

  Example: `GET /boats?location=Berlin&min_length=10&nr_guest=10&cabins=4`

### Front-end
- Language can be your own choice (We use React);
- Results should have pagination;
- Special values should be formatted accordingly (e.g. date);
- Should use semantic HTML tags;

### Bonus
- End-to-end tests;
- Unit tests;
- Results linking to a details page;
- CI implementation;
- You application is deployed somewhere (Heroku, Now or any other);
- Application is dockerized;

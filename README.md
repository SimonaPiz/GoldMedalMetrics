# 🏅 Gold Medal Metrics
> An Olympic metrics reporting web application

<img src="https://github.com/SimonaPiz/GoldMedalMetrics/blob/main/preview01.png" width="600px" alt="preview" title="preview"/>

## Table of Contents
* [General Info](#general-information)
  * [Features](#features)
* [Implementation Details](#implementation-details)
* [Testing](#testing)
* [Screenshots](#screenshots)
* [Technologies Used](#technologies-used)
* [Usage](#usage)
* [Acknowledgements](#acknowledgements)
* [Author](#author)

## General Information

In this project I wrote all the SQL statements for an Olympic metrics reporting web application called Gold Medal Metrics.

You can view all of this functionality in action in the video below: [▶](https://content.codecademy.com/programs/build-apis/solution-videos/GoldMedalMetrics480.mov)

### Features

Gold Medal Metrics allows users to:

 - View countries in a list with their population, GDP, and number of Olympic gold medals.
 - Sort the list of countries by any of these attributes, as well as alphabetically by name.
 - View a detailed description of a country, with statistics on their Olympic wins.
 - View a list of every Olympic win a country has with the year, season, winner name, city, and event.
 - Sort the list of Olympic wins by any of these attributes.

## Implementation Details

To complete this project, I needed to write a series of JavaScript functions that return the SQL queries (as strings) that operate Gold Medal Metrics:

- [x] `createCountryTable`

  Returns the SQL command that will create a table, named `Country`.

- [x] `createGoldMedalTable`

  Returns the SQL command that will create a table, named `GoldMedal`.

- [x] `goldMedalNumber`

  Returns the SQL command that will retrieve the number of gold medals that country has won in all Olympic games.

- [x] `mostSummerWins`

  Returns the SQL command that will retrieve the year where the given country won the most summer medals

- [x] `mostWinterWins`

  Returns the SQL command that will retrieve the year where the given country won the most winter medals

- [x] `bestYear`

  Returns the SQL command that will retrieve the `year` that country won the most Olympic medals, and how many medals were won.

- [x] `bestDiscipline`

  Returns the SQL command that will retrieve the `discipline` in which that country won the most Olympic medals, and how many medals were won.

- [x] `bestSport`

  Returns the SQL command that will retrieve the `sport` in which that country won the most Olympic medals, and how many medals were won.

- [x] `bestEvent`

  Returns the SQL command that will retrieve the `event` in which that country won the most Olympic medals, and how many medals were won.

- [x] `numberMenMedalists`

  Returns the SQL command that will retrieve the number of men who have won Olympic medals for that country.

- [x] `numberWomenMedalists`

  Returns the SQL command that will retrieve the number of women who have won Olympic medals for that country.

- [x] `mostMedaledAthlete`

  Returns the sql command that will retrieve the `name` of the athlete who won olympic medals for that country.

- [x] `orderedMedals`

  Return a SQL query that returns all fields for every Olympic medal won by the given country in the specified order, ascending or descending.

- [x] Bonus: `orderedSports`

  Return a SQL query that retrieves all the sports that country has received a Gold Medal in in the specified order, ascending or descending. Additionally the query returned should return the number of times the given country received a medal in that sport

✅ [#2 issue](https://github.com/SimonaPiz/GoldMedalMetrics/issues/2)

## Testing

A testing suite has been provided, checking for all essential functionality and
edge cases.

To run these tests run 
```
npm test
```

  ✅ [#3 issue](https://github.com/SimonaPiz/GoldMedalMetrics/issues/3)

  ✔ All test passed

  ![Test reults](https://user-images.githubusercontent.com/91121660/279079957-ea0285a2-940d-4273-8981-fa28465503f7.png)

## Screenshots

<img src="https://github.com/SimonaPiz/GoldMedalMetrics/blob/main/preview02.png" width="600px" alt="preview" title="preview"/>

## Usage

To view the webpage, run 
```
$ npm run webpack
``` 
to compile the front-end files, and follow that with `open index.html` from the root directory of this project. 

To start your server, run 
```
$ npm install
``` 
and then `node server.js`. Refresh your browser to collect the information from the server. 

## Technologies Used
   - React 15
   - react-router-dom 4
   - mocha 10
   - chai 4
   - express 4
   - sqlite3 5

## Acknowledgements

This project comes from the [Codecademy's Create a Back-End with JavaScript](https://www.codecademy.com/learn/paths/create-a-back-end-app-with-javascript) course.

## Author

- [Simona Pizio](https://github.com/SimonaPiz)

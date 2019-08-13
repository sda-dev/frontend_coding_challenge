# SDA Media - Frontend Coding Challenge:

## Goal:
The goal of the challenge is to build a one page react app that displays the typical price (TP) of Google stock in the last 30 days.

Typical Price is calculated as the average of High, Low and Close:
TP = (High + Low + Close)/3

## Technical Requirements:
The webapp should do the following:
- Show a “Load Data” button when it first gets loaded
- When triggered by a click on button, it should fetch the daily stock price of Google using alphavantage api.
Use the [TIME_SERIES_DAILY](https://www.alphavantage.co/documentation/) endpoint and GOOG for the stock symbol.
Your app should only make ONE "get" call.
- Make the required operations to pull the daily and weekly TP of the stock for in last 30 days/ last 4 weeks. 
--NB: A weekly TP is the average of the daily TP from Monday to Friday. You can always ignore the current week since it may be missing a few days. Also, you can round all the averages
- Display the daily TP data in a [Line Chart](http://jerairrest.github.io/react-chartjs-2/)
- Display the weekly TP data in a [Bar Chart](http://jerairrest.github.io/react-chartjs-2/)

## Dependencies:
- React (You can use create-react-app as  a boilerplate)
- Alpha Vantage API ([Get Free API Key](https://www.alphavantage.co/support/#api-key)) ([Documentation](https://www.alphavantage.co/documentation/))
- [react-chartjs-2](https://www.npmjs.com/package/react-chartjs-2)  for charts

You can use any other npm packages to build your react components (Material UI, reactstrap, styled-components, styled-system, lodash, momentjs ...), but try to keep it simple and minimal. 
We encourage you to use your favorite tools and packages to build a solid React application. Make sure the code is clean and linted.


## Instructions:
- Fork this repo
- Build a performant, clean and well-structured solution
- Add "How to run" instructions & push
- Create a pull request

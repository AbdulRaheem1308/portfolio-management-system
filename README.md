# Portfolio Management System

This is a sample implementation of a Financial Portfolio Management System in Angular.

## Running the Application

1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `ng serve` to start the application
4. Open `http://localhost:4200` in your browser to access the application

## Features

1. Dashboard Design and Implementation
	* Displays key portfolio information such as asset allocation, and performance metrics
	* Implements interactive charts to visualize portfolio performance over time
	* Maintains responsive design for different device compatibility
2. Form Creation and Validation
	* Creates a form for users to input their investment details including asset type, quantity, purchase price, and date
	* Provides an ability to review user input before submission
	* Validates the form inputs to ensure data accuracy and completeness before submitting
3. Client-side validation using Angular's built-in form validation features

## Technologies Used

* Angular 12
* TypeScript
* HTML5
* CSS3
* Highcharts for charting
* Bootstrap for responsive design

## Folder Structure

* `src/app`: Application components and services
* `src/app/dashboard`: Dashboard component and related files
* `src/app/forms`: Form component and related files
* `src/app/mock.service.ts`: Mock service for simulating backend API calls
* `src/assets`: Static assets such as images and fonts
* `src/environments`: Environment configuration files
* `src/index.html`: Application entry point
* `src/main.ts`: Application main file
* `src/styles.css`: Global styles file
* `src/test.ts`: Test configuration file

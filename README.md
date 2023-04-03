# 09-node.js-READMEGen

# README Generator

## Description

This application is a command-line application that dynamically genrates a professional README.md file given a user's input.

This application's goal is to provide a quick and easy method to generate a README file to allow the project creator to devote more time to working on the project. 

This project is intended for those creating an open source project on GitHub to provide necessary information about the project for other developers to contribute to the success of the project.


## Table of Contents

- [User Sotry](#userstory)
- [Acceptance Criteria](#accpetancecriteria)

## User Story

AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project

## Acceptance Criteria

GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generatsded with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README

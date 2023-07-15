# Getting Started

## Prerequisites

Before you can run this project, you must have the following software installed on your computer:
- nodeJS
- Visual studio code

## Installation
1. Clone this repository to your local machine using `git clone https://github.com/aldimanx/newman-API.git'
2. run npm install
   
## how to run a test

npx newman run collection\moduit.json -e environment\environment.json 

## how to run test and generate html report

npxnewman run collection\moduit.json -e environment\environment.json  -r htmlextra
report will be report/result.html


## how to run test via github actions and generate html report

trigger manually or on every approved code changes.
report will be in bottom of summary github actions item

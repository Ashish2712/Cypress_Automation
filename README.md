# Cypress_Automation

Prerequistes:
1. Node js (https://nodejs.org/en/download/)
2. IDE(vs code) or any other ide you are comfortable with (https://code.visualstudio.com/)


Cypress installation
1. npm install cypress --save-dev


Cypress open:
Below command will open cypress test runner which contains the basic introduction about the file structure(if this is the first time
you are opening cypress) also it gives you the flexibility to choose the browser(chrome, firefox, electron).

npx cypress open

New features comes with cypress 10.0
1. E2E testing 
2. Componenet testing

File strcture for E2E testing:
1. cypress.config.js -> Config file for cyress framework
2. cypress/support/e2e.js -> This file contains code which will be loaded before each and every test, one can put the
   global configuration here which will be executed for all the testcases.
3. cypress/support/commands.js -> This files comes handy when you want to create custom cypress command, or want to edit the existing one.
4. cypress/fixtures/example.json -> In fixtures folder you can put your data which later on be used by your test cases for example here,
   we have put some data inside example.json file which later on will be used by one of the testcase.
   
   
If you click on specs you will find the existing examples provided by the cyress team to understand the flow of the framework.
Also you can create your own spec file which will contain your code for the automation.

   
   


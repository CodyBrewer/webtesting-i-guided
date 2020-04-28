# WEB Unit Testing

## Why do we test?

 We test to create a safety net for when we refactor or add features, to prevent regressions, to gain a better overall understanding of how the application works.

### If we don't test
  * application code has to be tested manually
  * there is no way to know if a cahange broke another picece of code
  * you cannot be sure if the code is correct
  * manually testing takes a lot of unnecessary time
  * adding new features becomes slow

### Advantages of Testing
  * verifies edge cases
  * developer can concentrate on current changes (the safety net)
  
### Drawbacks of Testing
  * more code to write and maintain
  * more tooling
  * additional dependencies
  * may provide a false sense of security
  * trivial test failures may break build
  * regressions (when a new feature breaks existing code)

## JEST
A delightful JavaScript Testing Framework witha a focus on Simpliccty. 
Works with Node, React, Vue, Angular, + most other JavaScript Frameworks.
Jest is a test runneer and command line interface npm package. It was created originally by Facebook and is included in create-react-app.

### Using Jest
We add Jest as a devDependency because you don't test in Production you run your tests locally `npm i -D jest`
Testing script: `"test": "jest --watch` *The watch paramater will not work if you do not have a .git JEST uses git to view changes in all the individual files so if you are not using git you can run the --watchall parameter*

Jest is ran under the hood in react testing library


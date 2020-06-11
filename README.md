# Node.js TypeScript application with SonarQube static code analysis

It's a simple project to show you how SonarQube works.
You can find the article about it [here](https://medium.com/@anastasia.a.zhivaeva/static-analysis-of-javascript-applications-with-sonarqube-a916269c7099).

## Steps
- Install node_modules with command _npm i_
- Start SonarQube docker container with command _npm run sonarqube:up_
- Start tests with command _npm run test_
- Start analysis with command _npm run sonarqube-verify_
- Go to http://localhost:9000
- Log in with _admin/admin_ credentials
- Now you can see the _sonarqube-example_ project's report

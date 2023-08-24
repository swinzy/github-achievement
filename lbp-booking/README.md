# LBP Website Booking System Test Playground[^1]
## Configure Environment
Prerequisite:
- Node.js >= 18.16-LTS

### Install Node.js
**Linux**: <br>
Install package `nodejs`

**Windows**: <br>
Method 1: Download from <a href="https://nodejs.org/en">official website</a><br>
Method 2: Use winget `winget install OpenJS.NodeJS.LTS`

### Install Node.js Dependencies[^2]
1. Clone this repository first
2. Navigate into the project directory (not the root of the repository)
```
cd lbp-booking/lbp-booking
```
*(To check if you are in the right directory, type `ls` and check if `package.json` is present)*

4. Install React dependencies automatically
```
npm install
```
5. Install dependencies for development
```
npm install mongodb express cors dotenv
```

### Test the Project
```
npm start run
```
You should see something like:
```
Compiled successfully!

You can now view lbp-booking in the browser.

  Local:            http://localhost:3000
  On Your Network:  http://xxx.xxx.xxx.xxx:3000

Note that the development build is not optimized.
To create a production build, use npm run build.

webpack compiled successfully
```
At the same time, your default browser should launch and navigate to `http://localhost:3000/`, if not, you may manually launch a browser at your choice and navigate to `http://localhost:3000/`. You should be able to see a webpage now.

### Troubleshoot
```
'react-scripts' is not recognized as an internal or external command
```
Your node modules are not installed correctly, please ensure you are in the project directory, not the root of the repository, and re-excute section `4. Install React dependencies automatically` from above.

For any other questions, please post a thread in Microsoft Teams under `Discussion` tab.<br>
Alternatively, you may <a href="mailto://stephen.zhang1@student.unimelb.edu.au">contact product owner Stephen Zhang</a> for further assistance.

[^1]: *Written by Stephen Zhang 15 Aug 2023 | Last Revised on 24 Aug*
[^2]: <a href=https://www.mongodb.com/languages/mern-stack-tutorial>MERN Stack Tutorial - MongoDB</a>

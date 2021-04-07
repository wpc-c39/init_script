# Node.js Demo Application
Node.js basic application useful for demos and examples

&nbsp;

## General Information

The application show a basic web page
![Welcome-Page](https://github.com/selaworkshops/npm-demo-app/blob/master/Images/Image1.png?raw=true)

The application have a basic function to determine if a number is prime or not
![Welcome-Page](https://github.com/selaworkshops/npm-demo-app/blob/master/Images/Image2.png?raw=true)

The folder “spec” contains the application tests which are run using the jasmine-node module
![Welcome-Page](https://github.com/selaworkshops/npm-demo-app/blob/master/Images/Image3.png?raw=true)

The application Dockerfile is very simple, use node as a base image, copy the application files, download the application dependencies and run the application in the port 3000
![Welcome-Page](https://github.com/selaworkshops/npm-demo-app/blob/master/Images/Image4.png?raw=true)

## Build

Install Dependencies:
```
npm install
```

Run Tests:
```
npm test
```

create zip file
```
npm run build
```

Start the Application:
```
npm start
```


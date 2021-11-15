# ahmadmamdouh-10-BlogLab
This is a Blog Application using DatabaseFirst, ASP.NET Core API, Identity Library, JWT for Authentication, Dapper to connect with database, that all with Backend, and I use in Front-end: Angular11, HTML5, CSS3, Bootstrap, font-awesome, &amp; Typescript.

# PLEASE FOLLOW THESE STEPS TO AVOIDING GITTING ERRORS, And establish it smoothely:

1- Open Deployment.sql file & and Run the script to create your database
2- Create an account in https://cloudinary.com/
3- Take the username, apiKey,apiSecret and put it in the app.settings.json in the CloudinaryOptions
4- Go to BlogLab & Run these commands as following :
        -  dotnet build
        - cd BlogLab.Web
        - dotnet run
5- Now after you establish the backend server, you need to start the frontend "Angular" Server with the following command lines: 
   * Please Check if you already have installed Node.js 
   * Then install AngularCli
   * Open the BlogLab-UI with cmd 
    - cd ../BlogLab-UI
   * Run this command line : npm install
   * Run this command :      ng serve -o

##### IF YOU NEEDED TO TEST APIs & PUT DUMMY DATA TO DATABASE ######
* you will find Postman Folder in the App.Folder you will need to attach the environment & Collection of Ready Requests 
* After Running Backend Server, Test Every Endpoint with the Collection.

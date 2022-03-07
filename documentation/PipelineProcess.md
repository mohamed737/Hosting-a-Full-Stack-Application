the app is configered to work with aws servised the frontend and backend were build  both in www folders then tested also with the console then they were also tested using the cli and the porcess was automated using circleci by linking it to the project and the project were pushed to the main bransh multiple times until the errores were fixed

the way it works is for the forntend first installing the dependaencies 
then it is built 
and then it is deployed to s3

for the backend the dependencies is installed then
the project is built in the www folder
the initialization folder for the eb is copied to the buildt folder with the deploy file then
deploying to the environment accure 
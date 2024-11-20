# AngularPocProjects

Angular setup 

Node js download and in install
https://nodejs.org/en/download/prebuilt-installer/current

Download VS code or any other as per preference

Create an folder eg: C:/../angular_Projects/

open terminal run command 
1. node -v
2. npm -v
3. npm install -g @angular/cli   - to install commandline of angular/cli
Now if require,create git repo and clone it.
4. ng new angular_project_name   - creates new angular project.
5. npm install  - will download package.json and generates nodemoules folders in your project
After this we have completed the basic steps for angular app, there is lot more to know about the files present in the folder and whats use of them

  tip: Format code using 
  -Shift + Alt +F in Windows
  -Shift + Option +F in Mac
  -Ctrl + Shift + I in Linux


  tip: need to change the default port of angular then angular.json serve add in "development" as "port":8090


  tip :Need to add the bootstrap the add it its style in angular.json in  "styles" section 

how application executes like the flow of angular app
(SPA)index.html -> main.ts  app.component will load first asits defined here in main.ts->

app.config.ts ->
for services
http client


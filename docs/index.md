This is a research created by Nacho Moreno Navarro ([NachoMoren](https://github.com/NachoMoren)) for Project II subject in Videogame Design and Development at UPC/CITM. 

# Automated Builds CI + CD
In software development, building is the process that describes the conversion of files and other assets to create a software product that works in its intended form. This procedure includes compiling source files, packaging compiled files into compressed formats, producing installers and creating or updating database schemas. So, whenever we talk about an automated build, it means that there is no human intervention during this building process. Build automation is possible when the steps involved in the build are repeatable and can be performed using just the information that has already been stored in the source code control repository by the developers. Furthermore, build automation is a first step of any CI/CD process. 
## Continuous Integration (CI)
Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. It allows the developers to frequently merge code changes into the central repository where builds and tests will run. 
The goal of including CI in your project is to reduce the problems generated while working simultaneously on the same project. In order to make this happen, it is necessary to separate properly the work of each contributor and try to encapsulate changes in order to integrate them in a regular way. 


## Continuous Delivery and Continuous Develpoment(CD)
Continuous delivery is an extension of continuous integration, since it automatically deploys all code changes to a testing and/or production environment after the build stage. This means that you have an automated release process and you can deploy your app any time by clicking a button. 
Even if there is not established a quantity of time between two releases, in order to get as much benefit as possible from continuous delivery, you should deploy to production as early as possible. 

On the other hand, continuous deployment goes a step further than continuous delivery. With continuous deployment, every change done that passes all the tests and all the stages will be released to the customers. Working this way is an excellent way to accelerate the feedback loop with customers. 

## Comparison between different CI/CD tools


# cf-app-1
Cloud Foundry Static Application

Steps:
1- mkdir cf-app-1 & cd                    // create application folder with html and css files
2- cf login -a https://api.run.pivotal.io // login to Pivotal Web Services
3- touch Staticfile                       // create Staticfile
4- cf push cf-app-1                       // push application to Pivotal Web Services
5- cf app cf-app-1                        // check application health

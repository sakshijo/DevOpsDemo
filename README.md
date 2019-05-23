# ASP.NET Core getting started application
The IBM Cloud Getting started tutorial for ASP.NET Core uses this sample application to provide you with a sample workflow for working with any .NET Core app on IBM Cloud; you set up a development environment, deploy an app locally and on IBM Cloud, and integrate a IBM Cloud database service in your app.


The following steps are the general procedure to set up and deploy your app. See more detailed instructions in the [Getting started tutorial for ASP.NET Core](https://console.stage1.bluemix.net/docs/runtimes/dotnet/getting-started.html#getting_started).

This is the sample DOtnet website used to implement the contionous Integartion and continous delivery using Microsoft AZure pipeline.

How to Use: 
1.You can use Git repository to import the Dotnet application code or can use Azure repository to import it. 
2.Microsoft Azure Pipeline is required to create to implement CI/CD concepts .Build pipeline as well as release pipeline . 
3.Microsoft Azure portal can be used to launch or deploy your application on Azure cloud.
4.Update the code in Azure repostory ,update the text messages and deploy the updated code in Azure .Build pipeline will compile and run the code and shows if any errors are there.Once the build is successfull,then build will be executed in Delivery pipeline and Cloud applictaion URL will be updated .
5.On click of URL ,you will get updated code deploy on to the cloud .Launch the application with this URL.



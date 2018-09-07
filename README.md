# azure-appinsights-search

A smart html5 based standalone tool for viewing the instrumentation data when your web app is configured with Azure App Insights. Instrumentation data helps to monitor application health and help you diagnose issues and continuously improve performance and usability all in you live application.

The tool is powered by Application Insights REST API and uses the ***Application ID** and ***API Key***. So using these two parameters, you can leverage to view instrumentation for any of you web applications.

Instrumentation data included ***Request, Exception, Trace, Dependency, Availability Sets, Page Views and Custom Events***.

***Note:** Rest API retrieves data only using appid & apikey. instrument key cannot be used.*

## About Azure Application Insights

Application Insights is an extensible Application Performance Management (APM) service for web developers building and managing apps on multiple platforms including .NET, Node.js and J2EE, hosted on-premises or in the cloud. It includes powerful analytics tools to help you diagnose issues and to understand what users actually do with your app. It's designed to help you continuously improve performance and usability. [click here for details](https://azure.microsoft.com/en-us/services/application-insights/)

## Demo 

[click here](http://appinsightssearch.scm.azurewebsites.net)

## Built With

* [Jquery](https://jquery.com/) - cross-platform JavaScript Library 
* [Bootstrap v4](https://getbootstrap.com/) - Html Styling
* [Bootswatch](https://bootswatch.com/) - Boostrap based themes
* [Tabulator](http://tabulator.info/) - A lightweight, fully featured, interactive table jQuery plugin
* [Jquey UI Timepicker Addon](http://trentrichardson.com/examples/timepicker/) - Jquery UI based Timepicker Add-on 
* [Azure App Insights Rest API](https://dev.applicationinsights.io/) - Access all your app's event and metric data using powerful Rest API.

### Installation

Package Manager
```
Install-Package AppInsights.Search -Version 1.0.0
```
.NET CLI
```
dotnet add package AppInsights.Search --version 1.0.0	
```

## Using the tool
* when you open the file ***app-insights-search.html*** it will load demo key for testing and you screen will be like the below screenshot

![](images/image1.PNG)

* when you click on the button ***select account*** following popup will come.
* There you can add ***Description, application ID and API key*** and click on add. It will then save this to your browser localstorage for further use.

![](images/image2.PNG)


![](images/image3.PNG)

* When you click on any row of a table it will show further details *(depending upon item type)* of the selected row as shown below.

![](images/image5.PNG)

### Other Functions

* Main page have the field named ***Time Range*** *(Default is 12 hours)* from where you can enter the time of which you want to see the records.

This ***Time Range*** field also have a option named ***custom***. When you select this two fields will be visible blow it where you can add the time range and this app will search for the events that occure in this time range.

![](images/image6.PNG)

* It has a field named ***Limit*** *(Default value is 100)* where you can add the number of records you want *e.g: 100,200.. etc*


## Authors

* [Umair Tariq](https://github.com/umairtarik) 
* [Hamza Safdar](https://github.com/hamzasafdar01)

See also the list of [contributors](https://github.com/umairtarik/azure-appinsights-search/contributors) who participated in this project.

## Tags

appinsights, azure application insights, appinsights search, etc




# PromoteNugetPackage
Powershell script for promoting a nuget package to a view with Azure DevOps on-premise.

I couldn't find any examples of how to make this work on-premise.  Only examples of how to make it work with the online Azure 
DevOps server.

As a quick note, part of how I figured this out was by using Fiddler to look at the HTTP message being posted by the Azure DevOps web page
for promoting a package.  If you haven't used Fiddler before it is a neat tool for viewing the data passed in REST API calls.

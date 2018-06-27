# Serverless Microservice Bootstrap (Template)

[![serverless](https://dl.dropboxusercontent.com/s/d6opqwym91k0roz/serverless_badge_v3.svg)](http://www.serverless.com)
[![Build Status](https://travis-ci.org/PageUpPeopleOrg/serverless-microservice-bootstrap.svg?branch=making-it-relevant)](https://travis-ci.org/PageUpPeopleOrg/serverless-microservice-bootstrap)

This project is the .Net Core Template wrapper for the [Serverless Microservice Bootstrap project](https://github.com/PageUpPeopleOrg/serverless-microservice-bootstrap).

## Getting Started

Make sure you have the [Serverless Framework](http://www.serverless.com) installed.
```
npm install serverless -g
```

Install dotnet core on your machine. Instructions can be found at (dotnet website)[https://www.microsoft.com/net/download]

### Development

The original project is referenced here as a git submodule. To sync, run a `git submodule update` to get the latest copy from the remote repository.

## Setup

Install the template onto your machine with 

```
dotnet new -i Serverless.Microservice.Bootstrap.Template
```

Once installed, create a new project using the template with

```
dotnet new serverlessmicroservice
```


## Using the Bootsrap

For information on how to use the Bootstrap, [see the project's README](https://github.com/PageUpPeopleOrg/serverless-microservice-bootstrap/blob/master/README.md).

## Understanding how this works

The template is published is nuget.org and is named per recommendation from Microsoft, which enables us to use the dotnet new command.

[Serverless.Microservice.Bootstrap.Template 1.0.0 - Nuget link](https://www.nuget.org/packages/Serverless.Microservice.Bootstrap.Template/)

[Dotnet new templates for Serverless Microservice Bootstrap Template](https://dotnetnew.azurewebsites.net/template/Serverless.Microservice.Bootstrap.Template/Serverless.Microservice.Bootstrap)

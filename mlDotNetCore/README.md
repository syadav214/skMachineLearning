# mlDotNetCore

Machine Learning Engine in DotNet Core

#Commands for Ubuntu 16.04
sudo sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ xenial main" > /etc/apt/sources.list.d/dotnetdev.list'
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 417A0893
sudo apt-get update

#install core
sudo apt-get install dotnet-dev-1.0.1

#create console project
dotnet new <template>

## Templates Short Name Language Tags

Console Application console [C#], F# Common/Console
Class library classlib [C#], F# Common/Library
Unit Test Project mstest [C#], F# Test/MSTest  
xUnit Test Project xunit [C#], F# Test/xUnit  
ASP.NET Core Empty web [C#] Web/Empty  
ASP.NET Core Web App mvc [C#], F# Web/MVC  
ASP.NET Core Web API webapi [C#] Web/WebAPI  
Solution File sln Solution

#get dependancy
dotnet restore

#run the app
dotnet run

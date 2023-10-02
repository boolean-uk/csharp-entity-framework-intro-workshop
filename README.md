# C# Entity Framework Introduction Workshop

## created project with these commands

mkdir csharp-entity-framework-intro-workshop  

dotnet new sln --name workshop  

dotnet new nunit --name workshop.tests  

dotnet new webapi --name workshop.wwwapi  


## Adding to GIT  

-ensure that you have run the 'dotnet new gitignore' command in the root of the folder (where the .sln resides)  
-ensure that you have added the following to the gitignore:  
```
*/**/bin/Debug   
*/**/bin/Release   
*/**/obj/Debug   
*/**/obj/Release   
```
-ensure both 'appsettings.json' & 'appsettings.Development.json' are 'Ignore and untracked.'


## Entity Framework Dependencies   

Install these using the nuget package manager.  Ensure you have the api set as the default project!  

```
install-packages microsoft.entityframeworkcore.design  

install-packages microsoft.entityframeworkcore.design  

install-packages microsoft.entityframeworkcore.design  

install-packages microsoft.entityframeworkcore.design  

install-packages npgsql.entityframeworkcore.postgresql  
```

## 



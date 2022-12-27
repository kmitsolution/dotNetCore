# First Asp.Net core project
1. Open Visual Studio.
2. Select Asp.NET Core Empty Project ( I am creating Project with name EmptyAspNetCoreProj)
3. You can view the profiles and IIS express setting under launchSettings.json file
```json
{
  "iisSettings": {
    "windowsAuthentication": false,
    "anonymousAuthentication": true,
    "iisExpress": {
      "applicationUrl": "http://localhost:41970",
      "sslPort": 0
    }
  },
  "profiles": {
    "EmptyAspNetCoreProj": {
      "commandName": "Project",
      "dotnetRunMessages": true,
      "launchBrowser": true,
      "applicationUrl": "http://localhost:5190",
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    },
    "IIS Express": {
      "commandName": "IISExpress",
      "launchBrowser": true,
      "environmentVariables": {
        "ASPNETCORE_ENVIRONMENT": "Development"
      }
    }
  }
}
```
4. Now when you execute the code then it can be executed using <b>IIS Express</b> or <b>EmptyAspNetCoreProj</b> profile.
5. You can see the project output in the browser.

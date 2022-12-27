# Asp.Net Core InProcess Hosting
Open the Program.cs file and you will find the below code (or similar to below code if you are using < .Net 6 version you will find main() )
```c#
var builder = WebApplication.CreateBuilder(args); 
var app = builder.Build();

app.MapGet("/", () => "Hello World!");

app.Run();
```
### WebApplication
   The WebApplication class is used to configure the HTTP pipeline and routes.
#### CreateBuilder()
    It sets up the webhost with default properties of webapplication.It also perform below tasks.
     1. Setting up the web server.
     2. Loading the hosts and application configuration from various configuration sources
     3. Configuring logging
     4. It calls 
    
    

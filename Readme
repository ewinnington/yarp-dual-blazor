# YARP : Reverse proxy setup for two sites hosted locally with different names

To get two different blazor sites hosted on the same machine on different ports to respond to different DNS names, I use YARP, Microsoft's **Y**et **A**nother **R**everse **P**roxy. 

Ensure your *hosts* file has three entries: 
```
127.0.0.1 dev.local 
127.0.0.1 red.local 
127.0.0.1 blue.local 
```

Then launch ```dotnet``` run on site1 and site2. When they are running, you can launch ```reverse-proxy-yarp```. It is configured by the json file ```appsettings.json``` which gives the redirection Routes. 

When they are all running, try to access: 

- http://dev.local  => site1
- http://red.local  => site2
- http://blue.local => site2


# “ASP.NET Core Web App” to run on Microsoft machine

Basic ASP.NET web application to run on a Microsoft machine.

## whoami?

This guide shows how to deploy an ASP.NET web application on your Microsoft machine,

using Internet Information Services (IIS) Manager.

```bash
>whoami
"A guide + basic project files"
```
## Requirements:

A Microsoft machine server.

## Installation and Configuration


- clone the files on this repo or create your own ASP.NET project.
- create and configure IIS -> 
* At the server manager click on : Add feature and roles.
* After that Choose Web Server (IIS) at the Server Roles section.
* Add the ```.NET framework``` features at the ``` Features``` section.

- Add your web application to the IIS Manager ->
- 
Open IIS manager ->

Open your local connection. ->

Right click on Sites ->

Select "Add website" ->

  Fill the website form.
  -Site name - Your website name.
  -Physical path - The path to your website folder.
  -port - The port where the app will run - for us it was 5100

- Browse to the application
From your local Microsoft machine Browse to http://localhost:5100/

DONE

## Dependencies

Microsoft machine - This guide deployed with Windows Server 2019.

This project was written using Microsoft Visual Studio 2019 and C# ASP.NET 5.0 core, other versions mat not work.

Note .NET versions must be the same on the server and at your project.
